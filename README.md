# UE Feature Workspace

My working folder for Inception Technologies feature implementations. **Start admin sessions
here.** Task sessions start in the client project folder instead; see "Task workflow" in
`CLAUDE.md`.

`CLAUDE.md` links to `../Inception-UE-Workflow/CLAUDE.md`, which holds the rules. `AGENTS.md`
links to `CLAUDE.md`. The machine profile (paths, engine, identity) is
`../Inception-UE-Workflow/.local/workspace.json`. This repo tracks only this README, the ledger
and its git files. Its remote is the private GitHub repo
`https://github.com/Axrr44/ue-feature-workspace`. I push; agents never do.

| Path | Holds | Tracked |
|---|---|---|
| `IMPLEMENTATION-INDEX.md` | one row per implementation | yes |
| `private/` | receipts, notes and evidence. Never delivered | no |
| `scratch/` | throwaway work | no |
| `F:\InceptionUE\delivery` | client projects and repos, each kept as delivered (`delivery_root`) | no, outside this repo |

Client projects live on F: (NVMe) rather than here on E: (HDD), so builds and shader compiles
run off an SSD. Each one keeps its own git repo or Perforce workspace. Commit there only with my
approval, and never push. Ignoring `private/` keeps `git add -A` from staging it, but it cannot
stop a file being copied into a deliverable, so read every deliverable before it leaves.

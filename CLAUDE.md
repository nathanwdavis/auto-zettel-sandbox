# Working in this repository

## Standing instruction from the owner (2026-10-08)

When the owner asks for research, a source, or a paper outline to be added to this
zettel, the work is not done until it is on `main`. Open the pull request yourself,
enable auto-merge (squash), watch the `gates` check and any review, fix whatever fails,
and stay with the PR until it merges. Do not stop at pushing a branch, and do not wait to
be asked for the PR. That is what the "auto" in auto-zettel means, and it overrides any
default against opening pull requests unasked.

Do the work itself through the zettel-bootstrap skills (`zettel-ask` for a question,
`zettel-ingest` for a source the owner supplies, `zettel-query` to see what the base
already holds), and run `remote_cycle.sh gates` before every push. If the session is
assigned a branch, work and push there; otherwise use the run branch that
`session_cycle.sh` creates.

# Eval harness

Built on week 1, day 5, then reused by every level. Keep it small and boring.

## What it must do
- Load a dataset from `datasets/` (one JSONL file per task: `input`, `expected`, optional `tags`)
- Run a target (a prompt, a RAG pipeline, an agent) over every case
- Score each case with one or more scorers (exact match, a metric, an LLM judge)
- Save the run to `results/` with a timestamp, the git commit, the model and the prompt version
- Print a summary per tag, and a diff against the previous run

## Rules
- Never change a dataset and the system in the same run.
- Record cost and latency for every run, not only quality.
- Trust a judge only after you've measured its agreement with your own labels.

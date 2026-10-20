# AI Engineering: a 10-week build log

Working through the 16 levels of the [AI Engineer Roadmap 2026](https://ai-engineer-roadmap-2026.vercel.app/) at 40 hours a week.
Each level ends with four checks: a scenario quiz at 80% or more, an explanation from memory,
a deliberate break-and-diagnose exercise, and before/after numbers recorded here.

## Headline results
<!-- Fill in as levels pass. One line each, with the number first. -->
- _Nothing yet. First numbers land in week 1._

## Progress
Status: ⬜ Not started · 🟡 In progress · ✅ Passed

| Level | Weeks | Status | Key result | Notes |
|---|---|---|---|---|
| L0 Software Engineering Fundamentals | 1 | ⬜ Not started | — | [notes](levels/L00-software-fundamentals/notes.md) |
| L1 LLM 101 | 1 | ⬜ Not started | — | [notes](levels/L01-llm-101/notes.md) |
| L2 Working with LLM APIs | 1–2 | ⬜ Not started | — | [notes](levels/L02-llm-apis/notes.md) |
| L3 Prompt Engineering | 2 | ⬜ Not started | — | [notes](levels/L03-prompt-engineering/notes.md) |
| L4 RAG | 3–4 | ⬜ Not started | — | [notes](levels/L04-rag/notes.md) |
| L5 AI Agents | 5 | ⬜ Not started | — | [notes](levels/L05-agents/notes.md) |
| L6 Context Engineering | 6 | ⬜ Not started | — | [notes](levels/L06-context-engineering/notes.md) |
| L7 LLM Evaluations | 2–4 | ⬜ Not started | — | [notes](levels/L07-evals/notes.md) |
| L8 AI Security | 6 | ⬜ Not started | — | [notes](levels/L08-security/notes.md) |
| L9 AI System Design | 7 | ⬜ Not started | — | [notes](levels/L09-system-design/notes.md) |
| L10 LLMOps | 7–8 | ⬜ Not started | — | [notes](levels/L10-llmops/notes.md) |
| L11 Managed AI Platforms | 8 | ⬜ Not started | — | [notes](levels/L11-managed-platforms/notes.md) |
| L12 Multimodal 101 | 9 | ⬜ Not started | — | [notes](levels/L12-multimodal/notes.md) |
| L13 Fine-Tuning | 9 | ⬜ Not started | — | [notes](levels/L13-fine-tuning/notes.md) |
| L14 Projects | 10 | ⬜ Not started | — | [notes](levels/L14-projects/notes.md) |
| L15 GenAI Interview Prep | 1–10 | ⬜ Not started | — | [notes](levels/L15-interview-prep/notes.md) |

## Layout
| Folder | What's in it |
|---|---|
| [`project/`](project/) | The main project. It grows level by level from week 2 to week 10. |
| [`evals/`](evals/) | One eval harness reused by every level: datasets, runner, saved results. |
| [`from-scratch/`](from-scratch/) | The "build it yourself" exercises, done before using any framework. |
| [`levels/`](levels/) | One folder per level: notes, exit checks, break logs, numbers. |
| [`writeups/`](writeups/) | Drafts of the five public write-ups. |
| [`DECISIONS.md`](DECISIONS.md) | Every non-obvious decision, with options, evidence and when to revisit. |

## Setup
```bash
python -m venv .venv
cp .env.example .env   # then add your API keys; .env is git-ignored
```

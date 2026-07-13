# 365 Days of AI Mastery — how it's delivered & how to use the labs

**365 Days of AI Mastery** is a year-long path from "what is a computer,
really?" to designing, building, evaluating, securing, and deploying real AI
systems. It is delivered as **nine standalone courses** (Course01–Course09)
that can be taken one at a time and that together cover all 365 days. Each day
is one focused lesson plus one hands-on lab — about an hour a day.

This repository holds the **hands-on labs**. The daily lessons are published on
the course blog; every lesson links to its matching lab here.

---

## How the course is delivered

The same daily material is offered two ways, so you can learn whichever way
suits you:

- **A daily blog series.** One lesson is published per day — read the article,
  then do that day's lab. Follow along at the pace of one post a day, or catch
  up on the archive.
- **A drip-scheduled online course.** The same lessons are also packaged as a
  self-paced course that unlocks **one lesson per day** from the day you enrol,
  so a course of *N* days takes *N* days. The nine courses are also offered as
  a single **365 Days of AI Mastery** bundle for the complete path.

Whichever you choose, every lesson includes clear diagrams, a worked example, a
short quiz, and a practical exercise that points to the lab in this repository.

---

## The nine courses

| Course | Focus |
| ------ | ----- |
| Course01 · Computing Foundations | how computers, the terminal, networks, git, and tooling work |
| Course02 · Programming with Python | Python from zero to tested, packaged, database-backed apps |
| Course03 · Math, Statistics, and Data | linear algebra, calculus, probability, pandas, visualization |
| Course04 · Machine Learning | classical ML, evaluation discipline, features, deployment |
| Course05 · Deep Learning | neural nets from scratch, PyTorch, CNNs, transformers |
| Course06 · LLMs and Generative AI | prompting, LLM APIs, embeddings, RAG, fine-tuning, multimodal |
| Course07 · AI Engineering | agents, MCP, coding agents, evals, full-stack AI apps |
| Course08 · Deployment, MLOps, Security | Docker, cloud, monitoring, AI security and governance |
| Course09 · Capstone | a complete AI product, shipped and defended |

Each course is split into **subsections** (a few days each) with a clear
running theme, so progress always feels connected.

---

## How to use a lab

Every lab in this repository is self-contained. Clone the repo once, then open
the day you're on:

```bash
git clone <this-repository>.git
cd <repo>/labs/sections/<course>/day-<nnn>-<slug>
```

Then follow that day's `README.md`. Every lab includes:

- `starter/` — the files you work in, with clearly numbered exercises
- `examples/` — a completed reference implementation
- `tests/` — automated checks (run them; they exit `0` when you're done)
- `expected-output/` — genuinely captured runs to compare against
- `requirements/`, `troubleshooting.md`, `security.md`

Labs use free and open-source tools wherever possible; any exception (for
example an API key) is declared in the lab's `metadata.yml` and README, always
with a free alternative.

---

## The daily rhythm

1. Read the day's lesson (blog post or course lesson).
2. Open that day's lab folder here and read its `README.md`.
3. Work through `starter/`, comparing against `examples/` when stuck.
4. Run the tests until they pass and match `expected-output/`.
5. Move to the next day. Do one a day and the year takes care of itself.

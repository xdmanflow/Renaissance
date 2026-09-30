# Renaissance Project: The Way to the Peak in CS & Maths

> A public, one-year learning plan (Sept. 2026 → Sept. 2027) covering mathematics for machine learning, computer-science fundamentals, data engineering, machine learning, cloud and generative AI, with every weekend's learning applied to AeroLisa, a Skywise-inspired aviation data platform built only on public data. This is an independent learning project, not affiliated with, endorsed by, or connected to Airbus, Skywise or Palantir.

## Two repositories, two roles

| Repository | Role |
|---|---|
| **Renaissance Project** | *Learning*: plan, weekly exercises, notes, checkpoints, progress |
| **[AeroLisa Project](https://github.com/YOUR-USERNAME/aerolisa)** | *Application*: the platform where everything learned here is built and shipped |

## How it works

- **Saturday = Mathematics · Sunday = Computer Science.** Full calendar in [PLAN.md](PLAN.md).
- Each weekend has its own folder in [`weeks/`](weeks): topics, checklist, `math/` and `cs/` work, gaps and notes.
- Four **checkpoints** 🔍 test everything from memory. Scores are logged honestly in [checkpoints/](checkpoints/README.md).
- Exercises in `cs/` come with pytest tests; [CI](.github/workflows/ci.yml) runs them on every push.

## My rules

1. **One pushed commit every weekend.** The contribution graph is the streak.
2. **Minimum floor on bad weekends:** one hour and one commit. Never a zero week.
3. **First attempt without AI.** AI reviews my work; it never writes the first version.
4. **15-minute review every Sunday evening** with [the template](WEEKLY_REVIEW_TEMPLATE.md).
5. **Cut scope, not dates.**
6. **Protect rest.** At least one free half-day every weekend. Rest is part of the plan.

## Phases

| Phase | Period | Mathematics | Computer science | Aerolisa |
|---|---|---|---|---|
| 1 · Foundations | Sept.–Nov. 2026 | Logic, proofs, combinatorics, graphs, probability | Python, algorithms, data structures, Git, testing | CLI |
| 2 · Data | Nov. 2026–Jan. 2027 | Statistics, reliability, linear algebra | SQL, pandas, ETL, Airflow, data architecture | **v0.1** |
| 3 · Machine learning | Jan.–Mar. 2027 | Calculus, Bayes, optimization, inference, PCA | ML models, metrics, anomaly detection | **v0.2** |
| 4 · TOEIC & industrialization | Mar. 2027 | Neural-network math, TOEIC practice | PyTorch, Docker | — |
| 5 · Cloud & GenAI | Apr.–May 2027 | Norms, similarity, information theory, attention | GCP, CI/CD, FastAPI, LLMs, RAG, agents | **v0.3**, **v1.0** |
| 6 · Interviews | May–Jun. 2027 | Interview questions | Portfolio, mock interviews, pitches | Demo |

## Repository structure

```text
renaissance-project/
├── .github/
│   ├── workflows/ci.yml         # runs exercise tests on every push
│   └── ISSUE_TEMPLATE/          # weekly review, gap to review
├── checkpoints/README.md        # score log
├── weeks/
│   └── NN_topic/
│       ├── README.md            # topics, checklist, gaps, notes
│       ├── math/                # handwritten scans, notes, solutions
│       └── cs/                  # code + tests
├── PLAN.md                      # full calendar
├── PROGRESS.md                  # weekends, releases, career milestones
├── RESOURCES.md
├── WEEKLY_REVIEW_TEMPLATE.md
└── requirements.txt
```

## Getting started

```bash
git clone https://github.com/YOUR-USERNAME/renaissance-project.git
cd renaissance-project
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
pytest -q
```

## Progress

[PROGRESS.md](PROGRESS.md) · [Checkpoints](checkpoints/README.md)

## Author

**YOUR NAME**, engineering student in computer science (AI & data science), CESI.
[LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN) · [Portfolio](https://YOUR-USERNAME.github.io)

## License

Code under the [MIT License](LICENSE). Notes may be reused with attribution.

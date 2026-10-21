# Ruhan Sahasi

Computer science at Penn, B.S. plus an accelerated M.S. in Machine Learning and Robotics. I build AI products and the backends they run on. Previously engineering intern at Marlo (a16z SR004), summer 2026, and software engineering intern at CoreThink AI, summer 2025.

## Projects

- **[Mockingbird](https://github.com/ruhan-sahasi/mockingbird)**: a voice mock interviewer that grades each behavioral answer, and every score must point to words you actually said. Code runs the question order and the clock while Claude only writes the lines, and 613 Python tests and 220 web tests pass in CI. Python, FastAPI, WebSockets, React, Postgres, AWS Fargate, Claude API, Vapi.
- **[techval](https://github.com/ruhan-sahasi/techval)**: a command line tool that values US tech companies from free public data (SEC filings, Nasdaq quotes and the Treasury yield curve). It scores its prediction models against simple baselines and reports the losses too (two of six scores beat the baseline, three tie, one loses), and 2,255 tests pass in CI. Python, NumPy (neural networks written by hand), pandas, scikit-learn, Typer.
- **Vestige** (co-founder and CEO): an AI representative for each department of a company that answers questions from interviews with its key people and the systems it already runs. The first use is saving what a retiring maintenance expert knows, and every knowledge card carries a quote that code checks against the interview transcript. TypeScript, Node.js, Hono, React, Supabase, Claude API, Vapi.
- **[worldcup-oracle](https://github.com/ruhan-sahasi/worldcup-oracle)**: live World Cup forecasts in Rust, where a goal model and Elo ratings update each match as goals and red cards arrive, and a parallel Monte Carlo over the 2026 bracket gives title odds. The workspace has 14 crates and 425 passing tests, and CI fails the build if any forecaster scores worse than a committed baseline. Rust, tokio, axum, rayon, arc-swap, WebSockets, Docker.
- **[UIUC Bustle](https://github.com/ruhan-sahasi/UIUC-bustle)**: a campus transit app for UIUC students that ranks walk and bus options by ETA from live MTD bus departures and GTFS ride times, with an optional Claude rerank that falls back to the ETA order. CI runs 162 backend tests against Postgres and 280 mobile tests plus a TypeScript type check, all passing on main. React Native (Expo), TypeScript, FastAPI, PostgreSQL, Claude API.

## Stack

Python, TypeScript, Rust, FastAPI, Node.js, React, React Native, Postgres (Supabase), NumPy, pandas, scikit-learn, Terraform, AWS, Docker, Claude API, and Vapi.

## Contact

[LinkedIn](https://www.linkedin.com/in/ruhan-sahasi-69b677239/)

# Production ML systems, not just models

I'm Loukik Naik, a software and ML engineer building agent orchestration, computer vision pipelines, ML infrastructure, and distributed systems.

Models are one piece. The hard part is orchestration, reliability, evaluation, multi-tenancy, and infrastructure that teams ship on.

## What I work on

**Agent-based AI systems** -- Built and operated the backend for an agent-based legal document analysis platform at [Eudia](https://www.eudia.com). Temporal orchestration, multi-tenant Kubernetes, schema-based inference, structured logging, and production rollouts across live customers.

**Computer vision infrastructure** -- Real-time segmentation APIs (SAM/MobileSAM), cron-triggered retraining pipelines on Vertex AI, OCR evaluation frameworks, and end-to-end integration testing for model generation at [Plainsight Technologies](https://www.plainsight.ai).

**Distributed systems** -- Surfstore (Raft consensus, gRPC, horizontally scalable block storage in Go), HTTP servers, shell implementations, and systems-level work in C++ and Go.

## Selected projects

| Section | Project | Description |
|---|---|---|
| **AI agents** | [Verdict](https://github.com/LoukikNaik/verdict) ([Live](https://verdict.loukik.dev/)) | What if you could run a focus group in 90 seconds? Claude personas react to your product, 1–5 purchase intent rolls in, web-search adds live market context, and an exec brief drops at the end. [Browse real runs](https://verdict.loukik.dev/) — see what 200 to 2,000 random buyers think about your product before you ship. Inspired by [LLMs Reproduce Purchase Intent](https://arxiv.org/abs/2510.08338) (PyMC × Colgate, 2025). |
| | [DraftIn](https://github.com/LoukikNaik/DraftIn) ([Live](https://draftin.loukik.dev/)) | Keyboard-driven LinkedIn reach-out drafter. Alt+L on any LinkedIn page captures the viewport and drops a personalized message on the clipboard. Routes through my ChatGPT subscription via a local browser-driven CLI, so no paid API key. |
| | [PodClipper](https://github.com/LoukikNaik/PodClipper) ([Live](https://podclipper.loukik.dev/)) | Local-first pipeline for turning long-form videos into vertical reels with transcription, AI clip selection, smart cropping, and subtitles. |
| | [reelforge](https://github.com/LoukikNaik/reelforge) | Multi-agent AI video editor that turns long-form videos into viral short-form reels. |
| | [Synapse](https://github.com/LoukikNaik/Synapse) | Spaced repetition for decision-making. Turns any book, video, or topic into scenario-based flashcards that test judgment. |
| | [ColdBound](https://github.com/LoukikNaik/ColdBound) | AI-powered outreach platform: find people, research them, draft personalized messages from a single prompt. |
| **ML** | [F1-Prediction-Engine](https://github.com/LoukikNaik/F1-Prediction-Engine) | Ensemble models, Monte Carlo simulations, and live race tracking for F1 predictions. |
| **Systems** | [Surfstore](https://github.com/LoukikNaik/Surfstore-Distributed-File-Storage-System) | Distributed file storage with Raft consensus, gRPC, and horizontal scaling in Go. |
| **Full-stack** | [IGL · Funny or Not](https://github.com/LoukikNaik/igl-funny-or-not) ([Live](https://igl.loukik.dev)) | A "who's funnier?" voting game for the panel of *India's Got Latent*, a hit Indian comedy show where comedians roast and judge performers. Face two panelists off, pick the funnier one, and a live Elo leaderboard forms from the crowd. Zero-dependency frontend on GitHub Pages, Cloudflare Worker + D1 backend, and Turnstile + per-IP rate-limiting to keep the rankings honest. Live traction: ![votes](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Figlapi.loukik.dev%2Fapi%2Fleaderboard&query=%24.totals.faceoffVotes&label=votes&color=ffd21e&cacheSeconds=300) ![voters](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Figlapi.loukik.dev%2Fapi%2Fleaderboard&query=%24.totals.voters&label=voters&color=ff5470&cacheSeconds=300) |

## Engineering taste

- Agent orchestration should be explicit DAGs with retries and idempotency, not free-form chains that fail silently.
- Model serving without evaluation frameworks, retraining pipelines, and integration tests is a demo, not a product.
- Multi-tenancy, observability, and schema migrations are product architecture, not afterthoughts.
- If your ML system can't explain what it did at each step, it's not ready for production.
- Systems work (distributed storage, consensus, networking) keeps ML engineering grounded.

## Technical surface

**Languages:** Python, Go, C++, TypeScript, JavaScript, Swift, SQL, Bash

**ML & AI:** PyTorch, TensorFlow, LangGraph, LangChain, Scikit-Learn, Pandas, SAM/MobileSAM, NLP, LLMs

**Infrastructure:** Kubernetes, Docker, Temporal, Kubeflow, Terraform, ArgoCD, Helm, GKE, Vertex AI, CI/CD

**Observability:** Grafana, Prometheus, Signoz, structured logging, workflow tracing

**Systems:** gRPC, Raft consensus, FastAPI, PostgreSQL, Alembic, distributed systems

## Links

[Portfolio](https://portfolio.loukik.dev) -- [LinkedIn](https://www.linkedin.com/in/loukiknaik/) -- [Email](mailto:loukiknaik@gmail.com)

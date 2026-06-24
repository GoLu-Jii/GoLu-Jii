<div align="center">
  <img src="terminal-banner.svg" width="100%" alt="terminal banner" />
</div>

<br>

## `~/architecture-stack`

| Layer | Production Technologies |
| :--- | :--- |
| **Core Logic** | ![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB&labelColor=0D1117) ![C++](https://img.shields.io/badge/C++-161B22?style=flat-square&logo=cplusplus&logoColor=00599C&labelColor=0D1117) ![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688&labelColor=0D1117) |
| **AI & Vector** | ![Groq](https://img.shields.io/badge/Groq-161B22?style=flat-square&logo=groq&logoColor=F55036&labelColor=0D1117) ![Qdrant](https://img.shields.io/badge/Qdrant-161B22?style=flat-square&logo=qdrant&logoColor=DC244C&labelColor=0D1117) ![ChromaDB](https://img.shields.io/badge/ChromaDB-161B22?style=flat-square&logo=databricks&logoColor=FF6F00&labelColor=0D1117) |
| **Data & ORM** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=316192&labelColor=0D1117) ![SQL](https://img.shields.io/badge/SQL-161B22?style=flat-square&logo=postgresql&logoColor=4479A1&labelColor=0D1117) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-161B22?style=flat-square&logo=python&logoColor=D71F00&labelColor=0D1117) |
| **Client UI** | ![Next.js](https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=nextdotjs&logoColor=white&labelColor=0D1117) ![React](https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=61DAFB&labelColor=0D1117) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-161B22?style=flat-square&logo=tailwindcss&logoColor=06B6D4&labelColor=0D1117) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED&labelColor=0D1117) ![Git](https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=F05032&labelColor=0D1117) ![Vercel](https://img.shields.io/badge/Vercel-161B22?style=flat-square&logo=vercel&logoColor=white&labelColor=0D1117) |

<br>

## `~/sprints --active`

```zsh
[DATA]    Mastering classical relational normalization: PostgreSQL + raw SQL join mechanics
[WORK]    AI Engineering Intern @ GridSphere (Interactive Client-Side Simulation Ops)
```

<br>

## `~/shipped --production`

### `[01]` [CODE Sherpa](https://code-sherpa-mu.vercel.app/) `:: Codebase Ground-Truth Q&A Engine`

> Engineered to eliminate LLM code hallucination by pairing **deterministic Python AST analysis** with Groq LLM narration. 

* **Architecture:** Asynchronous FastAPI ingestion backend paired with hybrid chunking (file-level + function-level) and ChromaDB semantic fallback.
* **The Refactor:** Re-architected blocking endpoints to `FastAPI BackgroundTasks` with job-polling, resolving ChromaDB lifespan init deadlocks and runtime crashes.
* **STDOUT:** `[` **[ GitHub ](https://github.com/GoLu-Jii/CODE_Sherpa)** `]` `|` `[` **[ Live Demo ](https://youtu.be/iz0Rq9VYDA4)** `]`

<br>

### `[02]` [PDF-RAG-APP](https://huggingface.co/spaces/Joshijii/PDF-RAG-APP) `:: Citation-Enforced Document Intelligence`

> Production-grade PDF parsing system engineered to return verifiable chunk-level source tags and score-threshold filtering per API call.

* **Pipeline:** LangChain chunking → SentenceTransformer embeddings → Qdrant Cloud Vector Search → Groq LLaMA-3.3-70B.
* **DevOps:** Fully containerized backend via Docker, deployed natively on Hugging Face Spaces serving a static frontend via FastAPI.
* **STDOUT:** `[` **[ Space Demo ](https://huggingface.co/spaces/Joshijii/PDF-RAG-APP)** `]` `|` `[` **[ GitHub ](https://github.com/GoLu-Jii/PDF-RAG-APP)** `]`

<br>

### `[03]` [GoPro-Deblur-Net] `:: Deep Learning Image Restoration` *(Active Sprint)*

> Custom Computer Vision architecture utilizing the GoPro Dataset to restore motion-blurred high-speed captures via deep neural feature extraction.

* **Objective:** Building raw deep learning model weights to run inference without relying on external third-party Vision APIs.
* **Status:** `[ Architecture & feature extraction branch active ]`

<br>

## `~/connect`

```zsh
❯ cat ~/.contacts.json

{
  "name": "Gaurav Joshi",
  "status": "Available for USD Remote / High-Impact AI Engineering Internships",
  "email": "gauravj121232@gmail.com",
  "github": "[https://github.com/GoLu-Jii](https://github.com/GoLu-Jii)",
  "linkedin": "[https://linkedin.com/in/gaurav-joshi](https://linkedin.com/in/gaurav-joshi)",
  "x_twitter": "[https://x.com/](https://x.com/)[https://x.com/GauravJ82092430]",
  "location": "Bhimtal / Dehradun, India (Willing to relocate globally)"
}
```

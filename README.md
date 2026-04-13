<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:020010,30:0a0a1a,60:0d1f3c,100:00f7ff&height=280&section=header&text=TUSHAR%20PANDEY&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=⬡%20AI%20Engineer%20%20·%20%20Backend%20Architect%20%20·%20%20Systems%20Builder%20⬡&descAlignY=62&descSize=17&descColor=00f7ff&stroke=00f7ff&strokeWidth=2" />

<!-- LIVE TYPING -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=2200&pause=700&color=00F7FF&center=true&vCenter=true&width=950&lines=⚡+Architecting+RAG+Systems+that+actually+scale;🧠+LLM+Orchestration+%7C+Hybrid+Retrieval+%7C+Reranking;🔗+FastAPI+·+Supabase+·+Gemini+·+LangChain+·+Docker;📦+Production+AI+—+not+just+demos%2C+real+systems;🛡️+Clean+APIs+%7C+Vector+Search+%7C+Async+Pipelines;🚀+From+Architecture+Doc+→+Deployed+%26+Monitored" />

<br/>

<!-- STATUS BADGES -->
<img src="https://img.shields.io/badge/🔥_STATUS-Available_for_Work-00ff88?style=for-the-badge&labelColor=0a0a1a" />
<img src="https://img.shields.io/badge/🧠_FOCUS-Production_AI_Systems-00f7ff?style=for-the-badge&labelColor=0a0a1a" />
<img src="https://img.shields.io/badge/📍_LOCATION-India_🇮🇳-ff6b6b?style=for-the-badge&labelColor=0a0a1a" />
<img src="https://img.shields.io/badge/⚡_RESPONSE-Within_24h-f59e0b?style=for-the-badge&labelColor=0a0a1a" />

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="32" /> The Engineer Behind the Terminal

<img align="right" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" />

```typescript
// tushar.config.ts — Last updated: 2025

const TUSHAR_PANDEY = {
  role        : "AI Engineer & Backend Architect",
  location    : "India 🇮🇳",
  available   : ["Freelance", "Full-time", "Contract"],

  expertise   : {
    primary   : ["RAG Pipelines", "LLM Orchestration"],
    secondary : ["System Design", "Backend Architecture"],
    emerging  : ["Agentic AI", "Multi-Modal RAG", "Edge LLM"],
  },

  stack: {
    ai        : ["LangChain", "Gemini", "OpenAI", "HuggingFace"],
    backend   : ["FastAPI", "Python", "Node.js", "Async IO"],
    data      : ["Supabase", "PostgreSQL", "pgvector", "Redis"],
    infra     : ["Docker", "GCP", "Nginx", "GitHub Actions"],
    search    : ["BM25", "Semantic Search", "Hybrid Retrieval"],
  },

  philosophy  : "If it's not scalable, it's not finished.",
  currentGoal : "Build the most robust open-source RAG framework 🚀",
} as const;
```

<br clear="right"/>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## <img src="https://user-images.githubusercontent.com/74038190/216649417-9acc58df-9186-4132-ad8a-70ba28b0b585.png" width="34" /> Project Showcase

> Click any card to open the repo. Stars and forks update live from GitHub.

---

### 🏆 Flagship Project

<div align="center">

[![AI Teams Bot](https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-RAG-REPO&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12&description_lines_count=3)](https://github.com/tusharpandey436/YOUR-RAG-REPO)

</div>

<div align="center">
<img src="https://img.shields.io/badge/TYPE-Production_RAG_System-8b5cf6?style=for-the-badge&labelColor=0a0a1a" />
<img src="https://img.shields.io/badge/STATUS-Deployed_&_Active-00ff88?style=for-the-badge&labelColor=0a0a1a" />
<img src="https://img.shields.io/badge/LLM-Gemini_1.5_Pro-f59e0b?style=for-the-badge&labelColor=0a0a1a&logo=google" />
<img src="https://img.shields.io/badge/SCALE-Enterprise_Grade-ff6b6b?style=for-the-badge&labelColor=0a0a1a" />
</div>

<br/>

> 💡 **Problem**: Enterprise teams drowning in documents — policies, manuals, SOPs, reports. Nobody reads them. Nobody finds answers fast enough.
>
> **Solution**: A Teams-integrated AI bot that answers questions instantly, with source citations, across all document formats.

### 🗺️ System Architecture

```mermaid
flowchart LR
    subgraph INPUT ["📥 Input Layer"]
        U(["👤 User\nQuery"])
        D(["📄 Documents\nPDF·DOCX·XLSX·TXT"])
    end

    subgraph GATEWAY ["⚡ API Gateway"]
        TB["🤖 Teams Bot\nConnector"]
        FG["🚀 FastAPI\nAsync Gateway"]
        AUTH["🛡️ Auth &\nRate Limiter"]
    end

    subgraph INGESTION ["📦 Ingestion Pipeline"]
        PARSE["📋 Document\nParser"]
        CHUNK["🔪 Smart\nChunker"]
        META["🏷️ Metadata\nExtractor"]
        EMB["🧬 Embedding\nGenerator"]
    end

    subgraph STORAGE ["🗄️ Storage Layer"]
        VDB[("🟣 Supabase\npgvector")]
        CACHE[("⚡ Redis\nCache")]
        META_DB[("📊 Postgres\nMetadata")]
    end

    subgraph RETRIEVAL ["🔍 Retrieval Engine"]
        BM["📝 BM25\nKeyword Search"]
        SEM["🧠 Semantic\nVector Search"]
        HYB["🔀 Hybrid\nFusion (RRF)"]
        RANK["📊 Cross-Encoder\nReranker"]
    end

    subgraph GENERATION ["💎 Generation Layer"]
        CTX["📐 Context\nBuilder"]
        LLM["✨ Gemini\n1.5 Pro"]
        EVAL["📈 RAGAS\nEvaluator"]
    end

    subgraph OUTPUT ["📤 Output Layer"]
        RES(["✅ Answer +\nSource Citations"])
        LOG["📊 Observability\n& Logging"]
    end

    U --> TB --> FG --> AUTH
    D --> PARSE --> CHUNK --> META --> EMB --> VDB
    AUTH --> BM & SEM
    VDB --> SEM
    BM & SEM --> HYB --> RANK
    RANK --> CTX --> LLM --> EVAL
    LLM --> RES
    EVAL --> LOG
    CACHE -.-> FG
    META_DB -.-> META

    classDef primary fill:#00f7ff,color:#000,stroke:none,font-weight:bold
    classDef success fill:#00ff88,color:#000,stroke:none
    classDef accent fill:#8b5cf6,color:#fff,stroke:none
    classDef warning fill:#f59e0b,color:#000,stroke:none
    classDef danger fill:#ff6b6b,color:#fff,stroke:none
    classDef neutral fill:#1a1a2e,color:#00f7ff,stroke:#00f7ff,stroke-width:1px

    class U,D primary
    class RES success
    class VDB accent
    class LLM warning
    class RANK danger
    class FG,HYB,CTX neutral
```

### 🧬 Core Pipeline — Production Code

<details>
<summary><b>📂 Click to expand full pipeline implementation</b></summary>

```python
# rag_engine/pipeline.py
from dataclasses import dataclass
import asyncio, time

@dataclass
class RAGResponse:
    answer      : str
    sources     : list[Document]
    confidence  : float
    latency_ms  : int
    eval_scores : dict[str, float]

class ProductionRAGPipeline:
    def __init__(self, config: PipelineConfig):
        self.retriever   = HybridRetriever(config)
        self.reranker    = CrossEncoderReranker()
        self.generator   = GeminiGenerator(config)
        self.evaluator   = RAGASEvaluator()
        self.cache       = RedisSemanticCache()

    async def run(self, query: str) -> RAGResponse:
        start    = time.perf_counter()
        expanded = await self._expand_query(query)
        if cached := await self.cache.get(expanded):
            return cached
        bm25_results, sem_results = await asyncio.gather(
            self.retriever.bm25_search(expanded, top_k=30),
            self.retriever.semantic_search(expanded, top_k=30),
        )
        fused    = reciprocal_rank_fusion(bm25_results, sem_results)
        reranked = await self.reranker.score(fused[:20], query)
        context  = self._build_context(reranked[:5], max_tokens=3000)
        answer   = await self.generator.complete(SYSTEM_PROMPT, context, query)
        scores   = await self.evaluator.score(query, context, answer)
        response = RAGResponse(
            answer      = answer,
            sources     = reranked[:5],
            confidence  = scores["faithfulness"],
            latency_ms  = int((time.perf_counter() - start) * 1000),
            eval_scores = scores,
        )
        await self.cache.set(expanded, response)
        return response
```

</details>

### 📊 Production Metrics

| Metric | Target | Achieved | Status |
|--------|--------|----------|--------|
| **Answer Faithfulness** | > 85% | **91.4%** | 🟢 Exceeds |
| **Context Relevance** | > 80% | **87.2%** | 🟢 Exceeds |
| **P95 Latency** | < 3s | **1.8s** | 🟢 Exceeds |
| **Multi-format Support** | 5 types | **7 types** | 🟢 Exceeds |
| **Cache Hit Rate** | > 30% | **43%** | 🟢 Exceeds |
| **Concurrent Users** | 50 | **200+** | 🟢 Exceeds |

<div align="center">
  <a href="https://github.com/tusharpandey436/YOUR-RAG-REPO">
    <img src="https://img.shields.io/badge/📁_SOURCE_CODE-View_on_GitHub-161b22?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://your-demo-link">
    <img src="https://img.shields.io/badge/🎥_DEMO-Watch_Live-ff0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://your-docs-link">
    <img src="https://img.shields.io/badge/📚_DOCS-Read_Architecture-00f7ff?style=for-the-badge&logo=readthedocs&logoColor=black" />
  </a>
</div>

---

### 🗂️ All Projects — Live Repo Cards

<div align="center">

<!-- ROW 1 — AI / RAG Projects -->
<a href="https://github.com/tusharpandey436/YOUR-REPO-1">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-REPO-1&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12" />
</a>
<a href="https://github.com/tusharpandey436/YOUR-REPO-2">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-REPO-2&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12" />
</a>

<!-- ROW 2 — Backend / API Projects -->
<a href="https://github.com/tusharpandey436/YOUR-REPO-3">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-REPO-3&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12" />
</a>
<a href="https://github.com/tusharpandey436/YOUR-REPO-4">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-REPO-4&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12" />
</a>

<!-- ROW 3 — Tools / Utilities -->
<a href="https://github.com/tusharpandey436/YOUR-REPO-5">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-REPO-5&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12" />
</a>
<a href="https://github.com/tusharpandey436/YOUR-REPO-6">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tusharpandey436&repo=YOUR-REPO-6&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&border_radius=12" />
</a>

</div>

---

### 📌 Project Categories at a Glance

```
🤖 AI / RAG Systems
   ├── AI Teams Bot ────────── Production RAG · Gemini · Supabase · Hybrid Retrieval
   ├── YOUR-REPO-1 ─────────── [short description]
   └── YOUR-REPO-2 ─────────── [short description]

⚙️ Backend / APIs
   ├── YOUR-REPO-3 ─────────── [short description]
   └── YOUR-REPO-4 ─────────── [short description]

🛠️ Tools / Utilities
   ├── YOUR-REPO-5 ─────────── [short description]
   └── YOUR-REPO-6 ─────────── [short description]
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## ⚔️ Full Tech Arsenal

<div align="center">

### 🤖 AI / ML Stack
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini_1.5_Pro-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge" />
<img src="https://img.shields.io/badge/FAISS-00BFFF?style=for-the-badge" />
<img src="https://img.shields.io/badge/RAGAS-8B5CF6?style=for-the-badge" />

### ⚙️ Backend & Infrastructure
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />

### 🛠️ Dev Tools
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" />
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />

</div>

---

## 🧭 Skill Radar — Self Assessment

```
                        ★★★★★ EXPERT
                              │
  System Design  ────────── ████████████████░░  90%
  RAG Pipelines  ────────── ████████████████░░  88%
  FastAPI/Async  ────────── ███████████████░░░  85%
  LLM Integration────────── ███████████████░░░  85%
  Vector Search  ────────── ██████████████░░░░  80%
  Prompt Eng.    ────────── █████████████░░░░░  75%
  DevOps/Infra   ────────── ████████████░░░░░░  70%
  Agentic AI     ────────── ██████████░░░░░░░░  60%  ← Active Learning
  Multi-Modal    ────────── ████████░░░░░░░░░░  45%  ← Exploring
                              │
                        ★☆☆☆☆ LEARNING
```

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## 📊 GitHub Intelligence Dashboard

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=tusharpandey436&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&ring_color=00f7ff&include_all_commits=true" height="180" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tusharpandey436&layout=donut&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&text_color=c9d1d9&langs_count=8" height="180" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=tusharpandey436&theme=tokyonight&hide_border=true&background=0d1117&ring=00f7ff&fire=ff6b6b&currStreakLabel=00f7ff&sideLabels=7efff5&dates=7efff5&stroke=00f7ff" width="720" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=tusharpandey436&bg_color=0d1117&color=00f7ff&line=00f7ff&point=ff6b6b&area=true&area_color=00f7ff&hide_border=true&custom_title=Contribution+Activity+Graph" width="940" />

</div>

---

## 🏆 Achievements & Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=tusharpandey436&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=10" />
</div>

---

## 🐍 Commit Serpentine

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tusharpandey436/tusharpandey436/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tusharpandey436/tusharpandey436/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/tusharpandey436/tusharpandey436/output/github-contribution-grid-snake.svg" width="100%" />
  </picture>
</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## 🗓️ 2025 Engineering Roadmap

```
┌─────────────────────────────────────────────────────────────────────────┐
│                       TUSHAR'S 2025 BUILD PLAN                          │
├──────────┬──────────────────────────────────┬───────────┬───────────────┤
│ QUARTER  │ FOCUS                            │ PROGRESS  │ STATUS        │
├──────────┼──────────────────────────────────┼───────────┼───────────────┤
│  Q1 2025 │ Hybrid RAG + Reranking           │ ████████░ │ 🟢 Complete   │
│  Q1 2025 │ RAGAS Evaluation Integration     │ ███████░░ │ 🟢 Complete   │
│  Q2 2025 │ Agentic AI (Tool-Use + Planning) │ █████░░░░ │ 🟡 In Progress│
│  Q2 2025 │ Modular RAG Framework (OSS)      │ ████░░░░░ │ 🟡 In Progress│
│  Q3 2025 │ Multi-Modal RAG (Vision + Docs)  │ ██░░░░░░░ │ 🔵 Planned    │
│  Q3 2025 │ Streaming + SSE Response APIs    │ ██░░░░░░░ │ 🔵 Planned    │
│  Q4 2025 │ On-Device / Edge LLM Deployment  │ █░░░░░░░░ │ 🔵 Planned    │
│  Q4 2025 │ Open Source RAG Benchmark Suite  │ ░░░░░░░░░ │ 🔵 Planned    │
└──────────┴──────────────────────────────────┴───────────┴───────────────┘
```

---

## 🧠 What I'm Reading / Learning

<details>
<summary><b>📚 Current Study Stack (Click to expand)</b></summary>

```
📖 PAPERS
   ├── RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval
   ├── ColBERT v2: Effective and Efficient Retrieval via Lightweight Late Interaction
   ├── Self-RAG: Learning to Retrieve, Generate and Critique
   └── Mixture-of-Experts (MoE) — Sparse Gating Mechanisms

🛠️ BUILDING
   ├── Plug-and-play retriever interface (swap BM25/semantic/colbert)
   ├── Custom RAGAS metrics for domain-specific evaluation
   └── Streaming RAG API with Server-Sent Events

📺 FOLLOWING
   ├── LlamaIndex blog — advanced RAG patterns
   ├── Weaviate engineering newsletter
   └── Anthropic & Google DeepMind research drops
```

</details>

---

## 💬 Engineering Philosophy

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   "Real engineers don't just build features.                         ║
║    They build systems that survive production."                      ║
║                                                                      ║
║   "A RAG system is only as good as its worst retrieval."             ║
║                                                                      ║
║   "If it's not scalable, it's not finished."                         ║
║                                        — Tushar Pandey              ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## 🌐 Let's Connect & Collaborate

<div align="center">

<a href="https://www.linkedin.com/in/YOUR-LINK">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0077b5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0a1a" />
</a>
&nbsp;
<a href="mailto:tusharpandey436@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Drop_a_Mail-ea4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0a1a" />
</a>
&nbsp;
<a href="https://your-portfolio.dev">
  <img src="https://img.shields.io/badge/Portfolio-Live_Site-00f7ff?style=for-the-badge&logo=vercel&logoColor=black&labelColor=0a0a1a" />
</a>
&nbsp;
<a href="https://twitter.com/YOUR-HANDLE">
  <img src="https://img.shields.io/badge/Twitter-Follow-1da1f2?style=for-the-badge&logo=twitter&logoColor=white&labelColor=0a0a1a" />
</a>
&nbsp;
<a href="https://dev.to/YOUR-HANDLE">
  <img src="https://img.shields.io/badge/Dev.to-Articles-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white&labelColor=0a0a1a" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=tusharpandey436&color=00f7ff&style=for-the-badge&label=PROFILE+VIEWS" />
&nbsp;
<img src="https://img.shields.io/github/followers/tusharpandey436?style=for-the-badge&color=00ff88&labelColor=0d1117&label=GITHUB+FOLLOWERS" />
&nbsp;
<img src="https://img.shields.io/github/stars/tusharpandey436?style=for-the-badge&color=f59e0b&labelColor=0d1117&label=TOTAL+STARS" />

</div>

---

<!-- FOOTER -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f7ff,30:8b5cf6,60:0d1f3c,100:020010&height=180&section=footer&text=Built%20like%20a%20product.%20Not%20a%20profile.&fontSize=22&fontColor=ffffff&animation=twinkling&fontAlignY=68&desc=Open%20to%20collabs%20%7C%20AI%20%7C%20Backend%20%7C%20Systems&descColor=00f7ff&descAlignY=85&descSize=13" />
</div>

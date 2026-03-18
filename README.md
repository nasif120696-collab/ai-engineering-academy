<div align="center">

<img src="https://img.shields.io/badge/focus-Applied%20AI%20Engineering-6366f1?style=for-the-badge&labelColor=0a0b1a" />
<img src="https://img.shields.io/badge/cost-Free-10b981?style=for-the-badge&labelColor=0a0b1a" />
<img src="https://img.shields.io/badge/license-MIT-b48eff?style=for-the-badge&labelColor=0a0b1a" />
<img src="https://img.shields.io/badge/deployment-Vercel-000000?style=for-the-badge&logo=vercel&labelColor=0a0b1a" />
<img src="https://img.shields.io/badge/status-Live-10b981?style=for-the-badge&labelColor=0a0b1a" />

<br /><br />

# ⚙️ AI Engineering Academy

### *Mastering Applied AI, One Concept at a Time*

<br />

> **"Your journey into AI shouldn't be overwhelming.**
> **Structured paths. Hands-on practice. Production-ready skills."**
> — *Mushfiqul Alam Nasif, Creator*

<br />

**[🌐 Live Site](https://ai-engineering-academy.vercel.app/)** &nbsp;·&nbsp;
**[✨ Features](#-key-features)** &nbsp;·&nbsp;
**[🗺️ Learning Paths](#-learning-paths)** &nbsp;·&nbsp;
**[🚀 Getting Started](#-getting-started)** &nbsp;·&nbsp;
**[🤝 Contributing](#-contributing)**

<br />

---

</div>

## 📌 What is AI Engineering Academy?

**AI Engineering Academy** is a structured, hands-on learning platform for aspiring AI Engineers. It bridges the gap between knowing machine learning theory and actually **building production-grade AI systems** — covering everything from prompt engineering and RAG pipelines to LLM fine-tuning, MLOps, and real-world deployment.

Unlike generic AI tutorials, this platform is curated around the skills that professional AI engineers use on the job every day: designing retrieval systems, working with vector databases, building LLM applications, and deploying models at scale — all with practical, runnable code.

**Free. Structured. Production-focused.**

<br />

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🗺️ **Structured Learning Paths** | Carefully designed roadmaps from AI fundamentals to advanced production systems — no guesswork |
| 💻 **Hands-on Notebooks** | Every concept comes with runnable Python notebooks — learn by building, not just reading |
| 🤖 **LLM Engineering** | Deep coverage of Large Language Models: architecture, prompting, fine-tuning, and evaluation |
| 🔍 **RAG Systems** | Complete guide to Retrieval-Augmented Generation using LlamaIndex, LangChain, and vector databases |
| 🏭 **Production AI** | MLOps, model deployment, API serving, monitoring, and scaling AI systems in the real world |
| 🎯 **Industry-Aligned** | Focus on skills used in real AI engineering roles — not just academic theory |
| 📱 **Responsive Design** | Fully optimized across mobile, tablet, and desktop |
| ⚡ **Zero Dependencies** | Lightweight, fast-loading platform built with pure HTML/CSS/JS |

<br />

---

## 🗺️ Learning Paths

> Structured pathways from AI fundamentals to advanced applied engineering.

### 🔍 Retrieval-Augmented Generation (RAG)
Build AI systems that ground their responses in real external knowledge:
- **Basic RAG** — Document ingestion, chunking, embedding, and retrieval
- **Advanced RAG** — Re-ranking, hybrid search, query rewriting, and evaluation
- **Production RAG** — Qdrant/FAISS vector stores, LlamaIndex pipelines, chat engines
- **Tools:** LlamaIndex · LangChain · Qdrant · FAISS · FastEmbed · Groq

### 🧠 LLM Engineering
Master the art and science of working with Large Language Models:
- **Prompt Engineering** — Few-shot, chain-of-thought, ReAct, and structured prompting
- **Fine-tuning** — LoRA, QLoRA, instruction tuning on custom datasets
- **Evaluation** — ROUGE, BERTScore, LLM-as-judge, hallucination detection
- **Tools:** HuggingFace · OpenAI API · Ollama · PEFT · TRL

### 🏭 MLOps & Production AI
Deploy and maintain AI systems that actually work in production:
- **Experiment Tracking** — MLflow, Weights & Biases
- **Model Serving** — FastAPI, Docker, REST APIs for ML models
- **Deployment** — HuggingFace Spaces, Vercel, cloud deployment patterns
- **Monitoring** — Drift detection, logging, performance tracking

### 🤖 Agentic AI
Build autonomous AI systems that reason and act:
- **AI Agents** — Tool use, function calling, multi-step reasoning
- **Multi-Agent Systems** — Agent orchestration and collaboration
- **Tools:** LangChain Agents · LlamaIndex · AutoGen

<br />

---

## 🛠️ Tech Stack
```
Frontend        HTML5 · CSS3 · Vanilla JavaScript
Notebooks       Python · Jupyter · Google Colab compatible
AI Frameworks   LlamaIndex · LangChain · HuggingFace Transformers
Vector DBs      Qdrant · FAISS · Chroma
LLM Providers   OpenAI · Groq · Ollama (local, free)
Deployment      Vercel — free, high-performance global hosting
Dependencies    Zero external JS libraries
```

<br />

---

## 🏗️ Project Structure
```
ai-engineering-academy/
│
├── 📄 index.html               Main landing page
├── 🎨 style.css                Stylesheet — layout, theme, responsiveness
├── ⚙️  main.js                 Interactivity and navigation
├── 📋 README.md                This file
│
├── 📁 rag/                     RAG learning path
│   ├── 01_basic_rag/           Document ingestion, embedding, retrieval
│   ├── 02_advanced_rag/        Re-ranking, hybrid search, evaluation
│   └── 03_production_rag/      Scalable RAG with vector databases
│
├── 📁 llm-engineering/         LLM Engineering path
│   ├── prompt-engineering/     Prompting techniques and patterns
│   ├── fine-tuning/            LoRA, QLoRA, instruction tuning
│   └── evaluation/             LLM evaluation frameworks
│
├── 📁 mlops/                   MLOps & Deployment path
│   ├── experiment-tracking/    MLflow, W&B
│   └── model-serving/          FastAPI, Docker, deployment
│
└── 📁 agents/                  Agentic AI path
    ├── tool-use/               Function calling, tool integration
    └── multi-agent/            Agent orchestration patterns
```

<br />

---

## 🚀 Getting Started

### View the Platform

Simply visit the live site:
**[https://ai-engineering-academy.vercel.app/](https://ai-engineering-academy.vercel.app/)**

### Run Locally
```bash
# 1. Clone the repository
git clone https://github.com/nasif120696-collab/ai-engineering-academy.git

# 2. Navigate into the project
cd ai-engineering-academy

# 3. Open in your browser — no build step needed
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Run Notebooks

All notebooks are compatible with **Google Colab** (free GPU):
```bash
# Install dependencies for any notebook
pip install llama-index langchain transformers \
            qdrant-client fastembed openai groq

# Or use the requirements file if available
pip install -r requirements.txt
```

### Deploy Your Own Instance (Free)

**Vercel:**
```
1. Fork this repository
2. vercel.com → New Project → Import from GitHub
3. Select repo → Deploy
4. Live in ~30 seconds
```

**GitHub Pages:**
```
1. Fork this repository
2. Settings → Pages → Source: main branch → / (root)
3. Save → live at: https://YOUR-USERNAME.github.io/ai-engineering-academy
```

<br />

---

## 🗺️ Roadmap

- [x] **v1.0** — Core platform: learning paths, RAG notebooks, LLM engineering guide
- [ ] **Phase 1** — Interactive code playground embedded in the browser
- [ ] **Phase 2** — Progress tracking and personal learning dashboard
- [ ] **Phase 3** — Community-contributed notebooks and peer review system
- [ ] **Phase 4** — AI Engineer job board and interview preparation guide
- [ ] **Phase 5** — Bangla-language content track for Bangladeshi learners

<br />

---

## 🤝 Contributing

Contributions from AI engineers, researchers, and students are warmly welcome.
```bash
# 1. Fork the repository

# 2. Clone your fork
git clone https://github.com/YOUR-USERNAME/ai-engineering-academy.git
cd ai-engineering-academy

# 3. Create a descriptive branch
git checkout -b feat/add-advanced-rag-notebook

# 4. Add your content and commit
git commit -m "feat(rag): add hybrid search with BM25 + dense embeddings notebook"

# 5. Push and open a Pull Request
git push origin feat/add-advanced-rag-notebook
```

### Ways to contribute:
- 📓 Add new Jupyter notebooks on applied AI engineering topics
- 🐛 Fix bugs, broken links, or outdated package versions
- 📄 Improve documentation and concept explanations
- 🌍 Translate content for Bangla-speaking learners
- 💡 Suggest new learning paths via [GitHub Issues](https://github.com/nasif120696-collab/ai-engineering-academy/issues)

<br />

---

## 📊 Project Stats

| Metric | Value |
|---|---|
| Focus Area | Applied AI Engineering |
| Target Audience | Students & developers building real AI systems |
| Notebook Compatibility | Google Colab (free GPU) |
| Deployment | Vercel (free tier) |
| JS Dependencies | **0** |
| Framework | None — pure HTML/CSS/JS |
| License | MIT |

<br />

---

## 🔗 Related Projects by the Same Creator

| Project | Description |
|---|---|
| [🧠 NeuralPath](https://github.com/nasif120696-collab/neuralpath) | Free AI/ML mastery curriculum — Python to research publication |
| [🛩️ Pi-Lot](https://github.com/nasif120696-collab/PI-LOT) | Scholarship & study abroad platform for Bangladeshi students |
| [🎓 BAUST CSE Hub](https://github.com/nasif120696-collab/baust-khulna-cse-hub) | Student resource hub for BAUST Khulna CSE Department |

<br />

---

## 📄 License
```
MIT License — Copyright (c) 2025 Mushfiqul Alam Nasif

Free to use, fork, modify, and distribute.
All notebook content and code examples are released under MIT.
```

> External tools, libraries, and APIs referenced in notebooks
> (OpenAI, HuggingFace, Qdrant, LlamaIndex, LangChain, etc.)
> are subject to their own licenses and terms of service.

<br />

---

<div align="center">

**Developed with ❤️ by Mushfiqul Alam Nasif**

*Mastering Applied AI, One Concept at a Time.*

<br/>

⭐ **If this helped your AI engineering journey, please give it a star!** ⭐

[![GitHub stars](https://img.shields.io/github/stars/nasif120696-collab/ai-engineering-academy?style=social)](https://github.com/nasif120696-collab/ai-engineering-academy)
[![GitHub forks](https://img.shields.io/github/forks/nasif120696-collab/ai-engineering-academy?style=social)](https://github.com/nasif120696-collab/ai-engineering-academy/fork)

</div>

---
layout: default
---

Welcome to my portfolio. I design production AI systems that combine autonomous agents,
LLM evaluation, observability, and scalable cloud infrastructure.

Currently, I lead the competitive Machine Learning team at [Factored](https://www.factored.ai), driving technical strategy for global data science challenges while architecting advanced, reliable generative AI pipelines.

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
  <a href="https://www.linkedin.com/in/kelvin-andre-pacheco-34928379/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/kelvinandrepacheco" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://medium.com/@kelvinpac" target="_blank">
    <img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium">
  </a>
</div>

<style>
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
  margin: 30px 0;
}

.stat-card {
  background: var(--color-canvas-default, #ffffff);
  border: 1px solid var(--color-border-default, #d0d7de);
  border-radius: 12px;
  padding: 22px;
  transition: all .2s ease;
}

.stat-card:hover {
  transform: translateY(-4px);
  border-color: #58a6ff;
  box-shadow: 0 8px 20px rgba(0,0,0,.08);
}

.stat-number {
  font-size: 2rem;
  font-weight: 700;
  line-height: 1;
  color: #0969da;
  margin-bottom: 10px;
}

.stat-title {
  font-size: 1rem;
  font-weight: 600;
  color: inherit;
}

.stat-subtitle {
  margin-top: 6px;
  font-size: .9rem;
  color: #656d76;
  line-height: 1.4;
}

@media (prefers-color-scheme: dark) {

  .stat-card {
    background: #161b22;
    border-color: #30363d;
  }

  .stat-number {
    color: #58a6ff;
  }

  .stat-subtitle {
    color: #8b949e;
  }

  .stat-card:hover {
    box-shadow: 0 10px 25px rgba(0,0,0,.35);
  }

}
</style>

### Highlights

<div class="stats-grid">

<div class="stat-card">
<div class="stat-number">10+</div>
<div class="stat-title">Years Engineering</div>
<div class="stat-subtitle">
Building industrial software, optimization models and production AI systems.
</div>
</div>

<div class="stat-card">
<div class="stat-number">6+</div>
<div class="stat-title">Years in Machine Learning</div>
<div class="stat-subtitle">
Production ML, MLOps, LLMs, agentic workflows and enterprise AI.
</div>
</div>

<div class="stat-card">
<div class="stat-number">Ph.D.</div>
<div class="stat-title">Chemical Engineering</div>
<div class="stat-subtitle">
Research focused on neural networks, optimization and industrial AI.
</div>
</div>

<div class="stat-card">
<div class="stat-number">🏢</div>
<div class="stat-title">Enterprise GenAI</div>
<div class="stat-subtitle">
Architecting production-grade AI platforms for global organizations.
</div>
</div>

<div class="stat-card">
<div class="stat-number">🤖</div>
<div class="stat-title">Agentic AI</div>
<div class="stat-subtitle">
Multi-agent systems, structured outputs, evaluation and observability.
</div>
</div>

<div class="stat-card">
<div class="stat-number">☁️</div>
<div class="stat-title">Azure Cloud</div>
<div class="stat-subtitle">
Azure OpenAI, Databricks, Container Apps, DevOps and cloud-native ML.
</div>
</div>

</div>

---

### Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![PydanticAI](https://img.shields.io/badge/PydanticAI-E92063?style=for-the-badge)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub%20Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

**Architectural Philosophy:** I have moved beyond isolated notebook experiments. My approach emphasizes type-safe API boundaries, rigorous evaluation logs, and failure handling. *Vibe coding* for rapid architectural iterations, paired with strict human expert curation to guarantee production reliability.

---

### Engineered Systems & Projects

#### 1. Autonomous Agentic Systems: Deep Researcher
*An autonomous workflow designed to accelerate competitive machine learning strategy formulation.*
* **Architecture:** Built using **PydanticAI** and **FastAPI** to ensure strict data validation and type safety across agent interactions.
* **Capabilities:** Executes multi-step reasoning, complex tool calling, and autonomous data collection.
* **Impact:** Drastically reduces the time spent on initial data plumbing and pipeline setup during rapid-iteration Kaggle competitions.

#### 2. LLMOps & Evaluation Frameworks
*Because production LLMs require deep observability, not just basic text generation.*
* **Tracing:** Comprehensive integration with **Langfuse**, **Sentry**, and **Azure Monitor** to capture payload snapshots, trace token usage, and monitor system latency.
* **Validation:** Designed custom *LLM-as-a-judge* evaluation pipelines to run golden-set queries, trace citation coverage, and systematically catch failure edges.

#### 3. Full-Stack ML: API Churn Prediction & Process Optimization
*Transforming predictive models into consumable, scalable enterprise services.*
* **Implementation:** Deployed high-performance FastAPI predictive endpoints with robust error handling and real-time data validation.
* **Domain Applications:** Adapted similar architectural rigor to optimize complex industrial chemical processes, including battery optimization and data collection via neural networks.

---

### Writing & Publications

I write about production AI engineering,
LLMOps, evaluation frameworks,
and enterprise architecture. You can read my latest deep dives on Medium:

<style>
  .article-carousel {
    display: flex;
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    gap: 20px;
    padding-bottom: 20px;
    margin-top: 15px;
    -webkit-overflow-scrolling: touch;
  }
  
  .article-card {
    min-width: 300px;
    max-width: 300px;
    scroll-snap-align: start;
    background-color: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    display: flex;
    flex-direction: column;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .article-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  }

  @media (prefers-color-scheme: dark) {
    .article-card {
      background-color: #0d1117;
      border-color: #30363d;
    }
    .article-card:hover {
      box-shadow: 0 8px 15px rgba(0,0,0,0.4);
    }
  }

  .article-card h4 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 1.1em;
    color: #0366d6;
  }

  .article-card p {
    font-size: 0.9em;
    line-height: 1.5;
    margin-bottom: 10px;
    flex-grow: 1;
    color: #24292e;
  }

  @media (prefers-color-scheme: dark) {
    .article-card p { color: #c9d1d9; }
  }
  
  .article-tags {
    font-size: 0.8em;
    color: #586069;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
  
  .article-carousel::-webkit-scrollbar {
    height: 8px;
  }
  .article-carousel::-webkit-scrollbar-track {
    background: transparent;
  }
  .article-carousel::-webkit-scrollbar-thumb {
    background-color: #c1c1c1;
    border-radius: 4px;
  }

  .card-link {
    text-decoration: none !important;
    color: inherit !important;
  }
</style>

<div class="article-carousel">
  
  <a href="https://medium.com/@kelvinpac/llm-as-a-judge-evaluating-llm-outputs-and-the-challenge-of-hallucinations-7264e838f941" target="_blank" class="card-link">
    <div class="article-card">
      <h4>⚖️ LLM-as-a-judge</h4>
      <p>An exploration of using language models to systematically evaluate AI outputs and mitigate the persistent issue of hallucinations in generative pipelines.</p>
      <div class="article-tags">Read on Medium ↗</div>
    </div>
  </a>

  <a href="https://medium.com/@kelvinpac/from-fragile-to-agile-how-we-built-a-bulletproof-llm-gateway-with-portkey-54c13425fd21" target="_blank" class="card-link">
    <div class="article-card">
      <h4>🛡️ Bulletproof LLM Gateway</h4>
      <p>A deep dive into architecting a robust, production-ready LLM gateway to handle API routing, observability, and system resilience at scale.</p>
      <div class="article-tags">Read on Medium ↗</div>
    </div>
  </a>

  <a href="https://medium.com/@kelvinpac/from-vms-to-kubernetes-a-ci-cd-pipeline-migration-journey-d25bba90a1c8" target="_blank" class="card-link">
    <div class="article-card">
      <h4>⛴️ From VMs to Kubernetes</h4>
      <p>A technical walkthrough of modernizing infrastructure by migrating continuous integration and deployment pipelines from virtual machines to scalable Kubernetes clusters.</p>
      <div class="article-tags">Read on Medium ↗</div>
    </div>
  </a>

</div>

<br>

---

### Competitive Data Science
Leading technical strategy in global, high-stakes environments:
* **Kaggle Competitions:** ARC Prize, NFL Prediction, and the DeepPast Akkadian Challenge.

---

### Milestones & Certifications
* **Certification:** [Claude Architect Certification (2026)](https://www.credly.com/badges/b4695a98-3cf4-49af-9eac-fdefe03a1b22)
* **Speaking:** Presenting on *LLM Observabilidade e LLMOps com Langfuse* at [TDC São Paulo 2026](https://thedevconf.com/tdc/2026/sao-paulo/).

---

### Let's Connect

Outside engineering, you can usually find me listening to Tim Maia, Jorge Vercillo, and quality Pagode, or even enjoying the beach and catching waves on a surfboard.

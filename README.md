<div align="center">

<a href="https://github.com/sapna71">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3200&pause=1100&color=2C9CDB&center=true&vCenter=true&width=760&lines=Generative+AI+and+Backend+Engineer;Agentic+AI+workflows+%7C+RAG+applications+%7C+FastAPI+services;Third-year+B.Tech+CSE+%7C+Batch+2028;Open+to+internships+in+software+and+AI+engineering" alt="Typing animation" />
</a>

<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-2C5364?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-2zu6.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sapna-singh-9a652332a)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/sapnasingh81)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sapnasinghh71@gmail.com)

[About](#about) &nbsp;|&nbsp; [Projects](#projects) &nbsp;|&nbsp; [Experience](#experience) &nbsp;|&nbsp; [Skills](#skills) &nbsp;|&nbsp; [Activity](#activity) &nbsp;|&nbsp; [Contact](#contact)

</div>

---

## About

I build Generative AI and backend systems that stay reliable under failure. My work centres on agentic AI workflows, retrieval-augmented generation and asynchronous FastAPI services, with an emphasis on clean architecture, observability and clear documentation.

| | |
|---|---|
| **Education** | B.Tech in Computer Science and Engineering, Batch 2028 (Kolkata) |
| **Experience** | Generative AI Intern, GenAI Center of Excellence, IEM-UEM Group (May - Jul 2026) |
| **Focus** | Agentic AI workflows, RAG applications, async backend services |
| **Exploring** | LoRA and QLoRA fine-tuning, advanced Generative AI, LLM evaluation |
| **Ask me about** | RAG, LangChain and LangGraph, FastAPI, system design, data structures and algorithms |
| **Open to** | Internships in Software Engineering, Generative AI, AI/ML, Backend and Data Engineering |

---

## Projects

| Project | Summary | Stack | Links |
|---|---|---|---|
| **Sentinel** | Self-healing orchestration layer for distributed agentic AI workflows | Python, FastAPI, LangGraph, async SQLAlchemy | [Live demo](https://sentinel-drab-eight-78.vercel.app) / [Source](https://github.com/sapna71/Sentinel) |
| **Codent** | Answers questions about any GitHub repository with file-level citations | Groq (Llama 3.3 70B), LangChain, Gemini Embeddings, FAISS | [Live demo](https://codent-neon.vercel.app/) / [Source](https://github.com/sapna71/Codent) |
| **DigiRaksha** | Real-time SOS alert backend for disaster response | Python, FastAPI, REST APIs | [Source](https://github.com/sapna71/Digi-Raksha) |
| **VerifAI** | Detects contradictions in long narratives with retrieval and NLI | Sentence Transformers, RoBERTa-MNLI | [Source](https://github.com/sapna71/VerifAI) |
| **MiniGPT** | End-to-end Generative AI application prototype | Python, LLMs, RAG | [Source](https://github.com/sapna71/miniGPT) |

Expand a project below for the problem, approach and results.

<details>
<summary><b>Sentinel - self-healing orchestration for agentic AI workflows</b></summary>

<br/>

**Problem.** Distributed AI workflows must remain available and observable when individual agents fail.

**Approach**
- 8+ modular, scalable orchestration components built with FastAPI and LangGraph
- Async-first architecture with async SQLAlchemy, a Postgres-ready SQLite layer and Pydantic Settings v2
- Event-driven streaming and health monitoring for full operational visibility
- Circuit breaker for automatic failure recovery
- System architecture and workflow diagrams documented in the repository README

**Stack.** Python, FastAPI, LangGraph, SQLAlchemy (async), Pydantic

[Live demo](https://sentinel-drab-eight-78.vercel.app) / [Source](https://github.com/sapna71/Sentinel)

</details>

<details>
<summary><b>Codent - question answering over any GitHub repository</b></summary>

<br/>

**Problem.** Understanding an unfamiliar codebase is slow, and generic chatbots cannot show where an answer came from.

**Approach**
- Indexes any GitHub repository and retrieves relevant code with Gemini embeddings and a FAISS vector index
- Orchestrated with LangChain, generating answers with Llama 3.3 70B Versatile on Groq
- Every answer is grounded and cited to the exact files it came from
- FastAPI backend, deployed live on Vercel

```mermaid
flowchart LR
    A[GitHub repository] --> B[Index and chunk files]
    B --> C[Gemini embeddings]
    C --> D[(FAISS vector index)]
    Q[User question] --> E[Semantic retrieval]
    D --> E
    E --> F[LangChain orchestration]
    F --> G[Llama 3.3 70B on Groq]
    G --> H[Answer with file-level citations]
```

[Live demo](https://codent-neon.vercel.app/) / [Source](https://github.com/sapna71/Codent)

</details>

<details>
<summary><b>DigiRaksha - disaster-response backend (HackOasis, Top 4 of 112 teams)</b></summary>

<br/>

**Problem.** Responders need one reliable channel for real-time SOS alerts and incident reports during emergencies.

**Approach**
- FastAPI REST services for real-time SOS alert generation and incident reporting
- Asynchronous request handling that reduced API response latency by about 30%
- Authenticated endpoints so only verified responders can update incident status

**Result.** Top 4 of 112 teams at HackOasis.

[Source](https://github.com/sapna71/Digi-Raksha)

</details>

<details>
<summary><b>VerifAI - contradiction detection in long narratives</b></summary>

<br/>

**Problem.** Check whether a claim is consistent with, or contradicts, a long multi-part narrative.

**Approach**
- Splits text into atomic claims and retrieves top-k evidence with Sentence Transformers
- Verifies each claim with RoBERTa-MNLI natural language inference

**Results.** 91.2% accuracy, 89.8% F1-score, 90.5% precision and 89.1% recall on the evaluation dataset. Built for the Kshitij Data Science Challenge, IIT Kharagpur.

[Source](https://github.com/sapna71/VerifAI)

</details>

<details>
<summary><b>MiniGPT - end-to-end Generative AI application</b></summary>

<br/>

Prototyped during my internship at the GenAI Center of Excellence, with LLM and RAG workflows.

[Source](https://github.com/sapna71/miniGPT)

</details>

---

## Experience

<details>
<summary><b>Generative AI Intern - GenAI Center of Excellence, IEM-UEM Group (May - Jul 2026)</b></summary>

<br/>

- Contributed to software development with Python backend components and API integration for LLM solutions
- Prototyped MiniGPT, an end-to-end Generative AI application, with LLM and RAG workflows
- Applied prompt engineering and evaluated model outputs, debugging response quality during LLM experiments
- Collaborated with cross-functional teams and contributed to technical workshops and applied research initiatives

</details>

<details>
<summary><b>Achievements and leadership</b></summary>

<br/>

- Top 4 of 112 teams at HackOasis (DigiRaksha)
- Participated in 7 hackathons
- Solved 100+ data structures and algorithms problems on [LeetCode](https://leetcode.com/u/sapnasingh81)
- Core Team Member, Google Developer Group (GDG) on Campus, IEM-UEM
- Student Coordinator, GenAI Center of Excellence, IEM-UEM

</details>

---

## Skills

<div align="center">

| Area | Technologies |
|---|---|
| **Languages and databases** | ![Python](https://skillicons.dev/icons?i=py,cpp,postgres,mysql,sqlite) |
| **Backend and cloud** | ![Backend](https://skillicons.dev/icons?i=fastapi,docker,linux,vercel,postman) |
| **Data and ML** | ![ML](https://skillicons.dev/icons?i=numpy,pandas,sklearn,tensorflow) |
| **Tools** | ![Tools](https://skillicons.dev/icons?i=git,github,vscode) |
| **Generative AI** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-2C5364?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-2C5364?style=flat-square) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) ![Gemini Embeddings](https://img.shields.io/badge/Gemini_Embeddings-4285F4?style=flat-square) |

</div>

---

## Activity

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=sapna71&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub statistics" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sapna71&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages" />

<img src="https://streak-stats.demolab.com?user=sapna71&theme=tokyonight&hide_border=true" alt="Contribution streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sapna71&theme=tokyo-night&hide_border=true" alt="Contribution graph" width="95%" />

<img src="https://leetcard.jacoblin.cool/sapnasingh81?theme=dark&font=Karla&ext=heatmap" alt="LeetCode statistics" />

</div>

---

## Contact

I am seeking internships in software engineering, Generative AI and backend development. If you are building something in these areas, I would be glad to hear from you.

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sapnasinghh71@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-2C5364?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-2zu6.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sapna-singh-9a652332a)

</div>

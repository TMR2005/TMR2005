<div align="center">

# Hi, I'm Praveen 👋

### Systems & Backend Engineer · Performance Nerd · Compiler Tinkerer

*I build systems that scale, and I dig into why they break when they do.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/praveen-tmr)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tmrpraveen2005@gmail.com)
[![Codeforces](https://img.shields.io/badge/Codeforces-1514-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com)

</div>

---

## 🎯 About Me

B.Tech + M.Tech (Dual Degree) in Computer Science at **IIITDM Chennai** (2028).
I care about the stuff that lives under the abstraction: memory layout, cache behavior, concurrency, and what happens when a queue fills up at 3 AM.

**Currently chasing:**
- 🧠 Memory management and scheduling in distributed query engines
- ⚡ Lock-free data structures and high-throughput systems
- 🔍 Making AI systems more reliable: hallucination detection, grounded RAG, uncertainty-aware inference

---

## 🛠️ Stack

| Domain | Tools |
|---|---|
| **Systems** | C++17, C, Linux internals (`/proc`, `/sys`), concurrency, memory pools |
| **Backend** | FastAPI, Node.js, REST APIs, Redis, Celery, PostgreSQL |
| **Cloud & DevOps** | AWS EC2, Azure Functions, Azure Service Bus, Docker, Hostinger VPS |
| **Compilers & HDL** | Flex/Bison, TAC IR, MIPS codegen, SystemVerilog |
| **ML** | PyTorch, TensorFlow, scikit-learn, OpenCV |
| **Languages** | Python, TypeScript, JavaScript, Java, SystemVerilog |

---

## 🔥 Featured Work

### ⚡ [Low-Latency Limit Order Book](https://github.com/TMR2005/Limit-Order-Book)
Price-time priority matching engine in C++17.
- ~**9.8M orders/sec** (~101 ns/op) on synthetic benchmarks
- Preallocated memory pools, arena allocation, and array-indexed price levels
- ~30% faster than a `std::map` design thanks to better cache locality
- Atomic operations with explicit memory ordering for concurrent book updates

### 🧪 [Elekki: Online Verilog Judge](https://github.com/TMR2005)
Async HDL compile-and-simulate platform.
- FastAPI API, Redis/Celery job queues, isolated Docker workers for untrusted code
- **23.18 jobs/sec** on 4 workers, **100% job resolution** under 100–1,000 concurrent submissions
- Deployed on AWS EC2 with a status-polling API

### 📡 [MLinux: GPU & System Telemetry](https://github.com/TMR2005)
Telemetry daemon for ML workloads.
- Reads GPU, CPU, memory, and I/O metrics straight from `/proc` and `/sys` at **< 2% CPU overhead**
- Correlates resource usage with training throughput to find bottlenecks
- Real-time TUI dashboard and structured logging

### 🧩 [AI-Augmented Smart Compiler](https://github.com/TMR2005/AI-Augumented-Smart-Compiler)
MiniC compiler from lexing through MIPS codegen.
- Liveness-based register-pressure analysis on three-address code
- LLM-assisted TAC rewriting in the compilation pipeline

### 🩻 [Multimodal Brain Tumor Segmentation](https://github.com/TMR2005/Multimodal-Fusion-for-Medical-Image-Segmentation)
- MRI fused with radiology text via a Vision-Language Model (FiLM)
- **0.87 Dice**, **0.79 IoU**

---

## 💼 Experience

**Software Engineering Intern · IIITDM Chennai** *(May – Aug 2026)*
- Built a React Native + Node.js + TypeScript platform used by **2,500+ students** across 4 hostel blocks
- Cut cached API P95 latency from **50 ms to 1–5 ms** with Redis, PostgreSQL indexing, and connection pooling
- Ran it on a VPS with monitoring: **99%+ uptime**, sub-100 ms responses under peak load

**Product Engineering Intern · LiquidMind.AI** *(Jun – Jul 2025)*
- Led a team of 3 in rebuilding a monolithic document pipeline into event-driven microservices on Azure
- Raised throughput **12–16×** and cut end-to-end latency by **~90%** via batching and parallel execution
- Added idempotent workflows, dead-letter queues, and retry logic for fault tolerance

---

## 🏆 Competitive Programming

- **Codeforces Specialist**, max rating **1514**
- **400+** problems solved across Codeforces, LeetCode, and AtCoder

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TMR2005&show_icons=true&theme=algolia&hide_border=true&count_private=true" alt="GitHub Stats" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TMR2005&layout=compact&theme=algolia&hide_border=true&langs_count=8" alt="Top Languages" height="170"/>
</div>

<div align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=TMR2005&theme=algolia&hide_border=true" alt="GitHub Streak"/>
</div>

---

## 📫 Let's Talk

I'm happy to chat about systems war stories, performance debugging, compilers, or reliable AI systems.

- 💼 [LinkedIn](https://www.linkedin.com/in/praveen-tmr)
- 📧 [Email](mailto:tmrpraveen2005@gmail.com)
- 💻 [GitHub](https://github.com/TMR2005)

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=TMR2005&color=blueviolet&style=flat-square&label=Profile+Views)

</div>

<p align="center">
  <img src="./assets/varun-readme-hero.svg" alt="Varun Pratap Bhardwaj: AI Reliability Engineering" width="100%" />
</p>

# Varun Pratap Bhardwaj

I work on **AI Reliability Engineering**: how to know an AI agent did what it says it did. That means memory you can audit, contracts an agent cannot quietly break, tests built for answers that change from run to run, and loops that end on an independent check instead of the agent's own word.

I founded [Qualixar](https://github.com/qualixar), my independent research initiative, where I publish the tools and the papers behind them. My day job is enterprise solution architecture: 16 years in IT, and 5× Global Technology Innovation Award winner (2021–2025).

**17** open-source products · **10** arXiv preprints · **511** GitHub stars

[qualixar.com](https://qualixar.com) · [varunpratap.com](https://www.varunpratap.com) · [YouTube](https://www.youtube.com/@Qualixar-AI) · [X](https://x.com/varunPbhardwaj) · [LinkedIn](https://linkedin.com/in/varun-pratap-bhardwaj-7ab63742) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=CRRPXkwAAAAJ)

### ⭐ [SuperLocalMemory](https://github.com/qualixar/superlocalmemory): the flagship

Local-first memory for AI agents. Claude Code, Codex, Cursor and other MCP clients keep project context across sessions, and every recall points back to its source. **205k+ downloads** across npm and PyPI. Backed by 4 arXiv preprints.

[![stars](https://img.shields.io/github/stars/qualixar/superlocalmemory?style=for-the-badge&label=stars&color=f5b301&labelColor=2b2b2b)](https://github.com/qualixar/superlocalmemory) [![npm](https://img.shields.io/npm/dt/superlocalmemory?style=for-the-badge&label=npm&color=cb3837&labelColor=2b2b2b)](https://www.npmjs.com/package/superlocalmemory) [![pypi](https://img.shields.io/pepy/dt/superlocalmemory?style=for-the-badge&label=pypi&color=3775a9&labelColor=2b2b2b)](https://pypi.org/project/superlocalmemory/) [![release](https://img.shields.io/github/v/release/qualixar/superlocalmemory?style=for-the-badge&label=release&color=3b82f6&labelColor=2b2b2b)](https://github.com/qualixar/superlocalmemory/releases)

```bash
npm install -g superlocalmemory
```

### Flagship work

| Product | What it does | Proof |
| --- | --- | --- |
| **[SuperLocalMemory](https://github.com/qualixar/superlocalmemory)**<br><sub>Memory · [Start →](https://www.superlocalmemory.com)</sub> | Governed, local-first memory for agents, with source-linked recall and workspace isolation. | ![stars](https://img.shields.io/github/stars/qualixar/superlocalmemory?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/superlocalmemory?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>4 papers</sub> |
| **[brief2mp4](https://github.com/qualixar/brief2mp4) + [brief2motion](https://github.com/qualixar/brief2motion)**<br><sub>Motion · [Start →](https://github.com/qualixar/brief2mp4#quick-start)</sub> | Write a brief in Claude Code or Codex. brief2mp4 makes a checked MP4 in 82 art forms, even a [full documentary](https://youtu.be/aP2wHwG_dSA); brief2motion makes a website that moves ([film + website](https://youtu.be/fI3a3oDvLE4)). One install gives you both. | ![stars](https://img.shields.io/github/stars/qualixar/brief2mp4?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/brief2mp4?style=flat&label=&color=3b82f6&labelColor=2b2b2b) [![brief2motion stars](https://img.shields.io/github/stars/qualixar/brief2motion?style=flat&label=%E2%98%85%20brief2motion&color=f5b301&labelColor=2b2b2b)](https://github.com/qualixar/brief2motion) |
| **[Bounded Loops](https://github.com/qualixar/bounded-loops)**<br><sub>Loops & graphs · [Start →](https://github.com/qualixar/bounded-loops/blob/main/docs/QUICK_PROOF.md)</sub> | Agent loops and graphs that stop on an independent gate, with spend bounds set before the run and a hash-chained ledger. | ![stars](https://img.shields.io/github/stars/qualixar/bounded-loops?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/bounded-loops?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>1 paper</sub> |
| **[Qualixar OS](https://github.com/qualixar/qualixar-os)**<br><sub>Orchestration · [Start →](https://qualixar.com/products/qualixar-os)</sub> | Runs agent teams across multi-agent topologies, routes models by cost and quality, and judges outputs before they ship. | ![stars](https://img.shields.io/github/stars/qualixar/qualixar-os?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b)<br><sub>1 paper</sub> |
| **[SkillFortify](https://github.com/qualixar/skillfortify)**<br><sub>Security · [Start →](https://qualixar.com/products/skillfortify)</sub> | Scans agent skills and MCP configs before they run: capability analysis, dependency checks, a bill of materials. | ![stars](https://img.shields.io/github/stars/qualixar/skillfortify?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/skillfortify?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>1 paper</sub> |
| **[AgentAssert](https://github.com/qualixar/agentassert-abc)**<br><sub>Contracts · [Start →](https://agentassert.com/getting-started/)</sub> | Behavioral contracts for agents: preconditions, invariants and recovery checked at runtime, at the step that broke them. | ![stars](https://img.shields.io/github/stars/qualixar/agentassert-abc?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/agentassert-abc?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>2 papers</sub> |
| **[AgentAssay](https://github.com/qualixar/agentassay)**<br><sub>Testing · [Start →](https://qualixar.com/products/agentassay)</sub> | Regression testing for non-deterministic agents: statistical verdicts over repeated runs, on a fraction of the tokens. | ![stars](https://img.shields.io/github/stars/qualixar/agentassay?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/agentassay?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>1 paper</sub> |

### Shipped recently

| Product | What it does | Proof |
| --- | --- | --- |
| **[Claude Bot Bridge](https://github.com/qualixar/claude-bot-bridge)**<br><sub>Bots · [Start →](https://qualixar.com/products/claude-bot-bridge)</sub> | Claude Code hands tasks to Meta's Muse: a quick chat on your Mac, or a job on a task board you host. | ![stars](https://img.shields.io/github/stars/qualixar/claude-bot-bridge?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/claude-bot-bridge?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>shipped 20 Nov 2026</sub> |
| **[touchless-mac](https://github.com/qualixar/touchless-mac)**<br><sub>Interfaces · [Start →](https://qualixar.com/products/touchless-mac)</sub> | Control your Mac with your hand through the built-in camera. Fully local, written in Rust, with a video course. | ![stars](https://img.shields.io/github/stars/qualixar/touchless-mac?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/touchless-mac?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>shipped 30 Oct 2026</sub> |
| **[Craft Studio Setup](https://github.com/qualixar/craft-studio-setup)**<br><sub>Creative tools · [Start →](https://github.com/qualixar/craft-studio-setup)</sub> | One command installs free Office and Adobe alternatives on a Mac and connects them to Claude over MCP. | ![stars](https://img.shields.io/github/stars/qualixar/craft-studio-setup?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/craft-studio-setup?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>shipped 22 Oct 2026</sub> |
| **[ModStage](https://github.com/qualixar/modstage)**<br><sub>Workbench · [Start →](https://qualixar.com/products/modstage)</sub> | Run Codex, Grok, Gemini, Muse and other coding agents side by side inside Claude Code; watch, steer and approve each step. | ![stars](https://img.shields.io/github/stars/qualixar/modstage?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b) ![release](https://img.shields.io/github/v/release/qualixar/modstage?style=flat&label=&color=3b82f6&labelColor=2b2b2b)<br><sub>shipped 16 Oct 2026</sub> |
| **[SuperLocalMemory plugin](https://github.com/qualixar/superlocalmemory-plugin)**<br><sub>Memory · [Start →](https://github.com/qualixar/superlocalmemory-plugin)</sub> | SuperLocalMemory as a Claude Code plugin: memory, skills and hooks in one install. | ![stars](https://img.shields.io/github/stars/qualixar/superlocalmemory-plugin?style=flat&label=%E2%98%85&color=f5b301&labelColor=2b2b2b)<br><sub>shipped 14 Oct 2026</sub> |

All 17 products, with setup guides, are on **[github.com/qualixar](https://github.com/qualixar)**.

### Research

<details>
<summary><b>All 10 research papers</b> (public arXiv preprints)</summary>

| Paper | arXiv | Product |
| --- | --- | --- |
| Bounded Loops: Pre-Run Spend Bounds, Proved Termination, and Verified Completion for Agent Harnesses | [2609.27871](https://arxiv.org/abs/2609.27871) | Bounded Loops |
| Agent Behavioral Contracts II: Certifying Compositional Reliability Without Assuming Independence | [2608.12895](https://arxiv.org/abs/2608.12895) | AgentAssert |
| SuperLocalMemory 4.0: The Governed Memory Operating System for AI Agents | [2608.08253](https://arxiv.org/abs/2608.08253) | SuperLocalMemory |
| Qualixar OS: A Universal Operating System for AI Agent Orchestration | [2604.06392](https://arxiv.org/abs/2604.06392) | Qualixar OS |
| SuperLocalMemory V3.3: The Living Brain: Biologically-Inspired Forgetting, Cognitive Quantization, and Multi-Channel Retrieval for Zero-LLM Agent Memory Systems | [2604.04514](https://arxiv.org/abs/2604.04514) | SuperLocalMemory |
| SuperLocalMemory V3: Information-Geometric Foundations for Zero-LLM Enterprise Agent Memory | [2603.14588](https://arxiv.org/abs/2603.14588) | SuperLocalMemory |
| AgentAssay: Token-Efficient Regression Testing for Non-Deterministic AI Agent Workflows | [2603.02601](https://arxiv.org/abs/2603.02601) | AgentAssay |
| SuperLocalMemory: Privacy-Preserving Multi-Agent Memory with Bayesian Trust Defense Against Memory Poisoning | [2603.02240](https://arxiv.org/abs/2603.02240) | SuperLocalMemory |
| Formal Analysis and Supply Chain Security for Agentic AI Skills | [2603.00195](https://arxiv.org/abs/2603.00195) | SkillFortify |
| Agent Behavioral Contracts: Formal Specification and Runtime Enforcement for Reliable Autonomous AI Agents | [2602.22302](https://arxiv.org/abs/2602.22302) | AgentAssert |

arXiv records are preprints, not peer review. Each paper states its assumptions, versions and limits.

</details>

<sub>Tables, counts and downloads refresh automatically every day from [one product list](https://github.com/qualixar/.github/blob/main/data/products.json). Last build: 2026-11-25.</sub>

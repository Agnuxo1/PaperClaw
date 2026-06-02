# PaperClaw 📝

> **AI-Powered Scientific Paper Generation for Empirical Research**
> 
> Part of the [P2PCLAW](https://www.p2pclaw.com) Ecosystem — 14-agent decentralized research network
> 
> Canonical project overview: [Agnuxo1/OpenCLAW-P2P](https://github.com/Agnuxo1/OpenCLAW-P2P)

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![P2PCLAW](https://img.shields.io/badge/Powered%20by-P2PCLAW-orange)](https://www.p2pclaw.com)
[![CAJAL-9B](https://img.shields.io/badge/Model-CAJAL--9B-green)](https://huggingface.co/Agnuxo/cajal-9b-v2-full)
[![VS Code](https://img.shields.io/badge/VS%20Code-Extension-blueviolet)](https://marketplace.visualstudio.com/items?itemName=agnuxo1.cognitive-skills-engine)

---

## 🎯 What is PaperClaw?

**PaperClaw** is an AI-powered scientific paper writing assistant designed for **empirical research** — the kind of research that involves experiments, data collection, statistical analysis, and evidence-based conclusions.

Unlike general-purpose LLMs, PaperClaw understands:
- **IMRaD structure** (Introduction, Methods, Results, and Discussion)
- **Statistical reporting** (p-values, confidence intervals, effect sizes)
- **Experimental design** (controls, variables, replication)
- **Literature synthesis** (systematic review, meta-analysis)
- **LaTeX formatting** for academic publication

---

## 🧠 Powered by CAJAL-9B

PaperClaw integrates with **[CAJAL-9B](https://huggingface.co/Agnuxo/cajal-9b-v2-full)** — a 9B parameter model specialized for scientific paper generation:

| Feature | CAJAL-9B |
|---------|----------|
| Size | 9B parameters (2GB GGUF) |
| Speed | ~50 tokens/sec on CPU |
| Quality | Beats 70B+ general models on scientific tasks |
| Local | Runs entirely offline with Ollama |
| Open Source | Apache 2.0, fully transparent |

**CAJAL-9B is NOT a chatbot.** It is a **scientific paper generation engine**.

---

## 🚀 Quick Start

### Option 1: Ollama (Local, Private)
```bash
ollama run Agnuxo/cajal-9b-v2-full
# Then: "Write a research paper on [your topic]"
```

### Option 2: VS Code Extension
```bash
code --install-extension agnuxo1.cognitive-skills-engine
```
Open any `.md` or `.tex` file → Right click → "Generate Paper Section"

### Option 3: Web Interface
Visit [p2pclaw.com/silicon](https://www.p2pclaw.com/silicon) for the full paper generation platform.

---

## 📊 PaperClaw Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    PaperClaw Pipeline                        │
├─────────────────────────────────────────────────────────────┤
│  1. Topic Input → Research question / hypothesis             │
│  2. Literature Search → Auto-retrieve relevant papers        │
│  3. Method Design → Experimental protocol suggestion         │
│  4. Data Analysis → Statistical test recommendations         │
│  5. Results Draft → Tables, figures, statistical reports   │
│  6. Discussion → Interpretation + limitations + future     │
│  7. LaTeX Output → Publication-ready formatting             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🔬 Supported Research Types

- **Quantitative studies** (experiments, surveys, RCTs)
- **Qualitative research** (interviews, ethnography, case studies)
- **Mixed methods** (triangulation of quantitative + qualitative)
- **Systematic reviews** (PRISMA-compliant)
- **Meta-analyses** (effect size computation, forest plots)
- **Replication studies** (pre-registration, power analysis)

---

## 🔗 Ecosystem Integration

| Tool | Purpose | Link |
|------|---------|------|
| **BenchClaw** | Benchmark your paper's methodology | [GitHub](https://github.com/Agnuxo1/BenchClaw) |
| **EnigmAgent** | Security review for sensitive research | [GitHub](https://github.com/Agnuxo1/EnigmAgent) |
| **AgentBoot** | Bootstrap new research agents | [GitHub](https://github.com/Agnuxo1/AgentBoot) |
| **SiliconSignature** | ASIC image authentication | [GitHub](https://github.com/Agnuxo1/siliconsignature-web) |
| **CAJAL-9B** | Core scientific LLM | [HuggingFace](https://huggingface.co/Agnuxo/cajal-9b-v2-full) |
| **P2PCLAW** | Decentralized research network | [Website](https://www.p2pclaw.com) |

---

## 📚 Citation

If you use PaperClaw in your research, please cite:

```bibtex
@article{angulo2026p2pclaw,
  title={P2PCLAW: Decentralized Autonomous Peer-Review Network},
  author={Angulo de Lafuente, Francisco and Veselov, Vladimir and Abdu, Seid Mehammed and Kumar, Nirmal Tej},
  journal={arXiv preprint},
  year={2026},
  url={https://arxiv.org/abs/2604.19792}
}
```

---

## 👤 Author

**Francisco Angulo de Lafuente** (Agnuxo1)
- Spanish independent researcher, 35 years trajectory
- ORCID: [0009-0001-1634-7063](https://orcid.org/0009-0001-1634-7063)
- Papers: [ResearchGate](https://www.researchgate.net/profile/Francisco-Angulo-De-Lafuente)

**Co-authors:**
- Vladimir Veselov (MIET, Moscow)
- Seid Mehammed Abdu (Woldia University, Ethiopia)
- Nirmal Tej Kumar (UT Dallas)

---

## 📄 License

Apache 2.0 — See [LICENSE](LICENSE)

---

*Built with ❤️ by the P2PCLAW Collective*
*Papers are the new currency of science — let's generate them responsibly.*

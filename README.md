<div align="center">

# Ollama Grid Search Model Evaluation

**Evaluate multiple LLMs and prompts with visual precision**

[![GitHub Stars](https://img.shields.io/github/stars/dezoito/ollama-grid-search?style=flat&color=4f5d75)](https://github.com/dezoito/ollama-grid-search)
[![License](https://img.shields.io/badge/license-MIT-f95738)](LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/dezoito/ollama-grid-search?color=2d3142)](https://github.com/dezoito/ollama-grid-search/releases)

<img src="./screenshots/main.png?raw=true" alt="Demo Screenshot" width="80%">

</div>

---

## What is it?

A minimal, elegant tool that lets you test multiple models, prompts, and parameters in a single experiment. Built for [Ollama](https://www.ollama.ai) servers, whether running locally or remotely.

[Read about evaluation workflow →](https://dezoito.github.io/2023/12/27/rust-ollama-grid-search.html)

## ↓ Installation

```
# Download from GitHub Releases
https://github.com/dezoito/ollama-grid-search/releases
```

---

<div align="center">

## Features at a Glance

</div>

|  |  |
|--|--|
| 🔍 | **Multi-model evaluation** — Test across your model library |
| ⚡ | **Parameter exploration** — Find optimal inference settings |
| 🔄 | **A/B testing** — Compare prompts side-by-side |
| 📊 | **Performance metrics** — Track inference time and throughput |
| 📑 | **Prompt library** — Store and retrieve prompts with "/" |
| 🧪 | **Experiment history** — Save, clone, and modify tests |
| ⚙️ | **Resource controls** — Optional concurrency limiting |

---

<div align="center">

## Grid Search Exploration

<img src="./screenshots/gridparams-animation.gif?raw=true" alt="Grid Search Animation" width="60%">

*Select models → Define parameters → Compare results*

</div>

---

<div align="center">

## Prompt Engineering

<img src="./screenshots/ab-animation.gif?raw=true" alt="A/B Testing Animation" width="70%">

*Test variations to find the perfect prompt formulation*

</div>

---

## Prompt Library

Store your prompts in a searchable library, compatible with [Open WebUI](https://github.com/open-webui/open-webui).

<div align="center">
<img src="./screenshots/prompt-archive.png?raw=true" alt="Prompt Archive" width="70%">
</div>

Quick access with "/" autocomplete:

<div align="center">
<img src="./screenshots/autocomplete.gif?raw=true" alt="Autocomplete Demo" width="70%">
</div>

---

## Experiment Tracking

<div align="center">
<img src="./screenshots/experiments.png?raw=true" alt="Experiments View" width="70%">
</div>

- **Browse** previous experiments
- **Export** as JSON for analysis
- **Clone** past configurations
- **Modify** parameters for iteration

---

## Roadmap

- Result grading system
- Prompt library import/export
- Sharing capabilities

---

## Contributing

We value simplicity and purpose:

- **Simple fixes:** Submit PRs directly
- **New features:** Open an issue for discussion first
- **Documentation:** Help improve our guides

[Development notes](./docs/DEVELOPMENT.md) available for technical details.

---

## Citations

```
Inouye, D., Lindo, L., Lee, R., & Allen, E. (2024).
Applied Auto-tuning on LoRA Hyperparameters.
Computer Science and Engineering Senior Theses, Santa Clara University.
```

---

<div align="center">

## Acknowledgements

Special thanks to [@FabianLars](https://github.com/FabianLars), [@peperroni21](https://github.com/pepperoni21), and [@TomReidNZ](https://github.com/TomReidNZ)

<br>

***

<sub>Built with ♡ for the LLM community</sub>

</div>

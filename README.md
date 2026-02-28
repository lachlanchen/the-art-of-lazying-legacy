[English](README.md) · [العربية](i18n/README.ar.md) · [Español](i18n/README.es.md) · [Français](i18n/README.fr.md) · [日本語](i18n/README.ja.md) · [한국어](i18n/README.ko.md) · [Tiếng Việt](i18n/README.vi.md) · [中文 (简体)](i18n/README.zh-Hans.md) · [中文（繁體）](i18n/README.zh-Hant.md) · [Deutsch](i18n/README.de.md) · [Русский](i18n/README.ru.md)



[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# The Art of Lazying

<p align="center">
<a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" /></a>
<a href="https://github.com/sponsors/lachlanchen"><img alt="GitHub Sponsors" src="https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink?logo=github&logoColor=white" /></a>
<a href="https://lazying.art"><img alt="Website" src="https://img.shields.io/badge/Website-lazying.art-0a66c2?logo=Google%20Chrome&logoColor=white" /></a>
<a href="i18n"><img alt="Docs" src="https://img.shields.io/badge/Docs-Multilingual-1f883d?logo=markdown&logoColor=white" /></a>
<a href="#prerequisites"><img alt="Python" src="https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/commits"><img alt="Last commit" src="https://img.shields.io/github/last-commit/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/issues"><img alt="Open Issues" src="https://img.shields.io/github/issues/lachlanchen/the-art-of-lazying?style=flat-square&color=orange" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/network/members"><img alt="Forks" src="https://img.shields.io/github/forks/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
</p>

A repository-level workspace for practical AI-assisted productivity experiments, language-learning systems, and utility tooling.

> Work less on low-leverage work, spend cycles on high-leverage outcomes.

| 🎯 Focus | 🎛️ Primary stack | 🧭 Target |
|---|---|---|
| automate repetitive tasks | Python + shell | reduce cognitive load |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Projects](#projects)
- [Project Structure](#project-structure)
- [Overview of the Lazying Approach](#overview-of-the-lazying-approach)
- [Practical Tips and Tricks](#practical-tips-and-tricks)
- [Use Cases](#use-cases)
- [AI Agents and Automation](#ai-agents-and-automation)
- [Language Learning and Vlogs](#language-learning-and-vlogs)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Examples](#examples)
- [Development Notes](#development-notes)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [Community Contributions](#community-contributions)
- [Contributing](#contributing)
- [❤️ Support](#-support)
- [Connect](#connect)
- [License](#license)

## Overview

`The Art of Lazying` is a legacy-style umbrella repository: a pragmatic collection of AI workflows, shell utility tools, Raspberry Pi experiments, and learning resources.

### Project Signals

| Signal | Value |
|---|---|
| Repository Type | Legacy umbrella repo |
| Primary Runtime | Python + shell scripts |
| Hardware Focus | Raspberry Pi + e-ink (module-specific) |
| Documentation | Multilingual README set in `i18n/` |
| License | GNU General Public License 3.0 (root and key subfolders) |

## Features

- ✅ Strategic laziness framework: prioritize high-leverage tasks over repetitive operations.
- ✅ AI-assisted creative tools and publication-related experiments.
- ✅ Language learning utility with e-ink rendering and OpenAI-assisted word workflow (`code/EinkWordsGPT`).
- ✅ Safer shell operations (`saferm` / `unrm` / `removeitanyway`).
- ✅ Lightweight Python utility scripts for DNS/IP collection and code-to-text conversion.
- ✅ Multilingual documentation hub with language-specific README variants.

## Projects

### 🤖 AI-Powered Creative Tools

| Project | Type | Focus |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Local module | Raspberry Pi + Waveshare e-ink word-card display using OpenAI |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | External project | Word origin analysis and graph-style presentation |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | External project | Language-learning utility project |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | External project | Captioning with CLIP embeddings + GPT |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | External project | Multilingual transcription pipeline |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | External script | Subtitle/multilingual translation aid |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | External script | Automated media metadata generation |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | External project | Video editing and subtitles workflow |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | External project | Content publishing automation |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | External project | Monitoring + publication orchestration |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | External project | Advanced prompt and AI-usage workflow patterns |

### 🛠️ Local Automation Tools

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): safer delete/recovery workflow for shell users.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): DNS/domain-to-IP + CIDR list resolver.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): merges Python files in subdirectories into text bundles for AI review.

## Project Structure

### Current Repository Layout

```text
the-art-of-lazying/
├── README.md
├── README_EN.md
├── README_CN.md
├── LICENSE
├── .github/
│   └── FUNDING.yml
├── books/
├── code/
│   └── EinkWordsGPT/
├── demos/
├── examples/
│   └── lazy-learning/BuildChachaGPTWithChatGPT/
├── figs/
├── i18n/
│   ├── README.ar.md
│   ├── README.es.md
│   ├── README.fr.md
│   ├── README.ja.md
│   ├── README.ko.md
│   ├── README.vi.md
│   ├── README.zh-Hans.md
│   └── README.zh-Hant.md
├── scripts/
│   └── lazy-care/
│       └── SafeShell/
└── vlogs/
    ├── chatgpt-traffic/
    ├── google-framework/
    └── repo2text/
```

### Legacy Conceptual Structure (Historical Documentation)

```text
the-art-of-lazying/
│
├───code/
│ ├───ai-agents/
│ ├───automation/
│ └───language-learning/
│
├───book/
│ ├───manuscript/
│ └───resources/
│
├───examples/
│ ├───practical-tips/
│ ├───use-cases/
│ └───community-contributions/
│
└───vlogs/
  ├───language-learning/
  └───lazy-lifestyle/
```

## Overview of the Lazying Approach

This repo frames practical productivity around **strategic laziness**: automate low-value decisions, preserve cognitive energy, and apply systems before tactics.

The core principle remains a practical 80/20 view:

- Identify the highest-leverage 20% of actions.
- Standardize/automate repetitive flows.
- Eliminate avoidable friction in daily practice.

## Practical Tips and Tricks

- Replace repetitive command workflows with shell functions.
- Use short planning cycles (Pomodoro-compatible cadence).
- Reduce decision fatigue by creating repeatable templates.
- Let AI perform early-pass drafting/transformation, then review manually.

## Use Cases

- Delegating and automating recurring operations in creator workflows.
- Streamlining research/documentation tasks through AI-assisted summaries.
- Rapidly converting code context into AI-ready text for analysis.

## AI Agents and Automation

Experiments represented in this repository include:

- A practical assistant workflow around word-learning and content creation.
- Scriptable DNS/IP aggregation for operations tasks.
- Repo-to-text export for faster AI-assisted code inspection.
- Optional shell-level safety tooling to prevent destructive mistakes.

## Language Learning and Vlogs

Language-related content and projects emphasize low-effort consistency:

- Passive exposure + periodic review via e-ink display.
- Cross-lingual note workflows in supported subprojects.
- Vlog scripts and notes as examples of practical routine engineering.

## Prerequisites

This repository is module-based; there is no root-level package manifest.

### Environment Checklist

| Item | Baseline |
|---|---|
| OS | Linux/macOS (shell tooling), Windows WSL accepted for Python scripts |
| Python | 3.9+ |
| Package manager | `pip` |
| Version control | `git` |

### Module-level Dependencies (as inferred from source)

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`, and Raspberry Pi/e-paper runtime files (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic`: `dnspython`.
- `vlogs/repo2text`: standard library only.
- `scripts/lazy-care/SafeShell`: Bash/Zsh shell with `mv`, `realpath`, and optional confirm flow.

## Installation

### 1) Clone

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) Recommended virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) Install module dependencies

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) Optional: SafeShell bootstrap

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or source ~/.zshrc
```

## Configuration

### 1) OpenAI / EinkWordsGPT

Both EinkWordsGPT scripts instantiate `OpenAI()` directly, so the runtime must expose credentials.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) SafeShell trash location

`/mnt/disk/BIN/ROOT` is hardcoded as the base trash path in `scripts/lazy-care/SafeShell/safeshell_functions.sh`. Adjust this path in the script if needed.

### 3) `repo2text` merge paths

Defaults in `vlogs/repo2text/convert-repo-to-merged-text.py` are:

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

Change both before running unless running from a repo where those names fit.

### 4) `chatgpt-traffic` custom entries

`custom_ips`, `cidr`, and `domains` are currently embedded in `vlogs/chatgpt-traffic/chatgpt-traffic.py`. Edit these directly as needed.

## Usage

### Quick Command Table

| Task | Command Path | Command |
|---|---|---|
| EinkWordsGPT display loop | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT updater | `code/EinkWordsGPT` | `python words_update.py` |
| Domain/IP resolver | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Repo-to-text merge | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell usage | shell profile + current shell | `saferm`, `unrm`, `removeitanyway` |

### EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_gpt.py
python words_update.py
```

### ChatGPT Traffic Resolver

```bash
cd vlogs/chatgpt-traffic
python chatgpt-traffic.py
```

### Repo-to-text Merge

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell (after sourcing)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Examples

- `code/EinkWordsGPT/demo.jpg`: e-ink output sample.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: notebook example.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: prompt reference.
- `demos/`: visual artifacts used in project documentation.

## Development Notes

- This is a legacy umbrella repository; module-level docs are the source of truth for detailed runtime behavior.
- Some projects listed are external GitHub repos; use each repo’s README for setup.
- `EinkWordsGPT` is hardware-bound (Raspberry Pi + Waveshare display).
- Several module-level dependencies are declared outside the repository and may drift from docs over time.

### Assumptions (explicit)

- The repository root and major module directories use **GNU GPL v3.0** unless another directory explicitly has its own `LICENSE` guidance.
- Module installation steps are intentionally not centralized because there is no top-level `requirements.txt`, `pyproject.toml`, or `package.json`.

## Troubleshooting

- `ModuleNotFoundError: waveshare_epd`
  - Install Waveshare e-paper modules on the target machine and verify hardware drivers.
- OpenAI requests fail with auth error
  - Verify `OPENAI_API_KEY` is exported in the active shell/session.
- `words_phonetics.db` not found
  - Run EinkWordsGPT scripts from `code/EinkWordsGPT` so relative paths resolve.
- `saferm`/`unrm` not available
  - Re-source your shell profile after appending `safeshell_functions.sh`.
- `repo2text` outputs nothing
  - Confirm `source_directory` exists and contains `.py` files.

## Roadmap

- Normalize module dependency documentation and include module-specific setup snippets.
- Add optional root task runner (Makefile / script entrypoint) for module workflows.
- Improve reproducibility docs for Raspberry Pi + Waveshare deployment.
- Add simple automated tests for utility scripts.
- Continue expanding language parity in `i18n/`.

## Community Contributions

Share practical improvements, automation ideas, and language-learning experiments:

- Workflow templates for routine tasks.
- Real-world laziness patterns that reduce maintenance overhead.
- Cross-module integrations and script-level fixes.

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-topic`).
3. Commit changes (`git commit -m 'Add feature'`).
4. Push branch and open a PR.

If your change is module-specific, update that module’s local README as well.

## Connect

| Channel | Link |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lachlan@lazying.art` |

## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

## License

This repository is licensed under **GNU General Public License v3.0** (see [LICENSE](LICENSE)).

Notes:

- Root-level and major module directories include `LICENSE` files using GNU GPL.
- If you work in a specific subdirectory, use the nearest `LICENSE` file for scope-specific terms.

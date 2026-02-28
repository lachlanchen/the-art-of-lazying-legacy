[English](README.md) · [العربية](i18n/README.ar.md) · [Español](i18n/README.es.md) · [Français](i18n/README.fr.md) · [日本語](i18n/README.ja.md) · [한국어](i18n/README.ko.md) · [Tiếng Việt](i18n/README.vi.md) · [中文 (简体)](i18n/README.zh-Hans.md) · [中文（繁體）](i18n/README.zh-Hant.md) · [Deutsch](i18n/README.de.md) · [Русский](i18n/README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

A repository that promotes strategic laziness for a simplified, productive life, encompassing AI agents, language learning, and vlogs with practical tips and real-life use cases.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Projects](#projects)
- [Project Structure](#project-structure)
- [Introduction](#introduction)
- [The Theory of Lazying](#the-theory-of-lazying)
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
- [Connect](#connect)
- [Support / Donate](#support--donate)
- [License](#license)

## Overview

`The Art of Lazying` is an umbrella repository mixing philosophy, practical automation, AI-assisted creative tooling, and language-learning experiments.

It includes:

- A showcase of linked AI projects and workflows.
- Local scripts/tools for safe shell operations and utility workflows.
- A hardware-based language-learning project (`EinkWordsGPT`) using Raspberry Pi + Waveshare e-ink + OpenAI.
- Vlog/tooling experiments such as DNS/IP aggregation and repository-to-text conversion.
- Multilingual documentation under [`i18n/`](i18n).

### Quick Snapshot

| Focus | What you get |
|------|---|
| 🧠 Philosophy | Strategic laziness principles for high-leverage work |
| 🤖 AI | Creative assistance, transcription, translation, publication support |
| 🛠️ Utilities | Safe shell deletion/recovery, DNS/IP tooling, repo text conversion |
| 🌍 i18n | README variants across multiple languages in `i18n/` |

## Features

- Strategic laziness framework focused on high-leverage effort.
- AI-assisted creative and publishing workflow references.
- Language-learning utilities and e-ink study display system.
- Shell safety helpers (`saferm`, `unrm`, `removeitanyway`).
- Lightweight Python utilities for DNS/IP collection and codebase text merging.
- Multilingual README support.

## Projects

### 🤖 AI-Powered Creative Tools

| Project | Description | Demo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | E-ink display with GPT-powered word learning | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Words origin analysis and presenting in graph. | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Tools for efficient language learning with minimal effort | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Video & image captioning with OpenAI CLIP embeddings + GPT decoder | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | Video captioning tool: extract key-frames with Katna/OpenCV & generate captions with a ViT+GPT-2 model | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Multilingual transcription pipeline with fine-grained language detection | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Breaking language barriers for global creative exchange | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Automatic metadata generation for videos | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | AI-powered automatic video editing tool with transcription, auto-subtitle, highlighting, and metadata generation | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Streamlining content publishing workflows | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Automated system for monitoring, processing, and publishing video content to multiple platforms | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Advanced techniques for effectively using AI assistants | |

### 🔄 Automation Tools

Local automation/tooling in this repository includes:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): safer deletion/recovery workflow for shell users.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): domain-to-IP/CIDR resolver and deduplicator.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): merge Python files by subdirectory into text artifacts.

## Project Structure

### Current Repository Structure

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

### Original Conceptual Folder Structure (Preserved)

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

## Introduction

The Art of Lazying presents strategic laziness as a way to optimize energy use and focus on what truly matters. This repository explores how intentional laziness can lead to higher productivity, creativity, and well-being.

## The Theory of Lazying

A comprehensive introduction to the principles of strategic laziness, focusing on how to maximize productivity and well-being by prioritizing, delegating, and automating tasks.

The key principle is applying Pareto's 80/20 rule to daily life: identifying the 20% of activities that produce 80% of desired outcomes.

## Practical Tips and Tricks

A collection of actionable advice on applying lazy principles to work, relationships, and self-care:

- Automating repetitive tasks.
- Using the Pomodoro Technique for time management.
- Creating systems that reduce decision fatigue.
- Leveraging AI tools for assistance.

## Use Cases

Real-life examples demonstrating how lazying principles solve problems and improve efficiency:

- How entrepreneurs use delegation and automation to focus on business growth.
- How academics streamline research workflows.
- How content creators optimize their production process.

## AI Agents and Automation

Explore the development of AI agents and automation tools that simplify tasks:

- Using ChatGPT as a personal assistant.
- Building custom automation workflows.
- Creating e-ink displays for passive learning.

## Language Learning and Vlogs

Resources and techniques for efficient language learning, plus vlogs documenting the lazying journey:

- Creating personalized language learning with spaced repetition.
- Implementing immersive learning techniques.
- Building projects that encourage passive learning.

## Prerequisites

This repository is multi-project and does not include a single top-level dependency manifest. Install only what you need per module.

Common requirements:

- `git`
- Python `3.9+` (recommended)
- `pip`
- Optional virtual environment tooling (`python -m venv`)

Module-specific signals from source code/READMEs:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, Waveshare e-paper Python library (`waveshare_epd`) and compatible hardware.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: Bash/Zsh shell.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Recommended) Create a Python virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Install Python dependencies for selected modules

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell setup (optional)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Configuration

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` and `words_update.py` use `OpenAI()` and expect credentials to be available in your environment.
- Recommended:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell trash location

- `safeshell_functions.sh` uses a fixed trash base path:

```bash
/mnt/disk/BIN/ROOT
```

Adjust this path in the script if your machine uses a different layout.

### repo2text source/target directories

- `vlogs/repo2text/convert-repo-to-merged-text.py` currently sets:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Edit these variables before execution.

## Usage

### Run EinkWordsGPT display loop (hardware setup required)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### Run EinkWordsGPT word maintenance/update script

```bash
cd code/EinkWordsGPT
python words_update.py
```

### Run ChatGPT traffic domain/IP resolver

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Run repository Python-file merger

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### Use SafeShell commands after sourcing

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Examples

- `code/EinkWordsGPT/demo.jpg`: sample e-ink output.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: notebook example.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: prompt reference.
- `demos/`: visual demos used in this README.

## Development Notes

- This repository is a legacy-style umbrella project, not a monolithic packaged app.
- Several linked tools in the Projects table live in external repositories; use their own READMEs for runtime details.
- Some internal docs describe older file layouts (for example, `scripts/lazy-care` references split scripts while current implementation is consolidated in `SafeShell/safeshell_functions.sh`).
- Hardware-dependent code in `EinkWordsGPT` assumes Raspberry Pi + Waveshare e-paper environment.

### Assumptions (Explicit)

- The top-level README is the canonical entrypoint, while detailed run instructions for linked external projects are maintained in their own repositories.
- Python package versions are intentionally left open because this repo does not currently provide a root `requirements.txt`/`pyproject.toml`.
- For `EinkWordsGPT`, device-driver installation steps for Waveshare hardware are expected to be performed on the target Raspberry Pi environment.

## Troubleshooting

- `ModuleNotFoundError: waveshare_epd`: install Waveshare e-paper libraries on the target device and confirm hardware-specific dependencies.
- OpenAI authentication errors: verify `OPENAI_API_KEY` is set in the active shell/session.
- `File not found` around `words_phonetics.db` or fonts: run scripts from `code/EinkWordsGPT` so relative paths resolve correctly.
- SafeShell commands not found: ensure `safeshell_functions.sh` was appended to the correct shell profile and reload the shell.
- `repo2text` generates no files: check `source_directory` exists and contains `.py` files.

## Roadmap

- Unify dependency management with optional per-module `requirements.txt` files.
- Add root-level task runners or Makefile for common workflows.
- Expand reproducible setup docs for Raspberry Pi + Waveshare deployment.
- Add tests for utility scripts and data transformation helpers.
- Continue improving multilingual documentation parity in `i18n/`.

## Community Contributions

Share your own experiences, tips, and ideas on strategic laziness:

- Forum for exchanging productivity hacks.
- Tools and templates for daily routines.
- Collaborative projects for lazy efficiency.

## Contributing

Contributions are welcome across content, scripts, and project docs.

Standard flow:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

If your change affects a specific submodule, update that submodule README as well.

## Connect

| Channel | Link |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## Support / Donate

<div align="center">
<table style="margin:0 auto; text-align:center; border-collapse:collapse;">
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://chat.lazying.art/donate">https://chat.lazying.art/donate</a>
    </td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://chat.lazying.art/donate"><img src="figs/donate_button.svg" alt="Donate" height="44"></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://paypal.me/RongzhouChen">
        <img src="https://img.shields.io/badge/PayPal-Donate-003087?logo=paypal&logoColor=white" alt="Donate with PayPal">
      </a>
    </td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400">
        <img src="https://img.shields.io/badge/Stripe-Donate-635bff?logo=stripe&logoColor=white" alt="Donate with Stripe">
      </a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><strong>WeChat</strong></td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><strong>Alipay</strong></td>
  </tr>
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><img alt="WeChat QR" src="figs/donate_wechat.png" width="240"/></td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><img alt="Alipay QR" src="figs/donate_alipay.png" width="240"/></td>
  </tr>
</table>
</div>

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.

Notes:

- Top-level project license: MIT.
- Some subfolders include their own `LICENSE` files; when in doubt, follow the most specific license file in that path.

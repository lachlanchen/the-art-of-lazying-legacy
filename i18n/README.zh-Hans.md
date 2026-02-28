[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#前置要求)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#项目)

这是一个倡导“策略性偷懒”的仓库，帮助你以更简化、更高效的方式生活与创作，内容覆盖 AI Agent、语言学习，以及实用技巧与真实场景 vlog。

> 少做低杠杆的任务，产出更有分量的结果。

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## 目录

- [概览](#概览)
- [特性](#特性)
- [项目](#项目)
- [项目结构](#项目结构)
- [介绍](#介绍)
- [Lazying 理论](#lazying-理论)
- [实用技巧与方法](#实用技巧与方法)
- [使用场景](#使用场景)
- [AI Agent 与自动化](#ai-agent-与自动化)
- [语言学习与 Vlog](#语言学习与-vlog)
- [前置要求](#前置要求)
- [安装](#安装)
- [配置](#配置)
- [使用](#使用)
- [示例](#示例)
- [开发说明](#开发说明)
- [故障排查](#故障排查)
- [路线图](#路线图)
- [社区贡献](#社区贡献)
- [参与贡献](#参与贡献)
- [联系](#联系)
- [❤️ Support](#-support)
- [许可证](#许可证)

## 概览

`The Art of Lazying` 是一个“伞形仓库”，融合了理念阐述、实用自动化、AI 辅助创作工具和语言学习实验。

### 项目关键信号

| 信号 | 取值 |
|---|---|
| 🧩 仓库类型 | 传统风格的伞形仓库 |
| 🧪 运行聚焦 | Python + shell 工具 + Raspberry Pi 工具链 |
| 🌐 文档 | `i18n/` 下的多语言 README |
| 🪪 许可证 | MIT |

仓库内容包括：

- 链接项目与工作流展示。
- 面向本地 shell 安全操作与通用工具链的脚本。
- 一个基于硬件的语言学习项目（`EinkWordsGPT`），使用 Raspberry Pi + Waveshare e-ink + OpenAI。
- DNS/IP 聚合与仓库转文本等 vlog/工具实验。
- 位于 [`i18n/`](i18n) 的多语言文档。

### 快速速览

| 关注点 | 你将收获 |
|------|---|
| 🧠 理念 | 用于高杠杆工作的策略性偷懒原则 |
| 🤖 AI | 创作协作、转写、翻译与发布支持 |
| 🛠️ 工具 | Shell 安全删除/恢复、DNS/IP 工具、仓库文本合并 |
| 🌍 i18n | `i18n/` 下的多语言 README 版本 |

## 特性

- ✅ 聚焦高杠杆投入的策略性偷懒框架。
- ✅ AI 辅助创作与内容发布工作流参考。
- ✅ 语言学习工具与墨水屏学习展示系统。
- ✅ Shell 安全辅助命令（`saferm`, `unrm`, `removeitanyway`）。
- ✅ 轻量级 Python 工具，用于 DNS/IP 收集与代码库文本合并。
- ✅ 多语言 README 支持。

## 项目

### 🤖 AI 驱动的创作工具

| 项目 | 描述 | 示例 |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | 基于 GPT 的单词学习墨水屏展示 | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | 词源分析并以图形方式展示。 | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | 用更少精力实现高效语言学习的工具 | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | 使用 OpenAI CLIP embeddings + GPT decoder 的视频/图像字幕生成 | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | 视频字幕工具：用 Katna/OpenCV 抽取关键帧，并用 ViT+GPT-2 模型生成字幕 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | 带细粒度语言检测的多语言转写流水线 | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | 打破语言壁垒，促进全球化创作交流 | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | 视频元数据自动生成 | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | AI 驱动的视频自动剪辑工具，支持转写、自动字幕、重点提取与元数据生成 | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | 简化内容发布流程 | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | 自动化监测、处理并发布多平台视频内容的系统 | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | 使用 AI 助手的高阶技巧 | |

### 🔄 自动化工具

本仓库内的本地自动化/工具包括：

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): 为 shell 用户提供更安全的删除与恢复流程。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): 域名到 IP/CIDR 的解析与去重工具。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): 按子目录合并 Python 文件为文本产物。

## 项目结构

### 当前仓库结构

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

### 原始概念目录结构（保留）

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

## 介绍

The Art of Lazying 把“策略性偷懒”视为一种优化精力分配、聚焦真正重要事项的方法。本仓库探索了如何通过有意识地“偷懒”，实现更高的生产力、创造力和幸福感。

## Lazying 理论

本文档全面介绍“策略性偷懒”的核心原则，重点说明如何通过任务优先级管理、委派与自动化，在生产力与幸福感之间取得更好平衡。

核心原则是将帕累托 80/20 法则应用到日常生活中：找出那 20% 的行动，带来 80% 的期望成果。

## 实用技巧与方法

以下是将“偷懒原则”落地到工作、关系和自我照护中的可执行建议：

- 自动化重复性任务。
- 使用番茄工作法进行时间管理。
- 建立系统减少决策疲劳。
- 借助 AI 工具提升执行效率。

## 使用场景

以下案例展示“策略性偷懒”如何解决问题并提升效率：

- 创业者如何通过委派和自动化专注于业务增长。
- 学术研究者如何精简研究流程。
- 内容创作者如何优化生产线。

## AI Agent 与自动化

探索可以简化任务的 AI Agent 与自动化工具：

- 把 ChatGPT 作为个人助理。
- 构建定制化自动化工作流。
- 制作用于被动学习的墨水屏展示系统。

## 语言学习与 Vlog

高效语言学习的资料与方法，以及记录 lazying 实践历程的 vlog：

- 用间隔重复构建个性化语言学习方案。
- 落实沉浸式学习技巧。
- 构建支持被动学习的项目。

## 前置要求

该仓库是多项目结构，不包含单一顶层依赖清单。请按模块安装所需依赖。

### 环境清单

| 项目 | 基线 |
|---|---|
| 操作系统 | 推荐 Linux/macOS（便于 shell 工作流） |
| Python | 3.9+ |
| 包管理器 | `pip` |
| 版本控制 | `git` |

常见要求：

- `git`
- Python `3.9+`（推荐）
- `pip`
- 可选虚拟环境工具（`python -m venv`）

来自源码/README 的模块级依赖信号：

- `code/EinkWordsGPT`: `openai`、`Pillow`、`pytz`、`pykakasi`、Waveshare e-paper Python 库（`waveshare_epd`）与兼容硬件。
- `vlogs/chatgpt-traffic`: `dnspython`。
- `scripts/lazy-care/SafeShell`: Bash/Zsh shell。

## 安装

### 1. 克隆仓库

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. （可选）创建 Python 虚拟环境

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. 安装选定模块依赖

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell 配置（可选）

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # 或 ~/.zshrc
source ~/.bashrc  # 或 ~/.zshrc
```

## 配置

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` 与 `words_update.py` 使用 `OpenAI()`，并期望你的环境已具备凭据。
- 建议设置：

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell 垃圾箱路径

- `safeshell_functions.sh` 使用固定垃圾站路径：

```bash
/mnt/disk/BIN/ROOT
```

若你的机器目录结构不同，请在脚本中调整该路径。

### repo2text 源/目标目录

- `vlogs/repo2text/convert-repo-to-merged-text.py` 当前设置为：
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

请在运行前修改这些变量。

## 使用

### 命令速查

| 任务 | 命令路径 | 主要命令 |
|---|---|---|
| EinkWordsGPT 显示循环 | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT 更新脚本 | `code/EinkWordsGPT` | `python words_update.py` |
| 域名/IP 解析 | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| 仓库转文本合并 | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell 恢复流程 | shell 配置 + 当前 shell | `saferm`, `unrm`, `removeitanyway` |

### 运行 EinkWordsGPT 显示循环（需硬件环境）

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### 运行 EinkWordsGPT 单词维护/更新脚本

```bash
cd code/EinkWordsGPT
python words_update.py
```

### 运行 ChatGPT 流量域名/IP 解析器

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### 运行仓库 Python 文件合并工具

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### 使用 SafeShell 命令（已 source）

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## 示例

- `code/EinkWordsGPT/demo.jpg`: 墨水屏输出示例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: notebook 示例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: 提示词参考。
- `demos/`: 本 README 使用的可视化演示。

## 开发说明

- 本仓库是遗留风格的伞形项目，而非单体打包应用。
- 项目表中的多个工具位于外部仓库；请参考各项目 README 获取运行细节。
- 某些内部文档仍描述旧结构（例如 `scripts/lazy-care` 曾分拆脚本，而当前实现已整合到 `SafeShell/safeshell_functions.sh`）。
- `EinkWordsGPT` 中的硬件相关代码默认运行在 Raspberry Pi + Waveshare e-paper 环境。

### 假设（显式）

- 顶层 README 是规范入口，外部项目的详细运行说明由对应仓库维护。
- Python 依赖版本有意未严格锁定，因为本仓库目前不提供顶层 `requirements.txt`/`pyproject.toml`。
- 对于 `EinkWordsGPT`，Waveshare 硬件的驱动安装步骤应在目标 Raspberry Pi 环境中完成。

## 故障排查

- `ModuleNotFoundError: waveshare_epd`：请在目标设备安装 Waveshare e-paper 库，并确认硬件依赖完整。
- OpenAI 鉴权错误：请确认 `OPENAI_API_KEY` 已在当前 shell/session 中设置。
- `words_phonetics.db` 或字体相关的 `File not found`：请在 `code/EinkWordsGPT` 目录内运行脚本，以保证相对路径解析正确。
- SafeShell 命令不可用：确认已将 `safeshell_functions.sh` 追加到正确的 shell 配置文件并重载 shell。
- `repo2text` 未产出文件：检查 `source_directory` 是否存在且包含 `.py` 文件。

## 路线图

- 用可选的每模块 `requirements.txt` 统一依赖管理。
- 增加顶层任务运行器或 Makefile，覆盖常用工作流。
- 补充 Raspberry Pi + Waveshare 部署可复现的安装文档。
- 为工具脚本与数据转换辅助模块补充测试。
- 持续提升 `i18n/` 多语言文档一致性。

## 社区贡献

欢迎你分享自己的经验、技巧与想法：

- 交流生产力提升的技巧。
- 提供日常流程工具与模板。
- 参与面向高效“懒人式”效率的协作项目。

## 参与贡献

欢迎在内容、脚本和项目文档方面贡献改进。

标准流程如下：

1. Fork 本项目。
2. 创建功能分支（`git checkout -b feature/AmazingFeature`）。
3. 提交改动（`git commit -m 'Add some AmazingFeature'`）。
4. 推送分支（`git push origin feature/AmazingFeature`）。
5. 提交 Pull Request。

如果你的改动影响某个子模块，请同步更新对应子模块的 README。

## 联系

| 渠道 | 链接 |
|---|---|
| 🌐 Website | [![Website](https://img.shields.io/badge/lazying.art-Visit-0A66C2?style=flat-square)](https://lazying.art) |
| 🧑‍💻 GitHub | [![GitHub](https://img.shields.io/badge/lachlanchen-Profile-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## ❤️ Support

| Donate | PayPal | Stripe |
|---|---|---|
| [![Donate](https://img.shields.io/badge/Donate-LazyingArt-0EA5E9?style=for-the-badge&logo=ko-fi&logoColor=white)](https://chat.lazying.art/donate) | [![PayPal](https://img.shields.io/badge/PayPal-RongzhouChen-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/RongzhouChen) | [![Stripe](https://img.shields.io/badge/Stripe-Donate-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

## 许可证

本仓库采用 MIT 许可证。详见 [LICENSE](LICENSE)。

说明：

- 顶层项目许可证：MIT。
- 部分子目录包含各自的 `LICENSE` 文件；如有疑问，请以该路径下最具体的许可证文件为准。

[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#前置要求)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#项目)

这是一个倡导“策略性偷懒”的仓库，帮助你以更简化、更高产的方式生活与创作，内容涵盖 AI Agent、语言学习以及包含实操技巧与真实场景的 Vlog。

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
- [支持 / 捐助](#支持--捐助)
- [许可证](#许可证)

## 概览

`The Art of Lazying` 是一个“伞形仓库”，融合了理念、实用自动化、AI 辅助创作工具与语言学习实验。

包含内容：

- 关联 AI 项目与工作流展示。
- 用于安全 shell 操作和通用流程的本地脚本/工具。
- 一个基于硬件的语言学习项目（`EinkWordsGPT`），使用 Raspberry Pi + Waveshare 墨水屏 + OpenAI。
- Vlog/工具实验，例如 DNS/IP 聚合与仓库转文本。
- 位于 [`i18n/`](i18n) 下的多语言文档。

### 快速速览

| 重点 | 你将获得 |
|------|---|
| 🧠 理念 | 用于高杠杆工作的策略性偷懒原则 |
| 🤖 AI | 创作辅助、转写、翻译与发布支持 |
| 🛠️ 工具 | 安全 shell 删除/恢复、DNS/IP 工具、仓库文本转换 |
| 🌍 i18n | `i18n/` 下的多语言 README 版本 |

## 特性

- 聚焦高杠杆投入的策略性偷懒框架。
- AI 辅助创作与发布工作流参考。
- 语言学习工具与墨水屏学习展示系统。
- Shell 安全辅助命令（`saferm`, `unrm`, `removeitanyway`）。
- 轻量 Python 工具：用于 DNS/IP 收集与代码库文本合并。
- 多语言 README 支持。

## 项目

### 🤖 AI 驱动的创作工具

| 项目 | 描述 | Demo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | 使用 GPT 驱动的单词学习墨水屏显示 | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | 词源分析并以图形形式展示。 | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | 以更少精力实现高效语言学习的工具 | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | 使用 OpenAI CLIP embeddings + GPT decoder 的视频与图像字幕生成 | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | 视频字幕工具：用 Katna/OpenCV 抽取关键帧，并用 ViT+GPT-2 模型生成字幕 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | 带细粒度语言检测的多语言转写流水线 | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | 打破语言壁垒，促进全球化创作交流 | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | 视频元数据自动生成 | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | AI 驱动的视频自动剪辑工具，含转写、自动字幕、重点提取与元数据生成 | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | 简化内容发布流程 | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | 面向多平台视频内容的自动化监测、处理与发布系统 | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | 高效使用 AI 助手的进阶技巧 | |

### 🔄 自动化工具

本仓库内的本地自动化/工具包括：

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh)：为 shell 用户提供更安全的删除/恢复流程。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py)：域名到 IP/CIDR 的解析与去重工具。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py)：按子目录合并 Python 文件为文本产物。

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

The Art of Lazying 将“策略性偷懒”视为一种优化精力分配、聚焦真正重要事项的方法。本仓库探索了有意识地“偷懒”如何带来更高生产力、创造力与幸福感。

## Lazying 理论

这里系统介绍“策略性偷懒”的核心原则，重点在于通过任务优先级、委派与自动化，最大化生产力与幸福感。

关键原则是将帕累托 80/20 法则应用到日常生活中：识别那 20% 能产生 80% 目标结果的活动。

## 实用技巧与方法

以下是将“偷懒原则”落地到工作、关系和自我照护中的可执行建议：

- 自动化重复性任务。
- 使用番茄工作法进行时间管理。
- 建立系统以减少决策疲劳。
- 借助 AI 工具提供辅助。

## 使用场景

真实案例展示“偷懒原则”如何解决问题并提升效率：

- 创业者如何通过委派与自动化聚焦业务增长。
- 学术研究者如何精简研究工作流。
- 内容创作者如何优化生产流程。

## AI Agent 与自动化

探索如何开发可简化任务的 AI Agent 与自动化工具：

- 把 ChatGPT 当作个人助理。
- 构建定制化自动化工作流。
- 制作用于被动学习的墨水屏显示设备。

## 语言学习与 Vlog

高效语言学习的资源与方法，以及记录 lazying 实践历程的 Vlog：

- 使用间隔重复构建个性化语言学习方案。
- 实施沉浸式学习技巧。
- 构建鼓励被动学习的项目。

## 前置要求

该仓库包含多个项目，不提供单一的顶层依赖清单。请按模块安装所需依赖。

常见要求：

- `git`
- Python `3.9+`（推荐）
- `pip`
- 可选虚拟环境工具（`python -m venv`）

从源码/README 可见的模块依赖信号：

- `code/EinkWordsGPT`：`openai`、`Pillow`、`pytz`、`pykakasi`、Waveshare 墨水屏 Python 库（`waveshare_epd`）及兼容硬件。
- `vlogs/chatgpt-traffic`：`dnspython`。
- `scripts/lazy-care/SafeShell`：Bash/Zsh shell。

## 安装

### 1. 克隆仓库

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. （推荐）创建 Python 虚拟环境

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. 为所选模块安装 Python 依赖

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell 设置（可选）

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## 配置

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` 与 `words_update.py` 使用 `OpenAI()`，并期望你的环境中已可用凭据。
- 推荐：

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell 垃圾箱位置

- `safeshell_functions.sh` 使用固定的垃圾箱根路径：

```bash
/mnt/disk/BIN/ROOT
```

如果你的机器目录布局不同，请在脚本中调整该路径。

### repo2text 源/目标目录

- `vlogs/repo2text/convert-repo-to-merged-text.py` 当前设置为：
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

执行前请先修改这些变量。

## 使用

### 运行 EinkWordsGPT 显示循环（需要硬件环境）

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

### source 后使用 SafeShell 命令

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## 示例

- `code/EinkWordsGPT/demo.jpg`：墨水屏输出示例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`：notebook 示例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`：提示词参考。
- `demos/`：本 README 使用的可视化演示。

## 开发说明

- 本仓库是遗留风格的伞形项目，不是单体打包应用。
- 项目表中的多个工具位于外部仓库；运行细节请参考各自 README。
- 某些内部文档描述的是较旧目录布局（例如 `scripts/lazy-care` 曾引用拆分脚本，而当前实现已整合到 `SafeShell/safeshell_functions.sh`）。
- `EinkWordsGPT` 中依赖硬件的代码默认在 Raspberry Pi + Waveshare 墨水屏环境下运行。

### 假设（显式）

- 顶层 README 是规范入口；关联外部项目的详细运行说明维护在各自仓库中。
- Python 包版本刻意保持开放，因为当前仓库未提供根目录 `requirements.txt`/`pyproject.toml`。
- 对于 `EinkWordsGPT`，默认你会在目标 Raspberry Pi 环境中完成 Waveshare 硬件所需驱动安装。

## 故障排查

- `ModuleNotFoundError: waveshare_epd`：在目标设备安装 Waveshare 墨水屏库，并确认硬件相关依赖完整。
- OpenAI 鉴权错误：确认 `OPENAI_API_KEY` 已在当前 shell/session 中设置。
- 围绕 `words_phonetics.db` 或字体出现 `File not found`：请从 `code/EinkWordsGPT` 目录运行脚本，确保相对路径正确解析。
- 找不到 SafeShell 命令：确认已将 `safeshell_functions.sh` 追加到正确的 shell 配置文件，并重新加载 shell。
- `repo2text` 未生成文件：检查 `source_directory` 是否存在且包含 `.py` 文件。

## 路线图

- 统一依赖管理，并为模块按需提供 `requirements.txt`。
- 增加根目录任务运行器或 Makefile，覆盖常见工作流。
- 扩展 Raspberry Pi + Waveshare 部署的可复现安装文档。
- 为工具脚本与数据转换辅助模块补充测试。
- 持续提升 `i18n/` 多语言文档一致性。

## 社区贡献

欢迎分享你在“策略性偷懒”方面的经验、技巧与想法：

- 交流效率技巧的社区讨论。
- 日常流程工具与模板。
- 面向高效偷懒的协作项目。

## 参与贡献

欢迎在内容、脚本和项目文档方面贡献改进。

标准流程：

1. Fork 本项目。
2. 创建你的功能分支（`git checkout -b feature/AmazingFeature`）。
3. 提交修改（`git commit -m 'Add some AmazingFeature'`）。
4. 推送到分支（`git push origin feature/AmazingFeature`）。
5. 提交 Pull Request。

如果你的改动影响了某个子模块，也请同步更新该子模块 README。

## 联系

| 渠道 | 链接 |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## 支持 / 捐助

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

## 许可证

本仓库基于 MIT 许可证发布。详情见 [LICENSE](LICENSE)。

说明：

- 顶层项目许可证：MIT。
- 部分子目录包含各自的 `LICENSE` 文件；如有冲突，以该路径下更具体的许可证文件为准。

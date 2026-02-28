[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


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

这是一个用于实践 AI 辅助生产力实验、语言学习系统与实用工具的仓库级工作空间。

> 少做低杠杆工作，把精力留给高杠杆产出。

| 🎯 关注 | 🎛️ 主要技术栈 | 🧭 目标 |
|---|---|---|
| 自动化重复任务 | Python + shell | 降低认知负担 |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## 目录

- [概览](#概览)
- [特性](#特性)
- [项目](#项目)
- [项目结构](#项目结构)
- [Lazying 方法概览](#lazying-方法概览)
- [实用技巧与窍门](#实用技巧与窍门)
- [使用场景](#使用场景)
- [AI 助手与自动化](#ai-助手与自动化)
- [语言学习与 Vlog](#语言学习与-vlog)
- [前置条件](#前置条件)
- [安装](#安装)
- [配置](#配置)
- [使用](#使用)
- [示例](#示例)
- [开发说明](#开发说明)
- [故障排查](#故障排查)
- [路线图](#路线图)
- [社区贡献](#社区贡献)
- [参与贡献](#参与贡献)
- [❤️ Support](#-support)
- [联系](#联系)
- [许可证](#许可证)

## 概览

`The Art of Lazying` 是一个 legacy 风格的 umbrella 仓库：一个务实的集合体，覆盖 AI 工作流、shell 工具、树莓派实验与学习资源。

### 项目指标

| 指标 | 数值 |
|---|---|
| 仓库类型 | 遗留风格的伞形仓库 |
| 主要运行环境 | Python + shell 脚本 |
| 硬件侧重 | Raspberry Pi + e-ink（按模块定义） |
| 文档 | `i18n/` 中的多语言 README |
| 许可证 | GNU 通用公共许可证 3.0（根目录与主要子目录） |

## 特性

- ✅ 策略性懒惰框架：优先处理高杠杆任务，避免重复性动作耗费心智。
- ✅ AI 辅助创作工具与发布相关实验。
- ✅ 结合 e-ink 渲染与 OpenAI 工作流的语言学习工具（`code/EinkWordsGPT`）。
- ✅ 更安全的 shell 操作（`saferm` / `unrm` / `removeitanyway`）。
- ✅ 轻量级 Python 工具，用于 DNS/IP 收集和代码转文本。
- ✅ 多语言文档中心，支持语言独立的 README 变体。

## 项目

### 🤖 AI 驱动创作工具

| 项目 | 类型 | 聚焦 |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | 本地模块 | 使用 OpenAI 的 Raspberry Pi + Waveshare e-ink 单词卡展示 |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | 外部项目 | 词源分析与图结构式展示 |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | 外部项目 | 语言学习工具项目 |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | 外部项目 | 基于 CLIP embedding + GPT 的字幕制作 |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | 外部项目 | 多语言转录流水线 |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | 外部脚本 | 字幕与多语言翻译辅助 |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | 外部脚本 | 自动化媒体元数据生成 |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | 外部项目 | 视频编辑与字幕流程 |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | 外部项目 | 内容发布自动化 |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | 外部项目 | 发布监控与编排 |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | 外部项目 | 高阶提示词与 AI 使用范式 |

### 🛠️ 本地自动化工具

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh)：为 shell 用户提供更安全的删除与恢复流程。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py)：DNS 到 IP 与 CIDR 列表解析器。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py)：将子目录中的 Python 文件合并为文本，便于 AI 审阅。

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

### 遗留概念结构（历史文档）

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

## Lazying 方法概览

本仓库围绕**策略性懒惰**构建务实生产力：先自动化低价值决策，保留认知能量，再以系统方式替代临时性动作。

核心原则仍是务实的 80/20 视角：

- 找出对结果影响最高的 20%。
- 标准化并自动化重复流程。
- 消除日常实践中可避免的摩擦点。

## 实用技巧与窍门

- 用 shell 函数替代重复性的命令流程。
- 采用短周期的计划节奏（兼容番茄工作法）。
- 用可复用模板减少决策疲劳。
- 让 AI 先完成初稿/变换，再由人工复核。

## 使用场景

- 在创作者流程中委派并自动化重复操作。
- 借助 AI 摘要能力，提效研究与文档任务。
- 快速将代码上下文转为 AI 可读文本，便于分析。

## AI 助手与自动化

仓库中的实验包括：

- 围绕词汇学习与内容创作的实用助手工作流。
- 可脚本化的 DNS/IP 聚合，支持运营类任务。
- 仓库转文本导出，加速 AI 辅助代码检查。
- 可选的 shell 安全工具，避免误删等破坏性错误。

## 语言学习与 Vlog

语言相关内容与项目强调低负担的一致性：

- 通过 e-ink 显示器进行被动输入 + 周期复习。
- 在支持的子项目内完成跨语种笔记工作流。
- vlog 脚本与记录作为日常工程化实践示例。

## 前置条件

本仓库以模块为单位组织；根目录没有统一的 package 清单。

### 环境清单

| 条目 | 基线 |
|---|---|
| 操作系统 | Linux/macOS（shell 工具链），Windows WSL 可用于 Python 脚本 |
| Python | 3.9+ |
| 包管理器 | `pip` |
| 版本控制 | `git` |

### 模块级依赖（来自源码推断）

- `code/EinkWordsGPT`：`openai`、`Pillow`、`pytz`、`pykakasi`、`waveshare_epd`，以及 Raspberry Pi/e-paper 运行文件（`font/*`、`pic/*`）。
- `vlogs/chatgpt-traffic`：`dnspython`。
- `vlogs/repo2text`：仅标准库。
- `scripts/lazy-care/SafeShell`：具备 `mv`、`realpath` 的 Bash/Zsh 环境，并支持确认流程。

## 安装

### 1）克隆

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2）推荐的虚拟环境

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3）安装模块依赖

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4）可选：SafeShell 启动

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # 或 ~/.zshrc
source ~/.bashrc  # 或 source ~/.zshrc
```

## 配置

### 1）OpenAI / EinkWordsGPT

`code/EinkWordsGPT/words_gpt.py` 与 `words_update.py` 会直接实例化 `OpenAI()`，因此运行环境必须提供有效凭据。

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2）SafeShell 垃圾桶路径

`/mnt/disk/BIN/ROOT` 在 `scripts/lazy-care/SafeShell/safeshell_functions.sh` 中被硬编码为基础回收站路径。需要时请在脚本中调整。

### 3）`repo2text` 合并路径

`vlogs/repo2text/convert-repo-to-merged-text.py` 的默认值为：

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

如果你在目录名不匹配的仓库运行，请在执行前修改。

### 4）`chatgpt-traffic` 自定义项

`custom_ips`、`cidr` 与 `domains` 目前内置在 `vlogs/chatgpt-traffic/chatgpt-traffic.py` 中，需要时直接编辑。

## 使用

### 命令速查表

| 任务 | 命令路径 | 命令 |
|---|---|---|
| EinkWordsGPT 显示循环 | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT 更新脚本 | `code/EinkWordsGPT` | `python words_update.py` |
| 域名/IP 解析 | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| 仓库转文本合并 | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell 使用 | shell 配置 + 当前 shell | `saferm`, `unrm`, `removeitanyway` |

### EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_gpt.py
python words_update.py
```

### ChatGPT 流量解析器

```bash
cd vlogs/chatgpt-traffic
python chatgpt-traffic.py
```

### 仓库转文本合并

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell（source 之后）

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## 示例

- `code/EinkWordsGPT/demo.jpg`：e-ink 输出示例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`：Notebook 示例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`：提示词参考。
- `demos/`：项目文档中使用的可视化素材。

## 开发说明

- 这是一个遗留风格的 umbrella 仓库；详细运行行为以各模块级文档为准。
- 列表中的部分项目来自外部 GitHub 仓库；请以各自 README 的说明为准。
- `EinkWordsGPT` 依赖硬件（Raspberry Pi + Waveshare 显示屏）。
- 部分模块依赖在仓库外声明，随时间可能与当前文档存在偏差。

### 明确假设

- 仓库根目录与主要模块默认采用 **GNU GPL v3.0**，除非某目录明确有自己的 `LICENSE` 约定。
- 该仓库没有统一的 `requirements.txt`、`pyproject.toml` 或 `package.json`，因此模块安装步骤故意不集中在顶层。

## 故障排查

- `ModuleNotFoundError: waveshare_epd`
  - 在目标设备上安装 Waveshare e-paper 模块并确认硬件驱动正常。
- OpenAI 请求出现鉴权错误
  - 确认当前 shell/会话已导出 `OPENAI_API_KEY`。
- `words_phonetics.db` 未找到
  - 在 `code/EinkWordsGPT` 目录内运行 EinkWordsGPT 脚本，保证相对路径可解析。
- `saferm`/`unrm` 不可用
  - 追加 `safeshell_functions.sh` 后，重新 source 你的 shell 配置。
- `repo2text` 没有输出内容
  - 确认 `source_directory` 存在且包含 `.py` 文件。

## 路线图

- 统一模块依赖文档，并补充模块级安装片段。
- 为模块工作流增加可选根任务运行器（Makefile / 脚本入口）。
- 改善 Raspberry Pi + Waveshare 部署的可复现性文档。
- 为工具脚本补充简单自动化测试。
- 持续扩展 `i18n/` 的语言一致性。

## 社区贡献

欢迎分享实用改进、自动化思路和语言学习实验：

- 日常任务的流程模板。
- 降低维护成本的真实“懒人式”模式。
- 跨模块集成与脚本级修复。

## 参与贡献

欢迎贡献。

1. Fork 仓库。
2. 创建功能分支（`git checkout -b feature/your-topic`）。
3. 提交修改（`git commit -m 'Add feature'`）。
4. 推送分支并提 PR。

如果你的改动是模块内的，还请同步更新对应模块的 README。

## 联系

| 渠道 | 链接 |
|---|---|
| 🌐 网站 | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ 邮箱 | `lachlan@lazying.art` |

## 许可证

本仓库采用 **GNU 通用公共许可证 v3.0**（见 [LICENSE](LICENSE)）。

说明：

- 根目录及主要子目录包含 `LICENSE` 文件，采用 GNU GPL。
- 如果你在某个具体子目录工作，请以最接近该目录的 `LICENSE` 文件为准。


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

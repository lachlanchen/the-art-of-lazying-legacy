[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

AIエージェント、語学学習、Vlogを横断し、実践的なヒントと実生活のユースケースを通して、シンプルで生産的な暮らしのための「戦略的な怠け方」を提案するリポジトリです。

> 低い影響の作業を減らし、意味のある成果をより多く生み出そう。

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table of Contents

- [概要](#overview)
- [特徴](#features)
- [プロジェクト](#projects)
- [プロジェクト構成](#project-structure)
- [はじめに](#introduction)
- [Lazying の理論](#the-theory-of-lazying)
- [実践的ヒントとコツ](#practical-tips-and-tricks)
- [ユースケース](#use-cases)
- [AIエージェントと自動化](#ai-agents-and-automation)
- [語学学習とVlog](#language-learning-and-vlogs)
- [前提条件](#prerequisites)
- [インストール](#installation)
- [設定](#configuration)
- [使い方](#usage)
- [例](#examples)
- [開発ノート](#development-notes)
- [トラブルシューティング](#troubleshooting)
- [ロードマップ](#roadmap)
- [コミュニティ投稿](#community-contributions)
- [コントリビュート](#contributing)
- [接続先](#connect)
- [❤️ Support](#-support)
- [ライセンス](#license)

## Overview

`The Art of Lazying` は、思想、実用的な自動化、AI支援のクリエイティブツール、語学学習実験を融合したアンブレラ型リポジトリです。

### Project Signals

| Signal | Value |
|---|---|
| 🧩 Repository Type | Legacy-style umbrella repo |
| 🧪 Runtime Focus | Python + shell utilities + Raspberry Pi tooling |
| 🌐 Documentation | Multilingual READMEs in `i18n/` |
| 🪪 License | MIT |

It includes:

- 関連するAIプロジェクトとワークフローのショーケース。
- 安全なシェル操作とユーティリティワークフロー向けのローカルスクリプト/ツール。
- Raspberry Pi + Waveshare e-ink + OpenAI を使ったハードウェアベース語学学習プロジェクト（`EinkWordsGPT`）。
- DNS/IP集約やリポジトリ文字起こし変換などのVlogツール実験。
- [`i18n/`](i18n) 配下の多言語ドキュメント。

### Quick Snapshot

| Focus | What you get |
|------|---|
| 🧠 Philosophy | 高レバレッジ作業に集中するための「戦略的な怠け方」の原則 |
| 🤖 AI | クリエイティブ支援、文字起こし、翻訳、公開支援 |
| 🛠️ Utilities | 安全な削除・復元、DNS/IPツール、リポジトリテキスト変換 |
| 🌍 i18n | `i18n/` の複数言語README |

## Features

- ✅ 高レバレッジな努力へ軸足を置く戦略的怠惰フレームワーク。
- ✅ AI支援の制作・公開ワークフローへの参照。
- ✅ 語学学習ユーティリティとe-ink学習表示システム。
- ✅ シェル安全化ヘルパー（`saferm`, `unrm`, `removeitanyway`）。
- ✅ DNS/IP収集やコードベース統合テキスト化のための軽量Pythonユーティリティ。
- ✅ 多言語README対応。

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

このリポジトリ内のローカル自動化/ツールには、以下が含まれます。

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): シェル利用者向けの、より安全な削除/復元ワークフロー。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): ドメインからIP/CIDRへの解決と重複排除を行うツール。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): サブディレクトリ単位でPythonファイルを統合し、テキスト成果物を生成。

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

The Art of Lazying は、エネルギー配分を最適化し、本当に重要なことに集中する方法として「戦略的な怠け方」を提示します。このリポジトリでは、意図的に怠けることがより高い生産性・創造性・ウェルビーイングにつながる可能性を探ります。

## The Theory of Lazying

戦略的怠けの原則を包括的に紹介し、優先順位付け、委任、そして自動化によって生産性とウェルビーイングを最大化する方法を提示します。

The key principle is applying Pareto's 80/20 rule to daily life: identifying the 20% of activities that produce 80% of desired outcomes.

## Practical Tips and Tricks

仕事、人間関係、セルフケアに怠けの原則を適用するための実践的なアドバイスです。

- 反復作業を自動化する。
- 時間管理にポモドーロ・テクニックを使う。
- 意思決定疲れを減らす仕組みを作る。
- 補助としてAIツールを活用する。

## Use Cases

怠けの原則がどのように問題解決と効率改善につながるかを示す実例です。

- 起業家が委任と自動化によって事業成長に集中する方法。
- 研究者が研究ワークフローを効率化する方法。
- コンテンツ制作者が制作プロセスを最適化する方法。

## AI Agents and Automation

作業を簡素化するAIエージェントと自動化ツールの開発を扱います。

- ChatGPTをパーソナルアシスタントとして使う。
- カスタム自動化ワークフローを構築する。
- 受動学習のためのe-inkディスプレイを作る。

## Language Learning and Vlogs

効率的な語学学習のためのリソースと手法、そして laz ying の実践過程を記録したVlogをまとめます。

- 間隔反復でパーソナライズされた語学学習を作る。
- 没入型学習の手法を実装する。
- 受動学習を促進するプロジェクトを作る。

## Prerequisites

このリポジトリは複数プロジェクトで構成されており、ルートに単一の依存関係マニフェストはありません。必要なモジュール分だけ導入してください。

### Environment Checklist

| Item | Baseline |
|---|---|
| OS | Linux/macOS recommended (for shell workflows) |
| Python | 3.9+ |
| Package manager | `pip` |
| Version control | `git` |

Common requirements:

- `git`
- Python `3.9+`（推奨）
- `pip`
- Optional virtual environment tooling (`python -m venv`)

Module-specific signals from source code/READMEs:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, Waveshare e-paper Python library (`waveshare_epd`) と対応ハードウェア。
- `vlogs/chatgpt-traffic`: `dnspython`。
- `scripts/lazy-care/SafeShell`: Bash/Zsh shell。

## Installation

### 1. リポジトリをクローン

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. （推奨）Python 仮想環境を作成

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. 選択したモジュール向けに Python の依存関係をインストール

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell セットアップ（任意）

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Configuration

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` と `words_update.py` は `OpenAI()` を使用し、認証情報が環境変数で利用可能であることを前提とします。
- 推奨:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell trash location

- `safeshell_functions.sh` は固定のゴミ箱ベースパスを使用します。

```bash
/mnt/disk/BIN/ROOT
```

必要に応じてこのパスを、あなたの環境に合わせてスクリプト内で調整してください。

### repo2text source/target directories

- `vlogs/repo2text/convert-repo-to-merged-text.py` は現在、次を設定しています。
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

実行前にこれらの変数を編集してください。

## Usage

### Command Quick Index

| Task | Command Path | Primary Command |
|---|---|---|
| EinkWordsGPT display loop | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT updater | `code/EinkWordsGPT` | `python words_update.py` |
| Domain/IP resolver | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Repo-to-text merge | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell recovery workflow | shell profile + current shell | `saferm`, `unrm`, `removeitanyway` |

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

- `code/EinkWordsGPT/demo.jpg`: e-ink出力サンプル。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ノートブック例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: プロンプトリファレンス。
- `demos/`: このREADMEで使用されるビジュアルデモ。

## Development Notes

- このリポジトリは単一パッケージ化アプリではなく、レガシー型のアンブレラ型プロジェクトです。
- Projects 表の複数ツールは外部リポジトリに存在するため、実行時の詳細は各リポジトリの README を参照してください。
- 一部の内部ドキュメントは古いファイル構成を前提にしています（例: `scripts/lazy-care` が分割スクリプトを参照する一方、現在は `SafeShell/safeshell_functions.sh` に集約）。
- `EinkWordsGPT` のハードウェア依存コードは Raspberry Pi + Waveshare e-paper 環境を前提にしています。

### Assumptions (Explicit)

- ルートREADMEが正規エントリポイントであり、リンク先外部プロジェクトの詳細な実行手順は各自のリポジトリで管理されます。
- Pythonパッケージバージョンは意図的に固定しないでいます。本リポジトリは現状、トップレベルの `requirements.txt`/`pyproject.toml` を提供していないためです。
- `EinkWordsGPT` については、Waveshare機器向けデバイスドライバの導入は対象 Raspberry Pi 環境であらかじめ実施されている前提です。

## Troubleshooting

- `ModuleNotFoundError: waveshare_epd`: 対象デバイスにWaveshare e-paperライブラリをインストールし、ハードウェア依存関係を確認してください。
- OpenAI認証エラー: 現在のシェル/セッションで `OPENAI_API_KEY` が設定されているか確認してください。
- `words_phonetics.db` やフォント周りで `File not found`: `code/EinkWordsGPT` からスクリプトを実行し、相対パスが正しく解決されるようにしてください。
- SafeShellコマンドが見つからない: `safeshell_functions.sh` を適切なシェルプロファイルに追記し、シェルを再読み込みしてください。
- `repo2text` でファイルが生成されない: `source_directory` が存在し、`.py` ファイルを含んでいることを確認してください。

## Roadmap

- モジュール単位の `requirements.txt` を任意で追加し、依存関係管理を統一。
- よく使うワークフロー向けに、ルートレベルのタスクランナーやMakefileを追加。
- Raspberry Pi + Waveshare導入向けの再現可能なセットアップドキュメントを拡充。
- ユーティリティスクリプトやデータ変換ヘルパーのテストを追加。
- `i18n/` の多言語ドキュメント整合性を継続改善。

## Community Contributions

戦略的怠けに関する体験、ヒント、アイデアの共有を歓迎します。

- 生産性改善ハックを交換するフォーラム。
- 日々のルーティンに使えるツールやテンプレート。
- 「怠け効率」を高める共同プロジェクト。

## Contributing

コンテンツ、スクリプト、プロジェクトドキュメントへの貢献は歓迎します。

標準フロー:

1. Forkします。
2. フィーチャーブランチを作成します（`git checkout -b feature/AmazingFeature`）。
3. 変更をコミットします（`git commit -m 'Add some AmazingFeature'`）。
4. ブランチへプッシュします（`git push origin feature/AmazingFeature`）。
5. Pull Requestを作成します。

変更が特定のサブモジュールに影響する場合は、そのサブモジュールの README も更新してください。

## Connect

| Channel | Link |
|---|---|
| 🌐 Website | [![Website](https://img.shields.io/badge/lazying.art-Visit-0A66C2?style=flat-square)](https://lazying.art) |
| 🧑‍💻 GitHub | [![GitHub](https://img.shields.io/badge/lachlanchen-Profile-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## ❤️ Support

| Donate | PayPal | Stripe |
|---|---|---|
| [![Donate](https://img.shields.io/badge/Donate-LazyingArt-0EA5E9?style=for-the-badge&logo=ko-fi&logoColor=white)](https://chat.lazying.art/donate) | [![PayPal](https://img.shields.io/badge/PayPal-RongzhouChen-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/RongzhouChen) | [![Stripe](https://img.shields.io/badge/Stripe-Donate-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.

Notes:

- Top-level project license: MIT。
- Some subfolders include their own `LICENSE` files; when in doubt, follow the most specific license file in that path.

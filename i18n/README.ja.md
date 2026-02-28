[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

AIエージェント、語学学習、Vlogを横断し、実践的なヒントと実生活のユースケースを通して、シンプルで生産的な暮らしのための「戦略的な怠け方」を提案するリポジトリです。

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table of Contents

- [概要](#overview)
- [特徴](#features)
- [プロジェクト](#projects)
- [プロジェクト構成](#project-structure)
- [はじめに](#introduction)
- [Lazying の理論](#the-theory-of-lazying)
- [実践ヒントとコツ](#practical-tips-and-tricks)
- [ユースケース](#use-cases)
- [AIエージェントと自動化](#ai-agents-and-automation)
- [語学学習とVlog](#language-learning-and-vlogs)
- [前提条件](#prerequisites)
- [インストール](#installation)
- [設定](#configuration)
- [使い方](#usage)
- [例](#examples)
- [開発メモ](#development-notes)
- [トラブルシューティング](#troubleshooting)
- [ロードマップ](#roadmap)
- [コミュニティ貢献](#community-contributions)
- [コントリビュート](#contributing)
- [連絡先](#connect)
- [サポート / 寄付](#support--donate)
- [ライセンス](#license)

## Overview

`The Art of Lazying` は、思想、実用的な自動化、AI支援のクリエイティブツール、語学学習の実験を横断して扱うアンブレラ型リポジトリです。

内容は次のとおりです。

- 関連するAIプロジェクトとワークフローのショーケース。
- 安全なシェル操作とユーティリティワークフロー向けのローカルスクリプト/ツール。
- Raspberry Pi + Waveshare e-ink + OpenAI を使ったハードウェアベースの語学学習プロジェクト（`EinkWordsGPT`）。
- DNS/IP集約やリポジトリのテキスト化などのVlog/ツール実験。
- [`i18n/`](i18n) 配下の多言語ドキュメント。

### Quick Snapshot

| Focus | 得られるもの |
|------|---|
| 🧠 Philosophy | レバレッジの高い仕事に集中するための「戦略的怠け」原則 |
| 🤖 AI | クリエイティブ支援、文字起こし、翻訳、公開作業の支援 |
| 🛠️ Utilities | 安全な削除/復元、DNS/IPツール、リポジトリテキスト変換 |
| 🌍 i18n | `i18n/` 配下で複数言語のREADMEを提供 |

## Features

- 高レバレッジな努力に焦点を当てた戦略的怠けフレームワーク。
- AI支援の制作・公開ワークフローに関する参照情報。
- 語学学習ユーティリティと e-ink 学習表示システム。
- シェル安全化ヘルパー（`saferm`、`unrm`、`removeitanyway`）。
- DNS/IP収集やコードベース統合テキスト化のための軽量Pythonユーティリティ。
- 多言語README対応。

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

The Art of Lazying は、エネルギー配分を最適化し、本当に重要なことに集中する方法として「戦略的な怠け方」を提示します。このリポジトリでは、意図的に怠けることが、より高い生産性・創造性・ウェルビーイングにつながる可能性を探ります。

## The Theory of Lazying

優先順位づけ、委任、自動化によって生産性とウェルビーイングを最大化するための、戦略的怠けの原則を包括的に紹介します。

中心となる原則は、日常生活にパレートの80/20ルールを適用することです。つまり、望む成果の80%を生む20%の活動を特定することです。

## Practical Tips and Tricks

仕事、人間関係、セルフケアに怠けの原則を適用するための、実践的なアドバイス集です。

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
- 受動学習のための e-ink ディスプレイを作る。

## Language Learning and Vlogs

効率的な語学学習のためのリソースと手法、そして lazying の実践過程を記録したVlogをまとめています。

- 間隔反復でパーソナライズされた語学学習を作る。
- 没入型学習の手法を実装する。
- 受動学習を促進するプロジェクトを作る。

## Prerequisites

このリポジトリは複数プロジェクトで構成されており、ルートに単一の依存関係マニフェストはありません。必要なモジュール分だけ導入してください。

共通要件:

- `git`
- Python `3.9+`（推奨）
- `pip`
- 任意の仮想環境ツール（`python -m venv`）

ソースコード/READMEから読み取れるモジュール固有の要件:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, Waveshare e-paper Pythonライブラリ（`waveshare_epd`）および対応ハードウェア。
- `vlogs/chatgpt-traffic`: `dnspython`。
- `scripts/lazy-care/SafeShell`: Bash/Zsh シェル。

## Installation

### 1. リポジトリをクローン

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. （推奨）Python仮想環境を作成

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. 選択したモジュール向けにPython依存関係をインストール

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

マシンの構成が異なる場合は、スクリプト内のこのパスを調整してください。

### repo2text source/target directories

- `vlogs/repo2text/convert-repo-to-merged-text.py` は現在、次を設定しています。
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

実行前にこれらの変数を編集してください。

## Usage

### EinkWordsGPT の表示ループを実行（ハードウェア環境が必要）

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### EinkWordsGPT の単語メンテナンス/更新スクリプトを実行

```bash
cd code/EinkWordsGPT
python words_update.py
```

### ChatGPT traffic ドメイン/IP リゾルバを実行

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### リポジトリ内 Python ファイル統合ツールを実行

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### source 後に SafeShell コマンドを利用

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Examples

- `code/EinkWordsGPT/demo.jpg`: e-ink 出力サンプル。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ノートブック例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: プロンプト参照資料。
- `demos/`: このREADMEで使用しているビジュアルデモ。

## Development Notes

- このリポジトリは、単一パッケージ化アプリではなく、レガシー型のアンブレラプロジェクトです。
- Projectsテーブル内の複数ツールは外部リポジトリに存在するため、実行時の詳細は各READMEを参照してください。
- 一部の内部ドキュメントは古いファイル構成を前提にしています（例: `scripts/lazy-care` で分割スクリプトを参照している一方、現在は `SafeShell/safeshell_functions.sh` に集約）。
- `EinkWordsGPT` のハードウェア依存コードは、Raspberry Pi + Waveshare e-paper 環境を前提としています。

### Assumptions (Explicit)

- ルートREADMEを正規の入口とし、外部連携プロジェクトの詳細な実行手順は各リポジトリで管理されることを前提とします。
- 本リポジトリにはルート `requirements.txt`/`pyproject.toml` がないため、Pythonパッケージのバージョンは意図的に固定していません。
- `EinkWordsGPT` については、Waveshareハードウェア向けデバイスドライバの導入手順を、対象Raspberry Pi環境で実施済みであることを前提とします。

## Troubleshooting

- `ModuleNotFoundError: waveshare_epd`: 対象デバイスにWaveshare e-paperライブラリを導入し、ハードウェア依存関係を確認してください。
- OpenAI認証エラー: 現在のシェル/セッションで `OPENAI_API_KEY` が設定されているか確認してください。
- `words_phonetics.db` やフォント周りで `File not found`: 相対パス解決のため `code/EinkWordsGPT` からスクリプトを実行してください。
- SafeShellコマンドが見つからない: `safeshell_functions.sh` が正しいシェルプロファイルに追記されているか確認し、シェルを再読み込みしてください。
- `repo2text` でファイルが生成されない: `source_directory` が存在し、`.py` ファイルを含んでいるか確認してください。

## Roadmap

- モジュール単位の `requirements.txt` を任意で追加し、依存関係管理を統一。
- よく使うワークフロー向けに、ルートレベルのタスクランナーまたはMakefileを追加。
- Raspberry Pi + Waveshare 展開向けの再現可能なセットアップドキュメントを拡充。
- ユーティリティスクリプトとデータ変換ヘルパーのテストを追加。
- `i18n/` の多言語ドキュメントの内容整合性を継続的に改善。

## Community Contributions

戦略的怠けに関する体験、ヒント、アイデアの共有を歓迎します。

- 生産性向上ハックを交換するフォーラム。
- 日々のルーティンに使えるツールとテンプレート。
- 怠けの効率性を追求する共同プロジェクト。

## Contributing

コンテンツ、スクリプト、プロジェクトドキュメントへの貢献を歓迎します。

標準フロー:

1. プロジェクトをForkします。
2. フィーチャーブランチを作成します（`git checkout -b feature/AmazingFeature`）。
3. 変更をコミットします（`git commit -m 'Add some AmazingFeature'`）。
4. ブランチへPushします（`git push origin feature/AmazingFeature`）。
5. Pull Requestを作成します。

特定サブモジュールに影響する変更の場合は、そのサブモジュールのREADMEも更新してください。

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

このリポジトリはMITライセンスで提供されています。詳細は [LICENSE](LICENSE) を参照してください。

注記:

- ルートプロジェクトのライセンス: MIT。
- 一部サブフォルダには独自の `LICENSE` ファイルがあります。不明な場合は、そのパスで最も具体的なライセンスファイルを優先してください。

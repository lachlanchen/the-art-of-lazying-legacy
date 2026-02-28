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

実践的なAI支援による生産性実験、語学学習システム、ユーティリティツールを集約したリポジトリレベルのワークスペースです。

> 価値の低い作業には手間をかけず、価値の高い成果に集中する。

| 🎯 Focus | 🎛️ Primary stack | 🧭 Target |
|---|---|---|
| 繰り返し作業を自動化する | Python + shell | 認知負荷を下げる |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## 目次

- [概要](#overview)
- [特徴](#features)
- [プロジェクト](#projects)
- [プロジェクト構成](#project-structure)
- [Lazying の考え方](#overview-of-the-lazying-approach)
- [実践的なヒントとコツ](#practical-tips-and-tricks)
- [ユースケース](#use-cases)
- [AIエージェントと自動化](#ai-agents-and-automation)
- [語学学習とVlog](#language-learning-and-vlogs)
- [前提条件](#prerequisites)
- [インストール](#installation)
- [設定](#configuration)
- [使い方](#usage)
- [事例](#examples)
- [開発ノート](#development-notes)
- [トラブルシューティング](#troubleshooting)
- [ロードマップ](#roadmap)
- [コミュニティ投稿](#community-contributions)
- [コントリビューション](#contributing)
- [❤️ Support](#-support)
- [接続](#connect)
- [ライセンス](#license)

<a id="overview"></a>
## 概要

`The Art of Lazying` は、実用的なAIワークフロー、シェルユーティリティ、Raspberry Pi実験、学習リソースをまとめた、レガシー構成のアンブレラ型リポジトリです。

### プロジェクトのシグナル

| Signal | Value |
|---|---|
| リポジトリ種別 | レガシーなアンブレラリポジトリ |
| 実行環境 | Python + shell scripts |
| ハードウェア焦点 | Raspberry Pi + e-ink（モジュール依存） |
| ドキュメント | `i18n/` 内の多言語README群 |
| ライセンス | GNU General Public License 3.0（ルートと主要サブフォルダ） |

<a id="features"></a>
## 特徴

- ✅ 戦略的な「賢い怠惰」フレームワーク：反復作業よりも高レバレッジなタスクを優先する。
- ✅ AI支援のクリエイティブ系ツールと公開関連の実験。
- ✅ e-inkレンダリングとOpenAI支援単語ワークフロー（`code/EinkWordsGPT`）を用いた語学学習ユーティリティ。
- ✅ より安全なシェル操作（`saferm` / `unrm` / `removeitanyway`）。
- ✅ DNS/IP収集やコード→テキスト変換向けの軽量Pythonユーティリティ。
- ✅ `i18n/` に言語別READMEを持つ多言語ドキュメントハブ。

<a id="projects"></a>
## プロジェクト

### 🤖 AI搭載クリエイティブツール

| Project | Type | Focus |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Local module | Raspberry Pi + Waveshare e-ink 単語カード表示（OpenAI） |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | External project | 単語の語源分析とグラフ表示 |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | External project | 語学学習ユーティリティ |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | External project | CLIP埋め込み + GPTによる字幕生成 |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | External project | 多言語文字起こしパイプライン |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | External script | 字幕／多言語翻訳支援 |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | External script | メディアメタデータの自動生成 |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | External project | 動画編集と字幕のワークフロー |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | External project | コンテンツ公開の自動化 |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | External project | 監視＋公開のオーケストレーション |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | External project | 高度なプロンプト設計とAI活用の実践パターン |

### 🛠️ ローカル自動化ツール

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): シェル利用者向けの安全な削除/復旧フロー。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): ドメイン名からIP/CIDRを解決するDNSユーティリティ。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): サブディレクトリ内のPythonファイルをAIレビュー向けテキストに統合。

<a id="project-structure"></a>
## プロジェクト構成

### 現在のリポジトリ構成

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

### レガシーな概念構成（履歴資料）

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

<a id="overview-of-the-lazying-approach"></a>
## Lazying の考え方

このリポジトリでは、実践的生産性を**戦略的な怠惰**として捉えています。価値の低い判断は自動化し、認知エネルギーを節約し、戦術より先にシステムを置きます。

中心原則は実務向けの80/20です。

- 最も効果の高い20%の行動を特定する。
- 繰り返しフローを標準化・自動化する。
- 日常運用で避けられる摩擦を排除する。

<a id="practical-tips-and-tricks"></a>
## 実践的なヒントとコツ

- 繰り返しのコマンドワークフローをシェル関数に置き換える。
- 短い計画サイクル（ポモドーロ相性）を使う。
- 再利用可能なテンプレートで判断疲労を減らす。
- AIに一次ドラフトや変換を任せ、最後に自分でレビューする。

<a id="use-cases"></a>
## ユースケース

- クリエイターワークフローの定型作業を委任し自動化する。
- AI要約を使って調査・ドキュメント作業を効率化する。
- コードの文脈を短時間でAI向けテキストへ変換し分析する。

<a id="ai-agents-and-automation"></a>
## AIエージェントと自動化

このリポジトリの実験には次が含まれます。

- 単語学習とコンテンツ制作を支援する実践的なアシスタントワークフロー。
- 業務タスク向けのスクリプト可能なDNS/IP集約。
- AI支援の高速コード検査のためのrepo-to-textエクスポート。
- 誤削除などを防ぐ任意のシェル安全ツール。

<a id="language-learning-and-vlogs"></a>
## 語学学習とVlog

語学関連コンテンツとプロジェクトは、低コストで継続しやすい一貫性を重視しています。

- e-ink表示による受動的インプットと定期的な復習。
- 対応サブプロジェクトでのクロスリンガルノートフロー。
- Vlog向けスクリプトとノートを実践的なルーティン設計の例として整備。

<a id="prerequisites"></a>
## 前提条件

このリポジトリはモジュール構成で、ルートレベルのパッケージマニフェストはありません。

### 環境チェックリスト

| Item | Baseline |
|---|---|
| OS | Linux/macOS（シェル系ツール）、Windows WSLはPythonスクリプトを許容 |
| Python | 3.9+ |
| パッケージマネージャー | `pip` |
| バージョン管理 | `git` |

### モジュール単位の依存関係（ソースからの推定）

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`、およびRaspberry Pi/e-paper実行ファイル（`font/*`, `pic/*`）。
- `vlogs/chatgpt-traffic`: `dnspython`。
- `vlogs/repo2text`: 標準ライブラリのみ。
- `scripts/lazy-care/SafeShell`: Bash/Zsh と `mv`, `realpath`、任意の確認フロー。

<a id="installation"></a>
## インストール

### 1) クローン

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) 仮想環境の作成（推奨）

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) モジュール依存関係のインストール

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) （任意）SafeShellの初期化

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or source ~/.zshrc
```

<a id="configuration"></a>
## 設定

### 1) OpenAI / EinkWordsGPT

両方のEinkWordsGPTスクリプトは `OpenAI()` を直接初期化するため、実行環境で認証情報を利用できる必要があります。

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) SafeShell ゴミ箱の場所

`/mnt/disk/BIN/ROOT` は `scripts/lazy-care/SafeShell/safeshell_functions.sh` でベースゴミ箱パスとして固定されています。必要に応じてスクリプト内で変更してください。

### 3) `repo2text` の統合パス

`vlogs/repo2text/convert-repo-to-merged-text.py` のデフォルト値は次のとおりです。

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

実行するリポジトリの構成に合わせて、必要なら変更してください。

### 4) `chatgpt-traffic` のカスタム設定

`custom_ips`、`cidr`、`domains` は現在 `vlogs/chatgpt-traffic/chatgpt-traffic.py` に直接記述されています。必要に応じて直接編集してください。

<a id="usage"></a>
## 使い方

### クイックコマンド表

| Task | Command Path | Command |
|---|---|---|
| EinkWordsGPT 表示ループ | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT 更新 | `code/EinkWordsGPT` | `python words_update.py` |
| ドメイン/IP 解決 | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| repo-to-text マージ | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell 利用 | shell profile + 現在のシェル | `saferm`, `unrm`, `removeitanyway` |

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

### SafeShell (sourcing後)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

<a id="examples"></a>
## 事例

- `code/EinkWordsGPT/demo.jpg`: e-ink出力サンプル。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ノートブック例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: プロンプト参照。
- `demos/`: プロジェクト文書で使用されるビジュアル素材。

<a id="development-notes"></a>
## 開発ノート

- このリポジトリはレガシーなアンブレラ構成で、モジュール単位のドキュメントが詳細実装の信頼できる情報源です。
- 一部プロジェクトは外部GitHubリポジトリです。各リポジトリのREADMEでセットアップを確認してください。
- `EinkWordsGPT` はハードウェア依存（Raspberry Pi + Waveshareディスプレイ）です。
- モジュール単位の依存情報はリポジトリ外で管理されているものがあり、時間とともにドキュメントとズレることがあります。

### 前提条件（明示）

- ルートおよび主要モジュールディレクトリは、別途明示される `LICENSE` がない限り **GNU GPL v3.0** を採用しているものと見なします。
- モジュールごとのインストール手順は、ルートに `requirements.txt`、`pyproject.toml`、`package.json` がないため集約管理されていません。

<a id="troubleshooting"></a>
## トラブルシューティング

- `ModuleNotFoundError: waveshare_epd`
  - 対象端末に Waveshare e-paper モジュールをインストールし、ハードウェアドライバを確認します。
- OpenAIリクエストが認証エラーで失敗する
  - `OPENAI_API_KEY` が有効なシェル/セッションでエクスポートされていることを確認します。
- `words_phonetics.db` が見つからない
  - 相対パス解決のため、`code/EinkWordsGPT` からスクリプトを実行します。
- `saferm`/`unrm` が使用できない
  - `safeshell_functions.sh` を追記した後、シェルプロファイルを再読み込みしてください。
- `repo2text` が何も出力しない
  - `source_directory` が存在し、`.py` ファイルを含むことを確認してください。

<a id="roadmap"></a>
## ロードマップ

- モジュール依存ドキュメントを標準化し、モジュール別セットアップスニペットを追加。
- モジュールワークフロー向けにオプションのルートタスク実行環境（Makefile / スクリプトエントリポイント）を追加。
- Raspberry Pi + Waveshare デプロイの再現性ドキュメントを改善。
- ユーティリティスクリプト向けの簡易自動テストを追加。
- `i18n/` での言語追加と整合性を継続的に拡充。

<a id="community-contributions"></a>
## コミュニティ投稿

実用的な改善、運用自動化のアイデア、語学学習実験を共有してください。

- 日常業務向けワークフローテンプレート。
- メンテナンス負荷を下げる実践的な「怠け」パターン。
- モジュール横断の統合やスクリプト修正。

<a id="contributing"></a>
## コントリビューション

コントリビューション歓迎です。

1. リポジトリをフォークします。
2. フィーチャーブランチを作成します（`git checkout -b feature/your-topic`）。
3. 変更をコミットします（`git commit -m 'Add feature'`）。
4. ブランチをPushしてPRを作成します。

モジュール固有の変更なら、そのモジュールのローカルREADMEも更新してください。

## 接続

| Channel | Link |
|---|---|
| 🌐 ウェブサイト | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ メール | `lachlan@lazying.art` |

<a id="license"></a>
## ライセンス

このリポジトリは **GNU General Public License v3.0**（[LICENSE](LICENSE)）でライセンスされています。

補足:

- ルートと主要モジュールディレクトリには、GNU GPLを採用した `LICENSE` が含まれます。
- 特定のサブディレクトリで作業する場合は、適用範囲に関係する最も近い `LICENSE` を使用します。


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

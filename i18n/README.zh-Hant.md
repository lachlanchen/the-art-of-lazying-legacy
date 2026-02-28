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

這是個以實用導向的 AI 輔助生產力實驗、語言學習系統與實用工具為核心的儲存庫級工作空間。

> 少做低槓桿的工作，把精力放在高槓桿的結果上。

| 🎯 專注 | 🎛️ 主要技術棧 | 🧭 目標 |
|---|---|---|
| 自動化重複性任務 | Python + shell | 減少認知負擔 |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## 目錄

- [概覽](#概覽)
- [功能](#功能)
- [專案](#專案)
- [專案結構](#專案結構)
- [Lazying 方法概覽](#lazying-方法概覽)
- [實用技巧與訣竅](#實用技巧與訣竅)
- [使用情境](#使用情境)
- [AI 代理與自動化](#ai-代理與自動化)
- [語言學習與 Vlog](#語言學習與-vlog)
- [前置條件](#前置條件)
- [安裝](#安裝)
- [設定](#設定)
- [使用方法](#使用方法)
- [範例](#範例)
- [開發備註](#開發備註)
- [疑難排解](#疑難排解)
- [路線圖](#路線圖)
- [社群貢獻](#社群貢獻)
- [貢獻指南](#貢獻指南)
- [❤️ Support](#-support)
- [聯繫方式](#聯繫方式)
- [授權](#授權)

## 概覽

`The Art of Lazying` 是一個 legacy 風格的 umbrella 倉庫：一個務實的集合體，整合 AI 工作流、shell 工具、樹梅派實驗與學習資源。

### 專案指標

| 指標 | 數值 |
|---|---|
| 倉庫類型 | Legacy 風格的 umbrella 倉庫 |
| 主要執行環境 | Python + shell |
| 硬體關注 | Raspberry Pi + 電子紙（依模組而定） |
| 文件 | `i18n/` 內的多語 README |
| 授權 | GNU 通用公共授權 3.0（根目錄與主要子目錄） |

## 功能

- ✅ 戰略性懶惰框架：優先處理高槓桿任務，避免重複操作耗費心力。
- ✅ AI 輔助創作工具與發佈相關實驗。
- ✅ 結合 e-ink 渲染與 OpenAI 工作流程的語言學習工具（`code/EinkWordsGPT`）。
- ✅ 更安全的 shell 操作（`saferm` / `unrm` / `removeitanyway`）。
- ✅ 輕量級 Python 工具，用於 DNS/IP 收集與程式碼轉文本。
- ✅ 多語文件中心，支援語言專屬 README 變體。

## 專案

### 🤖 AI 驅動的創作工具

| 專案 | 類型 | 聚焦 |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | 本地模組 | 結合 OpenAI 的 Raspberry Pi + Waveshare e-ink 單字卡展示 |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | 外部專案 | 詞源分析與圖形化呈現 |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | 外部專案 | 語言學習工具專案 |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | 外部專案 | 使用 CLIP embeddings + GPT 的字幕製作 |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | 外部專案 | 多語轉錄流程 |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | 外部腳本 | 字幕與多語翻譯輔助 |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | 外部腳本 | 自動化媒體中繼資料生成 |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | 外部專案 | 影片剪輯與字幕流程 |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | 外部專案 | 內容發佈自動化 |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | 外部專案 | 發佈監控與調度 |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | 外部專案 | 進階 prompt 與 AI 使用工作流模式 |

### 🛠️ 本地自動化工具

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh)：為 shell 使用者提供更安全的刪除與還原流程。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py)：DNS 到 IP 與 CIDR 清單解析。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py)：將子目錄中的 Python 檔案合併為文字，方便 AI 檢視。

## 專案結構

### 目前倉庫目錄

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

### 歷史性概念結構（文件用）

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

## Lazying 方法概覽

這個倉庫以**戰略性懶惰**為核心：先自動化低價值決策，保留認知能量，並用系統思維取代臨時操作。

核心原則仍是務實的 80/20 視角：

- 找出影響最大的 20% 行動。
- 標準化並自動化重複流程。
- 消除日常實踐中可避免的摩擦點。

## 實用技巧與訣竅

- 用 shell 函數取代重複命令流程。
- 採用短週期規劃（與番茄鐘相容）。
- 用可重複使用的模板降低決策疲勞。
- 讓 AI 先做初稿或轉換，再由人工檢視。

## 使用情境

- 在創作者流程中委派並自動化重複操作。
- 借助 AI 摘要能力，簡化研究與文件化任務。
- 快速將程式碼上下文轉成 AI 可讀文本，用於分析。

## AI 代理與自動化

本倉庫中的實驗包含：

- 以詞彙學習與內容創作為核心的實用助理工作流。
- 可腳本化的 DNS/IP 聚合，支援操作流程。
- repo-to-text 匯出，提升 AI 輔助程式碼檢視效率。
- 可選的 shell 層安全工具，避免誤刪等破壞性錯誤。

## 語言學習與 Vlog

語言相關內容與專案強調低成本的持續一致性：

- 透過 e-ink 顯示器進行被動輸入與周期複習。
- 在支援的子專案裡執行跨語言筆記流程。
- Vlog 腳本與筆記作為實務日常工程化的示例。

## 前置條件

此倉庫為模組化設計；根目錄沒有統一套件清單。

### 環境檢核

| 項目 | 基準 |
|---|---|
| 作業系統 | Linux/macOS（shell 工具鏈），Windows WSL 亦可用於 Python 腳本 |
| Python | 3.9+ |
| 套件管理器 | `pip` |
| 版本控制 | `git` |

### 模組級相依性（依原始碼推斷）

- `code/EinkWordsGPT`：`openai`、`Pillow`、`pytz`、`pykakasi`、`waveshare_epd`，以及 Raspberry Pi/e-paper 執行時檔案（`font/*`、`pic/*`）。
- `vlogs/chatgpt-traffic`：`dnspython`。
- `vlogs/repo2text`：僅標準函式庫。
- `scripts/lazy-care/SafeShell`：具備 `mv`、`realpath` 的 Bash/Zsh shell 與可選確認流程。

## 安裝

### 1) Clone

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) 推薦虛擬環境

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) 安裝模組相依性

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) 可選：SafeShell 初始化

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## 設定

### 1) OpenAI / EinkWordsGPT

`code/EinkWordsGPT/words_gpt.py` 與 `words_update.py` 會直接實例化 `OpenAI()`，因此執行環境必須提供有效憑證。

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) SafeShell 回收桶位置

`/mnt/disk/BIN/ROOT` 在 `scripts/lazy-care/SafeShell/safeshell_functions.sh` 中是硬編碼的基礎回收桶路徑。若需要請直接在腳本中調整。

### 3) `repo2text` 合併路徑

`vlogs/repo2text/convert-repo-to-merged-text.py` 的預設值為：

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

在不符合目錄名稱的環境執行前請先修改。

### 4) `chatgpt-traffic` 自訂項目

`custom_ips`、`cidr` 與 `domains` 目前寫在 `vlogs/chatgpt-traffic/chatgpt-traffic.py`，可依需求直接編輯。

## 使用方法

### 指令速查表

| 任務 | 指令路徑 | 指令 |
|---|---|---|
| EinkWordsGPT 顯示循環 | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT 更新器 | `code/EinkWordsGPT` | `python words_update.py` |
| 網域 / IP 解析 | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Repo-to-text 匯出 | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell 使用 | shell 設定檔與目前 shell | `saferm`, `unrm`, `removeitanyway` |

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

### SafeShell（source 後）

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## 範例

- `code/EinkWordsGPT/demo.jpg`：e-ink 輸出範例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`：Notebook 範例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`：提示詞參考。
- `demos/`：文件中使用的視覺素材。

## 開發備註

- 這是 legacy umbrella 倉庫；模組級文件是詳細行為的真實來源。
- 列表中的部分專案來自外部 GitHub 倉庫；請以各自 README 作為安裝依據。
- `EinkWordsGPT` 綁定硬體（Raspberry Pi + Waveshare 顯示器）。
- 多個模組相依性位於倉庫外，隨時間可能與文件有落差。

### 明確假設

- 倉庫根目錄與主要模組預設採用 **GNU GPL v3.0**，除非某個目錄明確指定其他 `LICENSE` 規範。
- 模組安裝步驟沒有集中在根目錄，因為沒有統一的 `requirements.txt`、`pyproject.toml` 或 `package.json`。

## 疑難排解

- `ModuleNotFoundError: waveshare_epd`
  - 在目標裝置上安裝 Waveshare 電子紙模組並確認硬體驅動。
- OpenAI 請求出現驗證錯誤
  - 確認在目前 shell/工作階段已匯出 `OPENAI_API_KEY`。
- 找不到 `words_phonetics.db`
  - 從 `code/EinkWordsGPT` 目錄執行腳本，讓相對路徑可正常解析。
- `saferm` / `unrm` 無法使用
  - 將 `safeshell_functions.sh` 重新 append 到 shell 設定檔後，重新 source。
- `repo2text` 輸出為空
  - 確認 `source_directory` 存在且內含 `.py` 檔。

## 路線圖

- 統一模組相依文件並補齊模組級安裝範本。
- 新增可選的根任務執行器（Makefile / script entrypoint）以管理模組流程。
- 改善 Raspberry Pi + Waveshare 部署的可重現性文件。
- 為實用工具腳本補充簡易自動化測試。
- 持續擴展 `i18n/` 的語言一致性。

## 社群貢獻

分享實務改進、流程自動化想法與語言學習實驗：

- 日常任務的流程模板。
- 減少維護成本的真實懶人化模式。
- 跨模組整合與腳本層修正。

## 貢獻指南

歡迎提交貢獻。

1. Fork 倉庫。
2. 建立功能分支（`git checkout -b feature/your-topic`）。
3. 提交變更（`git commit -m 'Add feature'`）。
4. 推送分支並建立 PR。

若你的改動是模組特定的，也請同步更新該模組的本地 README。

## 聯繫方式

| 通道 | 連結 |
|---|---|
| 🌐 官方網站 | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ 電子信箱 | `lachlan@lazying.art` |

## 授權

本倉庫採用 **GNU 通用公共授權 v3.0**（請參閱 [LICENSE](LICENSE)）。

補充說明：

- 根目錄與主要模組目錄皆包含 `LICENSE` 檔案並使用 GNU GPL。
- 如果你在某個特定子目錄工作，請以該目錄最近的 `LICENSE` 為準。


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

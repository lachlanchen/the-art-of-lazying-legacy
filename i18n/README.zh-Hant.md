[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#先決條件)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#專案)

這是一個提倡「策略性偷懶」的儲存庫，目標是讓生活更簡化且更高效，內容涵蓋 AI 代理、語言學習與 vlog，並附帶實用技巧與真實情境案例。

> 少做低槓桿工作，交付更有價值的成果。

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## 目錄

- [概覽](#概覽)
- [特色](#特色)
- [專案](#專案)
- [專案結構](#專案結構)
- [簡介](#簡介)
- [偷懶理論](#偷懶理論)
- [實用技巧與訣竅](#實用技巧與訣竅)
- [使用案例](#使用案例)
- [AI 代理與自動化](#ai-代理與自動化)
- [語言學習與 Vlog](#語言學習與-vlog)
- [先決條件](#先決條件)
- [安裝](#安裝)
- [設定](#設定)
- [使用方式](#使用方式)
- [範例](#範例)
- [開發備註](#開發備註)
- [疑難排解](#疑難排解)
- [路線圖](#路線圖)
- [社群貢獻](#社群貢獻)
- [貢獻方式](#貢獻方式)
- [聯絡](#聯絡)
- [❤️ Support](#-support)
- [授權](#授權)

## 概覽

`The Art of Lazying` 是一個總整型儲存庫，結合哲學思維、實務自動化、AI 輔助創作工具與語言學習實驗。

### 專案訊號

| 訊號 | 內容 |
|---|---|
| 🧩 儲存庫類型 | Legacy 風格的 umbrella 專案 |
| 🧪 執行重點 | Python + shell 工具 + Raspberry Pi 工具鏈 |
| 🌐 文件 | `i18n/` 中的多語 README |
| 🪪 授權 | MIT |

包含：

- 已連結的 AI 專案與工作流程展示。
- 用於安全 shell 操作與實用流程的本地腳本/工具。
- 以 Raspberry Pi + Waveshare 電子紙 + OpenAI 打造的硬體語言學習專案（`EinkWordsGPT`）。
- DNS/IP 聚合與 repo-to-text 轉換等 vlog / 工具實驗。
- 位於 [`i18n/`](i18n) 的多語系文件。

### 快速總覽

| 重點 | 可獲得內容 |
|------|---|
| 🧠 哲學 | 聚焦高槓桿工作的策略性偷懶原則 |
| 🤖 AI | 創意輔助、轉錄、翻譯、發佈支援 |
| 🛠️ 實用工具 | 安全刪除/回復、DNS/IP 工具、儲存庫文字轉換 |
| 🌍 i18n | `i18n/` 中的多語版本 README |

## 特色

- 以高槓桿投入為核心的策略性偷懶框架。
- AI 輔助創作與發佈流程參考。
- 語言學習工具與電子紙學習顯示系統。
- Shell 安全輔助工具（`saferm`、`unrm`、`removeitanyway`）。
- 用於 DNS/IP 蒐集與程式碼庫文字合併的輕量 Python 工具。
- 多語 README 支援。

## 專案

### 🤖 AI 驅動創作工具

| 專案 | 說明 | 示範 |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | 以 GPT 為核心的電子紙單字學習顯示器 | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | 詞源分析並以圖表呈現。 | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | 用最少努力達到高效率語言學習的工具 | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | 結合 OpenAI CLIP embeddings 與 GPT decoder 的影音與圖片字幕工具 | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | 影像字幕工具：用 Katna/OpenCV 擷取關鍵影格，並用 ViT+GPT-2 生成字幕 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | 支援細緻語言判定的多語轉錄流程 | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | 破除語言隔閡，促進全球創作交流 | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | 影片自動產生元資料 | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | AI 驅動的自動影片剪輯工具，含轉錄、自動字幕、重點標示與元資料產生 | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | 優化內容發佈流程 | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | 自動化監控、處理並將影片內容同步發布到多個平台 | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | 更有效率使用 AI 助手的進階技巧 | |

### 🔄 自動化工具

此儲存庫中的本地自動化與工具包含：

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh)：為 shell 使用者提供更安全的刪除/回復流程。
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py)：網域到 IP/CIDR 的解析與去重工具。
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py)：依子目錄將 Python 檔合併成文字成果。

## 專案結構

### 目前儲存庫結構

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

### 保留的原始概念結構（參考）

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

## 簡介

The Art of Lazying 將「策略性偷懶」視為一種優化精力使用、聚焦真正重要事情的方法。本儲存庫探討如何透過有意識的「偷懶」，提升生產力、創造力與整體福祉。

## 偷懶理論

這裡提供策略性偷懶原則的完整導論，重點在於透過優先排序、委派與自動化任務，最大化生產力與生活品質。

核心原則是把帕累托 80/20 法則應用到日常生活：找出能帶來 80% 成果的 20% 活動。

## 實用技巧與訣竅

可直接落地的建議，協助把偷懶原則應用到工作、人際關係與自我照顧：

- 自動化重複性任務。
- 使用番茄鐘技術進行時間管理。
- 建立可降低決策疲勞的系統。
- 善用 AI 工具提供協助。

## 使用案例

以下是真實情境示例，展示偷懶原則如何解決問題並提升效率：

- 創業者如何透過委派與自動化，專注於業務成長。
- 學術研究者如何精簡研究工作流程。
- 內容創作者如何優化製作流程。

## AI 代理與自動化

探索可簡化任務的 AI 代理與自動化工具開發：

- 將 ChatGPT 當作個人助理。
- 建立客製化自動化工作流程。
- 打造用於被動學習的電子紙顯示器。

## 語言學習與 Vlog

提供高效率語言學習資源與技巧，並透過 vlog 記錄「策略性偷懶」的實踐歷程：

- 以間隔重複建立個人化語言學習流程。
- 實作沉浸式學習技巧。
- 建立能促進被動學習的專案。

## 先決條件

此儲存庫為多專案集合，沒有單一頂層依賴清單。請依你要使用的模組安裝所需套件。

### 環境檢查表

| 項目 | 基準值 |
|---|---|
| 作業系統 | 建議 Linux/macOS（用於 shell 流程） |
| Python | 3.9+ |
| 套件管理器 | `pip` |
| 版本控制 | `git` |

常見需求：

- `git`
- Python `3.9+`（建議）
- `pip`
- 可選虛擬環境工具（`python -m venv`）

模組需求（依原始碼/README 註記）：

- `code/EinkWordsGPT`：`openai`、`Pillow`、`pytz`、`pykakasi`、Waveshare 電子紙 Python 函式庫（`waveshare_epd`）與相容硬體。
- `vlogs/chatgpt-traffic`：`dnspython`。
- `scripts/lazy-care/SafeShell`：Bash/Zsh shell。

## 安裝

### 1. 複製這個儲存庫

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. （建議）建立 Python 虛擬環境

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. 安裝所選模組的 Python 依賴

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. 設定 SafeShell（可選）

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## 設定

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` 與 `words_update.py` 使用 `OpenAI()`，並預期憑證可在你的環境變數中取得。
- 建議：

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell 垃圾桶位置

- `safeshell_functions.sh` 使用固定垃圾桶基礎路徑：

```bash
/mnt/disk/BIN/ROOT
```

若你的機器路徑配置不同，請在腳本中調整此路徑。

### repo2text 來源/目標目錄

- `vlogs/repo2text/convert-repo-to-merged-text.py` 目前設定：
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

執行前請先編輯這些變數。

## 使用方式

### 指令速覽

| 任務 | 指令所在目錄 | 主要指令 |
|---|---|---|
| EinkWordsGPT 顯示循環 | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT 更新器 | `code/EinkWordsGPT` | `python words_update.py` |
| Domain/IP 解析器 | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| 儲存庫文字匯總工具 | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell 回復流程 | shell 設定檔 + 目前 shell | `saferm`、`unrm`、`removeitanyway` |

### 執行 EinkWordsGPT 顯示循環（需要硬體環境）

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### 執行 EinkWordsGPT 單字維護/更新腳本

```bash
cd code/EinkWordsGPT
python words_update.py
```

### 執行 ChatGPT 流量 domain/IP 解析工具

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### 執行儲存庫 Python 檔案合併工具

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### 載入後使用 SafeShell 指令

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## 範例

- `code/EinkWordsGPT/demo.jpg`：電子紙輸出範例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`：notebook 範例。
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`：提示詞參考。
- `demos/`：本 README 使用的視覺展示素材。

## 開發備註

- 這個儲存庫是 legacy 風格的 umbrella 專案，不是單體封裝應用程式。
- Projects 表中的多個連結工具位於外部儲存庫；執行細節請以各自 README 為準。
- 部分內部文件描述的是較舊檔案配置（例如 `scripts/lazy-care` 提到拆分腳本，但目前實作已整合在 `SafeShell/safeshell_functions.sh`）。
- `EinkWordsGPT` 中的硬體相依程式碼預設在 Raspberry Pi + Waveshare 電子紙環境。

### 假設（明確）

- 頂層 README 是主要入口；外部連結專案的詳細執行說明維護在其各自儲存庫。
- Python 套件版本刻意保持彈性，因為本專案目前未提供根目錄 `requirements.txt` / `pyproject.toml`。
- 對 `EinkWordsGPT` 而言，Waveshare 硬體驅動安裝步驟預期在目標 Raspberry Pi 環境中完成。

## 疑難排解

- `ModuleNotFoundError: waveshare_epd`：在目標裝置安裝 Waveshare 電子紙函式庫，並確認硬體相關依賴。
- OpenAI 驗證錯誤：確認 `OPENAI_API_KEY` 已在目前的 shell/session 中設定。
- `words_phonetics.db` 或字型出現 `File not found`：請在 `code/EinkWordsGPT` 目錄下執行腳本，讓相對路徑可正確解析。
- 找不到 SafeShell 指令：確認 `safeshell_functions.sh` 已追加到正確的 shell 設定檔，並重新載入 shell。
- `repo2text` 沒有產生檔案：檢查 `source_directory` 是否存在且包含 `.py` 檔案。

## 路線圖

- 透過可選的模組級 `requirements.txt` 統一依賴管理。
- 在根目錄新增常用流程的任務執行器（Task runner）或 Makefile。
- 擴充 Raspberry Pi + Waveshare 部署的可重現安裝文件。
- 為工具腳本與資料轉換輔助新增測試。
- 持續提升 `i18n/` 的多語文件一致性。

## 社群貢獻

分享你在策略性偷懶上的經驗、技巧與想法：

- 交流生產力技巧的論壇。
- 日常流程工具與模板。
- 共同打造提升效率的協作專案。

## 貢獻方式

歡迎對內容、腳本與專案文件提出貢獻。

標準流程：

1. Fork 此專案。
2. 建立功能分支（`git checkout -b feature/AmazingFeature`）。
3. 提交變更（`git commit -m 'Add some AmazingFeature'`）。
4. 推送分支（`git push origin feature/AmazingFeature`）。
5. 開啟 Pull Request。

若你的變更影響特定子模組，也請同步更新該子模組的 README。

## 聯絡

| 通道 | 連結 |
|---|---|
| 🌐 官方網站 | [![Website](https://img.shields.io/badge/lazying.art-Visit-0A66C2?style=flat-square)](https://lazying.art) |
| 🧑‍💻 GitHub | [![GitHub](https://img.shields.io/badge/lachlanchen-Profile-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lachlanchen) |
| ✉️ 電子信箱 | `lach@lazying.art` |

---

## ❤️ Support

| Donate | PayPal | Stripe |
|---|---|---|
| [![Donate](https://img.shields.io/badge/Donate-LazyingArt-0EA5E9?style=for-the-badge&logo=ko-fi&logoColor=white)](https://chat.lazying.art/donate) | [![PayPal](https://img.shields.io/badge/PayPal-RongzhouChen-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/RongzhouChen) | [![Stripe](https://img.shields.io/badge/Stripe-Donate-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

## 授權

此儲存庫採用 MIT License。詳情請見 [LICENSE](LICENSE)。

注意：

- 頂層專案授權：MIT。
- 部分子資料夾包含自己的 `LICENSE` 檔案；若有疑慮，請以該路徑下最具體的授權檔為準。

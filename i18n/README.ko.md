[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

AI 에이전트, 언어 학습, 브이로그를 아우르며, 실용적인 팁과 실제 활용 사례를 통해 더 단순하고 생산적인 삶을 위한 전략적 게으름을 제안하는 저장소입니다.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table of Contents

- [개요](#overview)
- [기능](#features)
- [프로젝트](#projects)
- [프로젝트 구조](#project-structure)
- [소개](#introduction)
- [게으름의 이론](#the-theory-of-lazying)
- [실전 팁과 요령](#practical-tips-and-tricks)
- [활용 사례](#use-cases)
- [AI 에이전트와 자동화](#ai-agents-and-automation)
- [언어 학습과 브이로그](#language-learning-and-vlogs)
- [사전 요구사항](#prerequisites)
- [설치](#installation)
- [설정](#configuration)
- [사용법](#usage)
- [예시](#examples)
- [개발 노트](#development-notes)
- [문제 해결](#troubleshooting)
- [로드맵](#roadmap)
- [커뮤니티 기여](#community-contributions)
- [기여하기](#contributing)
- [연락처](#connect)
- [지원 / 후원](#support--donate)
- [라이선스](#license)

## Overview

`The Art of Lazying`는 철학, 실용 자동화, AI 보조 창작 도구, 언어 학습 실험을 함께 담은 우산형(umbrella) 저장소입니다.

포함 내용:

- 연결된 AI 프로젝트와 워크플로 쇼케이스.
- 안전한 셸 작업 및 유틸리티 워크플로를 위한 로컬 스크립트/도구.
- Raspberry Pi + Waveshare e-ink + OpenAI 기반의 하드웨어 언어 학습 프로젝트(`EinkWordsGPT`).
- DNS/IP 집계, 저장소-텍스트 변환 같은 브이로그/도구 실험.
- [`i18n/`](i18n) 아래의 다국어 문서.

### Quick Snapshot

| Focus | 제공 내용 |
|------|---|
| 🧠 Philosophy | 높은 레버리지를 만드는 일에 집중하기 위한 전략적 게으름 원칙 |
| 🤖 AI | 창작 보조, 전사, 번역, 발행 지원 |
| 🛠️ Utilities | 안전한 셸 삭제/복구, DNS/IP 도구, 저장소 텍스트 변환 |
| 🌍 i18n | `i18n/`에 여러 언어 README 제공 |

## Features

- 높은 레버리지의 노력에 초점을 맞춘 전략적 게으름 프레임워크.
- AI 보조 창작 및 발행 워크플로 참고 자료.
- 언어 학습 유틸리티와 e-ink 학습 디스플레이 시스템.
- 셸 안전 도우미(`saferm`, `unrm`, `removeitanyway`).
- DNS/IP 수집 및 코드베이스 텍스트 병합을 위한 경량 Python 유틸리티.
- 다국어 README 지원.

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

이 저장소의 로컬 자동화/도구에는 다음이 포함됩니다.

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): 셸 사용자를 위한 더 안전한 삭제/복구 워크플로.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): 도메인을 IP/CIDR로 해석하고 중복을 제거하는 도구.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): 하위 디렉터리별 Python 파일을 텍스트 결과물로 병합.

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

The Art of Lazying는 에너지 사용을 최적화하고 진짜 중요한 일에 집중하는 방법으로 전략적 게으름을 제시합니다. 이 저장소는 의도적인 게으름이 더 높은 생산성, 창의성, 웰빙으로 이어질 수 있는 방식을 탐구합니다.

## The Theory of Lazying

우선순위화, 위임, 자동화를 통해 생산성과 웰빙을 극대화하는 전략적 게으름의 원칙을 종합적으로 소개합니다.

핵심 원칙은 파레토의 80/20 법칙을 일상에 적용하는 것입니다. 즉, 원하는 결과의 80%를 만드는 20% 활동을 식별하는 것입니다.

## Practical Tips and Tricks

일, 관계, 자기 관리에 게으름 원칙을 적용하기 위한 실행 가능한 조언 모음입니다.

- 반복 작업 자동화.
- 시간 관리를 위한 포모도로 기법 활용.
- 의사결정 피로를 줄이는 시스템 구축.
- 보조 수단으로 AI 도구 활용.

## Use Cases

게으름 원칙이 문제 해결과 효율 개선에 어떻게 기여하는지 보여주는 실제 사례입니다.

- 기업가가 위임과 자동화를 통해 비즈니스 성장에 집중하는 방법.
- 연구자가 연구 워크플로를 간소화하는 방법.
- 콘텐츠 크리에이터가 제작 과정을 최적화하는 방법.

## AI Agents and Automation

작업을 단순화하는 AI 에이전트와 자동화 도구 개발을 다룹니다.

- ChatGPT를 개인 비서로 활용.
- 맞춤형 자동화 워크플로 구축.
- 수동 학습을 위한 e-ink 디스플레이 제작.

## Language Learning and Vlogs

효율적인 언어 학습을 위한 리소스와 기법, 그리고 게으름 실천 여정을 기록한 브이로그를 제공합니다.

- 간격 반복으로 개인 맞춤형 언어 학습 만들기.
- 몰입형 학습 기법 적용.
- 수동 학습을 장려하는 프로젝트 구축.

## Prerequisites

이 저장소는 여러 프로젝트로 구성되어 있으며, 단일 최상위 의존성 매니페스트를 제공하지 않습니다. 모듈별로 필요한 항목만 설치하세요.

공통 요구사항:

- `git`
- Python `3.9+` (권장)
- `pip`
- 선택적 가상환경 도구 (`python -m venv`)

소스 코드/README 기준 모듈별 요구 신호:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, Waveshare e-paper Python 라이브러리(`waveshare_epd`) 및 호환 하드웨어.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: Bash/Zsh 셸.

## Installation

### 1. 저장소 클론

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (권장) Python 가상환경 생성

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. 선택한 모듈의 Python 의존성 설치

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell 설정 (선택)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Configuration

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py`와 `words_update.py`는 `OpenAI()`를 사용하며, 인증 정보가 환경에서 제공된다고 가정합니다.
- 권장 설정:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell trash location

- `safeshell_functions.sh`는 고정된 휴지통 기본 경로를 사용합니다:

```bash
/mnt/disk/BIN/ROOT
```

사용 중인 장비의 디렉터리 구조가 다르다면 스크립트에서 이 경로를 수정하세요.

### repo2text source/target directories

- `vlogs/repo2text/convert-repo-to-merged-text.py`는 현재 다음과 같이 설정되어 있습니다:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

실행 전에 이 변수를 편집하세요.

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

- `code/EinkWordsGPT/demo.jpg`: e-ink 출력 예시.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: 노트북 예시.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: 프롬프트 참고 자료.
- `demos/`: 이 README에서 사용하는 시각 데모.

## Development Notes

- 이 저장소는 모놀리식 패키지 앱이 아닌 레거시 스타일의 우산형 프로젝트입니다.
- Projects 표의 여러 연결 도구는 외부 저장소에 있으므로, 실행 세부사항은 각 저장소 README를 확인하세요.
- 일부 내부 문서는 이전 파일 레이아웃을 설명합니다(예: `scripts/lazy-care`는 분리된 스크립트를 언급하지만 현재 구현은 `SafeShell/safeshell_functions.sh`로 통합됨).
- `EinkWordsGPT`의 하드웨어 의존 코드는 Raspberry Pi + Waveshare e-paper 환경을 전제로 합니다.

### Assumptions (Explicit)

- 최상위 README를 표준 진입점으로 두고, 연결된 외부 프로젝트의 상세 실행 지침은 각 저장소에서 유지된다고 가정합니다.
- 이 저장소는 현재 루트 `requirements.txt`/`pyproject.toml`을 제공하지 않으므로 Python 패키지 버전은 의도적으로 고정하지 않았습니다.
- `EinkWordsGPT`의 Waveshare 하드웨어용 디바이스 드라이버 설치 단계는 대상 Raspberry Pi 환경에서 수행된다고 가정합니다.

## Troubleshooting

- `ModuleNotFoundError: waveshare_epd`: 대상 장치에 Waveshare e-paper 라이브러리를 설치하고 하드웨어 의존성이 충족되는지 확인하세요.
- OpenAI 인증 오류: 활성 셸/세션에 `OPENAI_API_KEY`가 설정되어 있는지 확인하세요.
- `words_phonetics.db` 또는 폰트 관련 `File not found`: 상대 경로가 올바르게 해석되도록 `code/EinkWordsGPT`에서 스크립트를 실행하세요.
- SafeShell 명령어를 찾을 수 없음: `safeshell_functions.sh`가 올바른 셸 프로필에 추가되었는지 확인하고 셸을 다시 로드하세요.
- `repo2text`가 파일을 생성하지 않음: `source_directory`가 존재하고 `.py` 파일을 포함하는지 확인하세요.

## Roadmap

- 모듈별 선택적 `requirements.txt`를 포함해 의존성 관리를 통합.
- 공통 워크플로를 위한 루트 수준 태스크 러너 또는 Makefile 추가.
- Raspberry Pi + Waveshare 배포를 위한 재현 가능한 설정 문서 확장.
- 유틸리티 스크립트와 데이터 변환 헬퍼 테스트 추가.
- `i18n/` 다국어 문서의 동등성(parity) 지속 개선.

## Community Contributions

전략적 게으름에 대한 여러분의 경험, 팁, 아이디어를 공유해 주세요.

- 생산성 해킹을 교환하는 포럼.
- 일상 루틴용 도구와 템플릿.
- 게으른 효율을 위한 협업 프로젝트.

## Contributing

콘텐츠, 스크립트, 프로젝트 문서 전반의 기여를 환영합니다.

Standard flow:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

특정 하위 모듈에 영향을 주는 변경이라면 해당 하위 모듈 README도 함께 업데이트해 주세요.

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

이 저장소는 MIT 라이선스로 배포됩니다. 자세한 내용은 [LICENSE](LICENSE)를 참고하세요.

참고:

- 최상위 프로젝트 라이선스: MIT.
- 일부 하위 폴더에는 자체 `LICENSE` 파일이 있으며, 충돌 시 해당 경로에서 가장 구체적인 라이선스 파일을 따르세요.

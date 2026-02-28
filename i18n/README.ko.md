[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# 게으름의 예술

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

AI 보조 기반의 실무형 생산성 실험, 언어 학습 시스템, 유틸리티 도구를 모아둔 저장소입니다.

> 낮은 레버리지를 갖는 일은 덜 하고, 높은 레버리지를 갖는 결과에 시간을 써보세요.

| 🎯 Focus | 🎛️ Primary stack | 🧭 Target |
|---|---|---|
| 반복 작업 자동화 | Python + shell | 인지 부하 감소 |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## 목차

- [개요](#overview)
- [기능](#features)
- [프로젝트](#projects)
- [프로젝트 구조](#project-structure)
- [게으름 접근 방식 개요](#overview-of-the-lazying-approach)
- [실전 팁과 요령](#practical-tips-and-tricks)
- [사용 사례](#use-cases)
- [AI 에이전트와 자동화](#ai-agents-and-automation)
- [언어 학습과 브이로그](#language-learning-and-vlogs)
- [필수 조건](#prerequisites)
- [설치](#installation)
- [구성](#configuration)
- [사용법](#usage)
- [예제](#examples)
- [개발 노트](#development-notes)
- [문제 해결](#troubleshooting)
- [로드맵](#roadmap)
- [커뮤니티 기여](#community-contributions)
- [기여하기](#contributing)
- [❤️ Support](#-support)
- [연결](#connect)
- [라이선스](#license)

<a id="overview"></a>
## 개요

`The Art of Lazying`은(는) 레거시 스타일의 상위 저장소로, 실전 AI 워크플로, 셸 유틸리티 도구, 라즈베리 파이 실험, 학습 자료를 실용적으로 모은 컬렉션입니다.

### 프로젝트 시그널

| 시그널 | 값 |
|---|---|
| 저장소 유형 | 레거시 상위 저장소 |
| 주요 런타임 | Python + shell 스크립트 |
| 하드웨어 초점 | Raspberry Pi + e-ink (모듈별) |
| 문서화 | `i18n/`에 다국어 README 모음 |
| 라이선스 | GNU General Public License 3.0 (루트 및 주요 하위 폴더) |

<a id="features"></a>
## 기능

- ✅ 전략적 게으름 프레임워크: 반복 작업보다 레버리지가 높은 작업을 우선 처리합니다.
- ✅ AI 기반 창작 도구 및 출판 관련 실험.
- ✅ e-ink 렌더링과 OpenAI 기반 단어 워크플로(`code/EinkWordsGPT`)를 활용한 언어 학습 유틸리티.
- ✅ 더 안전한 셸 작업(`saferm` / `unrm` / `removeitanyway`).
- ✅ DNS/IP 수집과 코드-텍스트 변환을 위한 경량 Python 유틸리티 스크립트.
- ✅ 언어별 README가 들어 있는 다국어 문서 허브.

<a id="projects"></a>
## 프로젝트

### 🤖 AI 기반 창작 도구

| 프로젝트 | 유형 | 초점 |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | 로컬 모듈 | OpenAI 기반 Raspberry Pi + Waveshare e-ink 단어 카드 표시 |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | 외부 프로젝트 | 단어 기원 분석 및 그래프형 표시 |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | 외부 프로젝트 | 언어 학습 유틸리티 프로젝트 |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | 외부 프로젝트 | CLIP 임베딩 + GPT를 활용한 자막 생성 |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | 외부 프로젝트 | 다국어 전사 파이프라인 |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | 외부 스크립트 | 자막/다국어 번역 지원 도구 |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | 외부 스크립트 | 미디어 메타데이터 자동 생성 |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | 외부 프로젝트 | 동영상 편집 및 자막 워크플로 |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | 외부 프로젝트 | 콘텐츠 발행 자동화 |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | 외부 프로젝트 | 모니터링 + 발행 오케스트레이션 |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | 외부 프로젝트 | 고급 프롬프트 및 AI 사용 패턴 워크플로 |

### 🛠️ 로컬 자동화 도구

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): 셸 사용자에게 더 안전한 삭제/복구 워크플로를 제공합니다.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): 도메인→IP 및 CIDR 목록 해결기.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): 하위 디렉터리의 Python 파일을 AI 검토용 텍스트 묶음으로 병합.

<a id="project-structure"></a>
## 프로젝트 구조

### 현재 저장소 구성

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

### 레거시 개념 구조 (과거 문서)

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
## 게으름 접근 방식 개요

이 저장소는 실무 생산성을 **전략적 게으름**으로 정리합니다. 가치가 낮은 판단은 자동화하고, 인지 에너지를 보존하며, 전술보다 시스템을 먼저 적용합니다.

핵심 원칙은 실용적인 80/20 관점입니다.

- 가장 높은 레버리지를 제공하는 상위 20% 작업을 식별합니다.
- 반복되는 흐름을 표준화/자동화합니다.
- 일상 실천에서 피할 수 있는 마찰을 제거합니다.

<a id="practical-tips-and-tricks"></a>
## 실전 팁과 요령

- 반복적인 명령 워크플로를 셸 함수로 바꿉니다.
- 짧은 계획 주기(포모도로 호환 템포)를 사용합니다.
- 반복 가능한 템플릿을 만들어 의사결정 피로를 줄입니다.
- 초안 작성/변환은 AI에게 먼저 맡기고, 이후 수동으로 검토합니다.

<a id="use-cases"></a>
## 사용 사례

- 크리에이터 워크플로에서 반복 작업을 위임하고 자동화합니다.
- AI 보조 요약으로 리서치/문서화 작업을 간소화합니다.
- 코드 맥락을 AI 분석용 텍스트로 빠르게 변환합니다.

<a id="ai-agents-and-automation"></a>
## AI 에이전트와 자동화

이 저장소에 포함된 실험은 다음을 포함합니다.

- 단어 학습과 콘텐츠 제작 중심의 실용적인 보조 워크플로.
- 운영 작업을 위한 스크립팅 가능한 DNS/IP 집계.
- AI 보조 코드 검토를 가속화하는 repo-to-text 내보내기.
- 실수로 삭제되는 일을 줄여주는 선택적 셸 레벨 안전 도구.

<a id="language-learning-and-vlogs"></a>
## 언어 학습과 브이로그

언어 관련 콘텐츠와 프로젝트는 적은 노력으로 꾸준함을 살리는 데 초점을 둡니다.

- e-ink 표시기 기반의 수동 노출 + 주기적 복습.
- 지원되는 하위 프로젝트들의 다국어 노트 워크플로.
- 브이로그 스크립트와 노트는 실전 루틴 엔지니어링의 예시입니다.

<a id="prerequisites"></a>
## 필수 조건

이 저장소는 모듈 기반 구조입니다. 루트 레벨에서 패키지 매니페스트가 없습니다.

### 환경 체크리스트

| Item | Baseline |
|---|---|
| OS | Linux/macOS (shell 도구), Windows WSL은 Python 스크립트에서 사용 가능 |
| Python | 3.9+ |
| 패키지 매니저 | `pip` |
| 버전 관리 | `git` |

### 모듈별 의존성 (소스 기준)

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`, Raspberry Pi/e-paper 실행 파일 (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic`: `dnspython`.
- `vlogs/repo2text`: 표준 라이브러리만 사용.
- `scripts/lazy-care/SafeShell`: `mv`, `realpath`가 있는 Bash/Zsh 셸 및 선택적 확인 흐름.

<a id="installation"></a>
## 설치

### 1) 클론

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) 권장 가상 환경

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) 모듈별 종속성 설치

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) 선택: SafeShell 부트스트랩

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # 또는 ~/.zshrc
source ~/.bashrc  # 또는 source ~/.zshrc
```

<a id="configuration"></a>
## 설정

### 1) OpenAI / EinkWordsGPT

두 `EinkWordsGPT` 스크립트는 `OpenAI()`를 직접 인스턴스화하므로 런타임에서 자격 증명이 노출되어야 합니다.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) SafeShell 휴지통 경로

`scripts/lazy-care/SafeShell/safeshell_functions.sh`에서는 `/mnt/disk/BIN/ROOT`가 기본 휴지통 경로로 하드코딩되어 있습니다. 필요하면 스크립트에서 직접 경로를 수정하세요.

### 3) `repo2text` 병합 경로

`vlogs/repo2text/convert-repo-to-merged-text.py`의 기본값은 다음과 같습니다.

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

실행 전 해당 값들을 변경하세요(해당 이름이 맞지 않을 경우).

### 4) `chatgpt-traffic` 사용자 지정 항목

`custom_ips`, `cidr`, 그리고 `domains`는 현재 `vlogs/chatgpt-traffic/chatgpt-traffic.py`에 내장되어 있습니다. 필요에 따라 직접 수정하세요.

<a id="usage"></a>
## 사용법

### 빠른 명령 표

| 작업 | 명령 경로 | 명령 |
|---|---|---|
| EinkWordsGPT 표시 루프 | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT 업데이트 | `code/EinkWordsGPT` | `python words_update.py` |
| 도메인/IP 해석기 | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| repo-to-text 병합 | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell 사용 | 쉘 프로필 + 현재 쉘 | `saferm`, `unrm`, `removeitanyway` |

### EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_gpt.py
python words_update.py
```

### ChatGPT 트래픽 해결기

```bash
cd vlogs/chatgpt-traffic
python chatgpt-traffic.py
```

### Repo-to-text 병합

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell (sourcing 후)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

<a id="examples"></a>
## 예제

- `code/EinkWordsGPT/demo.jpg`: e-ink 출력 샘플.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: 노트북 예제.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: 프롬프트 참조 자료.
- `demos/`: 프로젝트 문서에 사용되는 시각 자료.

<a id="development-notes"></a>
## 개발 노트

- 이 저장소는 레거시 상위 구조이며, 상세 동작은 모듈별 문서가 실제 기준입니다.
- 일부 프로젝트는 외부 GitHub 저장소입니다. 각 저장소의 README를 확인해 설정하세요.
- `EinkWordsGPT`는 하드웨어 종속형입니다(Raspberry Pi + Waveshare 화면).
- 일부 모듈별 의존성은 저장소 밖에서 선언되어 있어 시간이 지나며 문서와 달라질 수 있습니다.

### 가정 (명시)

- 저장소 루트와 주요 모듈 디렉터리는 별도 `LICENSE` 가이드가 없으면 **GNU GPL v3.0**을 사용합니다.
- 루트에는 `requirements.txt`, `pyproject.toml`, `package.json`이 없어 모듈별 설치 단계가 한곳에 집약되지 않습니다.

<a id="troubleshooting"></a>
## 문제 해결

- `ModuleNotFoundError: waveshare_epd`
  - 대상 장비에 Waveshare e-paper 모듈을 설치하고 하드웨어 드라이버를 확인하세요.
- OpenAI 요청이 인증 오류로 실패
  - 현재 셸/세션에서 `OPENAI_API_KEY`가 export되었는지 확인하세요.
- `words_phonetics.db`를 찾을 수 없음
  - 상대 경로가 해석되도록 `code/EinkWordsGPT`에서 EinkWordsGPT 스크립트를 실행하세요.
- `saferm`/`unrm` 사용 불가
  - `safeshell_functions.sh` 추가 후 셸 프로필을 다시 source 하세요.
- `repo2text` 출력이 없음
  - `source_directory`가 존재하고 `.py` 파일이 있는지 확인하세요.

<a id="roadmap"></a>
## 로드맵

- 모듈 의존성 문서를 정규화하고 모듈별 설치 예시를 추가합니다.
- 모듈 워크플로를 위한 선택적 루트 태스크 러너(Makefile/스크립트 엔트리포인트) 추가.
- Raspberry Pi + Waveshare 배포의 재현성 문서를 개선합니다.
- 유틸리티 스크립트용 간단한 자동화 테스트 추가.
- `i18n/`에서 언어 커버리지를 계속 확장합니다.

<a id="community-contributions"></a>
## 커뮤니티 기여

실용적인 개선, 자동화 아이디어, 언어 학습 실험을 공유하세요.

- 일상 작업을 위한 워크플로 템플릿.
- 유지보수 오버헤드를 줄이는 실전 게으름 패턴.
- 크로스 모듈 통합 및 스크립트 레벨 수정.

<a id="contributing"></a>
## 기여하기

기여를 환영합니다.

1. 저장소를 Fork 합니다.
2. 기능 브랜치를 생성합니다 (`git checkout -b feature/your-topic`).
3. 변경 사항을 커밋합니다 (`git commit -m 'Add feature'`).
4. 브랜치를 push하고 PR을 엽니다.

모듈별 변경이라면 해당 모듈의 로컬 README도 함께 업데이트하세요.

## 연결

| 채널 | 링크 |
|---|---|
| 🌐 웹사이트 | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ 이메일 | `lachlan@lazying.art` |

<a id="license"></a>
## 라이선스

이 저장소는 **GNU General Public License v3.0**으로 라이선스됩니다(자세한 내용은 [LICENSE](LICENSE) 참조).

참고:

- 루트 및 주요 모듈 디렉터리에는 GNU GPL을 적용한 `LICENSE` 파일이 포함되어 있습니다.
- 특정 하위 디렉터리에서 작업할 경우, 해당 범위에 맞는 가장 가까운 `LICENSE` 파일을 확인하세요.


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

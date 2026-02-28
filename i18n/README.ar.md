[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# فن الـ Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

مستودع يروّج للكسل الاستراتيجي من أجل حياة أبسط وأكثر إنتاجية، ويشمل وكلاء الذكاء الاصطناعي، وتعلّم اللغات، ومدونات فيديو مع نصائح عملية وحالات استخدام واقعية.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Projects](#projects)
- [Project Structure](#project-structure)
- [Introduction](#introduction)
- [The Theory of Lazying](#the-theory-of-lazying)
- [Practical Tips and Tricks](#practical-tips-and-tricks)
- [Use Cases](#use-cases)
- [AI Agents and Automation](#ai-agents-and-automation)
- [Language Learning and Vlogs](#language-learning-and-vlogs)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Examples](#examples)
- [Development Notes](#development-notes)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [Community Contributions](#community-contributions)
- [Contributing](#contributing)
- [Connect](#connect)
- [Support / Donate](#support--donate)
- [License](#license)

## Overview

`The Art of Lazying` هو مستودع مظلّة يجمع بين الفلسفة، والأتمتة العملية، وأدوات إبداعية مدعومة بالذكاء الاصطناعي، وتجارب تعلّم اللغات.

يتضمن:

- عرضًا لمشاريع وسير عمل مرتبطة بالذكاء الاصطناعي.
- سكربتات/أدوات محلية لعمليات Shell آمنة وسير عمل نفعية.
- مشروعًا قائمًا على العتاد لتعلّم اللغات (`EinkWordsGPT`) باستخدام Raspberry Pi + Waveshare e-ink + OpenAI.
- تجارب في المدونات/الأدوات مثل تجميع DNS/IP وتحويل المستودعات إلى نص.
- توثيقًا متعدد اللغات ضمن [`i18n/`](i18n).

### Quick Snapshot

| Focus | What you get |
|------|---|
| 🧠 Philosophy | مبادئ الكسل الاستراتيجي للعمل عالي الأثر |
| 🤖 AI | مساعدة إبداعية، تفريغ صوتي، ترجمة، دعم النشر |
| 🛠️ Utilities | حذف/استرجاع آمن في Shell، أدوات DNS/IP، تحويل المستودع إلى نص |
| 🌍 i18n | نسخ README بعدة لغات داخل `i18n/` |

## Features

- إطار عمل للكسل الاستراتيجي يركز على الجهد عالي الأثر.
- مراجع لسير عمل إبداعي ونشري مدعوم بالذكاء الاصطناعي.
- أدوات لتعلّم اللغات ونظام عرض دراسي بشاشة e-ink.
- مساعدات أمان Shell (`saferm`, `unrm`, `removeitanyway`).
- أدوات Python خفيفة لجمع DNS/IP ودمج نصوص قواعد الشيفرة.
- دعم README متعدد اللغات.

## Projects

### 🤖 AI-Powered Creative Tools

| Project | Description | Demo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | شاشة E-ink لتعلّم الكلمات مدعومة بـ GPT | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | تحليل أصل الكلمات وعرضه في مخطط بياني. | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | أدوات لتعلّم لغات بكفاءة وبأقل جهد | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | توليد تسميات للفيديو والصور باستخدام OpenAI CLIP embeddings + GPT decoder | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | أداة توليد وصف للفيديو: استخراج إطارات رئيسية عبر Katna/OpenCV وإنشاء الأوصاف بنموذج ViT+GPT-2 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | خط أنابيب تفريغ صوتي متعدد اللغات مع كشف دقيق للغة | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | كسر الحواجز اللغوية من أجل تبادل إبداعي عالمي | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | إنشاء بيانات وصفية تلقائيًا للفيديوهات | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | أداة تحرير فيديو تلقائي مدعومة بالذكاء الاصطناعي مع التفريغ الصوتي، والترجمة التلقائية، والإبراز، وتوليد البيانات الوصفية | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | تبسيط سير عمل نشر المحتوى | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | نظام آلي لمراقبة محتوى الفيديو ومعالجته ونشره على منصات متعددة | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | تقنيات متقدمة لاستخدام مساعدي الذكاء الاصطناعي بفعالية | |

### 🔄 Automation Tools

تشمل أدوات/أتمتة محلية في هذا المستودع:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): سير عمل أكثر أمانًا للحذف/الاسترجاع لمستخدمي Shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): محلّل domain-to-IP/CIDR مع إزالة التكرار.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): دمج ملفات Python حسب المجلد الفرعي إلى مخرجات نصية.

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

يقدّم The Art of Lazying مفهوم الكسل الاستراتيجي كطريقة لتحسين استخدام الطاقة والتركيز على ما يهم فعلًا. يستكشف هذا المستودع كيف يمكن للكسل المقصود أن يقود إلى إنتاجية أعلى، وإبداع أكبر، ورفاه أفضل.

## The Theory of Lazying

مقدمة شاملة لمبادئ الكسل الاستراتيجي، مع التركيز على تعظيم الإنتاجية والرفاه عبر تحديد الأولويات، والتفويض، وأتمتة المهام.

المبدأ الأساسي هو تطبيق قاعدة باريتو 80/20 في الحياة اليومية: تحديد 20% من الأنشطة التي تولّد 80% من النتائج المرغوبة.

## Practical Tips and Tricks

مجموعة من النصائح العملية القابلة للتطبيق لتفعيل مبادئ الكسل في العمل والعلاقات والعناية الذاتية:

- أتمتة المهام المتكررة.
- استخدام تقنية Pomodoro لإدارة الوقت.
- إنشاء أنظمة تقلّل إرهاق اتخاذ القرار.
- الاستفادة من أدوات الذكاء الاصطناعي للمساعدة.

## Use Cases

أمثلة واقعية توضّح كيف تحل مبادئ الكسل المشكلات وتحسّن الكفاءة:

- كيف يستخدم رواد الأعمال التفويض والأتمتة للتركيز على نمو الأعمال.
- كيف يبسّط الأكاديميون سير عمل البحث.
- كيف يحسّن صنّاع المحتوى عملية الإنتاج لديهم.

## AI Agents and Automation

استكشف تطوير وكلاء الذكاء الاصطناعي وأدوات الأتمتة التي تبسّط المهام:

- استخدام ChatGPT كمساعد شخصي.
- بناء سير عمل أتمتة مخصص.
- إنشاء شاشات e-ink للتعلّم السلبي.

## Language Learning and Vlogs

موارد وتقنيات لتعلّم لغات بكفاءة، إلى جانب مدونات فيديو توثّق رحلة الـ lazying:

- إنشاء تعلّم لغات مخصص باستخدام التكرار المتباعد.
- تطبيق تقنيات التعلّم الغامر.
- بناء مشاريع تشجّع التعلّم السلبي.

## Prerequisites

هذا المستودع متعدد المشاريع ولا يحتوي على ملف اعتماديات موحّد على المستوى الأعلى. ثبّت فقط ما تحتاجه لكل وحدة.

متطلبات شائعة:

- `git`
- Python `3.9+` (موصى به)
- `pip`
- أدوات بيئة افتراضية اختيارية (`python -m venv`)

إشارات خاصة بكل وحدة من الشيفرة المصدرية/ملفات README:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, مكتبة Python الخاصة بـ Waveshare e-paper (`waveshare_epd`) وعتاد متوافق.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: Bash/Zsh shell.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Recommended) Create a Python virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Install Python dependencies for selected modules

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell setup (optional)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Configuration

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` و `words_update.py` يستخدمان `OpenAI()` ويتوقعان توفر بيانات الاعتماد في البيئة.
- الموصى به:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell trash location

- `safeshell_functions.sh` يستخدم مسارًا أساسيًا ثابتًا لسلة المهملات:

```bash
/mnt/disk/BIN/ROOT
```

عدّل هذا المسار في السكربت إذا كان جهازك يستخدم تخطيطًا مختلفًا.

### repo2text source/target directories

- `vlogs/repo2text/convert-repo-to-merged-text.py` يضبط حاليًا:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

حرّر هذه المتغيرات قبل التنفيذ.

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

- `code/EinkWordsGPT/demo.jpg`: نموذج لمخرجات شاشة e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: مثال notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: مرجع prompts.
- `demos/`: عروض مرئية مستخدمة في README هذا.

## Development Notes

- هذا المستودع مشروع umbrella بطابع legacy، وليس تطبيقًا موحّدًا ومعبّأً كحزمة واحدة.
- عدة أدوات مرتبطة في جدول Projects موجودة في مستودعات خارجية؛ استخدم ملفات README الخاصة بها لتفاصيل التشغيل.
- بعض الوثائق الداخلية تصف تخطيطات ملفات أقدم (مثلًا، `scripts/lazy-care` يشير إلى سكربتات منفصلة بينما التنفيذ الحالي مدمج في `SafeShell/safeshell_functions.sh`).
- الشيفرة المعتمدة على العتاد في `EinkWordsGPT` تفترض بيئة Raspberry Pi + Waveshare e-paper.

### Assumptions (Explicit)

- README على المستوى الأعلى هو نقطة الدخول الأساسية، بينما تُحافَظ تعليمات التشغيل التفصيلية للمشاريع الخارجية المرتبطة في مستودعاتها الخاصة.
- تُركت إصدارات حزم Python مفتوحة عمدًا لأن هذا المستودع لا يوفّر حاليًا `requirements.txt`/`pyproject.toml` في الجذر.
- بالنسبة إلى `EinkWordsGPT`، يُفترض تنفيذ خطوات تثبيت تعريفات الجهاز الخاصة بعتاد Waveshare على بيئة Raspberry Pi المستهدفة.

## Troubleshooting

- `ModuleNotFoundError: waveshare_epd`: ثبّت مكتبات Waveshare e-paper على الجهاز المستهدف وتحقق من الاعتماديات الخاصة بالعتاد.
- أخطاء مصادقة OpenAI: تأكد من ضبط `OPENAI_API_KEY` في shell/session النشط.
- `File not found` حول `words_phonetics.db` أو الخطوط: شغّل السكربتات من `code/EinkWordsGPT` حتى تُحل المسارات النسبية بشكل صحيح.
- أوامر SafeShell غير موجودة: تأكد من إلحاق `safeshell_functions.sh` بملف إعداد shell الصحيح ثم أعد تحميل shell.
- `repo2text` لا يولّد ملفات: تحقق من أن `source_directory` موجود ويحتوي ملفات `.py`.

## Roadmap

- توحيد إدارة الاعتماديات مع ملفات `requirements.txt` اختيارية لكل وحدة.
- إضافة مشغلات مهام على مستوى الجذر أو Makefile لسير العمل الشائع.
- توسيع وثائق الإعداد القابلة لإعادة الإنتاج لنشر Raspberry Pi + Waveshare.
- إضافة اختبارات لسكربتات الأدوات ومساعدات تحويل البيانات.
- مواصلة تحسين التكافؤ في التوثيق متعدد اللغات داخل `i18n/`.

## Community Contributions

شارك تجاربك ونصائحك وأفكارك حول الكسل الاستراتيجي:

- منتدى لتبادل حِيَل الإنتاجية.
- أدوات وقوالب للروتين اليومي.
- مشاريع تعاونية لكفاءة أكثر بجهد أقل.

## Contributing

نرحّب بالمساهمات في المحتوى والسكربتات ووثائق المشاريع.

التدفق القياسي:

1. Fork المشروع.
2. أنشئ فرع الميزة (`git checkout -b feature/AmazingFeature`).
3. نفّذ commit لتغييراتك (`git commit -m 'Add some AmazingFeature'`).
4. ادفع الفرع (`git push origin feature/AmazingFeature`).
5. افتح Pull Request.

إذا أثّر تغييرك على وحدة فرعية محددة، حدّث README الخاص بتلك الوحدة أيضًا.

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

هذا المستودع مرخّص بموجب رخصة MIT. راجع [LICENSE](LICENSE) للتفاصيل.

ملاحظات:

- رخصة المشروع على المستوى الأعلى: MIT.
- بعض المجلدات الفرعية تتضمن ملفات `LICENSE` خاصة بها؛ عند الشك، اتبع ملف الترخيص الأكثر تحديدًا ضمن ذلك المسار.

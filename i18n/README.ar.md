[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# فن الكسل

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

مستودع على مستوى المشروع للتجارب العملية المتعلقة بالإنتاجية بمساعدة الذكاء الاصطناعي، وأنظمة تعلم اللغات، وأدوات المساعدة.

> اعمل أقل في الأعمال منخفضة العائد، وركّز الجهد على النتائج عالية الأثر.

| 🎯 الهدف | 🎛️ المكدس الأساسي | 🧭 الهدف |
|---|---|---|
| أتمتة المهام المتكررة | Python + shell | تقليل الحمل المعرفي |

---

![عرض إنك-وردز-جي بي تي](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## جدول المحتويات

- [نظرة عامة](#overview)
- [الميزات](#features)
- [المشاريع](#projects)
- [هيكل المشروع](#project-structure)
- [نظرة عامة على نهج الكسل](#overview-of-the-lazying-approach)
- [النصائح والحيل العملية](#practical-tips-and-tricks)
- [حالات الاستخدام](#use-cases)
- [الوكلاء الذكيون والأتمتة](#ai-agents-and-automation)
- [تعلم اللغات والفلوغز](#language-learning-and-vlogs)
- [المتطلبات الأساسية](#prerequisites)
- [التثبيت](#installation)
- [الإعداد](#configuration)
- [الاستخدام](#usage)
- [أمثلة](#examples)
- [ملاحظات التطوير](#development-notes)
- [استكشاف المشكلات](#troubleshooting)
- [خطة الطريق](#roadmap)
- [مساهمات المجتمع](#community-contributions)
- [المساهمة](#contributing)
- [❤️ Support](#-support)
- [التواصل](#connect)
- [الرخصة](#license)

<a id="overview"></a>
## نظرة عامة

`The Art of Lazying` هو مستودع مظلة بنمط legacy: مجموعة براغماتية من سيرات عمل الذكاء الاصطناعي، وأدوات الـ shell، وتجارب Raspberry Pi، وموارد التعلم.

### إشارات المشروع

| المؤشر | القيمة |
|---|---|
| نوع المستودع | Legacy umbrella repo |
| وقت التشغيل الأساسي | Python + shell scripts |
| تركيز العتاد | Raspberry Pi + e-ink (حسب الوحدة) |
| التوثيق | مجموعة README متعددة اللغات داخل `i18n/` |
| الترخيص | رخصة GNU General Public License 3.0 (جذر المشروع والمجلدات الفرعية الأساسية) |

<a id="features"></a>
## الميزات

- ✅ إطار عمل للكسل الاستراتيجي: أعطِ الأولوية للمهام عالية الرافعة بدلًا من العمليات المتكررة.
- ✅ أدوات إبداعية بمساعدة الذكاء الاصطناعي وتجارب مرتبطة بالنشر.
- ✅ أداة تعلم لغة مع عرض على شاشة e-ink وسير عمل كلمات مدعوم من OpenAI (`code/EinkWordsGPT`).
- ✅ تشغيل shell أكثر أمانًا (`saferm` / `unrm` / `removeitanyway`).
- ✅ سكربتات Python خفيفة لجمع DNS/IP وتحويل الكود إلى نص.
- ✅ مركز توثيق متعدد اللغات مع نسخ README لكل لغة.

<a id="projects"></a>
## المشاريع

### 🤖 أدوات إبداعية مدعومة بالذكاء الاصطناعي

| المشروع | النوع | التركيز |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | وحدة محلية | عرض بطاقات كلمات Raspberry Pi + Waveshare e-ink باستخدام OpenAI |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | مشروع خارجي | تحليل أصول الكلمات وتقديمها على شكل رسم بياني |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | مشروع خارجي | أداة عملية لتعلم اللغات |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | مشروع خارجي | الترجمة التوضيحية باستخدام CLIP embeddings + GPT |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | مشروع خارجي | خط أنابيب تفريغ متعدد اللغات |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | سكربت خارجي | أداة مساعدة للترجمة المترابطة/الترجمة متعددة اللغات |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | سكربت خارجي | توليد تلقائي لبيانات وصف الوسائط |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | مشروع خارجي | تحرير الفيديو وسير عمل الترجمة الفرعية |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | مشروع خارجي | أتمتة نشر المحتوى |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | مشروع خارجي | المراقبة + تنسيق عمليات النشر |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | مشروع خارجي | أنماط متقدمة لصياغة التعليمات واستخدام الذكاء الاصطناعي |

### 🛠️ أدوات أتمتة محلية

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): سير عمل حذف/استرجاع أكثر أمانًا لمستخدمي shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): محلل DNS/domain-to-IP + مدوّن قوائم CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): يدمج ملفات Python الفرعية إلى حزم نصية لمراجعة الذكاء الاصطناعي.

<a id="project-structure"></a>
## هيكل المشروع

### التخطيط الحالي للمستودع

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

### الهيكل المفاهيمي القديم (توثيقي)

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
## نظرة عامة على نهج الكسل

يقوم هذا المستودع بتصوير الإنتاجية العملية من خلال **الكسل الاستراتيجي**: أتمتة القرارات منخفضة القيمة، والحفاظ على الطاقة الذهنية، وتطبيق الأنظمة قبل التكتيكات.

المبدأ الأساسي ما زال رؤية عملية على أساس قاعدة 80/20:

- تحديد أعلى 20% من الإجراءات ذات التأثير الأعلى.
- توحيد/أتمتة المسارات المتكررة.
- إزالة الاحتكاك غير الضروري في الممارسة اليومية.

<a id="practical-tips-and-tricks"></a>
## النصائح والحيل العملية

- استبدل تدفقات الأوامر المتكررة بدوال shell.
- استخدم دورات تخطيط قصيرة (متوافقة مع تقنية بومودورو).
- قلل إرهاق القرار بإنشاء قوالب قابلة للتكرار.
- اسمح للذكاء الاصطناعي بالقيام بالصياغة الأولى والتحويل، ثم راجع يدويًا.

<a id="use-cases"></a>
## حالات الاستخدام

- تفويض وأتمتة العمليات المتكررة في سير عمل المنصات الإبداعية.
- تبسيط مهام البحث والتوثيق عبر ملخصات مدعومة بالذكاء الاصطناعي.
- تحويل سياق الكود بسرعة إلى نص جاهز للتحليل بمساعدة الذكاء الاصطناعي.

<a id="ai-agents-and-automation"></a>
## الوكلاء الذكيون والأتمتة

التجارب الممثلة في هذا المستودع تشمل:

- سير عمل مساعد عملي حول تعلم الكلمات وإنشاء المحتوى.
- جمع DNS/IP قابل للبرمجة لمهام التشغيل.
- تصدير repository-to-text لقراءة الكود بسرعة بمساعدة الذكاء الاصطناعي.
- أدوات أمان اختيارية على مستوى الـ shell لمنع أخطاء الحذف المدمرة.

<a id="language-learning-and-vlogs"></a>
## تعلم اللغات والفلوغز

المحتوى والمشاريع المتعلقة باللغات تركز على الثبات بجهد منخفض:

- التعرض السلبي + المراجعة الدورية عبر عرض e-ink.
- سير عمل ملاحظات عابرة للغات في المشاريع الفرعية المدعومة.
- سيناريوهات ودفاتر ملاحظات الفلوغز كمثال لهندسة الروتين العملي.

<a id="prerequisites"></a>
## المتطلبات الأساسية

هذا المستودع يعتمد على وحدات منفصلة؛ لا توجد حزمة إدارة تبعيات على مستوى الجذر.

### قائمة التحقق البيئية

| البند | الحد الأدنى |
|---|---|
| نظام التشغيل | Linux/macOS (أدوات shell)، Windows WSL مقبول لسكربتات Python |
| Python | 3.9+ |
| مدير الحزم | `pip` |
| التحكم بالإصدار | `git` |

### اعتماديات على مستوى الوحدات (مستمدة من المصدر)

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`، وملفات تشغيل Raspberry Pi/e-paper (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic`: `dnspython`.
- `vlogs/repo2text`: مكتبة Python القياسية فقط.
- `scripts/lazy-care/SafeShell`: Bash/Zsh مع `mv` و`realpath` وعبور تأكيد اختياري.

<a id="installation"></a>
## التثبيت

### 1) استنساخ المستودع

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) إعداد بيئة افتراضية (موصى به)

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) تثبيت اعتماديات الوحدات

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) اختيارية: تهيئة SafeShell

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # أو ~/.zshrc
source ~/.bashrc  # أو source ~/.zshrc
```

<a id="configuration"></a>
## الإعداد

### 1) OpenAI / EinkWordsGPT

يستدعي كل من سكربتي EinkWordsGPT `OpenAI()` مباشرة، لذلك يجب أن تتوفر بيانات الاعتماد أثناء التنفيذ.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) موقع سلة Safeshell المؤقتة

`/mnt/disk/BIN/ROOT` هو مسار السلة الافتراضي المكتوب صراحة داخل `scripts/lazy-care/SafeShell/safeshell_functions.sh`. عدّل هذا المسار داخل السكربت إذا لزم.

### 3) مسارات دمج `repo2text`

القيم الافتراضية في `vlogs/repo2text/convert-repo-to-merged-text.py` هي:

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

غيّر الاثنين قبل التشغيل ما لم تكن تعمل من مستودع يستخدم الأسماء نفسها.

### 4) المدخلات المخصصة في `chatgpt-traffic`

`custom_ips` و`cidr` و`domains` مضمّنة حاليًا داخل `vlogs/chatgpt-traffic/chatgpt-traffic.py`. عدّلها مباشرة حسب الحاجة.

<a id="usage"></a>
## الاستخدام

### جدول الأوامر السريع

| المهمة | مسار الأمر | الأمر |
|---|---|---|
| حلقة عرض EinkWordsGPT | `code/EinkWordsGPT` | `python words_gpt.py` |
| محدث EinkWordsGPT | `code/EinkWordsGPT` | `python words_update.py` |
| محلّل النطاق/IP | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| دمج repo-to-text | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| استخدام SafeShell | ملف تعريف shell + shell الحالي | `saferm`, `unrm`, `removeitanyway` |

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

### SafeShell (بعد التحميل)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

<a id="examples"></a>
## أمثلة

- `code/EinkWordsGPT/demo.jpg`: نموذج مخرج e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: مثال notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: مرجع التعليمات.
- `demos/`: عناصر بصرية تُستخدم في توثيق المشروع.

<a id="development-notes"></a>
## ملاحظات التطوير

- هذا مستودع umbrella تاريخي؛ توثيق الوحدات هو المصدر الأوثق للسلوك التفصيلي وقت التشغيل.
- بعض المشاريع المذكورة هي مستودعات GitHub خارجية؛ استخدم README الخاص بكل مستودع للإعداد.
- `EinkWordsGPT` مرتبط بعتاد (Raspberry Pi + شاشة Waveshare).
- تعتمد بعض اعتماديات الوحدات على تعريفات خارج هذا المستودع وقد تتغير بمرور الوقت.

### الافتراضات الصريحة

- جذر المستودع والدلائل الأساسية للوحدات يستخدمان **GNU GPL v3.0** ما لم يذكر دليل فرعي آخر تعليمات ترخيص مختلفة.
- خطوات التثبيت غير متمركزة عمدًا لعدم وجود `requirements.txt` أو `pyproject.toml` أو `package.json` على مستوى الجذر.

<a id="troubleshooting"></a>
## استكشاف المشكلات

- `ModuleNotFoundError: waveshare_epd`
  - ثبّت وحدات e-paper الخاصة بـ Waveshare على الجهاز الهدف وتحقق من تعريفات العتاد (drivers).
- فشل طلبات OpenAI بسبب خطأ مصادقة
  - تأكد من تصدير `OPENAI_API_KEY` في shell/session النشط.
- `words_phonetics.db` غير موجود
  - شغّل سكربتات EinkWordsGPT من `code/EinkWordsGPT` حتى تُحل المسارات النسبية بشكل صحيح.
- `saferm`/`unrm` غير متاح
  - أعد تحميل ملف تعريف shell بعد إضافة `safeshell_functions.sh`.
- `repo2text` لا ينتج نتائج
  - تأكد من وجود `source_directory` وأنه يحتوي ملفات `.py`.

<a id="roadmap"></a>
## خارطة الطريق

- توحيد توثيق اعتماديات الوحدات وإضافة مقاطع إعداد مخصصة لكل وحدة.
- إضافة مشغّل جذري اختياري للمشروع (Makefile / نقطة دخول سكربت) لتنسيق سير العمل.
- تحسين وثائق قابلية إعادة الإنتاج لنشر Raspberry Pi + Waveshare.
- إضافة اختبارات آلية بسيطة للأدوات المساعدة.
- الاستمرار في توسيع التماثل اللغوي داخل `i18n/`.

<a id="community-contributions"></a>
## مساهمات المجتمع

شارك في تحسينات عملية، وأفكار أتمتة، وتجارب تعلم لغات:

- قوالب سير عمل للمهام الروتينية.
- أنماط كسل عملية تقلل من عبء الصيانة.
- تكاملات بين الوحدات وإصلاحات على مستوى السكربت.

<a id="contributing"></a>
## المساهمة

المساهمات مرحّب بها.

1. اعمل Fork للمستودع.
2. أنشئ فرع ميزة (`git checkout -b feature/your-topic`).
3. أجر commit للتغييرات (`git commit -m 'Add feature'`).
4. ادفع الفرع وافتح PR.

إذا كان تغيّرُك متعلقًا بوحدة معيّنة، فحدّث README المحلي لتلك الوحدة أيضًا.

## التواصل

| القناة | الرابط |
|---|---|
| 🌐 الموقع | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ البريد الإلكتروني | `lachlan@lazying.art` |

<a id="license"></a>
## الرخصة

هذا المستودع مرخّص بموجب **GNU General Public License v3.0** (راجع [LICENSE](LICENSE)).

ملاحظات:

- جذر المستودع والمجلدات الأساسية للوحدات تتضمن ملفات `LICENSE` تستخدم GNU GPL.
- إذا كنت تعمل داخل مجلد فرعي معيّن، فاستخدم أقرب ملف `LICENSE` لتحديد شروط النطاق.


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

Ein Repository, das strategische Faulheit fuer ein vereinfachtes, produktives Leben foerdert und dabei KI-Agenten, Sprachenlernen und Vlogs mit praktischen Tipps und realen Anwendungsfaellen zusammenbringt.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Inhaltsverzeichnis

- [Ueberblick](#ueberblick)
- [Funktionen](#funktionen)
- [Projekte](#projekte)
- [Projektstruktur](#projektstruktur)
- [Einfuehrung](#einfuehrung)
- [Die Theorie des Lazying](#die-theorie-des-lazying)
- [Praktische Tipps und Tricks](#praktische-tipps-und-tricks)
- [Anwendungsfaelle](#anwendungsfaelle)
- [KI-Agenten und Automatisierung](#ki-agenten-und-automatisierung)
- [Sprachenlernen und Vlogs](#sprachenlernen-und-vlogs)
- [Voraussetzungen](#voraussetzungen)
- [Installation](#installation)
- [Konfiguration](#konfiguration)
- [Nutzung](#nutzung)
- [Beispiele](#beispiele)
- [Entwicklungsnotizen](#entwicklungsnotizen)
- [Fehlerbehebung](#fehlerbehebung)
- [Roadmap](#roadmap)
- [Community-Beitraege](#community-beitraege)
- [Mitwirken](#mitwirken)
- [Kontakt](#kontakt)
- [Support / Spenden](#support--spenden)
- [Lizenz](#lizenz)

## Ueberblick

`The Art of Lazying` ist ein uebergreifendes Repository, das Philosophie, praktische Automatisierung, KI-gestuetzte Kreativ-Tools und Experimente zum Sprachenlernen verbindet.

Es enthaelt:

- Eine Uebersicht verknuepfter KI-Projekte und Workflows.
- Lokale Skripte/Tools fuer sichere Shell-Operationen und Utility-Workflows.
- Ein hardwarebasiertes Sprachlernprojekt (`EinkWordsGPT`) mit Raspberry Pi + Waveshare E-Ink + OpenAI.
- Vlog-/Tooling-Experimente wie DNS/IP-Aggregation und Repository-zu-Text-Konvertierung.
- Mehrsprachige Dokumentation unter [`i18n/`](i18n).

### Kurzer Ueberblick

| Fokus | Was du bekommst |
|------|---|
| 🧠 Philosophie | Prinzipien strategischer Faulheit fuer Arbeit mit hoher Hebelwirkung |
| 🤖 KI | Kreative Assistenz, Transkription, Uebersetzung, Unterstuetzung bei der Veroeffentlichung |
| 🛠️ Utilities | Sichere Shell-Loeschung/Wiederherstellung, DNS/IP-Tools, Repo-Text-Konvertierung |
| 🌍 i18n | README-Varianten in mehreren Sprachen unter `i18n/` |

## Funktionen

- Framework fuer strategische Faulheit mit Fokus auf wirkungsstarke Anstrengung.
- Referenzen fuer KI-gestuetzte kreative und Publishing-Workflows.
- Utilities fuer Sprachenlernen und ein E-Ink-Lerndisplay-System.
- Shell-Sicherheitshelfer (`saferm`, `unrm`, `removeitanyway`).
- Leichtgewichtige Python-Utilities fuer DNS/IP-Erfassung und Text-Zusammenfuehrung von Codebases.
- Mehrsprachige README-Unterstuetzung.

## Projekte

### 🤖 KI-gestuetzte Kreativ-Tools

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

### 🔄 Automatisierungs-Tools

Lokale Automatisierung/Tooling in diesem Repository umfasst:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): sicherer Loesch-/Wiederherstellungs-Workflow fuer Shell-Nutzer.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): Domain-zu-IP/CIDR-Resolver mit Duplikatbereinigung.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): fuehrt Python-Dateien pro Unterverzeichnis in Textartefakte zusammen.

## Projektstruktur

### Aktuelle Repository-Struktur

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

### Urspruengliche konzeptionelle Ordnerstruktur (beibehalten)

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

## Einfuehrung

The Art of Lazying zeigt strategische Faulheit als Ansatz, den Energieeinsatz zu optimieren und den Fokus auf das wirklich Wichtige zu legen. Dieses Repository untersucht, wie absichtsvolle Faulheit zu hoeherer Produktivitaet, Kreativitaet und Wohlbefinden fuehren kann.

## Die Theorie des Lazying

Eine umfassende Einfuehrung in die Prinzipien strategischer Faulheit, mit Fokus darauf, Produktivitaet und Wohlbefinden durch Priorisieren, Delegieren und Automatisieren zu maximieren.

Das Kernprinzip ist, Paretos 80/20-Regel auf den Alltag anzuwenden: die 20 % der Aktivitaeten zu identifizieren, die 80 % der gewuenschten Ergebnisse liefern.

## Praktische Tipps und Tricks

Eine Sammlung umsetzbarer Hinweise, wie sich Lazying-Prinzipien auf Arbeit, Beziehungen und Selbstfuersorge anwenden lassen:

- Wiederkehrende Aufgaben automatisieren.
- Die Pomodoro-Technik fuer Zeitmanagement nutzen.
- Systeme aufbauen, die Entscheidungserschoepfung reduzieren.
- KI-Tools als Unterstuetzung einsetzen.

## Anwendungsfaelle

Praxisnahe Beispiele, wie Lazying-Prinzipien Probleme loesen und Effizienz verbessern:

- Wie Unternehmer Delegation und Automatisierung nutzen, um sich auf Wachstum zu konzentrieren.
- Wie Akademiker Forschungs-Workflows verschlanken.
- Wie Content Creator ihren Produktionsprozess optimieren.

## KI-Agenten und Automatisierung

Entdecke die Entwicklung von KI-Agenten und Automatisierungstools, die Aufgaben vereinfachen:

- ChatGPT als persoenlichen Assistenten nutzen.
- Eigene Automatisierungs-Workflows aufbauen.
- E-Ink-Displays fuer passives Lernen erstellen.

## Sprachenlernen und Vlogs

Ressourcen und Techniken fuer effizientes Sprachenlernen sowie Vlogs, die die Lazying-Reise dokumentieren:

- Personalisiertes Sprachenlernen mit Spaced Repetition erstellen.
- Immersive Lerntechniken umsetzen.
- Projekte bauen, die passives Lernen foerdern.

## Voraussetzungen

Dieses Repository umfasst mehrere Projekte und enthaelt kein einzelnes top-level Abhaengigkeitsmanifest. Installiere nur, was du pro Modul benoetigst.

Allgemeine Anforderungen:

- `git`
- Python `3.9+` (empfohlen)
- `pip`
- Optionale Virtual-Environment-Tools (`python -m venv`)

Modulspezifische Hinweise aus Quellcode/READMEs:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, Waveshare E-Paper Python Library (`waveshare_epd`) und kompatible Hardware.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: Bash/Zsh-Shell.

## Installation

### 1. Repository klonen

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Empfohlen) Python Virtual Environment erstellen

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Python-Abhaengigkeiten fuer ausgewaehlte Module installieren

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. SafeShell einrichten (optional)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Konfiguration

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` und `words_update.py` verwenden `OpenAI()` und erwarten verfuegbare Zugangsdaten in deiner Umgebung.
- Empfohlen:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell Papierkorb-Pfad

- `safeshell_functions.sh` verwendet einen festen Basis-Papierkorbpfad:

```bash
/mnt/disk/BIN/ROOT
```

Passe diesen Pfad im Skript an, falls dein System ein anderes Layout verwendet.

### repo2text Quell-/Zielverzeichnisse

- `vlogs/repo2text/convert-repo-to-merged-text.py` setzt aktuell:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Bearbeite diese Variablen vor der Ausfuehrung.

## Nutzung

### EinkWordsGPT Display-Loop ausfuehren (Hardware-Setup erforderlich)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### EinkWordsGPT Wortpflege-/Update-Skript ausfuehren

```bash
cd code/EinkWordsGPT
python words_update.py
```

### ChatGPT Traffic Domain/IP-Resolver ausfuehren

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Python-Datei-Merger fuer das Repository ausfuehren

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell-Befehle nach dem Sourcing verwenden

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Beispiele

- `code/EinkWordsGPT/demo.jpg`: Beispielausgabe auf dem E-Ink-Display.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: Notebook-Beispiel.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: Prompt-Referenz.
- `demos/`: visuelle Demos, die in diesem README verwendet werden.

## Entwicklungsnotizen

- Dieses Repository ist ein uebergreifendes Legacy-Projekt und keine monolithisch paketierte App.
- Mehrere im Projekt-Table verlinkte Tools liegen in externen Repositories; nutze deren eigene READMEs fuer Laufzeitdetails.
- Einige interne Dokus beschreiben aeltere Dateilayouts (z. B. verweisen `scripts/lazy-care` auf gesplittete Skripte, waehrend die aktuelle Implementierung in `SafeShell/safeshell_functions.sh` konsolidiert ist).
- Hardwareabhaengiger Code in `EinkWordsGPT` setzt eine Raspberry Pi + Waveshare E-Paper Umgebung voraus.

### Annahmen (Explizit)

- Das top-level README ist der kanonische Einstiegspunkt, waehrend detaillierte Ausfuehrungsanleitungen fuer verlinkte externe Projekte in deren eigenen Repositories gepflegt werden.
- Python-Paketversionen bleiben absichtlich offen, da dieses Repo derzeit kein root `requirements.txt`/`pyproject.toml` bereitstellt.
- Fuer `EinkWordsGPT` wird erwartet, dass Device-Driver-Installationsschritte fuer Waveshare-Hardware in der Ziel-Raspberry-Pi-Umgebung ausgefuehrt werden.

## Fehlerbehebung

- `ModuleNotFoundError: waveshare_epd`: Installiere Waveshare-E-Paper-Bibliotheken auf dem Zielgeraet und pruefe hardware-spezifische Abhaengigkeiten.
- OpenAI-Authentifizierungsfehler: Pruefe, ob `OPENAI_API_KEY` in der aktiven Shell/Session gesetzt ist.
- `File not found` bei `words_phonetics.db` oder Fonts: Fuehre Skripte aus `code/EinkWordsGPT` aus, damit relative Pfade korrekt aufgeloest werden.
- SafeShell-Befehle nicht gefunden: Stelle sicher, dass `safeshell_functions.sh` an das richtige Shell-Profil angehaengt wurde, und lade die Shell neu.
- `repo2text` erzeugt keine Dateien: Pruefe, ob `source_directory` existiert und `.py`-Dateien enthaelt.

## Roadmap

- Abhaengigkeitsmanagement vereinheitlichen, mit optionalen `requirements.txt` pro Modul.
- Root-Level Task-Runner oder Makefile fuer haeufige Workflows ergaenzen.
- Reproduzierbare Setup-Dokumentation fuer Raspberry Pi + Waveshare Deployment erweitern.
- Tests fuer Utility-Skripte und Daten-Transformationshelfer hinzufuegen.
- Mehrsprachige Dokumentationsparitaet in `i18n/` weiter verbessern.

## Community-Beitraege

Teile deine eigenen Erfahrungen, Tipps und Ideen zu strategischer Faulheit:

- Forum zum Austausch von Produktivitaets-Hacks.
- Tools und Vorlagen fuer taegliche Routinen.
- Kollaborative Projekte fuer entspannte Effizienz.

## Mitwirken

Beitraege sind fuer Inhalte, Skripte und Projektdokumentation willkommen.

Standardablauf:

1. Forke das Projekt.
2. Erstelle deinen Feature-Branch (`git checkout -b feature/AmazingFeature`).
3. Commite deine Aenderungen (`git commit -m 'Add some AmazingFeature'`).
4. Pushe in den Branch (`git push origin feature/AmazingFeature`).
5. Oeffne einen Pull Request.

Wenn deine Aenderung ein bestimmtes Submodul betrifft, aktualisiere auch das README dieses Submoduls.

## Kontakt

| Channel | Link |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## Support / Spenden

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

## Lizenz

Dieses Repository ist unter der MIT-Lizenz lizenziert. Siehe [LICENSE](LICENSE) fuer Details.

Hinweise:

- Top-level Projektlizenz: MIT.
- Einige Unterordner enthalten eigene `LICENSE`-Dateien; im Zweifel gilt die spezifischste Lizenzdatei in diesem Pfad.

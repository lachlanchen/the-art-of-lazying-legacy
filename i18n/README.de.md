[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

Ein Repository, das strategische Faulheit für ein vereinfachtes, produktives Leben fördert und dabei KI-Agenten, Sprachenlernen und Vlogs mit praktischen Tipps und realen Anwendungsszenarien verbindet.

> Arbeite weniger an Aufgaben mit geringem Nutzen und liefere mehr aussagekräftige Ergebnisse.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Inhaltsverzeichnis

- [Überblick](#überblick)
- [Funktionen](#funktionen)
- [Projekte](#projekte)
- [Projektstruktur](#projektstruktur)
- [Einführung](#einführung)
- [Die Theorie des Lazying](#die-theorie-des-lazying)
- [Praktische Tipps und Tricks](#praktische-tipps-und-tricks)
- [Anwendungsfälle](#anwendungsfälle)
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
- [Community-Beiträge](#community-beiträge)
- [Mitwirken](#mitwirken)
- [Kontakt](#kontakt)
- [❤️ Support](#️-support)
- [Lizenz](#lizenz)

## Überblick

`The Art of Lazying` ist ein übergreifendes Repository, das Philosophie, praktische Automatisierung, KI-gestützte kreative Werkzeuge und Sprachenlern-Experimente verbindet.

Es enthält:

- Eine Übersicht verknüpfter KI-Projekte und Workflows.
- Lokale Skripte/Tools für sichere Shell-Workflows und Utility-Funktionen.
- Ein hardwarebasiertes Sprachlernprojekt (`EinkWordsGPT`) mit Raspberry Pi + Waveshare E-Ink + OpenAI.
- Vlog-/Tooling-Experimente wie DNS/IP-Aggregation und Repository-zu-Text-Konvertierung.
- Mehrsprachige Dokumentation unter [`i18n/`](i18n).

### Projekt-Highlights

| Signal | Wert |
|---|---|
| 🧩 Repository-Typ | Legacy-Style-Umbrella-Repository |
| 🧪 Technischer Fokus | Python + Shell-Utilities + Raspberry-Pi-Tooling |
| 🌐 Dokumentation | Mehrsprachige READMEs in `i18n/` |
| 🪪 Lizenz | MIT |

### Kurzer Überblick

| Fokus | Was du bekommst |
|------|---|
| 🧠 Philosophie | Strategische-Faulheits-Prinzipien für Arbeit mit hoher Hebelwirkung |
| 🤖 KI | KI-gestützte kreative Unterstützung, Transkription, Übersetzung, Hilfe bei der Veröffentlichung |
| 🛠️ Utilities | Sicheres Löschen/Wiederherstellen in der Shell, DNS/IP-Tools, Zusammenführung von Codebase-Text |
| 🌍 i18n | README-Varianten in mehreren Sprachen unter `i18n/` |

## Funktionen

- ✅ Strategisches Faulheits-Framework mit Fokus auf hochwertigen Arbeitseinsatz.
- ✅ KI-gestützte kreative und Publishing-Workflow-Referenzen.
- ✅ Utilities für Sprachenlernen und ein E-Ink-Lerndisplay-System.
- ✅ Shell-Sicherheitswerkzeuge (`saferm`, `unrm`, `removeitanyway`).
- ✅ Leichtgewichtige Python-Utilities für DNS/IP-Erfassung und das Zusammenführen von Codebase-Texten.
- ✅ Unterstützung für mehrsprachige READMEs.

## Projekte

### 🤖 KI-gestützte kreative Tools

| Project | Description | Demo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | E-Ink-Display mit GPT-basierter Wortlern-Logik | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Analyse von Wortherkünften und Darstellung als Graph | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Werkzeuge für effizientes Sprachenlernen mit minimalem Aufwand | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Video- und Bildbeschriftung mit OpenAI-CLIP-Embeddings + GPT-Decoder | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | Video-Untertitel-Tool: extrahiert Keyframes mit Katna/OpenCV und erzeugt Beschriftungen mit ViT+GPT-2 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Mehrsprachige Transkriptions-Pipeline mit fein-granularer Spracherkennung | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Baut Sprachbarrieren für globalen kreativen Austausch ab | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Automatische Metadaten-Generierung für Videos | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | KI-gestütztes automatisches Videobearbeitungstool mit Transkription, Auto-Untertiteln, Highlighting und Metadaten-Generierung | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Vereinfachung von Content-Publishing-Workflows | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Automatisches System zum Überwachen, Verarbeiten und Veröffentlichen von Videoinhalten auf mehreren Plattformen | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Fortgeschrittene Techniken für den effektiven Einsatz von KI-Assistenten | |

### 🔄 Automatisierungs-Tools

Lokale Automatisierung/Tooling in diesem Repository umfasst:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): sicherer Löschen-/Wiederherstellungs-Workflow für Shell-Nutzer.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): Domain-zu-IP/CIDR-Resolver mit Duplikatbereinigung.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): Konsolidiert Python-Dateien nach Unterverzeichnis in Textartefakte.

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

### Ursprüngliche konzeptionelle Ordnerstruktur (beibehalten)

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

## Einführung

The Art of Lazying versteht strategische Faulheit als Methode, den Energieeinsatz zu optimieren und den Fokus auf das wirklich Wichtige zu lenken. Dieses Repository untersucht, wie absichtsvolle Faulheit zu höherer Produktivität, Kreativität und Wohlbefinden führen kann.

## Die Theorie des Lazying

Eine umfassende Einführung in die Prinzipien strategischer Faulheit mit Fokus darauf, durch Priorisieren, Delegieren und Automatisierung Produktivität und Wohlbefinden zu maximieren.

Das Kernprinzip ist die Anwendung der 80/20-Regel von Pareto auf den Alltag: Identifikation der 20 Prozent der Aktivitäten, die 80 Prozent der gewünschten Ergebnisse liefern.

## Praktische Tipps und Tricks

Eine Sammlung umsetzbarer Hinweise zur Anwendung von Lazying-Prinzipien in Arbeit, Beziehungen und Selbstfürsorge:

- Wiederkehrende Aufgaben automatisieren.
- Die Pomodoro-Technik für Zeitmanagement nutzen.
- Systeme bauen, die Entscheidungsmüdigkeit reduzieren.
- KI-Werkzeuge als Unterstützung nutzen.

## Anwendungsfälle

Praxisnahe Beispiele dafür, wie Lazying-Prinzipien Probleme lösen und die Effizienz steigern:

- Wie Unternehmer Delegation und Automatisierung nutzen, um sich auf Wachstum zu konzentrieren.
- Wie Forschende ihre Forschungs-Workflows verschlanken.
- Wie Content Creators ihren Produktionsprozess optimieren.

## KI-Agenten und Automatisierung

Erkunde die Entwicklung von KI-Agenten und Automatisierungstools, die Aufgaben vereinfachen:

- ChatGPT als persönlichen Assistenten einsetzen.
- Eigene Automatisierungs-Workflows aufbauen.
- E-Ink-Displays für passives Lernen erstellen.

## Sprachenlernen und Vlogs

Ressourcen und Techniken für effizientes Sprachenlernen sowie Vlogs, die die Lazying-Reise dokumentieren:

- Personalisierte Sprachlernansätze mit Spaced Repetition entwickeln.
- Immersive Lernmethoden umsetzen.
- Projekte aufbauen, die passives Lernen fördern.

## Voraussetzungen

Dieses Repository umfasst mehrere Projekte und enthält kein einzelnes Top-Level-Abhängigkeiten-Manifest. Installiere nur, was du für das jeweilige Modul brauchst.

### Umfeld-Checkliste

| Element | Grundlage |
|---|---|
| OS | Linux/macOS empfohlen (für Shell-Workflows) |
| Python | 3.9+ |
| Paketmanager | `pip` |
| Versionsverwaltung | `git` |

Allgemeine Anforderungen:

- `git`
- Python `3.9+` (empfohlen)
- `pip`
- Optionale Virtual-Environment-Tools (`python -m venv`)

Modulspezifische Hinweise aus Quellcode/READMEs:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, Waveshare E-Paper Python Library (`waveshare_epd`) und passende Hardware.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: Bash/Zsh-Shell.

## Installation

### 1. Repository klonen

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Empfohlen) Python-Virtual Environment erstellen

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Python-Abhängigkeiten für ausgewählte Module installieren

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

- `code/EinkWordsGPT/words_gpt.py` und `words_update.py` verwenden `OpenAI()` und erwarten, dass Credentials in deiner Umgebung vorhanden sind.
- Empfohlen:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### SafeShell-Papierkorbpfad

- `safeshell_functions.sh` verwendet einen festen Basis-Papierkorb-Pfad:

```bash
/mnt/disk/BIN/ROOT
```

Passe diesen Pfad im Skript an, falls dein System ein anderes Layout verwendet.

### repo2text Quell-/Zielverzeichnisse

- `vlogs/repo2text/convert-repo-to-merged-text.py` setzt aktuell:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Passe diese Variablen vor der Ausführung an.

## Nutzung

### Schneller Befehlsindex

| Aufgabe | Befehlsverzeichnis | Hauptbefehl |
|---|---|---|
| EinkWordsGPT Display-Loop | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT Aktualisierungs-Skript | `code/EinkWordsGPT` | `python words_update.py` |
| Domain/IP-Resolver | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Repo-zu-Text-Merge | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell-Wiederherstellungsworkflow | Shell-Profil + aktuelle Shell | `saferm`, `unrm`, `removeitanyway` |

### EinkWordsGPT Display-Loop ausführen (Hardware-Setup erforderlich)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### EinkWordsGPT-Wortpflege-/Update-Skript ausführen

```bash
cd code/EinkWordsGPT
python words_update.py
```

### ChatGPT Traffic Domain/IP Resolver ausführen

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Repository-Python-Datei-Merger ausführen

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell-Befehle nach dem Einbinden verwenden

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Beispiele

- `code/EinkWordsGPT/demo.jpg`: Beispielausgabe auf E-Ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: Notebook-Beispiel.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: Prompt-Referenz.
- `demos/`: visuelle Demos, die in dieser README verwendet werden.

## Entwicklungsnotizen

- Dieses Repository ist ein Legacy-Style-Umbrella-Projekt und kein monolithisches Paketprojekt.
- Mehrere Tools in der Projekt-Tabelle verweisen auf externe Repositories; für Laufzeitdetails nutze deren eigene READMEs.
- Einige interne Dokumente beschreiben ältere Dateistrukturen (z. B. `scripts/lazy-care`, das auf gesplittete Skripte verweist, während die aktuelle Implementierung in `SafeShell/safeshell_functions.sh` konsolidiert ist).
- Hardwareabhängiger Code in `EinkWordsGPT` setzt Raspberry-Pi + Waveshare-E-Paper-Umgebung voraus.

### Annahmen (explizit)

- Das Top-Level-README ist der kanonische Einstiegspunkt, während detaillierte Ausführungsanleitungen für verlinkte externe Projekte in deren eigene Repositories ausgelagert sind.
- Python-Paketversionen bleiben absichtlich offen, da dieses Repo aktuell kein root `requirements.txt`/`pyproject.toml` bereitstellt.
- Für `EinkWordsGPT` wird erwartet, dass Waveshare-Hardware-spezifische Treiberinstallationen in der Ziel-Raspberry-Pi-Umgebung durchgeführt werden.

## Fehlerbehebung

- `ModuleNotFoundError: waveshare_epd`: Installiere Waveshare-E-Paper-Bibliotheken auf dem Zielgerät und prüfe hardware-spezifische Abhängigkeiten.
- OpenAI-Authentifizierungsfehler: Überprüfe, dass `OPENAI_API_KEY` in der aktiven Shell/Session gesetzt ist.
- `File not found` bei `words_phonetics.db` oder Schriftarten: Führe Skripte aus `code/EinkWordsGPT` aus, damit relative Pfade korrekt aufgelöst werden.
- SafeShell-Befehle nicht gefunden: Stelle sicher, dass `safeshell_functions.sh` in das richtige Shell-Profil eingebunden wurde und lade die Shell neu.
- `repo2text` erzeugt keine Dateien: Prüfe, ob `source_directory` existiert und `.py`-Dateien enthält.

## Roadmap

- Abhängigkeitsmanagement vereinheitlichen und optional `requirements.txt` pro Modul ergänzen.
- Root-Level-Taskrunner oder Makefile für gängige Workflows ergänzen.
- Reproduzierbare Setup-Dokumentation für Raspberry Pi + Waveshare-Auslieferung erweitern.
- Tests für Utility-Skripte und Daten-Transformationshelfer hinzufügen.
- Die Parität der mehrsprachigen Dokumentation in `i18n/` weiter verbessern.

## Community-Beiträge

Teile eigene Erfahrungen, Tipps und Ideen zu strategischer Faulheit:

- Forum für den Austausch von Produktivitäts-Hacks.
- Werkzeuge und Vorlagen für tägliche Routinen.
- Kooperative Projekte für entspannte Effizienz.

## Mitwirken

Beiträge sind willkommen für Inhalte, Skripte und Projektdokumentation.

Standardablauf:

1. Forke das Projekt.
2. Erstelle deinen Feature-Branch (`git checkout -b feature/AmazingFeature`).
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`).
4. Pushe in den Branch (`git push origin feature/AmazingFeature`).
5. Öffne einen Pull Request.

Wenn deine Änderung ein bestimmtes Submodul betrifft, aktualisiere auch das README dieses Submoduls.

## Kontakt

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

## Lizenz

Dieses Repository ist unter der MIT-Lizenz lizenziert. Siehe [LICENSE](LICENSE) für Details.

Hinweise:

- Top-Level-Projektlizenz: MIT.
- Einige Unterordner enthalten eigene `LICENSE`-Dateien; im Zweifel gilt die spezifischste Lizenzdatei in diesem Pfad.

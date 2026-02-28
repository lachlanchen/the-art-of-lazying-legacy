[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# Die Kunst des Faulenzens

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

Ein repository-übergreifendes Arbeitsverzeichnis für praxisnahe KI-gestützte Produktivitäts-Experimente, Sprachlern-Systeme und nützliche Tools.

> Weniger Zeit mit Arbeit niedriger Hebelwirkung verbringen und mehr Ressourcen auf hochwertige Ergebnisse richten.

| 🎯 Fokus | 🎛️ Primärer Stack | 🧭 Ziel |
|---|---|---|
| repetitive Aufgaben automatisieren | Python + Shell | kognitive Last reduzieren |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Inhaltsverzeichnis

- [Überblick](#overview)
- [Funktionen](#features)
- [Projekte](#projects)
- [Projektstruktur](#project-structure)
- [Überblick des Lazying-Ansatzes](#overview-of-the-lazying-approach)
- [Praktische Tipps und Tricks](#practical-tips-and-tricks)
- [Anwendungsfälle](#use-cases)
- [KI-Agenten und Automatisierung](#ai-agents-and-automation)
- [Sprachenlernen und Vlogs](#language-learning-and-vlogs)
- [Voraussetzungen](#prerequisites)
- [Installation](#installation)
- [Konfiguration](#configuration)
- [Nutzung](#usage)
- [Beispiele](#examples)
- [Entwicklungsnotizen](#development-notes)
- [Fehlerbehebung](#troubleshooting)
- [Roadmap](#roadmap)
- [Community-Beiträge](#community-contributions)
- [Mitwirken](#contributing)
- [❤️ Support](#-support)
- [Kontakt](#connect)
- [Lizenz](#license)

<a id="overview"></a>
## Überblick

`The Art of Lazying` ist ein Legacy-Style-Umbrella-Repository: eine pragmatische Sammlung von KI-Workflows, Shell-Nutz-Tools, Raspberry-Pi-Experimenten und Lernressourcen.

### Projektsignale

| Signal | Wert |
|---|---|
| Repository-Typ | Legacy-Umbrella-Repository |
| Primäre Laufzeit | Python + Shell-Skripte |
| Hardware-Fokus | Raspberry Pi + E-Ink (modulspezifisch) |
| Dokumentation | Mehrsprachige README-Sammlung in `i18n/` |
| Lizenz | GNU General Public License 3.0 (Root und wichtige Unterordner) |

<a id="features"></a>
## Funktionen

- ✅ Strategisches Faulheits-Framework: hochwirksame Aufgaben gegenüber repetitiven Vorgängen priorisieren.
- ✅ KI-gestützte kreative Werkzeuge und publizierungsnahe Experimente.
- ✅ Sprachlern-Nützlichkeit mit E-Ink-Rendering und OpenAI-unterstütztem Wort-Workflow (`code/EinkWordsGPT`).
- ✅ Sicherere Shell-Operationen (`saferm` / `unrm` / `removeitanyway`).
- ✅ Leichte Python-Utilities für DNS/IP-Sammlung und Code-zu-Text-Konvertierung.
- ✅ Mehrsprachige Dokumentationsstruktur mit sprachspezifischen README-Varianten.

<a id="projects"></a>
## Projekte

### 🤖 KI-gestützte kreative Werkzeuge

| Projekt | Typ | Fokus |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Lokales Modul | Wortkarten-Anzeige mit Raspberry Pi + Waveshare E-Ink über OpenAI |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Externes Projekt | Wortursprungs-Analyse und graphische Darstellung |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Externes Projekt | Sprachlern-Tooling-Projekt |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Externes Projekt | Beschriftung mit CLIP-Embeddings + GPT |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Externes Projekt | Mehrsprachige Transkriptions-Pipeline |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Externes Skript | Hilfsskript für Untertitel-/Mehrsprachübersetzungen |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Externes Skript | Automatische Medien-Metadaten-Generierung |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Externes Projekt | Workflow für Video-Editing und Untertitel |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Externes Projekt | Automatisierung bei der Content-Publikation |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Externes Projekt | Monitoring + Orchestrierung von Veröffentlichungsprozessen |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Externes Projekt | Fortgeschrittene Prompt- und KI-Nutzungsmuster |

### 🛠️ Lokale Automatisierungs-Tools

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): Sichererer Lösch-/Wiederherstellungs-Workflow für Shell-Anwender.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): DNS-/Domain-to-IP + CIDR-Listen-Auflösung.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): Führt Python-Dateien aus Unterordnern für AI-Reviews zu Text-Bündeln zusammen.

<a id="project-structure"></a>
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

### Legacy-konzeptionelle Struktur (Historische Dokumentation)

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
## Überblick des Lazying-Ansatzes

Dieses Repo ordnet praktische Produktivität um **strategische Faulheit**: Wiederholte Entscheidungen niedriger Relevanz automatisieren, kognitive Energie sparen und zuerst Systeme statt Taktiken anwenden.

Der Kernprinzip bleibt eine pragmatische 80/20-Logik:

- Die 20 % der wirkungsvollsten Aktionen erkennen.
- Wiederkehrende Abläufe standardisieren/automatisieren.
- Vermeidbare Reibungsverluste im Alltag beseitigen.

<a id="practical-tips-and-tricks"></a>
## Praktische Tipps und Tricks

- Wiederkehrende Kommando-Workflows durch Shell-Funktionen ersetzen.
- Kurze Planungszyklen nutzen (Pomodoro-kompatibel).
- Entscheidungsmüdigkeit durch wiederverwendbare Vorlagen reduzieren.
- KI für einen ersten Entwurf/Transformationsdurchlauf einsetzen und anschließend manuell prüfen.

<a id="use-cases"></a>
## Anwendungsfälle

- Wiederkehrende Abläufe in Creator-Workflows delegieren und automatisieren.
- Recherche- und Dokumentationsaufgaben durch KI-basierte Zusammenfassungen verschlanken.
- Code-Kontext schnell in KI-gerechte Textformate für Analysen umwandeln.

<a id="ai-agents-and-automation"></a>
## KI-Agenten und Automatisierung

Zu diesem Repository gehörende Experimente:

- Ein praktischer Assistent-Workflow für Wortlernen und Content-Erstellung.
- Scriptbare DNS/IP-Aggregation für operative Aufgaben.
- Repo-to-Text-Export für schnellere KI-gestützte Codeprüfung.
- Optionales Shell-Sicherheits-Tooling zur Vermeidung zerstörerischer Fehler.

<a id="language-learning-and-vlogs"></a>
## Sprachenlernen und Vlogs

Die sprachbezogenen Inhalte und Projekte setzen auf konsequente, wenig aufwändige Routinen:

- Passive Exposition + periodische Wiederholung über E-Ink-Display.
- Cross-linguale Notiz-Workflows in unterstützten Subprojekten.
- Vlog-Skripte und Notizen als Beispiele für praktische Routine-Engineering.

<a id="prerequisites"></a>
## Voraussetzungen

Dieses Repository ist modulbasiert aufgebaut; es gibt kein Paket-Manifest auf Root-Ebene.

### Environment-Checkliste

| Punkt | Basis |
|---|---|
| OS | Linux/macOS (Shell-Tooling), Windows WSL für Python-Skripte akzeptiert |
| Python | 3.9+ |
| Paketmanager | `pip` |
| Versionskontrolle | `git` |

### Modulabhängigkeiten (aus den Quellen)

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd` und Raspberry-Pi/e-paper-Runtime-Dateien (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic`: `dnspython`.
- `vlogs/repo2text`: nur Standard-Bibliothek.
- `scripts/lazy-care/SafeShell`: Bash/Zsh mit `mv`, `realpath` und optionalem Bestätigungsablauf.

<a id="installation"></a>
## Installation

### 1) Klonen

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) Empfohlene virtuelle Umgebung

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) Modulabhängigkeiten installieren

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) Optional: SafeShell-Setup

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or source ~/.zshrc
```

<a id="configuration"></a>
## Konfiguration

### 1) OpenAI / EinkWordsGPT

Beide EinkWordsGPT-Skripte instanziieren `OpenAI()` direkt, daher muss die Laufzeitumgebung Credentials bereitstellen.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) SafeShell Papierkorb-Speicherort

`/mnt/disk/BIN/ROOT` ist als Basispfad des Papierkorbs in `scripts/lazy-care/SafeShell/safeshell_functions.sh` fest verdrahtet. Passe diesen Pfad im Skript bei Bedarf an.

### 3) `repo2text` Merge-Pfade

Standardwerte in `vlogs/repo2text/convert-repo-to-merged-text.py` sind:

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

Passe beide vor dem Start an, sofern das Repository andere Namen verwendet.

### 4) `chatgpt-traffic` benutzerdefinierte Einträge

`custom_ips`, `cidr` und `domains` sind derzeit in `vlogs/chatgpt-traffic/chatgpt-traffic.py` eingebettet. Bearbeite diese direkt bei Bedarf.

<a id="usage"></a>
## Nutzung

### Schnelle Befehlsübersicht

| Aufgabe | Kommando-Pfad | Befehl |
|---|---|---|
| EinkWordsGPT-Anzeigeschleife | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT-Aktualisierung | `code/EinkWordsGPT` | `python words_update.py` |
| Domain/IP-Resolver | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Repo-to-Text-Merge | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell-Nutzung | Shell-Profil + aktuelle Shell | `saferm`, `unrm`, `removeitanyway` |

### EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_gpt.py
python words_update.py
```

### ChatGPT-Traffic-Resolver

```bash
cd vlogs/chatgpt-traffic
python chatgpt-traffic.py
```

### Repo-to-Text-Merge

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell (nach dem Einbinden)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

<a id="examples"></a>
## Beispiele

- `code/EinkWordsGPT/demo.jpg`: E-Ink-Ausgabebeispiel.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: Notebook-Beispiel.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: Prompt-Referenz.
- `demos/`: visuelle Artefakte, die in der Projektdokumentation verwendet werden.

<a id="development-notes"></a>
## Entwicklungsnotizen

- Dies ist ein Legacy-Umbrella-Repository; modulspezifische Dokumentationen sind die verlässliche Quelle für detailiertes Laufzeitverhalten.
- Einige aufgelistete Projekte sind externe GitHub-Repositories; nutze jeweils deren README für die Einrichtung.
- `EinkWordsGPT` ist hardwaregebunden (Raspberry Pi + Waveshare-Display).
- Mehrere modul-spezifische Abhängigkeiten sind außerhalb dieses Repositories dokumentiert und können mit der Zeit abweichen.

### Annahmen (explizit)

- Repository-Root und wichtige Modul-Verzeichnisse verwenden **GNU GPL v3.0**, sofern kein Unterordner eine eigene `LICENSE`-Vorgabe hat.
- Modul-Installationsschritte sind bewusst nicht zentralisiert, da auf Root-Ebene kein `requirements.txt`, `pyproject.toml` oder `package.json` existiert.

<a id="troubleshooting"></a>
## Fehlerbehebung

- `ModuleNotFoundError: waveshare_epd`
  - Installiere Waveshare-e-paper-Module auf dem Zielgerät und prüfe Hardware-Treiber.
- OpenAI-Anfragen scheitern mit Auth-Fehlern
  - Vergewissere dich, dass `OPENAI_API_KEY` im aktiven Shell/Session-Kontext exportiert ist.
- `words_phonetics.db` nicht gefunden
  - Führe EinkWordsGPT-Skripte aus `code/EinkWordsGPT` aus, damit relative Pfade aufgelöst werden.
- `saferm`/`unrm` nicht verfügbar
  - Lade dein Shell-Profil neu nach dem Einfügen von `safeshell_functions.sh`.
- `repo2text` liefert keine Ausgabe
  - Stelle sicher, dass `source_directory` existiert und `.py`-Dateien enthält.

<a id="roadmap"></a>
## Roadmap

- Dokumentation der Modulabhängigkeiten vereinheitlichen und modulspezifische Setup-Schnipsel ergänzen.
- Optionalen Root-Task-Runner (Makefile / Skript-Entrypoint) für Modul-Workflows hinzufügen.
- Reproduzierbarkeit für Raspberry-Pi + Waveshare-Bereitstellung verbessern.
- Einfache automatisierte Tests für Utility-Skripte ergänzen.
- Die Sprachparität in `i18n/` weiter ausbauen.

<a id="community-contributions"></a>
## Community-Beiträge

Teile praxisnahe Verbesserungen, Automatisierungsideen und Sprachlern-Experimente:

- Vorlagen für Routine-Aufgaben.
- Reale Lazying-Muster, die Wartungsaufwand senken.
- Cross-Module-Integrationen und Skriptanpassungen.

<a id="contributing"></a>
## Mitwirken

Beiträge sind willkommen.

1. Forke das Repository.
2. Erstelle einen Feature-Branch (`git checkout -b feature/your-topic`).
3. Committe Änderungen (`git commit -m 'Add feature'`).
4. Push den Branch und öffne eine PR.

Wenn deine Änderung modulbezogen ist, aktualisiere auch die lokale README dieses Moduls.

## Kontakt

| Kanal | Link |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lachlan@lazying.art` |

<a id="license"></a>
## Lizenz

Dieses Repository steht unter der **GNU General Public License v3.0** (siehe [LICENSE](LICENSE)).

Hinweise:

- Root-Ebene und wichtige Modulverzeichnisse enthalten `LICENSE`-Dateien mit GNU GPL.
- Falls du in einem Unterverzeichnis arbeitest, nutze die jeweils nächstgelegene `LICENSE`-Datei für bereichsspezifische Gültigkeit.


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

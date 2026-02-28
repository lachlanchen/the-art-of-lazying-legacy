[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerequisites)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projects)

Un dépôt qui promeut la paresse stratégique pour une vie simplifiée et productive, couvrant les agents IA, l’apprentissage des langues et des vlogs avec des conseils pratiques et des cas d’usage réels.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table des matières

- [Vue d’ensemble](#vue-densemble)
- [Fonctionnalités](#fonctionnalités)
- [Projets](#projets)
- [Structure du projet](#structure-du-projet)
- [Introduction](#introduction)
- [La théorie du Lazying](#la-théorie-du-lazying)
- [Astuces et bonnes pratiques](#astuces-et-bonnes-pratiques)
- [Cas d’usage](#cas-dusage)
- [Agents IA et automatisation](#agents-ia-et-automatisation)
- [Apprentissage des langues et vlogs](#apprentissage-des-langues-et-vlogs)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Configuration](#configuration)
- [Utilisation](#utilisation)
- [Exemples](#exemples)
- [Notes de développement](#notes-de-développement)
- [Dépannage](#dépannage)
- [Feuille de route](#feuille-de-route)
- [Contributions de la communauté](#contributions-de-la-communauté)
- [Contribuer](#contribuer)
- [Contact](#contact)
- [Support / Don](#support--don)
- [Licence](#licence)

## Vue d’ensemble

`The Art of Lazying` est un dépôt ombrelle qui mêle philosophie, automatisation pratique, outillage créatif assisté par IA et expérimentations d’apprentissage des langues.

Il inclut :

- Une vitrine de projets IA liés et de workflows.
- Des scripts/outils locaux pour des opérations shell sûres et des workflows utilitaires.
- Un projet d’apprentissage des langues basé sur du matériel (`EinkWordsGPT`) utilisant Raspberry Pi + e-ink Waveshare + OpenAI.
- Des expérimentations vlog/outillage comme l’agrégation DNS/IP et la conversion de dépôt en texte.
- Une documentation multilingue sous [`i18n/`](i18n).

### Aperçu rapide

| Focus | Ce que vous obtenez |
|------|---|
| 🧠 Philosophie | Principes de paresse stratégique pour un travail à fort effet de levier |
| 🤖 IA | Assistance créative, transcription, traduction, support de publication |
| 🛠️ Utilitaires | Suppression/récupération shell sécurisée, outillage DNS/IP, conversion de dépôt en texte |
| 🌍 i18n | Variantes du README dans plusieurs langues sous `i18n/` |

## Fonctionnalités

- Cadre de paresse stratégique centré sur les efforts à fort effet de levier.
- Références de workflows créatifs et de publication assistés par IA.
- Utilitaires d’apprentissage des langues et système d’affichage d’étude sur e-ink.
- Helpers de sécurité shell (`saferm`, `unrm`, `removeitanyway`).
- Utilitaires Python légers pour la collecte DNS/IP et la fusion textuelle de bases de code.
- Support README multilingue.

## Projets

### 🤖 Outils créatifs propulsés par l’IA

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

### 🔄 Outils d’automatisation

L’automatisation/l’outillage local dans ce dépôt inclut :

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh) : workflow de suppression/récupération plus sûr pour les utilisateurs shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py) : résolveur et dédoublonneur de domaines vers IP/CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py) : fusionne les fichiers Python par sous-répertoire dans des artefacts texte.

## Structure du projet

### Structure actuelle du dépôt

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

### Structure conceptuelle d’origine des dossiers (préservée)

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

The Art of Lazying présente la paresse stratégique comme une manière d’optimiser l’énergie dépensée et de se concentrer sur ce qui compte vraiment. Ce dépôt explore comment une paresse intentionnelle peut mener à une meilleure productivité, plus de créativité et davantage de bien-être.

## La théorie du Lazying

Une introduction complète aux principes de la paresse stratégique, en mettant l’accent sur la manière de maximiser productivité et bien-être en priorisant, déléguant et automatisant les tâches.

Le principe clé consiste à appliquer la règle de Pareto 80/20 au quotidien : identifier les 20 % d’activités qui produisent 80 % des résultats souhaités.

## Astuces et bonnes pratiques

Une collection de conseils actionnables pour appliquer les principes du lazying au travail, aux relations et au soin de soi :

- Automatiser les tâches répétitives.
- Utiliser la technique Pomodoro pour gérer le temps.
- Créer des systèmes qui réduisent la fatigue décisionnelle.
- Exploiter les outils d’IA comme assistance.

## Cas d’usage

Exemples concrets montrant comment les principes du lazying résolvent des problèmes et améliorent l’efficacité :

- Comment les entrepreneurs utilisent la délégation et l’automatisation pour se concentrer sur la croissance de leur activité.
- Comment les universitaires rationalisent leurs workflows de recherche.
- Comment les créateurs de contenu optimisent leur processus de production.

## Agents IA et automatisation

Explorez le développement d’agents IA et d’outils d’automatisation qui simplifient les tâches :

- Utiliser ChatGPT comme assistant personnel.
- Construire des workflows d’automatisation personnalisés.
- Créer des affichages e-ink pour l’apprentissage passif.

## Apprentissage des langues et vlogs

Ressources et techniques pour apprendre les langues efficacement, avec des vlogs qui documentent le parcours lazying :

- Créer un apprentissage des langues personnalisé avec la répétition espacée.
- Mettre en œuvre des techniques d’apprentissage immersif.
- Construire des projets qui encouragent l’apprentissage passif.

## Prérequis

Ce dépôt contient plusieurs projets et n’inclut pas de manifeste de dépendances unique au niveau racine. Installez uniquement ce dont vous avez besoin selon le module.

Exigences communes :

- `git`
- Python `3.9+` (recommandé)
- `pip`
- Outillage d’environnement virtuel optionnel (`python -m venv`)

Signaux spécifiques aux modules d’après le code source/les README :

- `code/EinkWordsGPT` : `openai`, `Pillow`, `pytz`, `pykakasi`, bibliothèque Python e-paper Waveshare (`waveshare_epd`) et matériel compatible.
- `vlogs/chatgpt-traffic` : `dnspython`.
- `scripts/lazy-care/SafeShell` : shell Bash/Zsh.

## Installation

### 1. Cloner le dépôt

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Recommandé) Créer un environnement virtuel Python

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Installer les dépendances Python pour les modules sélectionnés

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. Configuration SafeShell (optionnel)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Configuration

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` et `words_update.py` utilisent `OpenAI()` et attendent que les identifiants soient disponibles dans votre environnement.
- Recommandé :

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### Emplacement de la corbeille SafeShell

- `safeshell_functions.sh` utilise un chemin de base fixe pour la corbeille :

```bash
/mnt/disk/BIN/ROOT
```

Ajustez ce chemin dans le script si votre machine utilise une organisation différente.

### Répertoires source/cible de repo2text

- `vlogs/repo2text/convert-repo-to-merged-text.py` définit actuellement :
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Modifiez ces variables avant l’exécution.

## Utilisation

### Exécuter la boucle d’affichage EinkWordsGPT (configuration matérielle requise)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### Exécuter le script de maintenance/mise à jour des mots EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_update.py
```

### Exécuter le résolveur de domaine/IP du trafic ChatGPT

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Exécuter l’outil de fusion des fichiers Python du dépôt

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### Utiliser les commandes SafeShell après le sourcing

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Exemples

- `code/EinkWordsGPT/demo.jpg` : exemple de sortie e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb` : exemple de notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf` : référence de prompts.
- `demos/` : démonstrations visuelles utilisées dans ce README.

## Notes de développement

- Ce dépôt est un projet ombrelle de style legacy, pas une application monolithique packagée.
- Plusieurs outils liés dans le tableau Projects vivent dans des dépôts externes ; utilisez leurs propres README pour les détails d’exécution.
- Certaines documentations internes décrivent d’anciens agencements de fichiers (par exemple, `scripts/lazy-care` référence des scripts séparés alors que l’implémentation actuelle est consolidée dans `SafeShell/safeshell_functions.sh`).
- Le code dépendant du matériel dans `EinkWordsGPT` suppose un environnement Raspberry Pi + e-paper Waveshare.

### Hypothèses (explicites)

- Le README racine est le point d’entrée canonique, tandis que les instructions d’exécution détaillées pour les projets externes liés sont maintenues dans leurs propres dépôts.
- Les versions de packages Python sont volontairement laissées ouvertes, car ce dépôt ne fournit pas actuellement de `requirements.txt`/`pyproject.toml` à la racine.
- Pour `EinkWordsGPT`, les étapes d’installation des pilotes pour le matériel Waveshare sont supposées être effectuées sur l’environnement Raspberry Pi cible.

## Dépannage

- `ModuleNotFoundError: waveshare_epd` : installez les bibliothèques e-paper Waveshare sur l’appareil cible et confirmez les dépendances spécifiques au matériel.
- Erreurs d’authentification OpenAI : vérifiez que `OPENAI_API_KEY` est défini dans le shell/la session active.
- `File not found` autour de `words_phonetics.db` ou des polices : exécutez les scripts depuis `code/EinkWordsGPT` pour que les chemins relatifs se résolvent correctement.
- Commandes SafeShell introuvables : assurez-vous que `safeshell_functions.sh` a été ajouté au bon profil shell, puis rechargez le shell.
- `repo2text` ne génère aucun fichier : vérifiez que `source_directory` existe et contient des fichiers `.py`.

## Feuille de route

- Unifier la gestion des dépendances avec des `requirements.txt` optionnels par module.
- Ajouter des task runners racine ou un Makefile pour les workflows courants.
- Étendre la documentation de setup reproductible pour le déploiement Raspberry Pi + Waveshare.
- Ajouter des tests pour les scripts utilitaires et les helpers de transformation de données.
- Continuer à améliorer la parité de la documentation multilingue dans `i18n/`.

## Contributions de la communauté

Partagez vos expériences, astuces et idées autour de la paresse stratégique :

- Forum d’échange de hacks de productivité.
- Outils et templates pour les routines quotidiennes.
- Projets collaboratifs pour une efficacité « lazy ».

## Contribuer

Les contributions sont les bienvenues pour le contenu, les scripts et la documentation des projets.

Flux standard :

1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`).
4. Poussez la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

Si votre modification impacte un sous-module spécifique, mettez aussi à jour le README de ce sous-module.

## Contact

| Channel | Link |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## Support / Don

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

## Licence

Ce dépôt est sous licence MIT. Voir [LICENSE](LICENSE) pour les détails.

Notes :

- Licence du projet racine : MIT.
- Certains sous-dossiers incluent leurs propres fichiers `LICENSE` ; en cas de doute, suivez le fichier de licence le plus spécifique à ce chemin.

[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# L'art du Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prérequis)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#projets)

Un dépôt qui promeut la paresse stratégique pour une vie simplifiée et productive, englobant des agents IA, l'apprentissage des langues et des vlogs avec des conseils pratiques et des cas d'usage réels.

> Faites moins de tâches à faible levier et livrez des résultats plus significatifs.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table des matières

- [Vue d'ensemble](#vue-densemble)
- [Fonctionnalités](#fonctionnalités)
- [Projets](#projets)
- [Structure du projet](#structure-du-projet)
- [Introduction](#introduction)
- [La théorie du Lazying](#la-théorie-du-lazying)
- [Astuces et bonnes pratiques](#astuces-et-bonnes-pratiques)
- [Cas d'usage](#cas-dusage)
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
- [❤️ Support](#-support)
- [Licence](#licence)

## Vue d'ensemble

`The Art of Lazying` est un dépôt parapluie mêlant philosophie, automatisation pratique, outils créatifs assistés par IA et expérimentations d'apprentissage des langues.

### Signaux du projet

| Signal | Valeur |
|---|---|
| 🧩 Type de dépôt | Dépôt parapluie de style legacy |
| 🧪 Focus d'exécution | Python + utilitaires shell + outils Raspberry Pi |
| 🌐 Documentation | README multilingues dans `i18n/` |
| 🪪 Licence | MIT |

Il inclut :

- Une vitrine de projets IA liés et de workflows.
- Des scripts/outils locaux pour des opérations shell sûres et des workflows utilitaires.
- Un projet d'apprentissage de langues basé sur du matériel (`EinkWordsGPT`) utilisant Raspberry Pi + e-ink Waveshare + OpenAI.
- Des expérimentations de vlogs/outils comme l'agrégation DNS/IP et la conversion de dépôt en texte.
- Une documentation multilingue dans [`i18n/`](i18n).

### Aperçu rapide

| Focus | Ce que vous obtenez |
|------|---|
| 🧠 Philosophie | Principes de paresse stratégique pour un travail à fort levier |
| 🤖 IA | Assistance créative, transcription, traduction, support de publication |
| 🛠️ Utilitaires | Suppression/récupération shell sécurisée, outils DNS/IP, conversion de dépôt en texte |
| 🌍 i18n | Variantes du README en plusieurs langues dans `i18n/` |

## Fonctionnalités

- ✅ Cadre de paresse stratégique centré sur les efforts à fort levier.
- ✅ Références de workflow de création et de publication assistés par IA.
- ✅ Utilitaires d'apprentissage des langues et système d'affichage d'étude sur e-ink.
- ✅ Helpers de sécurité shell (`saferm`, `unrm`, `removeitanyway`).
- ✅ Utilitaires Python légers pour la collecte DNS/IP et la fusion de texte de code.
- ✅ Support de README multilingue.

## Projets

### 🤖 Outils créatifs propulsés par IA

| Projet | Description | Démo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Affichage e-ink avec apprentissage de mots via GPT | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Analyse des origines des mots et présentation sous forme de graphe. | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Outils pour apprendre efficacement une langue avec peu d'effort | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Légender vidéos et images avec embeddings OpenAI CLIP + décodeur GPT | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | Outil de sous-titrage vidéo : extraire des images-clés avec Katna/OpenCV et générer des légendes avec un modèle ViT+GPT-2 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Pipeline de transcription multilingue avec détection fine des langues | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Supprimer les barrières linguistiques pour l'échange créatif mondial | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Génération automatique de métadonnées vidéo | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Outil automatique de montage vidéo assisté IA avec transcription, sous-titrage automatique, surlignage et génération de métadonnées | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Rationaliser les flux de publication de contenus | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Système automatisé de surveillance, traitement et publication de contenus vidéo sur plusieurs plateformes | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Techniques avancées pour utiliser efficacement des assistants IA | |

### 🔄 Outils d'automatisation

L'automatisation/outillage local dans ce dépôt inclut :

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh) : flux plus sûr de suppression/récupération pour les utilisateurs shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py) : résolveur et dédoublonneur de domaines vers IP/CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py) : fusionne les fichiers Python par sous-répertoire en artefacts texte.

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

### Structure conceptuelle d'origine des dossiers (préservée)

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

`The Art of Lazying` présente la paresse stratégique comme une manière d'optimiser l'énergie utilisée et de se concentrer sur ce qui compte vraiment. Ce dépôt explore comment une paresse intentionnelle peut mener à une meilleure productivité, créativité et bien-être.

## La théorie du Lazying

Une introduction complète aux principes de la paresse stratégique, centrée sur la façon de maximiser productivité et bien-être en priorisant, déléguant et automatisant les tâches.

Le principe clé consiste à appliquer la règle des 80/20 de Pareto à la vie quotidienne : identifier les 20 % d'activités qui produisent 80 % des résultats souhaités.

## Astuces et bonnes pratiques

Une collection de conseils actionnables pour appliquer les principes du lazying au travail, aux relations et au soin de soi :

- Automatiser les tâches répétitives.
- Utiliser la méthode Pomodoro pour la gestion du temps.
- Créer des systèmes qui réduisent la fatigue décisionnelle.
- Tirer parti des outils IA comme assistant.

## Cas d'usage

Des exemples concrets montrant comment les principes du lazying résolvent des problèmes et améliorent l'efficacité :

- Comment les entrepreneurs utilisent la délégation et l'automatisation pour se concentrer sur la croissance de leur entreprise.
- Comment les universitaires rationalisent leurs workflows de recherche.
- Comment les créateurs de contenu optimisent leur processus de production.

## Agents IA et automatisation

Explorer le développement d'agents IA et d'outils d'automatisation qui simplifient les tâches :

- Utiliser ChatGPT comme assistant personnel.
- Construire des workflows d'automatisation personnalisés.
- Créer des affichages e-ink pour l'apprentissage passif.

## Apprentissage des langues et vlogs

Ressources et techniques pour apprendre les langues efficacement, ainsi que des vlogs documentant le parcours du lazying :

- Créer un apprentissage linguistique personnalisé avec répétition espacée.
- Mettre en œuvre des techniques d'immersion.
- Construire des projets qui encouragent l'apprentissage passif.

## Prérequis

Ce dépôt est multi-projets et ne contient pas de manifeste de dépendances unique à la racine. Installez uniquement ce dont vous avez besoin par module.

### Liste de vérification de l'environnement

| Élément | Base |
|---|---|
| OS | Linux/macOS recommandé (pour les workflows shell) |
| Python | 3.9+ |
| Gestionnaire de paquets | `pip` |
| Contrôle de version | `git` |

Exigences courantes :

- `git`
- Python `3.9+` (recommandé)
- `pip`
- Outils d'environnement virtuel optionnels (`python -m venv`)

Signaux spécifiques aux modules depuis le code source/READMEs :

- `code/EinkWordsGPT` : `openai`, `Pillow`, `pytz`, `pykakasi`, bibliothèque e-paper Waveshare Python (`waveshare_epd`) et matériel compatible.
- `vlogs/chatgpt-traffic` : `dnspython`.
- `scripts/lazy-care/SafeShell` : Bash/Zsh shell.

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

### 4. Configuration SafeShell (optionnelle)

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

- `safeshell_functions.sh` utilise un chemin fixe de base pour la corbeille :

```bash
/mnt/disk/BIN/ROOT
```

Ajustez ce chemin dans le script si votre machine utilise une organisation différente.

### Répertoires source/cible de repo2text

- `vlogs/repo2text/convert-repo-to-merged-text.py` définit actuellement :
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Modifiez ces variables avant l'exécution.

## Utilisation

### Index rapide des commandes

| Tâche | Emplacement de la commande | Commande principale |
|---|---|---|
| Boucle d'affichage EinkWordsGPT | `code/EinkWordsGPT` | `python words_gpt.py` |
| Mise à jour des mots EinkWordsGPT | `code/EinkWordsGPT` | `python words_update.py` |
| Résolveur de domaine/IP | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Fusion repo-vers-texte | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| Workflow de récupération SafeShell | profil shell + shell actuel | `saferm`, `unrm`, `removeitanyway` |

### Exécuter la boucle d'affichage EinkWordsGPT (configuration matérielle requise)

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

### Exécuter la fusion des fichiers Python du dépôt

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### Utiliser les commandes SafeShell après sourcing

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Exemples

- `code/EinkWordsGPT/demo.jpg` : sortie e-ink d'exemple.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb` : exemple de notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf` : référence de prompts.
- `demos/` : démos visuelles utilisées dans ce README.

## Notes de développement

- Ce dépôt est un projet-parapluie de style legacy, pas une application monolithique empaquetée.
- Plusieurs outils liés dans le tableau des projets vivent dans des dépôts externes ; utilisez leurs propres README pour les détails d'exécution.
- Certains docs internes décrivent d'anciens agencements de fichiers (par exemple, `scripts/lazy-care` référence des scripts séparés alors que l'implémentation actuelle est consolidée dans `SafeShell/safeshell_functions.sh`).
- Le code dépendant du matériel dans `EinkWordsGPT` suppose un environnement Raspberry Pi + e-paper Waveshare.

### Hypothèses (explicites)

- Le README de premier niveau est le point d'entrée canonique, tandis que les instructions détaillées d'exécution pour les projets externes liés sont maintenues dans leurs propres dépôts.
- Les versions des paquets Python sont laissées volontairement ouvertes car ce dépôt ne fournit pas actuellement de `requirements.txt`/`pyproject.toml` à la racine.
- Pour `EinkWordsGPT`, les étapes d'installation des pilotes du matériel Waveshare sont censées être réalisées dans l'environnement Raspberry Pi cible.

## Dépannage

- `ModuleNotFoundError: waveshare_epd` : installez les bibliothèques e-paper Waveshare sur l'appareil cible et confirmez les dépendances spécifiques au matériel.
- Erreurs d'authentification OpenAI : vérifiez que `OPENAI_API_KEY` est défini dans le shell/session actif.
- `File not found` autour de `words_phonetics.db` ou des polices : exécutez les scripts depuis `code/EinkWordsGPT` pour que les chemins relatifs se résolvent correctement.
- Commandes SafeShell introuvables : assurez-vous que `safeshell_functions.sh` a été ajouté au bon profil shell et rechargez le shell.
- `repo2text` ne génère aucun fichier : vérifiez que `source_directory` existe et contient des fichiers `.py`.

## Feuille de route

- Unifier la gestion des dépendances avec des fichiers `requirements.txt` optionnels par module.
- Ajouter des task runners racine ou un Makefile pour les workflows courants.
- Étendre la documentation de mise en place reproductible pour le déploiement Raspberry Pi + Waveshare.
- Ajouter des tests pour les scripts utilitaires et les helpers de transformation de données.
- Continuer à améliorer la parité de la documentation multilingue dans `i18n/`.

## Contributions de la communauté

Partagez vos expériences, astuces et idées autour de la paresse stratégique :

- Forum d'échange de hacks de productivité.
- Outils et templates pour les routines quotidiennes.
- Projets collaboratifs pour l'efficacité « lazy ».

## Contribuer

Les contributions sont les bienvenues sur le contenu, les scripts et la documentation du projet.

Flux standard :

1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Commitez vos changements (`git commit -m 'Add some AmazingFeature'`).
4. Poussez la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

Si votre modification concerne un sous-module spécifique, mettez aussi à jour le README de ce sous-module.

## Contact

| Channel | Lien |
|---|---|
| 🌐 Site web | [![Website](https://img.shields.io/badge/lazying.art-Visit-0A66C2?style=flat-square)](https://lazying.art) |
| 🧑‍💻 GitHub | [![GitHub](https://img.shields.io/badge/lachlanchen-Profile-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## ❤️ Support

| Donate | PayPal | Stripe |
|---|---|---|
| [![Donate](https://img.shields.io/badge/Donate-LazyingArt-0EA5E9?style=for-the-badge&logo=ko-fi&logoColor=white)](https://chat.lazying.art/donate) | [![PayPal](https://img.shields.io/badge/PayPal-RongzhouChen-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/RongzhouChen) | [![Stripe](https://img.shields.io/badge/Stripe-Donate-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

Des options supplémentaires (y compris les QR codes) sont conservées ci-dessous :

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
- Certaines sous-dossiers incluent leurs propres fichiers `LICENSE` ; en cas de doute, suivez le fichier de licence le plus spécifique à ce chemin.

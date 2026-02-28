[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# L'art de la paresse

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

Un espace de travail de niveau dépôt pour des expériences de productivité pratique assistée par l'IA, des systèmes d'apprentissage des langues et des outils utilitaires.

> Faites moins de travail à faible levier, concentrez vos efforts sur des résultats à fort levier.

| 🎯 Focus | 🎛️ Stack principale | 🧭 Cible |
|---|---|---|
| automatiser les tâches répétitives | Python + shell | réduire la charge cognitive |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Table des matières

- [Aperçu](#overview)
- [Fonctionnalités](#features)
- [Projets](#projects)
- [Structure du projet](#project-structure)
- [Aperçu de l'approche “lazying”](#overview-of-the-lazying-approach)
- [Conseils et astuces pratiques](#practical-tips-and-tricks)
- [Cas d'utilisation](#use-cases)
- [Agents IA et automatisation](#ai-agents-and-automation)
- [Apprentissage des langues et vlogs](#language-learning-and-vlogs)
- [Prérequis](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Utilisation](#usage)
- [Exemples](#examples)
- [Notes de développement](#development-notes)
- [Dépannage](#troubleshooting)
- [Feuille de route](#roadmap)
- [Contributions communautaires](#community-contributions)
- [Contribuer](#contributing)
- [❤️ Support](#-support)
- [Contact](#connect)
- [Licence](#license)

<a id="overview"></a>
## Aperçu

`The Art of Lazying` est un dépôt parapluie de style legacy : une collection pragmatique de flux de travail IA, d'outils shell, d'expériences Raspberry Pi et de ressources d'apprentissage.

### Signaux du projet

| Signal | Valeur |
|---|---|
| Type de dépôt | Dépôt parapluie legacy |
| Runtime principal | Python + scripts shell |
| Focus matériel | Raspberry Pi + e-ink (dépendant du module) |
| Documentation | Ensemble de README multilingues dans `i18n/` |
| Licence | GNU General Public License 3.0 (racine et sous-dossiers principaux) |

<a id="features"></a>
## Fonctionnalités

- ✅ Cadre de paresse stratégique : privilégier les tâches à fort levier plutôt que les opérations répétitives.
- ✅ Outils créatifs assistés par l'IA et expériences liées à la publication.
- ✅ Utilitaire d'apprentissage des langues avec rendu e-ink et flux de travail OpenAI (`code/EinkWordsGPT`).
- ✅ Opérations shell plus sûres (`saferm` / `unrm` / `removeitanyway`).
- ✅ Scripts Python légers pour la collecte DNS/IP et la conversion code-vers-texte.
- ✅ Centre de documentation multilingue avec variantes de README dédiées à chaque langue.

<a id="projects"></a>
## Projets

### 🤖 Outils créatifs assistés par IA

| Projet | Type | Focus |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Module local | Affichage de cartes de vocabulaire e-ink sur Raspberry Pi + Waveshare avec OpenAI |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Projet externe | Analyse des origines des mots et présentation en mode graphe |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Projet externe | Outil d'apprentissage des langues |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Projet externe | Sous-titrage avec embeddings CLIP + GPT |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Projet externe | Pipeline de transcription multilingue |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Script externe | Aide à la traduction de sous-titres multilingues |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Script externe | Génération automatisée de métadonnées média |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Projet externe | Workflow de montage vidéo et de sous-titrage |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Projet externe | Automatisation de la publication de contenus |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Projet externe | Supervision + orchestration de publication |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Projet externe | Modèles avancés de prompts et d'usage de l'IA |

### 🛠️ Outils d'automatisation locale

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): workflow de suppression/récupération plus sûr pour les utilisateurs de shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): résolution DNS/nom-de-domaine vers IP + générateur de listes CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): fusionne les fichiers Python des sous-dossiers en lots texte pour revue IA.

<a id="project-structure"></a>
## Structure du projet

### Disposition actuelle du dépôt

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

### Structure conceptuelle historique (documentation)

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
## Aperçu de l'approche “lazying”

Ce dépôt aborde la productivité pratique autour de la **paresse stratégique** : automatiser les décisions à faible valeur, préserver l'énergie cognitive et appliquer des systèmes avant des tactiques.

Le principe central reste une approche pragmatique 80/20 :

- Identifier les 20 % d'actions au plus fort levier.
- Standardiser/automatiser les flux répétitifs.
- Supprimer les frictions évitables dans la pratique quotidienne.

<a id="practical-tips-and-tricks"></a>
## Conseils et astuces pratiques

- Remplacer les workflows de commandes répétitives par des fonctions shell.
- Utiliser des cycles de planification courts (cadence compatible Pomodoro).
- Réduire la fatigue décisionnelle via des templates réutilisables.
- Laisser l'IA produire un premier jet, puis le relire manuellement.

<a id="use-cases"></a>
## Cas d'utilisation

- Déléguer et automatiser les opérations récurrentes dans les flux de création.
- Rationaliser la recherche et la documentation grâce à des résumés assistés par l'IA.
- Convertir rapidement le contexte de code en texte prêt pour l'analyse IA.

<a id="ai-agents-and-automation"></a>
## Agents IA et automatisation

Les expérimentations représentées dans ce dépôt incluent :

- Un workflow d'assistant pratique autour de l'apprentissage lexical et de la création de contenu.
- Une agrégation DNS/IP scriptable pour les tâches opérationnelles.
- Une exportation repo-to-text pour une inspection de code plus rapide avec l'IA.
- Un outillage shell optionnel pour éviter les erreurs destructrices.

<a id="language-learning-and-vlogs"></a>
## Apprentissage des langues et vlogs

Le contenu et les projets linguistiques privilégient une régularité à faible effort :

- Exposition passive + révision périodique via un affichage e-ink.
- Workflows de notes interlingues dans les sous-projets soutenus.
- Scripts et notes de vlogs comme exemples d'ingénierie de routine pratique.

<a id="prerequisites"></a>
## Prérequis

Ce dépôt est organisé par modules ; il n'existe pas de manifeste de package à la racine.

### Liste de contrôle de l'environnement

| Élément | Référence |
|---|---|
| OS | Linux/macOS (outillage shell), Windows WSL accepté pour les scripts Python |
| Python | 3.9+ |
| Gestionnaire de paquets | `pip` |
| Contrôle de version | `git` |

### Dépendances par module (selon les sources)

- `code/EinkWordsGPT` : `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`, et fichiers d'exécution Raspberry Pi/e-paper (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic` : `dnspython`.
- `vlogs/repo2text` : bibliothèque standard uniquement.
- `scripts/lazy-care/SafeShell` : Bash/Zsh avec `mv`, `realpath` et flux de confirmation optionnel.

<a id="installation"></a>
## Installation

### 1) Cloner

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) Environnement virtuel recommandé

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) Installer les dépendances par module

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) Optionnel : initialisation SafeShell

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # ou ~/.zshrc
source ~/.bashrc  # ou source ~/.zshrc
```

<a id="configuration"></a>
## Configuration

### 1) OpenAI / EinkWordsGPT

Les deux scripts EinkWordsGPT instancient directement `OpenAI()`, donc l'environnement d'exécution doit fournir les identifiants.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) Emplacement de la corbeille SafeShell

`/mnt/disk/BIN/ROOT` est codé en dur comme chemin de base de la corbeille dans `scripts/lazy-care/SafeShell/safeshell_functions.sh`. Ajustez ce chemin dans le script si nécessaire.

### 3) Chemins de fusion `repo2text`

Les valeurs par défaut dans `vlogs/repo2text/convert-repo-to-merged-text.py` sont :

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

Modifiez-les avant l'exécution sauf si vous lancez le script depuis un dépôt où ces noms correspondent.

### 4) Entrées personnalisées `chatgpt-traffic`

`custom_ips`, `cidr` et `domains` sont actuellement intégrés dans `vlogs/chatgpt-traffic/chatgpt-traffic.py`. Modifiez-les directement selon vos besoins.

<a id="usage"></a>
## Utilisation

### Tableau rapide des commandes

| Tâche | Chemin | Commande |
|---|---|---|
| Boucle d'affichage EinkWordsGPT | `code/EinkWordsGPT` | `python words_gpt.py` |
| Mise à jour EinkWordsGPT | `code/EinkWordsGPT` | `python words_update.py` |
| Résolveur de domaines/IP | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Fusion repo-to-text | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| Utilisation de SafeShell | profil shell + shell actif | `saferm`, `unrm`, `removeitanyway` |

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

### SafeShell (après sourcing)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

<a id="examples"></a>
## Exemples

- `code/EinkWordsGPT/demo.jpg` : exemple de sortie e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb` : exemple de notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf` : référence des prompts.
- `demos/` : artefacts visuels utilisés dans la documentation du projet.

<a id="development-notes"></a>
## Notes de développement

- C'est un dépôt parapluie legacy ; la documentation propre à chaque module est la source principale pour le comportement d'exécution détaillé.
- Certains projets listés sont des dépôts GitHub externes ; utilisez leur README respectif pour la configuration.
- `EinkWordsGPT` dépend du matériel (Raspberry Pi + écran Waveshare).
- Plusieurs dépendances spécifiques aux modules sont déclarées en dehors du dépôt et peuvent évoluer au fil du temps.

### Hypothèses (explicites)

- La racine du dépôt et les principaux répertoires de modules utilisent la **GNU GPL v3.0** sauf indication contraire d'un autre fichier `LICENSE`.
- Les étapes d'installation des modules ne sont pas centralisées car il n'existe pas de `requirements.txt`, `pyproject.toml` ou `package.json` à la racine.

<a id="troubleshooting"></a>
## Dépannage

- `ModuleNotFoundError: waveshare_epd`
  - Installez les modules e-paper Waveshare sur la machine cible et vérifiez les pilotes matériels.
- Erreurs d'authentification OpenAI
  - Vérifiez que `OPENAI_API_KEY` est exporté dans le shell/session actif.
- `words_phonetics.db` introuvable
  - Lancez les scripts EinkWordsGPT depuis `code/EinkWordsGPT` pour que les chemins relatifs soient résolus.
- `saferm`/`unrm` indisponibles
  - Rechargez votre profil shell après l'ajout de `safeshell_functions.sh`.
- `repo2text` ne retourne rien
  - Vérifiez que `source_directory` existe et contient des fichiers `.py`.

<a id="roadmap"></a>
## Feuille de route

- Normaliser la documentation des dépendances des modules et ajouter des extraits d'installation dédiés.
- Ajouter un exécuteur de tâches racine optionnel (Makefile / script d'entrée) pour les workflows de modules.
- Améliorer la reproductibilité de la documentation pour le déploiement Raspberry Pi + Waveshare.
- Ajouter de simples tests automatisés pour les scripts utilitaires.
- Continuer d'élargir la parité linguistique dans `i18n/`.

<a id="community-contributions"></a>
## Contributions communautaires

Partagez des améliorations pratiques, des idées d'automatisation et des expérimentations d'apprentissage linguistique :

- Modèles de workflow pour les tâches de routine.
- Modèles de “paresse” qui réduisent la charge de maintenance.
- Intégrations inter-modules et corrections au niveau des scripts.

<a id="contributing"></a>
## Contribuer

Les contributions sont les bienvenues.

1. Faites un fork du dépôt.
2. Créez une branche de fonctionnalité (`git checkout -b feature/your-topic`).
3. Faites un commit (`git commit -m 'Add feature'`).
4. Poussez la branche et ouvrez une PR.

Si votre modification est spécifique à un module, mettez aussi à jour le README local de ce module.

## Connexion

| Canal | Lien |
|---|---|
| 🌐 Site web | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lachlan@lazying.art` |

<a id="license"></a>
## Licence

Ce dépôt est sous licence **GNU General Public License v3.0** (voir [LICENSE](LICENSE)).

Notes :

- La racine du dépôt et les principaux répertoires modules comprennent des fichiers `LICENSE` utilisant la GNU GPL.
- Si vous travaillez dans un sous-répertoire, utilisez le fichier `LICENSE` le plus proche pour connaître la portée exacte.


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

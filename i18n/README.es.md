[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# El arte de la pereza

<p align="center">
<a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" /></a>
<a href="https://github.com/sponsors/lachlanchen"><img alt="GitHub Sponsors" src="https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink?logo=github&logoColor=white" /></a>
<a href="https://lazying.art"><img alt="Website" src="https://img.shields.io/badge/Website-lazying.art-0a66c2?logo=Google%20Chrome&logoColor=white" /></a>
<a href="i18n"><img alt="Docs" src="https://img.shields.io/badge/Docs-Multilingual-1f883d?logo=markdown&logoColor=white" /></a>
<a href="#prerequisitos"><img alt="Python" src="https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/commits"><img alt="Last commit" src="https://img.shields.io/github/last-commit/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/issues"><img alt="Open Issues" src="https://img.shields.io/github/issues/lachlanchen/the-art-of-lazying?style=flat-square&color=orange" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/network/members"><img alt="Forks" src="https://img.shields.io/github/forks/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
</p>

Un espacio de trabajo de nivel de repositorio para experimentos prácticos de productividad asistida por IA, sistemas de aprendizaje de idiomas y herramientas utilitarias.

> Trabaja menos en tareas de bajo rendimiento y dedica más ciclos a resultados de alto impacto.

| 🎯 Enfoque | 🎛️ Stack principal | 🧭 Objetivo |
|---|---|---|
| automatizar tareas repetitivas | Python + shell | reducir la carga cognitiva |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Tabla de contenidos

- [Resumen](#resumen)
- [Caracteristicas](#caracteristicas)
- [Proyectos](#proyectos)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Vision general del enfoque perezoso](#vision-general-del-enfoque-perezoso)
- [Consejos y trucos practicos](#consejos-y-trucos-practicos)
- [Casos de uso](#casos-de-uso)
- [Agentes y automatizacion IA](#agentes-y-automatizacion-ia)
- [Aprendizaje de idiomas y vlogs](#aprendizaje-de-idiomas-y-vlogs)
- [Prerrequisitos](#prerrequisitos)
- [Instalacion](#instalacion)
- [Configuracion](#configuracion)
- [Uso](#uso)
- [Ejemplos](#ejemplos)
- [Notas de desarrollo](#notas-de-desarrollo)
- [Solucion de problemas](#solucion-de-problemas)
- [Hoja de ruta](#hoja-de-ruta)
- [Contribuciones de la comunidad](#contribuciones-de-la-comunidad)
- [Contribuir](#contribuir)
- [❤️ Support](#-support)
- [Conectar](#conectar)
- [Licencia](#licencia)

## Resumen

`El arte de la pereza` es un repositorio tipo umbrella con estilo legacy: una colección pragmática de flujos de trabajo con IA, herramientas de utilidad en shell, experimentos con Raspberry Pi y recursos de aprendizaje.

### Señales del proyecto

| Señal | Valor |
|---|---|
| Tipo de repositorio | Repositorio umbrella legacy |
| Runtime principal | Python + scripts shell |
| Enfoque de hardware | Raspberry Pi + e-ink (segun el modulo) |
| Documentacion | Conjunto de README multilingüe en `i18n/` |
| Licencia | GNU General Public License 3.0 (raiz y subcarpetas principales) |

## Caracteristicas

- ✅ Marco de trabajo de pereza estrategica: prioriza tareas de alto impacto en lugar de operaciones repetitivas.
- ✅ Herramientas creativas asistidas por IA y experimentos relacionados con publicación.
- ✅ Utilidad de aprendizaje de idiomas con renderizado en e-ink y flujo de palabras asistido por OpenAI (`code/EinkWordsGPT`).
- ✅ Operaciones de shell mas seguras (`saferm` / `unrm` / `removeitanyway`).
- ✅ Scripts ligeros en Python para recopilacion de DNS/IP y conversion de codigo a texto.
- ✅ Centro de documentacion multilingue con variantes de README por idioma.

## Proyectos

### 🤖 Herramientas creativas con IA

| Proyecto | Tipo | Enfoque |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Modulo local | Pantalla de tarjetas de palabras con Raspberry Pi + Waveshare e-ink usando OpenAI |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Proyecto externo | Analisis del origen de palabras y presentacion en grafos |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Proyecto externo | Utilidad de aprendizaje de idiomas |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Proyecto externo | Subtitulacion con embeddings CLIP + GPT |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Proyecto externo | Pipeline de transcripcion multilingue |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Script externo | Ayuda de subtitulado/traduccion multilingue |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Script externo | Generacion automatizada de metadatos multimedia |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Proyecto externo | Flujo de edicion de video y subtitulos |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Proyecto externo | Automatizacion de publicacion de contenidos |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Proyecto externo | Monitorizacion + orquestacion de publicacion |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Proyecto externo | Patrones avanzados de prompts y uso de IA |

### 🛠️ Herramientas de automatizacion local

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): flujo mas seguro para eliminar y recuperar en shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): resolucion DNS/domain-to-IP + listas CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): fusiona archivos Python en subdirectorios en lotes de texto para revision por IA.

## Estructura del proyecto

### Diseno actual del repositorio

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

### Estructura conceptual legacy (documentacion historica)

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

## Vision general del enfoque perezoso

Este repositorio enfoca la productividad practica en la **pereza estrategica**: automatiza decisiones de bajo valor, conserva energia cognitiva y aplica sistemas antes que tacticas.

El principio central permanece como una vision practica del 80/20:

- Identifica el 20% de acciones con mayor impacto.
- Estandariza y automatiza flujos repetitivos.
- Elimina la friccion evitable en la practica diaria.

## Consejos y trucos practicos

- Sustituye flujos de comandos repetitivos por funciones de shell.
- Usa ciclos cortos de planificacion (cadencia compatible con Pomodoro).
- Reduce la fatiga de decisiones creando plantillas repetibles.
- Permite que la IA haga el primer borrador/transformacion, y luego revisa manualmente.

## Casos de uso

- Delegar y automatizar operaciones recurrentes en flujos de trabajo de creadores.
- Agilizar tareas de investigacion y documentacion mediante resúmenes asistidos por IA.
- Convertir rapidamente contexto de codigo en texto apto para IA para su analisis.

## Agentes y automatizacion IA

Experimentos representados en este repositorio incluyen:

- Un flujo práctico de asistencia para aprendizaje de vocabulario y creacion de contenido.
- Agregacion scriptable de DNS/IP para tareas operativas.
- Exportacion repo-a-texto para inspeccion de codigo mas rapida con IA.
- Herramientas opcionales de seguridad a nivel de shell para evitar errores destructivos.

## Aprendizaje de idiomas y vlogs

El contenido y proyectos relacionados con idiomas enfatizan la consistencia con poco esfuerzo:

- Exposicion pasiva + repaso periodico via pantalla e-ink.
- Flujos de notas multilingues en subproyectos soportados.
- Scripts y notas de vlogs como ejemplos de ingenieria de rutina practico.

## Prerrequisitos

Este repositorio esta organizado por modulos; no hay un manifiesto de paquete a nivel raiz.

### Lista de entorno

| Item | Basico |
|---|---|
| OS | Linux/macOS (herramientas de shell), Windows WSL aceptado para scripts Python |
| Python | 3.9+ |
| Gestor de paquetes | `pip` |
| Control de versiones | `git` |

### Dependencias por modulo (segun codigo fuente)

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`, y archivos de runtime Raspberry Pi/e-paper (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic`: `dnspython`.
- `vlogs/repo2text`: solo libreria standard.
- `scripts/lazy-care/SafeShell`: Bash/Zsh con `mv`, `realpath` y flujo de confirmacion opcional.

## Instalacion

### 1) Clonar

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) Entorno virtual recomendado

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) Instalar dependencias de modulos

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) Opcional: inicializacion de SafeShell

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # o ~/.zshrc
source ~/.bashrc  # o source ~/.zshrc
```

## Configuracion

### 1) OpenAI / EinkWordsGPT

Ambos scripts de EinkWordsGPT instancian `OpenAI()` directamente, por lo que el entorno de ejecución debe exponer las credenciales.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) Ruta de basura de SafeShell

`/mnt/disk/BIN/ROOT` es la ruta base de la papelera escrita en `scripts/lazy-care/SafeShell/safeshell_functions.sh`. Ajusta esta ruta en el script si es necesario.

### 3) Rutas de `repo2text` merge

Los valores por defecto en `vlogs/repo2text/convert-repo-to-merged-text.py` son:

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

Cambialos antes de ejecutar, a menos que ejecutes desde un repositorio donde esos nombres ya encajen.

### 4) Entradas personalizadas de `chatgpt-traffic`

`custom_ips`, `cidr`, y `domains` estan incorporados actualmente en `vlogs/chatgpt-traffic/chatgpt-traffic.py`. Editalos directamente según sea necesario.

## Uso

### Tabla rapida de comandos

| Tarea | Ruta de comando | Comando |
|---|---|---|
| Bucle de visualizacion EinkWordsGPT | `code/EinkWordsGPT` | `python words_gpt.py` |
| Actualizador EinkWordsGPT | `code/EinkWordsGPT` | `python words_update.py` |
| Resolucion de dominio/IP | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Fusion repo-a-texto | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| Uso de SafeShell | perfil de shell + shell actual | `saferm`, `unrm`, `removeitanyway` |

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

### Fusion repo-a-texto

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell (despues de cargar perfil)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Ejemplos

- `code/EinkWordsGPT/demo.jpg`: muestra de salida en e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ejemplo de notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: referencia de prompts.
- `demos/`: artefactos visuales usados en la documentacion del proyecto.

## Notas de desarrollo

- Este es un repositorio umbrella legacy; la documentacion por modulo es la fuente de verdad para el comportamiento de ejecucion detallado.
- Algunos proyectos listados son repositorios externos de GitHub; usa el README de cada uno para la configuracion.
- `EinkWordsGPT` depende del hardware (Raspberry Pi + pantalla Waveshare).
- Varias dependencias a nivel de modulo se declaran fuera del repositorio y pueden desincronizarse del tiempo de publicacion de la documentacion.

### Suposiciones (explicitas)

- La raiz del repositorio y los directorios principales de modulos usan **GNU GPL v3.0** salvo que otro directorio especifique explicitamente su propio archivo `LICENSE`.
- Los pasos de instalacion no se centralizan intencionalmente porque no hay un `requirements.txt`, `pyproject.toml` ni `package.json` de nivel raiz.

## Solucion de problemas

- `ModuleNotFoundError: waveshare_epd`
  - Instala los modulos e-paper de Waveshare en la máquina destino y verifica los controladores del hardware.
- Fallos de autenticacion en peticiones OpenAI
  - Verifica que `OPENAI_API_KEY` este exportada en el shell/sesion activo.
- `words_phonetics.db` no encontrado
  - Ejecuta los scripts de EinkWordsGPT desde `code/EinkWordsGPT` para que las rutas relativas se resuelvan correctamente.
- `saferm`/`unrm` no disponible
  - Vuelve a cargar tu perfil de shell tras anadir `safeshell_functions.sh`.
- `repo2text` no devuelve salida
  - Confirma que `source_directory` exista y contenga archivos `.py`.

## Hoja de ruta

- Normalizar la documentacion de dependencias por modulos e incluir fragmentos de configuracion especificos.
- Añadir un runner raiz opcional (Makefile / punto de entrada script) para flujos modulares.
- Mejorar la reproducibilidad de la documentacion para despliegues con Raspberry Pi + Waveshare.
- Añadir pruebas automatizadas simples para scripts utilitarios.
- Seguir ampliando la paridad de idiomas en `i18n/`.

## Contribuciones de la comunidad

Comparte mejoras practicas, ideas de automatizacion y experimentos de aprendizaje de idiomas:

- Plantillas de flujo para tareas rutinarias.
- Patrones reales de pereza que reduzcan la carga de mantenimiento.
- Integraciones entre modulos y correcciones a nivel de script.

## Contribuir

Las contribuciones son bienvenidas.

1. Haz fork del repositorio.
2. Crea una rama de funcion (`git checkout -b feature/tu-tema`).
3. Haz commit de los cambios (`git commit -m 'Add feature'`).
4. Envia la rama y abre un PR.

Si tu cambio es especifico de un modulo, actualiza tambien el README local de ese modulo.

## Conectar

| Canal | Enlace |
|---|---|
| 🌐 Sitio web | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lachlan@lazying.art` |

## Licencia

Este repositorio esta licenciado bajo **GNU General Public License v3.0** (ver [LICENSE](LICENSE)).

Notas:

- Los archivos raiz y directorios principales incluyen archivos `LICENSE` con GNU GPL.
- Si trabajas en un subdirectorio especifico, usa el `LICENSE` mas cercano para conocer el alcance exacto de la licencia.


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |

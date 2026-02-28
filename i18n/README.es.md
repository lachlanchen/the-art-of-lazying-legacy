[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# El Arte de Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#prerrequisitos)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#proyectos)

Un repositorio que promueve la pereza estratégica para una vida más simple y productiva, abarcando agentes de IA, aprendizaje de idiomas y vlogs con consejos prácticos y casos de uso reales.

> Trabaja menos en tareas de bajo impacto y entrega resultados más significativos.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Tabla de Contenidos

- [Resumen](#resumen)
- [Características](#características)
- [Proyectos](#proyectos)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Introducción](#introducción)
- [La Teoría de Lazying](#la-teoría-de-lazying)
- [Consejos y Trucos Prácticos](#consejos-y-trucos-prácticos)
- [Casos de Uso](#casos-de-uso)
- [Agentes de IA y Automatización](#agentes-de-ia-y-automatización)
- [Aprendizaje de Idiomas y Vlogs](#aprendizaje-de-idiomas-y-vlogs)
- [Prerrequisitos](#prerrequisitos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Ejemplos](#ejemplos)
- [Notas de Desarrollo](#notas-de-desarrollo)
- [Resolución de Problemas](#resolución-de-problemas)
- [Hoja de Ruta](#hoja-de-ruta)
- [Contribuciones de la Comunidad](#contribuciones-de-la-comunidad)
- [Contribuir](#contribuir)
- [Contacto](#contacto)
- [❤️ Support](#-support)
- [Licencia](#licencia)

## Resumen

`The Art of Lazying` es un repositorio paraguas que combina filosofía, automatización práctica, herramientas creativas asistidas por IA y experimentos de aprendizaje de idiomas.

### Señales del Proyecto

| Signal | Value |
|---|---|
| 🧩 Repository Type | Legacy-style umbrella repo |
| 🧪 Runtime Focus | Python + shell utilities + Raspberry Pi tooling |
| 🌐 Documentation | Multilingual READMEs in `i18n/` |
| 🪪 License | MIT |

Incluye:

- Una vitrina de proyectos y flujos de trabajo de IA enlazados.
- Scripts/herramientas locales para operaciones seguras en shell y flujos utilitarios.
- Un proyecto de aprendizaje de idiomas basado en hardware (`EinkWordsGPT`) con Raspberry Pi + e-ink de Waveshare + OpenAI.
- Experimentos de vlogs/herramientas como agregación de DNS/IP y conversión de repositorios a texto.
- Documentación multilingüe en [`i18n/`](i18n).

### Vista Rápida

| Focus | What you get |
|------|---|
| 🧠 Philosophy | Strategic laziness principles for high-leverage work |
| 🤖 AI | Creative assistance, transcription, translation, publication support |
| 🛠️ Utilities | Safe shell deletion/recovery, DNS/IP tooling, repo text conversion |
| 🌍 i18n | README variants across multiple languages in `i18n/` |

## Características

- ✅ Marco de pereza estratégica centrado en esfuerzos de alto impacto.
- ✅ Referencias de flujos creativos y de publicación asistidos por IA.
- ✅ Utilidades de aprendizaje de idiomas y sistema de estudio en pantalla e-ink.
- ✅ Ayudantes de seguridad para shell (`saferm`, `unrm`, `removeitanyway`).
- ✅ Utilidades ligeras en Python para recopilación DNS/IP y fusión de texto del código fuente.
- ✅ Soporte de README multilingüe.

## Proyectos

### 🤖 Herramientas Creativas Impulsadas por IA

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

### 🔄 Herramientas de Automatización

La automatización/herramientas locales en este repositorio incluyen:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): flujo más seguro de eliminación/recuperación para usuarios de shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): resolvedor y deduplicador de dominios a IP/CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): fusiona archivos Python por subdirectorio en artefactos de texto.

## Estructura del Proyecto

### Estructura Actual del Repositorio

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

### Estructura Conceptual Original de Carpetas (Conservada)

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

## Introducción

The Art of Lazying presenta la pereza estratégica como una forma de optimizar el uso de energía y enfocarse en lo que realmente importa. Este repositorio explora cómo la pereza intencional puede conducir a mayor productividad, creatividad y bienestar.

## La Teoría de Lazying

Una introducción integral a los principios de la pereza estratégica, centrada en cómo maximizar productividad y bienestar mediante priorización, delegación y automatización de tareas.

El principio clave es aplicar la regla 80/20 de Pareto a la vida diaria: identificar el 20% de actividades que producen el 80% de los resultados deseados.

## Consejos y Trucos Prácticos

Una colección de recomendaciones accionables para aplicar principios de lazying al trabajo, las relaciones y el autocuidado:

- Automatizar tareas repetitivas.
- Usar la Técnica Pomodoro para la gestión del tiempo.
- Crear sistemas que reduzcan la fatiga de decisión.
- Aprovechar herramientas de IA como apoyo.

## Casos de Uso

Ejemplos reales que muestran cómo los principios de lazying resuelven problemas y mejoran la eficiencia:

- Cómo emprendedores usan delegación y automatización para enfocarse en el crecimiento del negocio.
- Cómo académicos simplifican flujos de investigación.
- Cómo creadores de contenido optimizan su proceso de producción.

## Agentes de IA y Automatización

Explora el desarrollo de agentes de IA y herramientas de automatización que simplifican tareas:

- Uso de ChatGPT como asistente personal.
- Construcción de flujos de automatización personalizados.
- Creación de pantallas e-ink para aprendizaje pasivo.

## Aprendizaje de Idiomas y Vlogs

Recursos y técnicas para aprender idiomas de forma eficiente, además de vlogs que documentan el camino de lazying:

- Crear aprendizaje de idiomas personalizado con repetición espaciada.
- Implementar técnicas de aprendizaje inmersivo.
- Construir proyectos que fomenten el aprendizaje pasivo.

## Prerrequisitos

Este repositorio contiene múltiples proyectos y no incluye un único manifiesto de dependencias a nivel raíz. Instala solo lo que necesites por módulo.

### Lista Base de Entorno

| Item | Baseline |
|---|---|
| OS | Linux/macOS recommended (for shell workflows) |
| Python | 3.9+ |
| Package manager | `pip` |
| Version control | `git` |

Requisitos comunes:

- `git`
- Python `3.9+` (recomendado)
- `pip`
- Herramientas opcionales para entornos virtuales (`python -m venv`)

Señales específicas de módulos desde el código fuente/READMEs:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, biblioteca Python de e-paper de Waveshare (`waveshare_epd`) y hardware compatible.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: shell Bash/Zsh.

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Recomendado) Crear un entorno virtual de Python

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Instalar dependencias de Python para los módulos seleccionados

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. Configuración de SafeShell (opcional)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Configuración

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` y `words_update.py` usan `OpenAI()` y esperan que las credenciales estén disponibles en tu entorno.
- Recomendado:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### Ubicación de papelera de SafeShell

- `safeshell_functions.sh` usa una ruta base fija de papelera:

```bash
/mnt/disk/BIN/ROOT
```

Ajusta esta ruta en el script si tu máquina usa una disposición diferente.

### Directorios de origen/destino de repo2text

- `vlogs/repo2text/convert-repo-to-merged-text.py` actualmente define:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Edita estas variables antes de ejecutar.

## Uso

### Índice Rápido de Comandos

| Task | Command Path | Primary Command |
|---|---|---|
| EinkWordsGPT display loop | `code/EinkWordsGPT` | `python words_gpt.py` |
| EinkWordsGPT updater | `code/EinkWordsGPT` | `python words_update.py` |
| Domain/IP resolver | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Repo-to-text merge | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| SafeShell recovery workflow | shell profile + current shell | `saferm`, `unrm`, `removeitanyway` |

### Ejecutar bucle de visualización de EinkWordsGPT (requiere configuración de hardware)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### Ejecutar script de mantenimiento/actualización de palabras de EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_update.py
```

### Ejecutar resolvedor de dominio/IP de tráfico de ChatGPT

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Ejecutar fusionador de archivos Python del repositorio

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### Usar comandos de SafeShell después de cargar el perfil

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Ejemplos

- `code/EinkWordsGPT/demo.jpg`: salida de ejemplo en e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ejemplo de notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: referencia de prompts.
- `demos/`: demostraciones visuales usadas en este README.

## Notas de Desarrollo

- Este repositorio es un proyecto paraguas de estilo legacy, no una aplicación monolítica empaquetada.
- Varias herramientas enlazadas en la tabla de Projects viven en repositorios externos; usa sus propios READMEs para detalles de ejecución.
- Algunos documentos internos describen estructuras antiguas de archivos (por ejemplo, `scripts/lazy-care` hace referencia a scripts separados, mientras que la implementación actual está consolidada en `SafeShell/safeshell_functions.sh`).
- El código dependiente de hardware en `EinkWordsGPT` asume un entorno Raspberry Pi + e-paper de Waveshare.

### Supuestos (Explícitos)

- El README de nivel superior es el punto de entrada canónico, mientras que las instrucciones detalladas de ejecución para proyectos externos enlazados se mantienen en sus propios repositorios.
- Las versiones de paquetes Python se dejan intencionalmente abiertas porque este repositorio no proporciona actualmente un `requirements.txt`/`pyproject.toml` en la raíz.
- Para `EinkWordsGPT`, se espera que los pasos de instalación de drivers del dispositivo Waveshare se realicen en el entorno Raspberry Pi de destino.

## Resolución de Problemas

- `ModuleNotFoundError: waveshare_epd`: instala bibliotecas e-paper de Waveshare en el dispositivo de destino y confirma dependencias específicas de hardware.
- Errores de autenticación de OpenAI: verifica que `OPENAI_API_KEY` esté configurada en la shell/sesión activa.
- `File not found` relacionado con `words_phonetics.db` o fuentes: ejecuta scripts desde `code/EinkWordsGPT` para que las rutas relativas se resuelvan correctamente.
- Comandos de SafeShell no encontrados: asegúrate de que `safeshell_functions.sh` se agregó al perfil de shell correcto y recarga la shell.
- `repo2text` no genera archivos: verifica que `source_directory` exista y contenga archivos `.py`.

## Hoja de Ruta

- Unificar la gestión de dependencias con archivos `requirements.txt` opcionales por módulo.
- Agregar ejecutores de tareas de nivel raíz o Makefile para flujos comunes.
- Ampliar documentación de configuración reproducible para despliegue Raspberry Pi + Waveshare.
- Agregar pruebas para scripts utilitarios y ayudas de transformación de datos.
- Seguir mejorando la paridad de documentación multilingüe en `i18n/`.

## Contribuciones de la Comunidad

Comparte tus experiencias, consejos e ideas sobre pereza estratégica:

- Foro para intercambiar hacks de productividad.
- Herramientas y plantillas para rutinas diarias.
- Proyectos colaborativos para eficiencia lazy.

## Contribuir

Las contribuciones son bienvenidas en contenido, scripts y documentación del proyecto.

Flujo estándar:

1. Haz un fork del proyecto.
2. Crea tu rama de funcionalidad (`git checkout -b feature/AmazingFeature`).
3. Confirma tus cambios (`git commit -m 'Add some AmazingFeature'`).
4. Sube la rama (`git push origin feature/AmazingFeature`).
5. Abre un Pull Request.

Si tu cambio afecta a un submódulo específico, actualiza también el README de ese submódulo.

## Contacto

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

Opciones adicionales (incluyendo códigos QR) se mantienen a continuación:

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

## Licencia

Este repositorio está licenciado bajo la Licencia MIT. Consulta [LICENSE](LICENSE) para más detalles.

Notas:

- Licencia del proyecto de nivel superior: MIT.
- Algunas subcarpetas incluyen sus propios archivos `LICENSE`; en caso de duda, sigue el archivo de licencia más específico en esa ruta.

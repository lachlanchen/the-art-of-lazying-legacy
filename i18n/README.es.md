[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# The Art of Lazying

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#requisitos-previos)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#proyectos)

Un repositorio que promueve la pereza estratégica para una vida más simple y productiva, abarcando agentes de IA, aprendizaje de idiomas y vlogs con consejos prácticos y casos de uso reales.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Tabla de contenidos

- [Resumen general](#resumen-general)
- [Características](#características)
- [Proyectos](#proyectos)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Introducción](#introducción)
- [La teoría de lazing](#la-teoría-de-lazying)
- [Consejos y trucos prácticos](#consejos-y-trucos-prácticos)
- [Casos de uso](#casos-de-uso)
- [Agentes de IA y automatización](#agentes-de-ia-y-automatización)
- [Aprendizaje de idiomas y vlogs](#aprendizaje-de-idiomas-y-vlogs)
- [Requisitos previos](#requisitos-previos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Ejemplos](#ejemplos)
- [Notas de desarrollo](#notas-de-desarrollo)
- [Solución de problemas](#solución-de-problemas)
- [Hoja de ruta](#hoja-de-ruta)
- [Contribuciones de la comunidad](#contribuciones-de-la-comunidad)
- [Cómo contribuir](#cómo-contribuir)
- [Contacto](#contacto)
- [Soporte / Donaciones](#soporte--donaciones)
- [Licencia](#licencia)

## Resumen general

`The Art of Lazying` es un repositorio paraguas que combina filosofía, automatización práctica, herramientas creativas asistidas por IA y experimentos de aprendizaje de idiomas.

Incluye:

- Una vitrina de proyectos y flujos de trabajo de IA enlazados.
- Scripts/herramientas locales para operaciones seguras en shell y flujos utilitarios.
- Un proyecto de aprendizaje de idiomas basado en hardware (`EinkWordsGPT`) con Raspberry Pi + e-ink de Waveshare + OpenAI.
- Experimentos de vlog/herramientas como agregación DNS/IP y conversión de repositorios a texto.
- Documentación multilingüe en [`i18n/`](i18n).

### Vista rápida

| Enfoque | Qué obtienes |
|------|---|
| 🧠 Filosofía | Principios de pereza estratégica para trabajo de alto apalancamiento |
| 🤖 IA | Asistencia creativa, transcripción, traducción y soporte de publicación |
| 🛠️ Utilidades | Eliminación/recuperación segura en shell, herramientas DNS/IP, conversión de repo a texto |
| 🌍 i18n | Variantes del README en varios idiomas dentro de `i18n/` |

## Características

- Marco de pereza estratégica centrado en esfuerzos de alto impacto.
- Referencias de flujos creativos y de publicación asistidos por IA.
- Utilidades para aprendizaje de idiomas y sistema de estudio con pantalla e-ink.
- Ayudantes de seguridad para shell (`saferm`, `unrm`, `removeitanyway`).
- Utilidades ligeras en Python para recolección de DNS/IP y fusión de texto de bases de código.
- Soporte de README multilingüe.

## Proyectos

### 🤖 Herramientas creativas impulsadas por IA

| Proyecto | Descripción | Demo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Pantalla e-ink con aprendizaje de palabras impulsado por GPT | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Análisis del origen de palabras y presentación en gráfico. | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Herramientas para aprender idiomas de forma eficiente con mínimo esfuerzo | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Subtitulado de video e imagen con embeddings de OpenAI CLIP + decodificador GPT | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | Herramienta de subtitulado de video: extrae fotogramas clave con Katna/OpenCV y genera subtítulos con un modelo ViT+GPT-2 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Pipeline de transcripción multilingüe con detección de idioma de grano fino | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Rompiendo barreras lingüísticas para el intercambio creativo global | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Generación automática de metadatos para videos | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Herramienta de edición de video automática impulsada por IA con transcripción, auto-subtítulos, resaltado y generación de metadatos | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Simplificando flujos de publicación de contenido | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Sistema automatizado para monitorear, procesar y publicar contenido de video en múltiples plataformas | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Técnicas avanzadas para usar asistentes de IA de manera eficaz | |

### 🔄 Herramientas de automatización

La automatización/herramientas locales de este repositorio incluyen:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): flujo más seguro de eliminación/recuperación para usuarios de shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): resolvedor y deduplicador de dominio a IP/CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): fusiona archivos Python por subdirectorio en artefactos de texto.

## Estructura del proyecto

### Estructura actual del repositorio

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

### Estructura conceptual original de carpetas (preservada)

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

## La teoría de lazing

Una introducción integral a los principios de la pereza estratégica, centrada en cómo maximizar la productividad y el bienestar al priorizar, delegar y automatizar tareas.

El principio clave es aplicar la regla 80/20 de Pareto a la vida diaria: identificar el 20% de actividades que producen el 80% de los resultados deseados.

## Consejos y trucos prácticos

Una colección de recomendaciones accionables para aplicar los principios de lazing al trabajo, las relaciones y el autocuidado:

- Automatizar tareas repetitivas.
- Usar la técnica Pomodoro para la gestión del tiempo.
- Crear sistemas que reduzcan la fatiga de decisiones.
- Aprovechar herramientas de IA como apoyo.

## Casos de uso

Ejemplos reales que muestran cómo los principios de lazing resuelven problemas y mejoran la eficiencia:

- Cómo emprendedores usan delegación y automatización para enfocarse en el crecimiento del negocio.
- Cómo el ámbito académico optimiza flujos de investigación.
- Cómo creadores de contenido optimizan su proceso de producción.

## Agentes de IA y automatización

Explora el desarrollo de agentes de IA y herramientas de automatización que simplifican tareas:

- Uso de ChatGPT como asistente personal.
- Construcción de flujos de automatización personalizados.
- Creación de pantallas e-ink para aprendizaje pasivo.

## Aprendizaje de idiomas y vlogs

Recursos y técnicas para aprender idiomas de forma eficiente, además de vlogs que documentan la travesía de lazing:

- Crear aprendizaje personalizado de idiomas con repetición espaciada.
- Implementar técnicas de aprendizaje inmersivo.
- Construir proyectos que fomenten el aprendizaje pasivo.

## Requisitos previos

Este repositorio es multiproyecto y no incluye un único manifiesto de dependencias de nivel superior. Instala solo lo que necesites por módulo.

Requisitos comunes:

- `git`
- Python `3.9+` (recomendado)
- `pip`
- Herramientas opcionales de entorno virtual (`python -m venv`)

Señales específicas por módulo según código fuente/README:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, librería Python de e-paper Waveshare (`waveshare_epd`) y hardware compatible.
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

### 3. Instalar dependencias de Python para módulos seleccionados

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

### Ubicación de la papelera de SafeShell

- `safeshell_functions.sh` usa una ruta base fija para la papelera:

```bash
/mnt/disk/BIN/ROOT
```

Ajusta esta ruta en el script si tu máquina usa una disposición distinta.

### Directorios origen/destino de repo2text

- `vlogs/repo2text/convert-repo-to-merged-text.py` actualmente define:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Edita estas variables antes de ejecutar.

## Uso

### Ejecutar el bucle de pantalla de EinkWordsGPT (requiere configuración de hardware)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### Ejecutar el script de mantenimiento/actualización de palabras de EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_update.py
```

### Ejecutar el resolvedor de dominio/IP de tráfico de ChatGPT

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Ejecutar el fusionador de archivos Python del repositorio

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### Usar comandos de SafeShell después de hacer sourcing

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Ejemplos

- `code/EinkWordsGPT/demo.jpg`: salida de muestra en e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ejemplo de notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: referencia de prompts.
- `demos/`: demos visuales usadas en este README.

## Notas de desarrollo

- Este repositorio es un proyecto paraguas de estilo legado, no una app monolítica empaquetada.
- Varias herramientas enlazadas en la tabla de Proyectos viven en repositorios externos; usa sus propios README para detalles de ejecución.
- Algunos documentos internos describen estructuras de archivos antiguas (por ejemplo, `scripts/lazy-care` referencia scripts separados mientras que la implementación actual está consolidada en `SafeShell/safeshell_functions.sh`).
- El código dependiente de hardware en `EinkWordsGPT` asume entorno Raspberry Pi + e-paper de Waveshare.

### Supuestos (explícitos)

- El README de nivel superior es el punto de entrada canónico, mientras que las instrucciones detalladas de ejecución para proyectos externos enlazados se mantienen en sus propios repositorios.
- Las versiones de paquetes Python se dejan intencionalmente abiertas porque este repositorio no ofrece actualmente un `requirements.txt`/`pyproject.toml` raíz.
- Para `EinkWordsGPT`, se espera que los pasos de instalación de drivers de Waveshare se realicen en el entorno Raspberry Pi de destino.

## Solución de problemas

- `ModuleNotFoundError: waveshare_epd`: instala las librerías e-paper de Waveshare en el dispositivo objetivo y confirma dependencias específicas de hardware.
- Errores de autenticación de OpenAI: verifica que `OPENAI_API_KEY` esté definido en la shell/sesión activa.
- `File not found` sobre `words_phonetics.db` o fuentes: ejecuta scripts desde `code/EinkWordsGPT` para que las rutas relativas se resuelvan correctamente.
- No se encuentran comandos de SafeShell: asegúrate de que `safeshell_functions.sh` se agregó al perfil de shell correcto y recarga la shell.
- `repo2text` no genera archivos: comprueba que `source_directory` exista y contenga archivos `.py`.

## Hoja de ruta

- Unificar la gestión de dependencias con archivos `requirements.txt` opcionales por módulo.
- Añadir task runners a nivel raíz o Makefile para flujos comunes.
- Ampliar documentación de configuración reproducible para despliegue Raspberry Pi + Waveshare.
- Añadir tests para scripts utilitarios y ayudas de transformación de datos.
- Seguir mejorando la paridad de la documentación multilingüe en `i18n/`.

## Contribuciones de la comunidad

Comparte tus propias experiencias, consejos e ideas sobre pereza estratégica:

- Foro para intercambiar trucos de productividad.
- Herramientas y plantillas para rutinas diarias.
- Proyectos colaborativos para eficiencia perezosa.

## Cómo contribuir

Se aceptan contribuciones en contenido, scripts y documentación del proyecto.

Flujo estándar:

1. Haz un fork del proyecto.
2. Crea tu rama de funcionalidad (`git checkout -b feature/AmazingFeature`).
3. Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`).
4. Haz push a la rama (`git push origin feature/AmazingFeature`).
5. Abre un Pull Request.

Si tu cambio afecta a un submódulo específico, actualiza también el README de ese submódulo.

## Contacto

| Canal | Enlace |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## Soporte / Donaciones

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

Este repositorio está licenciado bajo la licencia MIT. Consulta [LICENSE](LICENSE) para más detalles.

Notas:

- Licencia del proyecto de nivel superior: MIT.
- Algunas subcarpetas incluyen sus propios archivos `LICENSE`; en caso de duda, sigue el archivo de licencia más específico en esa ruta.

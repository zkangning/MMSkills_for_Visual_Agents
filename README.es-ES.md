

<h1 align="center">
  <img src="https://zkangning.github.io/MMSkills_for_Visual_Agents/assets/mmskills_title.svg" alt="MMSkills" width="440"/><br>
  Hacia Habilidades Multimodales para Agentes Visuales Generales
</h1>

<div align="center">

[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-Apache--2.0-green.svg)](LICENSE)
[![OSWorld](https://img.shields.io/badge/Benchmark-OSWorld-7b39e2.svg)](https://github.com/xlang-ai/OSWorld)
[![arXiv](https://img.shields.io/badge/arXiv-2605.13527-b31b1b.svg)](https://arxiv.org/abs/2605.13527)
[![Website](https://img.shields.io/badge/Website-MMSkills-0f766e.svg)](https://zkangning.github.io/MMSkills_for_Visual_Agents/)
[![Skill Library](https://img.shields.io/badge/Skill%20Library-515%20MMSkills-4420A8.svg)](https://zkangning.github.io/MMSkills_for_Visual_Agents/skills.html)
[![Demos](https://img.shields.io/badge/Demos-4%20Video%20Comparisons-a15c11.svg)](https://zkangning.github.io/MMSkills_for_Visual_Agents/cases.html)
[![Agent Adapter](https://img.shields.io/badge/Agent%20Adapter-Codex%20%7C%20OpenClaw%20%7C%20Claude%20Code-0f766e.svg)](agent_integrations/mmskills-agent-adapter/)
[![Submit MMSkill](https://img.shields.io/badge/Submit-MMSkill%20Package-a15c11.svg)](https://zkangning.github.io/MMSkills_for_Visual_Agents/submit.html)
[![GitHub stars](https://img.shields.io/github/stars/zkangning/MMSkills_for_Visual_Agents?style=social)](https://github.com/zkangning/MMSkills_for_Visual_Agents/stargazers)

</div>

<p align="center">
  <a href="#-latest-news">Noticias</a> |
  <a href="https://arxiv.org/abs/2605.13527">Artículo</a> |
  <a href="https://zkangning.github.io/MMSkills_for_Visual_Agents/">Sitio web</a> |
  <a href="https://zkangning.github.io/MMSkills_for_Visual_Agents/skills.html">Biblioteca de habilidades</a> |
  <a href="https://zkangning.github.io/MMSkills_for_Visual_Agents/cases.html">Demós</a> |
  <a href="#-agent-adapter">Adaptador de agente</a> |
  <a href="#-community-submissions">Enviar MMSkills</a> |
  <a href="#-overview">Descripción general</a> |
  <a href="#-installation">Instalación</a> |
  <a href="#-quick-start">Inicio rápido</a> |
  <a href="#-citation">Citación</a>
</p>

<h5 align="center">Si encuentras este proyecto útil, por favor danos una estrella ⭐ para las últimas actualizaciones.</h5>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=18&duration=3000&pause=1000&color=4420A8&center=true&vCenter=true&width=820&lines=Welcome+to+MMSkills;Reusable+Multimodal+Procedural+Knowledge;Skill-Augmented+Visual+Agents+for+DesktopTasks" alt="Typing Animation purple MMSkills" />
</div>

## 📣 Últimas noticias

- 🚀 **[junio de 2026]** Liberamos adaptadores para el benchmark MMSkills de [macOSWorld](macosworld_integration/), [VAB-Minecraft](vab_minecraft_integration/) y [GamingAgent](gaming_agent_integration/), facilitando la evaluación de agentes mejorados con habilidades más allá de OSWorld.
- 🏆 **[mayo de 2026]** MMSkills se ubicó en el **#1 en Hugging Face Daily Papers** el **18.05.2026**.
- 🤗 **[mayo de 2026]** El dataset MMSkills ya está disponible en [Hugging Face Datasets](https://huggingface.co/datasets/zhangkangning/mmskills); la página del artículo también está disponible en [Hugging Face Papers](https://huggingface.co/papers/2605.13527).
- 🌐 **[mayo de 2026]** El sitio web del proyecto está en línea con [comparaciones de demos](https://zkangning.github.io/MMSkills_for_Visual_Agents/cases.html) y una [Biblioteca de MMSkills](https://zkangning.github.io/MMSkills_for_Visual_Agents/skills.html) buscable que indexa **515 habilidades** en Ubuntu, macOS, VAB-Minecraft y Mario.
- 🚀 **[mayo de 2026]** La versión pública incluye un subconjunto compacto de habilidades multimodales de escritorio, adaptadores de tiempo de ejecución listos para OSWorld, mapeos de tareas y modos de habilidades independientes del modelo.
- 🔌 **[mayo de 2026]** Añadimos el **Adaptador de Agente MMSkills** para Codex, OpenClaw y Claude Code, con una instalación de un solo comando para Codex y recuperación de habilidades de Hugging Face bajo demanda.
- 🌱 **[mayo de 2026]** Las contribuciones de la comunidad de MMSkills están abiertas para nuevos dominios como conducción autónoma, robótica, agentes móviles y más.

## 🎬 Demós

Cuatro demos de OSWorld comparan la misma tarea sin habilidades, con orientación de habilidades solo en texto y con MMSkills multimodales. Estos videos muestran extractos seleccionados de trayectorias para resaltar las diferencias de comportamiento entre los tres entornos; no son trayectorias completas de principio a fin. Para mantener el texto de la GUI legible en el README de GitHub, cada caso utiliza tres reproductores MP4 1080p separados en lugar de una composición comprimida lado a lado. La disposición completa del video también está disponible en [zkangning.github.io/MMSkills_for_Visual_Agents/cases.html](https://zkangning.github.io/MMSkills_for_Visual_Agents/cases.html).

<details open>
<summary><h3>1. Encabezados fusionados en Calc</h3></summary>

<table>
  <tr>
    <th>Sin habilidades</th>
    <th>Solo texto</th>
    <th>MMSkills</th>
  </tr>
  <tr>
    <td><video src="https://github.com/user-attachments/assets/cfe1cde8-5da1-4f69-9e90-1a3ee0b82023" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/ce092ee3-4e10-44cb-bfd3-bb4780e5c9c4" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/24c8ca7a-a028-422a-8207-52b14c8b5d1e" width="280" controls></video></td>
  </tr>
</table>

Crea Hoja2, fusiona los rangos de encabezado solicitados y escribe las etiquetas objetivo. MMSkills sigue el flujo de trabajo de hojas de cálculo previsto, mientras que los otros modos progres avancesos más lentos o menos fiables.

</details>

<details>
<summary><h3>2. Instalación local de VSIX en VS Code</h3></summary>

<table>
  <tr>
    <th>Sin habilidades</th>
    <th>Solo texto</th>
    <th>MMSkills</th>
  </tr>
  <tr>
    <td><video src="https://github.com/user-attachments/assets/2296cd12-733e-4f25-95d5-402b2845ae37" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/4cfdfe99-6bb6-4a40-86ae-c7703eb1182c" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/90abd134-1e2c-4bbd-833f-83938b81383a" width="280" controls></video></td>
  </tr>
</table>

Instala una extensión VSIX local mediante el flujo de trabajo de GUI. La comparación destaca cómo las referencias de habilidades multimodales reducen los rodeos en los pasos de descubrimiento y confirmación de extensiones.

</details>

<details>
<summary><h3>3. Movimiento de capa de texto en GIMP</h3></summary>

<table>
  <tr>
    <th>Sin habilidades</th>
    <th>Solo texto</th>
    <th>MMSkills</th>
  </tr>
  <tr>
    <td><video src="https://github.com/user-attachments/assets/6f0d27ba-25a4-4b31-b34b-8480eb3d5fa0" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/57a4719d-0d62-4c00-a0b0-befecf5ac256" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/0e221a36-29a8-4b7f-8eac-1af5e492fbc7" width="280" controls></video></td>
  </tr>
</table>

Mueve una capa de texto específica en GIMP. El paquete de habilidades multimodales proporciona fundamentación visual para la capa y el estado de la barra de herramientas relevantes, haciendo que la ruta de edición sea más clara.

</details>

<details>
<summary><h3>4. Creación de gráfico en Calc</h3></summary>

<table>
  <tr>
    <th>Sin habilidades</th>
    <th>Solo texto</th>
    <th>MMSkills</th>
  </tr>
  <tr>
    <td><video src="https://github.com/user-attachments/assets/55a01c94-a748-4a22-9c40-cab707aca386" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/ca310dd1-252a-4608-a0c7-7e613b31ee08" width="280" controls></video></td>
    <td><video src="https://github.com/user-attachments/assets/1a485289-ceb5-4601-8e16-1be439593145" width="280" controls></video></td>
  </tr>
</table>

Construye el gráfico agrupado solicitado en LibreOffice Calc. La ejecución lado a lado muestra el efecto del conocimiento procedural reutilizable de hojas de cálculo en la manipulación de GUI en múltiples pasos.

</details>

## 💡 Descripción general

**MMSkills** es un framework para representar, cargar y utilizar conocimiento procedural multimodal reutilizable para agentes visuales. Cada habilidad combina orientación de procedimiento textual, metadatos compactos de "tarjetas de estado" y referencias visuales opcionales. En tiempo de inferencia, el agente mantiene solo "pistas de habilidad" ligeras en el contexto principal, y luego abre una rama temporal de habilidad cuando el estado de la tarea sugiere que puede ayudar.

<div align="center">
  <img src="https://zkangning.github.io/MMSkills_for_Visual_Agents/assets/full_figure.png" width="95%" alt="Descripción general de MMSkills" />
</div>

Este repositorio es un lanzamiento enfocado de código abierto. No es un fork completo de OSWorld; en cambio, proporciona la capa de tiempo de ejecución de MMSkill, un script de instalación, parches de ejecutor de OSWorld, mapeos de tarea a habilidad y una biblioteca de habilidades pública representativa.

Páginas del proyecto:

- [Artículo en arXiv](https://arxiv.org/abs/2605.13527)
- [Sitio web de MMSkills](https://zkangning.github.io/MMSkills_for_Visual_Agents/)
- [Biblioteca de Habilidades Multidominio Buscable](https://zkangning.github.io/MMSkills_for_Visual_Agents/skills.html)
- [Comparaciones de video de demos](https://zkangning.github.io/MMSkills_for_Visual_Agents/cases.html)

Los archivos del frontend del sitio web se publican desde la rama `gh-pages`. La rama `main` se mantiene enfocada en el código de código abierto, la integración de tiempo de ejecución, las habilidades y la documentación.

## ✨ Aspectos destacados

<table>
  <tr>
    <td width="50%"><strong>🧩 Paquetes de habilidades autocontenidos</strong><br>Cada directorio de habilidad contiene <code>SKILL.md</code>, tarjetas de estado de tiempo de ejecución, tarjetas de estado de auditoría y fotogramas clave visuales.</td>
    <td width="50%"><strong>👁️ Control de evidencia multimodal</strong><br>El tiempo de ejecución primero decide si se necesitan referencias visuales, y luego carga solo las vistas de estado solicitadas.</td>
  </tr>
  <tr>
    <td width="50%"><strong>🧠 Planificación cargada por ramas</strong><br>Una rama de planificador temporal consulta habilidades seleccionadas y devuelve orientación concisa, consejo de respaldo y señales de verificación.</td>
    <td width="50%"><strong>🔌 Preparado para OSWorld</strong><br>Scripts auxiliares instalan los archivos del agente, la integración del ejecutor, las habilidades y los mapeos de tareas en una copia"checkout"local de OSWorld.</td>
  </tr>
  <tr>
    <td width="50%"><strong>⚡ Adaptador de producto de agente</strong><br>El <code>mmskills-agent-adapter</code> puede instalarse como una habilidad de Codex y reutilizarse en OpenClaw o Claude Code a través del mismo contrato de paquete.</td>
    <td width="50%"><strong>📦 Recuperación de habilidades bajo demanda</strong><br>Los agentes buscan en la biblioteca de Hugging Face de 515 habilidades, descargan solo los paquetes relevantes para la tarea y luego leen <code>SKILL.md</code>, estados de tiempo de ejecución y referencias visuales según sea necesario.</td>
  </tr>
  <tr>
    <td width="50%"><strong>🌱 Biblioteca extensible por la comunidad</strong><br>Los investigadores pueden enviar paquetes MMSkills para nuevos dominios como conducción autónoma, robótica, aplicaciones móviles, agentes web y juegos.</td>
    <td width="50%"><strong>✅ Publicación con revisión previa</strong><br>Las contribuciones abren incidencias de GitHub, notificar a los mantenedores y son revisadas antes de normalizarse en la biblioteca pública de Hugging Face y en el sitio web.</td>
  </tr>
</table>

## 🔌 Adaptador de agente

El módulo [`mmskills-agent-adapter`](agent_integrations/mmskills-agent-adapter/) convierte a MMSkills en un adaptador de habilidades instalable y neutral respecto al producto para sistemas de agentes. Mantiene un único formato de paquete MMSkills compartido a través de Codex, OpenClaw, Claude Code y futuros productos de agente en lugar de mantener copias separadas para cada ecosistema.

El adaptador es intencionalmente ligero. No empaqueta el conjunto completo de 515 habilidades dentro de la rama del repositorio. En su lugar, señala a los agentes al [dataset público de Hugging Face de MMSkills](https://huggingface.co/datasets/zhangkangning/mmskills), busca en el índice de metadatos y descarga solo el paquete de ˜habilidad˜ necesario para la tarea actual.

Instalación de Codex en un solo comando:

```bash
curl -fsSL https://raw.githubusercontent.com/zkangning/MMSkills_for_Visual_Agents/main/scripts/install_codex_mmskills.sh | bash
```

Formulario de instalación de habilidades de Codex directo:

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo zkangning/MMSkills_for_Visual_Agents \
  --path agent_integrations/mmskills-agent-adapter
```

Después de reiniciar Codex, invoca `$mmskills` para tareas de agente GUI o de uso de computadora. Los scripts del adaptador proporcionan el flujo estándar:

```bash
python scripts/search_skills.py "chrome bookmark" --package ubuntu
python scripts/download_skill.py ubuntu/chrome/CHROME_Manage_Bookmarks_Reading_List_And_Shortcuts
python scripts/inspect_skill.py ~/.cache/mmskills/skills/ubuntu/chrome/CHROME_Manage_Bookmarks_Reading_List_And_Shortcuts
```

Para OpenClaw y Claude Code, utiliza el mismo contrato del adaptador: llama a los scripts de búsqueda/descarga, analiza `SKILL.md` y `runtime_state_cards.json`, y enruta `Images/` a la capa de fundamentación o verificación visual del producto solo cuando se necesite evidencia visual.

## 🌱 Contribuciones de la comunidad

Damos la bienvenida a paquetes de MMSkills de nuevos dominios. Una contribución puede ser una única habilidad reutilizable o una colección de un nuevo dominio, como conducción autónoma, robótica, agentes móviles, flujos de trabajo de navegador, software científico, juegos u otros entornos de agentes visuales.

Envía tu contribución a través del punto de entrada del sitio web o directamente mediante el formulario de incidencias de GitHub:

- Punto de entrada del sitio web: [zkangning.github.io/MMSkills_for_Visual_Agents/submit.html](https://zkangning.github.io/MMSkills_for_Visual_Agents/submit.html)
- Formulario de incidencias de GitHub: [Enviar un paquete MMSkill](https://github.com/zkangning/MMSkills_for_Visual_Agents/issues/new?template=skill_submission.yml)
- Guía de formato: [docs/submit_mmskills.md](docs/submit_mmskills.md)

Cada contribución crea una incidencia de GitHub asignada a la cuenta del mantenedor, para que los mantenedores puedan recibir notificaciones por correo electrónico a través de la configuración de notificaciones del repositorio de GitHub. Después de la revisión, los paquetes aceptados se normalizan en la biblioteca MMSkills, se cargan en el dataset público de Hugging Face y se muestran en la Biblioteca de Habilidades del sitio web.

## 🗂️ Estructura del repositorio

```text
MMSkills/
├── agent_integrations/        # Adaptadores y helpers de descarga para agentes Codex/OpenClaw/Claude Code
├── gaming_agent_integration/  # Adaptador SkillsAgent minimalista para GamingAgent/Lmgame-Bench
├── macosworld_integration/    # Archivos de agente MMSkills minimalistas para macOSWorld
├── mm_agents/                 # Adaptadores de agente OSWorld públicos y tiempo de ejecución de MMSkill
├── osworld_integration/       # Archivos de ejecutor de OSWorld con conciencia de MMSkills
├── skills_library/            # Subconjunto público de habilidades multimodales para uso directo en tiempo de ejecución
├── task_skill_mappings/       # Mapeo de tareas de OSWorld a habilidades para las habilidades publicadas
├── vab_minecraft_integration/ # Adaptador HTTPAgent minimalista para VAB-Minecraft
└── scripts/
    ├── install_into_osworld.py # Instala esta versión en un checkout de OSWorld
    └── sync_from_sources.py    # Helper de sincronización del mantenedor para checkouts de fuentes
```

## 🧠 Arquitectura

El punto de entrada del tiempo de ejecución público es [`mm_agents/mm_skill_agent.py`](mm_agents/mm_skill_agent.py), expuesto en OSWorld como:

```bash
--agent_type mm_skill
```

La arquitectura es independiente del modelo. Un agente visual principal recibe pistas de habilidades compactas; cuando una habilidad podría resultar"aplicarse", el tiempo de ejecución abre una rama que decide si se necesita evidencia visual, solicita vistas de estado relevantes, las compara con la captura de pantalla en vivo y devuelve una guía estructurada para la siguiente acción fundamentada.

Las capas de implementación históricas de MMSkills residen en `mm_agents/_mmskills_internal/`. Son módulos de soporte privados para `MMSkillAgent`, no elecciones de agente separadas. Usa `--agent_type mm_skill` para el tiempo de ejecución multimodal de MMSkills.

La integración de referencia soporta:

- `mm_skill`: consulta de habilidades cargada por rama multimodal.
- `general_text_skill`: consulta de habilidades solo en texto para ablativos y ejecuciones ligeras.
- `general_skill`: ablativo de contexto de habilidad `inline` para comparaciones hered"legadas".
- `general`: enrutamiento visual ˜"agente de captura a pyautogui"˜ base˜"independiente del modelo"˜.

Los nombres CLI heredados `gemini`, `gemini_skill` y `gemini_text_skill` todavía son aceptados por el ejecutor como `aliases` por compatibilidad, pero los archivos públicos y los comandos recomendados utilizan los nombres `general*` independientes del modelo.

Cualquier VLM con capacidad de captura de pantalla servido a través de una API de `chat-completions` compatible con OpenAI puede usar las mismas interfaces `general*` y `mm_skill` configurando `--model`, `--api_model` si es necesario, `--base_url` y `--api_key`.

## 🧩 Integraciones de benchmark

OSWorld es el tiempo de ejecución de referencia en este repositorio. Los adaptadores de benchmark adicionales se mantienen en carpetas separadas para que cada benchmark solo reciba los archivos de agente mínimos que necesita:

- [`osworld_integration/`](osworld_integration/): `--agent_type mm_skill`.
- [`macosworld_integration/`](macosworld_integration/): `openai-skill-v2-mm-branch` y `openai-skill-text-branch`.
- [`gaming_agent_integration/`](gaming_agent_integration/): GamingAgent `--agent_type skills`.
- [`vab_minecraft_integration/`](vab_minecraft_integration/): Envoltorio HTTP de VAB-Minecraft más agente de habilidad multimodal Gemini.

Cada carpeta contiene un README con comandos de copia/instalación para el `checkout` de benchmark correspondiente.

## 🔧 Instalación

### 1. Clonar MMSkills

```bash
git clone https://github.com/zkangning/MMSkills_for_Visual_Agents.git
cd MMSkills_for_Visual_Agents
```

### 2. Instalar dependencias de Python

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 3. Instalar en OSWorld

Clona e instala OSWorld siguiendo sus instrucciones originales, luego ejecuta:

```bash
python3 scripts/install_into_osworld.py /path/to/OSWorld --with-runner --with-skills
```

Esto copia los archivos del agente MMSkill en `OSWorld/mm_agents/`, instala los archivos del ejecutor con conciencia de MMSkills y copia la `skills_library/` publicada más `task_skill_mappings/`.

### 4. Configurar puntos finales de modelos

Para un punto final compatible con OpenAI:

```bash
export OPENAI_BASE_URL="https://your-openai-compatible-endpoint/v1"
export OPENAI_API_KEY="your_api_key"
```

Para enrutamiento nativo compatible con Gemini, pasa `--api_backend gemini` y configura:

```bash
export GEMINI_BASE_URL="https://your-gemini-compatible-endpoint/v1"
export GEMINI_API_KEY="your_api_key"
```

### 5. Instalar el Adaptador de Agente Codex

MMSkills también incluye un adaptador de producto de agente bajo [`agent_integrations/mmskills-agent-adapter/`](agent_integrations/mmskills-agent-adapter/). El adaptador es instalable como una habilidad de Codex y señala a los agentes al conjunto completo de dataset de habilidades de Hugging Face para la recuperación bajo demanda. Consulta [Adaptador de agente](#-agent-adapter) para el contrato completo entre agentes.

Instalación de Codex en un solo comando:

```bash
curl -fsSL https://raw.githubusercontent.com/zkangning/MMSkills_for_Visual_Agents/main/scripts/install_codex_mmskills.sh | bash
```

Formulario de instalación de habilidades de Codex directo:

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo zkangning/MMSkills_for_Visual_Agents \
  --path agent_integrations/mmskills-agent-adapter
```

Después de reiniciar Codex, usa `$mmskills` para buscar y cargar paquetes relevantes para la tarea. El mismo contrato del adaptador está destinado para OpenClaw y Claude Code: comparte el formato de paquete MMSkills, mantiene el comportamiento específico del producto en adaptadores ligeros y descarga solo las habilidades necesarias para la tarea actual desde [Hugging Face Datasets](https://huggingface.co/datasets/zhangkangning/mmskills).

## 🏃 Inicio rápido

Ejecuta los comandos desde el `checkout` de OSWorld después de la instalación.

### Línea base sin habilidades

```bash
python run.py \
  --agent_type general \
  --model gpt-4o \
  --api_backend openai \
  --observation_type screenshot \
  --action_space pyautogui \
  --max_steps 20 \
  --test_all_meta_path evaluation_examples/test_nogdrive.json \
  --domain chrome \
  --result_dir results/no_skills
```

### Habilidades solo en texto

```bash
python run.py \
  --agent_type general_text_skill \
  --model gpt-4o \
  --api_backend openai \
  --observation_type screenshot \
  --action_space pyautogui \
  --max_steps 20 \
  --skills_library_dir skills_library \
  --task_skill_mapping_root task_skill_mappings/task_skill_mapping.json \
  --skill_mode text_only \
  --text_skill_mode branch_planner \
  --test_all_meta_path evaluation_examples/test_nogdrive.json \
  --domain chrome \
  --result_dir results/text_only
```

### Agente MMSkill Multimodal

```bash
python run.py \
  --agent_type mm_skill \
  --model gpt-4o \
  --api_backend openai \
  --observation_type screenshot \
  --action_space pyautogui \
  --max_steps 20 \
  --skills_library_dir skills_library \
  --task_skill_mapping_root task_skill_mappings/task_skill_mapping.json \
  --skill_mode multimodal \
  --task_skill_top_k 6 \
  --save_conversation_json \
  --test_all_meta_path evaluation_examples/test_nogdrive.json \
  --domain chrome \
  --result_dir results/mm_skill_multimodal
```

Usa `--domain all` para la división completa de OSWorld sin Google Drive. El ejecutor escribe trayectorias, capturas de pantalla, `skill_invocations.json`, `skill_usage_summary.json` y métricas agregadas bajo el `--result_dir` seleccionado.

## 📚 Biblioteca de habilidades

El sitio web indexa **515 habilidades** de los activos de habilidades open-source de Ubuntu, macOS, VAB-Minecraft y Mario. Cada tarjeta de habilidad enlaza a una vista estructurada de su `SKILL.md`, tarjetas de estado de tiempo de ejecución y referencias visuales ordenadas.

Explora la biblioteca en vivo en [zkangning.github.io/MMSkills_for_Visual_Agents/skills.html](https://zkangning.github.io/MMSkills_for_Visual_Agents/skills.html).

El repositorio también incluye un subconjunto compacto listo para tiempo de ejecución bajo [`skills_library/`](skills_library/) para una integración inmediata con OSWorld.

## 📦 Formato del paquete de ˜habilidad"

```text
skills_library/<domain>/<skill_name>/
├── SKILL.md                  # Procedimiento, aplicabilidad, límites de transferencia, comprob"verificaciones"
├── runtime_state_cards.json  # Metadatos de estado/vista compactos utilizados en tiempo de inferencia
├── state_cards.json          # Metadatos de estado de auditoría para inspección
├── plan.json                 # Metadatos de plan generado, cuando están disponibles
└── Images/                   # Fotogramas completos, recortes de enfoque, referencias antes/después
```

El agente principal solo ve nombres de habilidades concisos y pistas de estado. La evidencia visual detallada se carga˜"perezosamente"˜ por el planificador de ramas, lo que mantiene el contexto principal compacto mientras preserva el acceso a referencias multimodales específicas del estado.

`runtime_state_cards.json` es la versión orientada a la inferencia: contiene descripciones de estado compactas, reglas de cuándo usar, señales visibles, señales de verificación y vistas de imagen seleccionadas para la carga en tiempo de rama. `state_cards.json` es la versión más rica de autoría/auditoría: conserva notas de límites de transferencia, objetivos de resaltado, consultas de fundamentación, cajas delimitadoras, decisiones de recorte y metadatos de˜"fuentes de evidencia"˜ para inspección y regeneración.

## 🧪 Salidas

MMSkills añade artefactos con conciencia de habilidades a los directorios de resultados de OSWorld:

| Archivo | Propósito |
|------|---------|
| `skill_invocations.json` | Registros de consulta por rama, estados seleccionados, vistas solicitadas y salidas del planificador |
| `skill_usage_summary.json` | Conteo agregado de habilidades, conteo de éxitos de rama, habilidades agotadas y acciones finales |
| `conversation.json` | Trazado de conversación principal y de rama opcional cuando `--save_conversation_json` está habilitado |

## 🤝 Contribución

Son bienvenidas las contribuciones para nuevas habilidades, integraciones de tiempo de ejecución, documentación y correcciones de reproducibilidad. Por favor, lee [`CONTRIBUTING.md`](CONTRIBUTING.md) antes de abrir una incidencia o `pull request`.

## 📄 Licencia

Este proyecto se publica bajo la [Licencia Apache 2.0](LICENSE). Porciones de la integración de OSWorld están derivadas de OSWorld; consulta [NOTICE](NOTICE) para los detalles de atribución.

## 📝 Citación

Si utilizas MMSkills en tu investigación o aplicaciones, por favor cita nuestro artículo de arXiv:

```bibtex
@misc{zhang2026mmskills,
  title = {MMSkills: Towards Multimodal Skills for General Visual Agents},
  author = {Kangning Zhang and Shuai Shao and Qingyao Li and Jianghao Lin and Lingyue Fu and Shijian Wang and Wenxiang Jiao and Yuan Lu and Weiwen Liu and Weinan Zhang and Yong Yu},
  year = {2026},
  eprint = {2605.13527},
  archivePrefix = {arXiv},
  primaryClass = {cs.AI},
  url = {https://arxiv.org/abs/2605.13527}
}
```

También puedes utilizar los metadatos de citación legibles por máquina en [`CITATION.cff`](CITATION.cff).

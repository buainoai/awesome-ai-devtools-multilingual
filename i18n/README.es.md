> **🌍 语言 / Languages:**
> [中文](./README.zh.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 Herramientas para Desarrolladores Impulsadas por IA

Esta es una lista curada de herramientas para desarrolladores impulsadas por IA. Estas herramientas aprovechan la IA para asistir a los desarrolladores en tareas como la compleción de código, refactorización, depuración, documentación y más.

- [IDEs](#ides)
- [Clientes Git](#git-clients)
- [Asistentes](#assistants)
  - [Basados en web](#web-based)
  - [Extensiones de IDE](#ide-extensions)
  - [Línea de comandos](#command-line)
  - [Escritorio](#desktop)
- [Asistentes de Shell](#shell-assistants)
- [Agentes](#agents)
- [Agentes de PR](#pr-agents)
- [Generadores de aplicaciones](#app-generators)
- [Generadores de UI](#ui-generators)
- [Generadores de fragmentos de código](#snippet-generators)
- [Documentación](#documentation)
- [Plugins de OpenAI](#openai-plugins)
- [Búsqueda](#search)
- [Pruebas](#testing)
- [Evaluación](#evaluation)
- [Recursos](#resources)

## IDEs
- [Google Antigravity](https://antigravity.google/) — Un IDE centrado en agentes que orquesta agentes de IA autónomos para planificar, ejecutar y verificar tareas de codificación complejas con una profunda integración con el navegador.
- [Crystal](https://github.com/stravu/crystal) — Un nuevo tipo de entorno de desarrollo para gestionar, inspeccionar y probar sesiones paralelas de Claude Code.
- [Cursor](https://www.cursor.com/) — Un IDE con funciones de chat, edición, generación y depuración. Bifurcado de VSCodium, por lo que la interfaz es similar a VS Code. Utiliza OpenAI.
- [OpenMagic](https://github.com/Kalmuraee/OpenMagic) — AI-powered coding toolbar for any web app. Captures element context, previews diffs, and applies approved changes through a reverse proxy.
- [PearAI](https://trypear.ai/) — Una bifurcación de código abierto de VS Code con chat y generación de código en línea.
- [Melty](https://melty.sh/) — Una bifurcación de código abierto de VS Code con chat integrado, previsualizaciones de cambios y capacidad para escribir commits con IA. Actualmente solo está disponible el código fuente.
- [Replit](https://replit.com/) — IDE basado en web con entornos de desarrollo en la nube, compleción de código, chat, un agente de desarrollo de software y despliegues.
- [Mutable](https://github.com/mutableai/monitors4codegen) — IDE basado en web, integrado con un chatbot y GitHub.
- [CodeStory](https://codestory.ai/) — Un IDE con chat, explicaciones de código, commits autogenerados y resúmenes de PR. Bifurcado de VSCodium.
- [UI Pilot](https://ui-pilot.com/) — Editor de código AI basado en chat que crea formularios usando Material UI, utilizando GPT-4.
- [GitWit](https://gitwit.dev/) — Editor basado en web para construir aplicaciones ReactJS con IA.
- [Windsurf](https://windsurf.com) — Un IDE con funciones de chat, edición, generación y depuración. Bifurcado de VSCodium, por lo que la interfaz es similar a VS Code. Anteriormente conocido como Codeium.
- [Theia IDE](https://theia-ide.org/#theiaide) — Un IDE extensible de código abierto (web y escritorio) que proporciona funciones impulsadas por IA como chat, compleción de código, asistencia de terminal y agentes personalizados utilizando LLMs arbitrarios. Construido sobre [Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/), una plataforma diseñada para permitir la creación de herramientas e IDEs personalizados impulsados por IA.
- [OneCompiler](https://onecompiler.com/) — Un compilador en línea gratuito impulsado por IA que soporta más de 70 lenguajes, incluyendo Java, Python, MySQL, C++ y HTML, para escribir, ejecutar y compartir código.
- [trae](https://www.trae.ai/) — Trae es un IDE de IA adaptativo que transforma tu forma de trabajar, colaborando contigo para ir más rápido.
- [Zed](https://zed.dev/) - Un editor de código multijugador de alto rendimiento de los creadores de Atom y Tree-sitter.
- [Nimbalyst](https://nimbalyst.com) - Un entorno de gestión de agentes para Claude Code y Codex. Edición visual interactiva de markdown, maquetas, excalidraw, código. Gestión de sesiones paralelas.

## Clientes Git

- [GitBrain](https://gitbrain.dev/) — Cliente Git que simplifica el flujo de trabajo de Git. Divide los cambios de código, genera resúmenes y mensajes de commit para los cambios de código. Utiliza OpenAI.
- [GitButler](https://gitbutler.com/) — Cliente Git para ramas simultáneas sobre tu flujo de trabajo existente. Por defecto usa OpenAI, se puede cambiar a Perplexity para generar mensajes de commit convencionales.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - Herramienta CLI que utiliza IA para generar automáticamente mensajes de commit de Git y descripciones de pull request de alta calidad.

## Asistentes

### Basados en web

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — Asistente integrado en [Replit](https://replit.com/) con chat, depuración proactiva y autocompletado. Utiliza OpenAI para el chat y [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS) para el autocompletado.
- [Unblocked](https://getunblocked.com/) — Aumenta el código fuente con conocimiento existente relevante en GitHub, Slack, Jira, Confluence y más. Obtén respuestas a través del chat y el contexto a nivel de archivo del IDE. Disponible en web, macOS, Slack, VSCode y los IDEs de JetBrains.
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — Asistente con chat, refactorización y generación de pruebas unitarias. Extensiones para VS Code y IntelliJ. También disponible como aplicación web.
- [Magnet](https://www.magnet.run/) — Chatbot basado en web con repositorios y problemas como contexto.
- [Adrenaline](https://useadrenaline.com/) — Chatbot basado en web que utiliza IA y ASTs para responder preguntas sobre tu base de código.
- [CodeSquire](https://codesquire.ai/) — Extensión de Chrome que añade autocompletado a Google Colab, BigQuery y JupyterLab.
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — Asistente de código abierto con editor e intérprete de Python integrados.
- [Onboard](https://www.getonboardai.com) — Chatea con una IA sobre bases de código públicas y privadas.
- [Code to Flow](https://codetoflow.com) — Visualiza, analiza y comprende código con diagramas de flujo interactivos.
- [Pieces](https://pieces.app/) — Un copiloto en el dispositivo que te ayuda a capturar, enriquecer y reutilizar código, agilizar la colaboración y resolver problemas complejos a través de una comprensión contextual de tu flujo de trabajo.
- [Wren AI](https://getwren.ai/oss) — Agente de IA SQL para obtener resultados e información más rápido haciendo preguntas sin escribir SQL, ¡y es de código abierto!
- [TEXT2SQL.AI](https://www.text2sql.ai/) — Constructor de consultas SQL impulsado por IA. Traduce, explica y corrige consultas SQL complejas usando lenguaje natural.
- [SQLAI.ai](https://www.sqlai.ai/) — La IA genera, corrige, explica y optimiza consultas SQL. Capacidad para añadir tu propio esquema de base de datos y entrenar a la IA para que lo entienda.
- [CodeWP](https://codewp.ai/) — Herramientas de chat y codificación de IA específicamente entrenadas para desarrolladores de WordPress. Generación de código AI para fragmentos de código y plugins en WordPress.
- [Gru.ai](https://www.gru.ai/) — Un desarrollador de IA puede ayudarte a resolver problemas técnicos y abordar tareas de codificación diarias, como construir algoritmos, depurar problemas, probar soluciones, responder preguntas de programación, etc.

### Extensiones de IDE

- [GitHub Copilot](https://github.com/features/copilot) — Una extensión de VS Code con chat, generación de texto para pull requests y generación de pruebas unitarias.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — Agente de codificación autónomo para VS Code que puede crear/editar archivos, ejecutar comandos y usar el navegador con permiso del usuario. Soporta múltiples proveedores de IA incluyendo OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure y GCP Vertex.
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — Asistente de código abierto con chat, compleción, refactorización y ajuste fino específico de la base de código. Extensiones para VS Code y JetBrains.
- [Continue](https://continue.dev/) — Extensión de VS Code con chat, refactorización y generación de código. Edita múltiples archivos y ejecuta comandos en tu nombre.
- [Blackbox AI](https://www.useblackbox.io/) — Extensión de VS Code con autocompletado y chat que incluye enlaces a referencias de codificación en línea.
- [CodeGeeX](https://codegeex.cn/) — Asistente de código abierto basado en el LLM CodeGeeX con chat, compleción y refactorización. Extensiones para 9 editores incluyendo VS Code y PyCharm.
- [Quack AI](https://www.quackai.com/) — Extensión de VS Code para adherirse a las directrices de codificación del proyecto.
- [Tabby](https://tabbyml.github.io/tabby/) — Asistente de compleción de código de código abierto y autoalojado. Extensiones para VS Code y Vim.
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — Asistente de compleción de código de código abierto y autoalojado. Extensiones para 15 editores incluyendo VS Code, IntelliJ, Neovim, Eclipse y PyCharm.
- [CodeMate](https://www.codemate.ai/) — Extensión de VS Code para depurar y optimizar código.
- [AskCodi](https://www.askcodi.com/) — Asistente de codificación de IA con extensiones para VS Code, JetBrains y Sublime Text.
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Asistente de chat de código abierto para la barra lateral de Visual Studio Code.
- [CodeComplete](https://codecomplete.ai/) — Asistente de compleción empresarial autoalojado.
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo es un agente de IA que te permite construir y desplegar aplicaciones full-stack sin esfuerzo, con despliegue en Vercel con un solo clic e integración perfecta con Supabase.
- [JetBrains AI](https://www.jetbrains.com/ai/) — Asistente de IA disponible en todos los IDEs de JetBrains.
- [aiXcoder](https://www.aixcoder.com/en/) — Asistente local o basado en la nube con extensiones para IntelliJ IDEA, CLion, GoLand, PyCharm, WebStorm, Visual Studio Code y Eclipse.
- [Sourcery](https://sourcery.ai/) — Asistente de IA y linter con una referencia de 160 mejores prácticas de Python y más de 40 mejores prácticas de JS/TS. Extensiones para VS Code, PyCharm, vim y Sublime.
- [Swimm](https://swimm.io) — Asistente para la comprensión contextual del código utilizando análisis estático y documentación generada por IA. VSCode, Jetbrains, IntelliJ, WebStorm, Rider, PhpStorm, Android Studio, PyCharm, PhPStorm.
- [Supermaven](https://supermaven.com/) — Extensión de VS Code para autocompletado con una ventana de contexto de 300.000 tokens.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — Asistente de codificación de IA con extensiones para IDEs como VS Code e IntelliJ IDEA. El plugin Amazon Q Developer IDE tiene varios agentes que también pueden escanear código para resaltar y definir problemas de seguridad (/review), escribir documentación (/doc), escribir pruebas unitarias (/test) y ayudarte a actualizar a versiones posteriores de Java (/transform) (anteriormente conocido como Amazon CodeWhisperer).
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot es un asistente de codificación impulsado por IA que está estrechamente integrado en Android Studio. Studio Bot puede ayudar a los desarrolladores de Android a generar código, encontrar recursos relevantes, aprender las mejores prácticas y ahorrar tiempo.
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z es un producto de modernización de aplicaciones mainframe impulsado por IA con generación de código. Las características incluyen descubrimiento y análisis de aplicaciones, refactorización automatizada de código y conversión de COBOL a Java.
- [EasyCode](https://www.easycode.ai/) — Extensión de VS Code con chat GPT-4.
- [Kilo Code](https://kilocode.ai) - Asistente de codificación de IA de código abierto para planificar, construir y corregir código dentro de VS Code.
- [FlyonUI MCP](https://flyonui.com/mcp) — Integra FlyonUI MCP - Tailwind AI Builder directamente en tu IDE y crea impresionantes componentes, bloques y páginas de Tailwind CSS inspirados en FlyonUI.
- [Traycer](https://traycer.ai) - Asistente de codificación "Plan-First" en VS Code.
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - Integra shadcn/studio MCP Server directamente en tu IDE favorito y crea impresionantes componentes, bloques y páginas de shadcn/ui inspirados en shadcn/studio.

### Línea de comandos

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - CLI que proporciona compleción de comandos, traducción de comandos utilizando IA generativa para traducir la intención a comandos, y una interfaz de chat agéntica completa con gestión de contexto que te ayuda a escribir código. Funciona con muchos terminales y shells, en MacOS, Linux y Windows (a través de wsl).
- [aloc](https://github.com/modern-tooling/aloc) — Un contador de líneas de código moderno y aumentado por IA construido con Rust y Ratatui. Utiliza perfiles de esfuerzo de IA para una estimación precisa del proyecto.
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — Chatbot CLI con repositorio como contexto. Soporta OpenAI, así como LLMs que se ejecutan localmente a través de GPT4All.
- [gptcomet](https://github.com/belingud/gptcomet) — Herramienta CLI para ayudarte a generar mensajes de commit y revisar cambios. Soporta múltiples proveedores e idiomas.
- [poorcoder](https://github.com/vgrichina/poorcoder) — Una colección de scripts Bash para extraer el contexto del código, aplicar cambios de markdown y generar mensajes de commit de IA utilizando LLMs basados en la web.
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — Una herramienta de autocompilación que transforma pilas de prompts basadas en markdown en código y pruebas utilizando la generación de LLM. Funciona con cualquier LLM a través de OpenRouter, incluyendo Claude, ChatGPT y Grok.
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - Convierte el lenguaje natural en comandos de shell ejecutables (ej.: `ai Dime el espacio libre en disco`).
- [promptext](https://github.com/1broseidon/promptext) — Extractor de contexto de código inteligente para asistentes de IA con conteo preciso de tokens, priorización de relevancia y gestión de presupuesto. Prepara contexto de código optimizado dentro de los límites de tokens de LLM.
- [Baz CLI](https://github.com/baz-scm/baz-cli) - CLI para revisión de código asistida por IA, con acceso al código real, diff, etc.
- [AdaL](https://sylph.ai/) — Agente de codificación de IA autoevolutivo que permite que los modelos colaboren (Claude, GPT, Gemini). Se ejecuta localmente, aprende los patrones de tu base de código.
- [Tokscale](https://github.com/junhoyeo/tokscale) — Herramienta CLI para rastrear el uso de tokens de agentes de codificación de IA (OpenCode, Claude Code, OpenClaw, Codex, Gemini CLI, Cursor IDE, AmpCode, Factory Droid) con una tabla de clasificación global y gráficos de contribución 2D/3D.
- [vsync](https://github.com/nicepkg/vsync) — Herramienta CLI que sincroniza Skills, servidores MCP, Agentes y Comandos a través de Claude Code, Cursor, OpenCode y Codex con conversión automática de formato (JSON ↔ TOML ↔ JSONC).
- [Arctic](https://github.com/arctic-cli/interface): Una TUI centrada en el terminal que unifica múltiples planes y APIs de codificación de IA con visibilidad de uso y cuota incorporada.

### Escritorio

- [Memex](https://memex.tech/) — Construye cualquier cosa en cualquier stack, con solo lenguaje natural, en tu escritorio.
- [Pieces](https://pieces.app/) — Aplicación de escritorio y extensión de navegador habilitadas para IA diseñadas para ayudar a los desarrolladores a mejorar la productividad.

## Asistentes de Shell

- [AskCommand](https://www.askcommand.cppexpert.online/) — Herramienta basada en web para generar comandos Unix a partir de texto automáticamente usando IA.
- [Butterfish](https://butterfi.sh) — Herramienta CLI que integra ChatGPT en tu shell para un fácil acceso. Incluye capacidades agénticas simples.
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — Asistente CLI altamente configurable para generar comandos de shell y obtener explicaciones para ellos.
- [GitFluence](https://www.gitfluence.com/) — Generador de comandos Git basado en web para generar automáticamente comandos Git para terminal o CLI a partir de una descripción de texto, utilizando una solución impulsada por IA para sugerir los comandos Git más relevantes.
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - Herramienta CLI que añade sugerencias de línea de comandos impulsadas por IA directamente a tu terminal con solo escribir <TAB><TAB> para obtener las mejores sugerencias.
- [code-collator](https://github.com/tawandakembo/code-collator) — Herramienta CLI que crea un único archivo markdown que describe toda tu base de código a los modelos de lenguaje. Útil para la asistencia de codificación de IA desde la interfaz web de Claude/ChatGPT en lugar de a través de la API.
- [Warp](https://www.warp.dev/) - Warp une la IA y el conocimiento del equipo en un terminal único, rápido e intuitivo.
- [TmuxAI](https://tmuxai.dev/) - Asistente de terminal no intrusivo impulsado por IA.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - Gestiona plantillas/fragmentos de comandos con compleciones dinámicas e integración de IA.

## Agentes

- [Smol Developer](https://github.com/smol-ai/developer) — Agente CLI que genera un repositorio a partir de un prompt. Utiliza OpenAI y Anthropic.
- [Aider](https://github.com/paul-gauthier/aider) — Asistente y agente CLI que genera cambios y commits en repositorios. Utiliza OpenAI.
- [Blinky](https://github.com/seahyinghang8/blinky) — Un agente de depuración para VS Code que ayuda a identificar y corregir errores de backend, inspirado en SWE-agent.
- [Mentat](https://www.mentat.ai/) — Asistente y agente CLI que realiza cambios en repositorios.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — Agente CLI que genera un repositorio a partir de un prompt y hace preguntas aclaratorias.
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — Agente CLI que convierte una aplicación full-stack de un lenguaje o framework a otro. Utiliza el contexto de 32k de GPT-4.
- [Grit](https://app.grit.io) — Agente integrado en GitHub para automatizar tareas de mantenimiento y otros trabajos de desarrollo.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Generador de aplicaciones Auto Gen-AI con el poder de Llama 2.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT: Solución de automatización del desarrollo de software impulsada por IA.
- [Second.dev](https://www.second.dev/) — Una plataforma para añadir características a aplicaciones full-stack.
- [Factory](https://www.factory.ai/) — Agentes para la generación de código. En lista de espera.
- [sudocode](https://sudocode.ai/) — Un asistente de chat basado en web para generar proyectos, similar a Code Interpreter.
- [CodeFlash AI](https://www.codeflash.ai/) — Una herramienta CLI y CI para optimizar código Python usando IA.
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — Un agente de IA que escribe y corrige código por ti.
- [Fine](https://fine.dev/?ref=awesome) — Entorno de desarrollo de IA para automatizar el trabajo tedioso. Integra GitHub, Sentry, Linear. Obtén respuestas contextuales a preguntas. Planifica, diseña e implementa cambios. Automatiza CI/CD de auto-reparación.
- [Potpie](https://potpie.ai) — Agentes de IA de código abierto para tu base de código en minutos. Utiliza agentes preconstruidos para preguntas y respuestas, pruebas, depuración y diseño de sistemas, o crea tus propios agentes específicos.
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — Servidor MCP de configuración cero que unifica múltiples asistentes de codificación de IA a través de auto-descubrimiento inteligente e interfaz estandarizada.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Herramienta de codificación agéntica de Anthropic.
- [Open Agent](https://github.com/Th0rgal/openagent) — Plano de control autoalojado para Claude Code con espacios de trabajo en contenedores aislados y transmisión de misiones en tiempo real.
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — Marco multi-agente auto-iterativo y basado en especificaciones para Claude Code con agentes especializados coordinados (Python, Next.js, CI/CD, QA, UI Testing).
- [Leap.new](https://leap.new/) - Construye aplicaciones funcionales con servicios de backend reales, APIs y se despliega en tu nube.
- [Recurse ML](https://recurse.ml) - Encuentra errores en el código generado por IA.
- [Zenable](https://zenable.io/) — Guardarraíles de IA que aprenden los estándares de tu equipo y aseguran que los agentes de codificación los sigan, maximizando la velocidad y la calidad.
- [Trellis](https://github.com/mindfold-ai/Trellis) - Marco y kit de herramientas de IA todo en uno para Claude Code y Cursor. Gestiona tareas, especificaciones y pipelines multi-agente.

## Agentes de PR

- [Greptile](https://greptile.com/code-review-bot) — Bot de IA que revisa PRs en GitHub/Gitlab con el contexto completo de la base de código.
- [Macroscope](https://macroscope.com/code-review) - Revisión de código impulsada por IA para GitHub que utiliza ASTs para construir una representación basada en gráficos de tu base de código y extrae contexto de tus sistemas de gestión de problemas.
- [EntelligenceAI](https://entelligence.ai/pr) — Revisiones de código impulsadas por IA para Github y Gitlab que mejoran con el tiempo basándose en los comentarios del usuario.
- [Sweep](https://github.com/sweepai/sweep) — Desarrollador junior de IA: integración con GitHub para generar, probar y auto-revisar pull requests a partir de issues.
- [Codegen](https://www.codegen.com/) — Agente de PR basado en GPT-4 para bases de código empresariales.
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — Una herramienta de código abierto para revisar PRs. Funciona como acción de GitHub, CLI de Gitlab o localmente.
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — Herramienta de código abierto para revisiones de código automatizadas. Qodo era anteriormente conocido como Codium (no confundir con Codeium con "E").
- [Nova](https://www.trynova.ai/) — Bot de CI para añadir acciones como resúmenes y pruebas a nuevos PRs.
- [CodeRabbit](https://coderabbit.ai/) — CI personalizable para añadir resúmenes y sugerencias de código a los PRs.
- [SwePT](https://github.com/keerthanpg/SwePT) — Generador de PR de código abierto escrito en 150 líneas de código Python.
- [Duckie](https://duckie.ai/) — Un asistente de chat basado en web para modificar repositorios de GitHub.
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — Una integración de GitHub que añade texto explicativo a los PRs recién creados.
- [Goast](https://goast.ai/) — Una herramienta alojada que ingiere tus registros de errores y sugiere soluciones.
- [Corgea](https://corgea.com/) — Una integración de GitHub que encuentra y corrige código vulnerable.
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — Una integración de GitHub centrada en la generación de UI con soporte integrado para shadcn, lucide y gráficos nivo.
- [Pixee](https://pixee.ai) — Pixeebot encuentra problemas de seguridad y calidad de código en tu código y crea pull requests listos para fusionar con las soluciones recomendadas.
- [CodeAnt AI](https://www.codeant.ai/) — Crea automáticamente PRs para corregir problemas de código.
- [What The Diff](https://whatthediff.ai/) — Aplicación impulsada por IA que revisa el diff de las pull requests y escribe un comentario descriptivo sobre los cambios en lenguaje sencillo.
- [Trag](https://usetrag.com/) — Revisiones de código impulsadas por IA con instrucciones y patrones predefinidos.
- [CodeReviewBot](https://codereviewbot.ai/) — Revisiones de código impulsadas por IA para GitHub.
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — Revisor de PR impulsado por IA para GitHub, diseñado para identificar errores, problemas de seguridad y cuellos de botella de rendimiento.
- [Matter AI](https://matterai.dev) - Revisor de código de IA de código abierto para ayudar a los equipos de ingeniería a lanzar código con confianza.
- [Gito](https://github.com/Nayjest/Gito) - Revisor de código de IA que funciona con cualquier modelo de lenguaje, localmente o en GitHub Actions.
- [Baz](https://baz.co) - Revisor de código de IA adaptado a las directrices y convenciones de tu equipo. Personalizable, adaptable, receptivo e integrado con el resto de las herramientas de desarrollo para el contexto.

## Generadores de aplicaciones

- [Pico](https://picoapps.xyz) — Generador de microaplicaciones de extremo a extremo con despliegue instantáneo.
- [Co.dev](https://www.co.dev/) — Plataforma de desarrollo de aplicaciones impulsada por IA que ayuda a construir y desplegar aplicaciones full-stack.
- [SoftGen](https://softgen.ai/) — Plataforma de generación de software impulsada por IA para construir aplicaciones web.
- [LlamaCoder](https://llamacoder.together.ai/) — Modelo de generación de código de código abierto para construir aplicaciones utilizando LLMs de código abierto.
- [e2b_Fragments](https://fragments.e2b.dev/) — Plataforma para construir y desplegar aplicaciones impulsadas por IA con entornos aislados.
- [Bolt.new](https://bolt.new) — Agente de desarrollo web impulsado por IA que te permite solicitar, ejecutar, editar y desplegar aplicaciones full-stack directamente en el navegador utilizando WebContainers. Soporta paquetes npm, servidores Node.js y APIs de terceros.
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Versión de código abierto de Bolt.new que soporta múltiples proveedores de LLM incluyendo Groq, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek.
- [Srcbook](https://github.com/srcbookdev/srcbook) — Plataforma de desarrollo de aplicaciones centrada en TypeScript con un constructor de aplicaciones de IA y un cuaderno TypeScript.
- [Capacity](https://capacity.so) — Desarrollo de aplicaciones web full-stack impulsado por IA que convierte prompts en lenguaje natural en aplicaciones web completamente funcionales.
- [Lovable](https://lovable.dev/) — Plataforma de desarrollo de aplicaciones full-stack impulsada por IA que convierte descripciones o diseños en lenguaje natural en aplicaciones completamente funcionales con despliegue integrado e integración con GitHub.
- [Literally anything](https://literallyanything.io) — Generador de aplicaciones web HTML y JavaScript.
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — Genera una aplicación full-stack React/Node.js/Prisma/Wasp a partir de una breve descripción.
- [Make Real](https://makereal.tldraw.com/) — Lienzo en línea que se puede utilizar para generar aplicaciones HTML/JavaScript.
- [Marblism](https://marblism.com) — Genera un boilerplate SaaS a partir de un prompt.
- [Glowbom](https://glowbom.com/) — Genera aplicaciones con IA y exporta a múltiples plataformas.
- [Mage](https://usemage.ai/) — Genera aplicaciones web full-stack en Wasp, React, Node.js y Prisma.
- [ScrollHub](https://hub.scroll.pub/) — Genera y publica sitios web utilizando el lenguaje de programación Scroll.
- [Taskade Genesis](https://taskade.com/genesis) — Plataforma impulsada por IA para construir agentes de IA personalizados, flujos de trabajo y aplicaciones utilizando lenguaje natural. Soporte multi-modelo (GPT-4o, Claude, Gemini), servidor MCP de código abierto.

- [Berrry](https://berrry.app) — Generador de aplicaciones de Twitter que transforma publicaciones de redes sociales en aplicaciones web funcionales. Convierte tweets y contenido de Reddit en aplicaciones completas con subdominios únicos.
- [Blank Space](https://www.blankspace.build/) — Constructor de aplicaciones de IA de código abierto para crear aplicaciones web utilizando lenguaje natural. Alternativa autoalojable a v0, Lovable y Bolt.
- [Fastshot](https://fastshot.ai/) — Plataforma no-code impulsada por IA para construir y desplegar aplicaciones móviles.

## Generadores de UI

- [v0](https://v0.dev/) — Crea e itera nuevos componentes de UI en tu navegador.
- [Rendition Create ](https://www.renditioncreate.com/) — Crea e itera nuevos componentes de UI en tu navegador.
- [Rapidpages](https://github.com/rapidpages/rapidpages) — Generador de UI de código abierto.
- [Magic Patterns](https://www.magicpatterns.com/) — Prototipa tus ideas de producto. Sitio web generador de UI donde puedes solicitar, subir imágenes o importar inspiración de diseño con su [Extensión de Chrome](https://www.magicpatterns.com/extension). Puede exportar a Figma con un [plugin](https://www.figma.com/community/plugin/1304255855834420274). Soporta varios sistemas de componentes incluyendo Shadcn, ChakraUI y HTML + Tailwind.
- [Tempo ](https://www.tempolabs.ai/) — Editor WYSIWYG para interfaces React.
- [Kombai](https://kombai.com/) — Herramienta de IA para generar código frontend a partir de Figma.
- [CodeParrot](https://www.codeparrot.ai/) — Plugin de VS Code para generar código Frontend a partir de Figma. Reutiliza componentes, librerías y estándares de codificación existentes para generar código que se ajusta perfectamente a tu base de código existente. Todo sin necesidad de prompts.
- [Galileo AI](https://www.usegalileo.ai/) — Una plataforma de texto a UI. Lista de espera.
- [Uizard](https://uizard.io/) — Genera maquetas de múltiples pantallas a partir de prompts de texto y edítalas con un editor de arrastrar y soltar. Escanea capturas de pantalla de aplicaciones o wireframes dibujados a mano y transfórmalos en maquetas de aplicaciones editables.
- [Frontly](https://fronty.com/) — Convierte la imagen subida a código HTML CSS.
- [BoringUi](https://www.boringui.xyz/) — Crea una UI hermosa usando tus datos JSON. La UI generada está en HTML y Tailwind CSS con código que se puede copiar y la UI se puede compartir con cualquiera usando enlaces.
- [CSS Picker](https://csspicker.dev/) - Copia la UI de un diseño existente e itera con IA, soporta copiar CSS de un sitio web (mediante [CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)), imagen a código y texto a UI.

## Generadores de fragmentos de código

- [CodePal](https://codepal.ai/) — Una herramienta web para generar o refactorizar código rápidamente.
- [AI Code Convert](https://aicodeconvert.com/) — Una herramienta web para traducir código entre lenguajes de programación.
- [AI Code Playground](https://aicodeplayground.com/) — Una herramienta web para refactorizar y mejorar código.
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex utiliza GPT-3 de OpenAI para producir expresiones regulares a partir de lenguaje natural.
- [unpkg.ai](https://unpkg.ai/) — Servicio de generación de módulos ESM impulsado por IA de código abierto. Genera módulos JavaScript a través de URL para prototipado rápido.

## Documentación

- [Trelent](https://trelent.net/) — Una extensión de VS Code para generar docstrings. Utiliza modelos propietarios.
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT es una aplicación web gratuita basada en IA que convierte un esquema, una definición de infraestructura, un fragmento de código o una descripción en lenguaje natural en diagramas. La herramienta puede generar diagramas de flujo, diagramas de relación de entidades, diagramas de arquitectura en la nube y diagramas de secuencia.
- [DocuWriter.ai](https://www.docuwriter.ai/) — Aplicación web impulsada por IA para generar documentación automatizada de código y API a partir de tus archivos de código fuente.
- [README-AI](https://github.com/eli64s/readme-ai) — Generador automático de archivos README.md, impulsado por APIs de modelos de lenguaje grandes.
- [Supacodes](https://www.supacodes.com) — Una herramienta de IA que automatiza la escritura y actualización de la documentación del código en Github.
- [CodexAtlas](https://codedocumentation.app/) — Documentación automatizada de código y API utilizando los últimos modelos de IA.

## Observabilidad
- [TraceRoot AI](https://traceroot.ai/) - Una herramienta de observabilidad nativa de IA que utiliza agentes de IA para corregir automáticamente tus errores de producción.

## Plugins de OpenAI

- [ChatWithGit](https://gitsearch.sdan.io/) — Permite a ChatGPT buscar en GitHub y devolver enlaces a repositorios relevantes.
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — Ejemplo de código abierto de un plugin de ChatGPT que extrae contexto de un directorio de archivos.

## Búsqueda

- [Bloop](https://bloop.ai/) — Búsqueda de lenguaje natural para repositorios.
- [Buildt](https://www.buildt.ai/) — Búsqueda de lenguaje natural para repositorios. Lista de espera.
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — Una herramienta de búsqueda local que aprovecha las incrustaciones vectoriales para buscar semánticamente en tu base de código.
- [ContextMCP](https://contextmcp.ai) — Búsqueda semántica autoalojada en la documentación de varias fuentes para agentes de IA.

## Pruebas

- [Checksum AI](https://checksum.ai) — Agente de automatización de QA totalmente autónomo de extremo a extremo que genera pruebas Playwright listas para CI/CD directamente en el repositorio.
- [OctoMind](https://octomind.dev) — Mantenimiento automático y pruebas de extremo a extremo basadas en navegador generadas e integradas en Github Actions, Azure DevOps y más.
- [Traceloop](https://traceloop.com/) — Utiliza datos de rastreo de OpenTelemetry con IA generativa para mejorar la fiabilidad del sistema.
- [Carbonate](https://carbonate.dev/) — Pruebas de extremo a extremo utilizando lenguaje natural. Se integra en tu suite de pruebas existente (actualmente Jest, PHPUnit y unittest de Python).
- [Meticulous.ai](https://www.meticulous.ai/) — Pruebas de extremo a extremo generadas y mantenidas automáticamente: a medida que tu aplicación evoluciona, también lo hace tu suite de pruebas.
- [DiffBlue](https://www.diffblue.com/) — Pruebas unitarias generadas automáticamente para Java.
- [Qodo](https://www.qodo.ai/) — Generación de pruebas no triviales con soporte para los principales lenguajes de programación. Extensiones para VS Code y JetBrains. (anteriormente Codium).
- [DeepUnit](https://www.deepunit.ai/) — Casos de prueba bien pensados y generación de archivos de pruebas unitarias completos. Disponible como extensión interactiva de VS Code, paquete npm, CLI o pipeline de CI/CD.
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — Acelera la productividad del desarrollador y la seguridad del código al encontrar vulnerabilidades en el código y generar pruebas para ellas. De código abierto y disponible como CLI o pipeline de CI/CD.
- [KushoAI](https://kusho.ai/) — Agente de IA para pruebas de API que transforma tus colecciones de Postman, especificaciones OpenAPI, comandos curl, etc., en suites de pruebas exhaustivas que se conectan a tu pipeline de CI/CD.
- [Test Gru](https://gru.ai/home#test-gru) — Proporciona servicios de automatización de pruebas unitarias a nivel empresarial.

- [AgentsKB](https://agentskb.com) - Capa de conocimiento experto para asistentes de IA. Tu IA busca, nosotros investigamos. Esa es la diferencia.

## Evaluación

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — Suite de benchmarks para evaluar agentes de codificación. Compara configuraciones, rastrea métricas y realiza pruebas A/B con problemas reales de tus repositorios.

## Recursos

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — Tutoriales detallados curados para proyectos de herramientas de IA y desarrollo de código abierto.
- [Havoptic](https://havoptic.com/) — Seguimiento de línea de tiempo gratuito y de código abierto que muestra lanzamientos de herramientas de codificación de IA. Se actualiza automáticamente a diario. [Fuente](https://github.com/scotthavird/havoptic.com).

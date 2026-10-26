> **🌍 语言 / Languages:**
> [中文](./README.zh.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 Потрясающие инструменты для разработчиков на базе ИИ

Это тщательно подобранный список инструментов для разработчиков на базе ИИ. Эти инструменты используют ИИ для помощи разработчикам в таких задачах, как автодополнение кода, рефакторинг, отладка, документирование и многое другое.

- [IDEs](#ides)
- [Git Clients](#git-clients)
- [Assistants](#assistants)
  - [Web-based](#web-based)
  - [IDE extensions](#ide-extensions)
  - [Command-line](#command-line)
  - [Desktop](#desktop)
- [Shell assistants](#shell-assistants)
- [Agents](#agents)
- [PR agents](#pr-agents)
- [App generators](#app-generators)
- [UI generators](#ui-generators)
- [Snippet generators](#snippet-generators)
- [Documentation](#documentation)
- [OpenAI plugins](#openai-plugins)
- [Search](#search)
- [Testing](#testing)
- [Evaluation](#evaluation)
- [Resources](#resources)

## IDEs

- [Google Antigravity](https://antigravity.google/) — IDE, ориентированная на агентов, которая организует автономных ИИ-агентов для планирования, выполнения и проверки сложных задач кодирования с глубокой интеграцией с браузером.
- [Crystal](https://github.com/stravu/crystal) — Новый тип среды разработки для управления, инспектирования и тестирования параллельных сессий Claude Code.
- [Cursor](https://www.cursor.com/) — IDE с функциями чата, редактирования, генерации и отладки. Форк VSCodium, поэтому интерфейс похож на VS Code. Использует OpenAI.
- [PearAI](https://trypear.ai/) — Форк VS Code с открытым исходным кодом, с чатом и встроенной генерацией кода.
- [Melty](https://melty.sh/) — Форк VS Code с открытым исходным кодом, со встроенным чатом, предварительным просмотром изменений и возможностью написания коммитов с помощью ИИ. В настоящее время доступен только исходный код.
- [Replit](https://replit.com/) — Веб-IDE с облачными средами разработки, автодополнением кода, чатом, агентом разработки программного обеспечения и развертыванием.
- [Mutable](https://github.com/mutableai/monitors4codegen) — Веб-IDE, интегрированная с чат-ботом и GitHub.
- [CodeStory](https://codestory.ai/) — IDE с чатом, объяснениями кода, автоматически генерируемыми коммитами и сводками PR. Форк VSCodium.
- [UI Pilot](https://ui-pilot.com/) — Редактор кода на основе чата с ИИ, который создает формы с использованием Material UI, используя GPT-4.
- [GitWit](https://gitwit.dev/) — Веб-редактор для создания приложений ReactJS с ИИ.
- [Windsurf](https://windsurf.com) — IDE с функциями чата, редактирования, генерации и отладки. Форк VSCodium, поэтому интерфейс похож на VS Code. Ранее известный как Codeium.
- [Theia IDE](https://theia-ide.org/#theiaide) — Расширяемая IDE с открытым исходным кодом (веб и десктоп), предоставляющая функции на основе ИИ, такие как чат, автодополнение кода, помощь в терминале и пользовательские агенты, использующие произвольные LLM. Построена на [Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/), платформе, разработанной для создания пользовательских инструментов и IDE на основе ИИ.
- [OneCompiler](https://onecompiler.com/) — Бесплатный онлайн-компилятор на базе ИИ, поддерживающий более 70 языков, включая Java, Python, MySQL, C++ и HTML, для написания, запуска и обмена кодом.
- [trae](https://www.trae.ai/) — Trae — это адаптивная ИИ-IDE, которая преобразует вашу работу, сотрудничая с вами для ускорения процессов.
- [Zed](https://zed.dev/) - Высокопроизводительный многопользовательский редактор кода от создателей Atom и Tree-sitter.
- [Nimbalyst](https://nimbalyst.com) - Среда управления агентами для Claude Code и Codex. Интерактивное визуальное редактирование markdown, макетов, excalidraw, кода. Управление параллельными сессиями.

## Git Clients

- [GitBrain](https://gitbrain.dev/) — Git-клиент, упрощающий рабочий процесс Git. Разделяет изменения кода, генерирует сводки и сообщения коммитов для изменений кода. Использует OpenAI.
- [GitButler](https://gitbutler.com/) — Git-клиент для одновременной работы с ветками поверх вашего существующего рабочего процесса. По умолчанию использует OpenAI, может быть изменен на Perplexity для генерации сообщений коммитов в соответствии с соглашениями.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - Инструмент CLI, который использует ИИ для автоматической генерации высококачественных сообщений коммитов Git и описаний pull-запросов.

## Assistants

### Web-based

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — Ассистент, встроенный в [Replit](https://replit.com/) с чатом, проактивной отладкой и автодополнением. Использует OpenAI для чата и [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS) для автодополнения.
- [Unblocked](https://getunblocked.com/) — Расширяет исходный код соответствующими существующими знаниями в GitHub, Slack, Jira, Confluence и других. Получайте ответы через чат и контекст на уровне файлов IDE. Доступно в вебе, macOS, Slack, VSCode и JetBrains IDE.
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — Ассистент с чатом, рефакторингом и генерацией модульных тестов. Расширения для VS Code и IntelliJ. Также доступен как веб-приложение.
- [Magnet](https://www.magnet.run/) — Веб-чат-бот с репозиториями и задачами в качестве контекста.
- [Adrenaline](https://useadrenaline.com/) — Веб-чат-бот, использующий ИИ и AST для ответов на вопросы о вашей кодовой базе.
- [CodeSquire](https://codesquire.ai/) — Расширение Chrome, которое добавляет автодополнение в Google Colab, BigQuery и JupyterLab.
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — Ассистент с открытым исходным кодом со встроенным редактором и интерпретатором Python.
- [Onboard](https://www.getonboardai.com) — Общайтесь с ИИ о публичных и частных кодовых базах.
- [Code to Flow](https://codetoflow.com) — Визуализируйте, анализируйте и понимайте код с помощью интерактивных блок-схем.
- [Pieces](https://pieces.app/) — Локальный помощник, который помогает вам захватывать, обогащать и повторно использовать код, оптимизировать совместную работу и решать сложные проблемы благодаря контекстному пониманию вашего рабочего процесса.
- [Wren AI](https://getwren.ai/oss) — SQL AI Agent для получения результатов и аналитики быстрее, задавая вопросы без написания SQL, и это с открытым исходным кодом!
- [TEXT2SQL.AI](https://www.text2sql.ai/) — Конструктор SQL-запросов на базе ИИ. Переводите, объясняйте и исправляйте сложные SQL-запросы, используя простой английский язык.
- [SQLAI.ai](https://www.sqlai.ai/) — ИИ генерирует, исправляет, объясняет и оптимизирует SQL-запросы. Возможность добавить свою собственную схему базы данных и обучить ИИ понимать ее.
- [CodeWP](https://codewp.ai/) — ИИ-чат и инструменты кодирования, специально обученные для разработчиков WordPress. Генерация кода ИИ для фрагментов кода и плагинов в WordPress.
- [Gru.ai](https://www.gru.ai/) — ИИ-разработчик может помочь вам решать технические проблемы и справляться с ежедневными задачами кодирования, такими как создание алгоритмов, отладка проблем, тестирование решений, ответы на вопросы по программированию и т. д.

### IDE extensions

- [GitHub Copilot](https://github.com/features/copilot) — Расширение VS Code с чатом, генерацией текста pull-запросов и генерацией модульных тестов.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — Автономный агент кодирования для VS Code, который может создавать/редактировать файлы, выполнять команды и использовать браузер с разрешения пользователя. Поддерживает несколько поставщиков ИИ, включая OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure и GCP Vertex.
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — Ассистент с открытым исходным кодом с чатом, автодополнением, рефакторингом и тонкой настройкой под конкретную кодовую базу. Расширения для VS Code и JetBrains.
- [Continue](https://continue.dev/) — Расширение VS Code с чатом, рефакторингом и генерацией кода. Редактирует несколько файлов и выполняет команды от вашего имени.
- [Blackbox AI](https://www.useblackbox.io/) — Расширение VS Code с автодополнением и чатом, включая ссылки на онлайн-справочники по кодированию.
- [CodeGeeX](https://codegeex.cn/) — Ассистент с открытым исходным кодом на основе LLM CodeGeeX с чатом, автодополнением и рефакторингом. Расширения для 9 редакторов, включая VS Code и PyCharm.
- [Quack AI](https://www.quackai.com/) — Расширение VS Code для соблюдения рекомендаций по кодированию проекта.
- [Tabby](https://tabbyml.github.io/tabby/) — Ассистент автодополнения кода с открытым исходным кодом, размещаемый самостоятельно. Расширения для VS Code и Vim.
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — Ассистент автодополнения кода с открытым исходным кодом, размещаемый самостоятельно. Расширения для 15 редакторов, включая VS Code, IntelliJ, Neovim, Eclipse и PyCharm.
- [CodeMate](https://www.codemate.ai/) — Расширение VS Code для отладки и оптимизации кода.
- [AskCodi](https://www.askcodi.com/) — ИИ-помощник по кодированию с расширениями для VS Code, JetBrains и Sublime Text.
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Ассистент чата с открытым исходным кодом для боковой панели Visual Studio Code.
- [CodeComplete](https://codecomplete.ai/) — Корпоративный ассистент автодополнения, размещаемый самостоятельно.
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo — это ИИ-агент, который позволяет легко создавать и развертывать полнофункциональные приложения, с развертыванием Vercel в один клик и бесшовной интеграцией Supabase.
- [JetBrains AI](https://www.jetbrains.com/ai/) — ИИ-ассистент, доступный во всех IDE JetBrains.
- [aiXcoder](https://www.aixcoder.com/en/) — Локальный или облачный ассистент с расширениями для IntelliJ IDEA, CLion, GoLand, PyCharm, WebStorm, Visual Studio Code и Eclipse.
- [Sourcery](https://sourcery.ai/) — ИИ-ассистент и линтер со справочником из 160 лучших практик Python и более 40 лучших практик JS/TS. Расширения для VS Code, PyCharm, vim и Sublime.
- [Swimm](https://swimm.io) — Ассистент для контекстного понимания кода с использованием статического анализа и документации, генерируемой ИИ. VSCode, Jetbrains, IntelliJ, WebStorm, Rider, PhpStorm, Android Studio, PyCharm, PhPStorm.
- [Supermaven](https://supermaven.com/) — Расширение VS Code для автодополнения с контекстным окном на 300 000 токенов.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — ИИ-помощник по кодированию с расширениями для IDE, таких как VS Code и IntelliJ IDEA. Плагин Amazon Q Developer IDE имеет ряд агентов, которые также могут сканировать код для выявления и определения проблем безопасности (/review), написания документации (/doc), написания модульных тестов (/test) и помощи в обновлении до более поздних версий Java (/transform) (ранее известный как Amazon CodeWhisperer).
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot — это ИИ-помощник по кодированию, тесно интегрированный в Android Studio. Studio Bot может помочь Android-разработчикам генерировать код, находить соответствующие ресурсы, изучать лучшие практики и экономить время.
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z — это продукт для модернизации мейнфрейм-приложений на базе ИИ с генерацией кода. Функции включают обнаружение и анализ приложений, автоматический рефакторинг кода и преобразование COBOL в Java.
- [EasyCode](https://www.easycode.ai/) — Расширение VS Code с чатом GPT-4.
- [Kilo Code](https://kilocode.ai) - Ассистент кодирования с открытым исходным кодом для планирования, создания и исправления кода внутри VS Code.
- [FlyonUI MCP](https://flyonui.com/mcp) — Интегрируйте FlyonUI MCP - Tailwind AI Builder непосредственно в вашу IDE и создавайте потрясающие компоненты, блоки и страницы Tailwind CSS, вдохновленные FlyonUI.
- [Traycer](https://traycer.ai) - Plan-First Coding Assistant в VS Code.
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - Интегрируйте shadcn/studio MCP Server непосредственно в вашу любимую IDE и создавайте потрясающие компоненты, блоки и страницы shadcn/ui, вдохновленные shadcn/studio.

### Command-line

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - CLI, который предоставляет автодополнение команд, перевод команд с использованием генеративного ИИ для преобразования намерений в команды, а также полноценный агентский чат-интерфейс с управлением контекстом, который помогает писать код. Он работает со многими терминалами и оболочками, на MacOS, Linux и Windows (через wsl).
- [aloc](https://github.com/modern-tooling/aloc) — Современный счетчик строк кода, дополненный ИИ, построенный на Rust и Ratatui. Использует профили усилий ИИ для точной оценки проекта.
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — CLI-чат-бот с репозиторием в качестве контекста. Поддерживает OpenAI, а также локально работающие LLM через GPT4All.
- [gptcomet](https://github.com/belingud/gptcomet) — Инструмент CLI, который помогает генерировать сообщения коммитов и просматривать изменения. Поддерживает несколько провайдеров и языков.
- [poorcoder](https://github.com/vgrichina/poorcoder) — Набор Bash-скриптов для извлечения контекста кода, применения изменений из markdown и генерации сообщений коммитов ИИ при использовании веб-LLM.
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — Самокомпилирующийся инструмент, который преобразует стеки подсказок на основе markdown в код и тесты с использованием генерации LLM. Работает с любым LLM через OpenRouter, включая Claude, ChatGPT и Grok.
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - Преобразует естественный язык в исполняемые команды оболочки (например: `ai Tell me the free space on disk`).
- [promptext](https://github.com/1broseidon/promptext) — Интеллектуальный экстрактор контекста кода для ИИ-ассистентов с точным подсчетом токенов, приоритизацией релевантности и управлением бюджетом. Подготавливает оптимизированный контекст кода в пределах лимитов токенов LLM.
- [Baz CLI](https://github.com/baz-scm/baz-cli) - CLI для ИИ-помощи в проверке кода, с доступом к фактическому коду, diff и т. д.
- [AdaL](https://sylph.ai/) — Саморазвивающийся ИИ-агент для кодирования, который позволяет моделям сотрудничать (Claude, GPT, Gemini). Работает локально, изучает шаблоны вашей кодовой базы.
- [Tokscale](https://github.com/junhoyeo/tokscale) — Инструмент CLI для отслеживания использования токенов ИИ-агентами кодирования (OpenCode, Claude Code, OpenClaw, Codex, Gemini CLI, Cursor IDE, AmpCode, Factory Droid) с глобальной таблицей лидеров и 2D/3D графиками вклада.
- [vsync](https://github.com/nicepkg/vsync) — Инструмент CLI, который синхронизирует Skills, MCP-серверы, агентов и команды между Claude Code, Cursor, OpenCode и Codex с автоматическим преобразованием форматов (JSON ↔ TOML ↔ JSONC).
- [Arctic](https://github.com/arctic-cli/interface): Терминальный TUI, который объединяет несколько планов и API ИИ-кодирования со встроенной видимостью использования и квот.

### Desktop

- [Memex](https://memex.tech/) — Создавайте что угодно в любом стеке, используя только естественный язык, на вашем рабочем столе.
- [Pieces](https://pieces.app/) — Настольное приложение и расширение для браузера с поддержкой ИИ, разработанное для помощи разработчикам в повышении производительности.

## Shell assistants

- [AskCommand](https://www.askcommand.cppexpert.online/) — Веб-инструмент для автоматической генерации команд Unix из текста с использованием ИИ.
- [Butterfish](https://butterfi.sh) — Инструмент CLI, который встраивает ChatGPT в вашу оболочку для легкого доступа. Включает простые агентские возможности.
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — Высоко настраиваемый CLI-ассистент для генерации команд оболочки и получения их объяснений.
- [GitFluence](https://www.gitfluence.com/) — Веб-генератор команд Git для автоматической генерации команд Git для терминала или CLI из текстового описания, использующий решение на основе ИИ для предложения наиболее релевантных команд Git.
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - Инструмент CLI, который добавляет ИИ-подсказки командной строки непосредственно в ваш терминал; просто наберите <TAB><TAB>, чтобы получить лучшие предложения.
- [code-collator](https://github.com/tawandakembo/code-collator) — Инструмент CLI, который создает один файл markdown, описывающий всю вашу кодовую базу для языковых моделей. Полезно для ИИ-помощи в кодировании через веб-интерфейс Claude/ChatGPT, а не через API.
- [Warp](https://www.warp.dev/) - Warp объединяет ИИ и командные знания в едином, быстром и интуитивно понятном терминале.
- [TmuxAI](https://tmuxai.dev/) - ИИ-помощник для терминала, неинтрузивный.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - Управление шаблонами/фрагментами команд с динамическими дополнениями и интеграцией ИИ.

## Agents

- [Smol Developer](https://github.com/smol-ai/developer) — CLI-агент, который генерирует репозиторий из подсказки. Использует OpenAI и Anthropic.
- [Aider](https://github.com/paul-gauthier/aider) — CLI-ассистент и агент, который генерирует изменения и коммиты в репозитории. Использует OpenAI.
- [Blinky](https://github.com/seahyinghang8/blinky) — Агент отладки для VS Code, который помогает выявлять и исправлять ошибки бэкенда, вдохновленный SWE-agent.
- [Mentat](https://www.mentat.ai/) — CLI-ассистент и агент, который вносит изменения в репозитории.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — CLI-агент, который генерирует репозиторий из подсказки и задает уточняющие вопросы.
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — CLI-агент, который преобразует полнофункциональное приложение из одного языка или фреймворка в другой. Использует контекст GPT-4 32k.
- [Grit](https://app.grit.io) — Агент, интегрированный с GitHub, для автоматизации задач обслуживания и других работ по разработке.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Автоматический генератор приложений Gen-AI с мощью Llama 2.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT: Решение для автоматизации разработки программного обеспечения на основе ИИ.
- [Second.dev](https://www.second.dev/) — Платформа для добавления функций в полнофункциональные приложения.
- [Factory](https://www.factory.ai/) — Агенты для генерации кода. В списке ожидания.
- [sudocode](https://sudocode.ai/) — Веб-чат-ассистент для генерации проектов, похожий на Code Interpreter.
- [CodeFlash AI](https://www.codeflash.ai/) — Инструмент CLI и CI для оптимизации кода Python с использованием ИИ.
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — ИИ-агент, который пишет и исправляет код за вас.
- [Fine](https://fine.dev/?ref=awesome) — Среда разработки ИИ для автоматизации рутинной работы. Интеграция с GitHub, Sentry, Linear. Получение контекстно-зависимых ответов на вопросы. Планирование, проектирование и реализация изменений. Автоматизация самовосстанавливающегося CI/CD.
- [Potpie](https://potpie.ai) — Агенты ИИ с открытым исходным кодом для вашей кодовой базы за считанные минуты. Используйте готовые агенты для вопросов и ответов, тестирования, отладки и системного проектирования или создавайте свои собственные специализированные агенты.
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — MCP-сервер с нулевой конфигурацией, который объединяет несколько ИИ-помощников по кодированию посредством интеллектуального автообнаружения и стандартизированного интерфейса.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Агентский инструмент кодирования от Anthropic.
- [Open Agent](https://github.com/Th0rgal/openagent) — Самостоятельно размещаемая панель управления для Claude Code с изолированными контейнерными рабочими пространствами и потоковой передачей миссий в реальном времени.
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — Управляемая спецификациями, самоитеративная многоагентная среда для Claude Code с координированными специализированными агентами (Python, Next.js, CI/CD, QA, UI Testing).
- [Leap.new](https://leap.new/) - Создает функциональные приложения с реальными бэкенд-сервисами, API и развертывает их в вашем облаке.
- [Recurse ML](https://recurse.ml) - Находит ошибки в коде, сгенерированном ИИ.
- [Zenable](https://zenable.io/) — ИИ-ограничители, которые изучают стандарты вашей команды и обеспечивают их соблюдение агентами кодирования, максимизируя скорость и качество.
- [Trellis](https://github.com/mindfold-ai/Trellis) - Универсальный ИИ-фреймворк и набор инструментов для Claude Code и Cursor. Управляет задачами, спецификациями и многоагентными конвейерами.

## PR agents

- [Greptile](https://greptile.com/code-review-bot) — ИИ-бот, который проверяет PR в GitHub/Gitlab с полным контекстом кодовой базы.
- [Macroscope](https://macroscope.com/code-review) - ИИ-анализ кода для GitHub, который использует AST для построения графового представления вашей кодовой базы и извлекает контекст из ваших систем управления задачами.
- [EntelligenceAI](https://entelligence.ai/pr) — Проверка кода на основе ИИ для Github и Gitlab, которая со временем улучшается на основе комментариев пользователей.
- [Sweep](https://github.com/sweepai/sweep) — ИИ-младший разработчик: интеграция с GitHub для генерации, тестирования и самопроверки pull-запросов из задач.
- [Codegen](https://www.codegen.com/) — Агент PR на основе GPT-4 для корпоративных кодовых баз.
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — Инструмент с открытым исходным кодом для проверки PR. Работает как действие GitHub, CLI Gitlab или локально.
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — Инструмент с открытым исходным кодом для автоматизированной проверки кода. Qodo ранее был известен как Codium (не путать с Codeium с "E").
- [Nova](https://www.trynova.ai/) — CI-бот для добавления действий, таких как сводки и тесты, к новым PR.
- [CodeRabbit](https://coderabbit.ai/) — Настраиваемый CI для добавления сводок и предложений по коду к PR.
- [SwePT](https://github.com/keerthanpg/SwePT) — Генератор PR с открытым исходным кодом, написанный на 150 строках кода Python.
- [Duckie](https://duckie.ai/) — Веб-чат-ассистент для изменения репозиториев GitHub.
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — Интеграция с GitHub, которая добавляет пояснительный текст к вновь созданным PR.
- [Goast](https://goast.ai/) — Хостинг-инструмент, который анализирует ваши журналы ошибок и предлагает исправления.
- [Corgea](https://corgea.com/) — Интеграция с GitHub, которая находит и исправляет уязвимый код.
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — Интеграция с GitHub, ориентированная на генерацию пользовательского интерфейса со встроенной поддержкой shadcn, lucide и nivo charts.
- [Pixee](https://pixee.ai) — Pixeebot находит проблемы безопасности и качества кода в вашем коде и создает готовые к слиянию pull-запросы с рекомендуемыми исправлениями.
- [CodeAnt AI](https://www.codeant.ai/) — Автоматически создает PR для исправления проблем с кодом.
- [What The Diff](https://whatthediff.ai/) — Приложение на базе ИИ, которое просматривает diff pull-запросов и пишет описательный комментарий об изменениях на простом английском языке.
- [Trag](https://usetrag.com/) — Проверка кода на основе ИИ с предопределенными инструкциями и шаблонами.
- [CodeReviewBot](https://codereviewbot.ai/) — Проверка кода на основе ИИ для GitHub.
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — ИИ-рецензент PR для GitHub, разработанный для выявления ошибок, проблем безопасности и узких мест в производительности.
- [Matter AI](https://matterai.dev) - Рецензент кода с открытым исходным кодом на базе ИИ, который помогает инженерным командам выпускать код с уверенностью.
- [Gito](https://github.com/Nayjest/Gito) - ИИ-рецензент кода, который работает с любой языковой моделью, локально или в GitHub Actions.
- [Baz](https://baz.co) - ИИ-рецензент кода, адаптированный к рекомендациям и соглашениям вашей команды. Настраиваемый, адаптируемый, отзывчивый и интегрированный с остальными инструментами разработчика для контекста.

## App generators

- [Pico](https://picoapps.xyz) — Сквозной генератор микроприложений с мгновенным развертыванием.
- [Co.dev](https://www.co.dev/) — Платформа для разработки приложений на базе ИИ, которая помогает создавать и развертывать полнофункциональные приложения.
- [SoftGen](https://softgen.ai/) — Платформа для генерации программного обеспечения на базе ИИ для создания веб-приложений.
- [LlamaCoder](https://llamacoder.together.ai/) — Модель генерации кода с открытым исходным кодом для создания приложений с использованием Opensource LLMs.
- [e2b_Fragments](https://fragments.e2b.dev/) — Платформа для создания и развертывания приложений на базе ИИ с изолированными средами.
- [Bolt.new](https://bolt.new) — Агент веб-разработки на базе ИИ, который позволяет запрашивать, запускать, редактировать и развертывать полнофункциональные приложения непосредственно в браузере с использованием WebContainers. Поддерживает пакеты npm, серверы Node.js и сторонние API.
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Версия Bolt.new с открытым исходным кодом, которая поддерживает несколько провайдеров LLM, включая Groq, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek.
- [Srcbook](https://github.com/srcbookdev/srcbook) — Платформа для разработки приложений, ориентированная на TypeScript, с конструктором приложений на базе ИИ и блокнотом TypeScript.
- [Capacity](https://capacity.so) — Разработка полнофункциональных веб-приложений на базе ИИ, которая превращает подсказки на естественном языке в полностью функциональные веб-приложения.
- [Lovable](https://lovable.dev/) — Платформа для разработки полнофункциональных приложений на базе ИИ, которая преобразует описания или дизайны на естественном языке в полностью функциональные приложения со встроенным развертыванием и интеграцией с GitHub.
- [Literally anything](https://literallyanything.io) — Генератор веб-приложений HTML и JavaScript.
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — Генерирует полнофункциональное приложение React/Node.js/Prisma/Wasp из короткого описания.
- [Make Real](https://makereal.tldraw.com/) — Онлайн-холст, который можно использовать для генерации приложений HTML/JavaScript.
- [Marblism](https://marblism.com) — Генерирует шаблон SaaS из подсказки.
- [Glowbom](https://glowbom.com/) — Генерирует приложения с помощью ИИ и экспортирует их на несколько платформ.
- [Mage](https://usemage.ai/) — Генерирует полнофункциональные веб-приложения на Wasp, React, Node.js и Prisma.
- [ScrollHub](https://hub.scroll.pub/) — Генерирует и публикует веб-сайты с использованием языка программирования Scroll.
- [Taskade Genesis](https://taskade.com/genesis) — Платформа на базе ИИ для создания пользовательских ИИ-агентов, рабочих процессов и приложений с использованием естественного языка. Поддержка нескольких моделей (GPT-4o, Claude, Gemini), MCP-сервер с открытым исходным кодом.

- [Berrry](https://berrry.app) — Генератор приложений Twitter, который преобразует сообщения из социальных сетей в функциональные веб-приложения. Превращает твиты и контент Reddit в полноценные приложения с уникальными поддоменами.
- [Blank Space](https://www.blankspace.build/) — Конструктор приложений с открытым исходным кодом на базе ИИ для создания веб-приложений с использованием естественного языка. Самостоятельно размещаемая альтернатива v0, Lovable и Bolt.
- [Fastshot](https://fastshot.ai/) — Платформа без кода на базе ИИ для создания и развертывания мобильных приложений.

## UI generators

- [v0](https://v0.dev/) — Создавайте и итерируйте новые компоненты пользовательского интерфейса в браузере.
- [Rendition Create ](https://www.renditioncreate.com/) — Создавайте и итерируйте новые компоненты пользовательского интерфейса в браузере.
- [Rapidpages](https://github.com/rapidpages/rapidpages) — Генератор пользовательского интерфейса с открытым исходным кодом.
- [Magic Patterns](https://www.magicpatterns.com/) — Прототипируйте свои продуктовые идеи. Веб-сайт генератора пользовательского интерфейса, где вы можете вводить подсказки, загружать изображения или импортировать вдохновение для дизайна с помощью их [расширения Chrome](https://www.magicpatterns.com/extension). Может экспортировать в Figma с помощью [плагина](https://www.figma.com/community/plugin/1304255855834420274). Поддерживает ряд систем компонентов, включая Shadcn, ChakraUI и HTML + Tailwind.
- [Tempo ](https://www.tempolabs.ai/) — WYSIWYG-редактор для интерфейсов React.
- [Kombai](https://kombai.com/) — Инструмент ИИ для генерации фронтенд-кода из Figma.
- [CodeParrot](https://www.codeparrot.ai/) — Плагин VS Code для генерации фронтенд-кода из Figma. Повторно использует существующие компоненты, библиотеки и стандарты кодирования для генерации кода, который идеально вписывается в вашу существующую кодовую базу. Все это без каких-либо подсказок.
- [Galileo AI](https://www.usegalileo.ai/) — Платформа "текст в UI". Список ожидания.
- [Uizard](https://uizard.io/) — Генерируйте многоэкранные макеты из текстовых подсказок и редактируйте их с помощью редактора drag-and-drop. Сканируйте скриншоты приложений или нарисованные от руки каркасы и преобразуйте их в редактируемые макеты приложений.
- [Frontly](https://fronty.com/) — Преобразует загруженное изображение в код HTML CSS.
- [BoringUi](https://www.boringui.xyz/) — Создавайте красивые пользовательские интерфейсы, используя ваши данные JSON. Сгенерированный пользовательский интерфейс представлен в HTML и Tailwind CSS с кодом, который можно скопировать, а пользовательский интерфейс можно поделиться с кем угодно с помощью ссылок.
- [CSS Picker](https://csspicker.dev/) - Копируйте UI из существующего дизайна и итерируйте с помощью ИИ, поддерживается копирование CSS с веб-сайта (с помощью [CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)), преобразование изображения в код и текста в UI.

## Snippet generators

- [CodePal](https://codepal.ai/) — Веб-инструмент для быстрой генерации или рефакторинга кода.
- [AI Code Convert](https://aicodeconvert.com/) — Веб-инструмент для перевода кода между языками программирования.
- [AI Code Playground](https://aicodeplayground.com/) — Веб-инструмент для рефакторинга и улучшения кода.
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex использует GPT-3 от OpenAI для создания регулярных выражений из простого английского языка.
- [unpkg.ai](https://unpkg.ai/) — Сервис генерации модулей ESM на базе ИИ с открытым исходным кодом. Генерируйте модули JavaScript по URL для быстрого прототипирования.

## Documentation

- [Trelent](https://trelent.net/) — Расширение VS Code для генерации docstrings. Использует проприетарные модели.
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT — это бесплатное веб-приложение на основе ИИ, которое преобразует схему, определение инфраструктуры, фрагмент кода или описание на простом языке в диаграммы. Инструмент может генерировать блок-схемы, диаграммы сущность-связь, диаграммы облачной архитектуры и диаграммы последовательности.
- [DocuWriter.ai](https://www.docuwriter.ai/) — Веб-приложение на базе ИИ для генерации автоматической документации по коду и API из ваших файлов исходного кода.
- [README-AI](https://github.com/eli64s/readme-ai) — Автоматический генератор файла README.md, работающий на API больших языковых моделей.
- [Supacodes](https://www.supacodes.com) — Инструмент ИИ, который автоматизирует написание и обновление документации по коду в Github.
- [CodexAtlas](https://codedocumentation.app/) — Автоматическая документация кода и API с использованием новейших моделей ИИ.

## Observability

- [TraceRoot AI](https://traceroot.ai/) - Нативный инструмент наблюдаемости на базе ИИ, который использует ИИ-агентов для автоматического исправления ваших производственных ошибок.

## OpenAI plugins

- [ChatWithGit](https://gitsearch.sdan.io/) — Позволяет ChatGPT искать в GitHub и возвращать ссылки на соответствующие репозитории.
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — Пример плагина ChatGPT с открытым исходным кодом, который извлекает контекст из каталога файлов.

## Search

- [Bloop](https://bloop.ai/) — Поиск по репозиториям на естественном языке.
- [Buildt](https://www.buildt.ai/) — Поиск по репозиториям на естественном языке. Список ожидания.
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — Локальный инструмент поиска, использующий векторные вложения для семантического поиска по вашей кодовой базе.
- [ContextMCP](https://contextmcp.ai) — Самостоятельно размещаемый семантический поиск по документации из различных источников для ИИ-агентов.

## Testing

- [agent-qa](https://vostride.com) — Агент vostride для тестирования веб-приложений, Android и iOS на естественном языке, с постоянной памятью, проверенными улучшениями и инструментами CLI и MCP.
- [Checksum AI](https://checksum.ai) — Полностью автономный агент QA Automation, который генерирует готовые к CI/CD тесты Playwright непосредственно в репозиторий.
- [OctoMind](https://octomind.dev) — Автоматическое обслуживание и генерируемые браузерные сквозные тесты, интегрированные в Github Actions, Azure DevOps и другие.
- [Traceloop](https://traceloop.com/) — Использует данные трассировки OpenTelemetry с генеративным ИИ для повышения надежности системы.
- [Carbonate](https://carbonate.dev/) — Сквозное тестирование с использованием естественного языка. Интегрируется в ваш существующий набор тестов (в настоящее время Jest, PHPUnit и Python's unittest).
- [Meticulous.ai](https://www.meticulous.ai/) — Автоматически генерируемые, автоматически поддерживаемые сквозные тесты: по мере развития вашего приложения развивается и ваш набор тестов.
- [DiffBlue](https://www.diffblue.com/) — Автоматически генерируемые модульные тесты для Java.
- [Qodo](https://www.qodo.ai/) — Генерация нетривиальных тестов с поддержкой основных языков программирования. Расширения для VS Code и JetBrains. (ранее Codium)
- [DeepUnit](https://www.deepunit.ai/) — Продуманные тестовые случаи и генерация полных файлов модульных тестов. Доступно как интерактивное расширение VS Code, пакет npm, CLI или конвейер CI/CD.
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — Ускоряет производительность разработчиков и безопасность кода, находя уязвимости в коде и генерируя для них тесты. Открытый исходный код и доступно как CLI или конвейер CI/CD.
- [KushoAI](https://kusho.ai/) — ИИ-агент для тестирования API, который преобразует ваши коллекции Postman, спецификации OpenAPI, команды curl и т. д. в исчерпывающие наборы тестов, которые подключаются к вашему конвейеру CI/CD.
- [Test Gru](https://gru.ai/home#test-gru) — Предоставляет услуги автоматизации модульных тестов корпоративного уровня.

- [AgentsKB](https://agentskb.com) - Экспертный слой знаний для ИИ-ассистентов. Ваш ИИ ищет, мы исследуем. В этом разница.

## Evaluation

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — Набор бенчмарков для оценки агентов кодирования. Сравнивайте конфигурации, отслеживайте метрики и проводите A/B-тестирование с реальными проблемами из ваших репозиториев.

## Resources

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — Кураторские подробные руководства по проектам ИИ с открытым исходным кодом и инструментам для разработчиков.
- [Havoptic](https://havoptic.com/) — Бесплатное, открытое отслеживание временной шкалы выпусков инструментов ИИ для кодирования. Ежедневно обновляется автоматически. [Source](https://github.com/scotthavird/havoptic.com)

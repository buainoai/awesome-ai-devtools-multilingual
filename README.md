# ⚡️🧑‍💻 Awesome AI 开发者工具 (多语言版)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-欢迎-brightgreen.svg)](http://makeapullrequest.com)
[![多语言](https://img.shields.io/badge/Languages-9-blue.svg)](#-其他语言)

> **🌍 其他语言:**
> [English](./i18n/README.en.md) | [日本語](./i18n/README.ja.md) | [한국어](./i18n/README.ko.md) | [Français](./i18n/README.fr.md) | [Deutsch](./i18n/README.de.md) | [Español](./i18n/README.es.md) | [Português](./i18n/README.pt.md) | [Русский](./i18n/README.ru.md)

一份全面的、多语言的 **AI 驱动开发者工具**精选列表，收录了超过 **216+** 款工具，涵盖 IDE、编程助手、AI 智能体、代码审查机器人、应用生成器、测试工具等。项目提供 **9 种语言版本**，旨在服务全球开发者社区。

> 本项目受 [jamesmurdza/awesome-ai-devtools](https://github.com/jamesmurdza/awesome-ai-devtools) 启发并基于其内容构建。我们通过增加多语言支持和 SEO 优化，希望帮助全球开发者发现优秀的 AI 工具。

---

- [IDEs](#ides)
- [Git 客户端](#git-客户端)
- [助手](#助手)
  - [Web端](#web端)
  - [IDE 扩展](#ide-扩展)
  - [命令行](#命令行)
  - [桌面](#桌面)
- [Shell 助手](#shell-助手)
- [代理](#代理)
- [PR 代理](#pr-代理)
- [应用生成器](#应用生成器)
- [UI 生成器](#ui-生成器)
- [代码片段生成器](#代码片段生成器)
- [文档](#文档)
- [可观测性](#可观测性)
- [OpenAI 插件](#openai-插件)
- [搜索](#搜索)
- [测试](#测试)
- [评估](#评估)
- [资源](#资源)

## IDEs

- [Google Antigravity](https://antigravity.google/) — 一个以代理为先的IDE，它协调自主AI代理，通过深度浏览器集成来规划、执行和验证复杂的编码任务。
- [Crystal](https://github.com/stravu/crystal) — 一种新型开发环境，用于管理、检查和测试并行 Claude Code 会话。
- [Cursor](https://www.cursor.com/) — 一个具有聊天、编辑、生成和调试功能的IDE。从VSCodium分支而来，因此界面类似于VS Code。使用OpenAI。
- [PearAI](https://trypear.ai/) — VS Code 的开源分支，具有聊天和内联代码生成功能。
- [Melty](https://melty.sh/) — VS Code 的开源分支，内置聊天、变更预览以及使用AI编写提交的能力。目前仅提供源代码。
- [Replit](https://replit.com/) — 基于Web的IDE，具有云开发环境、代码补全、聊天、软件开发代理和部署功能。
- [Mutable](https://github.com/mutableai/monitors4codegen) — 基于Web的IDE，集成了聊天机器人和GitHub。
- [CodeStory](https://codestory.ai/) — 一个具有聊天、代码解释、自动生成提交和PR摘要功能的IDE。从VSCodium分支而来。
- [UI Pilot](https://ui-pilot.com/) — 基于聊天的AI代码编辑器，使用GPT-4创建Material UI表单。
- [GitWit](https://gitwit.dev/) — 基于Web的编辑器，用于使用AI构建ReactJS应用程序。
- [Windsurf](https://windsurf.com) — 一个具有聊天、编辑、生成和调试功能的IDE。从VSCodium分支而来，因此界面类似于VS Code。以前称为Codeium。
- [Theia IDE](https://theia-ide.org/#theiaide) — 一个可扩展的开源IDE（Web和桌面），提供AI驱动的功能，如聊天、代码补全、终端辅助和使用任意LLM的自定义代理。基于[Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/)构建，这是一个旨在创建自定义AI驱动工具和IDE的平台。
- [OneCompiler](https://onecompiler.com/) — 一个免费的AI驱动在线编译器，支持70多种语言，包括Java、Python、MySQL、C++和HTML，用于编写、运行和分享代码。
- [trae](https://www.trae.ai/) — Trae是一个自适应AI IDE，它改变了您的工作方式，与您协作以更快地运行。
- [Zed](https://zed.dev/) - 由Atom和Tree-sitter的创建者开发的高性能、多人代码编辑器。
- [Nimbalyst](https://nimbalyst.com) - 用于Claude Code和Codex的代理管理环境。Markdown、模型、Excalidraw、代码的交互式可视化编辑。并行会话管理。

## Git 客户端

- [GitBrain](https://gitbrain.dev/) — 简化Git工作流程的Git客户端。分割代码更改，为代码更改生成摘要和提交消息。使用OpenAI。
- [GitButler](https://gitbutler.com/) — 在现有工作流程之上同时处理多个分支的Git客户端。默认使用OpenAI，可以更改为Perplexity来生成常规提交消息。
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - 使用AI自动生成高质量Git提交消息和拉取请求描述的CLI工具。

## 助手

### Web端

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — 内置于[Replit](https://replit.com/)的助手，具有聊天、主动调试和自动补全功能。聊天使用OpenAI，自动补全使用[replit-code-v1-3b](https://huggingface.co/replit/replit-v1-3b) (OS)。
- [Unblocked](https://getunblocked.com/) — 使用GitHub、Slack、Jira、Confluence等现有知识增强源代码。通过聊天和IDE文件级上下文获取答案。可在Web、macOS、Slack、VSCode和JetBrains IDE上使用。
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — 具有聊天、重构和单元测试生成功能的助手。VS Code和IntelliJ的扩展。也可用作Web应用程序。
- [Magnet](https://www.magnet.run/) — 基于Web的聊天机器人，以仓库和问题作为上下文。
- [Adrenaline](https://useadrenaline.com/) — 基于Web的聊天机器人，使用AI和AST回答有关代码库的问题。
- [CodeSquire](https://codesquire.ai/) — Chrome扩展，为Google Colab、BigQuery和JupyterLab添加自动补全功能。
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — 开源助手，内置Python编辑器和解释器。
- [Onboard](https://www.getonboardai.com) — 与AI就公共和私有代码库进行聊天。
- [Code to Flow](https://codetoflow.com) — 使用交互式流程图可视化、分析和理解代码。
- [Pieces](https://pieces.app/) — 一个设备上的副驾驶，通过对您的工作流程的上下文理解，帮助您捕获、丰富和重用代码，简化协作，并解决复杂问题。
- [Wren AI](https://getwren.ai/oss) — SQL AI代理，通过提问而无需编写SQL，更快地获取结果和洞察，并且它是开源的！
- [TEXT2SQL.AI](https://www.text2sql.ai/) — AI驱动的SQL查询构建器。使用纯英语翻译、解释和修复复杂的SQL查询。
- [SQLAI.ai](https://www.sqlai.ai/) — AI生成、修复、解释和优化SQL查询。能够添加您自己的数据库模式并训练AI理解它。
- [CodeWP](https://codewp.ai/) — 专门为WordPress开发者训练的AI聊天和编码工具。用于WordPress中代码片段和插件的AI代码生成。
- [Gru.ai](https://www.gru.ai/) — 一个AI开发者可以帮助您解决技术问题并处理日常编码任务，例如构建算法、调试问题、测试解决方案、回答编程问题等。

### IDE 扩展

- [GitHub Copilot](https://github.com/features/copilot) — 一个VS Code扩展，具有聊天、拉取请求文本生成和单元测试生成功能。
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — VS Code的自主编码代理，可以在用户许可下创建/编辑文件、执行命令和使用浏览器。支持多种AI提供商，包括OpenRouter、Anthropic、OpenAI、Google Gemini、AWS Bedrock、Azure和GCP Vertex。
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — 开源助手，具有聊天、补全、重构和代码库特定微调功能。VS Code和JetBrains的扩展。
- [Continue](https://continue.dev/) — VS Code扩展，具有聊天、重构和代码生成功能。代表您编辑多个文件并运行命令。
- [Blackbox AI](https://www.useblackbox.io/) — VS Code扩展，具有自动补全和聊天功能，包括指向在线编码参考的链接。
- [CodeGeeX](https://codegeex.cn/) — 基于CodeGeeX LLM的开源助手，具有聊天、补全和重构功能。支持9个编辑器，包括VS Code和PyCharm。
- [Quack AI](https://www.quackai.com/) — 遵守项目编码规范的VS Code扩展。
- [Tabby](https://tabbyml.github.io/tabby/) — 开源、自托管的代码补全助手。VS Code和Vim的扩展。
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — 开源、自托管的代码补全助手。支持15个编辑器，包括VS Code、IntelliJ、Neovim、Eclipse和PyCharm。
- [CodeMate](https://www.codemate.ai/) — 用于调试和优化代码的VS Code扩展。
- [AskCodi](https://www.askcodi.com/) — AI编码助手，具有VS Code、JetBrains和Sublime Text的扩展。
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Visual Studio Code侧边栏的开源聊天助手。
- [CodeComplete](https://codecomplete.ai/) — 自托管的企业补全助手。
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo是一个AI代理，让您轻松构建和部署全栈应用程序，一键Vercel部署和无缝Supabase集成。
- [JetBrains AI](https://www.jetbrains.com/ai/) — 所有JetBrains IDE中都可用的AI助手。
- [aiXcoder](https://www.aixcoder.com/en/) — 本地或基于云的助手，具有IntelliJ IDEA、CLion、GoLand、PyCharm、WebStorm、Visual Studio Code和Eclipse的扩展。
- [Sourcery](https://sourcery.ai/) — AI助手和linter，包含160条Python最佳实践和40多条JS/TS最佳实践。VS Code、PyCharm、vim和Sublime的扩展。
- [Swimm](https://swimm.io) — 使用静态分析和AI生成文档进行上下文代码理解的助手。VSCode、Jetbrains、IntelliJ、WebStorm、Rider、PhpStorm、Android Studio、PyCharm、PhPStorm。
- [Supermaven](https://supermaven.com/) — 具有300,000个token上下文窗口的VS Code自动补全扩展。
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — AI编码助手，具有VS Code和IntelliJ IDEA等IDE的扩展。Amazon Q Developer IDE插件有许多代理，还可以扫描代码以突出显示和定义安全问题（/review）、编写文档（/doc）、编写单元测试（/test），并帮助您升级到更高版本的Java（/transform）（以前称为Amazon CodeWhisperer）。
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot是一个AI驱动的编码助手，与Android Studio紧密集成。Studio Bot可以帮助Android开发者生成代码、查找相关资源、学习最佳实践并节省时间。
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z是一款AI驱动的大型机应用程序现代化产品，具有代码生成功能。功能包括应用程序发现和分析、自动化代码重构和COBOL到Java的转换。
- [EasyCode](https://www.easycode.ai/) — 带有GPT-4聊天的VS Code扩展。
- [Kilo Code](https://kilocode.ai) - 用于在VS Code中规划、构建和修复代码的开源AI编码助手。
- [FlyonUI MCP](https://flyonui.com/mcp) — 将FlyonUI MCP - Tailwind AI Builder直接集成到您的IDE中，并根据FlyonUI的灵感制作出令人惊叹的Tailwind CSS组件、块和页面。
- [Traycer](https://traycer.ai) - VS Code中的计划优先编码助手。
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - 将shadcn/studio MCP Server直接集成到您喜欢的IDE中，并根据shadcn/studio的灵感制作出令人惊叹的shadcn/ui组件、块和页面。

### 命令行

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - CLI提供命令补全、使用生成式AI将意图转换为命令的命令翻译，以及一个具有上下文管理的完整代理聊天界面，帮助您编写代码。它适用于MacOS、Linux和Windows（通过wsl）上的许多终端和shell。
- [aloc](https://github.com/modern-tooling/aloc) — 一个使用Rust和Ratatui构建的现代AI增强代码行计数器。使用AI工作量配置文件进行准确的项目估算。
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — 以仓库为上下文的CLI聊天机器人。支持OpenAI以及通过GPT4All本地运行的LLM。
- [gptcomet](https://github.com/belingud/gptcomet) — 帮助您生成提交消息和审查更改的CLI工具。支持多种提供商和语言。
- [poorcoder](https://github.com/vgrichina/poorcoder) — 一系列Bash脚本，用于提取代码上下文、应用markdown中的更改以及在使用基于Web的LLM时生成AI提交消息。
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — 一个自编译工具，使用LLM生成将基于markdown的提示堆栈转换为代码和测试。通过OpenRouter与任何LLM配合使用，包括Claude、ChatGPT和Grok。
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - 将自然语言转换为可执行的shell命令（例如：`ai Tell me the free space on disk`）。
- [promptext](https://github.com/1broseidon/promptext) — 智能代码上下文提取器，适用于AI助手，具有准确的token计数、相关性优先级和预算管理。在LLM token限制内准备优化的代码上下文。
- [Baz CLI](https://github.com/baz-scm/baz-cli) - 用于AI辅助代码审查的CLI，可访问实际代码、diff等。
- [AdaL](https://sylph.ai/) — 自进化的AI编码代理，让模型协作（Claude、GPT、Gemini）。本地运行，学习您的代码库模式。
- [Tokscale](https://github.com/junhoyeo/tokscale) — 用于跟踪AI编码代理（OpenCode、Claude Code、OpenClaw、Codex、Gemini CLI、Cursor IDE、AmpCode、Factory Droid）token使用情况的CLI工具，具有全球排行榜和2D/3D贡献图。
- [vsync](https://github.com/nicepkg/vsync) — CLI工具，通过自动格式转换（JSON ↔ TOML ↔ JSONC）同步Claude Code、Cursor、OpenCode和Codex中的技能、MCP服务器、代理和命令。
- [Arctic](https://github.com/arctic-cli/interface): 一个终端优先的TUI，统一了多个AI编码计划和API，并内置了使用情况和配额可见性。

### 桌面

- [Memex](https://memex.tech/) — 在您的桌面上，只需自然语言，即可构建任何堆栈中的任何东西。
- [Pieces](https://pieces.app/) — AI驱动的桌面应用程序和浏览器扩展，旨在帮助开发者提高生产力。

## Shell 助手

- [AskCommand](https://www.askcommand.cppexpert.online/) — 基于Web的工具，使用AI自动从文本生成Unix命令。
- [Butterfish](https://butterfi.sh) — CLI工具，将ChatGPT嵌入到您的shell中，方便访问。包括简单的代理功能。
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — 高度可配置的CLI助手，用于生成shell命令并获取其解释。
- [GitFluence](https://www.gitfluence.com/) — 基于Web的Git命令生成器，使用AI驱动的解决方案从文本描述自动生成终端或CLI的Git命令，以建议最相关的Git命令。
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - CLI工具，只需键入<TAB><TAB>即可直接在终端中添加AI驱动的命令行建议，返回最相关的建议。
- [code-collator](https://github.com/tawandakembo/code-collator) — CLI工具，创建一个单一的markdown文件，向语言模型描述您的整个代码库。对于Claude/ChatGPT Web界面而非通过API进行AI编码辅助非常有用。
- [Warp](https://www.warp.dev/) - Warp将AI和团队知识整合到一个快速直观的终端中。
- [TmuxAI](https://tmuxai.dev/) - AI驱动的非侵入式终端助手。
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - 管理具有动态补全和AI集成的命令模板/代码片段。

## 代理

- [Smol Developer](https://github.com/smol-ai/developer) — 从提示生成仓库的CLI代理。使用OpenAI和Anthropic。
- [Aider](https://github.com/paul-gauthier/aider) — 生成更改并提交到仓库的CLI助手和代理。使用OpenAI。
- [Blinky](https://github.com/seahyinghang8/blinky) — VS Code的调试代理，帮助识别和修复后端错误，灵感来自SWE-agent。
- [Mentat](https://www.mentat.ai/) — 对仓库进行更改的CLI助手和代理。
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — 从提示生成仓库并提出澄清问题的CLI代理。
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — 将全栈应用程序从一种语言或框架转换为另一种语言或框架的CLI代理。使用GPT-4 32k上下文。
- [Grit](https://app.grit.io) — GitHub集成代理，用于自动化维护任务和其他开发工作。
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — 借助Llama 2的力量自动生成AI应用程序。
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT：AI驱动的软件开发自动化解决方案。
- [Second.dev](https://www.second.dev/) — 一个用于向全栈应用程序添加功能的平台。
- [Factory](https://www.factory.ai/) — 用于代码生成的代理。已加入等待列表。
- [sudocode](https://sudocode.ai/) — 一个基于Web的聊天助手，用于生成项目，类似于Code Interpreter。
- [CodeFlash AI](https://www.codeflash.ai/) — 一个用于使用AI优化Python代码的CLI和CI工具。
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — 一个为您编写和修复代码的AI代理。
- [Fine](https://fine.dev/?ref=awesome) — 用于自动化繁琐工作的AI开发环境。集成GitHub、Sentry、Linear。获取上下文感知的答案。规划、设计和实施更改。自动化自修复CI/CD。
- [Potpie](https://potpie.ai) — 几分钟内为您的代码库创建开源AI代理。使用预构建的代理进行问答、测试、调试和系统设计，或创建您自己的专用代理。
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — 零配置MCP服务器，通过智能自动发现和标准化接口统一多个AI编码助手。
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Anthropic的代理编码工具。
- [Open Agent](https://github.com/Th0rgal/openagent) — Claude Code的自托管控制平面，具有隔离的容器工作区和实时任务流。
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — 规范驱动、自迭代的多代理框架，用于Claude Code，具有协调的专业代理（Python、Next.js、CI/CD、QA、UI测试）。
- [Leap.new](https://leap.new/) - 它使用真实的后端服务、API构建功能性应用程序，并部署到您的云端。
- [Recurse ML](https://recurse.ml) - 查找AI生成代码中的错误。
- [Zenable](https://zenable.io/) — AI护栏，学习您的团队标准并确保编码代理遵循它们，从而最大限度地提高速度和质量。
- [Trellis](https://github.com/mindfold-ai/Trellis) - 用于Claude Code和Cursor的一体化AI框架和工具包。管理任务、规范和多代理管道。

## PR 代理

- [Greptile](https://greptile.com/code-review-bot) — AI机器人，在GitHub/Gitlab中审查PR，并提供完整的代码库上下文。
- [Macroscope](https://macroscope.com/code-review) - AI驱动的GitHub代码审查，使用AST构建代码库的基于图的表示，并从问题管理系统中提取上下文。
- [EntelligenceAI](https://entelligence.ai/pr) — AI驱动的GitHub和Gitlab代码审查，根据用户评论随时间改进。
- [Sweep](https://github.com/sweepai/sweep) — AI初级开发人员：GitHub集成，用于从问题生成、测试和自审查拉取请求。
- [Codegen](https://www.codegen.com/) — 基于GPT-4的企业代码库PR代理。
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — 用于审查PR的开源工具。作为GitHub action、Gitlab CLI或本地工作。
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — 用于自动化代码审查的开源工具。Qodo以前称为Codium（不要与带有"E"的Codeium混淆）。
- [Nova](https://www.trynova.ai/) — CI机器人，为新的PR添加摘要和测试等操作。
- [CodeRabbit](https://coderabbit.ai/) — 可定制的CI，为PR添加摘要和代码建议。
- [SwePT](https://github.com/keerthanpg/SwePT) — 用150行Python代码编写的开源PR生成器。
- [Duckie](https://duckie.ai/) — 一个基于Web的聊天助手，用于修改GitHub仓库。
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — 一个GitHub集成，为新创建的PR添加解释性文本。
- [Goast](https://goast.ai/) — 一个托管工具，用于摄取错误日志并建议修复。
- [Corgea](https://corgea.com/) — 一个GitHub集成，用于查找和修复易受攻击的代码。
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — 一个专注于UI生成的GitHub集成，内置支持shadcn、lucide和nivo图表。
- [Pixee](https://pixee.ai) — Pixeebot在您的代码中查找安全和代码质量问题，并创建带有建议修复的合并就绪拉取请求。
- [CodeAnt AI](https://www.codeant.ai/) — 自动创建PR以修复代码问题。
- [What The Diff](https://whatthediff.ai/) — AI驱动的应用程序，审查拉取请求的差异，并用简单的英语编写关于更改的描述性评论。
- [Trag](https://usetrag.com/) — AI驱动的代码审查，具有预定义的指令和模式。
- [CodeReviewBot](https://codereviewbot.ai/) — AI驱动的GitHub代码审查。
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — AI驱动的GitHub PR审查器，旨在识别错误、安全问题和性能瓶颈。
- [Matter AI](https://matterai.dev) - 开源AI代码审查器，帮助工程团队自信地发布代码。
- [Gito](https://github.com/Nayjest/Gito) - AI代码审查器，可与任何语言模型配合使用，无论是本地还是在GitHub Actions中。
- [Baz](https://baz.co) - AI代码审查器，根据您的团队指南和约定量身定制。可定制、适应性强、响应迅速，并与其余开发人员工具集成以获取上下文。

## 应用生成器

- [Pico](https://picoapps.xyz) — 端到端微应用生成器，即时部署。
- [Co.dev](https://www.co.dev/) — AI驱动的应用程序开发平台，帮助构建和部署全栈应用程序。
- [SoftGen](https://softgen.ai/) — AI驱动的软件生成平台，用于构建Web应用程序。
- [LlamaCoder](https://llamacoder.together.ai/) — 用于使用开源LLM构建应用程序的开源代码生成模型。
- [e2b_Fragments](https://fragments.e2b.dev/) — 用于构建和部署具有沙盒环境的AI驱动应用程序的平台。
- [Bolt.new](https://bolt.new) — AI驱动的Web开发代理，允许您直接在浏览器中使用WebContainers提示、运行、编辑和部署全栈应用程序。支持npm包、Node.js服务器和第三方API。
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Bolt.new的开源版本，支持多种LLM提供商，包括Groq、Anthropic、Ollama、OpenRouter、Gemini、LMStudio、Mistral、xAI、HuggingFace、DeepSeek。
- [Srcbook](https://github.com/srcbookdev/srcbook) — 以TypeScript为中心的应用程序开发平台，具有AI应用程序构建器和TypeScript笔记本。
- [Capacity](https://capacity.so) — AI驱动的全栈Web应用程序开发，将自然语言提示转换为功能齐全的Web应用程序。
- [Lovable](https://lovable.dev/) — AI驱动的全栈应用程序开发平台，将自然语言描述或设计转换为功能齐全的应用程序，并内置部署和GitHub集成。
- [Literally anything](https://literallyanything.io) — HTML和JavaScript Web应用程序生成器。
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — 从简短描述生成全栈React/Node.js/Prisma/Wasp应用程序。
- [Make Real](https://makereal.tldraw.com/) — 可用于生成HTML/JavaScript应用程序的在线画布。
- [Marblism](https://marblism.com) — 从提示生成SaaS样板。
- [Glowbom](https://glowbom.com/) — 使用AI生成应用程序并导出到多个平台。
- [Mage](https://usemage.ai/) — 在Wasp、React、Node.js和Prisma中生成全栈Web应用程序。
- [ScrollHub](https://hub.scroll.pub/) — 使用Scroll编程语言生成和发布网站。
- [Taskade Genesis](https://taskade.com/genesis) — AI驱动的平台，用于使用自然语言构建自定义AI代理、工作流和应用程序。支持多模型（GPT-4o、Claude、Gemini），开源MCP服务器。
- [Berrry](https://berrry.app) — Twitter应用程序生成器，将社交媒体帖子转换为功能性Web应用程序。将推文和Reddit内容转换为具有独特子域的完整应用程序。
- [Blank Space](https://www.blankspace.build/) — 开源AI应用程序构建器，用于使用自然语言创建Web应用程序。v0、Lovable和Bolt的自托管替代方案。
- [Fastshot](https://fastshot.ai/) — AI驱动的无代码平台，用于构建和部署移动应用程序。

## UI 生成器

- [v0](https://v0.dev/) — 在浏览器中创建和迭代新的UI组件。
- [Rendition Create](https://www.renditioncreate.com/) — 在浏览器中创建和迭代新的UI组件。
- [Rapidpages](https://github.com/rapidpages/rapidpages) — 开源UI生成器。
- [Magic Patterns](https://www.magicpatterns.com/) — 快速原型化您的产品想法。UI生成器网站，您可以通过提示、上传图片或使用其[Chrome扩展](https://www.magicpatterns.com/extension)导入设计灵感。可以通过[插件](https://www.figma.com/community/plugin/1304255855834420274)导出到Figma。支持多种组件系统，包括Shadcn、ChakraUI和HTML + Tailwind。
- [Tempo](https://www.tempolabs.ai/) — React界面的WYSIWYG编辑器。
- [Kombai](https://kombai.com/) — 从Figma生成前端代码的AI工具。
- [CodeParrot](https://www.codeparrot.ai/) — VS Code插件，用于从Figma生成前端代码。重用现有组件、库和编码标准，生成与您现有代码库完美契合的代码。无需任何提示。
- [Galileo AI](https://www.usegalileo.ai/) — 一个文本到UI的平台。等待列表。
- [Uizard](https://uizard.io/) — 从文本提示生成多屏幕模型，并使用拖放编辑器进行编辑。扫描应用程序截图或手绘线框图，并将其转换为可编辑的应用程序模型。
- [Frontly](https://fronty.com/) — 将上传的图像转换为HTML CSS代码。
- [BoringUi](https://www.boringui.xyz/) — 使用您的JSON数据创建漂亮的UI。生成的UI是HTML和Tailwind CSS，代码可以复制，UI可以通过链接与任何人共享。
- [CSS Picker](https://csspicker.dev/) - 从现有设计复制UI并与AI迭代，支持从网站复制CSS（通过[CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)）、图像到代码和文本到UI。

## 代码片段生成器

- [CodePal](https://codepal.ai/) — 一个用于快速生成或重构代码的Web工具。
- [AI Code Convert](https://aicodeconvert.com/) — 一个用于在编程语言之间翻译代码的Web工具。
- [AI Code Playground](https://aicodeplayground.com/) — 一个用于重构和改进代码的Web工具。
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex使用OpenAI的GPT-3从纯英语生成正则表达式。
- [unpkg.ai](https://unpkg.ai/) — 开源AI驱动的ESM模块生成服务。通过URL生成JavaScript模块以进行快速原型设计。

## 文档

- [Trelent](https://trelent.net/) — 一个用于生成文档字符串的VS Code扩展。使用专有模型。
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT是一个免费的基于AI的Web应用程序，可将架构、基础设施定义、代码片段或纯语言描述转换为图表。该工具可以生成流程图、实体关系图、云架构图和序列图。
- [DocuWriter.ai](https://www.docuwriter.ai/) — AI驱动的Web应用程序，可从源代码文件生成自动化代码和API文档。
- [README-AI](https://github.com/eli64s/readme-ai) — 由大型语言模型API驱动的自动化README.md文件生成器。
- [Supacodes](https://www.supacodes.com) — 一个AI工具，可在Github中自动化编写和更新代码文档。
- [CodexAtlas](https://codedocumentation.app/) — 使用最新的AI模型自动化代码和API文档。

## 可观测性

- [TraceRoot AI](https://traceroot.ai/) - 一个AI原生可观测性工具，使用AI代理自动修复您的生产错误。

## OpenAI 插件

- [ChatWithGit](https://gitsearch.sdan.io/) — 使ChatGPT能够搜索GitHub并返回相关仓库的链接。
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — 一个ChatGPT插件的开源示例，它从文件目录中提取上下文。

## 搜索

- [Bloop](https://bloop.ai/) — 仓库的自然语言搜索。
- [Buildt](https://www.buildt.ai/) — 仓库的自然语言搜索。等待列表。
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — 一个本地搜索工具，利用向量嵌入语义搜索您的代码库。
- [ContextMCP](https://contextmcp.ai) — 自托管的语义搜索，跨各种来源的文档，用于AI代理。

## 测试

- [Checksum AI](https://checksum.ai) — 端到端全自动QA自动化代理，直接向仓库生成CI/CD就绪的Playwright测试。
- [OctoMind](https://octomind.dev) — 自动维护和生成的基于浏览器的端到端测试，集成到Github Actions、Azure DevOps等。
- [Traceloop](https://traceloop.com/) — 使用OpenTelemetry跟踪数据和生成式AI来提高系统可靠性。
- [Carbonate](https://carbonate.dev/) — 使用自然语言进行端到端测试。集成到您现有的测试套件中（目前支持Jest、PHPUnit和Python的unittest）。
- [Meticulous.ai](https://www.meticulous.ai/) — 自动生成、自动维护的端到端测试：随着您的应用程序的发展，您的测试套件也会随之发展。
- [DiffBlue](https://www.diffblue.com/) — 自动生成Java单元测试。
- [Qodo](https://www.qodo.ai/) — 支持主要编程语言的非平凡测试生成。VS Code和JetBrains的扩展。（以前称为Codium）
- [DeepUnit](https://www.deepunit.ai/) — 周到的测试用例和完整单元测试文件的生成。可作为交互式VS Code扩展、npm包、CLI或CI/CD管道使用。
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — 通过查找代码中的漏洞并为其生成测试来加速开发人员生产力和代码安全性。开源，可作为CLI或CI/CD管道使用。
- [KushoAI](https://kusho.ai/) — 用于API测试的AI代理，将您的Postman集合、OpenAPI规范、curl命令等转换为详尽的测试套件，并插入到您的CI/CD管道中。
- [Test Gru](https://gru.ai/home#test-gru) — 提供企业级单元测试自动化服务。
- [AgentsKB](https://agentskb.com) - AI助手的专家知识层。您的AI搜索，我们研究。这就是区别。

## 评估

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — 用于评估编码代理的基准测试套件。比较配置、跟踪指标，并使用来自您的仓库的实际问题进行A/B测试。

## 资源

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — 精选的开源AI和开发者工具项目的深度教程。
- [Havoptic](https://havoptic.com/) — 免费、开源的时间线，跟踪AI编码工具的发布。每日自动更新。[Source](https://github.com/scotthavird/havoptic.com)

---

## 🤝 如何贡献

我们欢迎任何形式的贡献！请先阅读 [贡献指南](CONTRIBUTING.md)。

1. Fork 本仓库
2. 创建一个新分支 (`git checkout -b feature/add-new-tool`)
3. 在英文版本 (`i18n/README.en.md`) 的适当类别中添加您的工具
4. 提交一个 Pull Request

---

## 📜 开源许可

本项目基于 [MIT 许可](LICENSE) 开源。

## 🔗 相关项目

- [awesome-ai-devtools](https://github.com/jamesmurdza/awesome-ai-devtools) — 原始的英文版精选列表
- [awesome](https://github.com/sindresorhus/awesome) — 关于各种有趣主题的 Awesome Lists

---

<p align="center">
  用心制作 ❤️ 服务全球开发者社区
</p>

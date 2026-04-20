> **🌍 语言 / Languages:**
> [中文](./README.zh.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 Awesome AI-Powered Developer Tools
Dies ist eine kuratierte Liste von KI-gestützten Entwicklertools. Diese Tools nutzen KI, um Entwickler bei Aufgaben wie Code-Vervollständigung, Refactoring, Debugging, Dokumentation und vielem mehr zu unterstützen.

- [IDEs](#ides)
- [Git Clients](#git-clients)
- [Assistenten](#assistenten)
  - [Webbasiert](#web-basiert)
  - [IDE-Erweiterungen](#ide-erweiterungen)
  - [Kommandozeile](#kommandozeile)
  - [Desktop](#desktop)
- [Shell-Assistenten](#shell-assistenten)
- [Agenten](#agenten)
- [PR-Agenten](#pr-agenten)
- [App-Generatoren](#app-generatoren)
- [UI-Generatoren](#ui-generatoren)
- [Snippet-Generatoren](#snippet-generatoren)
- [Dokumentation](#dokumentation)
- [OpenAI-Plugins](#openai-plugins)
- [Suche](#suche)
- [Testen](#testen)
- [Evaluierung](#evaluierung)
- [Ressourcen](#ressourcen)

## IDEs
- [Google Antigravity](https://antigravity.google/) — Eine Agent-First-IDE, die autonome KI-Agenten orchestriert, um komplexe Codierungsaufgaben mit tiefer Browser-Integration zu planen, auszuführen und zu verifizieren.
- [Crystal](https://github.com/stravu/crystal) — Eine neue Art von Entwicklungsumgebung zur Verwaltung, Inspektion und zum Testen paralleler Claude Code-Sitzungen.
- [Cursor](https://www.cursor.com/) — Eine IDE mit Chat-, Bearbeitungs-, Generierungs- und Debugging-Funktionen. Abgeleitet von VSCodium, daher ähnelt die Oberfläche VS Code. Verwendet OpenAI.
- [OpenMagic](https://github.com/Kalmuraee/OpenMagic) — AI-powered coding toolbar for any web app. Captures element context, previews diffs, and applies approved changes through a reverse proxy.
- [PearAI](https://trypear.ai/) — Ein Open-Source-Fork von VS Code mit Chat und Inline-Code-Generierung.
- [Melty](https://melty.sh/) — Ein Open-Source-Fork von VS Code mit integriertem Chat, Änderungs-Vorschauen und der Möglichkeit, Commits mit KI zu schreiben. Derzeit ist nur der Quellcode verfügbar.
- [Replit](https://replit.com/) — Webbasierte IDE mit Cloud-Entwicklungsumgebungen, Code-Vervollständigung, Chat, einem Softwareentwicklungsagenten und Deployments.
- [Mutable](https://github.com/mutableai/monitors4codegen) — Webbasierte IDE, integriert mit einem Chatbot und GitHub.
- [CodeStory](https://codestory.ai/) — Eine IDE mit Chat, Code-Erklärungen, automatisch generierten Commits und PR-Zusammenfassungen. Abgeleitet von VSCodium.
- [UI Pilot](https://ui-pilot.com/) — Chat-basierter KI-Code-Editor, der Formulare mit Material UI und GPT-4 erstellt.
- [GitWit](https://gitwit.dev/) — Webbasierter Editor zum Erstellen von ReactJS-Anwendungen mit KI.
- [Windsurf](https://windsurf.com) — Eine IDE mit Chat-, Bearbeitungs-, Generierungs- und Debugging-Funktionen. Abgeleitet von VSCodium, daher ähnelt die Oberfläche VS Code. Früher bekannt als Codeium.
- [Theia IDE](https://theia-ide.org/#theiaide) — Eine erweiterbare Open-Source-IDE (Web und Desktop), die KI-gestützte Funktionen wie Chat, Code-Vervollständigung, Terminal-Unterstützung und benutzerdefinierte Agenten unter Verwendung beliebiger LLMs bietet. Basierend auf [Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/), einer Plattform, die die Erstellung benutzerdefinierter, KI-gestützter Tools und IDEs ermöglicht.
- [OneCompiler](https://onecompiler.com/) — Ein kostenloser KI-gestützter Online-Compiler, der über 70 Sprachen unterstützt, darunter Java, Python, MySQL, C++ und HTML, zum Schreiben, Ausführen und Teilen von Code.
- [trae](https://www.trae.ai/) — Trae ist eine adaptive KI-IDE, die Ihre Arbeitsweise transformiert und mit Ihnen zusammenarbeitet, um schneller zu werden.
- [Zed](https://zed.dev/) - Ein leistungsstarker, Multiplayer-Code-Editor von den Machern von Atom und Tree-sitter.
- [Nimbalyst](https://nimbalyst.com) - Eine Agentenverwaltungsumgebung für Claude Code und Codex. Interaktive visuelle Bearbeitung von Markdown, Mockups, Excalidraw, Code. Parallele Sitzungsverwaltung.

## Git Clients

- [GitBrain](https://gitbrain.dev/) — Git-Client, der den Git-Workflow vereinfacht. Teilt Code-Änderungen auf, generiert Zusammenfassungen und Commit-Nachrichten für Code-Änderungen. Verwendet OpenAI.
- [GitButler](https://gitbutler.com/) — Git-Client für gleichzeitige Branches zusätzlich zu Ihrem bestehenden Workflow. Standardmäßig OpenAI, kann für die Generierung konventioneller Commit-Nachrichten auf Perplexity geändert werden.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - CLI-Tool, das KI verwendet, um automatisch hochwertige Git-Commit-Nachrichten und Pull-Request-Beschreibungen zu generieren.

## Assistenten

### Webbasiert

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — Assistent, der in [Replit](https://replit.com/) integriert ist, mit Chat, proaktivem Debugging und Autovervollständigung. Verwendet OpenAI für Chat und [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS) für Autovervollständigung.
- [Unblocked](https://getunblocked.com/) — Erweitert den Quellcode mit relevantem vorhandenem Wissen in GitHub, Slack, Jira, Confluence und mehr. Erhalten Sie Antworten über Chat und IDE-Dateikontext. Verfügbar im Web, macOS, Slack, VSCode und JetBrains IDEs.
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — Assistent mit Chat, Refactoring und Unit-Test-Generierung. Erweiterungen für VS Code und IntelliJ. Auch als Web-App verfügbar.
- [Magnet](https://www.magnet.run/) — Webbasierter Chatbot mit Repositories und Issues als Kontext.
- [Adrenaline](https://useadrenaline.com/) — Webbasierter Chatbot, der KI und ASTs verwendet, um Fragen zu Ihrer Codebasis zu beantworten.
- [CodeSquire](https://codesquire.ai/) — Chrome-Erweiterung, die Autovervollständigung zu Google Colab, BigQuery und JupyterLab hinzufügt.
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — Open-Source-Assistent mit integriertem Python-Editor und Interpreter.
- [Onboard](https://www.getonboardai.com) — Chatten Sie mit einer KI über öffentliche und private Codebasen.
- [Code to Flow](https://codetoflow.com) — Visualisieren, analysieren und verstehen Sie Code mit interaktiven Flussdiagrammen.
- [Pieces](https://pieces.app/) — Ein On-Device-Copilot, der Ihnen hilft, Code zu erfassen, anzureichern und wiederzuverwenden, die Zusammenarbeit zu optimieren und komplexe Probleme durch ein kontextuelles Verständnis Ihres Workflows zu lösen.
- [Wren AI](https://getwren.ai/oss) — SQL AI Agent, um schneller Ergebnisse und Erkenntnisse zu erhalten, indem Sie Fragen stellen, ohne SQL zu schreiben, und es ist Open-Source!
- [TEXT2SQL.AI](https://www.text2sql.ai/) — KI-gestützter SQL-Abfrage-Builder. Übersetzen, erklären und beheben Sie komplexe SQL-Abfragen mit einfachem Englisch.
- [SQLAI.ai](https://www.sqlai.ai/) — KI generiert, behebt, erklärt und optimiert SQL-Abfragen. Möglichkeit, Ihr eigenes Datenbankschema hinzuzufügen und die KI darauf zu trainieren, es zu verstehen.
- [CodeWP](https://codewp.ai/) — KI-Chat- und Codierungs-Tools, die speziell für WordPress-Entwickler trainiert wurden. KI-Code-Generierung für Code-Snippets und Plugins in WordPress.
- [Gru.ai](https://www.gru.ai/) — Ein KI-Entwickler kann Ihnen helfen, technische Probleme zu lösen und tägliche Codierungsaufgaben zu bewältigen, wie z.B. Algorithmen zu erstellen, Fehler zu debuggen, Lösungen zu testen, Programmierfragen zu beantworten usw.

### IDE-Erweiterungen

- [GitHub Copilot](https://github.com/features/copilot) — Eine VS Code-Erweiterung mit Chat, Pull-Request-Textgenerierung und Unit-Test-Generierung.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — Autonomer Codierungsagent für VS Code, der Dateien erstellen/bearbeiten, Befehle ausführen und den Browser mit Benutzererlaubnis nutzen kann. Unterstützt mehrere KI-Anbieter, darunter OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure und GCP Vertex.
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — Open-Source-Assistent mit Chat, Vervollständigung, Refactoring und Codebasis-spezifischem Fine-Tuning. Erweiterungen für VS Code und JetBrains.
- [Continue](https://continue.dev/) — VS Code-Erweiterung mit Chat, Refactoring und Code-Generierung. Bearbeitet mehrere Dateien und führt Befehle in Ihrem Namen aus.
- [Blackbox AI](https://www.useblackbox.io/) — VS Code-Erweiterung mit Autovervollständigung und Chat, einschließlich Links zu Online-Codierungsreferenzen.
- [CodeGeeX](https://codegeex.cn/) — Open-Source-Assistent basierend auf dem CodeGeeX LLM mit Chat, Vervollständigung und Refactoring. Erweiterungen für 9 Editoren, darunter VS Code und PyCharm.
- [Quack AI](https://www.quackai.com/) — VS Code-Erweiterung zur Einhaltung von Projekt-Codierungsrichtlinien.
- [Tabby](https://tabbyml.github.io/tabby/) — Open-Source, selbstgehosteter Code-Vervollständigungsassistent. Erweiterungen für VS Code und Vim.
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — Open-Source, selbstgehosteter Code-Vervollständigungsassistent. Erweiterungen für 15 Editoren, darunter VS Code, IntelliJ, Neovim, Eclipse und PyCharm.
- [CodeMate](https://www.codemate.ai/) — VS Code-Erweiterung zum Debuggen und Optimieren von Code.
- [AskCodi](https://www.askcodi.com/) — KI-Codierungsassistent mit Erweiterungen für VS Code, JetBrains und Sublime Text.
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Open-Source-Chat-Assistent für die Visual Studio Code Seitenleiste.
- [CodeComplete](https://codecomplete.ai/) — Selbstgehosteter, unternehmensweiter Vervollständigungsassistent.
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo ist ein KI-Agent, mit dem Sie Full-Stack-Apps mühelos erstellen und bereitstellen können, mit einem Klick Vercel-Bereitstellung und nahtloser Supabase-Integration.
- [JetBrains AI](https://www.jetbrains.com/ai/) — KI-Assistent, verfügbar in allen JetBrains IDEs.
- [aiXcoder](https://www.aixcoder.com/en/) — Lokaler oder Cloud-basierter Assistent mit Erweiterungen für IntelliJ IDEA, CLion, GoLand, PyCharm, WebStorm, Visual Studio Code und Eclipse.
- [Sourcery](https://sourcery.ai/) — KI-Assistent und Linter mit einer Referenz von 160 Python Best Practices und über 40 JS/TS Best Practices. Erweiterungen für VS Code, PyCharm, Vim und Sublime.
- [Swimm](https://swimm.io) — Assistent für kontextuelles Code-Verständnis unter Verwendung statischer Analyse und KI-generierter Dokumentation. VSCode, Jetbrains, IntelliJ, WebStorm, Rider, PhpStorm, Android Studio, PyCharm, PhPStorm.
- [Supermaven](https://supermaven.com/) — VS Code-Erweiterung für Autovervollständigung mit einem 300.000-Token-Kontextfenster.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — KI-Codierungsassistent mit Erweiterungen für IDEs wie VS Code und IntelliJ IDEA. Das Amazon Q Developer IDE-Plugin verfügt über eine Reihe von Agenten, die Code auch scannen können, um Sicherheitsprobleme hervorzuheben und zu definieren (/review), Dokumentation zu schreiben (/doc), Unit-Tests zu schreiben (/test) und Ihnen beim Upgrade auf spätere Java-Versionen zu helfen (/transform) (früher bekannt als Amazon CodeWhisperer).
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot ist ein KI-gestützter Codierungsassistent, der eng in Android Studio integriert ist. Studio Bot kann Android-Entwicklern helfen, Code zu generieren, relevante Ressourcen zu finden, Best Practices zu lernen und Zeit zu sparen.
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z ist ein KI-gestütztes Mainframe-Anwendungsmodernisierungsprodukt mit Code-Generierung. Zu den Funktionen gehören Anwendungsentdeckung und -analyse, automatisiertes Code-Refactoring und COBOL-zu-Java-Konvertierung.
- [EasyCode](https://www.easycode.ai/) — VS Code-Erweiterung mit GPT-4-Chat.
- [Kilo Code](https://kilocode.ai) - Open Source KI-Codierungsassistent zum Planen, Erstellen und Beheben von Code in VS Code.
- [FlyonUI MCP](https://flyonui.com/mcp) — Integrieren Sie FlyonUI MCP - Tailwind AI Builder direkt in Ihre IDE und erstellen Sie beeindruckende Tailwind CSS Komponenten, Blöcke und Seiten, inspiriert von FlyonUI.
- [Traycer](https://traycer.ai) - Plan-First Coding Assistant in VS Code.
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - Integrieren Sie shadcn/studio MCP Server direkt in Ihre bevorzugte IDE und erstellen Sie beeindruckende shadcn/ui Komponenten, Blöcke und Seiten, inspiriert von shadcn/studio.

### Kommandozeile

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - CLI, die Befehlsvervollständigung, Befehlsübersetzung unter Verwendung generativer KI zur Übersetzung von Absichten in Befehle und eine vollständige agentenbasierte Chat-Oberfläche mit Kontextverwaltung bietet, die Ihnen beim Schreiben von Code hilft. Sie funktioniert mit vielen Terminals und Shells unter MacOS, Linux und Windows (über wsl).
- [aloc](https://github.com/modern-tooling/aloc) — Ein moderner, KI-erweiterter Zeilencodezähler, erstellt mit Rust und Ratatui. Verwendet KI-Aufwandsprofile für genaue Projektkalkulationen.
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — CLI-Chatbot mit Repository als Kontext. Unterstützt OpenAI sowie lokal laufende LLMs über GPT4All.
- [gptcomet](https://github.com/belingud/gptcomet) — CLI-Tool, das Ihnen hilft, Commit-Nachrichten zu generieren und Änderungen zu überprüfen. Unterstützt mehrere Anbieter und Sprachen.
- [poorcoder](https://github.com/vgrichina/poorcoder) — Eine Sammlung von Bash-Skripten zum Extrahieren von Code-Kontext, Anwenden von Änderungen aus Markdown und Generieren von KI-Commit-Nachrichten unter Verwendung webbasierter LLMs.
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — Ein selbstkompilierendes Tool, das Markdown-basierte Prompt-Stacks in Code und Tests umwandelt, unter Verwendung von LLM-Generierung. Funktioniert mit jedem LLM über OpenRouter, einschließlich Claude, ChatGPT und Grok.
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - Wandelt natürliche Sprache in ausführbare Shell-Befehle um (z.B.: `ai Tell me the free space on disk`)
- [promptext](https://github.com/1broseidon/promptext) — Intelligenter Code-Kontext-Extraktor für KI-Assistenten mit präziser Token-Zählung, Relevanzpriorisierung und Budgetverwaltung. Bereitet optimierten Code-Kontext innerhalb der LLM-Token-Grenzen vor.
- [Baz CLI](https://github.com/baz-scm/baz-cli) - CLI für KI-gestützte Code-Überprüfung, mit Zugriff auf den tatsächlichen Code, Diff usw.
- [AdaL](https://sylph.ai/) — Sich selbst entwickelnder KI-Codierungsagent, der Modelle zusammenarbeiten lässt (Claude, GPT, Gemini). Läuft lokal, lernt Ihre Codebasis-Muster.
- [Tokscale](https://github.com/junhoyeo/tokscale) — CLI-Tool zur Verfolgung der Token-Nutzung von KI-Codierungsagenten (OpenCode, Claude Code, OpenClaw, Codex, Gemini CLI, Cursor IDE, AmpCode, Factory Droid) mit einer globalen Bestenliste und 2D/3D-Beitragskurven.
- [vsync](https://github.com/nicepkg/vsync) — CLI-Tool, das Skills, MCP-Server, Agenten & Befehle über Claude Code, Cursor, OpenCode und Codex hinweg synchronisiert, mit automatischer Formatkonvertierung (JSON ↔ TOML ↔ JSONC).
- [Arctic](https://github.com/arctic-cli/interface): Ein Terminal-First-TUI, das mehrere KI-Codierungspläne und APIs mit integrierter Nutzungs- und Quotenübersicht vereint.

### Desktop

- [Memex](https://memex.tech/) — Erstellen Sie alles in jedem Stack, nur mit natürlicher Sprache, auf Ihrem Desktop.
- [Pieces](https://pieces.app/) — KI-fähige Desktop-Anwendung und Browser-Erweiterung, die Entwickler bei der Steigerung der Produktivität unterstützen soll.

## Shell-Assistenten

- [AskCommand](https://www.askcommand.cppexpert.online/) — Web-basiertes Tool zur automatischen Generierung von Unix-Befehlen aus Text mittels KI.
- [Butterfish](https://butterfi.sh) — CLI-Tool, das ChatGPT in Ihre Shell einbettet, um einfachen Zugriff zu ermöglichen. Enthält einfache agentenbasierte Funktionen.
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — Hochgradig konfigurierbarer CLI-Assistent zum Generieren von Shell-Befehlen und zum Erhalten von Erklärungen dazu.
- [GitFluence](https://www.gitfluence.com/) — Webbasierter Git-Befehlsgenerator zur automatischen Generierung von Git-Befehlen für Terminal oder CLI aus Textbeschreibungen, unter Verwendung einer KI-gesteuerten Lösung, um die relevantesten Git-Befehle vorzuschlagen.
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - CLI-Tool, das KI-gestützte Befehlszeilenvorschläge direkt zu Ihrem Terminal hinzufügt, indem Sie einfach <TAB><TAB> eingeben, um die besten Vorschläge zu erhalten.
- [code-collator](https://github.com/tawandakembo/code-collator) — CLI-Tool, das eine einzelne Markdown-Datei erstellt, die Ihre gesamte Codebasis für Sprachmodelle beschreibt. Nützlich für KI-Codierungsunterstützung über die Claude/ChatGPT-Weboberfläche anstatt über die API.
- [Warp](https://www.warp.dev/) - Warp vereint KI und Teamwissen in einem einzigen, schnellen und intuitiven Terminal.
- [TmuxAI](https://tmuxai.dev/) - KI-gestützter, nicht-invasiver Terminal-Assistent.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - Verwalten Sie Befehlsvorlagen/Snippets mit dynamischen Vervollständigungen und KI-Integration.

## Agenten

- [Smol Developer](https://github.com/smol-ai/developer) — CLI-Agent, der ein Repository aus einem Prompt generiert. Verwendet OpenAI und Anthropic.
- [Aider](https://github.com/paul-gauthier/aider) — CLI-Assistent und Agent, der Änderungen generiert und in Repositories committet. Verwendet OpenAI.
- [Blinky](https://github.com/seahyinghang8/blinky) — Ein Debugging-Agent für VS Code, der hilft, Backend-Fehler zu identifizieren und zu beheben, inspiriert von SWE-agent.
- [Mentat](https://www.mentat.ai/) — CLI-Assistent und Agent, der Änderungen an Repositories vornimmt.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — CLI-Agent, der ein Repository aus einem Prompt generiert und klärende Fragen stellt.
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — CLI-Agent, der eine Full-Stack-Anwendung von einer Sprache oder einem Framework in ein anderes konvertiert. Verwendet GPT-4 32k Kontext.
- [Grit](https://app.grit.io) — GitHub-integrierter Agent zur Automatisierung von Wartungsaufgaben und anderen Entwicklungsarbeiten.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Auto Gen-AI App Generator mit der Power von Llama 2.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT: KI-gesteuerte Softwareentwicklungs-Automatisierungslösung.
- [Second.dev](https://www.second.dev/) — Eine Plattform zum Hinzufügen von Funktionen zu Full-Stack-Apps.
- [Factory](https://www.factory.ai/) — Agenten zur Code-Generierung. Warteliste.
- [sudocode](https://sudocode.ai/) — Ein webbasierter Chat-Assistent zum Generieren von Projekten, ähnlich wie Code Interpreter.
- [CodeFlash AI](https://www.codeflash.ai/) — Ein CLI- und CI-Tool zur Optimierung von Python-Code mittels KI.
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — Ein KI-Agent, der Code für Sie schreibt und repariert.
- [Fine](https://fine.dev/?ref=awesome) — KI-Entwicklungsumgebung zur Automatisierung routinemäßiger Arbeiten. Integriert GitHub, Sentry, Linear. Erhalten Sie kontextbezogene Antworten auf Fragen. Planen, entwerfen und implementieren Sie Änderungen. Automatisieren Sie selbstheilende CI/CD.
- [Potpie](https://potpie.ai) — Open Source KI-Agenten für Ihre Codebasis in Minuten. Verwenden Sie vorgefertigte Agenten für Q&A, Tests, Debugging und Systemdesign oder erstellen Sie Ihre eigenen zweckgebundenen Agenten.
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — Zero-Configuration MCP-Server, der mehrere KI-Codierungsassistenten durch intelligente Auto-Erkennung und standardisierte Schnittstelle vereint.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Anthropic's agentenbasiertes Codierungstool.
- [Open Agent](https://github.com/Th0rgal/openagent) — Selbstgehostete Steuerungsebene für Claude Code mit isolierten Container-Workspaces und Echtzeit-Missions-Streaming.
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — Spezifikationsgesteuertes, selbst-iteratives Multi-Agenten-Framework für Claude Code mit koordinierten spezialisierten Agenten (Python, Next.js, CI/CD, QA, UI Testing).
- [Leap.new](https://leap.new/) - Es erstellt funktionale Apps mit echten Backend-Diensten, APIs und stellt sie in Ihrer Cloud bereit.
- [Recurse ML](https://recurse.ml) - Findet Fehler in KI-generiertem Code.
- [Zenable](https://zenable.io/) — KI-Leitplanken, die die Standards Ihres Teams lernen und sicherstellen, dass Codierungsagenten diese befolgen, wodurch Geschwindigkeit und Qualität maximiert werden.
- [Trellis](https://github.com/mindfold-ai/Trellis) - All-in-One-KI-Framework & Toolkit für Claude Code & Cursor. Verwaltet Aufgaben, Spezifikationen und Multi-Agenten-Pipelines.

## PR-Agenten

- [Greptile](https://greptile.com/code-review-bot) — KI-Bot, der PRs in GitHub/Gitlab mit vollem Kontext der Codebasis überprüft.
- [Macroscope](https://macroscope.com/code-review) - KI-gestützte Code-Überprüfung für GitHub, die ASTs verwendet, um eine grafische Darstellung Ihrer Codebasis zu erstellen und Kontext aus Ihren Issue-Management-Systemen abruft.
- [EntelligenceAI](https://entelligence.ai/pr) — KI-gestützte Code-Reviews für Github und Gitlab, die sich im Laufe der Zeit basierend auf Benutzerkommentaren verbessern.
- [Sweep](https://github.com/sweepai/sweep) — KI-Junior-Entwickler: GitHub-Integration zum Generieren, Testen und Selbstüberprüfen von Pull Requests aus Issues.
- [Codegen](https://www.codegen.com/) — GPT-4-basierter PR-Agent für Unternehmenscodebasen.
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — Ein Open-Source-Tool zur Überprüfung von PRs. Funktioniert als GitHub Action, Gitlab CLI oder lokal.
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — Open-Source-Tool für automatisierte Code-Reviews. Qodo war früher als Codium bekannt (nicht zu verwechseln mit Codeium mit einem "E").
- [Nova](https://www.trynova.ai/) — CI-Bot zum Hinzufügen von Aktionen wie Zusammenfassungen und Tests zu neuen PRs.
- [CodeRabbit](https://coderabbit.ai/) — Anpassbarer CI zum Hinzufügen von Zusammenfassungen und Code-Vorschlägen zu PRs.
- [SwePT](https://github.com/keerthanpg/SwePT) — Open-Source-PR-Generator, geschrieben in 150 Zeilen Python-Code.
- [Duckie](https://duckie.ai/) — Ein webbasierter Chat-Assistent zum Ändern von GitHub-Repositories.
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — Eine GitHub-Integration, die erklärenden Text zu neu erstellten PRs hinzufügt.
- [Goast](https://goast.ai/) — Ein gehostetes Tool, das Ihre Fehlerprotokolle aufnimmt und Korrekturen vorschlägt.
- [Corgea](https://corgea.com/) — Eine GitHub-Integration, die anfälligen Code findet und behebt.
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — Eine GitHub-Integration, die sich auf die UI-Generierung konzentriert, mit integrierter Unterstützung für shadcn, lucide und nivo charts.
- [Pixee](https://pixee.ai) — Pixeebot findet Sicherheits- und Codequalitätsmängel in Ihrem Code und erstellt merge-fähige Pull Requests mit empfohlenen Korrekturen.
- [CodeAnt AI](https://www.codeant.ai/) — Erstellt automatisch PRs zur Behebung von Code-Problemen.
- [What The Diff](https://whatthediff.ai/) — KI-gestützte App, die den Diff von Pull Requests überprüft und einen beschreibenden Kommentar zu den Änderungen in einfachem Englisch schreibt.
- [Trag](https://usetrag.com/) — KI-gestützte Code-Reviews mit vordefinierten Anweisungen und Mustern.
- [CodeReviewBot](https://codereviewbot.ai/) — KI-gestützte Code-Reviews für GitHub.
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — KI-gestützter PR-Reviewer für GitHub, entwickelt zur Identifizierung von Fehlern, Sicherheitsproblemen und Performance-Engpässen.
- [Matter AI](https://matterai.dev) - Open Source KI-Code-Reviewer, um Ingenieurteams dabei zu helfen, Code mit Vertrauen zu veröffentlichen.
- [Gito](https://github.com/Nayjest/Gito) - KI-Code-Reviewer, der mit jedem Sprachmodell funktioniert, lokal oder in GitHub Actions.
- [Baz](https://baz.co) - KI-Code-Reviewer, der auf die Richtlinien und Konventionen Ihres Teams zugeschnitten ist. Anpassbar, adaptiv, reaktionsschnell und in die restlichen Entwicklertools für den Kontext integriert.

## App-Generatoren

- [Pico](https://picoapps.xyz) — End-to-End-Mikro-App-Generator mit sofortiger Bereitstellung.
- [Co.dev](https://www.co.dev/) — KI-gestützte App-Entwicklungsplattform, die beim Erstellen und Bereitstellen von Full-Stack-Anwendungen hilft.
- [SoftGen](https://softgen.ai/) — KI-gestützte Software-Generierungsplattform zum Erstellen von Web-Apps.
- [LlamaCoder](https://llamacoder.together.ai/) — Open-Source-Code-Generierungsmodell zum Erstellen von Anwendungen mit Opensource LLMs.
- [e2b_Fragments](https://fragments.e2b.dev/) — Plattform zum Erstellen und Bereitstellen von KI-gestützten Anwendungen mit Sandbox-Umgebungen.
- [Bolt.new](https://bolt.new) — KI-gestützter Webentwicklungsagent, der es Ihnen ermöglicht, Full-Stack-Anwendungen direkt im Browser mit WebContainers zu erstellen, auszuführen, zu bearbeiten und bereitzustellen. Unterstützt npm-Pakete, Node.js-Server und APIs von Drittanbietern.
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Open-Source-Version von Bolt.new, die mehrere LLM-Anbieter unterstützt, darunter Groq, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek.
- [Srcbook](https://github.com/srcbookdev/srcbook) — TypeScript-zentrierte App-Entwicklungsplattform mit einem KI-App-Builder und TypeScript-Notebook.
- [Capacity](https://capacity.so) — KI-gestützte Full-Stack-Web-App-Entwicklung, die Prompts in natürlicher Sprache in voll funktionsfähige Webanwendungen umwandelt.
- [Lovable](https://lovable.dev/) — KI-gestützte Full-Stack-App-Entwicklungsplattform, die Beschreibungen oder Designs in natürlicher Sprache in voll funktionsfähige Anwendungen mit integrierter Bereitstellung und GitHub-Integration umwandelt.
- [Literally anything](https://literallyanything.io) — HTML- und JavaScript-Web-App-Generator.
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — Generiert eine Full-Stack-React/Node.js/Prisma/Wasp-App aus einer kurzen Beschreibung.
- [Make Real](https://makereal.tldraw.com/) — Online-Canvas, das zur Generierung von HTML/JavaScript-Apps verwendet werden kann.
- [Marblism](https://marblism.com) — Generiert ein SaaS-Boilerplate aus einem Prompt.
- [Glowbom](https://glowbom.com/) — Generiert Apps mit KI und exportiert sie auf mehrere Plattformen.
- [Mage](https://usemage.ai/) — Generiert Full-Stack-Web-Apps in Wasp, React, Node.js und Prisma.
- [ScrollHub](https://hub.scroll.pub/) — Generiert und veröffentlicht Websites mit der Programmiersprache Scroll.
- [Taskade Genesis](https://taskade.com/genesis) — KI-gestützte Plattform zum Erstellen benutzerdefinierter KI-Agenten, Workflows und Apps mit natürlicher Sprache. Multi-Modell-Unterstützung (GPT-4o, Claude, Gemini), Open-Source-MCP-Server.

- [Berrry](https://berrry.app) — Twitter-App-Generator, der Social-Media-Beiträge in funktionale Webanwendungen umwandelt. Verwandelt Tweets und Reddit-Inhalte in vollständige Apps mit einzigartigen Subdomains.
- [Blank Space](https://www.blankspace.build/) — Open-Source-KI-App-Builder zum Erstellen von Webanwendungen mit natürlicher Sprache. Selbst hostbare Alternative zu v0, Lovable und Bolt.
- [Fastshot](https://fastshot.ai/) — KI-gesteuerte No-Code-Plattform zum Erstellen und Bereitstellen mobiler Apps.

## UI-Generatoren

- [v0](https://v0.dev/) — Erstellen und iterieren Sie neue UI-Komponenten in Ihrem Browser.
- [Rendition Create ](https://www.renditioncreate.com/) — Erstellen und iterieren Sie neue UI-Komponenten in Ihrem Browser.
- [Rapidpages](https://github.com/rapidpages/rapidpages) — Open-Source-UI-Generator.
- [Magic Patterns](https://www.magicpatterns.com/) — Prototypen Sie Ihre Produktideen. UI-Generator-Website, auf der Sie Prompts eingeben, Bilder hochladen oder Design-Inspirationen mit ihrer [Chrome Extension](https://www.magicpatterns.com/extension) importieren können. Kann mit einem [Plugin](https://www.figma.com/community/plugin/1304255855834420274) nach Figma exportieren. Unterstützt eine Reihe von Komponentensystemen, darunter Shadcn, ChakraUI und HTML + Tailwind.
- [Tempo ](https://www.tempolabs.ai/) — WYSIWYG-Editor für React-Schnittstellen.
- [Kombai](https://kombai.com/) — KI-Tool zur Generierung von Frontend-Code aus Figma.
- [CodeParrot](https://www.codeparrot.ai/) — VS Code-Plugin zur Generierung von Frontend-Code aus Figma. Verwendet vorhandene Komponenten, Bibliotheken und Codierungsstandards wieder, um Code zu generieren, der perfekt zu Ihrer bestehenden Codebasis passt. Alles ohne jegliche Prompts.
- [Galileo AI](https://www.usegalileo.ai/) — Eine Text-zu-UI-Plattform. Warteliste.
- [Uizard](https://uizard.io/) — Generieren Sie Multi-Screen-Mockups aus Text-Prompts und bearbeiten Sie sie mit einem Drag-and-Drop-Editor. Scannen Sie Screenshots von Apps oder handgezeichnete Wireframes und verwandeln Sie sie in bearbeitbare App-Mockups.
- [Frontly](https://fronty.com/) — Konvertiert das hochgeladene Bild in HTML-CSS-Code.
- [BoringUi](https://www.boringui.xyz/) — Erstellen Sie schöne UIs mit Ihren JSON-Daten. Die generierte UI ist in HTML und Tailwind CSS mit Code, der kopiert werden kann, und die UI kann über Links mit jedem geteilt werden.
- [CSS Picker](https://csspicker.dev/) - Kopieren Sie UI von bestehendem Design und iterieren Sie mit KI, unterstützt das Kopieren von CSS von Websites (durch [CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)), Bild zu Code und Text zu UI.

## Snippet-Generatoren

- [CodePal](https://codepal.ai/) — Ein Web-Tool zum schnellen Generieren oder Refactoring von Code.
- [AI Code Convert](https://aicodeconvert.com/) — Ein Web-Tool zum Übersetzen von Code zwischen Programmiersprachen.
- [AI Code Playground](https://aicodeplayground.com/) — Ein Web-Tool zum Refactoring und Verbessern von Code.
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex verwendet OpenAI's GPT-3, um reguläre Ausdrücke aus einfachem Englisch zu erstellen.
- [unpkg.ai](https://unpkg.ai/) — Open-Source-KI-gestützter ESM-Modulgenerierungsdienst. Generieren Sie JavaScript-Module über URL für schnelles Prototyping.

## Dokumentation

- [Trelent](https://trelent.net/) — Eine VS Code-Erweiterung zum Generieren von Docstrings. Verwendet proprietäre Modelle.
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT ist eine kostenlose KI-basierte Web-App, die ein Schema, eine Infrastrukturdefinition, ein Code-Snippet oder eine Beschreibung in einfacher Sprache in Diagramme umwandelt. Das Tool kann Flussdiagramme, Entity-Relationship-Diagramme, Cloud-Architekturdiagramme und Sequenzdiagramme generieren.
- [DocuWriter.ai](https://www.docuwriter.ai/) — KI-gestützte Web-App zur Generierung automatischer Code- und API-Dokumentation aus Ihren Quellcodedateien.
- [README-AI](https://github.com/eli64s/readme-ai) — Automatischer README.md-Dateigenerator, angetrieben von großen Sprachmodell-APIs.
- [Supacodes](https://www.supacodes.com) — Ein KI-Tool, das das Schreiben und Aktualisieren von Code-Dokumentation in Github automatisiert.
- [CodexAtlas](https://codedocumentation.app/) — Automatisierte Code- und API-Dokumentation unter Verwendung der neuesten KI-Modelle.

## Beobachtbarkeit
- [TraceRoot AI](https://traceroot.ai/) - Ein KI-natives Observability-Tool, das KI-Agenten verwendet, um Ihre Produktionsfehler automatisch zu beheben.

## OpenAI-Plugins

- [ChatWithGit](https://gitsearch.sdan.io/) — Ermöglicht ChatGPT, GitHub zu durchsuchen und Links zu relevanten Repositories zurückzugeben.
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — Open-Source-Beispiel eines ChatGPT-Plugins, das Kontext aus einem Dateiverzeichnis zieht.

## Suche

- [Bloop](https://bloop.ai/) — Natürliche Sprachsuche für Repositories.
- [Buildt](https://www.buildt.ai/) — Natürliche Sprachsuche für Repositories. Warteliste.
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — Ein lokales Suchwerkzeug, das Vektor-Embeddings nutzt, um Ihre Codebasis semantisch zu durchsuchen.
- [ContextMCP](https://contextmcp.ai) — Selbstgehostete semantische Suche über Dokumentationen aus verschiedenen Quellen für KI-Agenten.

## Testen

- [Checksum AI](https://checksum.ai) — End-to-End vollständig autonomer QA-Automatisierungsagent, der CI/CD-bereite Playwright-Tests direkt in das Repository generiert.
- [OctoMind](https://octomind.dev) — Automatische Wartung und generierte browserbasierte End-to-End-Tests, integriert in Github Actions, Azure DevOps und mehr.
- [Traceloop](https://traceloop.com/) — Verwendet OpenTelemetry-Tracing-Daten mit generativer KI, um die Systemzuverlässigkeit zu verbessern.
- [Carbonate](https://carbonate.dev/) — End-to-End-Tests mit natürlicher Sprache. Integriert sich in Ihre bestehende Testsuite (derzeit Jest, PHPUnit und Pythons unittest).
- [Meticulous.ai](https://www.meticulous.ai/) — Automatisch generierte, automatisch gewartete End-to-End-Tests: Wenn sich Ihre App weiterentwickelt, entwickelt sich auch Ihre Testsuite.
- [DiffBlue](https://www.diffblue.com/) — Automatisch generierte Unit-Tests für Java.
- [Qodo](https://www.qodo.ai/) — Nicht-triviale Testgenerierung mit Unterstützung für wichtige Programmiersprachen. Erweiterungen für VS Code und JetBrains. (früher Codium)
- [DeepUnit](https://www.deepunit.ai/) — Durchdachte Testfälle und Generierung kompletter Unit-Test-Dateien. Verfügbar als interaktive VS Code-Erweiterung, npm-Paket, CLI oder CI/CD-Pipeline.
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — Beschleunigt die Entwicklerproduktivität und Codesicherheit, indem Schwachstellen im Code gefunden und Tests dafür generiert werden. Open Source und als CLI oder CI/CD-Pipeline verfügbar.
- [KushoAI](https://kusho.ai/) — KI-Agent für API-Tests, der Ihre Postman-Sammlungen, OpenAPI-Spezifikationen, Curl-Befehle usw. in umfassende Testsuiten umwandelt, die in Ihre CI/CD-Pipeline integriert werden können.
- [Test Gru](https://gru.ai/home#test-gru) — Bietet Unit-Test-Automatisierungsdienste auf Unternehmensebene.

- [AgentsKB](https://agentskb.com) - Expertenwissensschicht für KI-Assistenten. Ihre KI sucht, wir recherchieren. Das ist der Unterschied.

## Evaluierung

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — Benchmark-Suite zur Evaluierung von Codierungsagenten. Vergleichen Sie Konfigurationen, verfolgen Sie Metriken und führen Sie A/B-Tests mit realen Problemen aus Ihren Repositories durch.

## Ressourcen

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — Kuratierte Deep-Dive-Tutorials für Open-Source-KI- und Entwickler-Tooling-Projekte.
- [Havoptic](https://havoptic.com/) — Kostenlose, Open-Source-Zeitleiste, die Veröffentlichungen von KI-Codierungstools verfolgt. Täglich automatisch aktualisiert. [Source](https://github.com/scotthavird/havoptic.com)

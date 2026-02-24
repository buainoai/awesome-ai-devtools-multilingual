> **🌍 Languages / 语言选择:**
> [English](./README.en.md) | [中文](./README.zh.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 Outils de développement géniaux basés sur l'IA

Ceci est une liste organisée d'outils de développement basés sur l'IA. Ces outils exploitent l'IA pour aider les développeurs dans des tâches telles que la complétion de code, la refactorisation, le débogage, la documentation, et bien plus encore.

- [IDEs](#ides)
- [Clients Git](#git-clients)
- [Assistants](#assistants)
  - [Basés sur le Web](#web-based)
  - [Extensions d'IDE](#ide-extensions)
  - [Ligne de commande](#command-line)
  - [Bureau](#desktop)
- [Assistants Shell](#shell-assistants)
- [Agents](#agents)
- [Agents de PR](#pr-agents)
- [Générateurs d'applications](#app-generators)
- [Générateurs d'UI](#ui-generators)
- [Générateurs de snippets](#snippet-generators)
- [Documentation](#documentation)
- [Plugins OpenAI](#openai-plugins)
- [Recherche](#search)
- [Tests](#testing)
- [Évaluation](#evaluation)
- [Ressources](#resources)

## IDEs

- [Google Antigravity](https://antigravity.google/) — Un IDE axé sur les agents qui orchestre des agents IA autonomes pour planifier, exécuter et vérifier des tâches de codage complexes avec une intégration profonde du navigateur.
- [Crystal](https://github.com/stravu/crystal) — Un nouveau type d'environnement de développement pour gérer, inspecter et tester des sessions Claude Code parallèles.
- [Cursor](https://www.cursor.com/) — Un IDE avec des fonctionnalités de chat, d'édition, de génération et de débogage. Forké de VSCodium, donc l'interface est similaire à VS Code. Utilise OpenAI.
- [PearAI](https://trypear.ai/) — Un fork open source de VS Code avec chat et génération de code en ligne.
- [Melty](https://melty.sh/) — Un fork open source de VS Code avec chat intégré, aperçus des modifications et la possibilité d'écrire des commits avec l'IA. Actuellement, seul le code source est disponible.
- [Replit](https://replit.com/) — IDE basé sur le Web avec des environnements de développement cloud, la complétion de code, le chat, un agent de développement logiciel et des déploiements.
- [Mutable](https://github.com/mutableai/monitors4codegen) — IDE basé sur le Web, intégré à un chatbot et GitHub.
- [CodeStory](https://codestory.ai/) — Un IDE avec chat, explications de code, commits auto-générés et résumés de PR. Forké de VSCodium.
- [UI Pilot](https://ui-pilot.com/) — Éditeur de code IA basé sur le chat qui crée des formulaires à l'aide de Material UI, en utilisant GPT-4.
- [GitWit](https://gitwit.dev/) — Éditeur basé sur le Web pour la création d'applications ReactJS avec l'IA.
- [Windsurf](https://windsurf.com) — Un IDE avec des fonctionnalités de chat, d'édition, de génération et de débogage. Forké de VSCodium, donc l'interface est similaire à VS Code. Anciennement connu sous le nom de Codeium.
- [Theia IDE](https://theia-ide.org/#theiaide) — Un IDE open-source extensible (web et bureau) offrant des fonctionnalités basées sur l'IA comme le chat, la complétion de code, l'assistance terminale et des agents personnalisés utilisant des LLM arbitraires. Construit sur [Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/), une plateforme conçue pour permettre la création d'outils et d'IDE personnalisés basés sur l'IA.
- [OneCompiler](https://onecompiler.com/) — Un compilateur en ligne gratuit alimenté par l'IA prenant en charge plus de 70 langages, y compris Java, Python, MySQL, C++ et HTML, pour écrire, exécuter et partager du code.
- [trae](https://www.trae.ai/) — Trae est un IDE IA adaptatif qui transforme votre façon de travailler, collaborant avec vous pour aller plus vite.
- [Zed](https://zed.dev/) - Un éditeur de code multijoueur haute performance des créateurs d'Atom et Tree-sitter.
- [Nimbalyst](https://nimbalyst.com) - Un environnement de gestion d'agents pour Claude Code et Codex. Édition visuelle interactive de markdown, maquettes, excalidraw, code. Gestion de sessions parallèles.

## Clients Git

- [GitBrain](https://gitbrain.dev/) — Client Git qui simplifie le workflow Git. Divise les modifications de code, génère des résumés et des messages de commit pour les modifications de code. Utilise OpenAI.
- [GitButler](https://gitbutler.com/) — Client Git pour des branches simultanées en plus de votre workflow existant. Par défaut, utilise OpenAI, peut être changé en Perplexity pour générer des messages de commit conventionnels.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - Outil CLI qui utilise l'IA pour générer automatiquement des messages de commit Git et des descriptions de pull request de haute qualité.

## Assistants

### Basés sur le Web

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — Assistant intégré à [Replit](https://replit.com/) avec chat, débogage proactif et autocomplétion. Utilise OpenAI pour le chat et [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS) pour l'autocomplétion.
- [Unblocked](https://getunblocked.com/) — Augmente le code source avec les connaissances existantes pertinentes dans GitHub, Slack, Jira, Confluence, et plus encore. Obtenez des réponses via le chat et le contexte au niveau des fichiers de l'IDE. Disponible sur le Web, macOS, Slack, VSCode et les IDE JetBrains.
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — Assistant avec chat, refactorisation et génération de tests unitaires. Extensions pour VS Code et IntelliJ. Également disponible en tant qu'application web.
- [Magnet](https://www.magnet.run/) — Chatbot basé sur le Web avec des dépôts et des problèmes comme contexte.
- [Adrenaline](https://useadrenaline.com/) — Chatbot basé sur le Web utilisant l'IA et les AST pour répondre aux questions sur votre codebase.
- [CodeSquire](https://codesquire.ai/) — Extension Chrome qui ajoute l'autocomplétion à Google Colab, BigQuery et JupyterLab.
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — Assistant open source avec éditeur et interpréteur Python intégrés.
- [Onboard](https://www.getonboardai.com) — Discutez avec une IA sur des bases de code publiques et privées.
- [Code to Flow](https://codetoflow.com) — Visualisez, analysez et comprenez le code avec des organigrammes interactifs.
- [Pieces](https://pieces.app/) — Un copilote sur appareil qui vous aide à capturer, enrichir et réutiliser du code, à rationaliser la collaboration et à résoudre des problèmes complexes grâce à une compréhension contextuelle de votre workflow.
- [Wren AI](https://getwren.ai/oss) — Agent SQL AI pour obtenir des résultats et des informations plus rapidement en posant des questions sans écrire de SQL, et c'est open-source !
- [TEXT2SQL.AI](https://www.text2sql.ai/) — Générateur de requêtes SQL alimenté par l'IA. Traduisez, expliquez et corrigez des requêtes SQL complexes en utilisant un langage naturel.
- [SQLAI.ai](https://www.sqlai.ai/) — L'IA génère, corrige, explique et optimise les requêtes SQL. Possibilité d'ajouter votre propre schéma de base de données et d'entraîner l'IA à le comprendre.
- [CodeWP](https://codewp.ai/) — Chat IA et outils de codage spécifiquement entraînés pour les développeurs WordPress. Génération de code IA pour des snippets de code et des plugins dans WordPress.
- [Gru.ai](https://www.gru.ai/) — Un développeur IA peut vous aider à résoudre des problèmes techniques et à gérer les tâches de codage quotidiennes, telles que la création d'algorithmes, le débogage de problèmes, le test de solutions, la réponse à des questions de programmation, etc.

### Extensions d'IDE

- [GitHub Copilot](https://github.com/features/copilot) — Une extension VS Code avec chat, génération de texte de pull request et génération de tests unitaires.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — Agent de codage autonome pour VS Code qui peut créer/éditer des fichiers, exécuter des commandes et utiliser le navigateur avec l'autorisation de l'utilisateur. Prend en charge plusieurs fournisseurs d'IA, y compris OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure et GCP Vertex.
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — Assistant open source avec chat, complétion, refactorisation et réglage fin spécifique à la base de code. Extensions pour VS Code et JetBrains.
- [Continue](https://continue.dev/) — Extension VS Code avec chat, refactorisation et génération de code. Modifie plusieurs fichiers et exécute des commandes en votre nom.
- [Blackbox AI](https://www.useblackbox.io/) — Extension VS Code avec autocomplétion et chat incluant des liens vers des références de codage en ligne.
- [CodeGeeX](https://codegeex.cn/) — Assistant open source basé sur le LLM CodeGeeX avec chat, complétion et refactorisation. Extensions pour 9 éditeurs, y compris VS Code et PyCharm.
- [Quack AI](https://www.quackai.com/) — Extension VS Code pour adhérer aux directives de codage du projet.
- [Tabby](https://tabbyml.github.io/tabby/) — Assistant de complétion de code open source, auto-hébergé. Extensions pour VS Code et Vim.
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — Assistant de complétion de code open source, auto-hébergé. Extensions pour 15 éditeurs, y compris VS Code, IntelliJ, Neovim, Eclipse et PyCharm.
- [CodeMate](https://www.codemate.ai/) — Extension VS Code pour le débogage et l'optimisation de code.
- [AskCodi](https://www.askcodi.com/) — Assistant de codage IA avec extensions pour VS Code, JetBrains et Sublime Text.
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Assistant de chat open source pour la barre latérale de Visual Studio Code.
- [CodeComplete](https://codecomplete.ai/) — Assistant de complétion d'entreprise auto-hébergé.
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo est un agent IA qui vous permet de créer et de déployer des applications full-stack sans effort, avec un déploiement Vercel en un clic et une intégration Supabase transparente.
- [JetBrains AI](https://www.jetbrains.com/ai/) — Assistant IA disponible dans tous les IDE JetBrains.
- [aiXcoder](https://www.aixcoder.com/en/) — Assistant local ou basé sur le cloud avec extensions pour IntelliJ IDEA, CLion, GoLand, PyCharm, WebStorm, Visual Studio Code et Eclipse.
- [Sourcery](https://sourcery.ai/) — Assistant IA et linter avec une référence de 160 meilleures pratiques Python et plus de 40 meilleures pratiques JS/TS. Extensions pour VS Code, PyCharm, vim et Sublime.
- [Swimm](https://swimm.io) — Assistant pour la compréhension contextuelle du code utilisant l'analyse statique et la documentation générée par l'IA. VSCode, Jetbrains, IntelliJ, WebStorm, Rider, PhpStorm, Android Studio, PyCharm, PhPStorm
- [Supermaven](https://supermaven.com/) — Extension VS Code pour l'autocomplétion avec une fenêtre de contexte de 300 000 jetons.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — Assistant de codage IA avec extensions pour les IDE tels que VS Code et IntelliJ IDEA. Le plugin Amazon Q Developer IDE dispose d'un certain nombre d'agents qui peuvent également analyser le code pour mettre en évidence et définir les problèmes de sécurité (/review), écrire de la documentation (/doc), écrire des tests unitaires (/test) et vous aider à passer à des versions ultérieures de Java (/transform) (anciennement connu sous le nom d'Amazon CodeWhisperer)
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot est un assistant de codage alimenté par l'IA qui est étroitement intégré à Android Studio. Studio Bot peut aider les développeurs Android à générer du code, à trouver des ressources pertinentes, à apprendre les meilleures pratiques et à gagner du temps.
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z est un produit de modernisation d'applications mainframe alimenté par l'IA avec génération de code. Les fonctionnalités incluent la découverte et l'analyse d'applications, la refactorisation de code automatisée et la conversion COBOL vers Java.
- [EasyCode](https://www.easycode.ai/) — Extension VS Code avec chat GPT-4.
- [Kilo Code](https://kilocode.ai) - Assistant de codage IA Open Source pour planifier, construire et corriger du code dans VS Code.
- [FlyonUI MCP](https://flyonui.com/mcp) — Intégrez FlyonUI MCP - Tailwind AI Builder directement dans votre IDE et créez de superbes composants, blocs et pages Tailwind CSS inspirés de FlyonUI.
- [Traycer](https://traycer.ai) - Assistant de codage axé sur la planification dans VS Code.
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - Intégrez le serveur shadcn/studio MCP directement dans votre IDE préféré et créez de superbes composants, blocs et pages shadcn/ui inspirés de shadcn/studio.

### Ligne de commande

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - CLI qui fournit la complétion de commandes, la traduction de commandes utilisant l'IA générative pour traduire l'intention en commandes, et une interface de chat agentique complète avec gestion de contexte qui vous aide à écrire du code. Il fonctionne avec de nombreux terminaux et shells, sur MacOS, Linux et Windows (via wsl).
- [aloc](https://github.com/modern-tooling/aloc) — Un compteur de lignes de code moderne, augmenté par l'IA, construit avec Rust et Ratatui. Utilise des profils d'effort IA pour une estimation précise des projets.
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — Chatbot CLI avec dépôt comme contexte. Prend en charge OpenAI ainsi que les LLM exécutés localement via GPT4All.
- [gptcomet](https://github.com/belingud/gptcomet) — Outil CLI pour vous aider à générer des messages de commit et à examiner les modifications. Prend en charge plusieurs fournisseurs et langages.
- [poorcoder](https://github.com/vgrichina/poorcoder) — Une collection de scripts Bash pour extraire le contexte de code, appliquer les modifications à partir de markdown et générer des messages de commit IA tout en utilisant des LLM basés sur le Web.
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — Un outil auto-compilant qui transforme des piles de prompts basées sur markdown en code et tests à l'aide de la génération LLM. Fonctionne avec n'importe quel LLM via OpenRouter, y compris Claude, ChatGPT et Grok.
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - Transforme le langage naturel en commandes shell exécutables (ex. : `ai Tell me the free space on disk`)
- [promptext](https://github.com/1broseidon/promptext) — Extracteur de contexte de code intelligent pour les assistants IA avec comptage précis des jetons, priorisation de la pertinence et gestion du budget. Prépare un contexte de code optimisé dans les limites de jetons LLM.
- [Baz CLI](https://github.com/baz-scm/baz-cli) - CLI pour la révision de code assistée par l'IA, avec accès au code réel, au diff, etc.
- [AdaL](https://sylph.ai/) — Agent de codage IA auto-évolutif qui permet aux modèles de collaborer (Claude, GPT, Gemini). S'exécute localement, apprend les modèles de votre base de code.
- [Tokscale](https://github.com/junhoyeo/tokscale) — Outil CLI pour suivre l'utilisation des jetons des agents de codage IA (OpenCode, Claude Code, OpenClaw, Codex, Gemini CLI, Cursor IDE, AmpCode, Factory Droid) avec un classement mondial et des graphiques de contribution 2D/3D.
- [vsync](https://github.com/nicepkg/vsync) — Outil CLI qui synchronise les compétences, les serveurs MCP, les agents et les commandes entre Claude Code, Cursor, OpenCode et Codex avec conversion automatique de format (JSON ↔ TOML ↔ JSONC).
- [Arctic](https://github.com/arctic-cli/interface): Une TUI axée sur le terminal qui unifie plusieurs plans de codage IA et API avec une visibilité intégrée de l'utilisation et des quotas.

### Bureau

- [Memex](https://memex.tech/) — Construisez n'importe quoi dans n'importe quelle pile, avec juste du langage naturel, sur votre bureau.
- [Pieces](https://pieces.app/) — Application de bureau et extension de navigateur activées par l'IA conçues pour aider les développeurs à améliorer leur productivité.

## Assistants Shell

- [AskCommand](https://www.askcommand.cppexpert.online/) — Outil basé sur le Web pour générer automatiquement des commandes Unix à partir de texte à l'aide de l'IA.
- [Butterfish](https://butterfi.sh) — Outil CLI qui intègre ChatGPT dans votre shell pour un accès facile. Inclut des capacités agentiques simples.
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — Assistant CLI hautement configurable pour générer des commandes shell et obtenir des explications pour celles-ci.
- [GitFluence](https://www.gitfluence.com/) — Générateur de commandes Git basé sur le Web pour générer automatiquement des commandes Git pour le terminal ou la CLI à partir d'une description textuelle, en utilisant une solution basée sur l'IA pour suggérer les commandes Git les plus pertinentes.
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - Outil CLI qui ajoute des suggestions de ligne de commande alimentées par l'IA directement à votre terminal avec juste la touche <TAB><TAB> pour vous renvoyer les meilleures suggestions.
- [code-collator](https://github.com/tawandakembo/code-collator) — Outil CLI qui crée un seul fichier markdown décrivant l'intégralité de votre base de code aux modèles de langage. Utile pour l'assistance au codage IA depuis l'interface web Claude/ChatGPT plutôt que via l'API.
- [Warp](https://www.warp.dev/) - Warp rassemble l'IA et les connaissances de l'équipe dans un terminal unique, rapide et intuitif.
- [TmuxAI](https://tmuxai.dev/) - Assistant de terminal non intrusif alimenté par l'IA.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - Gérez des modèles/snippets de commandes avec des complétions dynamiques et une intégration IA.

## Agents

- [Smol Developer](https://github.com/smol-ai/developer) — Agent CLI qui génère un dépôt à partir d'un prompt. Utilise OpenAI et Anthropic.
- [Aider](https://github.com/paul-gauthier/aider) — Assistant CLI et agent qui génère des modifications et des commits vers des dépôts. Utilise OpenAI.
- [Blinky](https://github.com/seahyinghang8/blinky) — Un agent de débogage pour VS Code qui aide à identifier et à corriger les erreurs backend, inspiré par SWE-agent.
- [Mentat](https://www.mentat.ai/) — Assistant CLI et agent qui apporte des modifications aux dépôts.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — Agent CLI qui génère un dépôt à partir d'un prompt et pose des questions de clarification.
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — Agent CLI qui convertit une application full-stack d'un langage ou framework à un autre. Utilise le contexte GPT-4 32k.
- [Grit](https://app.grit.io) — Agent intégré à GitHub pour automatiser les tâches de maintenance et autres travaux de développement.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Générateur d'applications Auto Gen-AI avec la puissance de Llama 2.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT : Solution d'automatisation du développement logiciel basée sur l'IA.
- [Second.dev](https://www.second.dev/) — Une plateforme pour ajouter des fonctionnalités aux applications full-stack.
- [Factory](https://www.factory.ai/) — Agents pour la génération de code. Liste d'attente.
- [sudocode](https://sudocode.ai/) — Un assistant de chat basé sur le Web pour générer des projets, similaire à Code Interpreter.
- [CodeFlash AI](https://www.codeflash.ai/) — Un outil CLI et CI pour optimiser le code Python à l'aide de l'IA.
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — Un agent IA qui écrit et corrige du code pour vous.
- [Fine](https://fine.dev/?ref=awesome) — Environnement de développement IA pour automatiser le travail fastidieux. Intègre GitHub, Sentry, Linear. Obtient des réponses contextuelles aux questions. Planifie, conçoit et implémente des changements. Automatise le CI/CD auto-réparateur.
- [Potpie](https://potpie.ai) — Agents IA Open Source pour votre base de code en quelques minutes. Utilisez des agents pré-construits pour les questions-réponses, les tests, le débogage et la conception de systèmes ou créez vos propres agents dédiés.
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — Serveur MCP sans configuration qui unifie plusieurs assistants de codage IA grâce à une auto-découverte intelligente et une interface standardisée.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Outil de codage agentique d'Anthropic.
- [Open Agent](https://github.com/Th0rgal/openagent) — Plan de contrôle auto-hébergé pour Claude Code avec des espaces de travail conteneurisés isolés et un streaming de mission en temps réel.
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — Framework multi-agents auto-itératif, piloté par les spécifications, pour Claude Code avec des agents spécialisés coordonnés (Python, Next.js, CI/CD, QA, UI Testing).
- [Leap.new](https://leap.new/) - Il construit des applications fonctionnelles avec de vrais services backend, des API, et se déploie sur votre cloud.
- [Recurse ML](https://recurse.ml) - Trouve les bugs dans le code généré par l'IA.
- [Zenable](https://zenable.io/) — Garde-fous IA qui apprennent les standards de votre équipe et garantissent que les agents de codage les suivent, maximisant la vitesse et la qualité.
- [Trellis](https://github.com/mindfold-ai/Trellis) - Framework et boîte à outils IA tout-en-un pour Claude Code et Cursor. Gère les tâches, les spécifications et les pipelines multi-agents.

## Agents de PR

- [Greptile](https://greptile.com/code-review-bot) — Bot IA qui examine les PR dans GitHub/Gitlab avec un contexte complet de la base de code.
- [Macroscope](https://macroscope.com/code-review) - Revue de code alimentée par l'IA pour GitHub qui utilise les AST pour construire une représentation graphique de votre base de code et extrait le contexte de vos systèmes de gestion des problèmes.
- [EntelligenceAI](https://entelligence.ai/pr) — Revues de code alimentées par l'IA pour Github et Gitlab qui s'améliorent avec le temps en fonction des commentaires des utilisateurs.
- [Sweep](https://github.com/sweepai/sweep) — Développeur junior IA : intégration GitHub pour générer, tester et auto-réviser les pull requests à partir des problèmes.
- [Codegen](https://www.codegen.com/) — Agent de PR basé sur GPT-4 pour les bases de code d'entreprise.
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — Un outil open source pour la révision des PR. Fonctionne comme une action GitHub, une CLI Gitlab ou localement.
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — Outil open source pour les revues de code automatisées. Qodo était anciennement connu sous le nom de Codium (à ne pas confondre avec Codeium avec un "E").
- [Nova](https://www.trynova.ai/) — Bot CI pour ajouter des actions telles que des résumés et des tests aux nouvelles PR.
- [CodeRabbit](https://coderabbit.ai/) — CI personnalisable pour ajouter des résumés et des suggestions de code aux PR.
- [SwePT](https://github.com/keerthanpg/SwePT) — Générateur de PR open source écrit en 150 lignes de code Python.
- [Duckie](https://duckie.ai/) — Un assistant de chat basé sur le Web pour modifier les dépôts GitHub.
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — Une intégration GitHub qui ajoute du texte explicatif aux PR nouvellement créées.
- [Goast](https://goast.ai/) — Un outil hébergé qui ingère vos journaux d'erreurs et suggère des corrections.
- [Corgea](https://corgea.com/) — Une intégration GitHub qui trouve et corrige le code vulnérable.
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — Une intégration GitHub axée sur la génération d'UI avec un support intégré pour shadcn, lucide et les graphiques nivo.
- [Pixee](https://pixee.ai) — Pixeebot trouve les problèmes de sécurité et de qualité du code dans votre code et crée des pull requests prêtes à être fusionnées avec les corrections recommandées.
- [CodeAnt AI](https://www.codeant.ai/) — Crée automatiquement des PR pour corriger les problèmes de code.
- [What The Diff](https://whatthediff.ai/) — Application alimentée par l'IA qui examine le diff des pull requests et écrit un commentaire descriptif sur les changements en langage clair.
- [Trag](https://usetrag.com/) — Revues de code alimentées par l'IA avec des instructions et des modèles prédéfinis.
- [CodeReviewBot](https://codereviewbot.ai/) — Revues de code alimentées par l'IA pour GitHub.
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — Réviseur de PR alimenté par l'IA pour GitHub, conçu pour identifier les bugs, les problèmes de sécurité et les goulots d'étranglement de performance.
- [Matter AI](https://matterai.dev) - Réviseur de code IA Open Source pour aider les équipes d'ingénieurs à publier du code en toute confiance.
- [Gito](https://github.com/Nayjest/Gito) - Réviseur de code IA qui fonctionne avec n'importe quel modèle de langage, localement ou dans GitHub Actions.
- [Baz](https://baz.co) - Réviseur de code IA adapté aux directives et conventions de votre équipe. Personnalisable, adaptable, réactif et intégré au reste des outils de développement pour le contexte.

## Générateurs d'applications

- [Pico](https://picoapps.xyz) — Générateur de micro-applications de bout en bout avec déploiement instantané.
- [Co.dev](https://www.co.dev/) — Plateforme de développement d'applications alimentée par l'IA qui aide à construire et à déployer des applications full-stack.
- [SoftGen](https://softgen.ai/) — Plateforme de génération de logiciels alimentée par l'IA pour la création d'applications Web.
- [LlamaCoder](https://llamacoder.together.ai/) — Modèle de génération de code open source pour la création d'applications utilisant des LLM open source.
- [e2b_Fragments](https://fragments.e2b.dev/) — Plateforme pour la création et le déploiement d'applications alimentées par l'IA avec des environnements sandboxés.
- [Bolt.new](https://bolt.new) — Agent de développement web alimenté par l'IA qui vous permet de prototyper, exécuter, éditer et déployer des applications full-stack directement dans le navigateur à l'aide de WebContainers. Prend en charge les packages npm, les serveurs Node.js et les API tierces.
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Version open source de Bolt.new qui prend en charge plusieurs fournisseurs LLM, y compris Groq, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek.
- [Srcbook](https://github.com/srcbookdev/srcbook) — Plateforme de développement d'applications centrée sur TypeScript avec un constructeur d'applications IA et un notebook TypeScript.
- [Capacity](https://capacity.so) — Développement d'applications web full-stack alimenté par l'IA qui transforme un prompt en langage naturel en applications web entièrement fonctionnelles.
- [Lovable](https://lovable.dev/) — Plateforme de développement d'applications full-stack alimentée par l'IA qui convertit des descriptions en langage naturel ou des conceptions en applications entièrement fonctionnelles avec déploiement intégré et intégration GitHub.
- [Literally anything](https://literallyanything.io) — Générateur d'applications web HTML et JavaScript.
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — Génère une application full-stack React/Node.js/Prisma/Wasp à partir d'une courte description.
- [Make Real](https://makereal.tldraw.com/) — Canevas en ligne qui peut être utilisé pour générer des applications HTML/JavaScript.
- [Marblism](https://marblism.com) — Génère un boilerplate SaaS à partir d'un prompt.
- [Glowbom](https://glowbom.com/) — Génère des applications avec l'IA et exporte vers plusieurs plateformes.
- [Mage](https://usemage.ai/) — Génère des applications web full-stack en Wasp, React, Node.js et Prisma.
- [ScrollHub](https://hub.scroll.pub/) — Génère et publie des sites web en utilisant le langage de programmation Scroll.
- [Taskade Genesis](https://taskade.com/genesis) — Plateforme alimentée par l'IA pour créer des agents IA personnalisés, des workflows et des applications en utilisant le langage naturel. Support multi-modèles (GPT-4o, Claude, Gemini), serveur MCP open-source.

- [Berrry](https://berrry.app) — Générateur d'applications Twitter qui transforme les publications de médias sociaux en applications web fonctionnelles. Transforme les tweets et le contenu Reddit en applications complètes avec des sous-domaines uniques.
- [Blank Space](https://www.blankspace.build/) — Constructeur d'applications IA open source pour créer des applications web en utilisant le langage naturel. Alternative auto-hébergeable à v0, Lovable et Bolt.
- [Fastshot](https://fastshot.ai/) — Plateforme sans code pilotée par l'IA pour la création et le déploiement d'applications mobiles.

## Générateurs d'UI

- [v0](https://v0.dev/) — Créez et itérez de nouveaux composants d'interface utilisateur dans votre navigateur.
- [Rendition Create ](https://www.renditioncreate.com/) — Créez et itérez de nouveaux composants d'interface utilisateur dans votre navigateur.
- [Rapidpages](https://github.com/rapidpages/rapidpages) — Générateur d'UI open source.
- [Magic Patterns](https://www.magicpatterns.com/) — Prototypez vos idées de produits. Site web de générateur d'UI où vous pouvez donner des prompts, télécharger des images ou importer de l'inspiration de design avec leur [extension Chrome](https://www.magicpatterns.com/extension). Peut exporter vers Figma avec un [plugin](https://www.figma.com/community/plugin/1304255855834420274). Prend en charge un certain nombre de systèmes de composants, y compris Shadcn, ChakraUI et HTML + Tailwind.
- [Tempo ](https://www.tempolabs.ai/) — Éditeur WYSIWYG pour les interfaces React.
- [Kombai](https://kombai.com/) — Outil IA pour générer du code frontend à partir de Figma.
- [CodeParrot](https://www.codeparrot.ai/) — Plugin VS Code pour générer du code Frontend à partir de Figma. Réutilise les composants, bibliothèques et normes de codage existants pour générer du code qui s'intègre parfaitement à votre base de code existante. Le tout sans aucun prompt.
- [Galileo AI](https://www.usegalileo.ai/) — Une plateforme texte-vers-UI. Liste d'attente.
- [Uizard](https://uizard.io/) — Générez des maquettes multi-écrans à partir de prompts textuels et éditez-les avec un éditeur glisser-déposer. Scannez des captures d'écran d'applications ou des wireframes dessinés à la main et transformez-les en maquettes d'applications éditables.
- [Frontly](https://fronty.com/) — Convertit l'image téléchargée en code HTML CSS.
- [BoringUi](https://www.boringui.xyz/) — Créez de belles interfaces utilisateur à l'aide de vos données JSON. L'interface utilisateur générée est en HTML et Tailwind CSS avec du code qui peut être copié et l'interface utilisateur peut être partagée avec n'importe qui à l'aide de liens.
- [CSS Picker](https://csspicker.dev/) - Copiez l'UI d'un design existant et itérez avec l'IA, prend en charge la copie de CSS à partir d'un site web (par [CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)), l'image vers le code et le texte vers l'UI.

## Générateurs de snippets

- [CodePal](https://codepal.ai/) — Un outil web pour générer ou refactoriser rapidement du code.
- [AI Code Convert](https://aicodeconvert.com/) — Un outil web pour traduire du code entre langages de programmation.
- [AI Code Playground](https://aicodeplayground.com/) — Un outil web pour refactoriser et améliorer le code.
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex utilise le GPT-3 d'OpenAI pour produire des expressions régulières à partir d'un langage naturel.
- [unpkg.ai](https://unpkg.ai/) — Service de génération de modules ESM alimenté par l'IA open source. Générez des modules JavaScript via URL pour un prototypage rapide.

## Documentation

- [Trelent](https://trelent.net/) — Une extension VS Code pour générer des docstrings. Utilise des modèles propriétaires.
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT est une application web gratuite basée sur l'IA qui convertit un schéma, une définition d'infrastructure, un extrait de code ou une description en langage clair en diagrammes. L'outil peut générer des organigrammes, des diagrammes d'entité-relation, des diagrammes d'architecture cloud et des diagrammes de séquence.
- [DocuWriter.ai](https://www.docuwriter.ai/) — Application web alimentée par l'IA pour générer automatiquement de la documentation de code et d'API à partir de vos fichiers de code source.
- [README-AI](https://github.com/eli64s/readme-ai) — Générateur de fichier README.md automatisé, alimenté par les API de grands modèles de langage.
- [Supacodes](https://www.supacodes.com) — Un outil IA qui automatise l'écriture et la mise à jour de la documentation de code dans Github.
- [CodexAtlas](https://codedocumentation.app/) — Documentation de code et d'API automatisée utilisant les derniers modèles d'IA.

## Observabilité

- [TraceRoot AI](https://traceroot.ai/) - Un outil d'observabilité natif de l'IA qui utilise des agents IA pour corriger automatiquement vos bugs de production.

## Plugins OpenAI

- [ChatWithGit](https://gitsearch.sdan.io/) — Permet à ChatGPT de rechercher sur GitHub et de renvoyer des liens vers des dépôts pertinents.
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — Exemple open source d'un plugin ChatGPT qui extrait le contexte d'un répertoire de fichiers.

## Recherche

- [Bloop](https://bloop.ai/) — Recherche en langage naturel pour les dépôts.
- [Buildt](https://www.buildt.ai/) — Recherche en langage naturel pour les dépôts. Liste d'attente.
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — Un outil de recherche local exploitant les embeddings vectoriels pour rechercher sémantiquement votre base de code.
- [ContextMCP](https://contextmcp.ai) — Recherche sémantique auto-hébergée dans la documentation de diverses sources pour les agents IA.

## Tests

- [Checksum AI](https://checksum.ai) — Agent d'automatisation QA entièrement autonome de bout en bout qui génère des tests Playwright prêts pour le CI/CD directement dans le dépôt.
- [OctoMind](https://octomind.dev) — Auto-maintenance et tests de bout en bout générés par navigateur intégrés à Github Actions, Azure DevOps et plus encore.
- [Traceloop](https://traceloop.com/) — Utilise les données de traçage OpenTelemetry avec l'IA générative pour améliorer la fiabilité du système.
- [Carbonate](https://carbonate.dev/) — Tests de bout en bout utilisant le langage naturel. S'intègre à votre suite de tests existante (actuellement Jest, PHPUnit et unittest de Python).
- [Meticulous.ai](https://www.meticulous.ai/) — Tests de bout en bout générés et maintenus automatiquement : à mesure que votre application évolue, votre suite de tests aussi.
- [DiffBlue](https://www.diffblue.com/) — Tests unitaires générés automatiquement pour Java.
- [Qodo](https://www.qodo.ai/) — Génération de tests non triviaux avec prise en charge des principaux langages de programmation. Extensions pour VS Code et JetBrains. (anciennement Codium)
- [DeepUnit](https://www.deepunit.ai/) — Cas de test réfléchis et génération de fichiers de tests unitaires complets. Disponible en tant qu'extension VS Code interactive, package npm, CLI ou pipeline CI/CD.
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — Accélère la productivité des développeurs et la sécurité du code en trouvant les vulnérabilités dans le code et en générant des tests pour celles-ci. Open Source et disponible en tant que CLI ou pipeline CI/CD.
- [KushoAI](https://kusho.ai/) — Agent IA pour les tests d'API qui transforme vos collections Postman, spécifications OpenAPI, commandes curl, etc. en suites de tests exhaustives qui s'intègrent à votre pipeline CI/CD.
- [Test Gru](https://gru.ai/home#test-gru) — Fournit des services d'automatisation de tests unitaires de niveau entreprise.

- [AgentsKB](https://agentskb.com) - Couche de connaissances expertes pour les assistants IA. Votre IA cherche, nous recherchons. C'est la différence.

## Évaluation

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — Suite de benchmarks pour évaluer les agents de codage. Comparez les configurations, suivez les métriques et effectuez des tests A/B avec de vrais problèmes de vos dépôts.

## Ressources

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — Tutoriels approfondis organisés pour les projets d'outils d'IA et de développement open source.
- [Havoptic](https://havoptic.com/) — Suivi gratuit et open source des versions des outils de codage IA. Mis à jour automatiquement quotidiennement. [Source](https://github.com/scotthavird/havoptic.com)

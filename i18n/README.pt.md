> **🌍 语言 / Languages:**
> [中文](./README.zh.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 Ferramentas de Desenvolvimento Incríveis com IA

Esta é uma lista selecionada de ferramentas de desenvolvimento com IA. Essas ferramentas utilizam IA para auxiliar desenvolvedores em tarefas como conclusão de código, refatoração, depuração, documentação e muito mais.

- [IDEs](#ides)
- [Clientes Git](#git-clients)
- [Assistentes](#assistants)
  - [Baseados na Web](#web-based)
  - [Extensões de IDE](#ide-extensions)
  - [Linha de Comando](#command-line)
  - [Desktop](#desktop)
- [Assistentes de Shell](#shell-assistants)
- [Agentes](#agents)
- [Agentes de PR](#pr-agents)
- [Geradores de Aplicativos](#app-generators)
- [Geradores de UI](#ui-generators)
- [Geradores de Snippets](#snippet-generators)
- [Documentação](#documentation)
- [Plugins OpenAI](#openai-plugins)
- [Pesquisa](#search)
- [Testes](#testing)
- [Avaliação](#evaluation)
- [Recursos](#resources)

## IDEs

- [Google Antigravity](https://antigravity.google/) — Uma IDE focada em agentes que orquestra agentes de IA autônomos para planejar, executar e verificar tarefas de codificação complexas com profunda integração de navegador.
- [Crystal](https://github.com/stravu/crystal) — Um novo tipo de ambiente de desenvolvimento para gerenciar, inspecionar e testar sessões paralelas do Claude Code.
- [Cursor](https://www.cursor.com/) — Uma IDE com recursos de chat, edição, geração e depuração. Bifurcada do VSCodium, então a interface é semelhante ao VS Code. Usa OpenAI.
- [OpenMagic](https://github.com/Kalmuraee/OpenMagic) — AI-powered coding toolbar for any web app. Captures element context, previews diffs, and applies approved changes through a reverse proxy.
- [PearAI](https://trypear.ai/) — Um fork de código aberto do VS Code com chat e geração de código inline.
- [Melty](https://melty.sh/) — Um fork de código aberto do VS Code com chat integrado, pré-visualizações de alterações e capacidade de escrever commits com IA. Atualmente, apenas o código-fonte está disponível.
- [Replit](https://replit.com/) — IDE baseada na web com ambientes de desenvolvimento em nuvem, conclusão de código, chat, um agente de desenvolvimento de software e implantações.
- [Mutable](https://github.com/mutableai/monitors4codegen) — IDE baseada na web, integrada com um chatbot e GitHub.
- [CodeStory](https://codestory.ai/) — Uma IDE com chat, explicações de código, commits gerados automaticamente e resumos de PR. Bifurcada do VSCodium.
- [UI Pilot](https://ui-pilot.com/) — Editor de código AI baseado em chat que cria formulários usando Material UI, utilizando GPT-4.
- [GitWit](https://gitwit.dev/) — Editor baseado na web para construir aplicativos ReactJS com IA.
- [Windsurf](https://windsurf.com) — Uma IDE com recursos de chat, edição, geração e depuração. Bifurcada do VSCodium, então a interface é semelhante ao VS Code. Anteriormente conhecido como Codeium.
- [Theia IDE](https://theia-ide.org/#theiaide) — Uma IDE extensível de código aberto (web e desktop) que oferece recursos baseados em IA como chat, conclusão de código, assistência de terminal e agentes personalizados usando LLMs arbitrários. Construída sobre [Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/), uma plataforma projetada para permitir a criação de ferramentas e IDEs personalizados e alimentados por IA.
- [OneCompiler](https://onecompiler.com/) — Um compilador online gratuito com IA que suporta mais de 70 linguagens, incluindo Java, Python, MySQL, C++ e HTML, para escrever, executar e compartilhar código.
- [trae](https://www.trae.ai/) — Trae é uma IDE de IA adaptativa que transforma a maneira como você trabalha, colaborando com você para operar mais rapidamente.
- [Zed](https://zed.dev/) - Um editor de código multiplayer de alto desempenho dos criadores de Atom e Tree-sitter.
- [Nimbalyst](https://nimbalyst.com) - Um ambiente de gerenciamento de agentes para Claude Code e Codex. Edição visual interativa de markdown, mockups, excalidraw, código. Gerenciamento de sessões paralelas.

## Clientes Git

- [GitBrain](https://gitbrain.dev/) — Cliente Git que simplifica o fluxo de trabalho Git. Divide as alterações de código, gera resumos e mensagens de commit para as alterações de código. Usa OpenAI.
- [GitButler](https://gitbutler.com/) — Cliente Git para branches simultâneos em cima do seu fluxo de trabalho existente. Padrão para OpenAI, pode ser alterado para Perplexity para gerar mensagens de commit convencionais.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - Ferramenta CLI que usa IA para gerar automaticamente mensagens de commit Git e descrições de pull request de alta qualidade.

## Assistentes

### Baseados na Web

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — Assistente integrado ao [Replit](https://replit.com/) com chat, depuração proativa e autocompletar. Usa OpenAI para chat e [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS) para autocompletar.
- [Unblocked](https://getunblocked.com/) — Aumente o código-fonte com conhecimento existente relevante no GitHub, Slack, Jira, Confluence e muito mais. Obtenha respostas através de chat e contexto de arquivo no IDE. Disponível na web, macOS, Slack, VSCode e IDEs JetBrains.
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — Assistente com chat, refatoração e geração de testes de unidade. Extensões para VS Code e IntelliJ. Também disponível como aplicativo web.
- [Magnet](https://www.magnet.run/) — Chatbot baseado na web com repositórios e issues como contexto.
- [Adrenaline](https://useadrenaline.com/) — Chatbot baseado na web usando IA e ASTs para responder perguntas sobre sua base de código.
- [CodeSquire](https://codesquire.ai/) — Extensão do Chrome que adiciona autocompletar ao Google Colab, BigQuery e JupyterLab.
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — Assistente de código aberto com editor e interpretador Python integrados.
- [Onboard](https://www.getonboardai.com) — Converse com uma IA sobre bases de código públicas e privadas.
- [Code to Flow](https://codetoflow.com) — Visualize, analise e entenda o código com fluxogramas interativos.
- [Pieces](https://pieces.app/) — Um copilot no dispositivo que ajuda você a capturar, enriquecer e reutilizar código, otimizar a colaboração e resolver problemas complexos através de uma compreensão contextual do seu fluxo de trabalho.
- [Wren AI](https://getwren.ai/oss) — Agente de IA SQL para obter resultados e insights mais rapidamente, fazendo perguntas sem escrever SQL, e é de código aberto!
- [TEXT2SQL.AI](https://www.text2sql.ai/) — Construtor de consultas SQL com IA. Traduza, explique e corrija consultas SQL complexas usando linguagem natural.
- [SQLAI.ai](https://www.sqlai.ai/) — A IA gera, corrige, explica e otimiza consultas SQL. Capacidade de adicionar seu próprio esquema de banco de dados e treinar a IA para entendê-lo.
- [CodeWP](https://codewp.ai/) — Ferramentas de chat e codificação de IA especificamente treinadas para desenvolvedores WordPress. Geração de código AI para snippets de código e plugins no WordPress.
- [Gru.ai](https://www.ai/) — Um desenvolvedor de IA pode ajudá-lo a resolver problemas técnicos e lidar com tarefas diárias de codificação, como construir algoritmos, depurar problemas, testar soluções, responder a perguntas de programação, etc.

### Extensões de IDE

- [GitHub Copilot](https://github.com/features/copilot) — Uma extensão do VS Code com chat, geração de texto para pull request e geração de testes de unidade.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — Agente de codificação autônomo para VS Code que pode criar/editar arquivos, executar comandos e usar o navegador com permissão do usuário. Suporta vários provedores de IA, incluindo OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure e GCP Vertex.
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — Assistente de código aberto com chat, conclusão, refatoração e ajuste fino específico da base de código. Extensões para VS Code e JetBrains.
- [Continue](https://continue.dev/) — Extensão do VS Code com chat, refatoração e geração de código. Edita vários arquivos e executa comandos em seu nome.
- [Blackbox AI](https://www.useblackbox.io/) — Extensão do VS Code com autocompletar e chat, incluindo links para referências de codificação online.
- [CodeGeeX](https://codegeex.cn/) — Assistente de código aberto baseado no LLM CodeGeeX com chat, conclusão e refatoração. Extensões para 9 editores, incluindo VS Code e PyCharm.
- [Quack AI](https://www.quackai.com/) — Extensão do VS Code para aderir às diretrizes de codificação do projeto.
- [Tabby](https://tabbyml.github.io/tabby/) — Assistente de conclusão de código de código aberto e auto-hospedado. Extensões para VS Code e Vim.
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — Assistente de conclusão de código de código aberto e auto-hospedado. Extensões para 15 editores, incluindo VS Code, IntelliJ, Neovim, Eclipse e PyCharm.
- [CodeMate](https://www.codemate.ai/) — Extensão do VS Code para depurar e otimizar código.
- [AskCodi](https://www.askcodi.com/) — Assistente de codificação de IA com extensões para VS Code, JetBrains e Sublime Text.
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Assistente de chat de código aberto para a barra lateral do Visual Studio Code.
- [CodeComplete](https://codecomplete.ai/) — Assistente de conclusão empresarial auto-hospedado.
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo é um agente de IA que permite construir e implantar aplicativos full-stack sem esforço, com implantação Vercel com um clique e integração perfeita com Supabase.
- [JetBrains AI](https://www.jetbrains.com/ai/) — Assistente de IA disponível em todas as IDEs JetBrains.
- [aiXcoder](https://www.aixcoder.com/en/) — Assistente local ou baseado em nuvem com extensões para IntelliJ IDEA, CLion, GoLand, PyCharm, WebStorm, Visual Studio Code e Eclipse.
- [Sourcery](https://sourcery.ai/) — Assistente de IA e linter com uma referência de 160 melhores práticas Python e mais de 40 melhores práticas JS/TS. Extensões para VS Code, PyCharm, vim e Sublime.
- [Swimm](https://swimm.io) — Assistente para compreensão contextual de código usando análise estática e documentação gerada por IA. VSCode, Jetbrains, IntelliJ, WebStorm, Rider, PhpStorm, Android Studio, PyCharm, PhPStorm.
- [Supermaven](https://supermaven.com/) — Extensão do VS Code para autocompletar com janela de contexto de 300.000 tokens.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — Assistente de codificação de IA com extensões para IDEs como VS Code e IntelliJ IDEA. O plugin Amazon Q Developer IDE possui vários Agentes que também podem escanear código para destacar e definir problemas de segurança (/review), escrever documentação (/doc), escrever testes de unidade (/test) e ajudar a atualizar para versões posteriores do Java (/transform) (anteriormente conhecido como Amazon CodeWhisperer).
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot é um assistente de codificação com IA que está totalmente integrado ao Android Studio. O Studio Bot pode ajudar os desenvolvedores Android a gerar código, encontrar recursos relevantes, aprender as melhores práticas e economizar tempo.
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z é um produto de modernização de aplicativos mainframe com IA e geração de código. Os recursos incluem descoberta e análise de aplicativos, refatoração automatizada de código e conversão de COBOL para Java.
- [EasyCode](https://www.easycode.ai/) — Extensão do VS Code com chat GPT-4.
- [Kilo Code](https://kilocode.ai) - Assistente de codificação de IA de código aberto para planejar, construir e corrigir código dentro do VS Code.
- [FlyonUI MCP](https://flyonui.com/mcp) — Integre o FlyonUI MCP - Tailwind AI Builder diretamente em sua IDE e crie componentes, blocos e páginas Tailwind CSS impressionantes inspirados no FlyonUI.
- [Traycer](https://traycer.ai) - Assistente de Codificação Plan-First no VS Code.
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - Integre o shadcn/studio MCP Server diretamente em sua IDE favorita e crie componentes, blocos e páginas shadcn/ui impressionantes inspirados no shadcn/studio.

### Linha de Comando

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - CLI que oferece conclusão de comandos, tradução de comandos usando IA generativa para traduzir intenções em comandos, e uma interface de chat agêntica completa com gerenciamento de contexto que ajuda a escrever código. Funciona com muitos terminais e shells, em MacOS, Linux e Windows (via wsl).
- [aloc](https://github.com/modern-tooling/aloc) — Um contador de linhas de código moderno, aumentado por IA, construído com Rust e Ratatui. Usa perfis de esforço de IA para estimativas precisas de projetos.
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — Chatbot CLI com repositório como contexto. Suporta OpenAI, bem como LLMs executados localmente via GPT4All.
- [gptcomet](https://github.com/belingud/gptcomet) — Ferramenta CLI para ajudar a gerar mensagens de commit e revisar alterações. Suporta múltiplos provedores e idiomas.
- [poorcoder](https://github.com/vgrichina/poorcoder) — Uma coleção de scripts Bash para extrair contexto de código, aplicar alterações de markdown e gerar mensagens de commit de IA usando LLMs baseados na web.
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — Uma ferramenta de auto-compilação que transforma pilhas de prompts baseadas em markdown em código e testes usando geração LLM. Funciona com qualquer LLM via OpenRouter, incluindo Claude, ChatGPT e Grok.
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - Transforma linguagem natural em comandos de shell executáveis (ex.: `ai Tell me the free space on disk`).
- [promptext](https://github.com/1broseidon/promptext) — Extrator inteligente de contexto de código para assistentes de IA com contagem precisa de tokens, priorização de relevância e gerenciamento de orçamento. Prepara contexto de código otimizado dentro dos limites de tokens do LLM.
- [Baz CLI](https://github.com/baz-scm/baz-cli) - CLI para revisão de código assistida por IA, com acesso ao código real, diff, etc.
- [AdaL](https://sylph.ai/) — Agente de codificação de IA auto-evolutivo que permite que modelos colaborem (Claude, GPT, Gemini). Executa localmente, aprende os padrões da sua base de código.
- [Tokscale](https://github.com/junhoyeo/tokscale) — Ferramenta CLI para rastrear o uso de tokens de agentes de codificação de IA (OpenCode, Claude Code, OpenClaw, Codex, Gemini CLI, Cursor IDE, AmpCode, Factory Droid) com um placar global e gráficos de contribuição 2D/3D.
- [vsync](https://github.com/nicepkg/vsync) — Ferramenta CLI que sincroniza Skills, servidores MCP, Agentes e Comandos entre Claude Code, Cursor, OpenCode e Codex com conversão automática de formato (JSON ↔ TOML ↔ JSONC).
- [Arctic](https://github.com/arctic-cli/interface): Uma TUI terminal-first que unifica múltiplos planos de codificação de IA e APIs com visibilidade de uso e cota integrada.

### Desktop

- [Memex](https://memex.tech/) — Construa qualquer coisa em qualquer stack, apenas com linguagem natural, em seu desktop.
- [Pieces](https://pieces.app/) — Aplicativo de desktop e extensão de navegador habilitados para IA, projetados para auxiliar desenvolvedores a aumentar a produtividade.

## Assistentes de Shell

- [AskCommand](https://www.askcommand.cppexpert.online/) — Ferramenta baseada na web para gerar comandos Unix a partir de texto automaticamente usando IA.
- [Butterfish](https://butterfi.sh) — Ferramenta CLI que incorpora o ChatGPT em seu shell para fácil acesso. Inclui capacidades agênticas simples.
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — Assistente CLI altamente configurável para gerar comandos de shell e obter explicações para eles.
- [GitFluence](https://www.gitfluence.com/) — Gerador de comandos Git baseado na web para gerar automaticamente comandos Git para terminal ou CLI a partir de uma descrição de texto, usando uma solução orientada por IA para sugerir os comandos Git mais relevantes.
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - Ferramenta CLI que adiciona sugestões de linha de comando com IA diretamente ao seu terminal, basta digitar <TAB><TAB> para retornar as principais sugestões para você.
- [code-collator](https://github.com/tawandakembo/code-collator) — Ferramenta CLI que cria um único arquivo markdown que descreve toda a sua base de código para modelos de linguagem. Útil para assistência de codificação de IA da interface web do Claude/ChatGPT, em vez de via API.
- [Warp](https://www.warp.dev/) - Warp reúne IA e conhecimento da equipe em um terminal único, rápido e intuitivo.
- [TmuxAI](https://tmuxai.dev/) - Assistente de terminal não intrusivo com IA.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - Gerencie modelos/snippets de comandos com preenchimentos dinâmicos e integração com IA.

## Agentes

- [Smol Developer](https://github.com/smol-ai/developer) — Agente CLI que gera um repositório a partir de um prompt. Usa OpenAI e Anthropic.
- [Aider](https://github.com/paul-gauthier/aider) — Assistente CLI e agente que gera alterações e commits para repositórios. Usa OpenAI.
- [Blinky](https://github.com/seahyinghang8/blinky) — Um agente de depuração para VS Code que ajuda a identificar e corrigir erros de backend, inspirado no SWE-agent.
- [Mentat](https://www.mentat.ai/) — Assistente CLI e agente que faz alterações em repositórios.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — Agente CLI que gera um repositório a partir de um prompt e faz perguntas esclarecedoras.
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — Agente CLI que converte um aplicativo full-stack de uma linguagem ou framework para outro. Usa contexto GPT-4 32k.
- [Grit](https://app.grit.io) — Agente integrado ao GitHub para automatizar tarefas de manutenção e outros trabalhos de desenvolvimento.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Gerador de aplicativos Auto Gen-AI com o poder do Llama 2.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT: Solução de Automação de Desenvolvimento de Software Orientada por IA.
- [Second.dev](https://www.second.dev/) — Uma plataforma para adicionar recursos a aplicativos full-stack.
- [Factory](https://www.factory.ai/) — Agentes para geração de código. Lista de espera.
- [sudocode](https://sudocode.ai/) — Um assistente de chat baseado na web para gerar projetos, semelhante ao Code Interpreter.
- [CodeFlash AI](https://www.codeflash.ai/) — Uma ferramenta CLI e CI para otimizar código Python usando IA.
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — Um agente de IA que escreve e corrige código para você.
- [Fine](https://fine.dev/?ref=awesome) — Ambiente de desenvolvimento de IA para automatizar trabalhos mundanos. Integre GitHub, Sentry, Linear. Obtenha respostas contextuais para perguntas. Planeje, projete e implemente alterações. Automatize CI/CD de auto-recuperação.
- [Potpie](https://potpie.ai) — Agentes de IA de código aberto para sua base de código em minutos. Use agentes pré-construídos para perguntas e respostas, testes, depuração e design de sistema ou crie seus próprios agentes específicos para cada finalidade.
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — Servidor MCP de configuração zero que unifica múltiplos assistentes de codificação de IA através de auto-descoberta inteligente e interface padronizada.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Ferramenta de codificação agêntica da Anthropic.
- [Open Agent](https://github.com/Th0rgal/openagent) — Plano de controle auto-hospedado para Claude Code com workspaces de contêiner isolados e streaming de missão em tempo real.
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — Framework multi-agente auto-iterativo e orientado por especificações para Claude Code com agentes especializados coordenados (Python, Next.js, CI/CD, QA, Testes de UI).
- [Leap.new](https://leap.new/) - Constrói aplicativos funcionais com serviços de backend reais, APIs e implanta em sua nuvem.
- [Recurse ML](https://recurse.ml) - Encontre bugs em códigos gerados por IA.
- [Zenable](https://zenable.io/) — Guardrails de IA que aprendem os padrões da sua equipe e garantem que os agentes de codificação os sigam, maximizando velocidade e qualidade.
- [Trellis](https://github.com/mindfold-ai/Trellis) - Framework e kit de ferramentas de IA tudo-em-um para Claude Code e Cursor. Gerencia tarefas, especificações e pipelines multi-agente.

## Agentes de PR

- [Greptile](https://greptile.com/code-review-bot) — Bot de IA que revisa PRs no GitHub/Gitlab com contexto completo da base de código.
- [Macroscope](https://macroscope.com/code-review) - Revisão de código com IA para GitHub que usa ASTs para construir uma representação baseada em grafo da sua base de código e extrai contexto dos seus sistemas de gerenciamento de issues.
- [EntelligenceAI](https://entelligence.ai/pr) — Revisões de código com IA para Github e Gitlab que melhoram com o tempo com base nos comentários do usuário.
- [Sweep](https://github.com/sweepai/sweep) — Desenvolvedor júnior de IA: integração com GitHub para gerar, testar e auto-revisar pull requests a partir de issues.
- [Codegen](https://www.codegen.com/) — Agente de PR baseado em GPT-4 para bases de código empresariais.
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — Uma ferramenta de código aberto para revisar PRs. Funciona como ação do GitHub, CLI do Gitlab ou localmente.
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — Ferramenta de código aberto para revisões de código automatizadas. Qodo era anteriormente conhecido como Codium (não confundir com Codeium com "E").
- [Nova](https://www.trynova.ai/) — Bot CI para adicionar ações como resumos e testes a novos PRs.
- [CodeRabbit](https://coderabbit.ai/) — CI personalizável para adicionar resumos e sugestões de código a PRs.
- [SwePT](https://github.com/keerthanpg/SwePT) — Gerador de PR de código aberto escrito em 150 linhas de código Python.
- [Duckie](https://duckie.ai/) — Um assistente de chat baseado na web para modificar repositórios GitHub.
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — Uma integração do GitHub que adiciona texto explicativo a PRs recém-criados.
- [Goast](https://goast.ai/) — Uma ferramenta hospedada que ingere seus logs de erro e sugere correções.
- [Corgea](https://corgea.com/) — Uma integração do GitHub que encontra e corrige código vulnerável.
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — Uma integração do GitHub focada na geração de UI com suporte integrado para shadcn, lucide e nivo charts.
- [Pixee](https://pixee.ai) — Pixeebot encontra problemas de segurança e qualidade de código em seu código e cria pull requests prontos para merge com correções recomendadas.
- [CodeAnt AI](https://www.codeant.ai/) — Cria automaticamente PRs para corrigir problemas de código.
- [What The Diff](https://whatthediff.ai/) — Aplicativo com IA que revisa o diff de pull requests e escreve um comentário descritivo sobre as mudanças em linguagem simples.
- [Trag](https://usetrag.com/) — Revisões de código com IA com instruções e padrões pré-definidos.
- [CodeReviewBot](https://codereviewbot.ai/) — Revisões de código com IA para GitHub.
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — Revisor de PR com IA para GitHub, projetado para identificar bugs, problemas de segurança e gargalos de desempenho.
- [Matter AI](https://matterai.dev) - Revisor de Código AI de Código Aberto para ajudar equipes de engenharia a lançar código com confiança.
- [Gito](https://github.com/Nayjest/Gito) - Revisor de código AI que funciona com qualquer modelo de linguagem, localmente ou em GitHub Actions.
- [Baz](https://baz.co) - Revisor de Código AI adaptado às diretrizes e convenções da sua equipe. Personalizável, adaptável, responsivo e integrado com o restante das ferramentas de desenvolvimento para contexto.

## Geradores de Aplicativos

- [Pico](https://picoapps.xyz) — Gerador de micro aplicativos ponta a ponta com implantação instantânea.
- [Co.dev](https://www.co.dev/) — Plataforma de desenvolvimento de aplicativos com IA que ajuda a construir e implantar aplicativos full-stack.
- [SoftGen](https://softgen.ai/) — Plataforma de geração de software com IA para construir aplicativos web.
- [LlamaCoder](https://llamacoder.together.ai/) — Modelo de geração de código de código aberto para construir aplicativos usando LLMs de código aberto.
- [e2b_Fragments](https://fragments.e2b.dev/) — Plataforma para construir e implantar aplicativos com IA com ambientes isolados.
- [Bolt.new](https://bolt.new) — Agente de desenvolvimento web com IA que permite solicitar, executar, editar e implantar aplicativos full-stack diretamente no navegador usando WebContainers. Suporta pacotes npm, servidores Node.js e APIs de terceiros.
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Versão de código aberto do Bolt.new que suporta múltiplos provedores de LLM, incluindo Groq, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek.
- [Srcbook](https://github.com/srcbookdev/srcbook) — Plataforma de desenvolvimento de aplicativos centrada em TypeScript com um construtor de aplicativos de IA e notebook TypeScript.
- [Capacity](https://capacity.so) — Desenvolvimento de aplicativos web full-stack com IA que transforma prompts em linguagem natural em aplicativos web totalmente funcionais.
- [Lovable](https://lovable.dev/) — Plataforma de desenvolvimento de aplicativos full-stack com IA que converte descrições ou designs em linguagem natural em aplicativos totalmente funcionais com implantação integrada e integração com GitHub.
- [Literally anything](https://literallyanything.io) — Gerador de aplicativos web HTML e JavaScript.
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — Gera um aplicativo full-stack React/Node.js/Prisma/Wasp a partir de uma breve descrição.
- [Make Real](https://makereal.tldraw.com/) — Canvas online que pode ser usado para gerar aplicativos HTML/JavaScript.
- [Marblism](https://marblism.com) — Gera um boilerplate SaaS a partir de um prompt.
- [Glowbom](https://glowbom.com/) — Gera aplicativos com IA e exporta para múltiplas plataformas.
- [Mage](https://usemage.ai/) — Gera aplicativos web full-stack em Wasp, React, Node.js e Prisma.
- [ScrollHub](https://hub.scroll.pub/) — Gera e publica sites usando a linguagem de programação Scroll.
- [Taskade Genesis](https://taskade.com/genesis) — Plataforma com IA para construir agentes de IA personalizados, fluxos de trabalho e aplicativos usando linguagem natural. Suporte multi-modelo (GPT-4o, Claude, Gemini), servidor MCP de código aberto.

- [Berrry](https://berrry.app) — Gerador de aplicativos Twitter que transforma posts de redes sociais em aplicativos web funcionais. Transforma tweets e conteúdo do Reddit em aplicativos completos com subdomínios únicos.
- [Blank Space](https://www.blankspace.build/) — Construtor de aplicativos de IA de código aberto para criar aplicativos web usando linguagem natural. Alternativa auto-hospedável ao v0, Lovable e Bolt.
- [Fastshot](https://fastshot.ai/) — Plataforma no-code orientada por IA para construir e implantar aplicativos móveis.

## Geradores de UI

- [v0](https://v0.dev/) — Crie e itere novos componentes de UI em seu navegador.
- [Rendition Create ](https://www.renditioncreate.com/) — Crie e itere novos componentes de UI em seu navegador.
- [Rapidpages](https://github.com/rapidpages/rapidpages) — Gerador de UI de código aberto.
- [Magic Patterns](https://www.magicpatterns.com/) — Prototipa suas ideias de produto. Site gerador de UI onde você pode dar prompts, fazer upload de imagens ou importar inspiração de design com sua [Extensão do Chrome](https://www.magicpatterns.com/extension). Pode exportar para Figma com um [plugin](https://www.figma.com/community/plugin/1304255855834420274). Suporta vários sistemas de componentes, incluindo Shadcn, ChakraUI e HTML + Tailwind.
- [Tempo ](https://www.tempolabs.ai/) — Editor WYSIWYG para interfaces React.
- [Kombai](https://kombai.com/) — Ferramenta de IA para gerar código frontend a partir do Figma.
- [CodeParrot](https://www.codeparrot.ai/) — Plugin do VS Code para gerar código Frontend a partir do Figma. Reutiliza componentes, bibliotecas e padrões de codificação existentes para gerar código que se encaixa perfeitamente na sua base de código existente. Tudo sem nenhum prompt.
- [Galileo AI](https://www.usegalileo.ai/) — Uma plataforma de texto para UI. Lista de espera.
- [Uizard](https://uizard.io/) — Gera mockups multi-tela a partir de prompts de texto e os edita com um editor de arrastar e soltar. Escaneia capturas de tela de aplicativos ou wireframes desenhados à mão e os transforma em mockups de aplicativos editáveis.
- [Frontly](https://fronty.com/) — Converte a imagem carregada em código HTML CSS.
- [BoringUi](https://www.boringui.xyz/) — Crie UIs bonitas usando seus dados JSON. A UI gerada está em HTML e Tailwind CSS com código que pode ser copiado e a UI pode ser compartilhada com qualquer pessoa usando links.
- [CSS Picker](https://csspicker.dev/) - Copie UI de um Design Existente e Itere com IA, suporte para Copiar CSS de um site (pela [Extensão CSS Picker](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)), imagem para código e texto para UI.

## Geradores de Snippets

- [CodePal](https://codepal.ai/) — Uma ferramenta web para gerar ou refatorar código rapidamente.
- [AI Code Convert](https://aicodeconvert.com/) — Uma ferramenta web para traduzir código entre linguagens de programação.
- [AI Code Playground](https://aicodeplayground.com/) — Uma ferramenta web para refatorar e melhorar código.
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex usa o GPT-3 da OpenAI para produzir expressões regulares a partir de linguagem natural.
- [unpkg.ai](https://unpkg.ai/) — Serviço de geração de módulos ESM com IA de código aberto. Gere módulos JavaScript via URL para prototipagem rápida.

## Documentação

- [Trelent](https://trelent.net/) — Uma extensão do VS Code para gerar docstrings. Usa modelos proprietários.
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT é um aplicativo web gratuito baseado em IA que converte um esquema, definição de infraestrutura, um snippet de código ou descrição em linguagem natural em diagramas. A ferramenta pode gerar fluxogramas, diagramas de relacionamento de entidades, diagramas de arquitetura de nuvem e diagramas de sequência.
- [DocuWriter.ai](https://www.docuwriter.ai/) — Aplicativo web com IA para gerar documentação automatizada de Código e API a partir de seus arquivos de código-fonte.
- [README-AI](https://github.com/eli64s/readme-ai) — Gerador automatizado de arquivos README.md, alimentado por APIs de modelos de linguagem grandes.
- [Supacodes](https://www.supacodes.com) — Uma ferramenta de IA que automatiza a escrita e atualização da documentação de código no Github.
- [CodexAtlas](https://codedocumentation.app/) — Documentação automatizada de código e API usando os modelos de IA mais recentes.

## Observabilidade

- [TraceRoot AI](https://traceroot.ai/) - Uma ferramenta de observabilidade nativa de IA que usa agentes de IA para corrigir automaticamente seus bugs de produção.

## Plugins OpenAI

- [ChatWithGit](https://gitsearch.sdan.io/) — Permite que o ChatGPT pesquise no GitHub e retorne links para repositórios relevantes.
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — Exemplo de código aberto de um plugin ChatGPT que extrai contexto de um diretório de arquivos.

## Pesquisa

- [Bloop](https://bloop.ai/) — Pesquisa em linguagem natural para repositórios.
- [Buildt](https://www.buildt.ai/) — Pesquisa em linguagem natural para repositórios. Lista de espera.
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — Uma ferramenta de pesquisa local que utiliza embeddings de vetor para pesquisar sua base de código semanticamente.
- [ContextMCP](https://contextmcp.ai) — Pesquisa semântica auto-hospedada em documentação de várias fontes para agentes de IA.

## Testes

- [Checksum AI](https://checksum.ai) — Agente de Automação de QA totalmente autônomo e ponta a ponta que gera testes Playwright prontos para CI/CD diretamente no repositório.
- [OctoMind](https://octomind.dev) — Manutenção automática e testes end-to-end baseados em navegador gerados, integrados ao Github Actions, Azure DevOps e muito mais.
- [Traceloop](https://traceloop.com/) — Usa dados de rastreamento OpenTelemetry com IA generativa para melhorar a confiabilidade do sistema.
- [Carbonate](https://carbonate.dev/) — Testes end-to-end usando linguagem natural. Integra-se à sua suíte de testes existente (atualmente Jest, PHPUnit e unittest do Python).
- [Meticulous.ai](https://www.meticulous.ai/) — Testes end-to-end gerados e mantidos automaticamente: à medida que seu aplicativo evolui, sua suíte de testes também evolui.
- [DiffBlue](https://www.diffblue.com/) — Testes de unidade gerados automaticamente para Java.
- [Qodo](https://www.qodo.ai/) — Geração de testes não triviais com suporte para as principais linguagens de programação. Extensões para VS Code e JetBrains. (anteriormente Codium)
- [DeepUnit](https://www.deepunit.ai/) — Casos de teste bem elaborados e geração de arquivos de teste de unidade completos. Disponível como uma extensão interativa do VS Code, pacote npm, CLI ou pipeline CI/CD.
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — Acelere a produtividade do desenvolvedor e a segurança do código encontrando vulnerabilidades no código e gerando testes para elas. Código aberto e disponível como CLI ou pipeline CI/CD.
- [KushoAI](https://kusho.ai/) — Agente de IA para testes de API que transforma suas coleções Postman, especificações OpenAPI, comandos curl, etc., em suítes de testes exaustivas que se conectam ao seu pipeline CI/CD.
- [Test Gru](https://gru.ai/home#test-gru) — Oferece serviços de automação de testes de unidade de nível empresarial.

- [AgentsKB](https://agentskb.com) - Camada de conhecimento especializada para assistentes de IA. Sua IA pesquisa, nós pesquisamos. Essa é a diferença.

## Avaliação

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — Suíte de benchmark para avaliar agentes de codificação. Compare configurações, rastreie métricas e faça testes A/B com problemas reais de seus repositórios.

## Recursos

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — Tutoriais aprofundados selecionados para projetos de ferramentas de IA e desenvolvedores de código aberto.
- [Havoptic](https://havoptic.com/) — Rastreamento de linha do tempo gratuito e de código aberto que acompanha os lançamentos de ferramentas de codificação de IA. Atualizado automaticamente diariamente. [Source](https://github.com/scotthavird/havoptic.com)

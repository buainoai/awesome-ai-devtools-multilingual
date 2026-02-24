> **🌍 Languages / 语言选择:**
> [English](./README.en.md) | [中文](./README.zh.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 뛰어난 AI 기반 개발자 도구

이 목록은 AI 기반 개발자 도구들을 엄선한 것입니다. 이 도구들은 AI를 활용하여 코드 완성, 리팩토링, 디버깅, 문서화 등과 같은 개발자 작업을 지원합니다.

- [IDEs](#ides)
- [Git 클라이언트](#git-clients)
- [어시스턴트](#assistants)
  - [웹 기반](#web-based)
  - [IDE 확장 프로그램](#ide-extensions)
  - [명령줄](#command-line)
  - [데스크톱](#desktop)
- [셸 어시스턴트](#shell-assistants)
- [에이전트](#agents)
- [PR 에이전트](#pr-agents)
- [앱 생성기](#app-generators)
- [UI 생성기](#ui-generators)
- [스니펫 생성기](#snippet-generators)
- [문서화](#documentation)
- [OpenAI 플러그인](#openai-plugins)
- [검색](#search)
- [테스팅](#testing)
- [평가](#evaluation)
- [자료](#resources)

## IDEs

- [Google Antigravity](https://antigravity.google/) — 자율 AI 에이전트를 조율하여 복잡한 코딩 작업을 계획, 실행 및 검증하는 에이전트 우선 IDE로, 브라우저와 깊이 통합되어 있습니다.
- [Crystal](https://github.com/stravu/crystal) — 병렬 Claude Code 세션을 관리, 검사 및 테스트하는 새로운 유형의 개발 환경입니다.
- [Cursor](https://www.cursor.com/) — 채팅, 편집, 생성 및 디버그 기능을 갖춘 IDE입니다. VSCodium에서 포크되어 VS Code와 유사한 인터페이스를 가지고 있습니다. OpenAI를 사용합니다.
- [PearAI](https://trypear.ai/) — 채팅 및 인라인 코드 생성을 지원하는 VS Code의 오픈 소스 포크입니다.
- [Melty](https://melty.sh/) — 내장 채팅, 변경 미리보기, AI로 커밋을 작성하는 기능을 갖춘 VS Code의 오픈 소스 포크입니다. 현재 소스 코드만 제공됩니다.
- [Replit](https://replit.com/) — 클라우드 개발 환경, 코드 완성, 채팅, 소프트웨어 개발 에이전트 및 배포 기능을 갖춘 웹 기반 IDE입니다.
- [Mutable](https://github.com/mutableai/monitors4codegen) — 챗봇 및 GitHub와 통합된 웹 기반 IDE입니다.
- [CodeStory](https://codestory.ai/) — 채팅, 코드 설명, 자동 생성 커밋 및 PR 요약 기능을 갖춘 IDE입니다. VSCodium에서 포크되었습니다.
- [UI Pilot](https://ui-pilot.com/) — GPT-4를 사용하여 Material UI로 폼을 생성하는 채팅 기반 AI 코드 편집기입니다.
- [GitWit](https://gitwit.dev/) — AI를 사용하여 ReactJS 애플리케이션을 구축하기 위한 웹 기반 편집기입니다.
- [Windsurf](https://windsurf.com) — 채팅, 편집, 생성 및 디버그 기능을 갖춘 IDE입니다. VSCodium에서 포크되어 VS Code와 유사한 인터페이스를 가지고 있습니다. 이전에는 Codeium으로 알려졌습니다.
- [Theia IDE](https://theia-ide.org/#theiaide) — 확장 가능한 오픈 소스 IDE(웹 및 데스크톱)로, 채팅, 코드 완성, 터미널 지원 및 임의의 LLM을 사용하는 사용자 지정 에이전트와 같은 AI 기반 기능을 제공합니다. 사용자 지정 AI 기반 도구 및 IDE 생성을 가능하게 하는 플랫폼인 [Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/)를 기반으로 구축되었습니다.
- [OneCompiler](https://onecompiler.com/) — Java, Python, MySQL, C++, HTML을 포함한 70개 이상의 언어를 지원하는 무료 AI 기반 온라인 컴파일러로, 코드를 작성, 실행 및 공유할 수 있습니다.
- [trae](https://www.trae.ai/) — Trae는 작업 방식을 변화시키고 더 빠르게 실행할 수 있도록 협력하는 적응형 AI IDE입니다.
- [Zed](https://zed.dev/) - Atom 및 Tree-sitter 개발자들이 만든 고성능 멀티플레이어 코드 편집기입니다.
- [Nimbalyst](https://nimbalyst.com) - Claude Code 및 Codex를 위한 에이전트 관리 환경입니다. 마크다운, 목업, Excalidraw, 코드의 대화형 시각 편집. 병렬 세션 관리.

## Git 클라이언트

- [GitBrain](https://gitbrain.dev/) — Git 워크플로우를 단순화하는 Git 클라이언트입니다. 코드 변경 사항을 분할하고, 코드 변경 사항에 대한 요약 및 커밋 메시지를 생성합니다. OpenAI를 사용합니다.
- [GitButler](https://gitbutler.com/) — 기존 워크플로우 위에 동시 브랜치를 위한 Git 클라이언트입니다. 기본적으로 OpenAI를 사용하며, 기존 커밋 메시지 생성을 위해 Perplexity로 변경할 수 있습니다.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - AI를 사용하여 고품질 Git 커밋 메시지 및 풀 리퀘스트 설명을 자동으로 생성하는 CLI 도구입니다.

## 어시스턴트

### 웹 기반

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — [Replit](https://replit.com/)에 내장된 어시스턴트로, 채팅, 사전 예방적 디버깅 및 자동 완성을 제공합니다. 채팅에는 OpenAI를 사용하고 자동 완성에는 [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS)를 사용합니다.
- [Unblocked](https://getunblocked.com/) — GitHub, Slack, Jira, Confluence 등에서 관련 기존 지식으로 소스 코드를 보강합니다. 채팅 및 IDE 파일 수준 컨텍스트를 통해 답변을 얻을 수 있습니다. 웹, macOS, Slack, VSCode 및 JetBrains IDE에서 사용할 수 있습니다.
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — 채팅, 리팩토링 및 단위 테스트 생성을 지원하는 어시스턴트입니다. VS Code 및 IntelliJ용 확장 프로그램이 있습니다. 웹 앱으로도 사용할 수 있습니다.
- [Magnet](https://www.magnet.run/) — 저장소 및 이슈를 컨텍스트로 사용하는 웹 기반 챗봇입니다.
- [Adrenaline](https://useadrenaline.com/) — AI 및 AST를 사용하여 코드베이스에 대한 질문에 답변하는 웹 기반 챗봇입니다.
- [CodeSquire](https://codesquire.ai/) — Google Colab, BigQuery 및 JupyterLab에 자동 완성을 추가하는 Chrome 확장 프로그램입니다.
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — 내장 Python 편집기 및 인터프리터를 갖춘 오픈 소스 어시스턴트입니다.
- [Onboard](https://www.getonboardai.com) — 공개 및 비공개 코드베이스에 대해 AI와 채팅합니다.
- [Code to Flow](https://codetoflow.com) — 대화형 순서도를 통해 코드를 시각화, 분석 및 이해합니다.
- [Pieces](https://pieces.app/) — 코드 캡처, 보강 및 재사용, 협업 간소화, 워크플로우에 대한 상황별 이해를 통해 복잡한 문제 해결을 돕는 온디바이스 코파일럿입니다.
- [Wren AI](https://getwren.ai/oss) — SQL을 작성하지 않고 질문하여 더 빠르게 결과와 통찰력을 얻을 수 있는 SQL AI 에이전트이며, 오픈 소스입니다!
- [TEXT2SQL.AI](https://www.text2sql.ai/) — AI 기반 SQL 쿼리 빌더입니다. 일반 영어를 사용하여 복잡한 SQL 쿼리를 번역, 설명 및 수정합니다.
- [SQLAI.ai](https://www.sqlai.ai/) — AI가 SQL 쿼리를 생성, 수정, 설명 및 최적화합니다. 자체 데이터베이스 스키마를 추가하고 AI가 이를 이해하도록 훈련할 수 있습니다.
- [CodeWP](https://codewp.ai/) — WordPress 개발자를 위해 특별히 훈련된 AI 채팅 및 코딩 도구입니다. WordPress에서 코드 스니펫 및 플러그인을 위한 AI 코드 생성.
- [Gru.ai](https://www.gru.ai/) — 알고리즘 구축, 문제 디버그, 솔루션 테스트, 프로그래밍 질문 답변 등 기술적인 문제 해결 및 일상적인 코딩 작업을 처리하는 데 도움을 줄 수 있는 AI 개발자입니다.

### IDE 확장 프로그램

- [GitHub Copilot](https://github.com/features/copilot) — 채팅, 풀 리퀘스트 텍스트 생성 및 단위 테스트 생성을 지원하는 VS Code 확장 프로그램입니다.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — 사용자 권한으로 파일 생성/편집, 명령 실행, 브라우저 사용이 가능한 VS Code용 자율 코딩 에이전트입니다. OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure, GCP Vertex를 포함한 여러 AI 공급자를 지원합니다.
- [Refact AI](https://refact.ai/) [소스](https://github.com/smallcloudai/refact) — 채팅, 완성, 리팩토링 및 코드베이스별 미세 조정을 지원하는 오픈 소스 어시스턴트입니다. VS Code 및 JetBrains용 확장 프로그램이 있습니다.
- [Continue](https://continue.dev/) — 채팅, 리팩토링 및 코드 생성을 지원하는 VS Code 확장 프로그램입니다. 여러 파일을 편집하고 사용자를 대신하여 명령을 실행합니다.
- [Blackbox AI](https://www.useblackbox.io/) — 온라인 코딩 참조 링크를 포함한 자동 완성 및 채팅 기능을 갖춘 VS Code 확장 프로그램입니다.
- [CodeGeeX](https://codegeex.cn/) — CodeGeeX LLM을 기반으로 하는 오픈 소스 어시스턴트로, 채팅, 완성 및 리팩토링을 지원합니다. VS Code 및 PyCharm을 포함한 9개 편집기용 확장 프로그램이 있습니다.
- [Quack AI](https://www.quackai.com/) — 프로젝트 코딩 가이드라인을 준수하기 위한 VS Code 확장 프로그램입니다.
- [Tabby](https://tabbyml.github.io/tabby/) — 오픈 소스, 자체 호스팅 코드 완성 어시스턴트입니다. VS Code 및 Vim용 확장 프로그램이 있습니다.
- [Tabnine](https://www.tabnine.com/) [(소스)](https://github.com/codota/TabNine) — 오픈 소스, 자체 호스팅 코드 완성 어시스턴트입니다. VS Code, IntelliJ, Neovim, Eclipse, PyCharm을 포함한 15개 편집기용 확장 프로그램이 있습니다.
- [CodeMate](https://www.codemate.ai/) — 코드 디버깅 및 최적화를 위한 VS Code 확장 프로그램입니다.
- [AskCodi](https://www.askcodi.com/) — VS Code, JetBrains 및 Sublime Text용 확장 프로그램을 갖춘 AI 코딩 어시스턴트입니다.
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Visual Studio Code 사이드바용 오픈 소스 채팅 어시스턴트입니다.
- [CodeComplete](https://codecomplete.ai/) — 자체 호스팅 엔터프라이즈 완성 어시스턴트입니다.
- [GoCodeo](https://www.gocodeo.com/) - GoCodeo는 클릭 한 번으로 Vercel 배포 및 원활한 Supabase 통합을 통해 풀 스택 앱을 손쉽게 구축하고 배포할 수 있도록 하는 AI 에이전트입니다.
- [JetBrains AI](https://www.jetbrains.com/ai/) — 모든 JetBrains IDE에서 사용할 수 있는 AI 어시스턴트입니다.
- [aiXcoder](https://www.aixcoder.com/en/) — IntelliJ IDEA, CLion, GoLand, PyCharm, WebStorm, Visual Studio Code 및 Eclipse용 확장 프로그램을 갖춘 로컬 또는 클라우드 기반 어시스턴트입니다.
- [Sourcery](https://sourcery.ai/) — 160가지 Python 모범 사례 및 40가지 이상의 JS/TS 모범 사례를 참조하는 AI 어시스턴트 및 린터입니다. VS Code, PyCharm, Vim 및 Sublime용 확장 프로그램이 있습니다.
- [Swimm](https://swimm.io) — 정적 분석 및 AI 생성 문서를 사용하여 상황별 코드 이해를 위한 어시스턴트입니다. VSCode, Jetbrains, IntelliJ, WebStorm, Rider, PhpStorm, Android Studio, PyCharm, PhPStorm
- [Supermaven](https://supermaven.com/) — 300,000 토큰 컨텍스트 창을 갖춘 자동 완성을 위한 VS Code 확장 프로그램입니다.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — VS Code 및 IntelliJ IDEA와 같은 IDE용 확장 프로그램을 갖춘 AI 코딩 어시스턴트입니다. Amazon Q Developer IDE 플러그인에는 코드 스캔을 통해 보안 문제 강조 및 정의(/review), 문서 작성(/doc), 단위 테스트 작성(/test), Java 최신 버전으로 업그레이드 지원(/transform)을 수행할 수 있는 여러 에이전트가 있습니다(이전에는 Amazon CodeWhisperer로 알려짐).
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Bot은 Android Studio에 긴밀하게 통합된 AI 기반 코딩 어시스턴트입니다. Studio Bot은 Android 개발자가 코드를 생성하고, 관련 리소스를 찾고, 모범 사례를 배우고, 시간을 절약하는 데 도움을 줄 수 있습니다.
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Z는 코드 생성을 지원하는 AI 기반 메인프레임 애플리케이션 현대화 제품입니다. 애플리케이션 검색 및 분석, 자동화된 코드 리팩토링 및 COBOL을 Java로 변환하는 기능이 포함됩니다.
- [EasyCode](https://www.easycode.ai/) — GPT-4 채팅을 지원하는 VS Code 확장 프로그램입니다.
- [Kilo Code](https://kilocode.ai) - VS Code 내에서 코드를 계획, 구축 및 수정하기 위한 오픈 소스 AI 코딩 어시스턴트입니다.
- [FlyonUI MCP](https://flyonui.com/mcp) — FlyonUI MCP - Tailwind AI Builder를 IDE에 직접 통합하고 FlyonUI에서 영감을 받은 멋진 Tailwind CSS 컴포넌트, 블록 및 페이지를 만드세요.
- [Traycer](https://traycer.ai) - VS Code의 계획 우선 코딩 어시스턴트입니다.
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - shadcn/studio MCP 서버를 좋아하는 IDE에 직접 통합하고 shadcn/studio에서 영감을 받은 멋진 shadcn/ui 컴포넌트, 블록 및 페이지를 만드세요.

### 명령줄

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - 명령 완성, 의도를 명령으로 번역하기 위한 생성형 AI를 사용한 명령 번역, 코드 작성을 돕는 컨텍스트 관리 기능을 갖춘 완전한 에이전트 채팅 인터페이스를 제공하는 CLI입니다. MacOS, Linux 및 Windows(wsl을 통해)에서 다양한 터미널 및 셸과 함께 작동합니다.
- [aloc](https://github.com/modern-tooling/aloc) — Rust 및 Ratatui로 구축된 현대적인 AI 증강 코드 라인 카운터입니다. 정확한 프로젝트 추정을 위해 AI 노력 프로필을 사용합니다.
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — 저장소를 컨텍스트로 사용하는 CLI 챗봇입니다. OpenAI뿐만 아니라 GPT4All을 통해 로컬에서 실행되는 LLM도 지원합니다.
- [gptcomet](https://github.com/belingud/gptcomet) — 커밋 메시지를 생성하고 변경 사항을 검토하는 데 도움이 되는 CLI 도구입니다. 여러 공급자 및 언어를 지원합니다.
- [poorcoder](https://github.com/vgrichina/poorcoder) — 코드 컨텍스트를 추출하고, 마크다운에서 변경 사항을 적용하고, 웹 기반 LLM을 사용하는 동안 AI 커밋 메시지를 생성하는 Bash 스크립트 모음입니다.
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — LLM 생성을 사용하여 마크다운 기반 프롬프트 스택을 코드 및 테스트로 변환하는 자체 컴파일 도구입니다. Claude, ChatGPT 및 Grok을 포함한 OpenRouter를 통해 모든 LLM과 작동합니다.
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - 자연어를 실행 가능한 셸 명령으로 변환합니다 (예: `ai Tell me the free space on disk`)
- [promptext](https://github.com/1broseidon/promptext) — 정확한 토큰 계산, 관련성 우선순위 지정 및 예산 관리를 통해 AI 어시스턴트를 위한 스마트 코드 컨텍스트 추출기입니다. LLM 토큰 제한 내에서 최적화된 코드 컨텍스트를 준비합니다.
- [Baz CLI](https://github.com/baz-scm/baz-cli) - 실제 코드, diff 등에 액세스할 수 있는 AI 지원 코드 검토를 위한 CLI입니다.
- [AdaL](https://sylph.ai/) — 모델이 협업할 수 있도록 하는 자체 진화형 AI 코딩 에이전트(Claude, GPT, Gemini)입니다. 로컬에서 실행되며 코드베이스 패턴을 학습합니다.
- [Tokscale](https://github.com/junhoyeo/tokscale) — 글로벌 리더보드 및 2D/3D 기여 그래프를 통해 AI 코딩 에이전트(OpenCode, Claude Code, OpenClaw, Codex, Gemini CLI, Cursor IDE, AmpCode, Factory Droid)의 토큰 사용량을 추적하는 CLI 도구입니다.
- [vsync](https://github.com/nicepkg/vsync) — Claude Code, Cursor, OpenCode 및 Codex에서 Skills, MCP 서버, 에이전트 및 명령을 자동 형식 변환(JSON ↔ TOML ↔ JSONC)을 통해 동기화하는 CLI 도구입니다.
- [Arctic](https://github.com/arctic-cli/interface): 여러 AI 코딩 계획 및 API를 내장된 사용량 및 할당량 가시성과 함께 통합하는 터미널 우선 TUI입니다.

### 데스크톱

- [Memex](https://memex.tech/) — 데스크톱에서 자연어로 모든 스택으로 무엇이든 구축할 수 있습니다.
- [Pieces](https://pieces.app/) — 개발자의 생산성 향상을 돕기 위해 설계된 AI 기반 데스크톱 애플리케이션 및 브라우저 확장 프로그램입니다.

## 셸 어시스턴트

- [AskCommand](https://www.askcommand.cppexpert.online/) — AI를 사용하여 텍스트에서 Unix 명령을 자동으로 생성하는 웹 기반 도구입니다.
- [Butterfish](https://butterfi.sh) — ChatGPT를 셸에 내장하여 쉽게 액세스할 수 있는 CLI 도구입니다. 간단한 에이전트 기능이 포함되어 있습니다.
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — 셸 명령을 생성하고 설명을 얻기 위한 고도로 구성 가능한 CLI 어시스턴트입니다.
- [GitFluence](https://www.gitfluence.com/) — AI 기반 솔루션을 사용하여 가장 관련성 높은 Git 명령을 제안하여 텍스트 설명에서 터미널 또는 CLI용 Git 명령을 자동으로 생성하는 웹 기반 Git 명령 생성기입니다.
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - <TAB><TAB>을 입력하기만 하면 상위 제안을 반환하여 터미널에 AI 기반 명령줄 제안을 직접 추가하는 CLI 도구입니다.
- [code-collator](https://github.com/tawandakembo/code-collator) — 전체 코드베이스를 언어 모델에 설명하는 단일 마크다운 파일을 생성하는 CLI 도구입니다. API를 통하는 대신 Claude/ChatGPT 웹 인터페이스에서 AI 코딩 지원을 받는 데 유용합니다.
- [Warp](https://www.warp.dev/) - Warp는 AI와 팀 지식을 단일하고 빠르고 직관적인 터미널에 통합합니다.
- [TmuxAI](https://tmuxai.dev/) - AI 기반의 비침습적 터미널 어시스턴트입니다.
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - 동적 완성 및 AI 통합을 통해 명령 템플릿/스니펫을 관리합니다.

## 에이전트

- [Smol Developer](https://github.com/smol-ai/developer) — 프롬프트에서 저장소를 생성하는 CLI 에이전트입니다. OpenAI 및 Anthropic을 사용합니다.
- [Aider](https://github.com/paul-gauthier/aider) — 저장소에 변경 사항을 생성하고 커밋하는 CLI 어시스턴트 및 에이전트입니다. OpenAI를 사용합니다.
- [Blinky](https://github.com/seahyinghang8/blinky) — SWE-agent에서 영감을 받아 백엔드 오류를 식별하고 수정하는 데 도움이 되는 VS Code용 디버깅 에이전트입니다.
- [Mentat](https://www.mentat.ai/) — 저장소에 변경 사항을 적용하는 CLI 어시스턴트 및 에이전트입니다.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — 프롬프트에서 저장소를 생성하고 명확한 질문을 하는 CLI 에이전트입니다.
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — 풀 스택 애플리케이션을 한 언어 또는 프레임워크에서 다른 언어 또는 프레임워크로 변환하는 CLI 에이전트입니다. GPT-4 32k 컨텍스트를 사용합니다.
- [Grit](https://app.grit.io) — 유지 관리 작업 및 기타 개발 작업을 자동화하기 위한 GitHub 통합 에이전트입니다.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Llama 2의 강력한 기능을 갖춘 자동 Gen-AI 앱 생성기입니다.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT: AI 기반 소프트웨어 개발 자동화 솔루션입니다.
- [Second.dev](https://www.second.dev/) — 풀 스택 앱에 기능을 추가하기 위한 플랫폼입니다.
- [Factory](https://www.factory.ai/) — 코드 생성을 위한 에이전트입니다. 대기 목록에 있습니다.
- [sudocode](https://sudocode.ai/) — Code Interpreter와 유사하게 프로젝트를 생성하기 위한 웹 기반 채팅 어시스턴트입니다.
- [CodeFlash AI](https://www.codeflash.ai/) — AI를 사용하여 Python 코드를 최적화하는 CLI 및 CI 도구입니다.
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — 코드를 작성하고 수정하는 AI 에이전트입니다.
- [Fine](https://fine.dev/?ref=awesome) — 지루한 작업을 자동화하는 AI 개발 환경입니다. GitHub, Sentry, Linear를 통합합니다. 컨텍스트 인식 질문에 대한 답변을 얻습니다. 변경 사항을 계획, 설계 및 구현합니다. 자체 복구 CI/CD를 자동화합니다.
- [Potpie](https://potpie.ai) — 몇 분 안에 코드베이스를 위한 오픈 소스 AI 에이전트입니다. Q&A, 테스트, 디버깅 및 시스템 설계를 위한 사전 구축된 에이전트를 사용하거나 자체 목적에 맞는 에이전트를 생성하세요.
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — 지능형 자동 검색 및 표준화된 인터페이스를 통해 여러 AI 코딩 어시스턴트를 통합하는 제로 구성 MCP 서버입니다.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Anthropic의 에이전트 코딩 도구입니다.
- [Open Agent](https://github.com/Th0rgal/openagent) — 격리된 컨테이너 작업 공간 및 실시간 미션 스트리밍을 갖춘 Claude Code용 자체 호스팅 제어 플레인입니다.
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — 조정된 전문 에이전트(Python, Next.js, CI/CD, QA, UI 테스트)를 갖춘 Claude Code용 사양 기반, 자체 반복 다중 에이전트 프레임워크입니다.
- [Leap.new](https://leap.new/) - 실제 백엔드 서비스, API를 사용하여 기능적인 앱을 구축하고 클라우드에 배포합니다.
- [Recurse ML](https://recurse.ml) - AI 생성 코드에서 버그를 찾습니다.
- [Zenable](https://zenable.io/) — 팀의 표준을 학습하고 코딩 에이전트가 이를 따르도록 보장하여 속도와 품질을 극대화하는 AI 가드레일입니다.
- [Trellis](https://github.com/mindfold-ai/Trellis) - Claude Code 및 Cursor를 위한 올인원 AI 프레임워크 및 툴킷입니다. 작업, 사양 및 다중 에이전트 파이프라인을 관리합니다.

## PR 에이전트

- [Greptile](https://greptile.com/code-review-bot) — 코드베이스의 전체 컨텍스트를 사용하여 GitHub/Gitlab에서 PR을 검토하는 AI 봇입니다.
- [Macroscope](https://macroscope.com/code-review) - AST를 사용하여 코드베이스의 그래프 기반 표현을 구축하고 이슈 관리 시스템에서 컨텍스트를 가져오는 GitHub용 AI 기반 코드 검토입니다.
- [EntelligenceAI](https://entelligence.ai/pr) — 사용자 의견을 기반으로 시간이 지남에 따라 개선되는 Github 및 Gitlab용 AI 기반 코드 검토입니다.
- [Sweep](https://github.com/sweepai/sweep) — AI 주니어 개발자: 이슈에서 풀 리퀘스트를 생성, 테스트 및 자체 검토하는 GitHub 통합입니다.
- [Codegen](https://www.codegen.com/) — 엔터프라이즈 코드베이스용 GPT-4 기반 PR 에이전트입니다.
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — PR을 검토하기 위한 오픈 소스 도구입니다. GitHub 액션, Gitlab CLI 또는 로컬에서 작동합니다.
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — 자동화된 코드 검토를 위한 오픈 소스 도구입니다. Qodo는 이전에 Codium으로 알려졌습니다("E"가 있는 Codeium과 혼동하지 마십시오).
- [Nova](https://www.trynova.ai/) — 새 PR에 요약 및 테스트와 같은 작업을 추가하는 CI 봇입니다.
- [CodeRabbit](https://coderabbit.ai/) — PR에 요약 및 코드 제안을 추가하는 사용자 지정 가능한 CI입니다.
- [SwePT](https://github.com/keerthanpg/SwePT) — 150줄의 Python 코드로 작성된 오픈 소스 PR 생성기입니다.
- [Duckie](https://duckie.ai/) — GitHub 저장소를 수정하기 위한 웹 기반 채팅 어시스턴트입니다.
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — 새로 생성된 PR에 설명 텍스트를 추가하는 GitHub 통합입니다.
- [Goast](https://goast.ai/) — 오류 로그를 수집하고 수정 사항을 제안하는 호스팅 도구입니다.
- [Corgea](https://corgea.com/) — 취약한 코드를 찾아 수정하는 GitHub 통합입니다.
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — shadcn, lucide 및 nivo 차트에 대한 내장 지원을 통해 UI 생성에 중점을 둔 GitHub 통합입니다.
- [Pixee](https://pixee.ai) — Pixeebot은 코드에서 보안 및 코드 품질 문제를 찾아 권장 수정 사항이 포함된 병합 준비 풀 리퀘스트를 생성합니다.
- [CodeAnt AI](https://www.codeant.ai/) — 코드 문제를 해결하기 위한 PR을 자동으로 생성합니다.
- [What The Diff](https://whatthediff.ai/) — 풀 리퀘스트의 diff를 검토하고 변경 사항에 대한 설명적인 주석을 일반 영어로 작성하는 AI 기반 앱입니다.
- [Trag](https://usetrag.com/) — 사전 정의된 지침 및 패턴을 사용하여 AI 기반 코드 검토를 수행합니다.
- [CodeReviewBot](https://codereviewbot.ai/) — GitHub용 AI 기반 코드 검토입니다.
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — 버그, 보안 문제 및 성능 병목 현상을 식별하도록 설계된 GitHub용 AI 기반 PR 검토자입니다.
- [Matter AI](https://matterai.dev) - 엔지니어링 팀이 자신감을 가지고 코드를 출시할 수 있도록 돕는 오픈 소스 AI 코드 검토자입니다.
- [Gito](https://github.com/Nayjest/Gito) - 로컬 또는 GitHub Actions에서 모든 언어 모델과 작동하는 AI 코드 검토자입니다.
- [Baz](https://baz.co) - 팀의 가이드라인 및 규칙에 맞춰진 AI 코드 검토자입니다. 사용자 정의 가능하고, 적응 가능하며, 반응성이 뛰어나고, 컨텍스트를 위해 다른 개발자 도구와 통합됩니다.

## 앱 생성기

- [Pico](https://picoapps.xyz) — 즉시 배포되는 엔드투엔드 마이크로 앱 생성기입니다.
- [Co.dev](https://www.co.dev/) — 풀 스택 애플리케이션을 구축하고 배포하는 데 도움이 되는 AI 기반 앱 개발 플랫폼입니다.
- [SoftGen](https://softgen.ai/) — 웹 앱 구축을 위한 AI 기반 소프트웨어 생성 플랫폼입니다.
- [LlamaCoder](https://llamacoder.together.ai/) — 오픈 소스 LLM을 사용하여 애플리케이션을 구축하기 위한 오픈 소스 코드 생성 모델입니다.
- [e2b_Fragments](https://fragments.e2b.dev/) — 샌드박스 환경을 통해 AI 기반 애플리케이션을 구축하고 배포하기 위한 플랫폼입니다.
- [Bolt.new](https://bolt.new) — WebContainers를 사용하여 브라우저에서 직접 풀 스택 애플리케이션을 프롬프트, 실행, 편집 및 배포할 수 있는 AI 기반 웹 개발 에이전트입니다. npm 패키지, Node.js 서버 및 타사 API를 지원합니다.
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Groq, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek을 포함한 여러 LLM 공급자를 지원하는 Bolt.new의 오픈 소스 버전입니다.
- [Srcbook](https://github.com/srcbookdev/srcbook) — AI 앱 빌더 및 TypeScript 노트북을 갖춘 TypeScript 중심 앱 개발 플랫폼입니다.
- [Capacity](https://capacity.so) — 자연어 프롬프트를 완전한 기능을 갖춘 웹 애플리케이션으로 변환하는 AI 기반 풀 스택 웹 앱 개발입니다.
- [Lovable](https://lovable.dev/) — 자연어 설명 또는 디자인을 내장된 배포 및 GitHub 통합을 통해 완전한 기능을 갖춘 애플리케이션으로 변환하는 AI 기반 풀 스택 앱 개발 플랫폼입니다.
- [Literally anything](https://literallyanything.io) — HTML 및 JavaScript 웹 앱 생성기입니다.
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — 짧은 설명에서 풀 스택 React/Node.js/Prisma/Wasp 앱을 생성합니다.
- [Make Real](https://makereal.tldraw.com/) — HTML/JavaScript 앱을 생성하는 데 사용할 수 있는 온라인 캔버스입니다.
- [Marblism](https://marblism.com) — 프롬프트에서 SaaS 보일러플레이트를 생성합니다.
- [Glowbom](https://glowbom.com/) — AI로 앱을 생성하고 여러 플랫폼으로 내보냅니다.
- [Mage](https://usemage.ai/) — Wasp, React, Node.js 및 Prisma에서 풀 스택 웹 앱을 생성합니다.
- [ScrollHub](https://hub.scroll.pub/) — Scroll 프로그래밍 언어를 사용하여 웹사이트를 생성하고 게시합니다.
- [Taskade Genesis](https://taskade.com/genesis) — 자연어를 사용하여 사용자 지정 AI 에이전트, 워크플로우 및 앱을 구축하기 위한 AI 기반 플랫폼입니다. 다중 모델 지원(GPT-4o, Claude, Gemini), 오픈 소스 MCP 서버.

- [Berrry](https://berrry.app) — 소셜 미디어 게시물을 기능적인 웹 애플리케이션으로 변환하는 Twitter 앱 생성기입니다. 트윗 및 Reddit 콘텐츠를 고유한 서브도메인을 가진 완전한 앱으로 변환합니다.
- [Blank Space](https://www.blankspace.build/) — 자연어를 사용하여 웹 애플리케이션을 생성하기 위한 오픈 소스 AI 앱 빌더입니다. v0, Lovable 및 Bolt의 자체 호스팅 대안입니다.
- [Fastshot](https://fastshot.ai/) — 모바일 앱 구축 및 배포를 위한 AI 기반 노코드 플랫폼입니다.

## UI 생성기

- [v0](https://v0.dev/) — 브라우저에서 새로운 UI 컴포넌트를 생성하고 반복합니다.
- [Rendition Create ](https://www.renditioncreate.com/) — 브라우저에서 새로운 UI 컴포넌트를 생성하고 반복합니다.
- [Rapidpages](https://github.com/rapidpages/rapidpages) — 오픈 소스 UI 생성기입니다.
- [Magic Patterns](https://www.magicpatterns.com/) — 제품 아이디어를 프로토타입화합니다. 프롬프트, 이미지 업로드 또는 [Chrome 확장 프로그램](https://www.magicpatterns.com/extension)으로 디자인 영감을 가져올 수 있는 UI 생성기 웹사이트입니다. [플러그인](https://www.figma.com/community/plugin/1304255855834420274)을 사용하여 Figma로 내보낼 수 있습니다. Shadcn, ChakraUI 및 HTML + Tailwind를 포함한 여러 컴포넌트 시스템을 지원합니다.
- [Tempo ](https://www.tempolabs.ai/) — React 인터페이스용 WYSIWYG 편집기입니다.
- [Kombai](https://kombai.com/) — Figma에서 프론트엔드 코드를 생성하기 위한 AI 도구입니다.
- [CodeParrot](https://www.codeparrot.ai/) — Figma에서 프론트엔드 코드를 생성하는 VS Code 플러그인입니다. 기존 컴포넌트, 라이브러리 및 코딩 표준을 재사용하여 기존 코드베이스와 완벽하게 맞는 코드를 생성합니다. 프롬프트 없이 모든 작업을 수행합니다.
- [Galileo AI](https://www.usegalileo.ai/) — 텍스트-UI 플랫폼입니다. 대기 목록에 있습니다.
- [Uizard](https://uizard.io/) — 텍스트 프롬프트에서 다중 화면 목업을 생성하고 드래그 앤 드롭 편집기로 편집합니다. 앱 스크린샷 또는 손으로 그린 와이어프레임을 스캔하여 편집 가능한 앱 목업으로 변환합니다.
- [Frontly](https://fronty.com/) — 업로드된 이미지를 HTML CSS 코드로 변환합니다.
- [BoringUi](https://www.boringui.xyz/) — JSON 데이터를 사용하여 아름다운 UI를 생성합니다. 생성된 UI는 HTML 및 Tailwind CSS로 되어 있으며, 코드를 복사하고 링크를 사용하여 누구와도 UI를 공유할 수 있습니다.
- [CSS Picker](https://csspicker.dev/) - 기존 디자인에서 UI를 복사하고 AI로 반복합니다. 웹사이트에서 CSS 복사([CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)를 통해), 이미지를 코드로, 텍스트를 UI로 변환하는 기능을 지원합니다.

## 스니펫 생성기

- [CodePal](https://codepal.ai/) — 코드를 빠르게 생성하거나 리팩토링하기 위한 웹 도구입니다.
- [AI Code Convert](https://aicodeconvert.com/) — 프로그래밍 언어 간에 코드를 번역하기 위한 웹 도구입니다.
- [AI Code Playground](https://aicodeplayground.com/) — 코드를 리팩토링하고 개선하기 위한 웹 도구입니다.
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegex는 OpenAI의 GPT-3를 사용하여 일반 영어에서 정규 표현식을 생성합니다.
- [unpkg.ai](https://unpkg.ai/) — 오픈 소스 AI 기반 ESM 모듈 생성 서비스입니다. 빠른 프로토타이핑을 위해 URL을 통해 JavaScript 모듈을 생성합니다.

## 문서화

- [Trelent](https://trelent.net/) — 독스트링을 생성하는 VS Code 확장 프로그램입니다. 독점 모델을 사용합니다.
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPT는 스키마, 인프라 정의, 코드 스니펫 또는 일반 언어 설명을 다이어그램으로 변환하는 무료 AI 기반 웹 앱입니다. 이 도구는 순서도, 엔티티 관계 다이어그램, 클라우드 아키텍처 다이어그램 및 시퀀스 다이어그램을 생성할 수 있습니다.
- [DocuWriter.ai](https://www.docuwriter.ai/) — 소스 코드 파일에서 자동화된 코드 및 API 문서를 생성하는 AI 기반 웹 앱입니다.
- [README-AI](https://github.com/eli64s/readme-ai) — 대규모 언어 모델 API를 기반으로 하는 자동화된 README.md 파일 생성기입니다.
- [Supacodes](https://www.supacodes.com) — Github에서 코드 문서 작성을 자동화하고 업데이트하는 AI 도구입니다.
- [CodexAtlas](https://codedocumentation.app/) — 최신 AI 모델을 사용한 자동화된 코드 및 API 문서화.

## 관찰 가능성

- [TraceRoot AI](https://traceroot.ai/) - AI 에이전트를 사용하여 프로덕션 버그를 자동으로 수정하는 AI 네이티브 관찰 가능성 도구입니다.

## OpenAI 플러그인

- [ChatWithGit](https://gitsearch.sdan.io/) — ChatGPT가 GitHub를 검색하고 관련 저장소 링크를 반환할 수 있도록 합니다.
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — 파일 디렉토리에서 컨텍스트를 가져오는 ChatGPT 플러그인의 오픈 소스 예제입니다.

## 검색

- [Bloop](https://bloop.ai/) — 저장소에 대한 자연어 검색입니다.
- [Buildt](https://www.buildt.ai/) — 저장소에 대한 자연어 검색입니다. 대기 목록에 있습니다.
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — 코드베이스를 의미론적으로 검색하기 위해 벡터 임베딩을 활용하는 로컬 검색 도구입니다.
- [ContextMCP](https://contextmcp.ai) — AI 에이전트를 위한 다양한 소스의 문서에 대한 자체 호스팅 의미론적 검색입니다.

## 테스팅

- [Checksum AI](https://checksum.ai) — CI/CD 준비 Playwright 테스트를 저장소에 직접 생성하는 엔드투엔드 완전 자율 QA 자동화 에이전트입니다.
- [OctoMind](https://octomind.dev) — GitHub Actions, Azure DevOps 등에 통합된 자동 유지 관리 및 생성된 브라우저 기반 엔드투엔드 테스트입니다.
- [Traceloop](https://traceloop.com/) — OpenTelemetry 추적 데이터를 생성형 AI와 함께 사용하여 시스템 안정성을 향상시킵니다.
- [Carbonate](https://carbonate.dev/) — 자연어를 사용한 엔드투엔드 테스트입니다. 기존 테스트 스위트(현재 Jest, PHPUnit 및 Python의 unittest)에 통합됩니다.
- [Meticulous.ai](https://www.meticulous.ai/) — 자동으로 생성되고 자동으로 유지 관리되는 엔드투엔드 테스트: 앱이 발전함에 따라 테스트 스위트도 발전합니다.
- [DiffBlue](https://www.diffblue.com/) — Java용으로 자동으로 생성된 단위 테스트입니다.
- [Qodo](https://www.qodo.ai/) — 주요 프로그래밍 언어를 지원하는 비자명 테스트 생성입니다. VS Code 및 JetBrains용 확장 프로그램이 있습니다. (이전에는 Codium)
- [DeepUnit](https://www.deepunit.ai/) — 사려 깊은 테스트 케이스 및 완전한 단위 테스트 파일 생성입니다. 대화형 VS Code 확장 프로그램, npm 패키지, CLI 또는 CI/CD 파이프라인으로 사용할 수 있습니다.
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — 코드에서 취약점을 찾아 테스트를 생성하여 개발자 생산성 및 코드 보안을 가속화합니다. 오픈 소스이며 CLI 또는 CI/CD 파이프라인으로 사용할 수 있습니다.
- [KushoAI](https://kusho.ai/) — Postman 컬렉션, OpenAPI 사양, curl 명령 등을 CI/CD 파이프라인에 연결되는 포괄적인 테스트 스위트로 변환하는 API 테스트용 AI 에이전트입니다.
- [Test Gru](https://gru.ai/home#test-gru) — 엔터프라이즈 수준의 단위 테스트 자동화 서비스를 제공합니다.

- [AgentsKB](https://agentskb.com) - AI 어시스턴트를 위한 전문 지식 계층입니다. AI가 검색하고, 우리가 연구합니다. 그것이 차이점입니다.

## 평가

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — 코딩 에이전트 평가를 위한 벤치마크 스위트입니다. 구성 비교, 메트릭 추적 및 저장소의 실제 문제로 A/B 테스트를 수행합니다.

## 자료

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — 오픈 소스 AI 및 개발자 도구 프로젝트에 대한 엄선된 심층 튜토리얼입니다.
- [Havoptic](https://havoptic.com/) — AI 코딩 도구의 릴리스를 추적하는 무료 오픈 소스 타임라인입니다. 매일 자동 업데이트됩니다. [소스](https://github.com/scotthavird/havoptic.com)


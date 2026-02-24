> **🌍 语言 / Languages:**
> [中文](./README.zh.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [Русский](./README.ru.md)

# ⚡️🧑‍💻 素晴らしいAI搭載開発者ツール

これは、AIを活用した開発者ツールの厳選されたリストです。これらのツールは、コード補完、リファクタリング、デバッグ、ドキュメント作成などのタスクで開発者を支援するためにAIを活用しています。

- [IDEs](#ides)
- [Gitクライアント](#git-clients)
- [アシスタント](#assistants)
  - [Webベース](#web-based)
  - [IDE拡張機能](#ide-extensions)
  - [コマンドライン](#command-line)
  - [デスクトップ](#desktop)
- [シェルアシスタント](#shell-assistants)
- [エージェント](#agents)
- [PRエージェント](#pr-agents)
- [アプリジェネレーター](#app-generators)
- [UIジェネレーター](#ui-generators)
- [スニペットジェネレーター](#snippet-generators)
- [ドキュメンテーション](#documentation)
- [OpenAIプラグイン](#openai-plugins)
- [検索](#search)
- [テスト](#testing)
- [評価](#evaluation)
- [リソース](#resources)

## IDEs

- [Google Antigravity](https://antigravity.google/) — 自律型AIエージェントを編成し、複雑なコーディングタスクを計画、実行、検証するエージェントファーストのIDEで、ブラウザとの深い統合が特徴です。
- [Crystal](https://github.com/stravu/crystal) — 並行Claude Codeセッションを管理、検査、テストするための新しいタイプの開発環境です。
- [Cursor](https://www.cursor.com/) — チャット、編集、生成、デバッグ機能を備えたIDEです。VSCodiumからフォークされているため、インターフェースはVS Codeに似ています。OpenAIを使用しています。
- [PearAI](https://trypear.ai/) — チャットとインラインコード生成機能を備えたVS Codeのオープンソースフォークです。
- [Melty](https://melty.sh/) — チャット、変更プレビュー、AIによるコミット作成機能を内蔵したVS Codeのオープンソースフォークです。現在、ソースコードのみが利用可能です。
- [Replit](https://replit.com/) — クラウド開発環境、コード補完、チャット、ソフトウェア開発エージェント、デプロイ機能を備えたWebベースのIDEです。
- [Mutable](https://github.com/mutableai/monitors4codegen) — チャットボットとGitHubが統合されたWebベースのIDEです。
- [CodeStory](https://codestory.ai/) — チャット、コード説明、自動生成コミット、PRサマリー機能を備えたIDEです。VSCodiumからフォークされています。
- [UI Pilot](https://ui-pilot.com/) — GPT-4を使用してMaterial UIでフォームを作成するチャットベースのAIコードエディターです。
- [GitWit](https://gitwit.dev/) — AIを使用してReactJSアプリケーションを構築するためのWebベースのエディターです。
- [Windsurf](https://windsurf.com) — チャット、編集、生成、デバッグ機能を備えたIDEです。VSCodiumからフォークされているため、インターフェースはVS Codeに似ています。以前はCodeiumとして知られていました。
- [Theia IDE](https://theia-ide.org/#theiaide) — 任意のLLMを使用して、チャット、コード補完、ターミナル支援、カスタムエージェントなどのAI搭載機能を提供する拡張可能なオープンソースIDE（Webおよびデスクトップ）です。[Theia AI](https://eclipsesource.com/blogs/2024/10/07/introducing-theia-ai/)上に構築されており、カスタムのAI搭載ツールやIDEの作成を可能にするように設計されたプラットフォームです。
- [OneCompiler](https://onecompiler.com/) — Java、Python、MySQL、C++、HTMLを含む70以上の言語をサポートし、コードの記述、実行、共有ができる無料のAI搭載オンラインコンパイラです。
- [trae](https://www.trae.ai/) — Traeは、作業方法を変革し、より速く実行するために協力する適応型AI IDEです。
- [Zed](https://zed.dev/) - AtomとTree-sitterの作成者による、高性能なマルチプレイヤーコードエディターです。
- [Nimbalyst](https://nimbalyst.com) - Claude CodeとCodexのエージェント管理環境です。マークダウン、モックアップ、Excalidraw、コードのインタラクティブなビジュアル編集。並行セッション管理。

## Gitクライアント

- [GitBrain](https://gitbrain.dev/) — Gitワークフローを簡素化するGitクライアントです。コード変更を分割し、コード変更の要約とコミットメッセージを生成します。OpenAIを使用しています。
- [GitButler](https://gitbutler.com/) — 既存のワークフローの上に複数のブランチを同時に扱うためのGitクライアントです。従来のコミットメッセージ生成にはデフォルトでOpenAIを使用しますが、Perplexityに変更することも可能です。
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) - AIを使用して高品質なGitコミットメッセージとプルリクエストの説明を自動生成するCLIツールです。

## アシスタント

### Webベース

- [Replit Ghostwriter Chat](https://replit.com/site/ghostwriter) — [Replit](https://replit.com/)に組み込まれたアシスタントで、チャット、プロアクティブなデバッグ、オートコンプリート機能を備えています。チャットにはOpenAIを、オートコンプリートには[replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) (OS)を使用しています。
- [Unblocked](https://getunblocked.com/) — GitHub、Slack、Jira、Confluenceなどの既存の知識でソースコードを拡張します。チャットやIDEのファイルレベルのコンテキストを通じて回答を得られます。Web、macOS、Slack、VSCode、JetBrains IDEで利用可能です。
- [Sourcegraph Cody](https://about.sourcegraph.com/cody) — チャット、リファクタリング、単体テスト生成機能を備えたアシスタントです。VS CodeとIntelliJ用の拡張機能があります。Webアプリとしても利用可能です。
- [Magnet](https://www.magnet.run/) — リポジトリと課題をコンテキストとするWebベースのチャットボットです。
- [Adrenaline](https://useadrenaline.com/) — AIとASTを使用してコードベースに関する質問に答えるWebベースのチャットボットです。
- [CodeSquire](https://codesquire.ai/) — Google Colab、BigQuery、JupyterLabにオートコンプリートを追加するChrome拡張機能です。
- [Incognito Pilot](https://github.com/silvanmelchior/IncognitoPilot) — Pythonエディターとインタープリターを内蔵したオープンソースアシスタントです。
- [Onboard](https://www.getonboardai.com) — 公開およびプライベートなコードベースについてAIとチャットできます。
- [Code to Flow](https://codetoflow.com) — インタラクティブなフローチャートでコードを視覚化、分析、理解します。
- [Pieces](https://pieces.app/) — コードのキャプチャ、強化、再利用、コラボレーションの合理化、ワークフローの文脈理解を通じて複雑な問題を解決するのに役立つオンデバイスのコパイロットです。
- [Wren AI](https://getwren.ai/oss) — SQL AIエージェント。SQLを書かずに質問することで、より速く結果と洞察を得られます。オープンソースです！
- [TEXT2SQL.AI](https://www.text2sql.ai/) — AI搭載のSQLクエリビルダーです。平易な英語を使用して複雑なSQLクエリを翻訳、説明、修正します。
- [SQLAI.ai](https://www.sqlai.ai/) — AIがSQLクエリを生成、修正、説明、最適化します。独自のデータベーススキーマを追加し、AIにそれを理解させるように学習させることができます。
- [CodeWP](https://codewp.ai/) — WordPress開発者向けに特別に訓練されたAIチャットおよびコーディングツールです。WordPressでのコードスニペットおよびプラグインのAIコード生成。
- [Gru.ai](https://www.gru.ai/) — AI開発者が、アルゴリズムの構築、問題のデバッグ、ソリューションのテスト、プログラミングの質問への回答など、技術的な問題解決や日常のコーディングタスクを支援します。

### IDE拡張機能

- [GitHub Copilot](https://github.com/features/copilot) — チャット、プルリクエストテキスト生成、単体テスト生成機能を備えたVS Code拡張機能です。
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) — ユーザーの許可を得てファイルを作成/編集、コマンド実行、ブラウザ使用が可能なVS Code用の自律型コーディングエージェントです。OpenRouter、Anthropic、OpenAI、Google Gemini、AWS Bedrock、Azure、GCP Vertexを含む複数のAIプロバイダーをサポートしています。
- [Refact AI](https://refact.ai/) [Source](https://github.com/smallcloudai/refact) — チャット、補完、リファクタリング、コードベース固有のファインチューニング機能を備えたオープンソースアシスタントです。VS CodeとJetBrains用の拡張機能があります。
- [Continue](https://continue.dev/) — チャット、リファクタリング、コード生成機能を備えたVS Code拡張機能です。複数のファイルを編集し、ユーザーに代わってコマンドを実行します。
- [Blackbox AI](https://www.useblackbox.io/) — オンラインコーディングリファレンスへのリンクを含むオートコンプリートとチャット機能を備えたVS Code拡張機能です。
- [CodeGeeX](https://codegeex.cn/) — CodeGeeX LLMをベースにしたオープンソースアシスタントで、チャット、補完、リファクタリング機能を備えています。VS Code、PyCharmを含む9つのエディター用の拡張機能があります。
- [Quack AI](https://www.quackai.com/) — プロジェクトのコーディングガイドラインを遵守するためのVS Code拡張機能です。
- [Tabby](https://tabbyml.github.io/tabby/) — オープンソースの自己ホスト型コード補完アシスタントです。VS CodeとVim用の拡張機能があります。
- [Tabnine](https://www.tabnine.com/) [(Source)](https://github.com/codota/TabNine) — オープンソースの自己ホスト型コード補完アシスタントです。VS Code、IntelliJ、Neovim、Eclipse、PyCharmを含む15のエディター用の拡張機能があります。
- [CodeMate](https://www.codemate.ai/) — コードのデバッグと最適化のためのVS Code拡張機能です。
- [AskCodi](https://www.askcodi.com/) — VS Code、JetBrains、Sublime Text用の拡張機能を備えたAIコーディングアシスタントです。
- [Rubberduck](https://github.com/rubberduck-ai/rubberduck-vscode) — Visual Studio Codeのサイドバー用のオープンソースチャットアシスタントです。
- [CodeComplete](https://codecomplete.ai/) — 自己ホスト型エンタープライズ補完アシスタントです。
- [GoCodeo](https://www.gocodeo.com/) - GoCodeoは、ワンクリックのVercelデプロイとシームレスなSupabase統合により、フルスタックアプリを簡単に構築およびデプロイできるAIエージェントです。
- [JetBrains AI](https://www.jetbrains.com/ai/) — すべてのJetBrains IDEで利用可能なAIアシスタントです。
- [aiXcoder](https://www.aixcoder.com/en/) — IntelliJ IDEA、CLion、GoLand、PyCharm、WebStorm、Visual Studio Code、Eclipse用の拡張機能を備えたローカルまたはクラウドベースのアシスタントです。
- [Sourcery](https://sourcery.ai/) — 160のPythonベストプラクティスと40以上のJS/TSベストプラクティスのリファレンスを備えたAIアシスタントおよびリンターです。VS Code、PyCharm、vim、Sublime用の拡張機能があります。
- [Swimm](https://swimm.io) — 静的解析とAI生成ドキュメントを使用した文脈コード理解のためのアシスタントです。VSCode、Jetbrains、IntelliJ、WebStorm、Rider、PhpStorm、Android Studio、PyCharm、PhPStormで利用可能です。
- [Supermaven](https://supermaven.com/) — 30万トークンのコンテキストウィンドウを備えたオートコンプリート用のVS Code拡張機能です。
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) — VS CodeやIntelliJ IDEAなどのIDE用の拡張機能を備えたAIコーディングアシスタントです。Amazon Q Developer IDEプラグインには、コードをスキャンしてセキュリティ問題の強調表示と定義（/review）、ドキュメントの作成（/doc）、単体テストの作成（/test）、Javaの新しいバージョンへのアップグレード支援（/transform）を行うことができる多数のエージェントがあります（以前はAmazon CodeWhispererとして知られていました）。
- [Android Studio Bot](https://developer.android.com/studio/preview/studio-bot) — Studio Botは、Android Studioに密接に統合されたAI搭載のコーディングアシスタントです。Studio Botは、Android開発者がコードを生成し、関連リソースを見つけ、ベストプラクティスを学び、時間を節約するのに役立ちます。
- [IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z) — watsonx Code Assistant for Zは、コード生成機能を備えたAI搭載のメインフレームアプリケーションモダナイゼーション製品です。機能には、アプリケーションの検出と分析、自動コードリファクタリング、COBOLからJavaへの変換が含まれます。
- [EasyCode](https://www.easycode.ai/) — GPT-4チャット機能を備えたVS Code拡張機能です。
- [Kilo Code](https://kilocode.ai) - VS Code内でコードの計画、構築、修正を行うためのオープンソースAIコーディングアシスタントです。
- [FlyonUI MCP](https://flyonui.com/mcp) — FlyonUI MCP - Tailwind AI BuilderをIDEに直接統合し、FlyonUIにインスパイアされた素晴らしいTailwind CSSコンポーネント、ブロック、ページを作成します。
- [Traycer](https://traycer.ai) - VS Codeのプランファーストコーディングアシスタントです。
- [shadcn/studio MCP](https://shadcnstudio.com/mcp) - shadcn/studio MCPサーバーをお気に入りのIDEに直接統合し、shadcn/studioにインスパイアされた素晴らしいshadcn/uiコンポーネント、ブロック、ページを作成します。

### コマンドライン

- [Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html?trk=fd6bb27a-13b0-4286-8269-c7b1cfaa29f0&sc_channel=el) - コマンド補完、意図をコマンドに変換する生成AIを使用したコマンド翻訳、およびコード作成を支援するコンテキスト管理を備えた完全なエージェントチャットインターフェースを提供するCLIです。MacOS、Linux、Windows（wsl経由）の多くのターミナルとシェルで動作します。
- [aloc](https://github.com/modern-tooling/aloc) — RustとRatatuiで構築された、モダンなAI拡張コード行数カウンターです。正確なプロジェクト見積もりのためにAIの労力プロファイルを使用します。
- [talk-codebase](https://github.com/rsaryev/talk-codebase) — リポジトリをコンテキストとするCLIチャットボットです。OpenAIだけでなく、GPT4All経由でローカルで実行されるLLMもサポートしています。
- [gptcomet](https://github.com/belingud/gptcomet) — コミットメッセージの生成と変更のレビューを支援するCLIツールです。複数のプロバイダーと言語をサポートしています。
- [poorcoder](https://github.com/vgrichina/poorcoder) — コードコンテキストの抽出、マークダウンからの変更の適用、WebベースのLLMを使用したAIコミットメッセージの生成を行うBashスクリプトのコレクションです。
- [Vibe Compiler (vibec)](https://github.com/Strawberry-Computer/vibe-compiler) — LLM生成を使用して、マークダウンベースのプロンプトスタックをコードとテストに変換する自己コンパイルツールです。Claude、ChatGPT、Grokを含むOpenRouter経由で任意のLLMと連携します。
- [cmd-ai](https://github.com/BrodaNoel/cmd-ai) - 自然言語を実行可能なシェルコマンドに変換します（例: `ai Tell me the free space on disk`）。
- [promptext](https://github.com/1broseidon/promptext) — 正確なトークンカウント、関連性優先順位付け、予算管理を備えたAIアシスタント向けのスマートなコードコンテキスト抽出ツールです。LLMトークン制限内で最適化されたコードコンテキストを準備します。
- [Baz CLI](https://github.com/baz-scm/baz-cli) - 実際のコード、差分などにアクセスできるAI支援コードレビュー用のCLIです。
- [AdaL](https://sylph.ai/) — モデルのコラボレーション（Claude、GPT、Gemini）を可能にする自己進化型AIコーディングエージェントです。ローカルで実行され、コードベースのパターンを学習します。
- [Tokscale](https://github.com/junhoyeo/tokscale) — AIコーディングエージェント（OpenCode、Claude Code、OpenClaw、Codex、Gemini CLI、Cursor IDE、AmpCode、Factory Droid）からのトークン使用量を追跡するためのCLIツールで、グローバルリーダーボードと2D/3D貢献グラフを備えています。
- [vsync](https://github.com/nicepkg/vsync) — Claude Code、Cursor、OpenCode、Codex間でスキル、MCPサーバー、エージェント、コマンドを自動フォーマット変換（JSON ↔ TOML ↔ JSONC）で同期するCLIツールです。
- [Arctic](https://github.com/arctic-cli/interface): 複数のAIコーディングプランとAPIを、組み込みの使用状況とクォータの可視性で統合するターミナルファーストのTUIです。

### デスクトップ

- [Memex](https://memex.tech/) — デスクトップ上で、自然言語だけで、あらゆるスタックで何でも構築できます。
- [Pieces](https://pieces.app/) — 開発者の生産性向上を支援するために設計されたAI対応デスクトップアプリケーションおよびブラウザ拡張機能です。

## シェルアシスタント

- [AskCommand](https://www.askcommand.cppexpert.online/) — AIを使用してテキストからUnixコマンドを自動生成するWebベースのツールです。
- [Butterfish](https://butterfi.sh) — ChatGPTをシェルに埋め込み、簡単にアクセスできるようにするCLIツールです。シンプルなエージェント機能も含まれています。
- [Shell Whiz](https://github.com/beimzhan/shell-whiz) — シェルコマンドを生成し、その説明を得るための高度に設定可能なCLIアシスタントです。
- [GitFluence](https://www.gitfluence.com/) — AI駆動型ソリューションを使用して最も関連性の高いGitコマンドを提案することで、テキスト記述からターミナルまたはCLI用のGitコマンドを自動生成するWebベースのGitコマンドジェネレーターです。
- [AutoComplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - <TAB><TAB>と入力するだけで、AI搭載のコマンドライン提案をターミナルに直接追加するCLIツールです。
- [code-collator](https://github.com/tawandakembo/code-collator) — コードベース全体を言語モデルに記述する単一のマークダウンファイルを作成するCLIツールです。API経由ではなく、Claude/ChatGPTのWebインターフェースからのAIコーディング支援に役立ちます。
- [Warp](https://www.warp.dev/) - WarpはAIとチームの知識を単一の高速で直感的なターミナルに統合します。
- [TmuxAI](https://tmuxai.dev/) - AI搭載の非侵入型ターミナルアシスタントです。
- [intelli-shell](https://github.com/lasantosr/intelli-shell) - 動的な補完とAI統合を備えたコマンドテンプレート/スニペットを管理します。

## エージェント

- [Smol Developer](https://github.com/smol-ai/developer) — プロンプトからリポジトリを生成するCLIエージェントです。OpenAIとAnthropicを使用しています。
- [Aider](https://github.com/paul-gauthier/aider) — リポジトリに変更を生成し、コミットするCLIアシスタントおよびエージェントです。OpenAIを使用しています。
- [Blinky](https://github.com/seahyinghang8/blinky) — SWE-agentにインスパイアされた、バックエンドエラーを特定して修正するVS Code用のデバッグエージェントです。
- [Mentat](https://www.mentat.ai/) — リポジトリに変更を加えるCLIアシスタントおよびエージェントです。
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) — プロンプトからリポジトリを生成し、明確化の質問をするCLIエージェントです。
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate) — フルスタックアプリケーションをある言語またはフレームワークから別の言語またはフレームワークに変換するCLIエージェントです。GPT-4 32kコンテキストを使用しています。
- [Grit](https://app.grit.io) — メンテナンス作業やその他の開発作業を自動化するためのGitHub統合エージェントです。
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Llama 2の力で自動生成AIアプリジェネレーターです。
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — DevOpsGPT: AI駆動型ソフトウェア開発自動化ソリューションです。
- [Second.dev](https://www.second.dev/) — フルスタックアプリに機能を追加するためのプラットフォームです。
- [Factory](https://www.factory.ai/) — コード生成用のエージェントです。ウェイティングリスト。
- [sudocode](https://sudocode.ai/) — Code Interpreterに似た、プロジェクト生成用のWebベースのチャットアシスタントです。
- [CodeFlash AI](https://www.codeflash.ai/) — AIを使用してPythonコードを最適化するためのCLIおよびCIツールです。
- [Micro Agent by Builder](https://www.builder.io/blog/micro-agent) — コードを記述および修正するAIエージェントです。
- [Fine](https://fine.dev/?ref=awesome) — 退屈な作業を自動化するAI開発環境です。GitHub、Sentry、Linearを統合します。コンテキストに応じた質問への回答を得られます。変更の計画、設計、実装を行います。自己修復CI/CDを自動化します。
- [Potpie](https://potpie.ai) — コードベース用のオープンソースAIエージェントを数分で作成できます。Q&A、テスト、デバッグ、システム設計用の事前構築済みエージェントを使用したり、独自の目的別エージェントを作成したりできます。
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) — インテリジェントな自動検出と標準化されたインターフェースを通じて複数のAIコーディングアシスタントを統合するゼロ構成MCPサーバーです。
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) - Anthropicのエージェント型コーディングツールです。
- [Open Agent](https://github.com/Th0rgal/openagent) — 隔離されたコンテナワークスペースとリアルタイムのミッションストリーミングを備えたClaude Code用の自己ホスト型コントロールプレーンです。
- [Agentic Sprint](https://github.com/damienlaine/agentic-sprint) — 調整された専門エージェント（Python、Next.js、CI/CD、QA、UIテスト）を備えた、仕様駆動型の自己反復型マルチエージェントフレームワークです。
- [Leap.new](https://leap.new/) - 実際のバックエンドサービス、APIを備えた機能的なアプリを構築し、クラウドにデプロイします。
- [Recurse ML](https://recurse.ml) - AI生成コードのバグを見つけます。
- [Zenable](https://zenable.io/) — チームの標準を学習し、コーディングエージェントがそれに従うことを保証するAIガードレールで、速度と品質を最大化します。
- [Trellis](https://github.com/mindfold-ai/Trellis) - Claude CodeとCursorのためのオールインワンAIフレームワーク＆ツールキットです。タスク、仕様、マルチエージェントパイプラインを管理します。

## PRエージェント

- [Greptile](https://greptile.com/code-review-bot) — コードベースの完全なコンテキストでGitHub/GitlabのPRをレビューするAIボットです。
- [Macroscope](https://macroscope.com/code-review) - ASTを使用してコードベースのグラフベースの表現を構築し、課題管理システムからコンテキストをプルするGitHub用のAI搭載コードレビューです。
- [EntelligenceAI](https://entelligence.ai/pr) — ユーザーコメントに基づいて時間とともに改善される、GithubおよびGitlab用のAI搭載コードレビューです。
- [Sweep](https://github.com/sweepai/sweep) — AIジュニア開発者: 課題からプルリクエストを生成、テスト、自己レビューするためのGitHub統合です。
- [Codegen](https://www.codegen.com/) — エンタープライズコードベース向けのGPT-4ベースのPRエージェントです。
- [Code Review GPT](https://github.com/mattzcarey/code-review-gpt) — PRをレビューするためのオープンソースツールです。GitHubアクション、Gitlab CLI、またはローカルで動作します。
- [Qodo PR Agent](https://github.com/qodo-ai/pr-agent) — 自動コードレビュー用のオープンソースツールです。Qodoは以前Codiumとして知られていました（「E」のCodeiumと混同しないでください）。
- [Nova](https://www.trynova.ai/) — 新しいPRに要約やテストなどのアクションを追加するCIボットです。
- [CodeRabbit](https://coderabbit.ai/) — PRに要約やコード提案を追加するためのカスタマイズ可能なCIです。
- [SwePT](https://github.com/keerthanpg/SwePT) — 150行のPythonコードで書かれたオープンソースPRジェネレーターです。
- [Duckie](https://duckie.ai/) — GitHubリポジトリを変更するためのWebベースのチャットアシスタントです。
- [PR Explainer Bot](https://pr-explainer-bot.web.app/) — 新しく作成されたPRに説明テキストを追加するGitHub統合です。
- [Goast](https://goast.ai/) — エラーログを取り込み、修正を提案するホスト型ツールです。
- [Corgea](https://corgea.com/) — 脆弱なコードを見つけて修正するGitHub統合です。
- [vx.dev](https://github.com/Yuyz0112/vx.dev) — shadcn、lucide、nivo chartsの組み込みサポートを備えたUI生成に焦点を当てたGitHub統合です。
- [Pixee](https://pixee.ai) — Pixeebotはコード内のセキュリティとコード品質の問題を発見し、推奨される修正を含むマージ可能なプルリクエストを作成します。
- [CodeAnt AI](https://www.codeant.ai/) — コードの問題を修正するためのPRを自動的に作成します。
- [What The Diff](https://whatthediff.ai/) — プルリクエストの差分をレビューし、変更内容を平易な英語で記述するAI搭載アプリです。
- [Trag](https://usetrag.com/) — 事前定義された指示とパターンを備えたAI搭載コードレビューです。
- [CodeReviewBot](https://codereviewbot.ai/) — GitHub用のAI搭載コードレビューです。
- [Callstack.ai Code Reviewer](https://callstack.ai/code-reviewer) — バグ、セキュリティ問題、パフォーマンスのボトルネックを特定するように設計された、GitHub用のAI搭載PRレビューアです。
- [Matter AI](https://matterai.dev) - エンジニアリングチームが自信を持ってコードをリリースするのを支援するオープンソースAIコードレビューアです。
- [Gito](https://github.com/Nayjest/Gito) - 任意の言語モデルで、ローカルまたはGitHub Actionsで動作するAIコードレビューアです。
- [Baz](https://baz.co) - チームのガイドラインと慣習に合わせて調整されたAIコードレビューアです。カスタマイズ可能、適応性があり、応答性が高く、コンテキストのために他の開発者ツールと統合されています。

## アプリジェネレーター

- [Pico](https://picoapps.xyz) — インスタントデプロイメントを備えたエンドツーエンドのマイクロアプリジェネレーターです。
- [Co.dev](https://www.co.dev/) — フルスタックアプリケーションの構築とデプロイを支援するAI搭載アプリ開発プラットフォームです。
- [SoftGen](https://softgen.ai/) — Webアプリ構築のためのAI搭載ソフトウェア生成プラットフォームです。
- [LlamaCoder](https://llamacoder.together.ai/) — オープンソースLLMを使用してアプリケーションを構築するためのオープンソースコード生成モデルです。
- [e2b_Fragments](https://fragments.e2b.dev/) — サンドボックス環境を備えたAI搭載アプリケーションを構築およびデプロイするためのプラットフォームです。
- [Bolt.new](https://bolt.new) — WebContainersを使用して、ブラウザで直接フルスタックアプリケーションをプロンプト、実行、編集、デプロイできるAI搭載Web開発エージェントです。npmパッケージ、Node.jsサーバー、サードパーティAPIをサポートしています。
- [Bolt.diy](https://github.com/stackblitz-labs/bolt.diy) — Groq、Anthropic、Ollama、OpenRouter、Gemini、LMStudio、Mistral、xAI、HuggingFace、DeepSeekを含む複数のLLMプロバイダーをサポートするBolt.newのオープンソースバージョンです。
- [Srcbook](https://github.com/srcbookdev/srcbook) — AIアプリビルダーとTypeScriptノートブックを備えたTypeScript中心のアプリ開発プラットフォームです。
- [Capacity](https://capacity.so) — 自然言語のプロンプトを完全に機能するWebアプリケーションに変換するAI搭載フルスタックWebアプリ開発です。
- [Lovable](https://lovable.dev/) — 自然言語記述またはデザインを、組み込みのデプロイメントとGitHub統合を備えた完全に機能するアプリケーションに変換するAI搭載フルスタックアプリ開発プラットフォームです。
- [Literally anything](https://literallyanything.io) — HTMLおよびJavaScript Webアプリジェネレーターです。
- [GPT Web App Generator](https://magic-app-generator.wasp-lang.dev/) — 短い説明からフルスタックのReact/Node.js/Prisma/Waspアプリを生成します。
- [Make Real](https://makereal.tldraw.com/) — HTML/JavaScriptアプリの生成に使用できるオンラインキャンバスです。
- [Marblism](https://marblism.com) — プロンプトからSaaSボイラープレートを生成します。
- [Glowbom](https://glowbom.com/) — AIでアプリを生成し、複数のプラットフォームにエクスポートします。
- [Mage](https://usemage.ai/) — Wasp、React、Node.js、PrismaでフルスタックWebアプリを生成します。
- [ScrollHub](https://hub.scroll.pub/) — Scrollプログラミング言語を使用してウェブサイトを生成および公開します。
- [Taskade Genesis](https://taskade.com/genesis) — 自然言語を使用してカスタムAIエージェント、ワークフロー、アプリを構築するためのAI搭載プラットフォームです。マルチモデルサポート（GPT-4o、Claude、Gemini）、オープンソースMCPサーバー。

- [Berrry](https://berrry.app) — ソーシャルメディアの投稿を機能的なWebアプリケーションに変換するTwitterアプリジェネレーターです。ツイートやRedditのコンテンツをユニークなサブドメインを持つ完全なアプリに変換します。
- [Blank Space](https://www.blankspace.build/) — 自然言語を使用してWebアプリケーションを作成するためのオープンソースAIアプリビルダーです。v0、Lovable、Boltの自己ホスト型代替です。
- [Fastshot](https://fastshot.ai/) — モバイルアプリを構築およびデプロイするためのAI駆動型ノーコードプラットフォームです。

## UIジェネレーター

- [v0](https://v0.dev/) — ブラウザで新しいUIコンポーネントを作成および反復します。
- [Rendition Create ](https://www.renditioncreate.com/) — ブラウザで新しいUIコンポーネントを作成および反復します。
- [Rapidpages](https://github.com/rapidpages/rapidpages) — オープンソースUIジェネレーターです。
- [Magic Patterns](https://www.magicpatterns.com/) — 製品のアイデアをプロトタイプ化します。プロンプト、画像のアップロード、または[Chrome拡張機能](https://www.magicpatterns.com/extension)を使用したデザインインスピレーションのインポートが可能なUIジェネレーターウェブサイトです。[プラグイン](https://www.figma.com/community/plugin/1304255855834420274)を使用してFigmaにエクスポートできます。Shadcn、ChakraUI、HTML + Tailwindを含む多数のコンポーネントシステムをサポートしています。
- [Tempo ](https://www.tempolabs.ai/) — Reactインターフェース用のWYSIWYGエディターです。
- [Kombai](https://kombai.com/) — Figmaからフロントエンドコードを生成するためのAIツールです。
- [CodeParrot](https://www.codeparrot.ai/) — Figmaからフロントエンドコードを生成するVS Codeプラグインです。既存のコンポーネント、ライブラリ、コーディング標準を再利用して、既存のコードベースに完璧にフィットするコードを生成します。プロンプトは不要です。
- [Galileo AI](https://www.usegalileo.ai/) — テキストからUIへのプラットフォームです。ウェイティングリスト。
- [Uizard](https://uizard.io/) — テキストプロンプトからマルチスクリーンモックアップを生成し、ドラッグアンドドロップエディターで編集します。アプリのスクリーンショットや手書きのワイヤーフレームをスキャンし、編集可能なアプリモックアップに変換します。
- [Frontly](https://fronty.com/) — アップロードされた画像をHTML CSSコードに変換します。
- [BoringUi](https://www.boringui.xyz/) — JSONデータを使用して美しいUIを作成します。生成されたUIはHTMLとTailwind CSSで、コードをコピーでき、UIはリンクを使用して誰とでも共有できます。
- [CSS Picker](https://csspicker.dev/) - 既存のデザインからUIをコピーし、AIで反復します。ウェブサイトからのCSSコピー（[CSS Picker Extension](https://chromewebstore.google.com/detail/csspicker-copy-css-from-w/laooinkgdapbcbjchpmihliljfnakkdh)による）、画像からコード、テキストからUIをサポートします。

## スニペットジェネレーター

- [CodePal](https://codepal.ai/) — コードを迅速に生成またはリファクタリングするためのWebツールです。
- [AI Code Convert](https://aicodeconvert.com/) — プログラミング言語間でコードを翻訳するためのWebツールです。
- [AI Code Playground](https://aicodeplayground.com/) — コードをリファクタリングおよび改善するためのWebツールです。
- [AutoRegex](https://www.autoregex.xyz/) — AutoRegexはOpenAIのGPT-3を使用して、平易な英語から正規表現を生成します。
- [unpkg.ai](https://unpkg.ai/) — オープンソースのAI搭載ESMモジュール生成サービスです。迅速なプロトタイピングのためにURL経由でJavaScriptモジュールを生成します。

## ドキュメンテーション

- [Trelent](https://trelent.net/) — ドキュメント文字列を生成するVS Code拡張機能です。独自のモデルを使用しています。
- [DiagramGPT](https://www.eraser.io/diagramgpt) — DiagramGPTは、スキーマ、インフラ定義、コードスニペット、または平易な言語記述をダイアグラムに変換する無料のAIベースのWebアプリです。このツールは、フローチャート、エンティティ関係図、クラウドアーキテクチャ図、シーケンス図を生成できます。
- [DocuWriter.ai](https://www.docuwriter.ai/) — ソースコードファイルから自動化されたコードおよびAPIドキュメントを生成するAI搭載Webアプリです。
- [README-AI](https://github.com/eli64s/readme-ai) — 大規模言語モデルAPIを搭載した自動README.mdファイルジェネレーターです。
- [Supacodes](https://www.supacodes.com) — Githubでコードドキュメントの記述と更新を自動化するAIツールです。
- [CodexAtlas](https://codedocumentation.app/) — 最新のAIモデルを使用した自動コードおよびAPIドキュメント。

## 可観測性

- [TraceRoot AI](https://traceroot.ai/) - AIエージェントを使用して本番環境のバグを自動的に修正するAIネイティブの可観測性ツールです。

## OpenAIプラグイン

- [ChatWithGit](https://gitsearch.sdan.io/) — ChatGPTがGitHubを検索し、関連するリポジトリへのリンクを返すことを可能にします。
- [Code ChatGPT Plugin](https://github.com/kesor/chatgpt-code-plugin) — ファイルのディレクトリからコンテキストをプルするChatGPTプラグインのオープンソース例です。

## 検索

- [Bloop](https://bloop.ai/) — リポジトリの自然言語検索です。
- [Buildt](https://www.buildt.ai/) — リポジトリの自然言語検索です。ウェイティングリスト。
- [SeaGOAT](https://kantord.github.io/SeaGOAT/latest/) — コードベースを意味的に検索するためにベクトル埋め込みを活用するローカル検索ツールです。
- [ContextMCP](https://contextmcp.ai) — AIエージェント向けに、さまざまなソースからのドキュメントを横断してセマンティック検索を行う自己ホスト型サービスです。

## テスト

- [Checksum AI](https://checksum.ai) — CI/CD対応のPlaywrightテストをリポジトリに直接生成する、エンドツーエンドの完全自律型QA自動化エージェントです。
- [OctoMind](https://octomind.dev) — 自動メンテナンスと生成されたブラウザベースのエンドツーエンドテストをGithub Actions、Azure DevOpsなどに統合します。
- [Traceloop](https://traceloop.com/) — OpenTelemetryトレースデータと生成AIを使用してシステム信頼性を向上させます。
- [Carbonate](https://carbonate.dev/) — 自然言語を使用したエンドツーエンドテストです。既存のテストスイート（現在はJest、PHPUnit、Pythonのunittest）に統合されます。
- [Meticulous.ai](https://www.meticulous.ai/) — 自動生成され、自動メンテナンスされるエンドツーエンドテスト: アプリの進化に合わせてテストスイートも進化します。
- [DiffBlue](https://www.diffblue.com/) — Java用の自動生成単体テストです。
- [Qodo](https://www.qodo.ai/) — 主要なプログラミング言語をサポートする非自明なテスト生成です。VS CodeとJetBrains用の拡張機能があります。（以前はCodium）
- [DeepUnit](https://www.deepunit.ai/) — 考慮されたテストケースと完全な単体テストファイルの生成です。インタラクティブなVS Code拡張機能、npmパッケージ、CLI、またはCI/CDパイプラインとして利用可能です。
- [MutahunterAI](https://github.com/codeintegrity-ai/mutahunter) — コードの脆弱性を発見し、それらのテストを生成することで、開発者の生産性とコードセキュリティを加速します。オープンソースで、CLIまたはCI/CDパイプラインとして利用可能です。
- [KushoAI](https://kusho.ai/) — Postmanコレクション、OpenAPI仕様、curlコマンドなどを、CI/CDパイプラインに接続する包括的なテストスイートに変換するAPIテスト用AIエージェントです。
- [Test Gru](https://gru.ai/home#test-gru) — エンタープライズレベルの単体テスト自動化サービスを提供します。

- [AgentsKB](https://agentskb.com) - AIアシスタントのための専門知識レイヤーです。AIが検索し、私たちが調査します。それが違いです。

## 評価

- [sniffbench](https://github.com/AnswerLayer/sniffbench) — コーディングエージェントを評価するためのベンチマークスイートです。構成を比較し、メトリクスを追跡し、リポジトリからの実際の問題でA/Bテストを行います。

## リソース

- [Awesome Code Docs](https://github.com/johnxie/awesome-code-docs) — オープンソースAIおよび開発者ツールプロジェクトの厳選された詳細チュートリアルです。
- [Havoptic](https://havoptic.com/) — AIコーディングツールからのリリースを追跡する無料のオープンソースタイムラインです。毎日自動更新されます。[Source](https://github.com/scotthavird/havoptic.com)

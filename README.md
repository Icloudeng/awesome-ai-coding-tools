# Awesome AI Coding Tools

AI tools for developers that help discover, compare, and adopt AI-powered solutions for code generation, refactoring, debugging, testing, documentation, and workflow automation.


## 📑 Table of Contents

- [AI Code Completion & Autocomplete (16)](#ai-code-completion--autocomplete)
- [AI Code Generation (9)](#ai-code-generation)
- [AI Autonomous Agents (10)](#ai-autonomous-agents)
- [AI Code Refactoring Tools (1)](#ai-code-refactoring-tools)
- [Ai Coding Assistants (5)](#ai-coding-assistants)
- [AI Coding Assistants (1)](#ai-coding-assistants-1)
- [AI Debugging & Error Fixing (1)](#ai-debugging--error-fixing)
- [AI Development Environments (3)](#ai-development-environments)
- [AI Documentation Generators (2)](#ai-documentation-generators)
- [AI IDE (1)](#ai-ide)
- [AI IDE Extensions (7)](#ai-ide-extensions)
- [AI Platform Integration (1)](#ai-platform-integration)
- [AI Security & Code Review (11)](#ai-security--code-review)
- [AI Testing & QA Tools (2)](#ai-testing--qa-tools)
- [AI Workflow Automation (4)](#ai-workflow-automation)
- [Low Code AI Builders (2)](#low-code-ai-builders)
- [Low-Code AI Builders (2)](#low-code-ai-builders-1)
- [Model Context Protocol (MCP) (3)](#model-context-protocol-mcp)


## AI Code Completion & Autocomplete

- [Tabnine](https://www.tabnine.com/) - AI code completion with whole-line/function suggestions, chat, and test gen across 30+ IDEs/languages, using proprietary models trained on permitted code. Enterprise features like custom models and on-prem deploy. Veteran tool vs. newer open-source like Tabby. ([Read more](/details/tabnine-com.md)) `Enterprise` `Multi Ide` `Custom Models` `Test Gen`
- [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer) - Amazon CodeWhisperer delivers real-time AI code suggestions, function completions, and security scans optimized for AWS services and 15+ languages. It features reference tracking to avoid licensed code and IDE plugins for VS Code/JetBrains. In enterprise 2026 setups, it's chosen over Copilot for its native AWS integrations and compliance-focused filtering. ([Read more](/details/amazon-codewhisperer.md)) `AWS` `Real Time` `Security Scan` `Enterprise`
- [Augment](https://www.augmentcode.com/) - Augment provides deep-context code completions for large enterprise codebases, leveraging proprietary models fine-tuned on internal repos for unmatched accuracy in Java, Python, and JS. It integrates with VS Code and JetBrains, offering chat-based explanations. Developers in 2026 select it over Tabnine for its superior handling of million-line repos without hallucination risks. ([Read more](/details/augment.md)) `Enterprise` `Context Aware` `VSCode` `JetBrains`
- [CodeComplete](https://codecomplete.ai) - CodeComplete offers self-hosted AI code completions using fine-tuned models on private codebases, ensuring data sovereignty for enterprises in VS Code and JetBrains. Features cascade suggestions and chat for explanations. Preferred in 2026 regulated industries over SaaS like Copilot for zero telemetry. ([Read more](/details/codecomplete.md)) `Self Hosted` `Enterprise` `Private Models` `VSCode`
- [Codeium](https://codeium.com) - Codeium provides lightning-fast, free AI autocompletions across 70+ languages with enterprise search and Waverly model for codebase chat. Native IDE support includes VS Code, JetBrains, and Vim. In 2026, it captures market share from Tabnine with unlimited usage and on-prem options. ([Read more](/details/codeium.md)) `Free` `Multi Language` `Enterprise` `VSCode`
- [Cosine](https://ai.cosine.sh/) - Cosine AI deeply indexes codebases for precise autocomplete, chat queries, and generation with 99% relevance on private repos via vector embeddings. Supports VS Code and web app. Enterprise 2026 choice for monorepos, outperforming Sourcegraph in AI speed. ([Read more](/details/cosine.md)) `Codebase Indexing` `Vector Search` `Enterprise` `VSCode`
- [FauxPilot](https://github.com/fauxpilot/fauxpilot) - FauxPilot self-hosts CodeGen models as a drop-in Copilot server, providing private AI completions in VS Code/Neovim without data leaks. Docker-deployable with GPT-J/StarCoder fine-tunes. Open-source devs in 2026 revive it for local inference, cheaper than TabbyML on consumer GPUs. ([Read more](/details/fauxpilot.md)) `Self Hosted` `Open Source` `Copilot-alternative` `Docker`
- [Gemini Code Assist](https://developers.google.com/gemini-code-assist) - Google's Gemini Code Assist offers chat/completions in VS Code/Android Studio with Gemini 1.5 Pro for code gen, debugging, and optimizations across 20+ langs. Free tier for individuals, enterprise VPC-deploy. 2026 Google Cloud devs pick it over AWS Q for multimodal code understanding. ([Read more](/details/gemini-code-assist.md)) `Google` `Multi Language` `Free Tier` `VSCode`
- [GitHub Copilot](https://github.com/features/copilot) - AI-powered code completion tool that suggests lines, functions, and entire files in real-time within IDEs like VS Code and JetBrains, using models trained on public GitHub code. Supports over 20 languages with context-aware, natural language-based suggestions for faster coding. Outperforms traditional autocomplete; ideal for solo devs and teams, though subscription-based unlike open-source alternatives like Codeium. ([Read more](/details/github-com.md)) `Context Aware` `Multi Language` `IDE-integration` `Chat Mode`
- [GitLab Code Suggestions](https://docs.gitlab.com/ee/user/project/repository/code_suggestions.html) - AI-powered autocomplete feature embedded in GitLab IDE and web editor, generating context-aware code snippets using repo analysis and custom instructions. Supports 20+ languages with Duo add-ons for chat and reviews; integrates natively without external extensions. GitLab alternative to Copilot for self-hosted teams emphasizing security and compliance over VS Code ecosystem. ([Read more](/details/gitlab-code-suggestions.md)) `Context Aware` `Self Hosted` `Multi Language` `Free Tier`
- [JetBrains AI](https://www.jetbrains.com/ai/) - AI assistant integrated into JetBrains IDEs, offering code completion, chat, and other intelligent features. ([Read more](/details/jetbrains-ai.md)) `IDE Integration` `Code Completion` `Ai Chat`
- [Obsidian Copilot Auto Completion](https://github.com/j0rd1smit/obsidian-copilot-auto-completion) - Auto-completion plugin for Obsidian, enabling AI-powered code suggestions within the note-taking app. ([Read more](/details/obsidian-copilot-auto-completion.md)) `Plugin` `Obsidian` `Auto Completion`
- [Refact.ai](https://refact.ai/) - Open Source coding helper offering completion and refactoring capabilities for developers. ([Read more](/details/refactai.md)) `Open Source` `Code Completion` `Refactoring`
- [Replit Ghostwriter](https://replit.com/site/ghostwriter) - Coding assistant integrated into Replit's online IDE, providing suggestions and edits. ([Read more](/details/replit-ghostwriter.md)) `IDE Integration` `Code Assistant` `Online Ide`
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant embedding codebase intelligence into VS Code/JetBrains for chat, autocomplete, and edits using enterprise LLMs like Anthropic. Leverages Sourcegraph search for precise context retrieval across monorepos. Enterprise-focused alternative to Copilot for code intelligence at scale. ([Read more](/details/sourcegraph-cody.md)) `Codebase Aware` `Enterprise` `Multi LLM` `Code Search`
- [Tabby](https://github.com/TabbyML/tabby) - Open-source self-hosted AI code completion server compatible with Copilot plugin, supporting StarCoder/CodeLlama for private inference. Easy Docker deploy with repo context. Popular Copilot alternative for on-prem needs. ([Read more](/details/tabby.md)) `Open Source` `Self Hosted` `Copilot Compatible` `LLM Agnostic`

## AI Code Generation

- [OpenAI Codex](https://openai.com/index/introducing-codex/) - Predecessor to GPT models powering GitHub Copilot, Codex translates natural language to code across 12+ languages via API. Trained on GitHub public code for docstring-to-function generation. Legacy but foundational for API-based code gen vs. modern chat interfaces. ([Read more](/details/openai-codex.md)) `Api` `Multi Language` `Nl To Code` `Legacy`
- [16x Prompt](https://prompt.16x.engineer/) - 16x Prompt empowers developers to engineer high-precision prompts tailored for AI code generation across diverse LLMs like GPT-4 and Claude. Key features include interactive prompt refinement, code-specific templates for algorithms and APIs, and performance benchmarking against baselines. Perfect for streamlining complex coding workflows in 2026, it outperforms generic tools by focusing exclusively on executable code outputs, unlike broader prompt playgrounds. ([Read more](/details/16x-prompt.md)) `Prompt Engineering` `Code Generation` `LLM-optimized` `Templates`
- [Amazon Q Developer](https://aws.amazon.com/q/developer/build/) - Amazon Q Developer is an AI-powered assistant that accelerates software development by generating code, transforming legacy systems, and optimizing AWS deployments across 15+ languages. It offers agentic features like multi-step reasoning for complex tasks and integrates natively with IDEs and CI/CD pipelines. In 2026, teams favor it over Cursor for its enterprise-grade security and seamless AWS ecosystem synergy. ([Read more](/details/amazon-q-developer.md)) `AWS` `Agentic` `Multi Language` `Enterprise`
- [Atomist](https://atomist.com/) - Atomist automates large-scale code transformations and refactoring across polyglot codebases using AI-driven skill graphs and event triggers. Key features include zero-downtime migrations and custom automation pipelines deployable on Kubernetes. In 2026, it stands out for DevOps teams refactoring monoliths, surpassing manual tools like jQAssistant in speed and safety. ([Read more](/details/atomist.md)) `Refactoring` `Automation` `Polyglot` `DevOps`
- [CensusGPT](https://censusgpt.com/) - CensusGPT translates natural language queries into SQL or API calls for US Census data analysis, generating charts and reports instantly for data devs. Supports Python/JS integrations and fine-tuned on demographic datasets. By 2026, it's a quick-win for analysts over ChatGPT plugins due to specialized accuracy. ([Read more](/details/censusgpt.md)) `Natural Language` `Data Query` `SQL-generation` `Charts`
- [Parsel](https://github.com/ezelikman/parsel) - Open-source framework for LLM algorithmic reasoning, translating natural language specs into executable code via structured prompting and verification loops. Enables reliable multi-step code generation beyond simple completions. Ideal for research prototypes vs. production tools like Devin. ([Read more](/details/parsel.md)) `Open Source` `Reasoning Chain` `Nl To Code` `Research`
- [Poolside AI](https://poolside.ai/) - Specialized AI coding assistant for production-grade code in C++/Rust/Python, with deep semantic understanding for enterprise-scale projects. Focuses on correctness/security over speed. Niche for systems/ML vs. generalists like Copilot. ([Read more](/details/poolside-ai.md)) `Systems Lang` `Enterprise` `Context Aware` `Rust Support`
- [Salesforce CodeGen](https://github.com/Salesforce/CodeGen) - Open-weights LLM family (350M-16B) specialized for code gen, trained on BigQuery public datasets. Supports 12 langs with high pass@1 on HumanEval. Fine-tunable base for custom code models vs. StarCoder. ([Read more](/details/salesforce-codegen.md)) `Open Weights` `Multi Language` `Fine Tunable` `Salesforce`
- [StackSpot AI](https://ai.stackspot.com/) - Enterprise AI platform generating code snippets, assistants, and enforcing standards via studio for custom LLMs/prompts. Integrates with IDEs for contextual suggestions. Brazil-origin tool for regulated industries vs. US-centric Copilot. ([Read more](/details/stackspot-ai.md)) `Enterprise` `Custom Llm` `Standards Enforce` `IDE Integration`

## AI Autonomous Agents

- [Aider Chat](https://aider.chat) - Aider Chat offers a conversational interface for AI-assisted coding, enabling natural language interactions to edit, refactor, and debug code in local repositories. It integrates seamlessly with Git for version control and supports multiple LLMs for flexible model selection. In 2026 dev stacks, it's favored for solo pair-programming sessions over chat-based IDE plugins due to its repository-wide context awareness. ([Read more](/details/aider-chat.md)) `Chat Interface` `Git Integration` `multi-LLM` `Pair Programming`
- [Atlassian Rovo](https://www.atlassian.com/blog/announcements/rovo-dev-command-line-interface) - Atlassian Rovo is a CLI-powered AI agent that automates developer workflows across Jira, Confluence, and Bitbucket using natural language commands. It supports code reviews, ticket triaging, and documentation syncing with multi-LLM backends. By 2026, it's essential for Atlassian stacks, bridging gaps left by generic agents like Devin in enterprise collaboration. ([Read more](/details/atlassian-rovo.md)) `CLI` `Atlassian` `Workflow Automation` `Enterprise`
- [Capacity](https://capacity.so) - Capacity automates developer support tickets and workflows using conversational AI agents that integrate with GitHub, Jira, and Slack for code reviews and deployments. It features multi-turn reasoning and custom toolchains for enterprise ops. In 2026, ops teams prefer it over linear bots for its adaptive, context-rich automations. ([Read more](/details/capacity.md)) `Automation` `Workflows` `Conversational` `Enterprise`
- [Claude Code](https://www.anthropic.com/solutions/coding) - Anthropic's Claude Code agent manages entire repos with multi-file edits, debugging cycles, and architecture planning using constitutional AI for safety. Integrates VS Code/JetBrains with 200k+ token context for monorepos. In 2026 benchmarks, it leads over GPT agents in reliability for production codebases. ([Read more](/details/claude-code.md)) `Multi File` `Repo Agent` `safe-AI` `Anthropic`
- [Cline](https://cline.bot/) - Cline is a terminal-based autonomous agent that executes CLI commands, edits files, and runs tests to complete dev tasks from natural language specs. LLM-agnostic with tool-use for browsers and shells. Devs in 2026 use it for local prototyping, surpassing remote agents in speed and privacy. ([Read more](/details/cline.md)) `CLI` `Autonomous` `LLM-agnostic` `Terminal`
- [Devin](https://devin.ai/) - Devin by Cognition is the first AI software engineer, autonomously planning, coding, debugging, and deploying full apps from specs using shell tools and browsers. Handles real-world GitHub issues end-to-end with 13.86% SWE-bench success. 2026 frontier for agentic dev, evolving beyond Aider in multi-step orchestration. ([Read more](/details/devin.md)) `Autonomous Engineer` `Multi Step` `SWE-bench` `Cognition`
- [Kilo Code](https://kilocode.ai) - Open-source VS Code extension turning AI into autonomous coding agent for planning, generating, and debugging entire features from natural language specs. Supports local LLMs with repo context for privacy-focused workflows. Lightweight Cursor alternative for offline, customizable dev acceleration. ([Read more](/details/kilo-code.md)) `Open Source` `Vscode Extension` `Local Llm` `Multi Step`
- [Plandex](https://github.com/plandex-ai/plandex) - Open-source CLI AI agent for multi-file refactors and features, using snapshots for safe experimentation and git integration. Handles repo-scale changes with human oversight loops. Devin-like autonomy for terminal power users. ([Read more](/details/plandex.md)) `Open Source` `CLI` `Multi File` `Git Integration`
- [Potpie](https://potpie.ai) - Platform for building/deploying custom AI engineering agents tailored to repos and workflows, with no-code config for tasks like review/gen/debug. Supports multi-LLM chaining and GitHub integration. Flexible alternative to fixed agents like Devin for team-specific automation. ([Read more](/details/potpie.md)) `Custom Agents` `No Code` `Github Integration` `Multi LLM`
- [Sourcegraph Amp](https://ampcode.com/) - AI coding agent leveraging Sourcegraph's code graph for codebase queries, edits, and debugging with natural language. Multi-file awareness via universal search. Enterprise Cody evolution for graph-powered agents. ([Read more](/details/sourcegraph-amp.md)) `Code Search` `Multi File` `Agentic` `Enterprise`

## AI Code Refactoring Tools

- [ReSharper](https://www.jetbrains.com/resharper/) - JetBrains .NET productivity tool with AI-enhanced refactoring, code analysis, and navigation for Visual Studio. Automates boilerplate, detects issues, and suggests fixes across C#/VB/F#. Complements JetBrains AI for legacy .NET maintenance vs. Roslyn analyzers. ([Read more](/details/resharper.md)) `.net` `JetBrains` `Refactoring` `Code Analysis`

## Ai Coding Assistants

- [TraceRoot AI](https://github.com/traceroot-ai/traceroot) - AI agents that automatically fix production bugs in code. ([Read more](/details/traceroot-ai.md)) `Bug Fixing` `Agents` `Production`
- [unpkg.ai](https://unpkg.ai) - Service generating ESM JavaScript modules from natural language descriptions. ([Read more](/details/unpkgai.md)) `Javascript` `Esm` `Natural Language`
- [Vibe Compiler](https://github.com/Strawberry-Computer/vibe-compiler) - Self-compiling tool that converts markdown prompt stacks into code and tests using LLMs. ([Read more](/details/vibe-compiler.md)) `Code Generation` `Testing` `Markdown`
- [Wizi](https://github.com/wizi-ai/code-search) - Code search tool across repositories using natural language queries. ([Read more](/details/wizi.md)) `Code Search` `Natural Language` `Open Source`
- [ZZZ Code AI](https://zzzcode.ai/) - AI tool for code generation, explanation, and conversion. ([Read more](/details/zzz-code-ai.md)) `Code Generation` `Explanation` `Conversion`

## AI Coding Assistants

- [v0 by Vercel](https://v0.dev/) - AI-powered tool specialized in generating polished UI code rapidly from natural language descriptions. Displays a comprehensive breakdown of pages, features, and technology choices prior to code generation. Suited for fast frontend prototyping and development. ([Read more](/details/v0-by-vercel.md)) `Code Generation` `Ui Generation` `Frontend`

## AI Debugging & Error Fixing

- [Blinky Debugging Agent](https://github.com/seahyinghang8/blinky) - Blinky is an open-source AI agent that autonomously identifies, reproduces, and fixes bugs in codebases via iterative testing and LLM reasoning. It integrates with pytest and Git for reproducible debugging sessions. By 2026, it's a staple for Python devs seeking Devin-like autonomy without vendor lock-in. ([Read more](/details/blinky-debugging-agent.md)) `Debugging` `Autonomous Agent` `Open Source` `Python`

## AI Development Environments

- [GitHub Codespaces](https://github.com/features/codespaces) - GitHub Codespaces provides instant, cloud-hosted development environments integrated with GitHub repositories, supporting VS Code in browser or desktop with full customization via devcontainers. It enables collaborative coding, debugging, and AI-assisted development through extensions like Copilot, with GPU support and scalable resources. Preferred by remote teams for reproducible setups, it excels over Replit in Git-native workflows and generous free core-hours. ([Read more](/details/github-codespaces.md)) `Cloud Ide` `Devcontainers` `Collab Coding` `Free Tier`
- [Lovable](https://lovable.dev/) - Browser-based AI code editor for generating full apps from descriptions, with collaborative real-time editing and one-click deployments. Leverages frontier models for React/TS apps with built-in auth/UI libs. Stands out vs. Cursor/Replit for instant full-stack prototypes without local setup. ([Read more](/details/lovable.md)) `Browser Based` `Full Stack Gen` `Collab` `Deploy Button`
- [Replit](https://replit.com/) - AI-powered browser IDE with Agent for building apps from prompts, including clarification Q&A and one-click deploys. Supports 50+ langs with collab/hosting. Go-to for education/prototyping vs. Codespaces' enterprise Git focus. ([Read more](/details/replit.md)) `Browser Ide` `Ai Agent` `Deployments` `Free Tier`

## AI Documentation Generators

- [Autodoc](https://github.com/context-labs/autodoc) - Autodoc leverages LLMs to generate comprehensive docs, diagrams, and changelogs from any codebase, supporting Markdown, PlantUML, and API specs. It scans repos holistically for architecture overviews and function docs. In 2026, it's the go-to open-source alternative to Swimm for teams ditching manual doc maintenance. ([Read more](/details/autodoc.md)) `Documentation` `Open Source` `Diagrams` `LLM`
- [Glide AI](https://useglide.ai) - AI-driven tool generating interactive walkthroughs and explanations for pull requests, enhancing code reviews with visual step-by-step guides. Analyzes diffs to highlight changes, risks, and best practices automatically. Complements tools like GitHub Copilot Chat for non-technical reviewers in teams. ([Read more](/details/glide-ai.md)) `Pull Requests` `Walkthroughs` `Visual Explain` `Team Review`

## AI IDE

- [Windsurf](https://windsurf.com) - An agentic AI-powered IDE by Codeium, designed for deep codebase understanding and collaborative coding with AI flows. ([Read more](/details/windsurf.md)) `agentic AI` `code generation` `codebase awareness`

## AI IDE Extensions

- [autocomplete.sh](https://github.com/closedLoop-technologies/autocomplete-sh) - Autocomplete.sh uses GPT models to suggest bash commands in real-time, parsing history and context for precise terminal completions. It's lightweight, privacy-first, and extensible via custom prompts. Ideal for 2026 shell warriors, it edges out Fig.io by running fully offline with local LLMs. ([Read more](/details/autocompletesh.md)) `Bash` `Terminal` `Open Source` `ChatGPT`
- [CodeGPT.nvim](https://github.com/dpayne/CodeGPT.nvim) - Neovim plugin for ChatGPT integration, providing code generation, refactoring, and explanations directly in the editor with custom prompts. Supports multiple models and session persistence. Vim enthusiasts in 2026 pair it with LazyVim configs over native Copilot for lightweight, open extensibility. ([Read more](/details/codegptnvim.md)) `Neovim` `ChatGPT` `Plugin` `Refactoring`
- [Continue](https://continue.dev/) - Continue is an open-source IDE autopilot connecting any LLM (local or cloud) for completions, chat, and edits in VS Code/JetBrains with codebase indexing. Customizable slash commands and diff previews enhance workflow. In 2026, it's the top Ollama companion, flexible unlike locked-in Copilot. ([Read more](/details/continue.md)) `Open Source` `LLM-agnostic` `VSCode` `JetBrains`
- [Cursor](https://cursor.com) - Cursor reimagines VS Code as an AI-native IDE with Composer for multi-file generation, Tab for smart autocompletes, and Agent mode for end-to-end task execution using GPT-4o/Claude. It handles 100k+ context for monorepos and custom rules for style enforcement. 2026 power users ditch vanilla VS Code for its 10x faster iteration cycles over Windsurf or traditional editors. ([Read more](/details/cursor.md)) `AI-IDE` `Multi File` `Agent Mode` `VSCode-fork`
- [OpenMagic](https://github.com/Kalmuraee/OpenMagic) - Browser-side AI coding toolbar for live web app edits with context capture and approval-gated diffs. ([Read more](/details/openmagic.md)) `browser` `editing` `diff`
- [Genie AI ChatGPT VSCode](https://github.com/ai-genie/chatgpt-vscode) - VS Code extension embedding ChatGPT for inline code assistance, prompt libraries, and diff views without leaving the editor. Supports GPT-4 vision for screenshot queries. Neovim-less devs in 2026 use it as lightweight Copilot alt before migrating to Continue. ([Read more](/details/genie-ai-chatgpt-vscode.md)) `VSCode` `ChatGPT` `Extension` `Vision`
- [org-ai](https://github.com/rksm/org-ai) - Emacs Org-mode extension for LLM interactions, enabling code generation, explanation, and editing within literate programming documents. Supports multiple providers for conversational coding in notes. Org-mode power tool akin to NotebookLM for Emacs users. ([Read more](/details/org-ai.md)) `Emacs` `Org Mode` `LLM Agnostic` `Literate Programming`
- [Safurai](https://www.safurai.com/) - Open-source AI VS Code/JetBrains extension for code gen, refactor, docs, and tests using local/remote LLMs. Privacy-focused with repo embeddings. Free alternative to Tabnine for self-hosting enthusiasts. ([Read more](/details/safurai.md)) `Open Source` `Self Hosted` `Multi Ide` `Docs Gen`

## AI Platform Integration

- [GitHub Models](https://github.com/features/models) - Platform for experimenting with, comparing, and prompting frontier AI models like Llama and Mistral directly in GitHub, with playground for rapid iteration. Integrates with Copilot Chat and Codespaces for code-related tasks. Useful for devs evaluating LLMs before production integration, bridging playgrounds like OpenAI and self-hosted options. ([Read more](/details/github-models.md)) `Prompt Playground` `Model Comparison` `Github Integration` `Free`

## AI Security & Code Review

- [CodeReviewBot](https://codereviewbot.ai) - CodeReviewBot AI automates pull request reviews with line-by-line feedback, vulnerability detection, and refactor suggestions across 20+ languages in GitHub/GitLab. It prioritizes critical issues with diff-aware context and integrates Slack notifications. In 2026 CI/CD pipelines, it reduces review cycles 3x faster than human-only processes, complementing tools like Snyk. ([Read more](/details/codereviewbot.md)) `Code Review` `Pull Requests` `Vulnerability Scan` `GitHub`
- [Codiga](https://www.codiga.io/) - Codiga delivers AI-driven code analysis, auto-fixes, and static security scans for real-time quality enforcement in IDEs and PRs, supporting Python, JS, Java. Features custom rulesets and metrics dashboards for teams. 2026 devs integrate it pre-commit over SonarQube for its predictive bug avoidance. ([Read more](/details/codiga.md)) `Refactoring` `Code Analysis` `Auto Fix` `IDE`
- [DeepCode](https://www.deepcode.ai/) - DeepCode AI scans code for bugs, vulnerabilities, and anti-patterns with SAST+ML hybrid analysis across 20+ languages, offering auto-fixes and PR comments. Processes 1M+ LOC/min with zero false positives tuning. In 2026, security teams pair it with GitHub Advanced Security for deeper semantic insights than rule-based scanners. ([Read more](/details/deepcode.md)) `SAST` `Bug Detection` `Auto Fix` `Multi Language`
- [GitHub Advanced Security](https://github.com/security/advanced-security) - GitHub Advanced Security employs AI for semantic code scanning, secret detection, and dependency vuln alerts across repos, with CodeQL for query-based SAST. Integrates PR blocking and auto-fixes for JavaScript, Python, Go. In 2026, OSS and enterprise teams mandate it over Snyk for native GitHub workflows and zero-config setup. ([Read more](/details/github-advanced-security.md)) `CodeQL` `Secret Detection` `SAST` `GitHub`
- [GitHub Secret Protection](https://github.com/security/advanced-security/secret-protection) - AI-powered secret scanning that detects leaked credentials in code changes before commit, using embeddings for high precision across 200+ secret types. Integrates with GitHub Advanced Security for real-time IDE alerts and push blocking. Reduces breach risk compared to regex-based tools like TruffleHog, with fewer false positives. ([Read more](/details/github-secret-protection.md)) `Secret Scanning` `Pre Commit` `False Positive Low` `Enterprise`
- [Gito](https://github.com/Nayjest/Gito) - Open-source AI code reviewer that analyzes PRs via GitHub Actions or CLI, supporting any LLM with Jira/Linear integration for automated feedback. Generates summaries, suggestions, and issue links without vendor lock-in. CLI-first alternative to CodeRabbit for self-hosted, customizable reviews. ([Read more](/details/gito.md)) `Open Source` `CLI` `LLM Agnostic` `Github Actions`
- [JetBrains Qodana](https://www.jetbrains.com/qodana/) - Cloud-based CI code quality platform using IntelliJ inspections for analysis, refactoring suggestions, and security vuln detection across 200+ languages. AI-enhanced auto-fixes and technical debt tracking integrate with GitHub/GitLab. Alternative to SonarQube for JetBrains users seeking IDE-parity in pipelines. ([Read more](/details/jetbrains-qodana.md)) `Code Quality` `Ci Cd` `JetBrains` `Auto Fix`
- [Perfect.Codes](https://perfect.codes) - AI-assisted service that quickly fixes bugs in code using expert tech support. ([Read more](/details/perfectcodes.md)) `Bug Fixing` `Code Review`
- [Pixee](https://pixee.ai) - AI security bot scanning repos for vulns/code smells, auto-creating fix PRs with zero config via GitHub App. Covers OWASP Top 10 and custom rules with 90%+ auto-fix rate. Scalable Snyk alternative for OSS/maintenance-heavy teams. ([Read more](/details/pixee.md)) `Auto Pr` `Vuln Fixing` `Github App` `Owasp`
- [Qodo](https://www.qodo.ai/) - AI-powered code review and quality platform providing enterprise-grade review across the SDLC. Offers pull request reviews, IDE plugins, CLI tools, context-aware codebase intelligence, and customizable rules to enforce standards and minimize risks before merge. Recognized in Gartner reports and benchmarks for 2026. ([Read more](/details/qodo.md)) `Ai Code Review` `Context Aware` `Enterprise`
- [Snyk Code](https://snyk.io/product-code/) - AI-powered SAST tool scanning for vulns, secrets, and quality issues in IDE/PR/CI with auto-fix PRs. ML-ranked prioritization for 20+ langs. Leader in security vs. general code tools like DeepCode. ([Read more](/details/snyk-code.md)) `SAST` `Auto Fix` `Multi Language` `Ci Integration`

## AI Testing & QA Tools

- [CodiumAI](https://www.codium.ai/) - CodiumAI generates intelligent unit tests, edge cases, and mocks from code analysis using LLMs, covering 80%+ untested branches automatically for Python, JS, Java. Integrates VS Code/PyCharm with coverage reports. Teams in 2026 rely on it over Codium TestGenius for deeper semantic understanding and fewer false positives. ([Read more](/details/codiumai.md)) `Test Generation` `Unit Tests` `Multi Language` `VSCode`
- [Test Gru](https://gru.ai/) - AI service auto-generating comprehensive unit tests for JS/TS/Python/Go/Java from codebases, with coverage reports and CI integration. Enterprise-focused for regression safety. Faster than Codium for full-suite gen. ([Read more](/details/test-gru.md)) `Unit Testing` `Multi Language` `Ci Integration` `Coverage`

## AI Workflow Automation

- [Fynix](https://fynix.ai) - Fynix AI supports full SDLC from ideation to deployment with code gen, testing, and ops automation via unified chat interface. Integrates Git, Jira, AWS for enterprise flows. 2026 teams use it as Copilot+DevOps hub, more holistic than siloed tools like Replit. ([Read more](/details/fynix.md)) `full-SDLC` `Chat Agent` `Enterprise` `Jira`
- [GitHub Actions](https://github.com/features/actions) - GitHub Actions orchestrates CI/CD with AI-enhanced steps for auto-testing, code gen, and deployment using LLMs in workflows. Marketplace agents handle PR triage and releases. In 2026, 90% open-source repos use it over Jenkins for native GitHub integration and cost-free minutes. ([Read more](/details/github-actions.md)) `CI/CD` `GitHub` `Agents` `Open Source`
- [GitHub Spark](https://github.com/features/spark) - Infrastructure for developing and deploying AI applications using hosted LLMs and GitHub's ecosystem, including model experimentation, prompt chaining, and auto-generated scaffolds. Streamlines full-cycle dev from spec to production with native Codespaces/Actions integration. Suited for teams building agentic apps, bridging Replit AI and Cursor for GitHub-centric scalability. ([Read more](/details/github-spark.md)) `App Generation` `Model Hosting` `Cicd Integration` `Open Source`
- [PoorCoder](https://github.com/vgrichina/poorcoder) - Collection of LLM-powered Unix CLI tools for code explanation, generation, and review, supporting Claude/Grok/OpenAI via simple pipes. Modular scripts for bash workflows without IDEs. Lightweight Aider alternative for terminal hackers. ([Read more](/details/poorcoder.md)) `CLI` `Scripts` `LLM Agnostic` `Open Source`

## Low Code AI Builders

- [Kiro](https://kiro.dev/) - AI-powered IDE emphasizing spec-first development, auto-generating code, tests, and docs from natural language requirements with live previews. Supports full-stack apps with integrated deployment. Differs from v0.dev by focusing on structured specs over freeform prompts for reliable outputs. ([Read more](/details/kiro.md)) `Spec Driven` `Full Stack` `Auto Docs` `Browser Ide`
- [Memex](https://memex.tech/) - Desktop AI app builder converting natural language descriptions into full cross-platform apps for Mac/Linux/Windows without coding. Generates UI, logic, and deploys locally. No-code alternative to Cursor for quick desktop prototypes. ([Read more](/details/memex.md)) `Desktop` `Natural Language` `No Code` `Cross Platform`

## Low-Code AI Builders

- [Berrry](https://berrry.app) - Berrry converts social media posts or natural language ideas into fully functional web apps with custom subdomains, handling UI, backend, and deployment automatically. It supports real-time previews and one-click iterations using frontier LLMs for pixel-perfect designs. In 2026, indie hackers love it over v0 for its viral sharing features and zero-infra setup. ([Read more](/details/berrry.md)) `No Code` `Web Apps` `Social Media` `Deployment`
- [Bolt](https://bolt.new/) - Bolt.new enables browser-based AI app creation from prompts, generating React/Next.js stacks with full-stack logic and Stripe integrations in seconds. It offers live editing and export to GitHub for seamless handoff to production. In 2026 low-code races, it outpaces Replit by delivering deploy-ready MVPs instantly. ([Read more](/details/bolt.md)) `Browser Based` `Full Stack` `Rapid Prototyping` `Next.js`

## Model Context Protocol (MCP)

- [MCP Registry](https://github.com/mcp) - Central GitHub-hosted registry for Model Context Protocol (MCP) tools, enabling seamless integration of external AI services into Copilot, Spark, and Codespaces workflows. Standardizes agent-tool interactions for extensible AI coding. Essential for devs building custom agents, unlike monolithic platforms. ([Read more](/details/mcp-registry.md)) `Mcp` `Registry` `Ai Extensions` `GitHub`
- [Roundtable MCP Server](https://github.com/askbudi/roundtable) - Self-hosted MCP server proxying multiple LLMs (Claude, Codex) through unified interface for agent tools. Zero-config Docker deploy enables LLM switching without code changes. Key for MCP ecosystems vs. single-provider lock-in. ([Read more](/details/roundtable-mcp-server.md)) `Open Source` `Self Hosted` `Multi LLM` `Proxy`
- [ToolHive](https://github.com/stacklok/toolhive) - Open-source marketplace and deployer for MCP servers/tools, enabling one-click setup of coding agents in local/cloud envs. Curates/discovers protocol-compliant extensions. Essential infrastructure for MCP adoption vs. manual GitHub forks. ([Read more](/details/toolhive.md)) `Open Source` `Mcp Marketplace` `One Click Deploy` `Self Hosted`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This directory may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this directory, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
# Awesome Hermes Plugins

> **Note:** This repository contains an automatically compiled list of Python directory plugins and plugin collections for Nous Research Hermes Agent, filtered by canonical same-directory manifest and entry-point evidence.

A curated list of Hermes Agent Python plugins and plugin collections for
tools, commands, hooks, platforms, model providers, memory, context engines,
observability, browser/media backends, and plugin development. Every collected
repository contains at least one directory with a Hermes plugin manifest and
Python entry point; runtime behavior and security remain unverified.


Table of Contents:
- [Tools & Automation](#tools-&-automation) (30)
- [Commands & Workflows](#commands-&-workflows) (3)
- [Hooks & Observability](#hooks-&-observability) (7)
- [Messaging Platforms](#messaging-platforms) (12)
- [Model Providers](#model-providers) (2)
- [Memory Providers](#memory-providers) (26)
- [Context Engines](#context-engines) (5)
- [Browser, Media & Other Backends](#browser,-media-&-other-backends) (3)
- [Plugin Collections & Developer Resources](#plugin-collections-&-developer-resources) (6)



## Tools & Automation

- [asimons81/hermes-dreaming](https://github.com/asimons81/hermes-dreaming) (74 Python) - Implement a staged self-improvement engine for Hermes-style memory, user, skill, and fact updates with explicit review and apply/discard gates.
- [AtlasOmnia/hermes-tool-router](https://github.com/AtlasOmnia/hermes-tool-router) (46 Python) - A Hermes Agent plugin that intelligently routes tools to reduce first-turn schema tokens and optimize LLM interactions, featuring deterministic routing and optional model-based classification.
- [clawnchdev/clawmes](https://github.com/clawnchdev/clawmes) (20 Python) - Clawmes is a Hermes Agent plugin offering extensive cryptocurrency functionalities including wallet management, DEX trading, lending, staking, governance, and on-chain automation.
- [Codename-11/hermes-relay](https://github.com/Codename-11/hermes-relay) (59 Kotlin) - Hermes-Relay is an Android companion app and CLI that extends Hermes Agent with chat, voice, and device control, enabling mobile interaction and remote execution.
- [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) (83572 JavaScript) - Ponytail is a set of plugins for AI agent development tools like Claude Code and GitHub Copilot CLI that helps agents write more efficient, concise, and safe code by following a 'lazy senior dev' m...
- [FahrenheitResearch/hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) (42 Python) - A Hermes Agent plugin providing 13 weather tools for observations, forecasts, alerts, model imagery, radar, soundings, and meteorological calculations, leveraging a Rust-backed stack.
- [GumbyEnder/hermes-local-rig-accounting](https://github.com/GumbyEnder/hermes-local-rig-accounting) (22 Python) - This plugin for Nous Research Hermes Agent provides transparent per-token cost accounting for local LLM inference rigs, factoring in hardware depreciation and electricity.
- [indranilbanerjee/contentforge](https://github.com/indranilbanerjee/contentforge) (12 Python) - ContentForge is an open-source enterprise content production plugin offering 21 skills for generating publication-ready .docx files with AI-detection humanization, fact-checking, and C2PA signing.
- [indranilbanerjee/digital-marketing-pro](https://github.com/indranilbanerjee/digital-marketing-pro) (229 Python) - Digital Marketing Pro is an open-source AI marketing plugin for agencies and in-house teams, offering 158 skills, 24 specialist agents, and a 12-Part Strategy Flow, with EU AI Act Article 50 readin...
- [indranilbanerjee/socialforge](https://github.com/indranilbanerjee/socialforge) (18 Python) - SocialForge is an open-source, agency-grade social media production engine with 16 skills and 25 commands, offering AI image/video generation, C2PA signing, and cross-platform content adaptation sp...
- [intentframe/agent-integrations](https://github.com/intentframe/agent-integrations) (11 Python) - This repository provides the IntentFrame security plugin for Nous Research's Hermes Agent, establishing an external policy checkpoint for critical tool calls like terminal, code execution, file ope...
- [itechmeat/hermes-workflows](https://github.com/itechmeat/hermes-workflows) (17 TypeScript) - This plugin introduces a visual editor for multi-step automations in Hermes Agent, allowing users to draw and execute workflows as graphs that compile to native Hermes primitives.
- [Leon-llb/codex-image](https://github.com/Leon-llb/codex-image) (63 Python) - This project enables AI image generation via your ChatGPT Plus subscription and Codex CLI, offering a cost-effective solution for Hermes and other agent integrations.
- [LeventeNagy/soul-forge](https://github.com/LeventeNagy/soul-forge) (19 JavaScript) - A Hermes Agent dashboard plugin for generating, customizing, and managing SOUL.MD persona files using curated templates or AI generation.
- [lorenzofamiglini/The-Forge-Protocol-Agent](https://github.com/lorenzofamiglini/The-Forge-Protocol-Agent) (10 Python) - The Forge Protocol is an anti-deskilling framework for Hermes Agent, implementing human-AI collaboration protocols across four modes to enhance cognitive sovereignty.
- [nativ3ai/hermes-payguard](https://github.com/nativ3ai/hermes-payguard) (12 Python) - A safe-by-design Hermes Agent plugin for secure USDC and x402 payments, featuring operator-approved intent staging and gated execution.
- [neptun-zuti/ponytail-hermes](https://github.com/neptun-zuti/ponytail-hermes) (30 Python) - A Hermes Agent plugin that enforces a "lazy senior dev" mindset by injecting instructions to prioritize simple, standard, and minimal code solutions, featuring configurable modes and slash commands.
- [open-world-project/model-router](https://github.com/open-world-project/model-router) (27 Python) - This Hermes Agent plugin provides automatic, cost-aware model routing based on a five-tier system, dynamic escalation, and deep integration with both CLI and WebUI interfaces.
- [pingchesu/hermes-curator-evolver](https://github.com/pingchesu/hermes-curator-evolver) (25 Python) - This plugin for Hermes Agent facilitates evidence-driven skill evolution through reports, dry-run proposals, candidate search, and guarded application for safer, more robust AI skill management.
- [raulvidis/hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) (40 Python) - Integrates Cloudflare's Browser Rendering API with Hermes Agent to enable advanced web crawling, scraping, and content extraction capabilities, including AI-powered structured data extraction.
- [robbyczgw-cla/hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) (337 Python) - A source-only Hermes Agent plugin for multi-provider web search and URL extraction, offering diagnostic routing and transparent evidence.
- [rusty4444/hermes-voice-ha-integration](https://github.com/rusty4444/hermes-voice-ha-integration) (46 Python) - This project integrates Hermes Agent with Home Assistant for on-device voice control, including wake word, STT, LLM, TTS, and media player functionality, all locally and without cloud dependencies.
- [Sahil-SS9/hermes-multichannel-prompt-optimizer](https://github.com/Sahil-SS9/hermes-multichannel-prompt-optimizer) (14 Python) - Optimize Hermes Agent prompts before they hit the LLM, reducing tokens, boosting quality, and providing analytics across CLI, TUI, Discord, and Telegram.
- [sergiocoding96/hermes-multi-agent](https://github.com/sergiocoding96/hermes-multi-agent) (10 TeX) - Multi-agent research system integrating Paperclip, Hermes, and MemOS for self-improving loops, featuring specialized agents, dynamic skill evolution, and robust web/memory infrastructure.
- [Strategic-Automation/violin](https://github.com/Strategic-Automation/violin) (10 Python) - Violin is a supervised, agentic Hermes Agent pentest profile featuring 31 playbooks, 8 references, and a required execution guard for authorized reconnaissance, exploit validation, and reporting.
- [Team-Volt/hermes-reasoning-router-plugin](https://github.com/Team-Volt/hermes-reasoning-router-plugin) (10 Python) - A Hermes gateway plugin that dynamically adjusts reasoning effort for Discord and Telegram messages based on content, optimizing cost and performance.
- [theopitori/hermeskill](https://github.com/theopitori/hermeskill) (28 Python) - Hermeskill is a plugin for Hermes Agent that provides an external supervision system to detect and terminate runaway or compromised AI coding agents via a documented apoptosis protocol, escalating ...
- [Tommy-yw/RunbookHermes](https://github.com/Tommy-yw/RunbookHermes) (534 Python) - RunbookHermes is an AIOps agent built on Nous Research Hermes Agent, designed for evidence-driven incident response, approval-gated remediation, and continuous learning.
- [Xquik-dev/hermes-tweet](https://github.com/Xquik-dev/hermes-tweet) (18 Python) - This is a native Hermes Agent plugin for X/Twitter automation through Xquik, providing structured tools for search, account management, tweeting, and more.
- [zaycruz/hermes-opencode-plugin](https://github.com/zaycruz/hermes-opencode-plugin) (45 Python) - This plugin integrates Hermes Agent with OpenCode, enabling the dispatch of complex software engineering tasks to OMO's multi-agent harness for autonomous code generation and modification.

## Commands & Workflows

- [lingjiuu/hermes-dynamic-workflows](https://github.com/lingjiuu/hermes-dynamic-workflows) (96 Python) - This plugin introduces dynamic workflows to Hermes Agent, allowing models to write, execute, and orchestrate sandboxed Python scripts for complex multi-agent tasks.
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) (25383 Python) - This repository provides a persistent, file-based planning skill for AI coding agents, ensuring plans survive context loss, restarts, and offering a completion gate for long-running tasks.
- [xuyang-liu16/hermes-code-bridge](https://github.com/xuyang-liu16/hermes-code-bridge) (22 Python) - This Hermes Agent plugin acts as a control plane, enabling coordination and routing of tasks to local coding agents like Codex, Kimi Code, Claude Code, OpenCode, and Gemini CLI.

## Hooks & Observability

- [8bit64k/cronalytics](https://github.com/8bit64k/cronalytics) (99 Python) - Cronalytics is a Hermes Agent plugin providing detailed analytics and observability for scheduled agentic automations, tracking costs, tokens, and performance.
- [Agent-Analytics/agent-analytics-hermes-plugin](https://github.com/Agent-Analytics/agent-analytics-hermes-plugin) (24 JavaScript) - Integrate Agent Analytics directly into the Hermes Agent dashboard for account connection, project selection, and read-only access to analytics data.
- [briancaffey/hermes-otel](https://github.com/briancaffey/hermes-otel) (43 Python) - An OpenTelemetry plugin for Hermes Agent that exports LLM tool calls, model invocations, and API requests as OTel spans to various tracing backends like Phoenix, Langfuse, SigNoz, and Jaeger.
- [JakimLi/cloe-desktop](https://github.com/JakimLi/cloe-desktop) (15 JavaScript) - Cloe Desktop is a realistic AI character companion that lives on your desktop, designed to integrate with the Hermes Agent lifecycle for contextual expressions and interactions.
- [nujovich/hermes-telemetry](https://github.com/nujovich/hermes-telemetry) (20 Python) - A comprehensive telemetry plugin for Hermes Agent that provides real-time budget enforcement and detailed observability for AI operations.
- [rullerzhou-afk/clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) (5375 JavaScript) - Clawd on Desk is a pixel desktop pet that reacts to your AI coding agent's activity in real time, offering visual feedback for various states and supporting numerous AI agents including Hermes.
- [waifuai/waifu-sprites](https://github.com/waifuai/waifu-sprites) (16 Python) - A Hermes Agent dashboard plugin that provides a video-based AI companion, dynamically reacting to agent states and emotions with corresponding animated sprites.

## Messaging Platforms

- [agentchatme/agentchat-hermes](https://github.com/agentchatme/agentchat-hermes) (13 Python) - This plugin integrates Hermes Agent with the AgentChat platform, providing persistent peer-to-peer messaging capabilities via WebSocket and a rich set of agent-to-agent communication tools.
- [arkseek/hermes-feishu](https://github.com/arkseek/hermes-feishu) (18 Python) - This plugin enhances Hermes Agent's Feishu messaging channel to support rich card messages and proper table rendering, addressing character limitations of Feishu's default Markdown.
- [cuongdev/hermes-zalo-plugin](https://github.com/cuongdev/hermes-zalo-plugin) (17 JavaScript) - Integrates Hermes Agent with the Zalo messaging platform via an unofficial Node.js bridge, enabling chat with a personal Zalo account.
- [eggyrooch-blip/hermes-multitenancy](https://github.com/eggyrooch-blip/hermes-multitenancy) (13 Python) - A Hermes Agent plugin enabling true multi-tenancy for Feishu bots, routing multiple users to isolated agent profiles without modifying the core agent runtime.
- [hellowind777/hermes-feishu-plugin](https://github.com/hellowind777/hermes-feishu-plugin) (10 Python) - This repository provides a Hermes Agent plugin for improved interaction with Feishu (Lark), aligning its behavior with the official OpenClaw model while adhering to Hermes's Python plugin standards.
- [Humalike/hermes-humalike-plugin](https://github.com/Humalike/hermes-humalike-plugin) (17 Python) - Integrates Humalike APIs into Hermes Agent to enhance bot presence in chat, providing human-like turn-taking, persona, theory of mind, and social learning.
- [inkbox-ai/hermes-agent-plugin](https://github.com/inkbox-ai/hermes-agent-plugin) (26 Python) - This plugin integrates Hermes Agent with Inkbox, providing communication capabilities like email, calls, SMS/MMS, and iMessage, directly manageable by the agent.
- [kisaragi-mochi/hermes-even-ai-plugin](https://github.com/kisaragi-mochi/hermes-even-ai-plugin) (10 Python) - This plugin integrates Hermes Agent with Even Realities G2 smart glasses, allowing voice control and displaying replies on the HUD, with Telegram fallback for long responses.
- [Mininglamp-OSS/hermes-channel-octo](https://github.com/Mininglamp-OSS/hermes-channel-octo) (22 Python) - This repository provides an Octo (WuKongIM-based corporate IM) channel plugin for Hermes Agent, enabling bot-to-user DMs, group messaging, and media attachments.
- [NousResearch/hermes-telegram-business](https://github.com/NousResearch/hermes-telegram-business) (10 Python) - This plugin transforms Hermes Agent into a Telegram Business secretary bot, requiring explicit owner approval for every LLM-drafted message before sending to customers.
- [outsourc-e/hermes-workspace-plugin](https://github.com/outsourc-e/hermes-workspace-plugin) (12 Python) - This plugin integrates Hermes Workspace chat into the Hermes Agent dashboard as a dedicated tab, facilitating direct interaction within the agent's UI.
- [stasstepv/hermes-pwa](https://github.com/stasstepv/hermes-pwa) (14 TypeScript) - An unofficial mobile PWA plugin for Hermes Agent, adding a "Mobile" tab to the Dashboard for phone-native chat, action approvals, and agent monitoring.

## Model Providers

- [BlockRunAI/ClawRouter-Hermes](https://github.com/BlockRunAI/ClawRouter-Hermes) (17 Python) - Integrates ClawRouter's 55+ LLMs, x402 USDC micropayments, and smart routing into Hermes Agent as a Python plugin, offering advanced model access and billing.
- [ThaungThanHan/hermes-omnivoice](https://github.com/ThaungThanHan/hermes-omnivoice) (10 Python) - Integrates Xiaomi's OmniVoice for multilingual zero-shot TTS, voice cloning, and voice design into Hermes Agent as a TTS provider with local inference.

## Memory Providers

- [410979729/scope-recall-hermes](https://github.com/410979729/scope-recall-hermes) (176 Python) - A Hermes Agent memory provider plugin offering current-turn recall, journal-first semantic capture, durable shared memory, SQLite truth storage, and optional LanceDB and SQLite vector companions.
- [aliyun/hermes-tablestore-memory](https://github.com/aliyun/hermes-tablestore-memory) (53 Python) - This plugin integrates Hermes Agent with Alibaba Cloud TableStore, providing an external memory provider for semantic long-term memory, automatic turn synchronization, and prefetching.
- [aristoapp/hermes-membase](https://github.com/aristoapp/hermes-membase) (12 Python) - This Hermes Agent plugin integrates Membase for persistent, long-term AI memory using hybrid vector search and a knowledge graph, enhancing agent recall and knowledge retention.
- [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) (3436 Python) - Basic Memory is a local-first, knowledge graph-based memory system for AI agents, providing persistent, bidirectional knowledge access via Markdown files and the MCP protocol, including a Hermes pl...
- [bellfireg/hermes-hybrid-memory](https://github.com/bellfireg/hermes-hybrid-memory) (10 Python) - Hybrid Memory Architecture for Hermes Agent, combining Honcho (subjective modeling) and OpenViking (knowledge retrieval) into a dual-memory system for persistent AI cognition.
- [benben17/hermes-d1-memory](https://github.com/benben17/hermes-d1-memory) (12 Python) - A Cloudflare D1-backed external memory provider for Hermes Agent, offering semantic-like long-term memory using FTS5 for zero-maintenance, edge-deployed persistence.
- [ClaudioDrews/memory-os](https://github.com/ClaudioDrews/memory-os) (1267 Python) - Memory OS is a 7-layer memory operating system for Hermes Agent, providing persistent memory, structured facts, fabric recall, an auto-curated wiki, and surgical context injection, running locally ...
- [eleboucher/memini](https://github.com/eleboucher/memini) (12 Go) - memini is a shared, persistent memory service for AI agents, providing tiered storage with hybrid vector + keyword retrieval, designed to scale from embedded SQLite to Postgres in Kubernetes.
- [engrammemory-labs/engram-lite](https://github.com/engrammemory-labs/engram-lite) (27 Python) - engram-lite provides local, persona-conditioned memory for AI agents, enhancing task success and reducing hallucinations by serving relevant information without LLM calls.
- [esaradev/icarus-plugin](https://github.com/esaradev/icarus-plugin) (138 Python) - Icarus is a Nous Research Hermes Agent plugin that provides persistent self-memory, training data extraction, and a model replacement pipeline for Hermes agents.
- [itechmeat/open-second-brain](https://github.com/itechmeat/open-second-brain) (127 TypeScript) - Open Second Brain provides an Obsidian-native, local-first memory layer for Hermes Agent, enabling deterministic learning and access across multiple AI runtimes.
- [jshph/enzyme-skill](https://github.com/jshph/enzyme-skill) (64 Python) - Enzyme is a Hermes Agent plugin that provides semantic memory and search for Obsidian vaults and markdown knowledge bases, compiling workspaces into concept graphs for fast, token-efficient retrieval.
- [Ladybug-Memory/hermes-memory-plugin](https://github.com/Ladybug-Memory/hermes-memory-plugin) (18 Python) - A fully local, file-based memory provider for Hermes Agent, utilizing LadybugMemory as a columnar embedded graph database for structured recall, search, and relationships.
- [magnus919/hermes-cashew](https://github.com/magnus919/hermes-cashew) (13 Python) - hermes-cashew is a Hermes Agent memory provider plugin that stores conversation context in a local Cashew thought graph with semantic search and automatic context recall.
- [mem9-ai/mem9-hermes-plugin](https://github.com/mem9-ai/mem9-hermes-plugin) (11 Python) - Integrates mem9, a persistent cross-session memory service, into Hermes Agent, allowing conversations to be extracted into facts and recalled semantically.
- [MemoriLabs/Memori](https://github.com/MemoriLabs/Memori) (15575 Python) - Memori is an agent-native memory infrastructure, offering an LLM-agnostic layer that converts agent execution and conversation into structured, persistent state for production systems, including a ...
- [mnemosyne-oss/mnemosyne](https://github.com/mnemosyne-oss/mnemosyne) (1526 Python) - Mnemosyne is a zero-dependency, sub-millisecond AI memory system for Hermes Agents and other LLM frameworks, focusing on efficient, local, and private knowledge retention.
- [p1s4/hermes-graphiti-plugin](https://github.com/p1s4/hermes-graphiti-plugin) (16 Python) - A Hermes Agent plugin providing temporal knowledge graph-based memory using Graphiti Core, storing and retrieving conversation data in a Neo4j database.
- [rikouu/cortex](https://github.com/rikouu/cortex) (238 TypeScript) - Cortex is a universal AI agent memory service designed to prevent AI forgetting, featuring a three-layer memory lifecycle, hybrid search, knowledge graph, and intelligent extraction.
- [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) (8932 TypeScript) - TencentDB Agent Memory is a Hermes Agent plugin providing a 4-tier progressive and local-first memory pipeline to enhance AI agents by reducing token usage and improving task success rates.
- [tuancookiez-hub/HyAtlas-Memory](https://github.com/tuancookiez-hub/HyAtlas-Memory) (15 Python) - A Hermes Agent plugin providing a personal, local, single-user long-term memory stack by forking and refining the Hy-Memory cognitive framework.
- [wysie/mnemosyne-dashboard](https://github.com/wysie/mnemosyne-dashboard) (149 JavaScript) - A local-first, read-only web dashboard plugin for Hermes Agent's Mnemosyne memory store, offering browsing, visualization, and safe maintenance.
- [wysie/yantrikdb-hermes-dashboard](https://github.com/wysie/yantrikdb-hermes-dashboard) (10 Python) - A local-first web dashboard plugin for Hermes Agent, designed to inspect, visualize, and maintain a YantrikDB memory store.
- [xraysight/hermes-memory-ui](https://github.com/xraysight/hermes-memory-ui) (46 Python) - A dashboard plugin for Hermes Agent that provides a read-only interface to inspect various memory components, including built-in, session, and external memory providers like Holographic, Mem0, Honc...
- [yantrikos/yantrikdb-hermes-plugin](https://github.com/yantrikos/yantrikdb-hermes-plugin) (70 Python) - This plugin integrates YantrikDB as a memory provider for Hermes Agent, offering self-maintaining memory, contradiction tracking, explainable recall, and autonomous skill management.
- [zhangfengcdt/memoir](https://github.com/zhangfengcdt/memoir) (594 Python) - Memoir is a high-performance semantic memory system for AI agents, offering Git-like version control for AI memory management to combat context contamination, token costs, and memory drift.

## Context Engines

- [claudioemmanuel/squeez](https://github.com/claudioemmanuel/squeez) (168 Rust) - squeez is an end-to-end token optimizer that provides hook-based token compression for Hermes Agent and several other AI CLI hosts, increasing context window efficiency.
- [EfficientContext/ContextPilot](https://github.com/EfficientContext/ContextPilot) (122 Python) - ContextPilot is a context engine that accelerates long-context LLM inference by optimizing context reuse, offering significant speedups and token savings for RAG, memory chat, and agentic AI worklo...
- [entrepeneur4lyf/hermes-context-manager](https://github.com/entrepeneur4lyf/hermes-context-manager) (31 Python) - Hermes Context Manager (HMC) is a silent-first, context optimization plugin for the Hermes Agent gateway, automatically compressing tool outputs and summarizing phases.
- [kenyonxu/hermes-persona](https://github.com/kenyonxu/hermes-persona) (21 Python) - hermes-persona is a configurable Hermes Agent plugin that dynamically injects persona context into LLM calls using various hooks and rules.
- [stephenschoettler/hermes-lcm](https://github.com/stephenschoettler/hermes-lcm) (861 Python) - hermes-lcm is a lossless context management plugin for Hermes Agent, providing a DAG-based context engine that ensures no messages are lost through persistent storage and intelligent summarization.

## Browser, Media & Other Backends

- [abundantbeing/hermes-browser-extension](https://github.com/abundantbeing/hermes-browser-extension) (986 JavaScript) - This project provides a browser-native side panel and full-page workspace for Hermes Agent, connecting active web context to local, cloud, or remote Hermes runtimes.
- [lEWFkRAD/hermes-agents-guide-to-the-galaxy](https://github.com/lEWFkRAD/hermes-agents-guide-to-the-galaxy) (10 JavaScript) - Hermes Notebook provides handwriting-first clients for Kindle Scribe, BOOX, and Android stylus tablets, integrating recognized notes into Hermes Agent sessions with OCR and offline ink support.
- [outsourc-e/hermesworld](https://github.com/outsourc-e/hermesworld) (28 Python) - This plugin integrates the HermesWorld creative AI platform directly into the Hermes Agent dashboard as an embedded tab.

## Plugin Collections & Developer Resources

- [42-evey/hermes-plugins](https://github.com/42-evey/hermes-plugins) (274 Python) - A comprehensive collection of 23 custom plugins for Hermes Agent, enhancing autonomy, observability, cost control, self-improvement, and communication.
- [bergside/typeui](https://github.com/bergside/typeui) (1541 TypeScript) - TypeUI provides AI-first resources like design skills, UI prompts, and layout guidance to help various AI coding tools generate better user interfaces and designs for websites and applications.
- [kaishi00/hermes-community-plugins](https://github.com/kaishi00/hermes-community-plugins) (38 Python) - A collection of battle-tested Hermes Agent plugins for advanced multi-agent interactions, including asynchronous task delegation and intelligent multi-agent context injection for Discord and Telegram.
- [NousResearch/hermes-example-plugins](https://github.com/NousResearch/hermes-example-plugins) (28 Python) - Reference implementations of Hermes Agent plugins, demonstrating core plugin surfaces like LLM access and dashboard extensions, for developers to learn from and adapt.
- [Shopify/Shopify-AI-Toolkit](https://github.com/Shopify/Shopify-AI-Toolkit) (453 JavaScript) - This toolkit provides AI agent plugins for Shopify's platform, offering access to documentation, API schemas, code validation, and store management capabilities through CLI. It enables developers t...
- [SouthpawIN/sovth-config](https://github.com/SouthpawIN/sovth-config) (12 Python) - This repository provides an opinionated configuration toolkit for Hermes Agent, featuring distributable profiles, skills (like turbofit), and plugin tools for deep research, character card generati...


## License

[<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)

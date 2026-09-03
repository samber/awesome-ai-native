# Awesome AI-Native [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-native products and resources, where an LLM is the product, not a feature.

The bar is deliberately high. "AI-powered" sidebars, summarize buttons, and semantic search bolted onto legacy products do not belong here. Links point at the product itself, and entries are dropped once a product shuts down or pivots away from AI.

## Contents

- [Chat & agents](#chat--agents)
  - [Chat](#chat)
  - [General-purpose agents](#general-purpose-agents)
  - [Self-hosted personal AI agents](#self-hosted-personal-ai-agents)
  - [Computer use models](#computer-use-models)
- [Vibe-coding and vibe-engineering](#vibe-coding-and-vibe-engineering)
  - [Coding agents](#coding-agents)
  - [Code understanding and docs](#code-understanding-and-docs)
  - [App builders](#app-builders)
- [Knowledge work](#knowledge-work)
  - [Search and research](#search-and-research)
  - [Knowledge management](#knowledge-management)
  - [Meetings and voice](#meetings-and-voice)
- [Industry applications](#industry-applications)
  - [Customer support](#customer-support)
  - [Sales and CRM](#sales-and-crm)
  - [Legal](#legal)
  - [Healthcare](#healthcare)
  - [Education](#education)
- [Creative & media](#creative--media)
  - [Design and creative](#design-and-creative)
  - [Image generation](#image-generation)
  - [Video generation](#video-generation)
  - [Audio and music](#audio-and-music)
- [Models & robotics](#models--robotics)
  - [Open-weight models](#open-weight-models)
  - [Small language models](#small-language-models)
  - [Robotics and embodied AI](#robotics-and-embodied-ai)
  - [OCR](#ocr)
- [Compute & infrastructure](#compute--infrastructure)
  - [AI chips and hardware](#ai-chips-and-hardware)
  - [Local inference](#local-inference)
  - [GPU clouds](#gpu-clouds)
  - [Hosted inference and fine-tuning](#hosted-inference-and-fine-tuning)
  - [Serving and orchestration](#serving-and-orchestration)
  - [Gateways and routing](#gateways-and-routing)
  - [Sandboxes](#sandboxes)
- [Developer tooling](#developer-tooling)
  - [Frameworks and SDKs](#frameworks-and-sdks)
  - [MCP and integrations](#mcp-and-integrations)
  - [Vector databases and retrieval](#vector-databases-and-retrieval)
  - [Agent memory](#agent-memory)
  - [Evaluation and observability](#evaluation-and-observability)
- [Learning & community](#learning--community)
  - [Newsletters and blogs](#newsletters-and-blogs)
  - [Podcasts](#podcasts)
  - [People to follow](#people-to-follow)
  - [Courses and learning](#courses-and-learning)
  - [Foundational papers](#foundational-papers)
  - [Events](#events)
  - [Communities](#communities)

## Chat & agents

Consumer assistants and autonomous agents you interact with directly. These are the products most people picture when they say "AI," from plain chat interfaces to agents that browse, act, and drive a computer on your behalf.

### Chat

General-purpose conversational assistants you talk to across web, mobile, and desktop.

- [ChatGPT](https://chatgpt.com) - OpenAI's consumer chat product with memory, canvas, voice, and the broadest third-party app ecosystem.
- [Claude](https://claude.ai) - Anthropic's assistant known for long-context reasoning, Projects, Artifacts, and Computer Use.
- [Gemini](https://gemini.google.com) - Google's multimodal assistant integrated across Workspace, Android, and the Pixel line.
- [Grok](https://grok.com) - xAI's assistant with real-time access to X and a distinct, less-filtered persona.
- [Meta AI](https://www.meta.ai) - Assistant embedded across WhatsApp, Instagram, Messenger, and Ray-Ban Meta glasses.
- [Vibe](https://mistral.ai/products/vibe) - Mistral's assistant, formerly Le Chat, unifying chat, work automation, and remote coding agents.

### General-purpose agents

Agents that plan and execute multi-step tasks across your tools, often specialized to a company's workflows and grounded in private data, returning finished work rather than just answers.

- [ChatGPT Agent](https://openai.com/index/introducing-chatgpt-agent) - OpenAI's agent that browses, uses tools, and completes multi-step web tasks on the user's behalf.
- [Claude Cowork](https://www.anthropic.com/product/claude-cowork) - Anthropic's agent for non-coding knowledge work that runs background and scheduled tasks across shared projects and files.
- [Dust](https://dust.tt) - Enterprise platform for building no-code AI agents grounded in company data through 100+ connectors, where teams and agents collaborate in a shared workspace.
- [Manus](https://manus.im) - General-purpose agent that plans, browses, writes code, and returns finished deliverables.
- [Swiftask](https://www.swiftask.ai) - No-code platform for building and orchestrating multi-model AI agents across a company's tools, with centralized governance.

### Self-hosted personal AI agents

Open-source assistants you self-host on your own server or VPS rather than your laptop, with persistent memory, custom skills, and access over the messaging apps you already use.

- [Hermes Agent](https://github.com/NousResearch/hermes-agent) - Nous Research's self-hosted agent that keeps memory across sessions, writes its own reusable skills, and is reachable over Telegram, Discord, Slack, WhatsApp, Signal, and CLI.
- [OpenClaw](https://github.com/openclaw/openclaw) - Self-hosted personal AI assistant that runs on your own devices and answers you across WhatsApp, Telegram, Slack, Discord, Signal, iMessage, and many other channels.
- [Paperclip](https://paperclip.ing) - Open-source, self-hosted control plane for running and governing teams of AI agents with org charts, budgets, and goals.

### Computer use models

Models and agents that operate a real browser or desktop by reading the screen and taking actions the way a person would.

- [Browser Use](https://browser-use.com) - Open-source library that lets AI agents control a browser to complete web tasks.
- [Claude for Chrome](https://www.anthropic.com/news/claude-for-chrome) - Anthropic's Claude agent that navigates and takes actions inside your Chrome browser.
- [cua](https://www.cua.ai) - Open-source infrastructure and SDK for building computer-use agents that control full desktops in sandboxes.
- [Firecrawl](https://www.firecrawl.dev) - API that crawls and scrapes websites into clean, LLM-ready markdown and structured data.
- [H Company](https://hcompany.ai) - Lab whose Holo models and Surfer H agent operate a real browser and desktop by reasoning, planning, and executing multi-step computer-use tasks.
- [OpenAI Operator](https://openai.com/index/introducing-operator) - OpenAI's computer-use agent that operates a browser via screenshots and actions.

## Vibe-coding and vibe-engineering

Tools that let you build software by describing intent rather than writing every line. This covers coding agents, repo-understanding assistants, and prompt-to-app builders.

### Coding agents

Agents and AI-first editors that read, write, and run code against real repositories.

- [Claude Code](https://www.anthropic.com/claude-code) - Anthropic's agentic tool that reads, edits, and executes against a real codebase from the terminal or IDE.
- [Cline](https://cline.bot) - Open-source autonomous coding agent that runs inside VS Code with human-in-the-loop approval.
- [Cursor](https://cursor.com) - AI-first code editor built around whole-repo context, an agent mode, and multi-line tab completion.
- [Devin](https://devin.ai) - Cognition's autonomous software engineer that takes tasks from Slack or an issue tracker, then plans, codes, tests, and opens pull requests.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source terminal agent powered by Gemini, with MCP support and a generous free tier.
- [GitHub Copilot](https://github.com/features/copilot) - Inline completion and an agent mode that edits across files and opens pull requests, integrated across GitHub and popular IDEs.
- [Google Antigravity](https://antigravity.google) - Agent-first development platform built around Gemini that orchestrates autonomous agents across editor, terminal, and browser.
- [Mistral Vibe](https://mistral.ai/products/vibe/code) - Mistral's terminal and IDE coding agent with cloud-based remote agents, built on the open-source mistral-vibe CLI.
- [OpenAI Codex](https://openai.com/codex) - OpenAI's coding agent spanning CLI, IDE, cloud, and web.
- [OpenCode](https://opencode.ai) - Provider-agnostic, open-source terminal coding agent.
- [Poolside](https://poolside.ai) - Enterprise coding assistant powered by its own foundation models, deployed inside a customer's environment and tuned on their codebases.
- [Windsurf](https://windsurf.com) - Agentic IDE with Cascade, a multi-step coding agent that operates across files.
- [Zed](https://zed.dev) - Collaborative editor written in Rust with first-class agent panels and multi-model support.

### Code understanding and docs

Tools that turn a codebase into searchable docs, wikis, and answers for humans and agents alike.

- [Code Wiki](https://codewiki.google) - Google's tool that turns any GitHub repo into an interactive, always-in-sync wiki with architecture diagrams and a Gemini-powered chat.
- [Context7](https://context7.com) - Upstash service that feeds up-to-date, version-specific library documentation into coding agents over MCP.
- [DeepWiki](https://deepwiki.com) - Cognition's Devin-generated wikis for any public GitHub repo, with architecture diagrams, source links, and a conversational assistant.
- [Zread](https://zread.ai) - Generates structured guides, API docs, and code Q&A for any GitHub repo by swapping github.com for zread.ai.

### App builders

Pure vibe-coding platforms that turn a plain-language description into a working app, aimed at non-technical builders who never touch the underlying code.

- [Bolt](https://bolt.new) - Prompt-to-app builder that generates and runs full web apps directly in the browser.
- [Figma Make](https://www.figma.com/make) - Prompt-to-app tool inside Figma that generates working prototypes from a description.
- [Google AI Studio](https://aistudio.google.com) - Browser-based platform for prototyping and building apps with Gemini models across text, image, audio, and video.
- [Google Opal](https://opal.google.com) - Google Labs no-code builder for creating and sharing mini AI apps as visual node workflows.
- [Google Stitch](https://stitch.withgoogle.com) - Gemini-powered tool that turns prompts or wireframes into high-fidelity UI plus front-end code, absorbing the former Galileo AI.
- [Lovable](https://lovable.dev) - Prompt-to-app builder that ships full-stack web apps from a chat window.
- [Replit Agent](https://replit.com/agent) - Browser-based agent that builds, runs, and deploys full-stack applications from natural-language prompts.
- [v0](https://v0.app) - Vercel's generative UI tool that produces production-ready React and Tailwind components.

## Knowledge work

AI-native products that help you find, organize, and act on information. Search and research engines, note-taking systems, and meeting assistants live here.

### Search and research

Answer engines and retrieval APIs that find, cite, and synthesize sources instead of returning a list of links.

- [Claude Science](https://www.anthropic.com/news/claude-science-ai-workbench) - Anthropic research workbench for scientists, pre-configured with scientific databases, coding tools, and compute.
- [Exa](https://exa.ai) - Neural search API designed for agents and retrieval-heavy applications rather than human browsing.
- [Perplexity](https://www.perplexity.ai) - Answer engine that retrieves, cites, and synthesizes web sources in place of a traditional results page.
- [You.com](https://you.com) - Multi-mode AI search with agent workflows and enterprise deployments.

### Knowledge management

Notes and knowledge bases that ground AI in your own documents and surface what's relevant.

- [Gemini Notebook (formerly NotebookLM)](https://notebooklm.google) - Google's research and note-taking tool that grounds answers in your uploaded sources and generates audio and video overviews.
- [Mem](https://get.mem.ai) - Self-organizing notes app that surfaces related notes and drafts follow-ups on demand.
- [Notion MCP](https://developers.notion.com/docs/mcp) - Notion's official MCP server that lets AI agents and assistants search, read, and update a Notion workspace.
- [Obsidian](https://obsidian.md) - Local-first markdown knowledge base with a large plugin ecosystem for AI assistants, semantic search, and note generation.

### Meetings and voice

Assistants that record, transcribe, and summarize meetings, then draft the follow-ups.

- [Fathom](https://fathom.video) - Meeting recorder that produces action items, CRM updates, and follow-up emails from a conversation.
- [Fireflies](https://fireflies.ai) - Meeting assistant that records, transcribes, and answers questions across a team's call history.
- [Granola](https://www.granola.ai) - Notepad that listens to your meetings and turns your rough notes into structured summaries.
- [Otter](https://otter.ai) - Live transcription and meeting summaries with a chat interface over meeting history.

## Industry applications

Vertical products where an LLM sits at the core of a specific profession's workflow, from customer support to law, medicine, sales, and the classroom.

### Customer support

AI agents that resolve customer conversations end to end across chat and messaging channels.

- [Hugo](https://hugo.ai) - Crisp's AI support agent that resolves conversations end-to-end across chat and messaging channels, connecting to live data and actions through MCP.
- [Intercom Fin](https://www.intercom.com/fin) - AI support agent built on Intercom's messenger that answers questions and takes actions across connected systems.

### Sales and CRM

AI-native CRMs and outbound platforms that research prospects, enrich records, and run sequences.

- [11x](https://www.11x.ai) - Digital sales development reps that prospect, personalize, and book meetings.
- [Artisan](https://www.artisan.co) - Outbound platform fronted by Ava, an AI SDR that researches and emails prospects.
- [Attio](https://attio.com) - AI-native CRM that builds pipeline views, enriches records, and runs research agents across customer data.
- [Clay](https://www.clay.com) - Data enrichment and outbound workspace that composes dozens of providers and LLM prompts into a spreadsheet.
- [muchbetter.ai](https://muchbetter.ai) - AI sales-coaching platform that trains field teams through voice-driven role-play simulations with virtual clients and real-time feedback.
- [Unify](https://www.unifygtm.com) - Warm outbound platform that combines intent signals with AI-written sequences.

### Legal

Platforms for legal research, drafting, review, and litigation analytics used inside law firms.

- [Harvey](https://www.harvey.ai) - Legal workflow platform deployed across large law firms for drafting, diligence, and case analysis.
- [Ironclad](https://ironcladapp.com/product/ai) - Contract review and redlining built into Ironclad's CLM.
- [Legora](https://legora.com) - Collaborative legal AI platform for research, drafting, and review, adopted across law firms worldwide.
- [Lex Machina](https://lexmachina.com) - Legal analytics platform mining litigation data to predict case outcomes and inform strategy.

### Healthcare

Clinical documentation, medical answer engines, and AI applied to drug discovery and diagnostics.

- [Abridge](https://www.abridge.com) - Ambient clinical documentation used in major health systems to generate notes during patient visits.
- [Isomorphic Labs](https://www.isomorphiclabs.com) - Alphabet/DeepMind spinout applying AI foundation models to drug discovery and molecular design.
- [Nabla](https://www.nabla.com) - Ambient AI assistant for clinicians that writes structured notes from the consultation audio.
- [OpenEvidence](https://www.openevidence.com) - Medical answer engine for clinicians grounded in peer-reviewed literature.
- [Owkin](https://www.owkin.com) - AI biotech for drug discovery and diagnostics, training multimodal models on data from hospitals worldwide.
- [Suki](https://www.suki.ai) - Voice-first clinical assistant that drafts notes, orders, and codes.

### Education

Tutors and teaching assistants that guide learners with Socratic prompting and help educators plan and grade.

- [ChatGPT Study Mode](https://openai.com/index/chatgpt-study-mode) - ChatGPT mode that guides learners through problems step by step with Socratic prompts instead of giving direct answers.
- [Claude Learning Mode](https://www.anthropic.com/news/introducing-claude-for-education) - Claude style that guides you to your own answer with a Socratic approach instead of solving directly, with Explanatory and Learning variants in Claude Code.
- [Duolingo Max](https://blog.duolingo.com/duolingo-max) - Duolingo's premium tier adding AI-powered roleplay conversations and answer explanations for language learning.
- [Khanmigo](https://www.khanmigo.ai) - Khan Academy's AI tutor that guides students through problems using Socratic prompting.
- [MagicSchool](https://www.magicschool.ai) - AI platform for teachers that plans lessons, differentiates materials, and drafts feedback.
- [Speak](https://www.speak.com) - AI-powered language tutor built around spoken conversation practice with real-time feedback.

## Creative & media

Generative tools for producing and editing visual, audio, and video content, from design canvases to image, video, and music models.

### Design and creative

Generative design canvases that turn prompts into editable visuals, prototypes, and production assets.

- [Claude Design](https://claude.ai/design) - Anthropic Labs tool that turns prompts into designs, prototypes, slides, and decks and can apply your team's design system.
- [Krea](https://www.krea.ai) - Real-time generative canvas for image, video, and 3D creation.
- [Pencil](https://www.pencil.dev) - AI-native design canvas for developers that generates editable designs and production-ready code from a VS Code or Cursor integration.
- [Photoroom](https://www.photoroom.com) - AI photo editor and product-image studio with instant background removal and generative editing.
- [Weavy](https://weave.figma.com) - Node-based creative canvas that chains AI models for image, video, and 3D generation and editing.

### Image generation

Text-to-image models and editors for creating and refining still images.

- [Flux](https://blackforestlabs.ai) - Black Forest Labs' open-weight and hosted models known for photoreal prompt adherence.
- [Imagen](https://deepmind.google/models/imagen) - Google DeepMind's text-to-image model generating high-resolution images with SynthID watermarking.
- [Magnific](https://magnific.ai) - AI upscaler and enhancer that adds detail and reimagines images at high resolution.
- [Midjourney](https://www.midjourney.com) - Generative image service known for a consistent aesthetic and a large creator community.
- [Nano Banana](https://deepmind.google/models/gemini-image) - Google's Gemini-based image model line known for precise, conversational editing.
- [Seelab](https://www.seelab.ai) - AI photo studio that trains custom models on your products and brand to generate on-brand product visuals.

### Video generation

Models and studios that generate and edit video, some with natively synchronized audio.

- [Google Flow](https://labs.google/fx/tools/flow) - AI filmmaking studio built on Veo and Imagen for generating and editing cinematic scenes.
- [HeyGen](https://www.heygen.com) - Generates talking-avatar videos from a script, with voice cloning and translation for marketing and training.
- [Kling](https://kling.kuaishou.com) - Kuaishou's video model with long-duration generations and strong motion coherence.
- [Pika](https://pika.art) - Generative video app with effects-driven editing and social sharing.
- [Runway](https://runwayml.com) - Video model suite and editor used in film and advertising production.
- [Veo](https://deepmind.google/models/veo) - Google DeepMind's video model producing high-resolution clips with natively generated synchronized audio.

### Audio and music

Speech-to-text, text-to-speech, voice cloning, and full music generation.

- [AssemblyAI](https://www.assemblyai.com) - Speech-to-text and audio-intelligence API with transcription, diarization, and LLM-powered audio understanding.
- [Deepgram](https://deepgram.com) - Voice AI API for fast, accurate speech-to-text and text-to-speech built for real-time agents.
- [ElevenLabs](https://elevenlabs.io) - Voice synthesis platform covering cloning, dubbing, conversational agents, and audiobooks.
- [Gladia](https://www.gladia.io) - Audio infrastructure API for real-time and async speech-to-text, diarization, and translation across 100+ languages.
- [Gradium](https://gradium.ai) - Kyutai spinout building ultra-low-latency text-to-speech, speech-to-text, and voice-cloning models for voice agents, behind a single API.
- [Suno](https://suno.com) - Text-to-song model that generates full vocal tracks from a prompt.
- [Udio](https://www.udio.com) - Music generation model with fine control over style and structure.

## Models & robotics

The models themselves and the machines they drive: open-weight and small language models, OCR, and robotics foundation models for embodied AI.

### Open-weight models

LLM families released with downloadable weights you can run, fine-tune, and self-host.

- [DeepSeek](https://www.deepseek.com) - Lab releasing reasoning- and coding-focused models with weights published under the MIT License.
- [Gemma](https://ai.google.dev/gemma) - Google DeepMind's family of lightweight open models built from the same research as Gemini, released under a permissive license.
- [GLM](https://z.ai) - Open-weight General Language Model family from Z.ai, formerly Zhipu AI, targeting long-horizon agentic and coding tasks.
- [gpt-oss](https://github.com/openai/gpt-oss) - OpenAI's open-weight reasoning models released under Apache 2.0 and designed to run on single-GPU or consumer hardware.
- [Kimi](https://huggingface.co/moonshotai) - Moonshot AI's Kimi family of large mixture-of-experts open-weight models, strong on agentic and coding tasks.
- [Llama](https://www.llama.com) - Meta's widely deployed open model family, with natively multimodal mixture-of-experts architectures.
- [MiniMax](https://www.minimax.io) - Lab releasing frontier-class open-weight reasoning and coding models under MIT-style licenses.
- [Mistral](https://mistral.ai) - Lab releasing open-weight dense and mixture-of-experts models under Apache 2.0.
- [Nemotron](https://www.nvidia.com/en-us/ai-data-science/foundation-models/nemotron) - NVIDIA's open model family released with open weights, training data, and recipes for agentic reasoning.
- [Qwen](https://github.com/QwenLM) - Alibaba's open-weight family, one of the most-downloaded open model lines, spanning phone-sized to very large MoE models.
- [Whisper](https://github.com/openai/whisper) - OpenAI's open-source automatic speech recognition model for multilingual transcription and translation.

### Small language models

Compact models tuned to run efficiently on-device or on modest hardware.

- [AlphaEdge](https://alphaedge-ai.com) - Sovereign-AI startup that compresses and distills models into small, efficient ones for on-prem document and enterprise workflows.
- [Phi](https://azure.microsoft.com/en-us/products/phi) - Microsoft's family of small open-weight models emphasizing strong reasoning at small parameter counts.
- [Pleias](https://pleias.ai) - Lab training small open-weight models exclusively on public-domain and permissibly licensed data, alongside the fully open Common Corpus dataset.
- [SmolLM](https://github.com/huggingface/smollm) - Hugging Face's fully open family of small text and vision models, with training data and code released for on-device use.

### Robotics and embodied AI

Foundation models and companies bringing learned control to humanoids and real-world machines.

- [1X](https://www.1x.tech) - Humanoid robotics company building the Neo home robot around neural control policies.
- [AMI Labs](https://amilabs.xyz) - Yann LeCun's lab building world models that learn abstract representations of the physical world so agents can predict and plan their actions.
- [Figure](https://www.figure.ai) - Humanoid robotics company training general-purpose manipulation models for commercial deployment.
- [Genesis AI](https://genesis.ai) - Physical-AI lab building robotics foundation models and a general-purpose robot that reasons, plans, and acts in the real world.
- [Gobano Robotics](https://www.gobano.ai) - Robotics company applying imitation learning, reinforcement learning, and world models to dexterous industrial and logistics tasks like folding, assembling, and bin picking.
- [Physical Intelligence](https://www.physicalintelligence.company) - Research lab building foundation models for robot control across embodiments.
- [Skild AI](https://www.skild.ai) - Developer of a general-purpose robot brain trained across thousands of hours of robot data.
- [UMA](https://uma.bot) - Physical-AI company building humanoid and mobile robots that learn new skills from demonstration.
- [Wandercraft](https://en.wandercraft.eu) - Robotics company building AI-powered self-balancing exoskeletons and the Calvin humanoid robot for industrial tasks.

### OCR

Models that convert documents and images into structured, machine-readable text.

- [DeepSeek-OCR](https://github.com/deepseek-ai/DeepSeek-OCR) - Open-weight OCR model using optical token compression for high-throughput, low-cost document-to-Markdown conversion; runs on vLLM.
- [Mistral OCR](https://mistral.ai/news/mistral-ocr) - Hosted OCR API with strong accuracy on complex tables and handwriting for managed, no-ops document extraction.

## Compute & infrastructure

The hardware and platforms that train and serve models: AI chips, local inference engines, GPU clouds, and sandboxes for running agent-generated code.

### AI chips and hardware

Processors purpose-built for training and inference, from GPUs to wafer-scale and photonic chips.

- [Arago](https://www.arago.inc) - Deeptech building a photonic AI chip that runs matrix math with light for order-of-magnitude lower energy use.
- [Cerebras](https://www.cerebras.ai) - Builder of wafer-scale chips that hold an entire model on a single processor for ultra-fast training and inference.
- [Groq](https://groq.com) - Designer of the LPU inference chip and cloud known for sub-hundred-millisecond token generation.
- [NVIDIA](https://www.nvidia.com) - Dominant maker of AI GPUs and the CUDA software stack that most frontier training and inference runs on.
- [Sesterce](https://www.sesterce.com) - AI-factory company operating large, sustainable GPU clusters for training and inference.
- [VSORA](https://vsora.com) - Startup building an inference chip to challenge GPU makers on performance per watt.

### Local inference

Engines and apps for running models on your own CPUs and GPUs.

- [llama.cpp](https://github.com/ggml-org/llama.cpp) - LLM inference engine in pure C/C++ that runs GGUF-format models across CPUs and GPUs on a wide range of hardware.
- [LM Studio](https://lmstudio.ai) - Desktop app to browse, download, and run local models with a built-in chat interface and local server.
- [MLX](https://github.com/ml-explore/mlx) - Apple's array and machine-learning framework optimized for Apple silicon, for on-device training and inference.
- [Ollama](https://ollama.com) - Tool that packages and runs LLMs locally via a simple command line and local API.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput inference and serving library using PagedAttention and continuous batching for production deployment.
- [ZML](https://zml.ai) - Zig-based inference stack that compiles models into standalone native binaries across NVIDIA, AMD, TPU, and Trainium with zero Python dependencies.

### GPU clouds

Providers renting raw GPU capacity, on demand or reserved, for training and inference workloads.

- [CoreWeave](https://www.coreweave.com) - GPU cloud purpose-built for AI, offering large-scale NVIDIA clusters for training and inference.
- [Koyeb](https://www.koyeb.com) - Serverless platform for deploying AI inference and apps on autoscaling CPUs and GPUs worldwide.
- [Lambda](https://lambda.ai) - GPU cloud offering on-demand and reserved NVIDIA clusters for training and inference.
- [Nebius](https://nebius.com) - AI-focused cloud providing GPU compute, managed inference, and ML tooling.
- [RunPod](https://www.runpod.io) - GPU cloud with on-demand and serverless GPUs for training and inference.

### Hosted inference and fine-tuning

Managed platforms that serve, fine-tune, and post-train models behind an API, with no infrastructure to operate.

- [Adaptive ML](https://www.adaptive-ml.com) - Reinforcement-learning platform for post-training, evaluating, and serving enterprise-specialized open models.
- [DeepInfra](https://deepinfra.com) - Serverless inference cloud for open-weight models across text, embeddings, speech, image, and video, billed per token with no minimums and no idle GPU charges.
- [Fireworks AI](https://fireworks.ai) - Inference and fine-tuning platform for open-weight models with low-latency routing.
- [FlexAI](https://flex.ai) - Universal AI compute platform that abstracts heterogeneous hardware so developers can train, fine-tune, and serve models without managing infrastructure.
- [Hugging Face](https://huggingface.co) - The hub for open models, datasets, and Spaces, plus the Transformers library and hosted inference that anchor the open-source AI ecosystem.
- [Replicate](https://replicate.com) - Hosted registry and inference layer for open-source models.
- [Together AI](https://www.together.ai) - Inference, fine-tuning, and training platform for open-weight models.

### Serving and orchestration

Self-hosted stacks that schedule, scale, and coordinate model serving across nodes.

- [llm-d](https://llm-d.ai) - Red Hat-led, Kubernetes-native distributed inference framework built on vLLM for serving LLMs at scale.
- [NVIDIA Dynamo](https://github.com/ai-dynamo/dynamo) - Open-source datacenter-scale orchestration layer that coordinates vLLM, SGLang, and TensorRT-LLM into distributed multi-node inference.
- [NVIDIA NIM](https://developer.nvidia.com/nim) - Prebuilt, containerized inference microservices for deploying optimized model endpoints across cloud, data center, and workstation.

### Gateways and routing

Proxies sitting in front of model providers to route, meter, and govern traffic.

- [Edgee](https://edgee.ai) - Agent gateway that sits between coding agents and LLM providers, applying budget-driven routing, gateway-side token compression, and per-developer cost attribution across Claude Code, Codex, Cursor, and Copilot.
- [OpenRouter](https://openrouter.ai) - Unified API and marketplace routing requests across hundreds of models and providers.

### Sandboxes

Isolated, ephemeral environments for safely executing AI-generated code.

- [Daytona](https://www.daytona.io) - Secure, elastic infrastructure for running AI-generated code, with agent sandboxes that spin up in tens of milliseconds.
- [E2B](https://e2b.dev) - Open-source runtime that gives AI agents isolated cloud sandboxes to execute code.
- [Modal](https://modal.com) - Serverless Python platform offering on-demand sandboxes for running AI-generated code, model inference, and batch jobs.
- [Vercel Sandbox](https://vercel.com/docs/vercel-sandbox) - Ephemeral, isolated microVMs for running untrusted AI-generated code, from Vercel.

## Developer tooling

Building blocks for developers shipping AI features: agent frameworks, MCP integrations, vector search, memory layers, and evaluation and observability.

### Frameworks and SDKs

Libraries for building, orchestrating, and observing LLM apps and multi-agent systems.

- [Claude Agent SDK](https://docs.claude.com/en/api/agent-sdk) - Anthropic's SDK for building custom agents on the same harness that powers Claude Code, with tools, subagents, and MCP support; formerly the Claude Code SDK.
- [CrewAI](https://www.crewai.com) - Open-source Python framework for orchestrating role-playing, collaborative multi-agent systems.
- [DeepAgents](https://github.com/langchain-ai/deepagents) - LangChain's batteries-included agent harness with planning, sub-agents, a virtual filesystem, and context management for long-running tasks.
- [Google ADK](https://google.github.io/adk-docs) - Google's open-source Agent Development Kit for building, evaluating, and deploying multi-agent systems, model-agnostic and optimized for Gemini.
- [LangChain](https://www.langchain.com) - Framework and platform for building, running, and observing LLM applications.
- [LlamaIndex](https://www.llamaindex.ai) - Data framework for connecting LLMs to private and enterprise data.
- [Vercel AI SDK](https://ai-sdk.dev) - TypeScript toolkit for building streaming AI applications across providers.

### MCP and integrations

Platforms for building and connecting Model Context Protocol servers and agent tool integrations.

- [Alpic](https://alpic.ai) - MCP-native cloud platform to build, deploy, monitor, and distribute MCP servers and ChatGPT apps.
- [Composio](https://composio.dev) - Integration layer that connects AI agents to over a thousand tools with managed authentication, tool search, and agent-friendly APIs.

### Vector databases and retrieval

Embedding stores and search engines that power retrieval-augmented generation.

- [Chroma](https://www.trychroma.com) - Open-source embedding database focused on developer ergonomics.
- [LanceDB](https://lancedb.com) - Embedded and serverless vector database built on the Lance columnar format.
- [Meilisearch](https://www.meilisearch.com) - Open-source search engine with hybrid full-text and vector search and built-in AI-powered semantic ranking.
- [Pinecone](https://www.pinecone.io) - Managed vector database used in production retrieval pipelines.
- [Qdrant](https://qdrant.tech) - Open-source vector search engine with on-disk indexing and filtering.
- [Turbopuffer](https://turbopuffer.com) - Serverless vector and full-text search built directly on object storage.
- [Weaviate](https://weaviate.io) - Open-source vector database with hybrid search and built-in modules.

### Agent memory

Memory layers that give agents persistent, personalized context across sessions.

- [Cognee](https://www.cognee.ai) - Open-source memory layer that builds knowledge graphs from your data for AI agents and RAG.
- [Letta](https://www.letta.com) - Platform for stateful agents with long-term memory, formerly the MemGPT project.
- [Mem0](https://mem0.ai) - Open-source memory layer that gives AI agents persistent, personalized memory across sessions.
- [Supermemory](https://supermemory.ai) - Single memory API for fact extraction, user-profile building, contradiction resolution, and selective forgetting.
- [Zep](https://www.getzep.com) - Memory server for AI agents built on a temporal knowledge graph via the open-source Graphiti library.

### Evaluation and observability

Tracing, testing, and monitoring to measure and debug LLM and agent behavior in production.

- [Datadog LLM Observability](https://www.datadoghq.com/product/ai/llm-observability) - End-to-end tracing, monitoring, and quality and safety evaluation for LLM and agentic applications.
- [Giskard](https://www.giskard.ai) - Open-source testing and evaluation framework that detects hallucinations, biases, and vulnerabilities in LLM and ML systems.
- [Helicone](https://www.helicone.ai) - Open-source LLM observability proxy and analytics.
- [Langfuse](https://langfuse.com) - Open-source tracing, evals, and prompt management for LLM apps.
- [LangSmith](https://www.langchain.com/langsmith) - Tracing, evaluation, and monitoring for LangChain and plain LLM apps.
- [Ragas](https://github.com/explodinggradients/ragas) - Open-source evaluation framework for RAG and LLM applications, with metrics for faithfulness, answer relevance, and context precision.

## Learning & community

Where to keep up and go deeper: newsletters, podcasts, people to follow, courses, foundational papers, events, and communities.

### Newsletters and blogs

Writers and publications covering AI engineering, research, and industry economics.

- [Chip Huyen](https://huyenchip.com) - Essays on ML systems, AI engineering, and shipping models to production.
- [Eugene Yan](https://eugeneyan.com) - Applied scientist writing on ML systems design, LLM evals, and recommender systems.
- [Hamel Husain's Blog](https://hamel.dev) - Practical writing on LLM evaluation, fine-tuning, and shipping ML products.
- [Han-Chung Lee](https://leehanchung.github.io) - Notes on ML engineering, evaluation, and compound AI systems.
- [Latent Space](https://www.latent.space) - Practitioner-focused newsletter and community covering AI engineering.
- [Lilian Weng](https://lilianweng.github.io) - In-depth technical posts on agents, RL, diffusion, and LLMs.
- [One Useful Thing](https://www.oneusefulthing.org) - Ethan Mollick's essays on how knowledge workers are actually using frontier models.
- [Sebastian Raschka](https://magazine.sebastianraschka.com) - "Ahead of AI": deep dives on LLM training, architectures, and research.
- [SemiAnalysis](https://semianalysis.com) - Dylan Patel's research on AI hardware, data centers, and the semiconductor supply chain behind frontier compute.
- [Simon Willison's Weblog](https://simonwillison.net) - Detailed technical notes on LLMs, tools, and prompt engineering from the creator of Datasette.
- [Tensor Economics](https://www.tensoreconomics.com) - Analysis of the economics of AI compute, inference costs, and model serving.
- [Where's Your Ed At](https://www.wheresyoured.at) - Ed Zitron's newsletter with skeptical, deeply reported takes on AI hype, economics, and Big Tech.

### Podcasts

Long-form conversations with the researchers and founders building frontier AI.

- [Dwarkesh Podcast](https://www.dwarkeshpatel.com/podcast) - Long-form interviews with researchers and founders on where AI is heading.
- [Latent Space Podcast](https://www.latent.space/podcast) - Conversations with AI engineers on the systems, tools, and tradeoffs behind production apps.
- [No Priors](https://www.no-priors.com) - Elad Gil and Sarah Guo interview the builders of frontier AI companies.
- [The Cognitive Revolution](https://www.cognitiverevolution.ai) - Deep technical interviews on frontier model capability and alignment.

### People to follow

Researchers, builders, and educators worth following for signal on where AI is going.

- [Andrej Karpathy](https://x.com/karpathy) - Founding OpenAI member and former Tesla AI lead whose talks and threads explain LLMs from first principles.
- [Andrew Ng](https://x.com/AndrewYNg) - DeepLearning.AI and Coursera founder posting pragmatically on applied AI, agents, and education.
- [Boris Cherny](https://x.com/bcherny) - Creator of Claude Code at Anthropic, sharing tips and thinking on agentic coding.
- [Chip Huyen](https://x.com/chipro) - Author of "AI Engineering" and "Designing Machine Learning Systems" writing on shipping ML and LLM systems to production.
- [Clément Delangue](https://x.com/ClementDelangue) - Co-founder and CEO of Hugging Face, championing open-source AI and the model-sharing community.
- [François Chollet](https://x.com/fchollet) - Keras creator and ARC-AGI co-author on reasoning, generalization, and where deep learning falls short.
- [Jim Fan](https://x.com/DrJimFan) - NVIDIA senior research lead covering embodied AI, robotics, and foundation agents.
- [Lilian Weng](https://x.com/lilianweng) - Former OpenAI research lead whose long-form posts are canonical references on agents, RL, and diffusion.
- [Sebastian Raschka](https://x.com/rasbt) - Author of "Build a Large Language Model (From Scratch)" who breaks down model internals and training.
- [Yann LeCun](https://www.linkedin.com/in/yann-lecun) - Turing Award laureate and deep-learning pioneer arguing for world models and open research.

### Courses and learning

Hands-on courses and guides for learning to build and understand LLMs from the ground up.

- [Claude Code Best Practices](https://www.anthropic.com/engineering/claude-code-best-practices) - Anthropic's engineering guide to agentic coding workflows and getting the most out of Claude Code.
- [Claude Code Documentation](https://docs.claude.com/en/docs/claude-code) - Official docs for Anthropic's terminal coding agent, covering setup, workflows, hooks, MCP, and the SDK.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses) - Free hands-on courses on RAG, agents, evaluation, and multimodal systems.
- [LLM101n](https://github.com/karpathy/LLM101n) - Andrej Karpathy's course building a Storyteller LLM from scratch, end to end.
- [nanochat](https://github.com/karpathy/nanochat) - Karpathy's minimal full-stack ChatGPT-style pipeline (tokenizer, pretraining, SFT, RL, inference) in one clean codebase.
- [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) - Andrej Karpathy's video course that builds backprop, GPTs, and tokenizers from scratch.
- [Stanford CS336](https://stanford-cs336.github.io) - Stanford's "Language Modeling from Scratch" course spanning tokenization, architecture, training, and systems.
- [The Rise of the AI Engineer](https://www.latent.space/p/ai-engineer) - The essay that named the discipline and remains a canonical reading list.

### Foundational papers

The research papers that define modern LLMs: architecture, scaling, reasoning, and post-training.

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Vaswani et al., 2017. The transformer: self-attention, multi-head attention, and positional encoding, the architecture everything else builds on.
- [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) - Wei et al., 2022. Showed reasoning can be elicited by prompting alone; the conceptual seed for later reasoning work.
- [DeepSeek-R1](https://arxiv.org/abs/2501.12948) - Guo et al., 2025. Reasoning behavior emerging from reinforcement learning (GRPO) rather than prompting or SFT; the current post-training frontier.
- [FlashAttention](https://arxiv.org/abs/2205.14135) - Dao et al., 2022. IO-aware exact attention that treats the GPU memory hierarchy as the real bottleneck, which is why long context and cheap inference are practical.
- [Kimi k1.5: Scaling RL with LLMs](https://arxiv.org/abs/2501.12599) - Moonshot AI, 2025. The other major RL-reasoning report alongside DeepSeek-R1, with more long-context and infrastructure detail; together they define the reasoning-model recipe.
- [RULER](https://arxiv.org/abs/2404.06654) - Hsieh et al., 2024. Benchmark measuring the real usable context length of long-context models beyond simple retrieval.
- [Training Compute-Optimal LLMs (Chinchilla)](https://arxiv.org/abs/2203.15556) - Hoffmann et al., 2022. Showed token count matters as much as parameter count for a fixed compute budget, revealing most prior models were badly undertrained.
- [Training LMs to Follow Instructions (InstructGPT)](https://arxiv.org/abs/2203.02155) - Ouyang et al., 2022. The post-training blueprint, SFT then RLHF, that turned a text predictor into an assistant.

### Events

Conferences and hackathons for practitioners and researchers shipping AI.

- [AI Engineer Summit](https://www.ai.engineer) - Annual conference for practitioners shipping AI into production.
- [dotAI](https://www.dotai.io) - AI conference for builders and developers, gathering full AI teams and top researchers.
- [Gen AI Days](https://www.generativeai.paris) - Conference on scaling generative AI systems in production, with real-world implementation talks.
- [ICML](https://icml.cc) - International Conference on Machine Learning, a top-tier ML research venue.
- [NeurIPS](https://neurips.cc) - Conference on Neural Information Processing Systems, the largest ML research conference.
- [NVIDIA GTC](https://www.nvidia.com/gtc) - NVIDIA's GPU Technology Conference, a major event for AI compute, research, and tooling.
- [Shift Hackathon](https://shift-hackathon.com) - 48-hour generative-AI hackathon.

### Communities

Forums and subreddits where AI builders and enthusiasts share and discuss.

- [r/artificial](https://www.reddit.com/r/artificial) - General artificial-intelligence discussion community.
- [r/ArtificialInteligence](https://www.reddit.com/r/ArtificialInteligence) - Large general AI community (the subreddit's name is spelled this way).
- [r/ChatGPT](https://www.reddit.com/r/ChatGPT) - One of the largest AI subreddits, covering ChatGPT and consumer AI.
- [r/Claude](https://www.reddit.com/r/Claude) - Community discussing Anthropic's Claude models and apps.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI) - Community for Claude and Claude Code users sharing workflows, prompts, and tips.
- [r/codex](https://www.reddit.com/r/codex) - Community around OpenAI Codex and its coding workflows.
- [r/cursor](https://www.reddit.com/r/cursor) - Community for the Cursor AI code editor.
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA) - Running, fine-tuning, and evaluating open-weight models locally.
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning) - Long-running research-focused subreddit for ML papers and releases.
- [r/mcp](https://www.reddit.com/r/mcp) - Community around the Model Context Protocol and MCP servers.
- [r/midjourney](https://www.reddit.com/r/midjourney) - Community for the Midjourney image generator.
- [r/MistralAI](https://www.reddit.com/r/MistralAI) - Community around Mistral's open-weight models and products.
- [r/OpenAI](https://www.reddit.com/r/OpenAI) - Community tracking OpenAI's models, products, and announcements.
- [r/singularity](https://www.reddit.com/r/singularity) - High-traffic subreddit debating AGI progress and frontier AI news.
- [r/StableDiffusion](https://www.reddit.com/r/StableDiffusion) - Hub for open image-generation models, workflows, and tooling.

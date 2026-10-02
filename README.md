[![VibeOps Forum](./img/vibelinks.png)](https://join.slack.com/t/vibeopsforum/shared_invite/zt-40mvrfmy8-gqycEL7G~Q2tB5KuNW8tBQ)

# 🔗 VibeLinks

> Links to awesome projects from the **VibeOps Forum Community**.

Agents, MCP servers, RAG assistants, labs, and the occasional video game – built in the open by the members of the VibeOps Forum. Everything here is something you can learn from whether you're building something or just trying to keep up with the latest.

**New here?** There's a [⭐ Start Here](#-start-here) section below.
**Want to add something?** See [🤝 Contributing](#-contributing) at the end.

---

### 👉 [Join the VibeOps Forum](https://join.slack.com/t/vibeopsforum/shared_invite/zt-40mvrfmy8-gqycEL7G~Q2tB5KuNW8tBQ)

A Slack community for people building with coding agents, agent operations, A2A, and MCP. Bring working code, hard questions, and lessons from real projects.

---

## 📑 Contents

**🧰 [Build With It](#-build-with-it)**  
[🔌 MCP Servers](#-mcp-servers) · [🤖 AI Agents](#-ai-agents) · [📡 A2A & Agent Interop](#-a2a--agent-interop) · [🧬 GAIT Ecosystem](#-gait-ecosystem) · [💎 Gemini CLI Extensions](#-gemini-cli-extensions) · [💬 Chat With Your X](#-chat-with-your-x) · [☸️ Self-Hosted & Local AI](#-self-hosted--local-ai) · [🧠 Fine-Tuning & Training](#-fine-tuning--training) · [🛠️ Dev Tooling & Clients](#-dev-tooling--clients) · [🎨 Vision, Media & Creative](#-vision-media--creative)

**📚 [Learn From It](#-learn-from-it)**  
[🎓 Workshops, Labs & Learning](#-workshops-labs--learning) · [📰 Articles](#-articles) · [📺 Videos](#-videos) · [🔖 Other Curated Lists](#-other-curated-lists)

**👤 [From the Founder](#-from-the-founder-john-capobianco)**

---

## 🦅 Featured

### 🦞 NetClaw

**[netclaw](https://github.com/automateyournetwork/netclaw)**

A CCIE-level AI network engineering coworker built on [OpenClaw](https://github.com/openclaw/openclaw), with **235 skills and 174 MCP integrations**. Investigate live networks, ground answers in your own documentation with RAG, coordinate specialist agents, and carry out approved changes with baselines, verification, and an immutable audit trail.

Work from chat, the visual HUD, your phone, or a Zoom call. Start with one NetClaw, or run a pack of specialists behind a single Border.

### 🎧 VibeOps Lounge Series

**[VibeOps Lounge (Playlist)](https://www.youtube.com/playlist?list=PLK2-Xx6zS4ME)**

**Where the vibes are real & so are the agents.**

The community's podcast. The VibeOps Lounge is a recurring video series where John sits down with the people actually building at the intersection of AI, MCP, and network ops – interviews, AMAs, unscripted takes, and live demos. No slides. No pitch. Just builders getting into it and figuring this stuff out together.

### 🤖 Itential FlowAI

**[Itential FlowAI](https://www.itential.com/flowai/)**

Itential's agent harness for network and infrastructure operations. Agents reason through goals and execute governed actions – scoped tools, autonomy thresholds, RBAC, full audit trail.

See it working alongside NetClaw in [this A2A demo](https://www.itential.com/resource/demo/netclaw-ai-agents-platform-demo/).

## ⭐ Start Here

We're all figuring this out as we go. If you're not sure where to start, here are a few places others started.

| Project | Why |
| :--- | :--- |
| **[netclaw](https://github.com/automateyournetwork/netclaw)** | Start here. An agentic network engineering coworker, and the deep end of what this looks like. |
| **[pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP)** | The MCP pattern: run show commands and parse them into structured data. |
| **[NetworkingVideoGameStarterKit](https://github.com/automateyournetwork/NetworkingVideoGameStarterKit)** | Spec-driven development, three files, zero blast radius. |
| **[netbox_react_agent](https://github.com/automateyournetwork/netbox_react_agent)** | The agent pattern: plain-English CRUD against your source of truth. |
| **[packet_buddy](https://github.com/automateyournetwork/packet_buddy)** | The RAG pattern: load a packet capture and ask it questions. |
| **[spec-kit](https://github.com/github/spec-kit)** | The discipline: write the spec first, let the agent build to it. |
| **[SpaceAce](https://github.com/automateyournetwork/SpaceAce)** | A hello world for AI Agents, no network required. |
| **[RAG & MCP Workshop – AutoCon 5](https://github.com/automateyournetwork/NAF_AC5)** | Self-paced RAG, TOON, and MCP labs. |

---

## 🧰 Build With It

### 🔌 MCP Servers

*Model Context Protocol servers that expose systems and APIs as tools your agents can call.*

- **[ACI_MCP](https://github.com/automateyournetwork/ACI_MCP)** – A Model Context Protocol Server for Cisco Application Centric Infrastructure (ACI) Application Policy Infrastructure Controller (APIC)
- **[chatGPT_MCP](https://github.com/automateyournetwork/chatGPT_MCP)** – An MCP Server for chatGPT Chat Completions
- **[GitPacketCopilot](https://github.com/automateyournetwork/GitPacketCopilot)** – Add a .pcap(ng); automated reporting; all powered by GitActions, Gemini-CLI, and Packet Copilot MCP
- **[ISE_MCP](https://github.com/automateyournetwork/ISE_MCP)** – An MCP server for Cisco ISE
- **[itential_mark_map](https://github.com/automateyournetwork/itential_mark_map)** – A mark map MCP implementation for Itential
- **[MajorLeagueBaseball_MCP](https://github.com/automateyournetwork/MajorLeagueBaseball_MCP)** – An MCP Server for Major League Baseball
- **[markmap_mcp](https://github.com/automateyournetwork/markmap_mcp)** – An MCP implementation of markmap.js.org
- **[MCPyATS](https://github.com/automateyournetwork/MCPyATS)** – VibeOps – Cisco pyATS MCP Plus Many Other MCPs
- **[netbox-mcp-server](https://github.com/automateyournetwork/netbox-mcp-server)** *(fork)* – Model Context Protocol (MCP) server for read-only interaction with NetBox data in LLMs
- **[NetBox_MCP](https://github.com/automateyournetwork/NetBox_MCP)** – MCP using NetBox
- **[Packet_Conversations](https://github.com/automateyournetwork/Packet_Conversations)** – Selector Packet Copilot Conversations via MCP
- **[pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP)** – An MCP Server for pyATS (experimental)
- **[Wikipedia_MCP](https://github.com/automateyournetwork/Wikipedia_MCP)** – A Model Context Protocol (MCP) Server for Wikipedia
- **[78_MCPs_for_network_automation](https://www.itential.com/resource/guide/the-ultimate-mcp-guide-for-network-automation/)** – The ultimate guide for MCP servers for networking and infrastructure

### 🤖 AI Agents

*ReAct and multi-agent systems – for network gear, and for learning the pattern on something lower-stakes.*

- **[ACI_Agent](https://github.com/automateyournetwork/ACI_Agent)** – An AI ReAct Agent sysem for Cisco ACI
- **[Agent_ISE](https://github.com/automateyournetwork/Agent_ISE)** – AI Agents (ReAct) for Cisco Identity Services Engine
- **[BaseballSuperFan](https://github.com/automateyournetwork/BaseballSuperFan)** – An AI Agent powered by MCP and A2A for Major League Baseball
- **[catalyst-center-health-test](https://github.com/automateyournetwork/catalyst-center-health-test)** – Reverse-engineering test: rebuilding Itential FlowAI agent tools as IAG wrappers around an MCP server
- **[chatGPT_DNAC_analyzer](https://github.com/automateyournetwork/chatGPT_DNAC_analyzer)** – Using chatGPT prompts from Cisco DNAC REST API data
- **[chatGPT_Meraki_Event_Analyzer](https://github.com/automateyournetwork/chatGPT_Meraki_Event_Analyzer)** – A chatGPT / Meraki SDK Python powered event analyzer
- **[ChatterBox](https://github.com/automateyournetwork/ChatterBox)** – Talk to your Netbox with a Langchain
- **[Cisco_Multi_AI_Agent](https://github.com/automateyournetwork/Cisco_Multi_AI_Agent)** – AI Agent using Resoning and Actions (ReAct) Multi AI Agent system for Cisco Systems
- **[Find_A_Job_Agent](https://github.com/automateyournetwork/Find_A_Job_Agent)** – An AI Agent that can help find work!
- **[google_drone](https://github.com/automateyournetwork/google_drone)** – 100% vibe coded Google Drone using Google Maps SDK / MCP; Vision Extension; Computer Use extension from just prompts
- **[langchain_agents](https://github.com/automateyournetwork/langchain_agents)** – Langchain agents
- **[Multi_Device_AI_Agent](https://github.com/automateyournetwork/Multi_Device_AI_Agent)** – Trying to extend AI Agents to a full topology of devices using CML
- **[netbox_react_agent](https://github.com/automateyournetwork/netbox_react_agent)** – An artificial intelligence NetBox ReAct Agent
- **[PokeAgent](https://github.com/automateyournetwork/PokeAgent)** – A ReAct AI Agent for Pokemon
- **[pyATS-Agent](https://github.com/automateyournetwork/pyATS-Agent)** – A Google-based AI Agent for pyATS
- **[ReACT_AI_Agent_for_Cisco_IOS_XE](https://github.com/automateyournetwork/ReACT_AI_Agent_for_Cisco_IOS_XE)** – Playing with Agents
- **[SpaceAce](https://github.com/automateyournetwork/SpaceAce)** – An AI Agent for Space! And a good starting point, a hello world, for AI Agents
- **[SpaceGraph](https://github.com/automateyournetwork/SpaceGraph)** – LangGraph AI Agent approach with Space APIs

### 📡 A2A & Agent Interop

*Agent2Agent protocol work, listeners, and registries for agents that talk to each other.*

- **[A2A](https://github.com/automateyournetwork/A2A)** *(fork)* – An open protocol enabling communication and interoperability between opaque agentic applications.
- **[A2A_Listener](https://github.com/automateyournetwork/A2A_Listener)** – Quick listener to test Agent Push Notifications
- **[AgentExchange](https://github.com/automateyournetwork/AgentExchange)** – A registry for A2A AI Agents

### 🧬 GAIT Ecosystem

*Version control for AI. Git for Artificial Intelligence Tracking – commit, branch, and merge your agent conversations.*

- **[gait](https://github.com/automateyournetwork/gait)** – An open source version and source control system, inspired by Git, for Artificial Intelligence Agents
- **[gait_mcp](https://github.com/automateyournetwork/gait_mcp)** – A Model Context Protocol (MCP) Server for Git for Artificial Intelligence Tracking (GAIT)
- **[gaithub](https://github.com/automateyournetwork/gaithub)** – A hub for Gait repositories
- **[itential_gait_mcp](https://github.com/automateyournetwork/itential_gait_mcp)** – GAIT MCP adjusted for FlowAI
- **[PrincipalSkinner](https://github.com/automateyournetwork/PrincipalSkinner)** – First attempt at blending Ralph Wiggum Loops with GAIT – dummy project
- **[ProfessorFrink](https://github.com/automateyournetwork/ProfessorFrink)** – Ralph Wiggum + GAIT + pyATS

### 💎 Gemini CLI Extensions

*Extensions and companion MCP servers that add voice, vision, screen sharing, and more to Gemini CLI.*

- **[GeminiCLI_ComputerUse_Extension](https://github.com/automateyournetwork/GeminiCLI_ComputerUse_Extension)** – A Google Gemini-CLI extension than enables Gemini Computer Use from the CLI
- **[GeminiCLI_File_Search_Extension](https://github.com/automateyournetwork/GeminiCLI_File_Search_Extension)** – Extending Gemini-CLI with Google Gemini File Search; cloud based RAG
- **[GeminiCLI_GAIT_Extension](https://github.com/automateyournetwork/GeminiCLI_GAIT_Extension)** – A Gemini-CLI extension that adds GAIT support for context control
- **[GeminiCLI_Listen_Extension](https://github.com/automateyournetwork/GeminiCLI_Listen_Extension)** – Turn Gemini-CLI into a server with /isten commands packaged as a Gemini-CLI extension
- **[GeminiCLI_Packet_Buddy_Extension](https://github.com/automateyournetwork/GeminiCLI_Packet_Buddy_Extension)** – A Gemini CLI extension that uses RAG and MCP and Custom Slash Commands to analyze packet captures
- **[GeminiCLI_ScreenShare_Extension](https://github.com/automateyournetwork/GeminiCLI_ScreenShare_Extension)** – Share your screen with Gemini-CLI via this extension using MCP and custom slash commands
- **[GeminiCLI_Slash_Listen](https://github.com/automateyournetwork/GeminiCLI_Slash_Listen)** – A /listen feature for Gemini CLI
- **[GeminiCLI_Slash_Talk](https://github.com/automateyournetwork/GeminiCLI_Slash_Talk)** – Enable your microphone on Windows WSL Ubuntu with this and the corresponding MCP
- **[GeminiCLI_Slash_Vision](https://github.com/automateyournetwork/GeminiCLI_Slash_Vision)** – Custom Slash Commands that use Vision MCP to enable webcam access
- **[GeminiCLI_SubnetCalculator_Extension](https://github.com/automateyournetwork/GeminiCLI_SubnetCalculator_Extension)** – An extension for GeminiCLI that performs subnet calculation
- **[GeminiCLI_Talk_Extension](https://github.com/automateyournetwork/GeminiCLI_Talk_Extension)** – An Extension for Gemini-CLI that enables voice (input) and audio (output); requires openAI for TTS currently
- **[GeminiCLI_TOON_Extension](https://github.com/automateyournetwork/GeminiCLI_TOON_Extension)** – An extension that coverts JSON to TOON before sending to Gemini-CLI for tokens savings and better inference!
- **[GeminiCLI_Vision_Extension](https://github.com/automateyournetwork/GeminiCLI_Vision_Extension)** – An Extension for Gemini-CLI that enables Webcam access including single frame capture and American Sign Language (ASL) modes
- **[pyATS_GeminiCLI_Extension](https://github.com/automateyournetwork/pyATS_GeminiCLI_Extension)** – An easy to install pyATS extension for Gemini CLI
- **[Talk_MCP_for_Gemini_CLI](https://github.com/automateyournetwork/Talk_MCP_for_Gemini_CLI)** – An MCP for Gemini CLI to allow voice
- **[Vision_MCP_for_Gemini_CLI](https://github.com/automateyournetwork/Vision_MCP_for_Gemini_CLI)** – Integrating the webcam with Gemini-CLI via MCP

### 💬 Chat With Your X

*RAG assistants that let you ask questions of packets, docs, configs, routing tables, and rooms.*

- **[capophied](https://github.com/automateyournetwork/capophied)** – A free open source AI chatbot / assistant alternative to chatGPT built using Microsoft phi-2 model
- **[Document_Buddy](https://github.com/automateyournetwork/Document_Buddy)** – Chat with various documents – XLSX, DOCX, PPTX, CSV, PDF, TXT – using chatGPT 4 Turbo and Langchain
- **[Document_graphRAG](https://github.com/automateyournetwork/Document_graphRAG)** – graphRAG approach with .pcap
- **[Document_RAPTOR](https://github.com/automateyournetwork/Document_RAPTOR)** – A RAPTOR Tree of your documents used for Language Model Retrieval to chat with the documents!
- **[IOS_XE_Buddy](https://github.com/automateyournetwork/IOS_XE_Buddy)** – A Basic RAG AI Assistant for Cisco IOS XE powered by Cisco pyATS and ollama
- **[IOS_XE_RAPTOR](https://github.com/automateyournetwork/IOS_XE_RAPTOR)** – An AI assistant for Cisco IOS XE that uses RAPTOR Tree Multi-Query RAG and Ollama so you can 'chat' with your Cisco IOS XE device
- **[Microsoft_Foundry_Local_RAG](https://github.com/automateyournetwork/Microsoft_Foundry_Local_RAG)** – Refactoring my NAF AC4 Workshop from openAI to Foundry Local
- **[packet_buddy](https://github.com/automateyournetwork/packet_buddy)** – pcap analysis provided by chatGPT4 Turbo
- **[packet_graph](https://github.com/automateyournetwork/packet_graph)** – A Knowledge Graph of a .pcap Packet Capture!
- **[packet_raptor](https://github.com/automateyournetwork/packet_raptor)** – An AI Assistant using RAPTOR to talk to .pcaps
- **[Packet_TAG](https://github.com/automateyournetwork/Packet_TAG)** – Table Augmented Generation (TAG) with Packet Captures (.pcaps/pcapng)
- **[pingbuddy](https://github.com/automateyournetwork/pingbuddy)** – AI Analysis and "chat" with your PING
- **[Routing_Table_Buddy](https://github.com/automateyournetwork/Routing_Table_Buddy)** – Quick streamlit app using langchain and pyats
- **[Routing_Table_RAPTOR](https://github.com/automateyournetwork/Routing_Table_RAPTOR)** – Artificial Intelligence analysis and chat with a Tree-Oriented Retrieval approach
- **[Webex_Room_Buddy](https://github.com/automateyournetwork/Webex_Room_Buddy)** – An AI Assistant for Webex Rooms powered by langchain, ollama, and open source language models
- **[Webex_Room_RAPTOR](https://github.com/automateyournetwork/Webex_Room_RAPTOR)** – An AI Assistant for Webex Rooms powered by langchain, ollama, and open source language models using a RAPTOR approach for much larger rooms and much deeper insight

### ☸️ Self-Hosted & Local AI

*Run it yourself – Kubernetes, Ollama, multi-model consensus, and on-device inference.*

- **[ai_cli](https://github.com/automateyournetwork/ai_cli)** – An AI Powered Command Line Interface on Cisco Catalyst IOS XE with Guestshell;Ollama;phi3
- **[Document_KAI8](https://github.com/automateyournetwork/Document_KAI8)** – Document Buddy using Kubernetes with 8 different SLM/LLM for multi-AI analysis
- **[IOS_XE_KAI8](https://github.com/automateyournetwork/IOS_XE_KAI8)** – Chat with Cisco IOS XE using mult-AI consensus with Kubernetes and Ollama
- **[kagent_vision](https://github.com/automateyournetwork/kagent_vision)** – A KAgent Agent with Vision – Capture photos, transform them with Nano Banana, animate them with Veo3. Supports ASL.
- **[kai8s](https://github.com/automateyournetwork/kai8s)** – Ollama as Kubernetes
- **[ollama_with_webui](https://github.com/automateyournetwork/ollama_with_webui)** – Ollama with WebUI – configured to use GPU
- **[Packet_KAI8](https://github.com/automateyournetwork/Packet_KAI8)** – Packet Buddy on Kubernetes with Ollama and multi-LLM using RACK (Retrieval Augmented Consensus Kubernetes)

### 🧠 Fine-Tuning & Training

*RAFT, ReFT, and other approaches to teaching models your network.*

- **[CiscoDevNetIOSXESandbox_ReFT](https://github.com/automateyournetwork/CiscoDevNetIOSXESandbox_ReFT)** – The code used to build the large language model for the Cisco DevNet IOS XE Always-On Sandbox
- **[fine_tune_example](https://github.com/automateyournetwork/fine_tune_example)** – Using RAFT from VLAN 1020 from the Cisco Validated Design for FlexPod for AI
- **[IOS_XE_RAFT](https://github.com/automateyournetwork/IOS_XE_RAFT)** – Using the Retrieval Augmented Fine Tuning (RAFT) approach with Cisco IOS XE JSON using pyATS to fine tune open source models
- **[pyreft_testing](https://github.com/automateyournetwork/pyreft_testing)** – Testing pyreft approach to fine tuning

### 🛠️ Dev Tooling & Clients

*Clients, copilots, terminal tooling, and the specs that keep agents honest.*

- **[chatgpt_client](https://github.com/automateyournetwork/chatgpt_client)** – An interactive Python client for chatGPT
- **[CodingWithCapo](https://github.com/automateyournetwork/CodingWithCapo)** – Creating a chatGPT client with Python
- **[ConfigurationCopilot](https://github.com/automateyournetwork/ConfigurationCopilot)** – A copilot for network configurations
- **[itential_agent_catalogue](https://github.com/automateyournetwork/itential_agent_catalogue)** – Working example
- **[spec-kit](https://github.com/github/spec-kit)** – Open source toolkit from GitHub giving coding agents structured processes, templates, and documented outcomes: spec-driven development, bug fixing, and idea assessment
- **[toad](https://github.com/automateyournetwork/toad)** *(fork)* – A unified interface for AI in your terminal.

### 🎨 Vision, Media & Creative

*Screen capture, image-to-config, generative media, and the occasional chess game.*

- **[BattleChess9000](https://github.com/automateyournetwork/BattleChess9000)** – Inspired by Battle Chess for DOS 1988 – Using Gemini3, Nano Banana3, and Veo3 to reimagine Battle Chess
- **[BattleChess9000_Multiplayer_Service](https://github.com/automateyournetwork/BattleChess9000_Multiplayer_Service)** – The Google Cloud Run service for the multiplayer
- **[ConfigurationVision](https://github.com/automateyournetwork/ConfigurationVision)** – Image to config utility
- **[dream_machine](https://github.com/automateyournetwork/dream_machine)** – Text to AI generated images which are animated with AI with AI generated audio. Make your dreams come true.
- **[Easy_SV3D](https://github.com/automateyournetwork/Easy_SV3D)** – A Streamlit and slightly modified and enhanced version of Stability AI SV3D
- **[screenspeak](https://github.com/automateyournetwork/screenspeak)** – AI as a hotkey – Transform your screenshots into real-time audio analysis with chatGPT Vision and Text to Speech
- **[swarmui_python_script](https://github.com/automateyournetwork/swarmui_python_script)** – A Python script to run multiple Image generation models against the SwarmUI API
- **[VibeGraphics](https://github.com/automateyournetwork/VibeGraphics)** – An MCP Server / Gemini CLI Extension to create modern Infographics for your project – VibeGraphics – Generated with Nano Banana and animated with Veo3

---

## 📚 Learn From It

### 🎓 Workshops, Labs & Learning

*Self-paced labs and workshop material.*

- **[CiscoLive2026_VibeOpsLounge](https://github.com/automateyournetwork/CiscoLive2026_VibeOpsLounge)** – Repository for the full week of Vibe Ops Lounge content for Cisco Live US 2026 in Las Vegas
- **[NAF_AC4_Workshop](https://github.com/automateyournetwork/NAF_AC4)** – RAG Labs from AutoCon 4 in Austin
- **[NAF_AC5_Workshop](https://github.com/automateyournetwork/NAF_AC5)** – RAG, TOON, MCP Labs from AutoCon 5 in Munich
- **[NANOG96_Workshop](https://github.com/automateyournetwork/NANON96_Workshop)** – From RAG to MCP
- **[NetworkingVideoGameStarterKit](https://github.com/automateyournetwork/NetworkingVideoGameStarterKit)** – Using Spec-Driven Development you can use these 3 files as a starter kit to make your very own educational network themed video game (as seen on the [Art of Network Engineering](https://www.itential.com/resource/podcast/stop-vibe-coding-start-spec-driven-development-art-of-network-engineering/))
- **[ONUG_Dallas_2025](https://github.com/automateyournetwork/ONUG_Dallas_2025)** – Repository for ONUG 2025 in Dallas – RAG Session
- **[ONUG_MCP_NYC_2025](https://github.com/automateyournetwork/ONUG_MCP_NYC_2025)** – Repository for ONUG 2025 in NYC – MCP Session
- **[ONUG_RAG_NYC_2025](https://github.com/automateyournetwork/ONUG_RAG_NYC_2025)** – Repository for ONUG 2025 in NYC – RAG Session
- **[PacktEngineeringAgenticNetworkOperations](https://github.com/automateyournetwork/PacktEngineeringAgenticNetworkOperations)** – Labs and presentation from Packt Engineering Agentic Network Operations Session
- **[SharkFest_25_EU_Workshop](https://github.com/automateyournetwork/SharkFest_25_EU_Workshop)** – Code for the Talk to Your Packets Workshop

### 📰 Articles

*Writing on AI, MCP, A2A, and agentic network automation.*

- [MCP 101: Understanding the Model Context Protocol](https://www.itential.com/resource/blog/mcp-101-understanding-the-model-context-protocol/) – Introductory explainer on MCP as a standard for AI-to-infrastructure tool communication.
- [Context as the New Currency: Designing Effective MCP Servers for AI](https://www.itential.com/resource/blog/context-as-the-new-currency-designing-effective-mcp-servers-for-ai/) – Best practices for designing MCP servers/tool descriptions to reduce agent hallucination and improve performance.
- [AI Reasoning for Network Automation: What It Is, How It Works, & Where It Fits](https://www.itential.com/resource/blog/ai-reasoning-for-network-automation-what-it-is-how-it-works-where-it-fits/) – Explains ReAct-style reasoning agents combined with governed, deterministic execution.
- [The Definitive Guide to Spec-Driven Development](https://www.itential.com/resource/guide/spec-driven-development/) – The SDD framework end-to-end: how requirements become approved designs and designs become auditable automation, across five phases with approval gates.
- [AI Agents for Infrastructure](https://www.itential.com/resource/guide/infrastructure-engineers-guide-to-ai-agents/) – A practical taxonomy of agent types, paradigms, and when to use each.
- [From Intent to Impact: Building Production Network Agents in Minutes](https://www.itential.com/blog/company/ai-networking/from-intent-to-impact-building-production-network-agents-in-minutes) – Building a fully functional network agent on Itential's FlowAI platform in under seven minutes.
- [From the CLI to Natural Language: A Network Engineer's Case for VibeOps](https://www.itential.com/blog/company/ai-networking/vibeops-network-engineer-natural-language-infrastructure) – How VibeOps lets engineers operate infrastructure via natural language/AI agents instead of the CLI.
- [Network Engineers: You've Been Doing Spec-Driven Development for Years, You Just Didn't Know It](https://www.itential.com/blog/company/ai-networking/network-engineers-spec-driven-development) – Frames traditional change-management discipline as spec-driven development, essential for safely deploying AI agents in production networks.
- [The Evolution From Network Engineer To AI Orchestrator](https://www.itential.com/resource/blog/from-network-engineer-to-ai-orchestrator/) – A personal account from John Capobianco of transitioning from network engineering to AI orchestration work.
- [Build Agents vs. Operate Agents](https://www.itential.com/resource/guide/build-agents-vs-operate-agents/) – The two kinds of AI agents in infrastructure operations: build agents that generate your automation, and operate agents that act in your environment.

### 📺 Videos

*Talks, walkthroughs, and conference sessions.*

- [VibeOps Lounge (Playlist)](https://www.youtube.com/playlist?list=PLK2-Xx6zS4ME) – The community's podcast; a new AI guest every couple of weeks.
- [Network Automation and Artificial Intelligence Converge](https://www.youtube.com/watch?v=5RgmhIFezas) – Talk on the intersection of network automation and AI.
- [The Evolution From Network Engineer To AI Orchestrator](https://www.youtube.com/watch?v=C4fmlg4-yVo) – On the shift from traditional network engineering to AI-agent orchestration.
- [Stop Vibe Coding: Start Spec-Driven Development](https://www.youtube.com/watch?v=9iWDteEhYk0) – Spec-Driven Development (SDD) as a fix for vibe-coding's flaws.
- [About Model Context Protocol (MCP) – with the AI MadMan, Selector.AI](https://www.youtube.com/watch?v=vYF-vZnpQ4M) – Deep dive on MCP fundamentals and use in networking.
- [From CLI to GPT: How AI Is Rewriting the Rules of Network Automation](https://www.youtube.com/watch?v=hHzN8WeQ86I) – An AIOps-journey talk (CLI → GPT → agents/MCP/SDD).
- [Lab Day! Gemini CLI](https://www.youtube.com/watch?v=_Fx4lBVfARU) – Hands-on Gemini CLI lab session.
- [When AI Agents Talk to Each Other: NetClaw, Itential Platform, & FlowAI in Action](https://www.youtube.com/watch?v=PtPScawUYnE) – Demo of NetClaw, Itential Platform, and FlowAI cooperating via agent-to-agent (A2A) communication.

### 🔖 Other Curated Lists

*Lists worth knowing about from elsewhere in the community.*

- **[awesome-network-automation-ai](https://github.com/automateyournetwork/awesome-network-automation-ai)** *(fork)* – A curated list of awesome resources for applying Artificial Intelligence (AI), Large Language Models (LLMs), and Machine Learning (ML) to network automation.

---

## 👤 From the Founder, John Capobianco

[John Capobianco](https://github.com/automateyournetwork) started the VibeOps Forum and wrote most of what's listed above. His own corner of the internet:

- **[Automate Your Network](https://automateyournetwork.com)** – the site, and the book it's named after
- **[@automateyournetwork](https://github.com/automateyournetwork)** – the GitHub org behind nearly every project here
- **[YouTube Channel](https://www.youtube.com/@johncapobianco2527)** – Personal channel; most videos pair a topic with a companion GitHub repo (network automation, AI agents, Docker, Kubernetes, and more).
- **[Automate Your Network (Playlist)](https://www.youtube.com/playlist?list=PLYYsGDln_GC-XNkO4D0GvuIQIlqZVPMzy)** – Long-running playlist walking through the "Automate Your Network" book chapters.
- [Automate Your Network, Orchestrate the Future: Why My Next Chapter Starts at Itential](https://www.itential.com/resource/blog/automate-your-network-orchestrate-the-future-why-my-next-chapter-starts-at-itential/) – Pairing AI agent reasoning with governed, compliant execution.

---

## 🤝 Contributing

Found something that belongs here? Open a pull request.

**Where does it go?**

1. Does it extend a specific product? → that product's section (Gemini CLI, GAIT).
2. Is it network or infrastructure focused? → the matching capability section.
3. Is it teaching material? → Workshops, Labs & Learning.

Rule 1 wins over rule 2. Entries are alphabetical within each section, formatted as `- **[name](url)** – What it does`, and each project appears exactly once.

## 📄 License

See [LICENSE](./LICENSE).

---

*110 projects · last verified 2026-09-08*

# Festus Koech

**AI Systems Engineer — Agentic AI · Voice · RAG · MLOps · Full-Stack · VoIP**

I design and ship production-grade AI systems end-to-end. Six production deployments, real users, built from scratch.

---

## Skills

| Area | Technologies |
|---|---|
| **AI & Agents** | `LangChain` `LangGraph` `FastMCP` `CrewAI` `Anthropic Claude` `Azure OpenAI` `OpenAI` `Hugging Face` `Prompt Engineering` `Human-in-the-loop` `Agent governance` `A2A flows` |
| **Voice & Speech** | `Whisper STT` `Chatterbox TTS` `Piper TTS` `Silero VAD` `LiveKit` `FreeSWITCH` `VoIP/SIP` `SIP/RTP` `WebSocket audio streaming` `Linphone` |
| **RAG & Search** | `Qdrant` `Weaviate` `ChromaDB` `Jina Embeddings` `Crawl4AI` `SearXNG` `hybrid search` `query rewriting` `multi-source RAG` |
| **MLOps** | `Azure ML` `MLflow` `continuous retraining` `CI/CD quality gates` `model observability` `automated promotion` `GPU compute` |
| **ML & Deep Learning** | `PyTorch` `TensorFlow` `LSTM` `YOLOv11/12 fine-tuning` `NLP` `Behavioural ML` |
| **Computer Vision** | `MediaPipe FaceMesh` `OpenCV` `YOLO object detection` `solvePnP` `head pose estimation` |
| **Backend & APIs** | `FastAPI` `Node.js` `Express.js` `REST APIs` `WebSockets` `Redis pub/sub` `Celery` `BullMQ` `GraphQL` `JWT/OAuth` |
| **Frontend** | `React` `Next.js` `TypeScript` `TailwindCSS` `CSS3` `Component Architecture` |
| **Mobile** | `React Native` `NativeWind` `Kotlin` |
| **Infrastructure** | `Kubernetes (AKS)` `Docker` `NGINX` `Azure Container Apps` `GitHub Actions` `Vercel` `Linux` |
| **Cloud** | `Microsoft Azure` `IBM Cloud` `Vercel` |
| **Databases** | `PostgreSQL` `MySQL` `MongoDB` `Redis` `Qdrant` `Weaviate` `ChromaDB` |
| **Languages** | `Python` `TypeScript` `JavaScript` `Go` `Kotlin` `C/C++` `Rust` `Java` |
| **Network & Telephony** | `MikroTik RouterOS` `Yeastar PBX` `FreeSWITCH` `SIP trunk administration` `IVR` `VLAN segmentation` `WireGuard VPN` |

---

## Projects

| Project | Description | Stack |
|---|---|---|
| [**Elimika AI Tutor**](https://festus-portolio.vercel.app/) | Adaptive agentic learning platform. LangGraph pipeline with real-time multi-source RAG and a custom PyTorch LSTM tracking per-student learning patterns. 1,500+ students, 100% uptime. KCA University pilot incoming. | `Python` `LangGraph` `PyTorch` `Qdrant` `Azure ML` `MLflow` `Kubernetes` |
| [**Elimika 365**](https://festus-portolio.vercel.app/) | Real-time AI exam supervision system. YOLOv11/12 + MediaPipe FaceMesh 478-landmark pose estimation + custom LSTM anomaly model with per-student calibration. 500 concurrent sessions on AKS. | `Python` `FastAPI` `YOLO` `PyTorch` `Redis` `Azure ML` `Kubernetes` |
| [**Voicekit**](https://github.com/Festuskipkoech/voice-kit) | Self-hosted voice agent infrastructure package. Eliminates $0.15–0.25/min platform fees. Whisper STT, Piper TTS, Chatterbox TTS with voice cloning, Silero VAD, OpenAI and Claude LLM routing. True end-to-end token-to-audio streaming. | `Python` `Whisper` `Chatterbox` `Silero VAD` `FastAPI` `Docker` |
| [**Sieve**](https://github.com/Festuskipkoech/sieve) | VoIP AI call interception on FreeSWITCH. LangGraph agent handles or escalates live calls autonomously. Escalated calls pushed to a Kotlin Android app via FCM over Linphone SIP. Full human-in-the-loop telephony. Zero per-minute costs. | `Python` `FastAPI` `LangGraph` `FreeSWITCH` `Kotlin` `Redis` `Docker` |
| [**Prepwise**](https://github.com/Festuskipkoech/Prepwise) | AI job search operating system. Four LangGraph agents — job search, document generation, interview prep, application tracker — sharing state over WebSockets. Ingests a CV, scores jobs, generates tailored resumes and cover letters. | `Python` `LangGraph` `Qdrant` `Jina` `Claude` `PostgreSQL` `Next.js` |
| [**GitHub PR Review MCP Server**](https://github.com/Festuskipkoech/github-pr-mcp) | FastMCP server exposing GitHub pull request operations as deterministic LLM-callable tools. List PRs, read diffs, post inline comments, approve, request changes. Tested end-to-end with MCP Inspector and Claude Desktop. | `Python` `FastMCP` `httpx` `Docker` |
| [**Docker Container Manager MCP Server**](https://github.com/Festuskipkoech) | FastMCP server wrapping the Docker SDK. Gives any LLM client the ability to list, start, stop, inspect, and monitor Docker containers with accurate CPU and memory stats matching `docker stats` output. | `Python` `FastMCP` `Docker SDK` |
| [**OpenSearch Engine**](https://github.com/Festuskipkoech/opensearch) | Zero-cost self-hosted search infrastructure for AI agents. SearXNG metasearch + Spider-rs content extraction, intent classification, parallel engine routing, structured LLM-ready JSON with token counts and relevance scores. | `Go` `Rust` `Python` `SearXNG` `gRPC` `Docker` |
| [**Events Zawadi**](https://eventszawadi.com/) | Full-stack social gifting platform with concurrent transaction handling, BullMQ async job queues, and a surprise-preservation mechanic requiring careful state management at the database layer. 100% uptime. | `Node.js` `Express` `Next.js` `TypeScript` `PostgreSQL` `BullMQ` `Redis` `Azure` |

---

## Contact

[Portfolio](https://festus-portolio.vercel.app/) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/festuskoech) &nbsp;·&nbsp; [GitHub](https://github.com/Festuskipkoech) &nbsp;·&nbsp; koechfestus003@gmail.com &nbsp;·&nbsp; +254 701 183 935

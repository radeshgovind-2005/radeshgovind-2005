# Radesh Govind

**AI Software Engineer** — LLM Infrastructure, Backend Systems & Agentic AI  
BSc Computer Science & Engineering @ ISEL, Lisbon · Expected July 2026

---

## Open Source Contributions

### [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/pull/3732) — Anthropic
**PR #3732** · `fix(schema): add missing property descriptions across official MCP servers`  
Fixed missing `description` fields across 3 official MCP reference servers (filesystem, memory, everything) and resolved missing `required` arrays in 4 tools. Improvements affect how accurately LLMs call these tools across the entire MCP ecosystem.  
`TypeScript` `Zod` `JSON Schema` `MCP`

### [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk/pull/891) — Anthropic · Spring AI
**PR #891** · `docs: document best practice for handling argument errors in MCP tools`  
Documented the recommended error-handling pattern for MCP tool implementations — clarifying when to use `CallToolResult` with `isError: true` vs throwing exceptions, with annotated code examples.  
`Java` `MCP` `Documentation`

---

## Projects

### [LLM eBPF Guardian](https://github.com/radeshgovind-2005/llm-ebpf-guardian)
eBPF-based security sidecar that intercepts syscalls from LLM-generated code at the kernel level — detecting intent-to-action mismatches in agentic AI processes.  
`eBPF` `Linux Kernel` `Python` `Agentic AI Security`

### [MCP Systems Controller](https://github.com/radeshgovind-2005/mcp-systems-controller)
Secure MCP server for Docker/K8s orchestration with Human-in-the-Loop approval gates and Prometheus telemetry — built for agentic AI workflows.  
`MCP` `Docker` `Kubernetes` `Prometheus` `TypeScript`

### [Mech Interp MCP](https://github.com/radeshgovind-2005/mech-interp-mcp)
MCP server exposing mechanistic interpretability tooling — activation patching and attention extraction for transformer models.  
`Mechanistic Interpretability` `Python` `MCP` `Transformers`

### [Multiplatform Adaptive Learning App](https://github.com/radeshgovind-2005/play4change)
Educational ecosystem using AI Agents and RAG to generate contextualized learning content. Built @ U!REKA.  
`RAG` `AI Agents` `Cross-Platform`

### [Serverless AI Interview Assistant](https://github.com/radeshgovind-2005/cf_ai_interview_assistant) · [Live](https://cold-resonance-d00c.radesh-govind.workers.dev)
Edge-native stateful LLM assistant deployed on Cloudflare Workers — uses Durable Objects for strict consistency and Llama 3.3 for inference.  
`Cloudflare Workers` `Durable Objects` `LLM` `Edge AI`

### [Real-Time Multiplayer Poker Dice](https://github.com/radeshgovind-2005/Pdm-Chelas_Poker_Dice)
Real-time multiplayer Android game with synchronized lobbies. MVVM + UDF architecture. **Graded 20/20.**  
`Kotlin` `Jetpack Compose` `Coroutines` `Ktor`

### [ISOLA Strategy Engine](https://github.com/radeshgovind-2005/isolation-board-game)
Complete logic engine for the Isola board game using Minimax + Alpha-Beta Pruning in Prolog.  
`Prolog` `AI` `Game Theory`

---

## Languages & Tools

`Kotlin` `Java` `TypeScript` `Python` `C`  
`Spring Boot` `Node.js` `PostgreSQL` `MongoDB` `Elasticsearch`  
`Docker` `Kubernetes` `Cloudflare Workers` `Linux` `eBPF`  
`MCP` `LangChain` `RAG` `Agentic AI`

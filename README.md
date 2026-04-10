<!--  ╔══════════════════════════════════════════════╗  -->
<!--  ║   radeshgovind-2005/radeshgovind-2005        ║  -->
<!--  ║   paste into your profile repo's README.md  ║  -->
<!--  ╚══════════════════════════════════════════════╝  -->

<h1>
  Radesh
  <em>Govind</em>
</h1>

<p>
  <strong>Software engineer</strong> &nbsp;·&nbsp; Lisbon, Portugal<br>
  <sub>BSc Computer Science & Engineering · ISEL · final year &nbsp;·&nbsp; Jun 2026 · full-time / new grad </sub>
</p>

---

## Open source &nbsp;·&nbsp; Anthropic ecosystem

**[modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk)** &nbsp;`PR #891`&nbsp; ![merged](https://img.shields.io/badge/merged-%E2%9C%93-darkgreen?style=flat-square&labelColor=e6f4ea&color=e6f4ea)

Documented the canonical error-handling pattern for MCP tool implementations — reviewed and merged by Anthropic core team.

<br>

**[modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)** &nbsp;`PR #3732`&nbsp; ![in review](https://img.shields.io/badge/in%20review-%E2%86%BB-orange?style=flat-square&labelColor=fff8e6&color=fff8e6)

Fixed missing fields and malformed `required` arrays across 4 official MCP reference server tools.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Guardian](https://github.com/Viriato-Security/guardian) &nbsp;<sub>active · kernel</sub>

eBPF syscall interceptor for AI processes. Attaches probes to Linux kernel tracepoints to capture every file read, network write, and privilege escalation — nanosecond timestamps, cryptographic event chaining, zero code changes to the monitored model. EU AI Act compliance layer (Art. 12, 13, 15, 17).

`eBPF` `Linux kernel` `Python` `gRPC` `TLS 1.3` `EU AI Act`

</td>
<td width="50%" valign="top">

### [U!REKA Play4Change](https://github.com/radeshgovind-2005/play4change) &nbsp;<sub>final year project</sub>

Multiplatform gamified learning platform. RAG pipeline with pgvector for semantic deduplication. Nightly batch generation eliminates cold-start inference latency. Hexagonal arch + transactional Outbox pattern for consistency under unreliable mobile networks. P95/P99 instrumented.

`Spring Boot` `Kotlin Multiplatform` `pgvector` `LangChain4j` `Prometheus` `Grafana`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [MCP Systems Controller](https://github.com/radeshgovind-2005/mcp-systems-controller) &nbsp;<sub>agentic infra</sub>

MCP server exposing Docker/K8s operations with a mandatory human-in-the-loop approval gate — prevents agentic processes from making unauthorised infrastructure changes.

`MCP` `TypeScript` `Docker` `Kubernetes` `Prometheus`

</td>
<td width="50%" valign="top">

### [Multiplayer Poker Dice](https://github.com/radeshgovind-2005/Pdm-Chelas_Poker_Dice) &nbsp;<sub>full-stack</sub>

Spring Boot SSE for live state broadcasting. Kotlin Coroutines/Flows under concurrent load. Android and web clients from a single REST API.

`Kotlin` `Jetpack Compose` `Coroutines` `React` `TypeScript`

</td>
</tr>
</table>

---

## Stack

<table>
  <tr><td><sub>languages</sub></td><td>Kotlin &nbsp;·&nbsp; Java &nbsp;·&nbsp; Python &nbsp;·&nbsp; TypeScript &nbsp;·&nbsp; C</td></tr>
  <tr><td><sub>backend</sub></td><td>Spring Boot &nbsp;·&nbsp; Node.js &nbsp;·&nbsp; REST &nbsp;·&nbsp; DDD &nbsp;·&nbsp; Hexagonal Architecture</td></tr>
  <tr><td><sub>observability</sub></td><td>Prometheus &nbsp;·&nbsp; Grafana &nbsp;·&nbsp; Micrometer &nbsp;·&nbsp; eBPF</td></tr>
  <tr><td><sub>infra</sub></td><td>Docker &nbsp;·&nbsp; Kubernetes &nbsp;·&nbsp; GitHub Actions &nbsp;·&nbsp; Nginx</td></tr>
  <tr><td><sub>data</sub></td><td>PostgreSQL &nbsp;·&nbsp; pgvector &nbsp;·&nbsp; MongoDB</td></tr>
  <tr><td><sub>AI / agents</sub></td><td>MCP &nbsp;·&nbsp; RAG &nbsp;·&nbsp; LangChain4j &nbsp;·&nbsp; LLM APIs</td></tr>
</table>

---

*I care about what happens under the hood — kernel boundaries, failure modes, how things behave at scale. Right now that means building a kernel-level AI observability agent with eBPF and shipping a production-instrumented multiplatform platform as my final year project. I contribute to Anthropic's MCP ecosystem because I think that's where the most interesting agentic systems are being designed correctly.*

---

<sub>
  <a href="https://github.com/radeshgovind-2005">github.com/radeshgovind-2005</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/radesh-govind">linkedin.com/in/radesh-govind</a> &nbsp;·&nbsp;
  radesh.govind@gmail.com &nbsp;·&nbsp;
  Lisbon, Portugal
</sub>

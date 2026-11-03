<div align="center">

# Ney Fred Jiménez Campos

**AI agents · LLM evaluation · Analytics engineering · Test automation**

I build AI agents and data systems, and I check that they're right: every project below is tested
against known answers.

📍 Cartago, Costa Rica · 🎓 Graduate studies in Computer Science, University of Costa Rica

[![LinkedIn](https://img.shields.io/badge/LinkedIn-neyfred-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neyfred/)
[![Email](https://img.shields.io/badge/Email-neyfred%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:neyfred@gmail.com)

</div>

---

### 🔬 [MetricBench](https://github.com/jmnzcn/metricbench) · [results](https://jmnzcn.github.io/metricbench/)
Can AI agents answer business questions about real data correctly? On raw SQL, four models got
**23–47%** right. With a one-page metric glossary, **92–100%**. Through a dbt + MetricFlow semantic
layer, **98–100%** of what it covers, and "I can't answer that" for the rest, never a made-up number.
78 questions with known answers, 100k real orders.<br>
`dbt` · `MetricFlow` · `DuckDB` · `Claude` · `Gemini`

### 🧪 [dax-parity](https://github.com/jmnzcn/dax-parity) · [![PyPI](https://img.shields.io/pypi/v/dax-parity?label=PyPI)](https://pypi.org/project/dax-parity/)
Tests every DAX measure in a Power BI model against an independent SQL implementation, cell by cell,
on Power BI's own engine: 18,159 cells in about 30 seconds. Claude can draft the reference without
seeing the DAX, and mutation testing shows which bugs your checks would miss.<br>
`Power BI` · `DAX` · `DuckDB` · `.NET` · `Python`

### 🇨🇷 [mcp-hacienda-cr](https://github.com/jmnzcn/mcp-hacienda-cr) · [![npm](https://img.shields.io/npm/v/mcp-hacienda-cr?label=npm)](https://www.npmjs.com/package/mcp-hacienda-cr)
Connects Claude, Cursor and other assistants to Costa Rica's Ministry of Finance: exchange rates,
taxpayer status, product codes with their VAT, tax exemptions, and a validator for e-invoice XML
(official 4.4 schema, line and total math, live checks against the ministry's data).<br>
`TypeScript` · `MCP` · `XML Schema` · `Vitest`

---

| Area | Project | Proof |
|---|---|---|
| **AI agents & evaluation** | [ReconBench](https://github.com/jmnzcn/reconbench) | Benchmark of 261 finance cases with known answers, including planted false facts and prompt injections |
| | [dispute-agent](https://github.com/jmnzcn/dispute-agent) | Claude agent with deterministic guardrails: 100% exact decisions (Opus), 0 false disputes, 20/20 injections resisted |
| | [voice-agent-benchmark](https://github.com/jmnzcn/voice-agent-benchmark) | 15 cloud speech and LLM services vs. fully local ones: latency, accuracy, cost, privacy |
| **Analytics & BI** | [recovery-bi](https://github.com/jmnzcn/recovery-bi) | Power BI report generated as code (TMDL + PBIR): 17,885 cells checked, 0 mismatches |
| **Data engineering** | [vendor-recovery-engine](https://github.com/jmnzcn/vendor-recovery-engine) | Reconciliation over 2.7M rows: $895,010 recoverable found, 0 false claims against ground truth |
| | [deduction-stream](https://github.com/jmnzcn/deduction-stream) | Kafka Streams, exactly-once: 19,283 of 19,283 verdicts identical to batch after a chaos test |
| **QA & testing** | [flightbooking-qa-copilot-mcp](https://github.com/jmnzcn/flightbooking-qa-copilot-mcp) | Flask microservices, API tests with RAG-generated cases, and an MCP server as a QA copilot |
| | [avanxa](https://github.com/jmnzcn/avanxa) | Full-stack app with 70 tests (API, frontend, Playwright end to end) · [live demo](https://avanxa.onrender.com) |
| **Research** | [virtual-agent-trust-study](https://github.com/jmnzcn/virtual-agent-trust-study) | Unity experiment: how chat vs. a 3D avatar with voice changes user trust |

Five of these form one system for recovering money Amazon deducts from vendors: the [engine](https://github.com/jmnzcn/vendor-recovery-engine), its [real-time version](https://github.com/jmnzcn/deduction-stream), an [agent](https://github.com/jmnzcn/dispute-agent) that disputes the claims, a [benchmark](https://github.com/jmnzcn/reconbench) for such agents, and the [report](https://github.com/jmnzcn/recovery-bi) finance reads.

**Stack:** Python · TypeScript · Java · C# · SQL · DuckDB · dbt · Power BI / DAX · Kafka · PostgreSQL ·
Claude · Gemini · MCP · pytest · Playwright · GitHub Actions · Docker

Open to roles and projects in applied AI, LLM evaluation, analytics engineering and QA:
[get in touch](mailto:neyfred@gmail.com).

<details>
<summary><b>Coursework and smaller projects</b></summary>
<br>

- [asesor-agilidad-escala](https://github.com/jmnzcn/asesor-agilidad-escala): an agent that recommends a scaled agile framework (Nexus, LeSS, SAFe, Disciplined Agile) with an auditable multi-criteria matrix. Graduate course, UCR.
- [pf3312_lab](https://github.com/jmnzcn/pf3312_lab): three 3D virtual agents in Unity with facial expressions and lip-sync, the start of the trust study above.
- [coursework](https://github.com/jmnzcn/coursework): other course projects in one repository, with their history (a Gemini voice chat CLI, the flight microservices that became the QA copilot).

</details>

<details>
<summary><b>🇨🇷 En español</b></summary>
<br>

Construyo agentes de IA y sistemas de datos, y compruebo que den la respuesta correcta: cada proyecto
de esta página se prueba contra respuestas conocidas.

- **MetricBench:** los agentes de IA aciertan 23–47% de preguntas de negocio con SQL directo, 92–100%
  con un glosario de métricas y 98–100% con una capa semántica (dbt + MetricFlow).
- **dax-parity** (PyPI): prueba cada medida DAX de Power BI contra una implementación independiente,
  celda por celda.
- **mcp-hacienda-cr** (npm): conecta asistentes de IA con las APIs de Hacienda y valida facturas
  electrónicas 4.4 antes de enviarlas.

Abierto a roles y proyectos en IA aplicada, evaluación de LLMs, analytics engineering y QA:
[escribime](mailto:neyfred@gmail.com).

</details>

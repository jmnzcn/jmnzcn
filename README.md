<div align="center">

# Ney Fred Jiménez Campos

**AI agents · LLM evaluation · Analytics engineering · Test automation**

I build AI agents and data systems, and I check that they're right: every project below is tested
against known answers.

📍 Cartago, Costa Rica · 🎓 Graduate studies in Computer Science, University of Costa Rica

[![LinkedIn](https://img.shields.io/badge/LinkedIn-neyfred-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neyfred/)
[![Email](https://img.shields.io/badge/Email-neyfred%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:neyfred@gmail.com)

</div>

**Experience.** IT Systems Business Analyst at GSK since 2022, with 9+ years in pharmaceutical and
healthcare IT (GSK, Baxter) in FDA-regulated environments. Day to day: supporting the main commercial
system, Oracle SQL and Power BI reporting, automating manual daily processes, building data pipelines
that clean data and produce consolidated reports, and the full testing cycle for upgrades, including
a cloud migration. Before that, QA automation with Playwright and Selenium (Crux Consultores) and BI with
OLAP cubes (Avantica, now Encora). The projects below are what I build outside that work.

---

### 🔬 [MetricBench](https://github.com/jmnzcn/metricbench) · [results](https://jmnzcn.github.io/metricbench/)
Can AI agents answer business questions about real data correctly? On raw SQL, four models got
**12–40%** of the answerable questions right, and three out of four misses were one unwritten
convention: which orders count. With a one-page metric glossary, **91–100%**. Through a dbt + MetricFlow semantic
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
| **AI agents & evaluation** | [ReconBench](https://github.com/jmnzcn/reconbench) and [dispute-agent](https://github.com/jmnzcn/dispute-agent) | A benchmark of 261 synthetic finance cases and a Claude agent whose decisions are re-checked by code. Four models ignored all 32 instructions planted in documents, but accepted planted false facts (Haiku 16 of 32, Opus 1). Filing only what a rule check confirms sends 10% of cases to a person with Opus and 27% with Haiku. On references the rules could only call ambiguous, the agent matched the right invoice in 8 of 8 |
| | [voice-agent-benchmark](https://github.com/jmnzcn/voice-agent-benchmark) | 15 cloud speech and LLM services vs. fully local ones: latency, accuracy, cost, privacy |
| **Analytics & BI** | [recovery-bi](https://github.com/jmnzcn/recovery-bi) | Power BI report generated as code (TMDL + PBIR): 17,885 cells checked, 0 mismatches |
| **Data engineering** | [vendor-recovery-engine](https://github.com/jmnzcn/vendor-recovery-engine) | Reconciliation over 2.7M synthetic rows: $895,010 recoverable found, 0 false claims against the known answers |
| | [deduction-stream](https://github.com/jmnzcn/deduction-stream) | Kafka Streams, exactly-once: 19,283 of 19,283 verdicts identical to batch after a chaos test |
| **QA & testing** | [flightbooking-qa-copilot-mcp](https://github.com/jmnzcn/flightbooking-qa-copilot-mcp) | Flask microservices, API tests with RAG-generated cases, and an MCP server as a QA copilot |
| | [avanxa](https://github.com/jmnzcn/avanxa) | Full-stack app with 70 tests (API, frontend, Playwright end to end) · [live demo](https://avanxa.onrender.com) |
| **Research** | [virtual-agent-trust-study](https://github.com/jmnzcn/virtual-agent-trust-study) | Unity experiment: how chat vs. a 3D avatar with voice changes user trust |

Five of these form one system for recovering money Amazon deducts from vendors: the [engine](https://github.com/jmnzcn/vendor-recovery-engine), its [real-time version](https://github.com/jmnzcn/deduction-stream), an [agent](https://github.com/jmnzcn/dispute-agent) that disputes the claims, a [benchmark](https://github.com/jmnzcn/reconbench) for such agents, and the [report](https://github.com/jmnzcn/recovery-bi) finance reads. All five run on synthetic data: the engine generates a world of 170 vendors, which is how the right answer for every deduction is known. Real exports will bring cases this world doesn't have.

I work with Claude Code, and the commits say so. My part is what a model can't grade for itself: the questions, the known answers and the checks each project has to pass.

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
de esta página se prueba contra respuestas conocidas. Trabajo con Claude Code y los commits lo indican;
lo mío son las preguntas, las respuestas conocidas y las comprobaciones que cada proyecto debe pasar.
Los cinco proyectos de recuperación de deducciones usan datos sintéticos.

**Experiencia.** Analista de sistemas de negocio en GSK desde 2022, con más de 9 años en TI de la
industria farmacéutica y de salud (GSK, Baxter) en entornos regulados por la FDA: soporte del sistema
comercial principal, reportes en Oracle SQL y Power BI, automatización de procesos manuales diarios,
pipelines de datos que limpian la información y generan consolidados, y el ciclo completo de pruebas
de actualizaciones, incluida una migración a la nube. Antes, automatización de pruebas con Playwright y
Selenium (Crux Consultores) e inteligencia de negocios con cubos OLAP (Avantica, hoy Encora).

- **MetricBench:** los agentes de IA aciertan 12–40% de las preguntas respondibles con SQL directo, 91–100%
  con un glosario de métricas y 98–100% con una capa semántica (dbt + MetricFlow).
- **dax-parity** (PyPI): prueba cada medida DAX de Power BI contra una implementación independiente,
  celda por celda.
- **mcp-hacienda-cr** (npm): conecta asistentes de IA con las APIs de Hacienda y valida facturas
  electrónicas 4.4 antes de enviarlas.

Abierto a roles y proyectos en IA aplicada, evaluación de LLMs, analytics engineering y QA:
[escribime](mailto:neyfred@gmail.com).

</details>

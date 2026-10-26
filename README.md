<div align="center">

# Ney Fred Jiménez Campos

**Ingeniero de software · Agentes de IA · Evaluación de LLMs · QA automatizado**<br>
*Software engineer · AI agents · LLM evaluation · Test automation*

📍 Cartago, Costa Rica · 🎓 Posgrado en Computación e Informática, UCR

[![LinkedIn](https://img.shields.io/badge/LinkedIn-neyfred-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neyfred/)
[![Email](https://img.shields.io/badge/Email-neyfred%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:neyfred@gmail.com)

[Español](#-español) · [English](#-english)

</div>

---

## 🇨🇷 Español

Construyo y evalúo **agentes conversacionales con IA**: desde elegir qué modelo de voz o LLM conviene según latencia, costo y privacidad, hasta probar que el sistema completo funcione y medir cómo lo perciben las personas que lo usan.

### Proyectos destacados

#### 📦 [Vendor Recovery Engine: conciliación de deducciones de Amazon](https://github.com/jmnzcn/vendor-recovery-engine) · [📊 resultados interactivos](https://jmnzcn.github.io/vendor-recovery-engine/)
Concilia las deducciones de Amazon Vendor Central (faltantes, reclamos de precio, chargebacks) y los pagos contra los registros del vendor: decide qué se puede disputar, con qué evidencia y qué fila de qué archivo lo prueba, y arma la cola de trabajo por plazo y valor esperado. Sobre **2,7 millones de filas** de 170 vendors (mundo sintético construido con datos reales de UCI y del BCE) encontró **$895.010 recuperables**, con **0 reclamos falsos** frente a la verdad conocida.
- Curva de robustez contra lo que *realmente* pasó: la precisión se mantiene en 100 % aunque falte evidencia. Pipeline de cartas de disputa con **Claude** y un verificador determinista que exige que cada monto, ID y fecha salga de la evidencia (atrapó 975 de 975 errores inyectados).
- `Python` · `pandas` · `pandera` · `pytest` · `hypothesis` · `Claude API` · `GitHub Actions`

#### 🎙️ [Benchmark de servicios de voz para agentes conversacionales](https://github.com/jmnzcn/voice-agent-benchmark) · [📊 resultados interactivos](https://jmnzcn.github.io/voice-agent-benchmark/)
Comparé **15 servicios** de STT, LLM y TTS (OpenAI, Anthropic, Gemini, Groq, Deepgram, Azure, AssemblyAI, ElevenLabs, Google) contra alternativas **100 % locales** (Ollama, faster-whisper, Piper). Medí latencia, precisión (WER, MOS), costo, privacidad, customización e integración, y el flujo completo **STT → LLM → TTS** en cuatro stacks.
- Datos crudos, audios de prueba con hash SHA-256 y scripts para regenerar tablas y gráficos sin volver a gastar créditos.
- `Python` · `Ollama` · `faster-whisper` · `Piper` · `pandas` · `pytest`

#### 🇨🇷 [mcp-hacienda-cr: servidor MCP de Hacienda para facturación electrónica](https://github.com/jmnzcn/mcp-hacienda-cr)
Conecta a Claude, Cursor y otros asistentes con las APIs públicas del Ministerio de Hacienda: tipo de cambio, situación tributaria de contribuyentes (moroso u omiso), códigos **CABYS con su IVA** y exoneraciones. Por ejemplo, le puedes preguntar *"¿qué CABYS e IVA lleva el café tostado?"* o *"¿esta empresa está al día con Hacienda?"*.
- 25 tests unitarios, tests de contrato contra la API real y CI en Node 18/20/22 con una corrida semanal en vivo.
- `TypeScript` · `MCP SDK` · `Zod` · `Vitest` · `GitHub Actions`

#### 🧪 [FlightBooking QA Copilot: microservicios + servidor MCP](https://github.com/jmnzcn/flightbooking-qa-copilot-mcp)
Sistema de reservas de vuelos con **3 microservicios Flask** (vuelos, reservas, usuario) documentados con Swagger/OpenAPI, y una suite de **pruebas automatizadas de API** que incluye casos generados con un enfoque **RAG** (ChromaDB).
- Un **servidor MCP** que funciona como "QA Copilot": revisa la salud de los servicios, invoca endpoints, ejecuta suites de `pytest` y lee código y documentación del repo.
- CI en **GitHub Actions** con reportes JUnit y recolección de métricas de pruebas.
- `Python` · `Flask` · `FastMCP` · `ChromaDB` · `pytest` · `Docker` · `GitHub Actions`

#### 🤖 [Efecto de la visibilidad de un agente virtual en la confianza del usuario](https://github.com/jmnzcn/virtual-agent-trust-study)
Experimento de investigación en **Unity** con tres condiciones: sin asistencia, chat con **Gemini**, y avatar 3D con voz **Azure TTS** y sincronía labial. Registra el desempeño y la confianza de cada participante (escala 1–7) para analizar cómo la presencia del agente cambia la confianza del usuario.
- Demos en video: [sin asistencia](https://youtu.be/upMpOpCAWgQ) · [solo chat](https://youtu.be/U_A_y0d-Hxg) · [avatar y voz](https://youtu.be/_h3h9BOnI18)
- `Unity` · `C#` · `Gemini API` · `Azure Speech` · `Python` (análisis)

#### ✅ [Avanxa: app full-stack de hábitos](https://github.com/jmnzcn/avanxa) · [🚀 demo en vivo](https://avanxa.onrender.com)
App para registrar hábitos diarios, semanales o mensuales, con rachas, estadísticas y un panel de administración. La llevé de prototipo a app integrada: corregí el contrato roto entre frontend y backend, conecté el panel a datos reales y cerré un hueco de seguridad que encontraron los tests.
- **70 tests** (API con Supertest, servicios del frontend y end-to-end con Playwright) y CI en GitHub Actions; desplegada en Render como un solo servicio con PostgreSQL.
- `TypeScript` · `React` · `Express` · `Prisma` · `PostgreSQL` · `Playwright` · `GitHub Actions`

### Stack

**IA y LLMs:** OpenAI · Anthropic · Gemini · Ollama · RAG · MCP · STT/TTS  
**Backend:** Python · Flask · Node.js · Express · Prisma · PostgreSQL  
**Frontend:** React · Vite · TypeScript · Tailwind CSS  
**Calidad y DevOps:** pytest · GitHub Actions · Docker  
**Otros:** Unity · C#

### Me interesa

Agentes de IA en producción, evaluación y observabilidad de LLMs, automatización de pruebas con IA y productos de datos. Abierto a oportunidades y proyectos freelance: [escribime](mailto:neyfred@gmail.com).

---

## 🇺🇸 English

I build and evaluate **AI conversational agents**: from choosing the right speech or LLM model based on latency, cost and privacy, to testing that the whole system works and measuring how people perceive it.

### Featured projects

#### 📦 [Vendor Recovery Engine: Amazon deduction reconciliation](https://github.com/jmnzcn/vendor-recovery-engine) · [📊 interactive results](https://jmnzcn.github.io/vendor-recovery-engine/)
Reconciles Amazon Vendor Central deductions (shortages, price claims, chargebacks) and payments against a vendor's records: decides what can be disputed, with which evidence and which file row proves it, and builds a work queue by deadline and expected value. On **2.7M rows** from 170 vendors (a synthetic world built on real UCI and ECB data) it found **$895,010 recoverable** with **zero false claims** against ground truth.
- Robustness curve against what *really* happened: precision holds at 100 % as evidence goes missing. A dispute-letter pipeline with **Claude** and a deterministic verifier that requires every amount, ID and date to come from the evidence (caught 975 of 975 injected errors).
- `Python` · `pandas` · `pandera` · `pytest` · `hypothesis` · `Claude API` · `GitHub Actions`

#### 🎙️ [Speech services benchmark for conversational agents](https://github.com/jmnzcn/voice-agent-benchmark) · [📊 interactive results](https://jmnzcn.github.io/voice-agent-benchmark/)
Benchmarked **15 STT, LLM and TTS services** (OpenAI, Anthropic, Gemini, Groq, Deepgram, Azure, AssemblyAI, ElevenLabs, Google) against **fully local** alternatives (Ollama, faster-whisper, Piper). Measured latency, accuracy (WER, MOS), cost, privacy, customization and integration effort, plus the full **STT → LLM → TTS** pipeline across four stacks.
- Raw data, SHA-256-verified test audio and scripts to rebuild every table and chart without spending API credits.
- `Python` · `Ollama` · `faster-whisper` · `Piper` · `pandas` · `pytest`

#### 🇨🇷 [mcp-hacienda-cr: Costa Rica Ministry of Finance MCP server for e-invoicing](https://github.com/jmnzcn/mcp-hacienda-cr)
Connects Claude, Cursor and other assistants to Costa Rica's Ministry of Finance public APIs: exchange rates, taxpayer status, **CABYS product codes with their VAT rate**, and tax exemptions.
- 25 unit tests, live contract tests against the real API, and CI on Node 18/20/22 with a weekly live run.
- `TypeScript` · `MCP SDK` · `Zod` · `Vitest` · `GitHub Actions`

#### 🧪 [FlightBooking QA Copilot: microservices + MCP server](https://github.com/jmnzcn/flightbooking-qa-copilot-mcp)
Flight booking system with **3 Flask microservices** (flights, bookings, user facade) documented with Swagger/OpenAPI, plus an **automated API test suite** that includes **RAG-generated** test cases (ChromaDB).
- An **MCP server** acting as a "QA Copilot": checks service health, calls endpoints, runs `pytest` suites and reads code and docs from the repo.
- **GitHub Actions** CI with JUnit reports and test metrics collection.
- `Python` · `Flask` · `FastMCP` · `ChromaDB` · `pytest` · `Docker` · `GitHub Actions`

#### 🤖 [How virtual agent visibility affects user trust](https://github.com/jmnzcn/virtual-agent-trust-study)
A **Unity** research experiment with three conditions: no assistance, **Gemini** chat, and a 3D avatar with **Azure TTS** voice and lip sync. It logs each participant's performance and trust (1–7 scale) to study how the agent's presence changes user trust.
- Video demos: [no assistance](https://youtu.be/upMpOpCAWgQ) · [chat only](https://youtu.be/U_A_y0d-Hxg) · [avatar + voice](https://youtu.be/_h3h9BOnI18)
- `Unity` · `C#` · `Gemini API` · `Azure Speech` · `Python` (analysis)

#### ✅ [Avanxa: full-stack habit tracker](https://github.com/jmnzcn/avanxa) · [🚀 live demo](https://avanxa.onrender.com)
Track daily, weekly or monthly habits with streaks, stats and an admin panel. I took it from prototype to integrated app: fixed the broken frontend/backend contract, wired the dashboard to real data, and closed a security gap the tests uncovered.
- **70 tests** (Supertest API tests, frontend service tests and Playwright end-to-end) with GitHub Actions CI; deployed on Render as a single service with PostgreSQL.
- `TypeScript` · `React` · `Express` · `Prisma` · `PostgreSQL` · `Playwright` · `GitHub Actions`

### Stack

**AI & LLMs:** OpenAI · Anthropic · Gemini · Ollama · RAG · MCP · STT/TTS  
**Backend:** Python · Flask · Node.js · Express · Prisma · PostgreSQL  
**Frontend:** React · Vite · TypeScript · Tailwind CSS  
**Quality & DevOps:** pytest · GitHub Actions · Docker  
**Other:** Unity · C#

### Interests

Production AI agents, LLM evaluation and observability, AI-assisted test automation and data products. Open to roles and freelance projects: [get in touch](mailto:neyfred@gmail.com).

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

#### 🎙️ [Benchmark de servicios de voz para agentes conversacionales](https://github.com/jmnzcn/pf3312_lab_2)
Comparé **15 servicios** de STT, LLM y TTS (OpenAI, Anthropic, Gemini, Groq, Deepgram, Azure, AssemblyAI, ElevenLabs, Google) contra alternativas **100 % locales** (Ollama, faster-whisper, Piper). Medí latencia, precisión (WER, MOS), costo, privacidad, customización e integración, y el flujo completo **STT → LLM → TTS** en cuatro stacks.
- Datos crudos, audios de prueba con hash SHA-256 y scripts para regenerar tablas y gráficos sin volver a gastar créditos.
- `Python` · `Ollama` · `faster-whisper` · `Piper` · `pandas` · `pytest`

#### 🧪 [FlightBooking QA Copilot: microservicios + servidor MCP](https://github.com/jmnzcn/pf3866_pruebas_de_software_ney_laboratorio)
Sistema de reservas de vuelos con **3 microservicios Flask** (vuelos, reservas, usuario) documentados con Swagger/OpenAPI, y una suite de **pruebas automatizadas de API** que incluye casos generados con un enfoque **RAG** (ChromaDB).
- Un **servidor MCP** que funciona como "QA Copilot": revisa la salud de los servicios, invoca endpoints, ejecuta suites de `pytest` y lee código y documentación del repo.
- CI en **GitHub Actions** con reportes JUnit y recolección de métricas de pruebas.
- `Python` · `Flask` · `FastMCP` · `ChromaDB` · `pytest` · `Docker` · `GitHub Actions`

#### 🤖 [Efecto de la visibilidad de un agente virtual en la confianza del usuario](https://github.com/jmnzcn/pf3311_proyecto)
Experimento de investigación en **Unity** con tres condiciones: sin asistencia, chat con **Gemini**, y avatar 3D con voz **Azure TTS** y sincronía labial. Registra el desempeño y la confianza de cada participante (escala 1–7) para analizar cómo la presencia del agente cambia la confianza del usuario.
- Demos en video: [sin asistencia](https://youtu.be/upMpOpCAWgQ) · [solo chat](https://youtu.be/U_A_y0d-Hxg) · [avatar y voz](https://youtu.be/_h3h9BOnI18)
- `Unity` · `C#` · `Gemini API` · `Azure Speech` · `Python` (análisis)

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

#### 🎙️ [Speech services benchmark for conversational agents](https://github.com/jmnzcn/pf3312_lab_2)
Benchmarked **15 STT, LLM and TTS services** (OpenAI, Anthropic, Gemini, Groq, Deepgram, Azure, AssemblyAI, ElevenLabs, Google) against **fully local** alternatives (Ollama, faster-whisper, Piper). Measured latency, accuracy (WER, MOS), cost, privacy, customization and integration effort, plus the full **STT → LLM → TTS** pipeline across four stacks.
- Raw data, SHA-256-verified test audio and scripts to rebuild every table and chart without spending API credits.
- `Python` · `Ollama` · `faster-whisper` · `Piper` · `pandas` · `pytest`

#### 🧪 [FlightBooking QA Copilot: microservices + MCP server](https://github.com/jmnzcn/pf3866_pruebas_de_software_ney_laboratorio)
Flight booking system with **3 Flask microservices** (flights, bookings, user facade) documented with Swagger/OpenAPI, plus an **automated API test suite** that includes **RAG-generated** test cases (ChromaDB).
- An **MCP server** acting as a "QA Copilot": checks service health, calls endpoints, runs `pytest` suites and reads code and docs from the repo.
- **GitHub Actions** CI with JUnit reports and test metrics collection.
- `Python` · `Flask` · `FastMCP` · `ChromaDB` · `pytest` · `Docker` · `GitHub Actions`

#### 🤖 [How virtual agent visibility affects user trust](https://github.com/jmnzcn/pf3311_proyecto)
A **Unity** research experiment with three conditions: no assistance, **Gemini** chat, and a 3D avatar with **Azure TTS** voice and lip sync. It logs each participant's performance and trust (1–7 scale) to study how the agent's presence changes user trust.
- Video demos: [no assistance](https://youtu.be/upMpOpCAWgQ) · [chat only](https://youtu.be/U_A_y0d-Hxg) · [avatar + voice](https://youtu.be/_h3h9BOnI18)
- `Unity` · `C#` · `Gemini API` · `Azure Speech` · `Python` (analysis)

### Stack

**AI & LLMs:** OpenAI · Anthropic · Gemini · Ollama · RAG · MCP · STT/TTS  
**Backend:** Python · Flask · Node.js · Express · Prisma · PostgreSQL  
**Frontend:** React · Vite · TypeScript · Tailwind CSS  
**Quality & DevOps:** pytest · GitHub Actions · Docker  
**Other:** Unity · C#

### Interests

Production AI agents, LLM evaluation and observability, AI-assisted test automation and data products. Open to roles and freelance projects: [get in touch](mailto:neyfred@gmail.com).

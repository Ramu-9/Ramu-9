<div align="center">
  <img src="./assets/ramu-banner.svg" width="100%" alt="Ramu.exe: Backend systems, applied AI and real-time products" />
  <br/><br/>
  <a href="https://www.linkedin.com/in/r7mu"><img src="https://img.shields.io/badge/LET'S_CONNECT-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ramu7maddirala@gmail.com"><img src="https://img.shields.io/badge/SEND_A_SIGNAL-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Ramu-9?tab=repositories"><img src="https://img.shields.io/badge/OPEN_THE_LAB-Repositories-20232A?style=for-the-badge&logo=github&logoColor=white" /></a>
</div>

<br/>

<table>
<tr>
<td width="58%" valign="top">

### 👋 So, who is Ramu?

Computer Science undergrad at **BITS Pilani (2028)**. I like building software with moving parts: backend systems, AI-powered products, real-time pipelines, and the occasional bug that clearly has a personal grudge.

I usually start with a question, end up drawing boxes and arrows, and somehow there's a repository at the end.

**Currently interested in:** applied AI, backend engineering, agentic workflows, distributed systems and developer tools.

</td>
<td width="42%" valign="top">

### 🖥️ Current status

```text
BUILD MODE      : ON
BUG HUNTING     : ON
AI TRUST LEVEL  : "SHOW ME THE TEST"
COFFEE          : COMPILING...
DSA             : 1,600+ solved
LOCATION        : India
```

</td>
</tr>
</table>

> **My default rule:** AI can make a suggestion. Code, tests and evidence decide what ships.

---

## 🧪 The things I've brought to life

Not tutorial clones. Not 47 weather apps. Three projects where I got to wrestle with very different engineering problems.

<details open>
<summary><h3>🌉 SETU.ai — The real-time voice coordination experiment</h3></summary>

**A multilingual voice workflow where timing, context and reliability all matter.**

I wanted to explore what happens when a voice interface has to deal with interruptions, changing information and multiple services working together.

<div align="center">

`Browser Audio` → `VAD` → `Streaming STT` → `AI Reasoning` → `Deterministic Orchestration` → `Streaming TTS`

</div>

- 7-language voice workflow with streaming speech services
- React 19 + TypeScript frontend, Node.js WebSocket gateway, Python FastAPI/asyncio backend
- Silero VAD running through ONNX Runtime WebAssembly
- 1.5-second audio pre-roll, interruption handling and request deduplication
- Gemini structured reasoning with deterministic fallback paths
- PostgreSQL + PostGIS, provenance-aware facts and append-only audit events

**The part I enjoyed most:** making the AI useful without giving it unchecked control over critical decisions.

<p>
  <a href="https://github.com/Ramu-9/Sethu"><img src="https://img.shields.io/badge/READ_THE_CODE-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://ais-pre-3gbhjctjktnswx6fxkrs7c-123461625038.asia-east1.run.app"><img src="https://img.shields.io/badge/TRY_THE_PREVIEW-0B806B?style=for-the-badge&logo=googlecloud&logoColor=white" /></a>
</p>

<sub>Important: SETU.ai is a prototype, not connected to India's official 112 service. All fleet resources, assignments, routes and ETAs are simulated.</sub>

</details>

<details open>
<summary><h3>🛒 SmartKart — Shopping by intent, not SKU memorisation</h3></summary>

**Tell the store what you're trying to do. Let it help assemble the plan.**

SmartKart turns a natural-language goal and budget into an editable product bundle, then helps the user evaluate purchases before checkout.

<div align="center">

`Shopping Goal` → `AI Bundle Proposal` → `User Approval` → `Purchase Check` → `Secure Checkout`

</div>

- React 19, Node.js, Express 5, MongoDB and Mongoose
- Gemini structured outputs backed by a deterministic recommendation engine
- Product IDs, stock and business rules validated server-side
- Suggestions stay separate from the persisted cart until the user approves them
- Contextual cross-selling and discounts capped at 15%
- Razorpay workflow with server-side HMAC-SHA256 verification and replay protection

**The part I enjoyed most:** making the AI negotiate, recommend and assist without letting it rewrite the rules of the store.

<p>
  <a href="https://github.com/Ramu-9/SmartKart"><img src="https://img.shields.io/badge/READ_THE_CODE-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://smartkart-ai.vercel.app"><img src="https://img.shields.io/badge/OPEN_THE_STORE-0B806B?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

</details>

<details open>
<summary><h3>🏏 PitchIQ — Cricket, but make it probability</h3></summary>

**What if every match state could be explored through 10,000 possible futures?**

PitchIQ is a cricket analytics platform built around a Java simulation engine. It runs 10,000 Monte Carlo iterations per match state and turns the resulting numbers into contextual insights.

- Java 21 simulation engine, Spring Boot APIs and Spring Data JPA
- TreeMap / NavigableMap weighted sampling in O(log N)
- Match-data integration and CSV probability-calibration pipeline
- Gemini commentary grounded in deterministic simulation outputs

**The part I enjoyed most:** keeping the maths in charge and the AI in the commentary box.

<p>
  <a href="https://github.com/Ramu-9/PitchIQ"><img src="https://img.shields.io/badge/READ_THE_CODE-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://pitchiq-ai.vercel.app"><img src="https://img.shields.io/badge/WATCH_A_MATCH-0B806B?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

</details>

---

## 🧰 My workshop

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,python,js,ts,react,nodejs,spring,fastapi,postgres,mongodb,mysql,docker,git,github,linux" alt="Technology icons" />
</div>

| Area | Tools I have used |
|---|---|
| Languages | Java, Python, JavaScript, TypeScript, SQL |
| Backend | Spring Boot, Node.js, Express, FastAPI, REST APIs, WebSockets |
| Frontend | React, Vite, Tailwind CSS, Web Audio API |
| Data | PostgreSQL, PostGIS, MongoDB, MySQL |
| AI & systems | Gemini API, structured outputs, deterministic fallbacks, ONNX Runtime WebAssembly |
| Security & tooling | JWT, HMAC-SHA256, Git, Docker, Maven, Postman |

---

## 🧠 A few opinions from the bug battlefield

- A green response code is not proof the workflow succeeded.
- If the model says “done”, I still want the receipt.
- The most interesting bugs live between services. They enjoy the rent-free space.
- Good abstractions make change easier. Bad abstractions make simple changes feel like archaeology.
- I like AI-assisted development. I also like reading the code it writes.

---

<div align="center">

### Have a hard problem, a weird edge case, or something worth building?

**I'm listening.**

<a href="mailto:ramu7maddirala@gmail.com">ramu7maddirala@gmail.com</a> · <a href="https://www.linkedin.com/in/r7mu">LinkedIn</a>

<br/>

<sub>Made with curiosity, stubborn debugging, and an unreasonable number of README edits.</sub>

</div>

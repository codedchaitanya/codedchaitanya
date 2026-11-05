<p align="center">
  <img src="chaitanya.png" width="170" alt="Chaitanya Roy"/>
</p>

<h1 align="center">Chaitanya Roy</h1>

<p align="center">
  <b>Software Engineer · Backend & Distributed Systems · Applied AI</b><br/>
  Java · Spring Boot · Python · Microservices · Kafka · Redis · Docker · AWS
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/chaitanya-roy-a8b756257/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:chaitanyaroy2004@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/u/sam13299work/"><img src="https://img.shields.io/badge/LeetCode-1901_Knight-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://www.codechef.com/users/long_seren_98"><img src="https://img.shields.io/badge/CodeChef-1552-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/></a>
  <a href="https://codeforces.com/profile/vengeance_04"><img src="https://img.shields.io/badge/Codeforces-vengeance__04-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
</p>

---

## About me

I'm a backend engineer who likes systems that keep working when things go wrong: crashed workers, flaky networks, retried requests, money that has to reconcile to the rupee.

- **Software Development Engineer at Lenskart (Fintech)**, Bengaluru, Jan – Nov 2026: migrated a PHP monolith to Java 21 / Spring Boot microservices and built an automated GST reconciliation service.
- **B.Tech, Mathematics & Computing, Delhi Technological University (DCE)**, class of 2026.
- **IEEE author**: *A Hybrid QLoRA and LLM Framework for Indian Law*, 5th IEEE ICDCECE 2026.
- **Reliance Foundation Undergraduate Scholar**, selected among the top 5,000 students in India.

📍 New Delhi, India · open to relocate · **open to SDE-1 / Backend / Full-stack roles, available to join immediately**

---

## Professional experience

### Software Development Engineer — Lenskart (Fintech) · Jan 2026 – Nov 2026
- **Monolith to microservices:** led the end-to-end migration of a 350-file, 20,000-LOC PHP monolith to a Java 21 + Spring Boot + MySQL backend with a Next.js / React frontend, shipping **20+ CMS modules** as Docker, Kafka and Redis microservices.
- **GST reconciliation:** built an automated daily reconciliation service in Java 21 / Spring Boot that removed **₹14 lakh per cycle in commission errors** for the year.
- **AI audio analytics:** built a pipeline for in-store customer conversations on open-source models (Whisper, speaker diarization) that kept the conversation context and **cut Gemini API cost by 70%**.

### Software Engineer Intern — AlgoUniversity · May 2025 – Jul 2025
- Built **Roy's Code**, a full-stack online judge: sandboxed execution against hidden test suites with **sub-2 s verdicts**, deployed on AWS EC2 with an AI debugging agent. ([repo](https://github.com/codedchaitanya/AlgoDev))

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [Relay](https://github.com/codedchaitanya/Relay-Project)
**Crash-safe runtime for AI agents** · [live demo](https://relay-project-murex.vercel.app/)

Every model call and tool call goes to a write-ahead ledger in PostgreSQL. Kill a worker mid-run and another one takes over at the exact step, without paying for a model call twice or repeating a side effect.

- **196 / 196** runs killed mid-flight still finished, **0** duplicate writes
- Leases + fencing tokens, `SKIP LOCKED` claiming, idempotency keys
- **15.6×** throughput from 1 → 16 workers (1.18 → 18.4 runs/s)
- Retries with circuit breaker, dead-letter queue, Prometheus `/metrics`, CI on GitHub Actions

`Python` `FastAPI` `PostgreSQL` `Docker` `Gemini`

</td>
<td width="50%" valign="top">

### ⚖️ [ILLA — Indian Legal Litigation Agent](https://github.com/codedchaitanya/Legal-AI-agent)
**Published at IEEE ICDCECE 2026**

A legal assistant for Indian law: Qwen2.5-7B in 4-bit with **12 domain-specific QLoRA adapters**, a domain router, OCR + document indexing, a citation validator for BNS / BNSS / IPC / CrPC sections, and an argument generator.

- **68.6%** on BhashaBench-Legal, ahead of the 10× larger **LawMA-70B (60.0%)**
- Fine-tuned on **16,785** Indian legal Q&A samples
- Adapter swaps in under a millisecond on a single GPU

`Python` `PyTorch` `QLoRA / PEFT` `Legal-BERT` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧑‍⚖️ [Roy's Code — Online Judge](https://github.com/codedchaitanya/AlgoDev)
**Competitive-programming platform** · [demo video](https://drive.google.com/drive/folders/1wSndazeoIzb_UPJDNI1fZTUCWGoY-n-S)

Problems by topic and difficulty, code execution in isolated Docker sandboxes against hidden test cases, verdicts in under 2 seconds, leaderboard, and an AI agent that explains why a submission failed.

`Django REST` `PostgreSQL` `Docker` `AWS EC2`

</td>
<td width="50%" valign="top">

### 🎓 [YouEducation](https://github.com/codedchaitanya/YouEducation)
**AI learning platform**

Upload a syllabus and get an interactive mind map of the subject, with curated videos, AI-written notes, a custom video player with time-stamped transcripts, markdown notes and a contextual AI chat. Cut manual study planning by **~75%**; sub-2 s page loads on Vercel.

`Next.js` `TypeScript` `MongoDB` `Azure OpenAI` `NextAuth`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ [LiveKit Agents — open-source work](https://github.com/codedchaitanya/agents/tree/feature/interrupt-handler-chaitanya-roy)
**Real-time voice AI framework**

Context-aware interruption handling so a voice agent is not cut off by "hmm" / "okay" backchannels (**~60%** fewer false interruptions), and an STT-aware async grace period that fixes a VAD–STT race (**~40%** fewer race failures). Proposed upstream in [livekit/agents#4492](https://github.com/livekit/agents/pull/4492).

`Python` `asyncio` `Voice AI`

</td>
<td width="50%" valign="top">

### 🚨 [On-Call Incident Management](https://github.com/codedchaitanya/On-Call-Incident-Management-System)
**PagerDuty-style incident response** · [demo video](https://drive.google.com/file/d/1wERBxuXZ4gGOui4p5a-5uHGY21JoKDdm/view?usp=drivesdk)

On-call schedules, automatic routing of incidents to the responder on call, acknowledge / resolve lifecycle, timed escalation, and an MTTA / MTTR metrics dashboard. Built for correctness and clear edge-case handling.

`Django` `Django REST Framework` `SQLite`

</td>
</tr>
</table>

---

## More things I've built

| Project | What it does | Stack |
|---|---|---|
| [SurfaceGuard](https://github.com/codedchaitanya/SurfaceGuard-Multimodal-3D-Defect-Mapping) | 3D perception for construction robots: finds cracks and holes on walls from RGB-D data and gives their 3D position and size (voxel grid + RANSAC plane segmentation) | C++17, ROS 2, PCL, OpenCV, PyTorch |
| [Aura AI](https://github.com/codedchaitanya/Aura_AI) | Security gateway that screens inputs to an AI model for adversarial attacks before they reach it | Python |
| [Boostly](https://github.com/codedchaitanya/Chaitanya-Roy-2K22MC41) | Student recognition platform: send credits with a message, leaderboard, admin panel | Django |
| [Vehicle Detection & Counting](https://github.com/codedchaitanya/Vehicle_dectection_and_counting) | Detects, tracks and counts cars, bikes, buses and trucks crossing lines in traffic video | Python, YOLOv8 |
| [Eco-Track](https://github.com/codedchaitanya/Eco-Track) | ESG analytics: data cleaning, EDA and a dashboard for company ESG scores, resource use and industry comparison | Python, pandas, Plotly Dash |
| [E-commerce Website](https://github.com/codedchaitanya/Ecommerce-Website) | Full-stack store with sign-up, product pages and payments | Node.js, Express, MongoDB, EJS |
| [ArUco Pose Estimation](https://github.com/codedchaitanya/aruco-marker-detection-and-pose-estimation) | Camera calibration, ArUco marker detection and 6-DoF pose estimation | Python, OpenCV |
| [Image Mosaicing](https://github.com/codedchaitanya/uas-first-project) | Stitches overlapping images into one seamless panorama | Python, OpenCV |

---

## Tech stack

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=java,python,cpp,c,js,ts&perline=12" alt="Languages"/>
</p>

**Backend & frameworks**
<p>
  <img src="https://skillicons.dev/icons?i=spring,django,flask,fastapi,nodejs,express,react,nextjs,bootstrap&perline=12" alt="Frameworks"/>
</p>

**Data, messaging & cloud**
<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,kafka,docker,aws,azure,vercel,git,githubactions&perline=12" alt="Infra"/>
</p>

**AI / ML** — PyTorch, QLoRA / PEFT, YOLO, OpenCV, Whisper, speech diarization, LLM agents  
**Testing** — JUnit, Mockito, PyTest  
**Daily tools** — Claude Code, Cursor, GitHub Copilot

---

## Achievements

- 📄 **IEEE publication** — *A Hybrid QLoRA and LLM Framework for Indian Law* (ILLA), 5th IEEE ICDCECE 2026
- 🏅 **Reliance Foundation Undergraduate Scholar** — top 5,000 students nationwide
- 💻 **LeetCode 1901 (Knight)** · **CodeChef 1552**
- 🎤 Director of Logistics, DELTECH MUN · Head of Corporate, 60 fps (DTU)

---

<p align="center">
  <b>Hiring for backend, platform or applied-AI engineering?</b><br/>
  <a href="mailto:chaitanyaroy2004@gmail.com">chaitanyaroy2004@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/chaitanya-roy-a8b756257/">LinkedIn</a>
</p>

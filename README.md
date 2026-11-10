<h1 align="center">Hi, I'm Muhammad Huzaifa 👋</h1>
<p align="center">Software Engineer · Mobile, Full-Stack &amp; AI · Karachi, Pakistan</p>
<br>

### 👨‍💻 About Me

- 🧱 I build whole products: the mobile app, the backend and dashboards behind it, the AI features inside it, and the infrastructure that ships it.
- 📱 In 2026 I built **five mobile products** and released **four** of them to the App Store and Google Play, as sole or lead engineer on most.
- 🤖 At Rehani Soko I built **Hani**, an AI property concierge (app and backend), and ran the platform's **LLM layer** across Anthropic and OpenAI.
- 🧰 I care about the unglamorous half too: CI gates, test coverage, infrastructure as code, and release pipelines.
- 🎓 Computer & Information Systems Engineering, NED University. Two co-authored papers.

---

### 🚀 2026: 5 apps built, 4 live in the stores

| App | What it is | iOS | Android | Web |
|---|---|---|---|---|
| **Wash42** | Car-wash booking & membership | [Live](https://apps.apple.com/us/app/wash42/id6803226300) | [Live](https://play.google.com/store/apps/details?id=com.wash42.app) | [PWA live](https://brave-smoke-0e0c01010.6.azurestaticapps.net) |
| **HeadQuarters CRM** | Field-service CRM (sole engineer) | [Live](https://apps.apple.com/app/id6819401164) | In review | [Website](https://www.headquarterscrm.com) |
| **Dugan Psychiatry** | Mental-health care with video visits | In review | [Live](https://play.google.com/store/apps/details?id=com.duganpsychiatry.app) | [Website](https://duganpsychiatry.com/) |
| **Hani by Rehani** | AI property concierge (sole engineer) | [Live](https://apps.apple.com/app/id6830137760) | In review | [Website](https://www.rehanisoko.com/app) |
| **ProperTkt** | Maintenance tickets for landlords | In development | [Preview APK](https://expo.dev/artifacts/eas/EPoAdILqSzFw5Ch_cRjoZX5AWWK71vReFQS7CMUJGNo.apk) | [Website](https://www.propertkt.com) |

<sub>These are client and employer products, so their source code is private. Stack across them: React Native, Expo, Next.js, React, FastAPI, Django, NestJS, PostgreSQL, Redis, AWS, Azure, Stripe.</sub>

---

### 📌 Featured Work

**[self-healing-rag](https://github.com/huzaifa620/self-healing-rag)** · A RAG service that critiques its own answers, refuses to guess, and can't be merged if it regresses.

A LangGraph loop where a critic model grades every draft against the retrieved chunks and sends ungrounded ones back for a reformulated query. If it still can't ground the answer, it abstains instead of guessing. Every push runs 60 hand-verified golden pairs through a **cross-provider judge** (Claude grading GPT output), and GitHub Actions blocks the merge if the hallucination rate goes above 5%. There's an open PR on the repo sitting red on purpose, to prove the gate actually fires.

<sub>Current: 4.4% hallucination · 0% false answers on unanswerable questions · 100% valid citations · ~$0.0005/query</sub>

**🏆 3rd Prize, AI Track ($15,000), Solana Breakout Hackathon** · out of 8,300+ global submissions, for **Agent Arc**, a non-custodial AI trading terminal on Solana where I led the frontend.

<sub>
  <a href="https://medium.com/@huzaifa6201/building-agent-arc-a-trustless-ai-trading-terminal-on-solana-ff98c6f02b13">Build blog</a> ·
  <a href="https://blog.colosseum.com/announcing-the-winners-of-the-solana-breakout-hackathon/">Winners announcement</a> ·
  <a href="https://arena.colosseum.org/projects/explore/agent-arc">Project page</a>
</sub>

---

### ⚡ Tech Stack

- **Languages:** TypeScript, JavaScript, Python, SQL, C#
- **Mobile:** React Native, Expo (EAS Build, Submit, Update), Expo Router, offline sync, push notifications, WebRTC, App Store & Google Play releases
- **Frontend:** React, Next.js, Vue/Nuxt, Vite, Tailwind CSS, Redux Toolkit, TanStack Query, PWAs
- **Backend:** FastAPI, Django, NestJS, Node.js, Celery, REST/OpenAPI, Socket.IO
- **Data:** PostgreSQL, SQL Server, MongoDB, Redis
- **AI/LLM:** Anthropic & OpenAI APIs, multi-model routing, vision, structured output, RAG, LangChain, LangGraph, embeddings, LLM evals, Whisper
- **Cloud & DevOps:** AWS (CDK, EC2, S3, CloudFront, SES), Azure, Docker, GitHub Actions, GitLab CI, Vercel, Sentry
- **Testing:** pytest, Jest, Playwright, Maestro, coverage gates in CI

---

### 📄 Publications

- *An Integrated Approach to Robotic Object Grasping and Manipulation using 6D Pose Estimation* · [arXiv:2411.13205](https://arxiv.org/abs/2411.13205)
- *Smart Shelf Advertising using Real-Time Product Segmentation and Interaction on Low-Cost Edge Devices* · [DOI:10.13140/RG.2.2.34475.96800](https://doi.org/10.13140/RG.2.2.34475.96800)

---

### 🔗 Connect With Me

<p align="center">
  <a href="https://huzaifa620.github.io"><img src="https://img.icons8.com/bubbles/50/000000/domain.png" alt="Portfolio"/></a>
  <a href="mailto:huzaifa62012@gmail.com"><img src="https://img.icons8.com/bubbles/50/000000/gmail.png" alt="Gmail"/></a>
  <a href="https://github.com/huzaifa620"><img src="https://img.icons8.com/bubbles/50/000000/github.png" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/muhammad-huzaifa-2a3821249/"><img src="https://img.icons8.com/bubbles/50/000000/linkedin.png" alt="LinkedIn"/></a>
  <a href="https://medium.com/@huzaifa6201"><img src="https://img.icons8.com/?size=50&id=59813&format=png" alt="Medium"/></a>
</p>

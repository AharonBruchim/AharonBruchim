<div align="center">

<img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/hero.svg" width="100%" alt="Aharon Bruchim — Full-Stack Engineer" />

<br/>

<img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/typing.svg" alt="React · Node.js · TypeScript · MongoDB" />

<br/>
<br/>

<a href="mailto:aharonbruchim.dev@gmail.com"><img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/link-email.svg" height="46" alt="Email" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/aharonbruchim/"><img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/link-linkedin.svg" height="46" alt="LinkedIn" /></a>
&nbsp;
<a href="https://glianix.com"><img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/link-website.svg" height="46" alt="glianix.com" /></a>

</div>

---

## About

For a decade I studied Talmud twelve hours a day before I wrote a single line of code.
It turned out to be the best debugging training I could have asked for.

Today I'm a **Full-Stack Engineer** building production systems in an elite technology unit —
React and TypeScript on the front, Node.js, Express and MongoDB behind it, shipped end to end.

What sets me apart isn't the stack. It's that I take the problems that get handed back. More than
once I've cracked a challenge experienced teams had already given up on — by learning the thing
properly instead of working around it, and by connecting small, seemingly unrelated details into a
pattern nobody else saw.

**Next:** AI/LLM engineering — RAG, agents and model-based systems in production, on a strong
full-stack foundation.

---

<div align="center">

<img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/stack.svg" width="100%" alt="Tech stack — Frontend: React, TypeScript, JavaScript, Tailwind, MUI, HTML5, CSS3. Backend: Node.js, Express, REST API, Zod, JWT, OAuth2. State &amp; Data: Zustand, TanStack Query, React Router, MongoDB, Mongoose. Tools &amp; DevOps: Git, Docker, Vite, Linux, Nginx, RabbitMQ" />

</div>

---

## Featured Projects

### 🎓 Yesodot Eitanim · Nonprofit Platform for At-Risk Youth

🔒 *Private repository — client work, source not public.*

End-to-end development: **React 19 + Vite + Tailwind** (Frontend), **Node/TypeScript + Express + MongoDB**
(Backend). Secure video LMS (signed-token playback, per-user moving watermark, progress tracking),
online donations via payment gateways, courses & certificates, full i18n (Hebrew/English, RTL), and
WCAG AA accessibility compliance (Standard 5568).

> **Result:** A cost-optimized, multi-provider media architecture that keeps the nonprofit at near-zero cost.

### 🔐 Signet · Identity Provider / OAuth2 Auth Server

🔒 *Private repository — source not public.*

Built from scratch a self-hostable central authentication server in **TypeScript, Express, MongoDB**:
Google OAuth2 with PKCE, JWT over a JWKS endpoint with encrypted auto-rotating keys, refresh-token
rotation with reuse detection, RBAC, session management, NIST 800-63B password policy, and a full
audit log — at **100% test coverage (800+ tests)**.

> **Result:** Deployed to production, serving real applications as a central auth service.

---

## Open Source

Everything below is public — clone it, read it, run it.

### AI / LLM

| Repo | What it is |
|---|---|
| [**codegen**](https://github.com/AharonBruchim/codegen) | A fully-local autonomous coding agent on Ollama. One engine behind a CLI, a browser GUI, a VS Code extension and a Telegram bot — CPU-friendly, no API keys |
| [**docrag**](https://github.com/AharonBruchim/docrag) | Layered local RAG for Hebrew/English documents: classify → extract → SQL *or* hybrid vector search, behind a router. Offline, stdlib + numpy + SQLite |
| [**rag-financebench**](https://github.com/AharonBruchim/rag-financebench) | A RAG pipeline measured against the FinanceBench dataset across several evaluation dimensions |
| [**skills**](https://github.com/AharonBruchim/skills) | Claude Code Skills — modular, auto-loaded instruction units for LangGraph agents, MCP integration and knowledge-graph memory |

### Services & Infrastructure

| Repo | What it is |
|---|---|
| [**template-service**](https://github.com/AharonBruchim/template-service) | Production-ready Node.js service template — Express, strict TypeScript, MongoDB, Zod, Winston, Helmet, Docker, Vitest |
| [**Website-Monitor**](https://github.com/AharonBruchim/Website-Monitor) | Uptime monitor that polls a list of sites and records only status *transitions*, with a React dashboard |
| [**minio**](https://github.com/AharonBruchim/minio) | S3-compatible file storage — React frontend, Express API, MinIO and MongoDB, wired up with Docker Compose |
| [**bun-template**](https://github.com/AharonBruchim/bun-template) | Microservice template on the Bun runtime: Hono, tRPC, MongoDB, Zod, Pino |

---

## What I'm Working On

- 🔍 **Retrieval** — taking [`docrag`](https://github.com/AharonBruchim/docrag) past brute-force
  cosine: ANN indexing and a reranker pass on top of the hybrid dense⊕BM25 layer
- 🤖 **Agents** — extending [`codegen`](https://github.com/AharonBruchim/codegen) toward
  multi-step planning and safer tool execution, still fully local
- 📊 **Evaluation** — measuring RAG quality against standard benchmarks
  ([`rag-financebench`](https://github.com/AharonBruchim/rag-financebench)) instead of eyeballing answers
- ☁️ **Production** — moving model-based systems off a local Ollama box and into deployed services

---

## Contributions

<div align="center">

<img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/output/snake.svg" alt="Contribution snake" width="100%" />

</div>

---

<div align="center">

<img src="https://raw.githubusercontent.com/AharonBruchim/AharonBruchim/main/assets/footer.svg" width="100%" alt="" />

</div>

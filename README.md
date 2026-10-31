<a href="https://gitroll.io/profile/uNcllNgZIyAOKrnUm43AumtTuJ6w1"><img src="https://gitroll.io/api/badges/profiles/v1/uNcllNgZIyAOKrnUm43AumtTuJ6w1?theme=darkEmerald" alt="GitRoll Profile" /></a>

# abhishek sharma

i'm an **associate forward deployed engineer** at **[Wednesday Solutions](https://www.wednesday.is/)** in Pune. i own client problems from end to end: the analytics, the billing, who gets access to what, and the releases that ship it. i'm full-stack because the problems are. the job started with Spring Boot, then grew into React and Postgres, Python for agents, and Terraform when a client needed AWS from nothing.

## what i run right now

**an AI video platform for a US client**: 170+ paying customers, ~$200K MRR. i was brought in to cover a month of leave and i'm still running it.

- **analytics**: i built the module alone, from scratch. it's a time series over five social networks, recorded on a schedule because the provider only reports lifetime counters.
- **billing**: i own Stripe for the whole platform. i rebuilt pricing into modular plans in 8 days, and revenue from existing customers rose 35% afterwards. i also built a sales checkout: 71% of quoted prospects paid, at a median of 12 minutes from quote to payment.
- **releases**: i promote to main and write the notes the founders read. 42 production releases since june, and 68 customer fixes in four months.
- **the boring wins**: 712 type errors down to zero, feature-PR CI from 48 minutes to under 5, and frozen render frames from 23.42% to 0.00%.

**a grading platform for a US EdTech client**, integrated with Canvas and Moodle. Java 21 on Spring Boot with 105 endpoints, on ECS Fargate and SQS. i provisioned it alone in Terraform: 121 resources across 3 environments. self-hosted Canvas has no live event stream, so i built polling over SQS that stands in for one. i load tested 100 simultaneous graders: p95 1.82s, zero 5xx.

**an autonomous content engine**: 26 agents on LangGraph and FastAPI. it picks topics from live search console data, writes, runs each article through anti-AI writing checks, pauses on Postgres checkpoints for human review, and publishes as a GitHub PR.

## what i build on my own

**[Polaris](https://github.com/abhisheksharm-3/polaris)** is the one that changed how i work. it's an SDLC platform for Claude Code: 27 flows, 29 agents, a quality gate that blocks its own author, and memory that keeps refutations, not only conclusions. a phase counts as done only when its artifact is on disk. i built it because four jobs in the same hours is an architecture problem, not a time-management one.

**[ProjectSleeve](https://projectsleeve.vercel.app)** keeps free-tier backends awake. Supabase pauses after a week of quiet and Render sleeps after fifteen minutes, and each platform counts activity differently, so it checks six of them the way they count: a `keepalive()` function inside Postgres, a heartbeat row, a real Atlas ping, a timed visit. pg_cron runs the pinger every minute through Deno Edge Functions, an opt-in restorer brings back a project that paused anyway, and public status pages show 90 days of uptime. built alone in three weeks.

**[Flockr](https://github.com/abhisheksharm-3/flockr)**: household chores, shopping, and shared expenses in Kotlin and Jetpack Compose on Supabase, 22 releases to v2.0.0. before v2 i found 22 database functions with no membership check and locked every one down.

**hands-free voice for Off Grid**, Wednesday's offline AI app: a one-week prototype with six swappable on-device TTS engines, sentence-by-sentence synthesis, and barge-in on hardware echo cancellation. the voice mode that shipped drew on it.

## before wednesday

**[Credify](https://verifiedbycredify.vercel.app/)** won the Network18 track at Google's Gen AI Exchange Hackathon. it detects media tampering and tracks provenance, with Neo4j holding the graph. i led a team of three and wrote 240 of the 361 commits. still live.

**[Inquora](https://inquora.vercel.app/)** lets you chat with any file: PDFs, images, YouTube videos. built on LangChain, Pinecone, and Gemini.

**[QuickGist](https://quickgist.vercel.app/)** is code sharing in Go and React.

also public: [tensa](https://github.com/abhisheksharm-3/tensa) (FastAPI + ARQ media toolkit with SSE progress), [gpt-unloader](https://github.com/abhisheksharm-3/gpt-unloader) (virtualizes the DOM so long ChatGPT threads stop dying), [resummarize](https://github.com/abhisheksharm-3/resummarize) (pgvector notes), [radar](https://github.com/abhisheksharm-3/radar) (live flight tracking), [lexalyze](https://github.com/abhisheksharm-3/lexalyze) (legal doc analysis on SvelteKit + FastAPI).

## stack

**languages**: TypeScript, Python, Java, Kotlin, Go, SQL

**web**: React, Next.js, SvelteKit, Tailwind, Node.js

**backend**: Spring Boot, FastAPI, PostgreSQL, Supabase, Stripe, MongoDB, Neo4j

**ai**: LangGraph, LiteLLM, LangChain, pgvector, Claude API

**infra**: AWS (ECS, SQS, RDS, Cognito), Terraform, Docker, GCP, Vercel

**mobile**: Jetpack Compose, React Native

---

<p align="center">
  <a href="https://abhisheksan.com/">abhisheksan.com</a> &nbsp;·&nbsp;
  <a href="https://abhisheksan.com/resume">resume</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/abhisheksan/">linkedin</a> &nbsp;·&nbsp;
  <a href="https://x.com/iabhisheksan">x</a>
</p>


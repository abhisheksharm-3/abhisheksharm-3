<a href="https://gitroll.io/profile/uNcllNgZIyAOKrnUm43AumtTuJ6w1"><img src="https://gitroll.io/api/badges/profiles/v1/uNcllNgZIyAOKrnUm43AumtTuJ6w1?theme=darkEmerald" alt="GitRoll Profile" /></a>

# abhishek sharma

i'm a **forward deployed engineer** at **[Wednesday Solutions](https://www.wednesday.is/)** in Pune, which mostly means i own a client problem end to end: discovery, architecture, the spec, the code, the deploy, and the call where someone asks why it costs that much. full-stack by necessity. the job started with Spring Boot, grew into React/Next.js, pulled in Python for an AI pipeline, then Terraform when we needed to rebuild the whole AWS stack from scratch. picking up tools because the problem requires them.

## what i'm shipping

**[Polaris](https://github.com/abhisheksharm-3/polaris)** is mine, and the one that changed how i work. an all-in-one SDLC platform for Claude Code: 27 agents, 32 commands, declared flows, a quality gate that blocks its own author, and memory that keeps refutations instead of just conclusions. a phase is done only when its artifact is on disk and the hash matches. built it because four jobs in the same hours is an architecture problem, not a time-management one.

**an autonomous SEO content pipeline** for B2B SaaS. LangGraph for orchestration, LiteLLM for model routing, pgvector for retrieval. picks topics from live GSC signals, writes, validates each article against anti-AI writing heuristics, then opens a GitHub PR. no human checkpoint. about $1 per article in production. every article is a tracked experiment: predicted ranking outcome, 7-day validation window, 30-day outcome window. the system updates future topic selection based on what actually ranked.

the validator runs anti-AI checks on output before anything publishes. it rejected my first draft. humbling.

**a multi-tenant LMS grading platform** for a client, integrated with Canvas and Moodle. Java 21 on Spring Boot, ECS Fargate, SQS, full AWS stack on Terraform. self-hosted Canvas has no live event streaming; it depends on Kinesis, which most self-hosted setups don't have. built a polling architecture over SQS that simulates it. load tested at 100+ concurrent users and 15,000 monthly submissions. it held up.

**an on-device offline voice stack**: TTS and the full voice loop, with hardware acoustic echo cancellation. benchmarked Kokoro vs Piper vs native Android TTS. Piper won at 2 seconds. Kokoro crashed the app with hardware acceleration on.

**[Flockr](https://github.com/abhisheksharm-3/flockr)** is a household expense app in Kotlin/Jetpack Compose on Supabase. the existing options are embarrassing.

## before wednesday

**[Credify](https://verifiedbycredify.vercel.app/)** won the Network18 track at Google's Gen AI Exchange Hackathon. full media attribution chain: metadata extraction, watermarking, verification API, Neo4j for the provenance graph. led a team of four. still live.

**[Inquora](https://inquora.vercel.app/)** lets you chat with any file: PDFs, images, YouTube videos. wired LangChain, Pinecone, and Gemini together without setting anything on fire.

**[QuickGist](https://quickgist.vercel.app/)** is code-sharing in Go + React because pasting into Slack was making me sad. my friends actually use it. that's the only metric i care about.

also public and occasionally useful: [tensa](https://github.com/abhisheksharm-3/tensa) (FastAPI + ARQ media toolkit with SSE progress), [gpt-unloader](https://github.com/abhisheksharm-3/gpt-unloader) (virtualizes the DOM so long ChatGPT threads stop dying), [resummarize](https://github.com/abhisheksharm-3/resummarize) (pgvector notes), [radar](https://github.com/abhisheksharm-3/radar) (live flight tracking), [lexalyze](https://github.com/abhisheksharm-3/lexalyze) (legal doc analysis on SvelteKit + FastAPI).

## stack

**languages** — TypeScript, Python, Java, Kotlin, Go, SQL

**web** — React, Next.js, SvelteKit, Tailwind, Node.js

**backend** — Spring Boot, FastAPI, PostgreSQL, MongoDB, Supabase, Neo4j

**ai** — LangGraph, LiteLLM, LangChain, pgvector, Claude API

**infra** — AWS (ECS, SQS, RDS, Cognito), Terraform, Docker, GCP, Vercel

**mobile** — Jetpack Compose, React Native

## true things

- ran a 44-finding security audit on a production database. found things i can't unsee.
- terraformed a whole dev environment into the void. rebuilt it from scratch. on purpose. it worked.
- accidentally became the "resume guy" with [GetResume](https://getresumes.vercel.app). now i know more about ATS filters than any developer should.
- debugging process: write `console.log()`, stare at the screen, question my life choices.
- diet: black coffee and compiler errors.

---

<p align="center">
  <a href="https://www.linkedin.com/in/abhisheksan/">linkedin</a> &nbsp;·&nbsp;
  <a href="https://abhisheksan.com/">abhisheksan.com</a> &nbsp;·&nbsp;
  <a href="https://x.com/iabhisheksan">x</a>
</p>

<p align="center">
  <em>writing confusing code so AI stays confused. if it can't understand, i win.</em>
</p>

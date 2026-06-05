<a href="https://gitroll.io/profile/uNcllNgZIyAOKrnUm43AumtTuJ6w1" target="_blank"><img src="https://gitroll.io/api/badges/profiles/v1/uNcllNgZIyAOKrnUm43AumtTuJ6w1?theme=darkEmerald" alt="GitRoll Profile Badge"/></a>

# abhishek sharma

> building software like IKEA furniture: confusing docs, existential crises, but somehow it works.

i'm an SDE at **[Wednesday Solutions](https://www.wednesday.is/)** in Pune. full-stack by necessity. the job started with Spring Boot, grew into React/Next.js, pulled in Python for an AI pipeline, then Terraform when we needed to rebuild the whole AWS stack from scratch. picking up tools because the problem requires them. the company recently moved engineers toward owning the full problem: architecture, proposals, roadmaps, delivery. 

---

## what i'm shipping

**Skald** is the one i'm most proud of right now. autonomous SEO content pipeline for B2B SaaS. LangGraph for orchestration, LiteLLM for model routing, pgvector for retrieval. picks topics from live GSC signals, writes, validates each article against anti-AI writing heuristics, then opens a GitHub PR. no human checkpoint. about $1 per article in production. every article is a tracked experiment: predicted ranking outcome, 7-day validation window, 30-day outcome window. the system updates future topic selection based on what actually ranked.

the validator runs anti-AI checks on output before anything publishes. it rejected my first draft. humbling.

**Upthink QMS** is a multi-tenant LMS grading platform integrated with Canvas and Moodle. Java 21 on Spring Boot, ECS Fargate, SQS, full AWS stack on Terraform. self-hosted Canvas has no live event streaming; it depends on Kinesis, which most self-hosted setups don't have. built a polling architecture over SQS that simulates it. load tested at 100+ concurrent users and 15,000 monthly submissions. it held up.

**[Flockr](https://github.com/abhisheksharm-3/flockr)** is a household management app in Kotlin/Jetpack Compose. the existing options are embarrassing.

---

## before wednesday

**[Credify](https://verifiedbycredify.vercel.app/)** won a hackathon. full media attribution chain: metadata extraction, watermarking, verification API. led a team of four. still live.

**[Inquora](https://inquora.vercel.app/)** lets you chat with any file: PDFs, images, YouTube videos. wired LangChain, Pinecone, and Gemini together without setting anything on fire.

**[QuickGist](https://quickgist.vercel.app/)** is code-sharing in Go + React because pasting into Slack was making me sad. my friends actually use it. that's the only metric i care about.

---

## stack

`TypeScript` `JavaScript` `Python` `Java` `Kotlin` `Go` `SQL`

`React` `Next.js` `SvelteKit` `Tailwind` `Spring Boot` `FastAPI` `Node.js`

`LangGraph` `LiteLLM` `LangChain` `pgvector` `Claude API`

`PostgreSQL` `MongoDB` `MySQL` `Supabase` `Neo4j`

`AWS (ECS · SQS · RDS · Cognito)` `Terraform` `Docker` `GCP` `Vercel`

`Jetpack Compose` `React Native`

---

## true things

- built an autonomous content pipeline that validates against anti-AI writing heuristics. it rejected my first draft.
- ran a 44-finding security audit on a production database. found things i can't unsee.
- terraformed a whole dev environment into the void. rebuilt it from scratch. on purpose. it worked.
- benchmarked Kokoro vs Piper vs native Android TTS. Piper won at 2 seconds. Kokoro crashed the app with hardware acceleration on.
- passed probation. zero corrective feedback. not unrelated to the four points above.
- accidentally became the "resume guy" with [GetResume](https://getresumes.vercel.app). now i know more about ATS filters than any developer should.
- debugging process: write `console.log()`, stare at the screen, question my life choices.
- diet: black coffee and compiler errors.

---

<p align="center">
  <a href="https://www.linkedin.com/in/abhisheksan/">linkedin</a> &nbsp;·&nbsp;
  <a href="https://abhisheksan.com/">abhisheksan.com</a> &nbsp;·&nbsp;
  <a href="https://x.com/iabhisheksan">x</a>
</p>

---

*writing confusing code so AI stays confused. if it can't understand, i win.*

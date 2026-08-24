# Batıkan Akdeniz

**Final-year Software Engineering student.**

[LinkedIn](https://www.linkedin.com/in/batikanakdeniz/) · batikanakdeniz@hotmail.com

<details open>
<summary><h2>Projects</h2></summary>

<details>
<summary><b>Hotel Booking System</b> — Microservices with an LLM booking agent</summary>
<br>

Seven FastAPI services, one of them the gateway and one an AI agent on Groq's Llama 3.3 70B
that books through the same public API a browser would use. Bookings take a row lock across
the date range and publish to RabbitMQ only after the commit.

`Python` `FastAPI` `React` `Groq Llama 3.3 70B` `PostgreSQL` `MongoDB` `Redis` `RabbitMQ` `Docker`

[Repository](https://github.com/batikanakdenizz/Hotel-Booking-System) · [Live demo](https://hotel-booking-system-psi-beryl.vercel.app)

</details>
<details>
<summary><b>RAG Concepts Explainer</b> — Offline RAG chatbot on Foundry Local</summary>
<br>

A local, offline document Q&A assistant that teaches beginners how RAG and on-device AI work —
using the RAG pattern itself to explain it. Retrieves grounded passages from a curated knowledge
base, embeds queries with `qwen3-embedding-0.6b`, ranks by cosine similarity, and streams answers
from `qwen2.5-0.5b` — entirely on-device with zero network calls at inference time. CLI and
Streamlit UI, with a similarity-threshold refusal gate and a recorded evaluation suite.

Built as part of a Microsoft summer internship program.

`Python` `Microsoft Foundry Local` `Streamlit` `SQLite` `RAG` `Embeddings` `pytest`

[Repository](https://github.com/batikanakdenizz/rag-concepts-explainer)

</details>
<details>
<summary><b>AI Flight Agent</b> — Conversational booking over MCP</summary>
<br>

Searches flights, books tickets and checks passengers in through conversation. A local
`qwen2.5:7b` picks the tool, MCP carries the call over stdio to `query_flights` /
`buy_ticket` / `check_in`, and those drive the .NET API below. 50 tests, CI across three
Python versions.

`Python` `Ollama` `MCP` `FastAPI` `React` `pytest`

[Repository](https://github.com/batikanakdenizz/ai-flight-agent)

</details>
<details>
<summary><b>Airline Ticketing System</b> — Layered .NET API behind a gateway</summary>
<br>

The .NET backend the agent above drives. Layered API / Application / Domain / Infrastructure,
an Ocelot gateway enforcing JWT auth and per-client rate limits, k6 scripts to prove it holds
under concurrency.

`C#` `.NET 8` `EF Core` `PostgreSQL` `Ocelot` `JWT` `k6`

[Repository](https://github.com/batikanakdenizz/AirlineTicketingSystem)

</details>
<details>
<summary><b>LinePulse Report Builder</b> — Self-service reporting, built twice</summary>
<br>

Lets factory users design their own reports — KPIs, breakdown dimensions, cascading
Line/Machine/Product filters — then drill into a live chart and table. Built twice, on PrimeVue
and on DevExtreme, over one report engine that is byte-identical in both repositories.

`Vue 3` `PrimeVue` `DevExtreme` `Chart.js` `Vite` `Vitest`

[PrimeVue build](https://github.com/batikanakdenizz/CTS-DynamicReports-PrimeVue) · [live](https://batikanakdenizz.github.io/CTS-DynamicReports-PrimeVue/)
&nbsp;&nbsp;·&nbsp;&nbsp;
[DevExtreme build](https://github.com/batikanakdenizz/CTS-DynamicReports-DevExtreme) · [live](https://batikanakdenizz.github.io/CTS-DynamicReports-DevExtreme/)

</details>
<details>
<summary><b>Senior Project</b> — Capstone platform, team of ten</summary>
<br>

Spring Boot backend for a capstone-management platform: rubric grading, sprint tracking, and a
Jira integration that matches issue keys against merged pull requests. My part: 11 merged pull
requests and 11 code reviews.

`Java` `Spring Boot` `MySQL` `Jira API` `Postman` `JUnit`

[Repository](https://github.com/SE3318-Spring-2025-2026/senior-app-6)

</details>
<details>
<summary><b>Secretless Azure Deployment</b> — No credentials stored anywhere</summary>
<br>

Reads its database credentials from Key Vault through a Managed Identity, so no secret sits in
the image, the app settings, or the repository.

`Python` `Flask` `Azure Key Vault` `Managed Identity` `Docker` `GitHub Actions`

[Repository](https://github.com/batikanakdenizz/azure-flask-keyvault-postgres)

</details>
<details>
<summary><b>Akakçe Test Automation</b> — 42 tests against a live site</summary>
<br>

42 JUnit 5 tests driving a live e-commerce site: login, typo-tolerant search, price and brand
filters, watchlist follow/unfollow, sort order and currency format.

`Java` `Selenium` `JUnit 5`

[Repository](https://github.com/batikanakdenizz/Akakce-Test-Automation)

</details>
<details>
<summary><b>Weather MCP Server</b> — MCP tool server in TypeScript</summary>
<br>

Model Context Protocol server on the official TypeScript SDK, exposing a `get-weather` tool
with Zod-validated input over stdio.

`TypeScript` `MCP SDK` `Zod` `Node.js`

[Repository](https://github.com/batikanakdenizz/getWeather-MCPServer)

</details>

</details>

<details open>
<summary><h2>What I work with</h2></summary>

<details>
<summary><b>Languages</b></summary>
<br>

[![](https://skillicons.dev/icons?i=py,cs,java,js,ts)](https://skillicons.dev)

Python · C# · Java · JavaScript · TypeScript

</details>
<details>
<summary><b>AI &amp; agents</b></summary>
<br>

[![](https://skillicons.dev/icons?i=py,fastapi,ts)](https://skillicons.dev)

Python · FastAPI · TypeScript · MCP · Ollama · Groq · Function calling · Jupyter
Python · FastAPI · TypeScript · MCP · Ollama · Groq · Foundry Local · RAG · Embeddings · Function calling · Jupyter

</details>
<details>
<summary><b>Backend &amp; data</b></summary>
<br>

[![](https://skillicons.dev/icons?i=fastapi,flask,spring,dotnet,postgres,mysql,sqlite,mongodb,redis,rabbitmq)](https://skillicons.dev)

FastAPI · Flask · Spring Boot · .NET 8 · PostgreSQL · MySQL · SQLite · MongoDB · Redis · RabbitMQ · SQLAlchemy · Alembic · NumPy · Swagger / OpenAPI

</details>
<details>
<summary><b>Cloud &amp; DevOps</b></summary>
<br>

[![](https://skillicons.dev/icons?i=azure,docker,githubactions,nginx,linux,bash,firebase,supabase,vercel)](https://skillicons.dev)

Azure · Docker · GitHub Actions · Nginx · Linux · Bash · Firebase · Supabase · Vercel · Render

</details>
<details>
<summary><b>Frontend</b></summary>
<br>

[![](https://skillicons.dev/icons?i=react,vue,vite,tailwind,streamlit)](https://skillicons.dev)

React · Vue 3 · Vite · Tailwind CSS · TanStack Query · Zod
React · Vue 3 · Vite · Streamlit · Tailwind CSS · TanStack Query · Zod

</details>
<details>
<summary><b>Testing &amp; ways of working</b></summary>
<br>

[![](https://skillicons.dev/icons?i=selenium,postman,maven,git)](https://skillicons.dev)

pytest · JUnit 5 · Selenium · k6 · Postman · Jira · Scrum · Conventional Commits

</details>

</details>

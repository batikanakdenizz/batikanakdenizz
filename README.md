# Batıkan Akdeniz

**Final-year Software Engineering student.**

[LinkedIn](https://www.linkedin.com/in/batikanakdeniz/) · batikanakdeniz@hotmail.com

<details>
<summary><b>What I work with</b></summary>

**Languages**

[![](https://skillicons.dev/icons?i=py,cs,java,js,ts)](https://skillicons.dev)

Python · C# · Java · JavaScript · TypeScript

---

**AI & agents**

[![](https://skillicons.dev/icons?i=py,fastapi,ts)](https://skillicons.dev)

Python · FastAPI · TypeScript · MCP · Ollama · Groq · Function calling · Jupyter

---

**Backend & data**

[![](https://skillicons.dev/icons?i=fastapi,flask,spring,dotnet,postgres,mysql,sqlite,mongodb,redis,rabbitmq)](https://skillicons.dev)

FastAPI · Flask · Spring Boot · .NET 8 · PostgreSQL · MySQL · SQLite · MongoDB · Redis · RabbitMQ · SQLAlchemy · Alembic · Swagger / OpenAPI

---

**Cloud & DevOps**

[![](https://skillicons.dev/icons?i=azure,docker,githubactions,nginx,linux,bash,firebase,supabase,vercel)](https://skillicons.dev)

Azure · Docker · GitHub Actions · Nginx · Linux · Bash · Firebase · Supabase · Vercel · Render

---

**Frontend**

[![](https://skillicons.dev/icons?i=react,vue,vite,tailwind)](https://skillicons.dev)

React · Vue 3 · Vite · Tailwind CSS · TanStack Query · Zod

---

**Testing & ways of working**

[![](https://skillicons.dev/icons?i=selenium,postman,maven,git)](https://skillicons.dev)

pytest · JUnit 5 · Selenium · k6 · Postman · Jira · Scrum · Conventional Commits

</details>

<details>
<summary><b>Projects</b></summary>

| Project | What it does | Stack |
|---|---|---|
| **[Hotel Booking System](https://github.com/batikanakdenizz/Hotel-Booking-System)** · [live](https://hotel-booking-system-psi-beryl.vercel.app) | Seven FastAPI services, one of them the gateway and one an AI agent on Groq's Llama 3.3 70B that books through the same public API a browser would use. Bookings take a row lock across the date range and publish to RabbitMQ only after the commit | FastAPI · Groq · Postgres · Mongo · Redis · RabbitMQ |
| **[AI Flight Agent](https://github.com/batikanakdenizz/ai-flight-agent)** | Searches flights, books tickets and checks passengers in through conversation. A local `qwen2.5:7b` picks the tool, MCP carries the call over stdio to `query_flights` / `buy_ticket` / `check_in`, and those drive the .NET API below. 50 tests, CI across three Python versions | Ollama · MCP · FastAPI · React |
| **[Airline Ticketing System](https://github.com/batikanakdenizz/AirlineTicketingSystem)** | The .NET backend the agent above drives. Layered API / Application / Domain / Infrastructure, an Ocelot gateway enforcing JWT auth and per-client rate limits, k6 scripts to prove it holds under concurrency | .NET 8 · EF Core · PostgreSQL · Ocelot |
| **[LinePulse Report Builder](https://github.com/batikanakdenizz/CTS-DynamicReports-PrimeVue)** · [live](https://batikanakdenizz.github.io/CTS-DynamicReports-PrimeVue/) | Lets factory users design their own reports — KPIs, breakdown dimensions, cascading Line/Machine/Product filters — then drill into a live chart and table. Built [twice](https://github.com/batikanakdenizz/CTS-DynamicReports-DevExtreme), PrimeVue and DevExtreme, over one report engine that is byte-identical in both repos | Vue 3 · PrimeVue / DevExtreme · Chart.js |
| **[Senior project — team backend](https://github.com/SE3318-Spring-2025-2026/senior-app-6)** | Spring Boot backend for a capstone-management platform: rubric grading, sprint tracking, and a Jira integration that matches issue keys against merged pull requests. My part: 11 merged PRs and 11 code reviews in a ten-person team | Spring Boot · MySQL · Jira API · Postman |
| **[azure-flask-keyvault-postgres](https://github.com/batikanakdenizz/azure-flask-keyvault-postgres)** | Reads its database credentials from Key Vault through a Managed Identity, so no secret sits in the image, the app settings, or the repo | Flask · Azure · Docker |
| **[Akakçe Test Automation](https://github.com/batikanakdenizz/Akakce-Test-Automation)** | 42 JUnit 5 tests driving a live e-commerce site: login, typo-tolerant search, price and brand filters, watchlist, sort order | Java · Selenium · JUnit 5 |
| **[Weather MCP Server](https://github.com/batikanakdenizz/getWeather-MCPServer)** | Model Context Protocol server on the official TypeScript SDK, with Zod-validated tool schemas over stdio | TypeScript · MCP SDK |

</details>

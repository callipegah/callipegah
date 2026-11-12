<p align="center">
  <img src="assets/hero.svg" alt="pegah davari — backend & agentic systems, learning AI in public" width="100%">
</p>

<p align="center">
  <a href="https://linkedin.com/in/pegahdavari"><img src="https://img.shields.io/badge/LinkedIn-say_hi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=05060a" alt="LinkedIn"></a>
  <a href="https://relokitjobs.com"><img src="https://img.shields.io/badge/Relokit-live-a3e635?style=for-the-badge&logo=rocket&logoColor=a3e635&labelColor=05060a" alt="Relokit"></a>
  <a href="https://github.com/callipegah/ai-content-system"><img src="https://img.shields.io/badge/learning_AI-in_public-22d3ee?style=for-the-badge&logo=claude&logoColor=22d3ee&labelColor=05060a" alt="Learning AI in public"></a>
  <img src="https://komarev.com/ghpvc/?username=callipegah&style=for-the-badge&color=a78bfa&label=visitors" alt="profile views">
</p>

```yaml
name:        Pegah Davari
based_in:    Tehran 🇮🇷  →  wherever the next good problem is
day_job:     building a production LLM analytics agent @ Snapp
side_quest:  Relokit, jobs abroad with visa sponsorship, in Persian
superpower:  doing something twice by hand, then turning it into a tool
rule_no_1:   if it can be deterministic, don't ask an LLM to do it
fuel:        curiosity + a dangerously long Watch Later list
```

## 🛠️ Now building

<p align="center">
  <a href="https://relokitjobs.com"><img src="assets/card-relokit.svg" width="49%" alt="Relokit: live, iterating weekly"></a>
  <a href="#-how-i-build-agents"><img src="assets/card-agent.svg" width="49%" alt="Agentic analytics engine: in production"></a>
  <a href="https://github.com/callipegah/youtube-digest"><img src="assets/card-youtube-digest.svg" width="49%" alt="youtube-digest: just shipped"></a>
  <a href="https://github.com/callipegah/ai-content-system"><img src="assets/card-ai-content-system.svg" width="49%" alt="ai-content-system: ongoing"></a>
  <a href="https://github.com/callipegah/scout"><img src="assets/card-scout.svg" width="49%" alt="Scout: LIVE, planner/explainer v2"></a>
  <img src="assets/card-labkit.svg" width="49%" alt="labkit: early build, data layer first">
  <img src="assets/card-mimital.svg" width="49%" alt="mimital: handmade marketplace, in progress">
  <a href="https://github.com/callipegah/reel-bot"><img src="assets/card-reel-bot.svg" width="49%" alt="reel-bot: running 24/7"></a>
</p>

## 🧠 How I build agents

```text
question --> planner --> tools --> evidence pack --> reasoning LLM --> judge --> answer
                |                        |                               |
                |_____ deterministic ____|      every claim checked here ^
```

- **The model is rarely the bug.** The harness around it (context, tools, checks) usually is.
- **Numbers come from code, words come from the model.** Guardrails cross-check every figure an LLM writes against the evidence and fix what doesn't match.
- **Tests or it didn't happen.** 1,150+ regression tests stand between a prompt change and production.
- **Company claims stay labeled as company claims** until someone else measures them.

## 📦 Shipped & tinkering

| | Project | What it is |
| --- | --- | --- |
| 📈 | [**prometheus-grafana-observability-demo**](https://github.com/callipegah/prometheus-grafana-observability-demo) | A Go service exposing all four Prometheus metric types, visualized in Grafana. One `docker compose up`. |
| 📲 | [**reel-bot**](https://github.com/callipegah/reel-bot) *(running 24/7, private to me)* | Telegram bot: send an Instagram reel link, get a summary, then chat about it ("shorter", "explain this tool"). yt-dlp + Whisper + an LLM, locked to one user ID, no Instagram login. |
| 🎬 | [**youtube-digest**](https://github.com/callipegah/youtube-digest) | `/plugin marketplace add callipegah/youtube-digest` and your Watch Later becomes a reading list. |
| ✨ | [**ai-content-system**](https://github.com/callipegah/ai-content-system) | `/plugin marketplace add callipegah/ai-content-system`: Radar, deep dives, Lightboard visuals, narrated videos. |
| 🛍️ | [**scout**](https://github.com/callipegah/scout) *(private)* | Shopping assistant: a planner picks search queries, Python enforces budget/mode rules, an explainer writes the answer from evidence only — never an invented price or link. |
| 🧪 | **labkit** *(private)* | Lab report in, weekly meal plan out. Unit conversions are derived from molar mass and tested against published factors; extraction is a strict JSON contract; meals come from a constraint solver, not free generation. |
| 🛍️ | **mimital** *(private)* | Marketplace for handmade and concept-store goods in Persian. React + FastAPI + Postgres; clothing hangs on a 3D rail that turns toward you on hover, product photos get AI background removal, login is a phone number plus an SMS code, and an LLM assistant recommends from the real catalog. |

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,fastapi,flask,postgres,mongodb,redis,rabbitmq,kafka,docker,kubernetes,grafana,prometheus,airflow,linux,gitlab&theme=dark&perline=8" alt="Python, Go, FastAPI, Flask, PostgreSQL, MongoDB, Redis, RabbitMQ, Kafka, Docker, Kubernetes, Grafana, Prometheus, Airflow, Linux, GitLab">
</p>
<p align="center">
  <sub>+ ClickHouse · NATS · OpenShift · LLM agents · evals · Claude Code skills &amp; plugins</sub>
</p>

---

<p align="center">
  <b>Always curious, always shipping something small.</b><br>
  <sub>همیشه کنجکاو، همیشه در حال ساختن یه چیز کوچیک ✦</sub>
</p>

<h1 align="center">Hi, I'm Ruqi 👋</h1>

<p align="center">
  Founder of <a href="https://trapstreet.run"><b>trapstreet.run</b></a> — a public leaderboard for AI agents, skills and tools.<br>
  <sub><i>Pick a task. Run it locally. Submit your score.</i></sub>
</p>

<p align="center">
  <a href="https://trapstreet.run"><img alt="Website" src="https://img.shields.io/badge/trapstreet.run-111111?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://x.com/ruqi_zheng"><img alt="X" src="https://img.shields.io/badge/@ruqi__zheng-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://discord.gg/Ymm57FzYmF"><img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>
  <a href="https://github.com/trapstreet"><img alt="Org" src="https://img.shields.io/badge/@trapstreet-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

### 🎯 What I'm working on

Most AI benchmarks measure a model. I care about the whole thing you actually ship — the model *plus* the prompt, the scaffold, the tools, the retries. So I'm building a place where you point that whole thing at a real task, run it on your own machine, and put the score on a public board.

Every number on a board is a real run, not a claim.

<br>

### 🧱 The platform — [`@trapstreet`](https://github.com/trapstreet)

| Repo | What it is |
| :--- | :--- |
| **[trap](https://github.com/trapstreet/trap)** &nbsp;<img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"> | `tp` — score any agent, skill, model or script against an eval task, then submit it to a public leaderboard |
| **[trapstreet-tasks](https://github.com/trapstreet/trapstreet-tasks)** &nbsp;<img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"> | Open evaluation tasks — inputs, expected outputs, and a judge |
| **[trapstreet-skills](https://github.com/trapstreet/trapstreet-skills)** &nbsp;<img src="https://img.shields.io/badge/-Agent%20Skills-D97757?style=flat-square"> | Set up the CLI, build a solution against a task, or author a new task |
| **[dsh-trapstreet](https://github.com/trapstreet/dsh-trapstreet)** &nbsp;<img src="https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white"> | Check which DeepSeek Harness plugins actually loaded, and look up public boards |

```bash
uv tool install trap-cli && tp auth login
```

<br>

### 🔬 Evaluation work, in the open

Almost everything below is me answering the same question in a different domain: *given one task, how differently do models and scaffolds actually behave?*

<details>
<summary><b>Multi-model comparisons</b> — same task, several models, one scoreboard</summary>
<br>

| Repo | Task |
| :--- | :--- |
| [cuad-multi-model](https://github.com/Ruqii/cuad-multi-model) | Legal contract clause extraction (CUAD) |
| [vendor-payout-multi-model](https://github.com/Ruqii/vendor-payout-multi-model) | Debugging a real payout bug |
| [mbti-multi-model](https://github.com/Ruqii/mbti-multi-model) | 32-question questionnaire — do models answer consistently? |
| [worldcup-multi-model](https://github.com/Ruqii/worldcup-multi-model) | Constraint solving over match schedules |
| [agents-in-situationship-multi-model](https://github.com/Ruqii/agents-in-situationship-multi-model) | Attachment-style quiz, across models |

</details>

<details>
<summary><b>Baselines</b> — the honest floor a fancy agent has to beat</summary>
<br>

| Repo | Baseline |
| :--- | :--- |
| [trapstreet-solutions](https://github.com/Ruqii/trapstreet-solutions) | Reference implementations across tasks |
| [cuad-baseline](https://github.com/Ruqii/cuad-baseline) | Deterministic extraction, no LLM |
| [python-deterministic](https://github.com/Ruqii/python-deterministic) | Pure-Python timezone scheduler |
| [identify-the-animal-vlm-baseline](https://github.com/Ruqii/identify-the-animal-vlm-baseline) | VLM species identification |
| [minecraft-obtain-diamond](https://github.com/Ruqii/minecraft-obtain-diamond) | An agent plays Minecraft for a diamond |

</details>

<details>
<summary><b>Agent skills & tooling</b> — things I built because I needed them</summary>
<br>

| Repo | What it does |
| :--- | :--- |
| [obsidian-cli-skill](https://github.com/Ruqii/obsidian-cli-skill) | Automate an Obsidian vault from the terminal |
| [llm-wiki-skills](https://github.com/Ruqii/llm-wiki-skills) | Ingest, query and lint a personal LLM wiki |
| [MergeNarrator](https://github.com/Ruqii/MergeNarrator) | Merged PR → analysis → review → post |
| [skill-distill](https://github.com/Ruqii/skill-distill) | Measure whether a community code-review skill helps |
| [ad-pipeline](https://github.com/Ruqii/ad-pipeline) | URL → brand DNA → strategy → copy → images |

</details>

<br>

### 🧰 Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black">
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white">
  <img alt="Postgres" src="https://img.shields.io/badge/Postgres-4169E1?style=flat&logo=postgresql&logoColor=white">
  <img alt="Drizzle" src="https://img.shields.io/badge/Drizzle-C5F74F?style=flat&logo=drizzle&logoColor=black">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=flat&logo=claude&logoColor=white">
</p>

<br>

### 📊 Languages

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Ruqii&theme=github_dark">
  <img alt="Top languages" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Ruqii&theme=github">
</picture>

<br>

---

<p align="center">
  <sub>Building something you want on a board? <a href="https://discord.gg/Ymm57FzYmF">Come say hi in Discord</a>.</sub>
</p>

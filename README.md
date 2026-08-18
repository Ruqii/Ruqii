<h1 align="center">Hi, I'm Ruqi 👋</h1>

<p align="center">
  Founder of <a href="https://trapstreet.run"><b>trapstreet.run</b></a> — a public eval platform helping people find the best AI solutions through evidence.<br>
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

<table>
<tr><td width="34%">

**[trap](https://github.com/trapstreet/trap)**

<img src="https://img.shields.io/pypi/v/trap-cli?label=trap-cli&color=3776AB&logo=pypi&logoColor=white"> <img src="https://img.shields.io/github/license/trapstreet/trap?color=blue">

</td><td>

`tp` — the CLI. Runs your solution as a subprocess with one env var, captures what it writes, scores it through a judge and grader, then submits the run to a board. Your code never imports it or knows it exists.

</td></tr>
<tr><td>

**[trapstreet-tasks](https://github.com/trapstreet/trapstreet-tasks)**

<img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/github/license/trapstreet/trapstreet-tasks?color=blue">

</td><td>

The open tasks themselves — inputs, expected outputs, and a judge. Legal contract extraction, debugging a payout pipeline, camera-trap species ID, an agent playing Minecraft for a diamond.

</td></tr>
<tr><td>

**[trapstreet-skills](https://github.com/trapstreet/trapstreet-skills)**

<img src="https://img.shields.io/github/stars/trapstreet/trapstreet-skills?style=flat-square&color=D97757"> <img src="https://img.shields.io/github/license/trapstreet/trapstreet-skills?color=blue">

</td><td>

Agent skills, so your coding agent can do the setup for you — install the CLI, build a solution against a task, or author a new task.

</td></tr>
<tr><td>

**[dsh-trapstreet](https://github.com/trapstreet/dsh-trapstreet)**

<img src="https://img.shields.io/npm/v/@trapstreet/dsh-trapstreet?color=CB3837&logo=npm&logoColor=white"> <img src="https://img.shields.io/github/license/trapstreet/dsh-trapstreet?color=blue">

</td><td>

A DeepSeek Harness plugin — check which plugins actually loaded, and look up public boards without leaving your session.

</td></tr>
</table>

<br>

### ⚡ Try it

Point your coding agent at it — installs into Claude Code, Cursor, Codex, Cline, Amp, Antigravity and 70+ more:

```bash
npx skills add trapstreet/trapstreet-skills
```

Then just say:

| Say this | What happens |
| :--- | :--- |
| *"set up trapstreet"* | Installs and authorizes the `tp` CLI. One time — local scoring needs no account. |
| *"build a solution for &lt;task&gt;"* | Writes `trap.yaml` and the solver, runs it locally, submits when you're happy. From scratch, around code you have, or by adapting someone else's repo. |
| *"make a task that evaluates &lt;X&gt;"* | Interviews you on what counts as correct and where ground truth comes from, writes the judge and grader, then calibrates until the scores mean something. |

<details>
<summary><b>Prefer the CLI directly?</b></summary>
<br>

```bash
uv tool install trap-cli   # the command is `tp`
tp auth login              # authorize this machine, once
tp run && tp submit        # from any directory with a trap.yaml
```

</details>

Tasks live in their author's own repository, not mine — publish from anywhere public and register it on the site.

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

---

<p align="center">
  <sub>Building something you want on a board? <a href="https://discord.gg/Ymm57FzYmF">Come say hi in Discord</a>.</sub>
</p>

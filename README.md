<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-header-dark.png">
  <img alt="Paul Southall. I build real systems. I share what actually works. AI adoption consultant, Sydney." src="github-header-image.png">
</picture>

---

### About Me

AI adoption consultant in Sydney. Engineering leader. Operator.

I lead a globally distributed team of ~175 engineers and architecture building high-performance platforms in fintech and trading where uptime and performance is non-negotiable.

AI-native decision making sits at the core of how I operate - keeping people risk, delivery health and compliance exposure in front of me, not behind me.

I build real systems. I share what actually works.

Currently **Global Head of Architecture & Engineering at FDJ**.

[![LinkedIn](https://img.shields.io/badge/-Paul%20Southall-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/pauliosouthall/)

---

### AI Systems I've Built

| System | What it does | Impact |
|---|---|---|
| **Throughline** | Engineering intelligence for teams of humans and agents: flow and DORA metrics, working agreements and an agent-run ledger. Built by the agent pipeline it measures, with 7 agent roles and 21 Claude skills | 6 of 15 merged pull requests came from the unattended pipeline, every one behind my merge (Oct 2026) |
| **Jarvis** | AI orchestrator - the backbone of how I run my organisation | Shifted from instinct-led to signal-led leadership at scale |
| **Chief of Staff AI** | Weekly Pulse skill: turns anonymised voice notes into a leadership read across ~175 engineers | Earlier risk detection, better 1:1s, more proactive leadership |
| **Engineering Health Companion** | Weekly engineering health from GitLab: deterministic metrics, a Claude-written narrative and follow-up questions | Every number is checked against tool output, and names are pseudonymised before data leaves the laptop |
| **AI-governed software factory** | Five role-separated agents (spec, architect, dev, QA, security) with a human approval gate between every stage | A tamper-evident audit trail from intent to release |
| **Corporate Bingo** | Real-time multiplayer buzzword bingo, built as a vehicle for end-to-end AI orchestration. A requirements skill turns a plain-English brief into a ready GitHub issue | Live on Vercel |
| **Peckish** | A Claude skill plus an MCP server: photo of the fridge in, three dinners you can make tonight out | Built in public, weekend by weekend |
| **CornealScope** | Webcam computer vision that tracks how a ring pattern reflected off the cornea distorts over time, the shape change keratoconus causes. Runs entirely in the browser, with no data leaving the device | Scoring validated against synthetic eyes with known distortion. An engineering demo, not a medical device |
| **Morning brief** | Claude skill that renders my day as one page, on a weekday schedule | One read before the first meeting |
| **Andrew** | Property investment bot - shortlists and evaluates listings against personal investment goals | Replaced hours of manual weekend research with automated recommendations |

---

### How I build: loop engineering

Throughline is built by the loop it measures. Agents plan, build, verify and review; three separate review passes check for bugs, security and the spec; only I merge.

```mermaid
%%{init: {"flowchart": {"wrappingWidth": 320}}}%%
flowchart TB
    issue["<b>Jira story</b><br/>ready, assigned to the agent"]
    build["<b>Implement</b><br/>plan mode · playbook by issue type<br/>loops until checks pass"]
    verify["<b>Verify</b><br/>QA agent · fresh context · read-only"]
    bugs["<b>Review 1</b><br/>bugs and logic"]
    sec["<b>Review 2</b><br/>security and privacy"]
    spec["<b>Review 3</b><br/>spec and plan"]
    merge(["I review and merge"])
    ship["<b>Deploy</b><br/>Vercel · Jira to Done"]
    measure["<b>Throughline measures it</b><br/>flow · DORA · agent-run ledger"]

    issue --> build --> verify
    verify -. NOT_READY .-> build
    verify --> bugs & sec & spec
    bugs & sec & spec --> merge
    merge --> ship --> measure
    measure -. "closing the loop" .-> issue

    classDef default fill:transparent,stroke:#8E8E93,stroke-width:1px
    classDef human fill:transparent,stroke:#2563EB,stroke-width:2px
    classDef product fill:#2563EB,stroke:#2563EB,color:#FFFFFF
    class merge human
    class measure product
```

---

### How I lead: signals in front of me

```mermaid
%%{init: {"flowchart": {"wrappingWidth": 320}}}%%
flowchart TB
    signals["<b>Org signals</b><br/>delivery health<br/>compliance exposure<br/>anonymised team notes"]
    jarvis("<b>Jarvis</b><br/>orchestrator")
    cos["<b>Chief of Staff AI</b><br/>patterns and risk<br/>across ~175 engineers"]
    front["<b>In front of me, not behind me</b><br/>daily briefing · 1:1 prep<br/>early risk flags"]
    me(["I decide and act"])
    andrew["<b>Andrew</b> · personal<br/>listings in, investment<br/>shortlists out"]

    signals --> jarvis --> cos --> front
    front -- "signal-led, not instinct-led" --> me
    jarvis -.-> andrew

    classDef default fill:transparent,stroke:#8E8E93,stroke-width:1px
    classDef hub fill:#2563EB,stroke:#2563EB,color:#FFFFFF
    classDef human fill:transparent,stroke:#2563EB,stroke-width:2px
    classDef side fill:transparent,stroke:#8E8E93,stroke-width:1px,stroke-dasharray:4 4
    class jarvis hub
    class me human
    class andrew side
```

---

### Where I share

Practical AI for leaders in the missing middle, between beginner tips and advanced builds: real systems, honest experiments and the simple stuff first.

[LinkedIn](https://www.linkedin.com/in/pauliosouthall/) · [psouthall.com](https://psouthall.com)

---

### AI Stack

Tools I actually use to operate:

![Claude](https://img.shields.io/badge/Claude-Anthropic-black?style=flat&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-Agents-black?style=flat&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-black?style=flat&logo=modelcontextprotocol&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Operator-blue?style=flat)
![StudioLLM](https://img.shields.io/badge/StudioLLM-AI-blue?style=flat)
![PaperClip](https://img.shields.io/badge/PaperClip-Orchestration-blue?style=flat)

---

### Technologies I've Led at Scale

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="Redux" alt="Redux" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg" title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain-wordmark.svg" title="Django" alt="Django" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-plain-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nextjs/nextjs-original.svg" title="NextJS" alt="NextJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-original.svg" title="Tailwind" alt="Tailwind" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/sentry/sentry-original.svg" title="Sentry" alt="Sentry" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/grafana/grafana-original.svg" title="Grafana" alt="Grafana" width="40" height="40"/>
</div>

#### Building with now

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/githubactions/githubactions-original.svg" title="GitHub Actions" alt="GitHub Actions" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vercel/vercel-original.svg" title="Vercel" alt="Vercel" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/supabase/supabase-original.svg" title="Supabase" alt="Supabase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/playwright/playwright-original.svg" title="Playwright" alt="Playwright" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vitest/vitest-original.svg" title="Vitest" alt="Vitest" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original.svg" title="Jira" alt="Jira" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/opencv/opencv-original.svg" title="OpenCV" alt="OpenCV" width="40" height="40"/>
</div>

---

### GitHub Stats

[![GitHub Streak](https://streak-stats.demolab.com?user=paul-southall&hide_border=true&background=000000&stroke=2563EB&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&sideLabels=ffffff&dates=ffffff&currStreakNum=ffffff&sideNums=ffffff)](https://git.io/streak-stats)

# Mini PM

**AI-powered skills for product managers, built as a Claude plugin.**

![banner](./assets/banner.png)

Stop writing the same PRDs, research briefs, and job strategies from scratch. Mini PM gives you a focused PM toolkit inside Claude — strategy, research, and career, all invokable in one line.

---

## Overview

**Mini PM** is a Claude plugin that gives product managers a set of AI-powered skills — pre-built, structured workflows you invoke with a single slash command inside Claude.

Instead of prompting Claude from scratch every time, Mini PM packages senior PM best practices into repeatable skills:

- **Strategy** — write PRDs and audit product specs against a quality checklist
- **Research** — run competitive and market analysis, or synthesize raw user interviews into ranked insights
- **Career** — build a personalized AI job strategy and generate an ATS-optimized resume

Each skill asks Claude to think and respond like a senior PM. You bring the context; Mini PM brings the structure and rigor.

**Who it's for:** PMs at any level who want faster, higher-quality output without starting from a blank page — and anyone breaking into product or AI product roles who wants professional-grade frameworks on demand.

---

## What's inside

| Skill | Category | What it produces |
|---|---|---|
| `/prd` | Strategy | Full PRD — hypothesis, problem, solution, metrics, rollout plan |
| `/prd-review` | Strategy | PRD quality audit — completeness checklist for 2-pagers and 6-pagers |
| `/market-research` | Research | Competitive landscape, TAM/SAM/SOM, trends, pricing intel, strategic implications |
| `/user-research` | Research | Synthesizes raw interviews and notes into ranked PM insights |
| `/job-strategy` | Career | Personalized AI job strategy — diagnosis, positioning, outreach, prep |
| `/resume-builder` | Career | AI-optimized resume — impact bullets, ATS keywords, tailored to the role |

---

## Install

1. Open Claude app
2. Click **Customize** in the sidebar

![banner](./assets/7.png)

3. Under **Personal Plugins**, click **Add** → **Create Plugin** → **Add Marketplace**

![banner](./assets/2.png)

4. Paste the repo URL:
   ```
   https://github.com/sachin0034-tech/miniPM.git
   ```

![banner](./assets/3.png)

5. A **Directory** option will appear — under **Personal**, you will see the **miniPM** plugin listed

![banner](./assets/4.png)

6. Click on the plugin and then click on **Install**

![banner](./assets/5.png)

7. You now have the plugin with all the skills available inside Claude

![banner](./assets/6.png)

---

## Usage

Once installed, invoke any skill by name:

```
/prd  Real-time collaboration feature for enterprise design teams
```
```
/market-research  AI coding assistants for enterprise software teams
```
```
/prd-review  [paste your PRD]
```
```
/user-research  [paste interview transcripts or research notes]
```
```
/job-strategy  I want to land an AI PM role at a top foundation model company
```
```
/resume-builder  [paste your current resume]
```

Every skill accepts free-text input and returns structured, senior-quality output.

---

## Repo structure

```
miniPM/
├── .claude-plugin/
│   ├── plugin.json          ← plugin manifest
│   └── marketplace.json     ← marketplace index
├── skills/
│   ├── prd/SKILL.md
│   ├── prd-review/SKILL.md
│   ├── market-research/SKILL.md
│   ├── user-research/SKILL.md
│   ├── job-strategy/SKILL.md
│   └── resume-builder/SKILL.md
├── assets/
└── README.md
```

---

## License

MIT — free to use, fork, and extend.

<div align="center">

# 🌉 Immersion Week SF

### From a vague idea to a battle-tested prototype — in three days

**3 Days · 9 Sessions · 27 Goals · 11 Tools**

`Dates TBD` · San Francisco · Instructor: **Victor Palacios**

**9:00 AM – 12:00 PM PT daily**

</div>

---

## 🎯 The Arc

| Day | Title | What you walk out with |
|:--|:--|:--|
| **Day 1** | 🧭 **The Blueprint** | A precise problem statement, a mapped workflow, and a task board with owners |
| **Day 2** | 🔨 **The Build** | A working happy-path prototype someone else can drive |
| **Day 3** | ⚔️ **The Battle Test** | A prototype hardened against the edge cases your peers found |

---

## 🤖 The Tool Ladder

The AI tooling climbs with the days. Each layer assumes the one below it, so
nothing arrives before you have a reason to want it.

| Day | Layer | You are learning to… | Tools |
|:--|:--|:--|:--|
| **Day 1** | 💬 **Conversational** | talk to Claude well enough that it sharpens your thinking | Prompt Engineering · Claude Projects · Claude Artifacts · Claude Cowork · GitHub |
| **Day 2** | 🔧 **Constructive** | build and ship a real thing with Claude in the loop | RAG · Claude Code · GitHub Pages · Cloudflare |
| **Day 3** | 🚀 **Autonomous** | hand work to something that runs without you watching | Agents · Nvidia API (free LLMs) · Claude Routines |

<details>
<summary><strong>Why this order</strong></summary>

<br>

The ladder follows the same escalation Anthropic recommends for building with
Claude: **a single call, then a workflow you control, then an agent that
controls itself.** Each rung is strictly more powerful and strictly harder to
debug, so we only climb when the rung below stops being enough.

Day 1 is one conversation at a time — no code, no deployment, nothing that can
break while you sleep. Day 2 adds retrieval, a repo, and a public URL, so
mistakes become visible to other people. Day 3 hands the loop to the machine,
which is where the failure modes get genuinely interesting — and why it lands
on the day whose whole theme is *finding out what breaks*.

</details>

---

## ⏱️ Daily Rhythm

**Every day runs the same shape.** Learn it once — it never changes.

| Time (PT) | Block | Length |
|:--|:--|--:|
| **9:00 – 9:20** | 📝 **Review assignment** · Qualtrics<br>_Day 1 only:_ 👋 Intro to the course & instructor | 20 min |
| **9:20 – 9:55** | 🎓 **Hour 1 lecture** | 35 min |
| 9:55 – 10:00 | ☕ Break | 5 min |
| **10:00 – 10:55** | 🎓 **Hour 2 lecture** | 55 min |
| 10:55 – 11:00 | ☕ Break | 5 min |
| **11:00 – 11:50** | 🎓 **Hour 3 lecture** | 50 min |
| 11:50 – 12:00 | 🏢 Prep for Company Visit | 10 min |

> [!IMPORTANT]
> **One review per day, and only at 9:00** — not at the top of every hour.
> **Day 1 has no review at all.** There is nothing to review yet, so it opens with a 20-minute intro to the course and instructor.
> **The day ends at 11:50.** Hour 3 takes no break; the last 10 minutes are Prep for Company Visit.

<details>
<summary><strong>Where the 180 minutes go</strong></summary>

<br>

| | Minutes |
|:--|--:|
| 🎓 Lecture (35 + 55 + 50) | **140** |
| 📝 Review assignment _(Day 1: intro)_ | 20 |
| ☕ Breaks (2 × 5) | 10 |
| 🏢 Prep for Company Visit | 10 |
| **Total** | **180** |

</details>

---

## 📅 Schedule at a Glance

All times Pacific. Click any session to jump to its goals and materials.

| Lecture | 🧭 **Day 1 — The Blueprint** | 🔨 **Day 2 — The Build** | ⚔️ **Day 3 — The Battle Test** |
|:--|:--|:--|:--|
| **9:00 – 9:20**<br>_opening block_ | 👋 Intro to course & instructor | 📝 [Review — _Qualtrics TBD_](#) | 📝 [Review — _Qualtrics TBD_](#) |
| **Hour 1**<br>`9:20–9:55` | [**1.1** — Precise Problem Statement](#s11) | [**2.1** — Choosing the Stack](#s21) | [**3.1** — Designing the Attack](#s31) |
| **Hour 2**<br>`10:00–10:55` | [**1.2** — Mapping the Workflow](#s12) | [**2.2** — Building the Happy Path](#s22) | [**3.2** — Peer Red-Team Round](#s32) |
| **Hour 3**<br>`11:00–11:50` | [**1.3** — Dividing the Work](#s13) | [**2.3** — Making It Demoable](#s23) | [**3.3** — Hardening & Handoff](#s33) |

---

## 🧭 Day 1 — The Blueprint · `Date TBD`

> **Identify and define a precise, achievable problem — then map the entire
> workflow to reach the solution and divide it across the team's skillset.**

💬 **Tool layer — Conversational:** `Prompt Engineering` `Claude Projects` `Claude Artifacts` `Claude Cowork` `GitHub`

**👋 9:00 – 9:20 · Intro to the course and instructor** — no review on Day 1.

<a id="s11"></a>

### 🕘 Hour 1 · **1.1** — From Vague Idea to Precise Problem Statement

`🎓 Lecture 9:20–9:55` → `☕ Break 9:55–10:00`

🤖 **Tools:** `Prompt Engineering` `Claude Projects`

> **Goals**
> 1. Tell a **problem** statement apart from a **solution** statement, and use **prompt engineering** to make Claude interrogate a vague ask until it is precise
> 2. Apply a scoping test — measurable outcome, data actually available, achievable in three days — and make Claude argue the opposite case before you commit
> 3. Stand up a **Claude Project** as the team's shared brain: project instructions, uploaded context, one place everyone works from

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

<a id="s12"></a>

### 🕙 Hour 2 · **1.2** — Mapping the Workflow to the Solution

`🎓 Lecture 10:00–10:55` → `☕ Break 10:55–11:00`

🤖 **Tools:** `Claude Artifacts` `Prompt Engineering`

> **Goals**
> 1. Decompose the problem into a stepwise workflow, from raw input to delivered output
> 2. Turn that workflow into a **Claude Artifact** — a diagram the whole team can see, revise, and share by link
> 3. Name what each step needs (data, a tool, or a human decision), then have Claude generate the three ways the riskiest step most likely fails

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

<a id="s13"></a>

### 🕚 Hour 3 · **1.3** — Dividing the Work Across the Team

`🎓 Lecture 11:00–11:50` → `🏢 Prep for Company Visit 11:50–12:00`

🤖 **Tools:** `Claude Cowork` `GitHub`

> **Goals**
> 1. Inventory the team's actual skills and assign every workflow step a single owner
> 2. Use **Claude Cowork** to run several workstreams in parallel without the team stepping on each other
> 3. Put the task board in **GitHub** — a repo, issues with owners, and a definition of done for every Day 2 task

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

---

## 🔨 Day 2 — The Build · `Date TBD`

> **Construct a 'happy path' prototype using low-code tools.**

🔧 **Tool layer — Constructive:** `RAG` `Claude Code` `GitHub Pages` `Cloudflare`

**📝 9:00 – 9:20 · Review assignment** — [_Qualtrics link TBD_](#)

<a id="s21"></a>

### 🕘 Hour 1 · **2.1** — Choosing Your Low-Code Stack

`🎓 Lecture 9:20–9:55` → `☕ Break 9:55–10:00`

🤖 **Tools:** `RAG` `Claude Projects`

> **Goals**
> 1. Match each step of yesterday's workflow map to a specific tool, and decide deliberately what to **stub** and what to **build**
> 2. Tell the difference between needing **RAG** and just needing context in the window — then pick the cheaper one that works
> 3. Stand up the smallest retrieval layer that answers your prototype's questions, with a **Claude Project** as the baseline to beat

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

<a id="s22"></a>

### 🕙 Hour 2 · **2.2** — Building the Happy Path

`🎓 Lecture 10:00–10:55` → `☕ Break 10:55–11:00`

🤖 **Tools:** `Claude Code` `GitHub`

> **Goals**
> 1. Drive **Claude Code** to implement each step against one known-good input — no edge cases, no error handling, not yet
> 2. Connect the steps so a single input reaches a finished output with no manual intervention
> 3. Commit to **GitHub** the moment it works, before adding anything else to it

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

<a id="s23"></a>

### 🕚 Hour 3 · **2.3** — Making It Demoable

`🎓 Lecture 11:00–11:50` → `🏢 Prep for Company Visit 11:50–12:00`

🤖 **Tools:** `GitHub Pages` `Cloudflare` `Claude Artifacts`

> **Goals**
> 1. Wrap the prototype in a front end a stranger can drive — a **Claude Artifact**, or a page you write and host
> 2. Ship it to a public URL with **GitHub Pages** or **Cloudflare**, so your demo does not depend on your laptop staying open
> 3. Write a three-minute demo script, and document what is stubbed, faked, or known-broken — this is Day 3's attack surface

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

---

## ⚔️ Day 3 — The Battle Test · `Date TBD`

> **Rigorously peer-test prototypes to identify and harden against edge cases.**

🚀 **Tool layer — Autonomous:** `Agents` `Nvidia API (free LLMs)` `Claude Routines`

**📝 9:00 – 9:20 · Review assignment** — [_Qualtrics link TBD_](#)

<a id="s31"></a>

### 🕘 Hour 1 · **3.1** — Designing the Attack

`🎓 Lecture 9:20–9:55` → `☕ Break 9:55–10:00`

🤖 **Tools:** `Agents` `Prompt Engineering`

> **Goals**
> 1. Build an edge-case inventory across the standard axes: empty, malformed, adversarial, out-of-scope, and at scale
> 2. Learn what an **agent** actually is — a loop with tools and a goal — and when the four tests (complexity, value, viability, cost of error) say to build one
> 3. Design an agent that probes a prototype on its own, and draw the line between **failure** and acceptable **degradation** before it runs

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

<a id="s32"></a>

### 🕙 Hour 2 · **3.2** — Peer Red-Team Round

`🎓 Lecture 10:00–10:55` → `☕ Break 10:55–11:00`

🤖 **Tools:** `Agents` `Nvidia API`

> **Goals**
> 1. Break another team's prototype — run their test script by hand, then turn your **testing agent** loose on it
> 2. Use **Nvidia's free LLM API** to generate adversarial inputs in bulk, so volume costs you nothing
> 3. Log every failure with reproduction steps and a severity — and receive your own log without defending it

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

<a id="s33"></a>

### 🕚 Hour 3 · **3.3** — Hardening & Handoff

`🎓 Lecture 11:00–11:50` → `🏢 Prep for Company Visit 11:50–12:00`

🤖 **Tools:** `Claude Routines` `GitHub`

> **Goals**
> 1. Triage the failure log by severity against cost to fix, and commit to a cut line
> 2. Fix what is above the line, re-run the exact tests that caught each one, and push to **GitHub**
> 3. Set up a **Claude Routine** that re-runs the regression suite on a schedule, so the prototype keeps being tested after you stop looking

📊 **Slides:** [_TBD_](#) &nbsp;·&nbsp; 📎 **Materials:** [_TBD_](#) &nbsp;·&nbsp; ✏️ **Homework:** _TBD_

---

## 📚 Materials Index

### Opening block · 9:00 – 9:20

| Day | Block | Link |
|:--|:--|:--|
| **Day 1** | 👋 Intro to the course and instructor | _no review_ |
| **Day 2** | 📝 Review assignment | [_Qualtrics TBD_](#) |
| **Day 3** | 📝 Review assignment | [_Qualtrics TBD_](#) |

### Sessions

| Session | Lecture | Topic | Tools | Slides | Materials | Homework |
|:--|:--|:--|:--|:--|:--|:--|
| [1.1](#s11) | `9:20–9:55` | Precise Problem Statement | Prompt Engineering · Projects | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [1.2](#s12) | `10:00–10:55` | Mapping the Workflow | Artifacts | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [1.3](#s13) | `11:00–11:50` | Dividing the Work | Cowork · GitHub | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [2.1](#s21) | `9:20–9:55` | Choosing the Stack | RAG · Projects | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [2.2](#s22) | `10:00–10:55` | Building the Happy Path | Claude Code · GitHub | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [2.3](#s23) | `11:00–11:50` | Making It Demoable | Pages · Cloudflare | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [3.1](#s31) | `9:20–9:55` | Designing the Attack | Agents | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [3.2](#s32) | `10:00–10:55` | Peer Red-Team Round | Agents · Nvidia API | [_TBD_](#) | [_TBD_](#) | _TBD_ |
| [3.3](#s33) | `11:00–11:50` | Hardening & Handoff | Routines · GitHub | [_TBD_](#) | [_TBD_](#) | _TBD_ |

**2 Qualtrics review links** to come — one for Day 2, one for Day 3.

---

<details>
<summary><strong>🛠️ How this repo is organized</strong></summary>

<br>

```
.
├── README.md            ← you are here (the schedule everyone reads)
└── materials/           ← handouts, datasets, notebooks hosted in-repo
```

**This README is the schedule.** It renders on the repo homepage with no setup,
works in the GitHub mobile app, and can be edited straight in the browser.

**Session numbering** is `<day>.<hour>` — so `2.3` is Day 2, the 11:00 hour.
Goals inside a session are `1`, `2`, `3`, making `2.3` goal `1` unambiguous to
reference out loud in class.

**Links** can point anywhere — Google Slides, Overleaf, Colab, Qualtrics, a PDF
in `materials/`, an external article. Anything currently showing `TBD` is a
placeholder waiting on content.

</details>

<div align="center">

<sub>Immersion Week SF · University of Chicago Careers in AI</sub>

</div>

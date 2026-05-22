# Ex. No. 7 — Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

### Name: Abdur Rahman Basil A H
### Reg No : 212223040002
## Aim

To develop a prompt-based application using ChatGPT that demonstrates how to organize daily tasks and personal activities, showing the clear progression from simple to intermediate to advanced prompt designs — and how each level produces increasingly useful, structured, and actionable outputs.

---

## AI Tools Used

| Tool | Purpose |
|---|---|
| **ChatGPT (GPT-4o)** | Primary LLM for prompt testing and output generation |
| **Google Gemini** | Cross-validation of prompts and comparative output analysis |
| **GitHub Copilot** | Assisted in structuring prompt templates and documentation |

---

## Explanation

This experiment focuses on building a **personal productivity assistant** powered entirely by prompt engineering — no code or database required. By iterating prompts from basic to advanced, the same AI tool produces vastly different quality outputs. The assistant is capable of:

- Organizing daily tasks by priority and time
- Generating structured schedules for study, work, and travel
- Breaking down complex projects into manageable steps
- Managing budgets and flagging overspending
- Planning travel itineraries with timing and tips
- Offering contextual wellness and productivity suggestions

The key insight is that **the prompt is the application** — thoughtful prompt design replaces traditional programming logic.

---

## Procedure

1. Identified four practical personal use cases: scheduling, project breakdown, budgeting, and travel planning.
2. Designed three prompt tiers (Simple → Intermediate → Advanced) for each use case.
3. Tested every prompt in ChatGPT and Google Gemini independently.
4. Recorded and compared outputs at each tier.
5. Identified what specific additions to the prompt caused output quality to improve.
6. Summarized findings and prompt design patterns as reusable guidelines.

---

## Application 1 — Study Time Scheduler

### Background

A student needs to fit multiple subjects, revision sessions, and breaks into a productive daily study plan. Prompts guide the AI from a simple list to a fully structured, personalized timetable.

---

### Prompt Tier 1 — Simple

```
Create a study schedule for me. I need to study Maths, Physics, and Chemistry today.
```

**Output:**
```
Study Plan:
- Maths
- Physics
- Chemistry
```

**Observation:** Output is a flat list. No timing, no priority, no structure — essentially what the user already typed.

---

### Prompt Tier 2 — Intermediate

```
Act as a study planner. Organize my subjects — Maths, Physics, and Chemistry — 
into a time-blocked daily schedule with priority levels. I study best in the morning.
```

**Output:**
```
Study Schedule:

07:00 AM – Maths (High Priority) ★★★
  → Focus on problem sets and formulas

09:30 AM – Physics (High Priority) ★★★
  → Cover mechanics and numericals

11:30 AM – Chemistry (Medium Priority) ★★
  → Revise organic reactions

01:00 PM – Lunch Break

02:00 PM – Revision: Maths quick review (30 min)

Note: High-priority subjects are placed in morning peak hours for better retention.
```

**Observation:** Time slots appear, morning preference is respected, and priority levels are applied. A significant improvement over Tier 1.

---

### Prompt Tier 3 — Advanced

```
Act as an expert academic coach and study planner. I am a college student preparing 
for exams next week. Create a full day study timetable for Maths, Physics, and Chemistry 
with the following constraints:
- I am most focused between 7 AM and 12 PM.
- Physics is my weakest subject — allocate more time.
- Include Pomodoro-style 25-minute study + 5-minute break blocks.
- Add short motivational cues and memory tips for each subject.
- If I fall behind, suggest what to cut without harming exam performance.
```

**Output:**
```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🎓 EXAM PREP TIMETABLE — DAY PLAN
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

MORNING PEAK BLOCK (07:00 AM – 12:00 PM)
──────────────────────────────────────────
07:00–07:25  📘 Physics — Mechanics (Pomodoro 1)
07:25–07:30  Break — stretch and breathe
07:30–07:55  📘 Physics — Waves & Optics (Pomodoro 2)
07:55–08:00  Break
08:00–08:25  📘 Physics — Numericals practice (Pomodoro 3)
             💡 Tip: Draw free-body diagrams before solving.
08:25–08:45  Extended break — water + light snack

09:00–09:25  📗 Maths — Calculus (Pomodoro 1)
09:25–09:30  Break
09:30–09:55  📗 Maths — Algebra revision (Pomodoro 2)
             💡 Tip: Rederive key formulas from scratch to lock them in.
09:55–10:00  Break

10:00–10:25  📙 Chemistry — Organic reactions (Pomodoro 1)
10:25–10:30  Break
10:30–10:55  📙 Chemistry — Periodic trends (Pomodoro 2)
             💡 Tip: Use mnemonics — "LEO says GER" for redox reactions.
10:55–11:00  Break

11:00–12:00  🔁 Mixed Revision — 20 min each subject (rapid recall)

AFTERNOON BLOCK (02:00 PM – 04:00 PM)
──────────────────────────────────────
02:00–03:00  📘 Physics — Past paper questions (focus on weak areas)
03:00–03:30  📗 Maths — Formula sheet creation
03:30–04:00  📙 Chemistry — Equations and balancing

IF YOU FALL BEHIND:
  ✂ Cut: Afternoon Chemistry (least exam-weighted)
  ✂ Shorten: Mixed revision to 10 min per subject
  ✅ Keep: All Physics blocks — weakest subject, highest risk
  ✅ Keep: Morning Maths — highest marks potential

🌟 Motivational Cue: "One Pomodoro at a time. You don't need to study everything 
   — you need to study smart."
```

**Observation:** The Advanced prompt produces an exam-ready, personalized timetable with memory science (Pomodoro), subject-specific tips, contingency planning, and motivational framing. This is a complete productivity application response.

---

## Application 2 — Project Task Breakdown

### Background

A developer needs to break down a college mini-project (a Library Management System) into actionable tasks with deadlines and team assignments.

---

### Prompt Tier 1 — Simple

```
Break down a Library Management System project into tasks.
```

**Output:**
```
Tasks:
1. Design database
2. Build frontend
3. Write backend code
4. Test the system
5. Deploy
```

**Observation:** Extremely generic. No deadlines, no ownership, no subtasks.

---

### Prompt Tier 2 — Intermediate

```
Act as a project manager. Break down a Library Management System college project 
into phases with tasks, estimated time, and priority. The deadline is 3 weeks away 
and there are 3 team members.
```

**Output:**
```
PROJECT: Library Management System
Team Size: 3 | Deadline: 3 weeks

PHASE 1 — Planning & Design (Week 1)
  [HIGH] Requirements gathering       — 1 day  — All members
  [HIGH] Database schema design       — 2 days — Member 1
  [MED]  UI wireframes                — 2 days — Member 2
  [MED]  Tech stack finalisation      — 1 day  — Member 3

PHASE 2 — Development (Week 2)
  [HIGH] Backend: CRUD for books      — 3 days — Member 1
  [HIGH] Frontend: book listing page  — 2 days — Member 2
  [HIGH] Authentication system        — 2 days — Member 3

PHASE 3 — Testing & Deployment (Week 3)
  [HIGH] Integration testing          — 2 days — All members
  [MED]  Bug fixes                    — 2 days — Member 1 + 2
  [LOW]  Documentation & README       — 1 day  — Member 3
  [HIGH] Deployment (Render / Vercel) — 1 day  — Member 1
```

**Observation:** Clear phases, timing, and team assignments emerge. Usable as an actual project plan.

---

### Prompt Tier 3 — Advanced

```
Act as a senior software project manager and Agile coach. 
I have a 3-week college project: Library Management System using the MERN stack.
Team: 3 members — a backend developer, a frontend developer, and a tester.
Constraints:
- We have 2 hours per day on weekdays only.
- Week 1 is exam week — available time is reduced to 30 minutes/day.
- We must submit on GitHub with a working demo.
Break this into a sprint plan with daily tasks, blockers to watch out for, 
and a risk mitigation plan if someone falls sick.
```

**Output:**
```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🗂 AGILE SPRINT PLAN — Library Management System (MERN)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

SPRINT 0 — EXAM WEEK (30 min/day, Mon–Fri)
  Mon: Finalise project scope + GitHub repo setup (All)
  Tue: Database schema draft — Books, Users, Transactions (Backend Dev)
  Wed: Low-fidelity wireframes (Frontend Dev)
  Thu: Tech stack lock-in + environment setup (All)
  Fri: README skeleton + project board on GitHub Projects (Tester)

⚠ Blocker Watch: Don't start coding in Sprint 0 — exam fatigue causes bugs.

SPRINT 1 — CORE DEVELOPMENT (2 hrs/day, Mon–Fri)
  Mon–Tue: Backend — Express routes for Books CRUD (Backend Dev)
           Frontend — Landing page + navigation bar (Frontend Dev)
           Tester — Write test cases for Book APIs
  Wed–Thu: Backend — User auth with JWT (Backend Dev)
           Frontend — Book listing + search UI (Frontend Dev)
           Tester — API testing with Postman
  Fri:     Integration checkpoint — connect frontend to backend for Books module

⚠ Blocker Watch: JWT auth commonly breaks CORS. Prepare a CORS middleware template.

SPRINT 2 — FEATURES + POLISH (2 hrs/day, Mon–Fri)
  Mon–Tue: Issue/Return system (Backend + Frontend pair programming)
  Wed:     Admin dashboard (Frontend Dev)
  Thu:     Full integration testing + bug fixes (All)
  Fri:     Deploy to Render (backend) + Vercel (frontend) — Live demo ready

RISK MITIGATION:
  🚨 If Backend Dev falls sick:
     → Frontend Dev takes API integration; Tester handles basic Express routes.
     → Simplify: use mock JSON data temporarily.
  🚨 If Frontend Dev falls sick:
     → Use a pre-built React admin template (e.g., React-Admin) to save time.
  🚨 If Tester falls sick:
     → Backend Dev writes unit tests with Jest during development.

GITHUB SUBMISSION CHECKLIST:
  ✅ README with setup instructions
  ✅ .env.example file (never commit real .env)
  ✅ Screenshots / screen recording of working demo
  ✅ All members have commit history
  ✅ Live demo link in repo description
```

**Observation:** The Advanced prompt generates a real Agile sprint plan, accounts for real-world constraints (exam week, sickness), and produces a submission-ready checklist — functioning as a full project management tool.

---


## Prompt Progression Summary

| Tier | Prompt Characteristics | Output Quality |
|---|---|---|
| **Simple** | Short, task-only, no context | Flat list; no structure or detail |
| **Intermediate** | Role assignment + key constraints | Structured output with timing, priority, categories |
| **Advanced** | Role + constraints + output format + edge cases + contingencies | Professional-grade, personalized, actionable output |

### Key Prompt Engineering Techniques Used

| Technique | Effect |
|---|---|
| **Role assignment** (`"Act as a..."`) | Shifts the AI's tone and depth significantly |
| **Explicit constraints** (budget, time, preferences) | Output becomes personalized rather than generic |
| **Output format specification** | Eliminates unnecessary prose; structures response for readability |
| **Edge case handling** (`"If I fall behind..."`) | Adds contingency planning and practical resilience |
| **Numbered sub-tasks in the prompt** | Each task is addressed; nothing is skipped |
| **Domain vocabulary** (Pomodoro, sprint, variance) | AI applies the correct framework for the domain |

---

## Expected Output

All four applications demonstrate the following progression pattern:

**Simple Prompt** → One-line flat list (no value beyond restating input)

**Intermediate Prompt** → Structured table or schedule with priorities and timing

**Advanced Prompt** → Full, professional, domain-expert-quality output with edge cases, contingencies, tips, and actionable next steps

---

## Result

This experiment demonstrated that **prompt design is the primary engineering discipline** when building LLM-based applications. The same AI tool produced outputs ranging from unhelpful one-liners to professional-grade plans — based entirely on how the prompt was constructed.

---

*GitHub Repository: [RaajaThilahar/Ex.No.7](https://github.com/RaajaThilahar/Ex.No.7)*

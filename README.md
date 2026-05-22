# Ex. No. 7 — Prompt-Based Personal Productivity Application

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

## Application 3 — Personal Budget Manager

### Background

A college student needs to track monthly expenses, flag overspending, and receive savings suggestions within a fixed monthly stipend.

---

### Prompt Tier 1 — Simple

```
Help me manage my monthly budget of ₹8000.
```

**Output:**
```
Budget: ₹8000

- Save some money
- Track your expenses
- Avoid overspending
```

**Observation:** Vague and unhelpful — no categories, no plan, no actionable guidance.

---

### Prompt Tier 2 — Intermediate

```
Act as a personal finance assistant. I am a college student with a monthly budget 
of ₹8000. My expenses are: Rent ₹2500, Food ₹2000, Transport ₹500, Entertainment ₹800, 
Stationery ₹300. Create a budget breakdown and tell me if I am overspending.
```

**Output:**
```
MONTHLY BUDGET ANALYSIS — ₹8000
──────────────────────────────────
Category         Allocated    Status
─────────────────────────────────────
Rent             ₹2500        ✅ OK
Food             ₹2000        ✅ OK
Transport        ₹  500        ✅ OK
Entertainment    ₹  800        ⚠ Review
Stationery       ₹  300        ✅ OK
─────────────────────────────────────
TOTAL SPENT      ₹6100
REMAINING        ₹1900        ✅ Surplus

Recommendation: Entertainment at ₹800 is 10% of budget. Consider capping at ₹500 
to increase your savings by ₹300/month.
```

**Observation:** Structured table, surplus calculation, and one targeted recommendation appear. Genuinely usable output.

---

### Prompt Tier 3 — Advanced

```
Act as an expert personal finance coach for a college student in India. 
My monthly stipend is ₹8000. Here are my actual expenses this month:
Rent ₹2500, Food ₹2200 (went over by ₹200), Transport ₹650 (went over by ₹150), 
Entertainment ₹1200 (significantly over budget), Stationery ₹400, Medical ₹300 (unexpected).

Tasks:
1. Show a full budget vs actual table with variance.
2. Flag categories that are over budget and explain why they are risky.
3. Suggest specific cuts for next month with realistic alternatives.
4. Calculate how much I can save in 6 months if I follow your advice.
5. Give me one financial habit tip suitable for a college student.
```

**Output:**
```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  💰 MONTHLY BUDGET REPORT — KARTHIKEYAN (October)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. BUDGET vs ACTUAL TABLE
─────────────────────────────────────────────────────
Category       Budget     Actual     Variance   Status
─────────────────────────────────────────────────────
Rent           ₹2500      ₹2500      ₹0         ✅ On track
Food           ₹2000      ₹2200      –₹200       ⚠ Over
Transport      ₹ 500      ₹ 650      –₹150       ⚠ Over
Entertainment  ₹ 800      ₹1200      –₹400       🚨 Significantly over
Stationery     ₹ 300      ₹ 400      –₹100       ⚠ Over
Medical        ₹   0      ₹ 300      –₹300       ℹ Unplanned
─────────────────────────────────────────────────────
TOTAL          ₹6100      ₹7250      –₹1150      🚨 Over by ₹1150
REMAINING      ₹1900      ₹  750     ↓ ₹1150

2. 🚨 RISK FLAGS
  Entertainment (+₹400): This is the highest risk category. Discretionary 
  spending is the easiest to cut but the hardest to self-regulate. At current 
  rate, this alone erodes ₹4800/year in savings potential.
  
  Food (+₹200): Likely from eating out. Cooking 3 extra meals at home per 
  week saves approximately ₹200–₹300/month.
  
  Transport (+₹150): Possibly from cab usage. Switching to bus or sharing 
  rides twice a week recovers this.

3. ✂ CUTS FOR NEXT MONTH
  Entertainment: ₹1200 → ₹600 (save ₹600)
    → Use free alternatives: YouTube, college events, library
  Food: ₹2200 → ₹1900 (save ₹300)
    → Meal prep on Sundays; limit eating out to once a week
  Transport: ₹650 → ₹500 (save ₹150)
    → Use college bus pass if available; walk for <2 km distances
  Stationery: ₹400 → ₹300 (save ₹100)
    → Use digital notes (Notion/OneNote) to reduce paper purchases

  Projected monthly saving if cuts applied: ₹1150 → BREAKS EVEN
  Additional surplus potential: ₹500–₹700/month

4. 📈 6-MONTH SAVINGS PROJECTION
  Without changes:   ₹750/month  × 6 = ₹4,500
  With recommended cuts: ₹1,500/month × 6 = ₹9,000
  Difference: +₹4,500 over 6 months — enough for a new laptop EMI or emergency fund.

5. 💡 FINANCIAL HABIT TIP
  "Pay yourself first."
  On the day your stipend arrives, immediately transfer ₹500–₹1000 to a separate 
  savings account or a UPI piggy bank (Jar, Groww Jar). Spend only what remains. 
  Saving after spending never works — saving before spending always does.
```

**Observation:** The Advanced prompt produces a full financial report with variance analysis, risk assessment, actionable category-level cuts with alternatives, a 6-month projection, and a behavioural finance tip — matching the output quality of a real budgeting app.

---

## Application 4 — Travel Itinerary Planner

### Background

A group of friends wants to plan a 3-day weekend trip to Ooty, Tamil Nadu, on a budget, including sightseeing, food, and travel logistics.

---

### Prompt Tier 1 — Simple

```
Plan a trip to Ooty for 3 days.
```

**Output:**
```
Day 1: Arrive in Ooty
Day 2: Visit tourist spots
Day 3: Return home
```

**Observation:** Placeholder-level output. No locations, no timing, no practical value.

---

### Prompt Tier 2 — Intermediate

```
Act as a travel guide. Plan a 3-day trip to Ooty, Tamil Nadu for 3 college friends 
on a budget of ₹3000 per person. Include places to visit, approximate timings, 
and budget-friendly food options.
```

**Output:**
```
OOTY 3-DAY ITINERARY (Budget: ₹3000/person)

DAY 1 — Arrival & Local Sightseeing
  10:00 AM  Arrive at Ooty Bus Stand
  11:00 AM  Botanical Garden (Entry: ₹30)
  01:00 PM  Lunch at Hotel Dasaprakash (~₹150/person)
  03:00 PM  Ooty Lake boating (₹60/person)
  06:00 PM  Ooty Market — buy chocolates & tea
  08:00 PM  Dinner + check-in to hostel (~₹300/night)

DAY 2 — Hills & Nature
  07:00 AM  Doddabetta Peak (highest point in Nilgiris — Entry: ₹30)
  10:00 AM  Tea factory visit (free/₹50)
  01:00 PM  Lunch — local mess (~₹120)
  03:00 PM  Pine Forest photo walk (free)
  06:00 PM  Rose Garden (₹30)

DAY 3 — Coonoor & Return
  08:00 AM  Day trip to Coonoor — Sim's Park, Lamb's Rock (bus ₹30)
  12:00 PM  Lunch in Coonoor (~₹130)
  03:00 PM  Return to Ooty, shopping
  05:00 PM  Board return bus to Chennai/Coimbatore

Estimated Total Spend: ₹2600–₹2900 per person ✅ Within budget
```

**Observation:** A real itinerary emerges with timing, entry costs, and food suggestions. Practically usable for actual trip planning.

---

### Prompt Tier 3 — Advanced

```
Act as an expert travel planner specialising in budget trips in South India. 
Plan a detailed 3-day trip to Ooty and Coonoor for 3 college students from Chennai.

Constraints:
- Total budget: ₹3000 per person (including travel from Chennai)
- Travel: Overnight bus from Chennai (TNSTC/SETC preferred)
- Accommodation: Budget hostels or government guesthouses
- Food: Local Tamil restaurants, no fancy hotels
- Interests: Nature, photography, local culture, tea plantations
- One person is vegetarian — flag non-veg recommendations separately

Output format:
- Hour-by-hour itinerary for all 3 days
- Cost breakdown table (travel, stay, food, entry)
- Top 3 photography spots with best time of day
- What NOT to do (common tourist mistakes)
- Emergency contacts and nearest hospital
```

**Output:**
```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🌿 OOTY & COONOOR — 3-DAY BUDGET TRAVEL PLAN
  Group: 3 friends | Budget: ₹3000/person
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PRE-TRIP — Night before (Chennai)
  09:00 PM   Board SETC overnight bus from Chennai CMBT (Ticket: ₹450–₹550)
             Book via redBus or TNSTC website. Prefer Volvo for comfort.

──────────────────────────────────────────────────
DAY 1 — OOTY ARRIVAL + TOWN SIGHTSEEING
──────────────────────────────────────────────────
06:00 AM   Arrive at Ooty Bus Stand. Freshen up at bus stand facilities (₹10)
07:00 AM   Breakfast — Saravana Bhavan Ooty or local idli shop (~₹60/person) 🥬
08:30 AM   Check in: YHA Ooty Youth Hostel / TTDC Hotel Tamil Nadu (₹350–₹450/night)
           Drop bags, begin day

10:00 AM   Government Botanical Garden
           📸 PHOTOGRAPHY SPOT #1 — Best at 10–11 AM (soft morning light on flower beds)
           Entry: ₹30 | Duration: 90 min

12:00 PM   Ooty Lake — paddleboat or rowboat
           Entry + boat: ₹60/person | Duration: 1 hour

01:30 PM   Lunch — Hotel Shri Ganesh (100% vegetarian, South Indian thali ₹120) 🥬

03:00 PM   Ooty Bazaar Street — buy Varkey biscuits, homemade chocolates, Nilgiri tea
           Budget for shopping: ₹200–₹300

05:30 PM   Charing Cross viewpoint — sunset walk (free)

07:30 PM   Dinner — local mess near bus stand (~₹100) 🥬
           Non-veg option: Chicken biryani shops on Commissioner's Road 🍗

09:00 PM   Return to hostel. Rest.

Day 1 Spend: ~₹850/person

──────────────────────────────────────────────────
DAY 2 — DODDABETTA + TEA PLANTATIONS + PINE FOREST
──────────────────────────────────────────────────
06:30 AM   Doddabetta Peak (2637 m — highest in Nilgiris)
           📸 PHOTOGRAPHY SPOT #2 — Arrive before 7 AM for fog layers & sunrise
           Share auto from town: ₹60/person | Entry: ₹30

09:00 AM   Tea Factory & Museum (Chamraj Tea Estate or similar)
           Entry: Free to ₹50 | Buy 250g Nilgiri tea: ₹120

11:00 AM   Pine Forest — Kodanad View Point area
           📸 PHOTOGRAPHY SPOT #3 — Best 11 AM–1 PM (light through pine rows)
           Entry: Free | Auto: ₹40/person

01:00 PM   Lunch — local meals near Elk Hill (~₹110) 🥬

02:30 PM   Rose Garden (₹30 entry) — short visit

04:00 PM   Thread Garden / Wax World (optional, ₹75)

06:00 PM   Explore local market for handmade items

08:00 PM   Dinner — Willy's Coffee Pub (budget-friendly, great hot chocolate) 🥬

Day 2 Spend: ~₹650/person

──────────────────────────────────────────────────
DAY 3 — COONOOR DAY TRIP & RETURN
──────────────────────────────────────────────────
07:00 AM   Breakfast at hostel or nearby (~₹60) 🥬
07:45 AM   Take toy train OR TNSTC bus to Coonoor (Bus: ₹30 | Train: ₹35 — book in advance)

09:00 AM   Sim's Park, Coonoor (Entry: ₹30) — lush, quiet, great for portraits

11:00 AM   Lamb's Rock viewpoint — sweeping valley views (Auto from Sim's Park: ₹150 for 3)

12:30 PM   Dolphin's Nose viewpoint (10 min from Lamb's Rock by auto)

01:30 PM   Lunch in Coonoor — Hotel Blue Hills or local mess (~₹120) 🥬
           Non-veg: Mutton chops available at roadside dhabas 🍗

03:00 PM   Return bus to Ooty (₹30)
03:30 PM   Collect bags from hostel, final shopping

05:30 PM   Board return bus to Chennai from Ooty Bus Stand (₹450–₹550)

Day 3 Spend: ~₹700/person

──────────────────────────────────────────────────
TOTAL COST BREAKDOWN (per person)
──────────────────────────────────────────────────
Item                         Estimated Cost
─────────────────────────────────────────────
Bus Chennai → Ooty           ₹  500
Bus Ooty → Chennai           ₹  500
Accommodation (2 nights)     ₹  800
Food (all 3 days)            ₹  570
Entry tickets                ₹  200
Local autos / transport      ₹  250
Shopping & snacks            ₹  300
Miscellaneous buffer         ₹  150
─────────────────────────────────────────────
TOTAL                        ₹ 3,270  (slight over — cut shopping by ₹270)
WITHIN ₹3000 if:             Skip Thread Garden + reduce shopping

──────────────────────────────────────────────────
🚫 WHAT NOT TO DO — COMMON TOURIST MISTAKES
──────────────────────────────────────────────────
  ✗ Don't visit in January–February if you hate cold (temp drops to 5°C at night)
  ✗ Don't book private taxis from touts near the bus stand — overpriced by 2×
  ✗ Don't skip the toy train booking (fills up fast — book 2 weeks ahead on IRCTC)
  ✗ Don't drink unbottled water at viewpoints — stomach issues are common
  ✗ Don't leave Doddabetta after 9 AM if you want fog — it clears fast

──────────────────────────────────────────────────
🆘 EMERGENCY INFORMATION
──────────────────────────────────────────────────
  Government Hospital Ooty:   0423-244-2212
  Tourist Police Helpline:    1800-425-4747 (toll-free)
  Nearest pharmacy:           Ooty Medicals, Commissioner's Road
  Auto helpline (Ooty):       Local auto union stand at Charing Cross
```

**Observation:** The Advanced prompt delivers a professional-grade travel plan — hour-by-hour, with a cost breakdown table, photography timing advice, common mistake warnings, dietary flags, and emergency contacts. This directly rivals paid travel planning apps.

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

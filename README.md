## Habit Tracker - Product Improvement Case Study

A gamified retention redesign with rest days, a coin economy, streak freezes, and priority-driven task management.

What Is This?

This is an end-to-end product improvement prototype for a habit-tracking app, built as a case study
The prototype is a fully functional React + Vite + Tailwind app, originally built using Figma Make and iterated with custom product specs. It includes three core feature additions designed to reduce user churn at the most critical moment in the habit-tracking journey.


---
 
## The Problem
 
Habit-tracking apps are built around unbroken streaks — complete every day or your counter resets to zero. But real life isn't a perfect loop. Travel, illness, a demanding week — any of these snaps a streak. When that happens, the app offers no recovery path.
 
**Result:** users don't restart. They uninstall. One missed day triggers a permanent exit.
 
Meanwhile, urgent daily tasks (bills, deadlines) pile up with no way to surface what's critical.
 
---

## Features Built
 
### Feature 1: Weekly Goals + Rest Days
Users pre-commit to 5, 6, or 7 active days per week. Rest days are planned upfront — they show as a distinct blue ring on the calendar and **don't break the streak**. This turns flexibility into a designed feature instead of a silent excuse to quit.
 
### Feature 2: Coins + Streak Freeze Economy
A gamified reward system where users earn coins through daily habit completions and clearing urgent to-dos. Coins can be spent on **Streak Freezes** (20 coins each, capped at 2/month) — an earned safety net that protects a streak after a missed active day without removing accountability.
 
| Action | Reward |
|---|---|
| Daily habit completion | +1 coin |
| Complete urgent to-do | +1 coin |
| Day 15 milestone | +5 coins |
| Day 30 milestone | +5 coins |
| Streak Freeze cost | 20 coins |
 
### Feature 3: Priority-Based To-Do System
A three-tier task priority system (Normal / Important / Urgent) with automatic behavior:
- **Normal** — default, lives in "All Tasks"
- **Important** — yellow visual tag, still in "All Tasks" but visually distinct
- **Urgent** — red border + tag, auto-pinned to a dedicated "Urgent" section at the top of the screen
Completing urgent to-dos earns coins, tying the task system into the same reward economy as habits.
 
---
 
## Case Study Deck
 
A full **8-slide product case study** is included in the `/case-study` folder, covering:
 
1. **Cover** — Product Improvement Case Study framing
2. **Problem & Context** — What problem, who faces it, why now, why it matters
3. **Users, Goals & Data Flow** — Persona, product goals, two-track user flow
4. **Feature 1** — Weekly Goals + Rest Days (deep dive)
5. **Feature 2** — Coins + Streak Freeze Economy (deep dive)
6. **Feature 3** — Priority-Based To-Do System (deep dive)
7. **Prioritization & Tradeoffs** — 4 deliberate design decisions with rejected alternatives
8. **Impact & Next Steps** — North Star Metric, supporting metrics, NSM input tree
---

---
 
## Key Product Decisions
 
| Decision | Why |
|---|---|
| Freeze costs 20 coins, not 10 | 10 coins is too cheap (~10 days). 20 coins takes ~3 weeks — makes each freeze a real decision. |
| 2 freezes/month, not unlimited | Covers realistic disruptions without becoming a loophole. |
| Rest days ≠ free skips | Must be pre-committed during habit creation. Keeps the streak signal clean. |
| 3 priority levels, not a binary toggle | Important tasks get noticed without false alarms. Only truly urgent tasks get the red pin. |
 
---
 
## North Star Metric
 
**Weekly Active Completions per User** — the single metric that captures whether the redesign is delivering value. If rest days, coins, freezes, and priority to-dos are working, this number goes up.
 
---
 
## Interactive Prototype
 
[**View the live prototype →**](https://www.figma.com/make/6JOGotILq5U9qO67rSa1PD/p_to_so_figma?p=f&fullscreen=1)
 
---






# CGPA Planner

Know your SGPA, and plan the grades you need next. A private semester planner: add courses, credits and letter grades, and it works out your SGPA per semester, your CGPA overall, and the average grade point you need in your remaining credits to hit a target.

**Live:** https://kanishksaini-007.github.io/CGPAPlanner/

## What it does
- Semesters with courses: name, credits, letter grade. SGPA per semester, CGPA across all of them.
- Editable grading scale (default is the common 10-point S/A/B/C/D/E/F map, but colleges differ, so every row can be changed).
- Target planner: enter your goal CGPA and the credits you still have left, and it tells you the average grade point you need - and says honestly when the target is out of reach, with the best finish still possible.
- Backup and restore as JSON. Everything is saved only in your browser (localStorage). No account, no server, no tracking.

## Why I built it
GradeGoal already answers "what do I need on the final for this one subject". I kept wanting the semester-level version: how does each course pull my CGPA, and is my goal still reachable? So I built that. I am a first-year student learning JavaScript by building small tools like this.

## Tech
Plain HTML, CSS and JavaScript in a single file. No framework, no build step.

## Honest limits
- Grading letters and points vary by university. Edit the scale card to match yours before trusting the numbers.
- It computes from the grades you enter; it cannot predict what you will actually score.

Not affiliated with any university. Built by Kanishk Saini.

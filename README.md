# Arise — Daily Leveling

Arise is a task, calendar, and wellness manager built for students juggling
academics, work, and personal life. It centralizes tasks, a calendar, and
daily wellness tracking (sleep, water, exercise, meals, medication) behind a
simple account system.

## Features
- Account creation and login, with per-account data isolation
- Dashboard: today's tasks, upcoming events, weekly progress, quick-add
- Tasks: add, complete, delete, search, filter by priority
- Calendar: month view, click-to-view/add/delete events, task due-dates shown
- Wellness: sleep/water/exercise tracking, meal & medication toggles, daily
  score, 7-day chart
- Responsive layout: sidebar (desktop), icon sidebar (tablet), bottom tab
  bar (mobile)

## Architecture
Single-file front-end application (HTML/CSS/JavaScript, no build step,
no dependencies). Data is stored in the browser via `localStorage`, keyed
per account. There is currently no backend server; see "Known limitations"
below.

## Setup — run it locally
1. Clone this repository:
git clone
https://github.com/DivijaReddyVarkuti/Arise-The-Daily-Leveling-.git
3. Open `arise.html` directly in any modern browser (Chrome, Firefox,
   Edge, Safari) — no server or install step required.

## Known limitations
- Accounts and data are stored per browser/device (`localStorage`), so the
  same account will not appear on a different device or browser.
- Passwords are hashed client-side for basic obfuscation only — this is
  not production-grade security.
- Task editing, recurring tasks, notifications, and activity categories
  are not yet implemented (see Future Scope in the final presentation).

## Roadmap
- Backend + database (per original system design) for real accounts and
  cross-device sync
- Task editing and recurring tasks
- Notification/reminder system
- Activity categories and habit streaks
## Documentation
- [Initial Report — Requirements](./Initial_Report_Assignment.pdf)
- [System Design & Wireframing](./project_2_CSCI_.pdf) 

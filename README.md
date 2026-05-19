# mbsPlanner
Personal daily planning tool built for medical staffing — MBS internal use.
# MBS Daily Planner

An internal daily planning and task management tool built for MBS Locums. 
Runs entirely in the browser — no backend, no login, no dependencies.

## Features

- **Daily view** — Must Do Today (8-task cap), Follow Ups, Prospecting, Waiting On
- **Weekly tabs** — This Week, Next Week, and Last Week with day-by-day navigation
- **Hot Jobs & Hot Docs** — persistent sidebar for urgent placements and candidates
- **Scheduled tasks** — set a future date and target section; items auto-inject on the due date
- **Brain Dump** — freeform capture with one-click routing to any section
- **Defer** — push any task to the next business day automatically
- **Copy to tomorrow** — roll all incomplete items forward in one click
- **Weekly carry-over** — review unfinished items from last week on Monday morning
- **Save File** — exports a self-contained HTML file with data baked in; 
  open on any machine and your data is there

## Usage

Open `index.html` in Chrome. No install required.

Hit **💾 Save File** at the end of each day to keep a local backup 
with your data embedded in the file itself.

## Stack

Vanilla HTML, CSS, and JavaScript. Zero dependencies. Data persists 
via localStorage with file-based backup and restore.

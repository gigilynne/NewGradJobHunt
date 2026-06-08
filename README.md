# NewGradJobHunt
Interactive tool to help with planning, tracking, and job search
# Job Hunt Launchpad 🚀

A personalized, interactive job search tool built for a recent CS graduate targeting data analysis, marketing, and project management roles.

## What This Is

This is a single HTML file that runs entirely in the browser — no backend, no login, no installation required. It combines a structured job hunt plan, an AI-powered resume analyzer, a cover letter generator, and a job application tracker into one shareable tool.

## Features

### 📋 The Plan
A phase-by-phase job hunt roadmap with interactive checklists:
- **Phase 1** — Foundation (LinkedIn, GitHub, tracking setup)
- **Phase 2** — Applying (5 applications/week, recurring rhythm)
- **Phase 3** — Networking (warm connections, informational calls)
- **Phase 4** — Show Your Skills (data projects, certifications)
- **Phase 5** — Interview Prep (dossier, STAR stories, weekly practice)
- **Looking Ahead** — Path toward Project Management

Each phase includes:
- Checkable task list with progress tracking
- Shared job application tracker
- Phase-specific check-in questions
- **My Progress Notes** and **Mom's Feedback** fields

### 🔍 Resume Analyzer
AI-powered resume ↔ job description alignment tool:
- Scores alignment across 10 key requirements (1–5)
- ATS keyword match percentage (before and after optimization)
- Suggested resume edits with before/after language
- Career Compass section tailored for data → marketing → PM trajectory
- Neurodivergent fit assessment (ADHD inattentive considerations)
- **GO / NO GO / Borderline** recommendation

After analysis:
- **GO — Add to Tracker** opens a pre-filled application entry form
- **GO — Write Cover Letter** carries inputs to the Cover Letter tab
- **NO GO — Next Job** resets the analyzer for the next posting

### ✉️ Cover Letter Generator
- Paste job description + resume → get a tailored, human-sounding letter
- Fully editable before downloading
- Download as **Word (.doc)** or **PDF**

### 📋 Application Tracker (Shared Across All Phases)
Tracks every application with:
- Company, Role, Date Applied, Status, Contact, Follow-Up Date, Notes
- Color-coded status pills (Applied, Follow-Up Sent, Interview Scheduled, Offer, Rejected, Ghosted)
- Auto-flags applications 10+ days old with no response for follow-up

## How Progress Is Saved

All data saves to the **browser's localStorage** — no account or server needed.

To sync progress between devices (e.g. daughter's laptop → mom's laptop):

1. Click **⬇ Export Progress** — downloads a `.json` file
2. Send the file (text, email, AirDrop)
3. Click **⬆ Import** on the other device — restores all checkboxes, notes, and job entries

## Updating the File

When a new version of `index.html` is uploaded to this repo:
1. She refreshes the page to get the latest version
2. Her progress is preserved in her browser's localStorage
3. If major changes were made, import her exported JSON to restore everything

## Built With

- Vanilla HTML, CSS, JavaScript — no frameworks, no dependencies
- [Anthropic Claude API](https://www.anthropic.com) for resume analysis and cover letter generation
- Google Fonts (Syne + DM Sans)

## Notes

- The AI features (Resume Analyzer, Cover Letter Generator) require an active internet connection
- Progress and notes are stored locally per device — use the JSON export to share between devices
- Designed with ADHD (inattentive type) in mind: focused one-phase-at-a-time layout, clear recurring tasks, time-boxed daily rhythm

# Design Portfolio Builder Skill

A professional-grade agent skill for transforming scattered notes, sketches, and engineering logs into deep, STAR-formatted design case studies.

## 🚀 Overview

Writing a good design portfolio is hard. Most designers either write "water" (vague phrases) or forget to document the strategic visual artifacts that prove their expertise. This skill turns your AI assistant into a **Senior Product Editor** and **Visual Strategist** who interviews you to extract the most impactful details.

## ✨ Key Features

- **STAR Interviewer:** Guided deep-dives into Situation, Task, Actions, and Results.
- **Visual Strategy:** Mandatory suggestions for visual artifacts (Videos, Before/Afters, Diagrams) for *every* action.
- **Water Detector:** Automatically flags and challenges vague corporate-speak like "improved UX" or "intuitive design."
- **Hard Editing Rule:** Ensures the agent only edits what you ask, preserving your specific voice and vocabulary.

## 📦 Installation

To add this skill to your environment, run:

```bash
npx skills add [YOUR_GITHUB_REPO_URL] --skill design-portfolio-builder
```

## ⌨️ Available Commands

Once installed, you can trigger the skill's logic using these shortcuts in your chat:

- `/case-init [project-name]` — Start a new project or restore context for an existing one.
- `/case-module [name]` — Initiate a deep STAR interview for a specific theme (e.g., Discovery, UI/UX, Engineering).
- `/case-list` — Get a status report of all projects and modules in your `portfolio/` directory.
- `/case-review` — Run a holistic audit of your project to find narrative gaps and "water."

## 📁 Recommended Structure

The skill organizes your work into:
- `portfolio/[project-name]/overview.md` — Core product info and impact.
- `portfolio/[project-name]/[module].md` — Thematic STAR deep-dives.

---
Created with ❤️ for designers who ship.

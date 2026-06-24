# PE Skills Matrix — Crystal Fountains Product Engineering

Interactive skills tracking and training progress tool for the Crystal Fountains Product Engineering team.

## Live Tool

**https://crystalfountainsinc.github.io/pe-skills-matrix/**

Open the URL in any browser. No login or installation required.

---

## What It Does

- Tracks skill levels across 8 team members and 152 skills in 17 categories
- Real-time sync — changes made by one user are visible to all others within ~1 second
- Five views: Dashboard, Full Matrix, Team View, Categories, Admin
- Skill levels: Awareness → Developing → Competent → Expert
- Exposes a `window.CF_PE_SKILLS_KPI` object for integration with the PE KPI dashboard (in development)

## How to Use

1. Open the live URL above
2. Toggle **Edit Mode** (top right) to enable skill level editing
3. Click any skill badge to cycle through levels
4. Changes save automatically and sync to all users in real time

## Tech Stack

- Vanilla HTML/CSS/JS — no framework, no build step
- Firebase Realtime Database for live sync (`cf-pe-skills-matrix` project)
- GitHub Pages for hosting

## Updating the Tool

1. Edit `cf_pe_skills_matrix_v1.html` in Dropbox:  
   `02 - Crystal Fountains\23 - Product Eng AI\PE KPI's\Crystal Product Engineering Scorecard and Teirs\`
2. Copy the updated file to this repo as `index.html`
3. Commit and push — GitHub Pages redeploys automatically within ~1 minute

## Maintainer

George Ayer — george.ayer@crystalfountains.com  
Crystal Fountains Product Engineering

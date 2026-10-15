# WorkforceAI — Intelligent Workforce & Resource Planner

A React + TypeScript + Vite prototype for workload balancing, employee skills, task allocation, learning recommendations, and reports. It includes a demo sign-in screen with separate Manager and Employee entry points.

## Demo login

**Manager**
- Email: `manager@workforceai.demo`
- Password: `Manager123!`
- Access: manager navigation, workload planner, smart allocation, employee directory, skill analysis, and reports.

**Employee**
- Email: `employee@workforceai.demo`
- Password: `Employee123!`
- Choose an employee profile from the dropdown before signing in.
- Access: employee-oriented navigation for overview, projects/tasks, academy, and settings.

These credentials are for a local demo only. The sign-in is client-side and is **not secure production authentication**. Do not use real employee or confidential company data. Server-side authentication, password hashing, API authorization, and a production database are not configured.

## Requirements

- Node.js 18+ (recommended)
- npm

## Run locally on Windows

1. Extract the ZIP.
2. Open the extracted `WorkforceAI` folder in VS Code.
3. Open Terminal in that folder.
4. Run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the local URL printed by Vite (usually `http://localhost:5173`).

For a production build:
```bash
npm run build
npm run preview
```

## Features

- Responsive workforce dashboard with demonstration data.
- Employee profiles, skills and verification labels.
- Project task register and task creation.
- Workload utilization calculations and visualizations.
- Rule-based task reassignment suggestions with manager approval.
- Skill gap and learning pages.
- CSV workload report export.
- Demo data persistence in browser local storage and reset controls.
- Separate Manager and Employee demo login experiences.

## Limitations

- Uses fictional seeded demonstration data.
- Login is a front-end demo gate; it does not protect APIs or data from a determined user.
- Data is stored in the browser's local storage, not a shared server database.
- Recommendation logic is deterministic, not a connected AI model.
- Deadline/dependency validation is a prototype and requires human review.

# Personal Study Planner — Module 1 + 2 + 3

**Student:** Muhammad Uzair Khan  
**Internship ID:** ZYNVEX-CERT-1795  
**Domain:** Frontend Development

This version extends the existing Module 1 + Module 2 project in-place. The existing subject and task management interface is retained, and Module 3 adds an interactive progress dashboard.

## Module 3 additions
- Total tasks, completed tasks, pending tasks, and overall completion percentage.
- Doughnut chart for completed vs pending tasks (Chart.js).
- Subject-wise progress bars and percentages.
- Task progress table with All / Pending / Completed filters.
- Overdue pending-task labels.
- Dashboard automatically updates when tasks or subjects are added, edited, deleted, or marked complete/pending.
- Responsive layout using the existing Bootstrap styling.

## Run
1. Extract the ZIP.
2. Open `index.html` in a browser, or open the folder in VS Code and use Live Server.
3. Internet is required for Bootstrap and Chart.js CDN resources.

## Existing LocalStorage integration
The dashboard uses the same keys as Modules 1 and 2:
- Subjects: `psp_subjects`
- Tasks: `psp_tasks`

Task fields follow Module 2's existing object structure: `title`, `subjectId`, `subjectName`, `deadline`, and `status` (`pending` or `completed`). No migration is needed.

## Submission
Upload the updated `index.html`, `css/style.css`, `js/app.js`, and `README.md` to the same GitHub repository that contains the earlier modules. Check whether the internship form requests a repository link, screenshots, or both.

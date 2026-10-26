# Productivity App Alpha

This is a dependency-free, launchable prototype of the productivity app. It preserves the core idea from the existing Next.js project while presenting it as a polished mobile-style app.

## Launch

```bash
npm run dev
```

Open the URL printed in the terminal, normally `http://localhost:3000`.

You can also open `index.html` directly in a browser. The app saves changes in local storage, so refreshes keep tasks, time blocks, theme, and the selected screen.

## Prototype flows

- Home: today's briefing, work needing attention, daily plan, and focus timer.
- To-dos: real checkboxes, edit/delete icons, filters, search, subtasks, swipe-style action affordances, and drag reorder.
- Add: task or time block entry in a bottom sheet. Only a task name is required.
- Calendar: month and week views, date selection, task/event markers, and imported `.ics` events.
- Settings: theme, data export/import, and a short prototype status panel.

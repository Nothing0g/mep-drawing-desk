# MEP Drawing, Submittal & Action Tracker

A separate portfolio project for engineering coordination teams. Drawing / Desk provides a revision-aware drawing register, a design-query and action log, and a two-week look-ahead for HVAC, electrical, plumbing, firefighting, and BIM coordination.

## Included

- Drawing register with drawing numbers, revisions, disciplines, submittal dates, reviewers, and approval statuses
- Search and filters for drawing metadata, discipline, and status
- Coordination log covering design queries, dependencies, decisions, owners, due dates, and closure status
- Two-week look-ahead cards for control points and upcoming handoffs
- New submittal form that adds a record to the in-browser register
- Responsive engineering-desk layout using Roboto and Roboto Mono
- Clearly labeled sample portfolio data for demonstration

## Run locally

```bash
python3 -m http.server 3001
```

Open `http://localhost:3001`.

This is a static case-study app. The sample records live in `app.js` and can be connected to Excel, an API, or a managed database later.

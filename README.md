# internal-ai-agent-needs

Internal AI agent needs board — a lightweight tool to identify and track AI agent
opportunities across internal divisions.

- `index.html` — the board (viewer). Loads its data from `data.json`.
- `data.json` — the data store. Edit it directly or use the backend editor.
- `backend/` — minimal static editor: edit/add rows, add tables, then download
  the updated `data.json` and commit it. No server needed; git is the persistence layer.
- `catalog/` — archived v1 AI agents catalog.
- `list-view/` — archived v2 list-view catalog.

Deployed on Vercel from `main`.

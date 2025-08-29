# AMS – Agency Management System Starter

Minimal starter repo for AMS. Open in VS Code, build with Copilot.

## Stack
- **Backend:** C# (.NET 8, LLBLGen, SQLite)
- **Frontend:** React (TypeScript, Vite)
- **Docs:** Product spec + API notes

## Folder Structure
- `api/` – C# backend
- `web/` – React frontend
- `docs/` – Product + API documentation

## How to Run

### API (backend)
```bash
cd api/Ams.Api
dotnet run
```
- Runs Minimal API with stub endpoints.
- See `api/Ams.Api/README.md` for details.

### Web (frontend)
```bash
cd web
npm install
npm run dev
```
- Runs React app with `/dashboard` and `/settings`.

## Sample curl requests
```bash
curl http://localhost:5000/health
curl http://localhost:5000/ams/metrics/monthly
curl http://localhost:5000/ams/agents
curl http://localhost:5000/projects
curl http://localhost:5000/ams/settings/logo
```

## Developer Notes
- Use TODOs in files for next steps.
- LLBLGen entities are placeholders — regenerate later.
- SQLite DB file: `api/Ams.Api/App_Data/ams_dev.db`
# API Notes

Endpoints (stubs):

- `GET /health` – Health check
- `GET /ams/metrics/monthly` – Q/P/B by month
- `GET /ams/agents?search=&role=&status=` – Agent metrics
- `POST /projects` – Create project
- `GET /projects?search=&status=` – List projects
- `POST /quotes/pollution/request` – Create quote request
- `GET /quotes/pollution/requests/:id` – Get request
- `POST /quotes/pollution/requests/:id/quote` – Add quote
- `GET /quotes/pollution/requests/:id/quotes` – Compare quotes
- `POST /quotes/pollution/:quoteId/bind` – Bind quote
- `POST /ams/settings/logo` – Upload logo
- `POST /ams/settings/colors/extract` – Extract palette

Stub handlers return demo/static data for now.

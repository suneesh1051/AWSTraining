# Pipeline Class Demo

A tiny app we use to learn CI/CD pipelines from scratch, one day at a time.

- **backend/**: a small API with two endpoints, `/api/health` and `/api/hello?name=...`
- **frontend/**: one web page that calls the backend

There are no extra libraries to install. Everything uses plain Node.js (version 22 or newer).

## Run it on your computer

```bash
cd backend
npm test        # run the backend tests
npm start       # start the API on http://localhost:4000
```

In a second terminal:

```bash
cd frontend
npm test        # run the frontend tests
npm run build   # copy the page into frontend/dist
```

Then open `frontend/index.html` in your browser while the backend is running.

## Branches

Each class day has a branch with that day's finished pipeline files. If you fall behind, compare your work with it.

| Branch | What it adds |
|---|---|
| `main` | The app only, no pipeline yet |
| `day-01` | `.github/workflows/hello.yml`, our first workflow |

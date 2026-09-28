# Contractor demo UI (Vercel)

WhatsApp-style demo for **contractors** helping **બાંધકામ શ્રમિક** with registration, applications, and scheme awareness.

Standalone project (same UI code as `frontend/`, contractor copy only).

## Deploy on Vercel

1. Import this repo.
2. Set **Root Directory** to `frontend-contractor`.
3. Framework: **Vite** — Build: `npm run build`, Output: `dist`.
4. Deploy.

## Local dev

```bash
cd frontend-contractor
npm install
npm run dev
```

Open **http://localhost:5175** (port in `vite.config.ts`).

Workers app: `frontend/` → port **5173**.

# Goal Tracker V1

Personal daily/weekly goal tracker built with React + TypeScript + Vite.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Current persistence

V1 uses browser `localStorage`, so it works immediately without accounts or backend credentials. Data is local to each browser/device.

## Deploy

Push this folder to GitHub and import the repository into Vercel. Build command: `npm run build`; output directory: `dist`.

The included web manifest enables standalone installation behavior. For a fully installable offline PWA, add a service worker in the next deployment pass.

## Next infrastructure step

To synchronize laptop and Android data, replace the localStorage persistence adapter with Supabase. The UI/domain model is already separated enough to do this without redesigning the product.

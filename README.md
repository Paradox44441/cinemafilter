# CinemaFilter

Local-only movie content filtering, powered by community timestamp guides. No video ever leaves the browser.

## Run locally

```
npm install
npm run dev
```

Opens at http://localhost:5173

## Before deploying

1. Open `src/App.jsx` and set `FEEDBACK_EMAIL` to a real inbox (search for `feedback@example.com`).
2. Optionally set `FEEDBACK_FORM_URL` to a Google Form link once you've created one.

## Deploy to Vercel (free)

1. Push this folder to a new GitHub repository.
2. Go to https://vercel.com → "Add New Project" → Import the repo.
3. Vercel auto-detects Vite — leave build settings as default (`npm run build`, output dir `dist`) — click Deploy.
4. You'll get a live `*.vercel.app` URL in about a minute. Every future push to the repo auto-redeploys.

## Add a real backend later (Supabase)

Free tier, no credit card: https://supabase.com → New Project. Once created, grab the Project URL and anon key from Settings → API and hand them over to wire up real community submissions, cross-device persistence, and a built-in admin table editor for the movie library.

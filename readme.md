# GariAudit – Vehicle Truth Layer

Professional vehicle inspection platform. Trust-as-a-Service for the used car market.

## Deploy to Vercel (Free)

### Option 1: GitHub + Vercel (Recommended – no CLI)

1. Go to **[vercel.com](https://vercel.com)** and sign in with GitHub.
2. Click **Add New** → **Project**.
3. Import **mul734320-web/GariAudit_Web** from your GitHub.
4. Leave settings as default (Vercel auto-detects static HTML).
5. Click **Deploy**.

Your site will be live at `https://gariaudit-web.vercel.app` (or similar).

### Option 2: Vercel CLI

```bash
npm i -g vercel
cd "GariAudit_Stitch_AI Studio"
vercel
```

Follow the prompts to log in and deploy.

## Local Development

Open `index.html` or `landing page.html` in a browser, or use a local server:

```bash
npx serve .
```

## Structure

- **index.html** – Redirects to landing page
- **landing page.html** – Main marketing hub
- **site architecture.html** – Site map
- All subpages linked via navigation dropdowns

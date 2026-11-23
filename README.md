# Oremari Limo — Deploy Guide

## Files
- `index.html` — the entire site (open directly in a browser to test locally)
- `hero.jpg` — add your Suburban photo here before deploying

## Add your hero photo
Drop a photo named exactly `hero.jpg` into the same folder as `index.html`.
- Resize to ~1400px wide, compress to under 200 KB (use squoosh.app)
- The site already falls back gracefully to a black background if the file is missing

---

## Deploy to Vercel (recommended — free, instant HTTPS)

1. Go to [vercel.com](https://vercel.com) and sign in (or create a free account)
2. Click **Add New → Project**
3. Choose **"Deploy from your computer"** or look for the drag-and-drop option on the dashboard
4. Drag the entire `oremari-limo` folder onto the Vercel drop zone
5. Leave all settings as defaults — click **Deploy**
6. Vercel gives you a URL like `oremari-limo.vercel.app` instantly
7. Optional: connect a custom domain (e.g. `oremari.limo`) under **Settings → Domains**

---

## Deploy to Netlify (alternative — also free)

1. Go to [netlify.com](https://netlify.com) and sign in
2. On the dashboard, scroll to **"Sites"** and find the drag-and-drop box:
   > *"Drag and drop your site folder here"*
3. Drag the `oremari-limo` folder onto that box
4. Netlify deploys in seconds and gives you a URL like `random-name.netlify.app`
5. Optional: rename the site under **Site settings → Site name**
6. Optional: connect your custom domain under **Domain management**

---

## Test the form before going live

1. Open `index.html` directly in Chrome or Safari (double-click it)
2. Fill out the quote form completely
3. Click **Send My Quote Request**
4. Check that the success message appears: *"Thanks, [Name]! Your quote request is in."*
5. Check the inbox you registered with Web3Forms — submissions go there

> **Important:** Web3Forms requires an internet connection even for local testing because it hits their API. The form won't work if you're offline.

---

## Quick edits cheat sheet

| What to change | Where in index.html |
|---|---|
| Phone number | Search for `+19204006406` and `(920) 400-6406` |
| Email address | Search for `info@oremari.limo` |
| Web3Forms key | Search for `f57bc0b5` |
| Business name | Search for `OREMARI LIMO` |
| Tagline | Hero section — "Premium Bay Area limo service" |
| Success message | Search for `success-heading` |
redeploy test
ikk
ez kuze



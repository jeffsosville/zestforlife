# Zest for Life

Landing page for **Zest for Life — Catering & Meal Prep**, Village of Skaneateles, NY.
Chef Zest Dougherty · 908-403-5591

Static site (plain HTML/CSS, no build step). Intended domain: **skancatering.com**

## Structure
```
index.html        # the whole page
images/           # optimized photos
vercel.json       # caching + clean URLs
```

## Deploy to Vercel

**Option A — Git (recommended)**
1. Create a new GitHub repo and push this folder:
   ```bash
   git init
   git add .
   git commit -m "Zest for Life landing page"
   git branch -M main
   git remote add origin https://github.com/<you>/zest-site.git
   git push -u origin main
   ```
2. In Vercel: **Add New → Project → Import** the repo.
3. Framework preset: **Other**. Build command: none. Output dir: `./` (leave default).
4. Deploy, then add the domain **skancatering.com** under **Settings → Domains**.

**Option B — CLI**
```bash
npm i -g vercel
vercel          # preview
vercel --prod   # production
```

## TODO before launch
- Point the **Contact us** button (`#book` section) at a real form or `mailto:`.
- Wire the **newsletter** field to your email provider (Instantly / Mailchimp / etc.).
- Swap the domain in the footer link if not using skancatering.com.

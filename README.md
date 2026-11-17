# Zest for Life

Landing page for **Zest for Life — Catering & Meal Prep**, Village of Skaneateles, NY.
Chef Zest Dougherty · 908-403-5591

Static site (plain HTML/CSS, no build step). Intended domain: **skancatering.com**

## Structure
```
index.html          # home: services, senior meals, menu, chef, service area, FAQ, contact
catering.html       # /catering
private-chef.html   # /private-chef
meal-prep.html      # /meal-prep (incl. #seniors)
styles.css          # shared styles
robots.txt, sitemap.xml
vercel.json         # caching + clean URLs (/catering serves catering.html)
```

Contact: email link uses hello@skancatering.com (forward it to her private Gmail at the
domain's DNS/email-forwarding settings, so the Gmail never appears on the site). Text/call: 908-403-5591.

## Updating the menu
Edit the "Menu" section in index.html (search for `id="menu"`).

## After deploying
- Submit https://skancatering.com/sitemap.xml in Google Search Console.
- Link the site from the Google Business Profile.

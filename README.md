# Parent/Caregiver EdTech Survey

A single-page survey for parents and caregivers to share their perspectives on technology and screen time in schools. Built as a static site (just `index.html`) that submits responses to a Google Apps Script endpoint.

Originally created by [PA Unplugged](https://paunplugged.org) for Pennsylvania families.

## Forking This Project

1. **Set up your own Google Apps Script** to receive form submissions (Google Sheets + Apps Script web app).
2. **Update `GOOGLE_SCRIPT_URL`** in `index.html` (line ~1547) with your own endpoint URL.
3. **Update the survey content** — the text, links, and metadata reference PA Unplugged and Pennsylvania. Customize these for your organization/region.
4. **Deploy anywhere** — this is a static site. Vercel, Netlify, GitHub Pages, or any web server will work.

## Deployment

No build step required. Just serve `index.html`.

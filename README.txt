OSOL AI LANDING PAGE - DEPLOY PACKAGE

Upload the CONTENTS of this folder (index.html at the site root) to any static host.
Easiest options (all free): Cloudflare Pages, Netlify (drag-and-drop), Vercel, GitHub Pages.

Steps (Netlify drag-and-drop, ~5 min):
1. Unzip. Go to app.netlify.com/drop and drag the folder in.
2. Domain settings > Add custom domain > osolai.com. Follow the DNS instructions at your registrar.
3. HTTPS turns on automatically.

BEFORE GOING LIVE, search index.html for these and replace:
- Elements with class "ph" (dashed boxes): founder bio/photo, LinkedIn, email, phone, social links,
  Privacy Policy / Terms links, pilot details [5] [confirm] [6 months] [15 or more].
- Calendly: see the HTML comment in the #audit section; paste your inline-widget embed.
- Only the real Calendly URL/handle goes there; remove the dashed placeholder card when embedded.

AFTER GOING LIVE:
- Submit https://osolai.com/sitemap.xml in Google Search Console.
- Create a 1200x630 social share image and add <meta property="og:image" content="https://osolai.com/assets/og.png">.
- Fonts (Caladea, Inter) load from Google Fonts; self-host them later for max speed/privacy.
- GSAP 3.15.1 is self-hosted in /assets. Review GSAP's license terms at gsap.com/standard-license.

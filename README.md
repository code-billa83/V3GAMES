# V3 Games - Website

Free browser games website built with plain HTML, CSS and JavaScript. No framework, no build step.

## Folder structure
```
v3games/
├── index.html          Home
├── games.html          All games list
├── games/
│   ├── snake.html
│   ├── memory-match.html
│   └── reaction-tap.html
├── services.html
├── about.html
├── contact.html
├── privacy.html
├── 404.html
├── css/style.css       Styles (responsive)
├── js/main.js          Mobile menu
├── images/og-cover.svg Social share image
├── sitemap.xml
└── robots.txt
```

## Step 1: Change your domain (IMPORTANT)
Search and replace `https://www.yourdomain.com` and `hello@yourdomain.com` in all files
(VS Code: Ctrl+Shift+H / Cmd+Shift+H). Also update `sitemap.xml` and `robots.txt`.

## Step 2: Upload / host
Any free or paid static host works: Netlify, Vercel, GitHub Pages, Cloudflare Pages, or cPanel / shared hosting (upload into `public_html`).
Make sure the site is served over HTTPS.

## Step 3: Set up Google (for ranking)
1. Go to https://search.google.com/search-console and add your domain.
2. Verify ownership (DNS or HTML file method).
3. Submit `https://yourdomain.com/sitemap.xml`.
4. Use "URL Inspection" to request indexing for the home page and each game page.
5. Create a Google Business Profile too if you have a physical office.

## Step 4: Check speed and SEO
- PageSpeed Insights: https://pagespeed.web.dev
- Mobile-Friendly Test: https://search.google.com/test/mobile-friendly
- Rich Results Test (checks the schema data): https://search.google.com/test/rich-results

## Ranking honesty
No website is guaranteed to reach #1 on Google. Ranking depends on competition, content quality,
backlinks, and time. To improve your chances:
- Publish new games and blog posts regularly.
- Get genuine links from other game blogs, communities and directories.
- Keep pages fast, mobile-friendly and useful.
- Pick low-competition keywords first (e.g. "free reaction time test online"), then aim for bigger ones.
- Track results in Google Search Console and improve pages that get impressions but few clicks.

## Editing
- Colours and fonts: edit the variables at the top of `css/style.css`.
- Brand name: change `BRAND` in the build notes, or find and replace "V3 Games".
- Add a new game: copy `games/snake.html`, change the title, description, canvas script and FAQs, then add it to `sitemap.xml`, `games.html` and the footer.

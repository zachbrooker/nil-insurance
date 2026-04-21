# NIL Insurance — Static Site

Multi-page static website for World Insurance Associates' NIL and incentive insurance practice. Built as plain HTML + CSS with no build step or backend — fully platform-agnostic.

## Structure

```
index.html              Home page
nil-insurance.html      NIL Insurance product page
styles.css              Shared stylesheet
```

Additional product and company pages (contractual-bonus.html, prize-contest.html, why-world.html, team.html, contact.html) to follow.

## Design

- Typography: Geist + Geist Mono (loaded via Google Fonts)
- Palette: Near-black background with World's brand colors (navy, teal, green) as accents
- No JavaScript dependencies, no build step

## Deployment

This is a pure static site. It will deploy to any static host:
- GitHub Pages
- Netlify
- Cloudflare Pages
- Vercel
- Any standard web server

For the contact form to accept submissions, a form-handling service (Formspree, HubSpot, or similar) or a simple backend endpoint is required.

## Editing

All content is in the HTML files. No templating language, no compilation — edit HTML directly.

## License

Content and design belong to World Insurance Associates.

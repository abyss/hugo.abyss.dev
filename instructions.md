# Hugo + Sveltia CMS

Build a complete Hugo website for a fictional Magician/Mentalist named "Victor Ashveil".
This is a dark-aesthetic, professional marketing site. The site will be hosted on GitHub
Pages at the custom subdomain hugo.abyss.dev.

## Stack
- Hugo (latest, no theme — build from scratch)
- Tailwind CSS (via Hugo Pipes or PostCSS)
- Sveltia CMS
- GitHub Actions for CI/CD deploy to GitHub Pages

## Design
- Dark aesthetic: near-black background (#0a0a0f), deep purple/navy accents, warm gold highlights
- Display font: Cormorant Garant (Google Fonts)
- Body font: Inter (Google Fonts)
- Professional, atmospheric, approachable — not cheesy Halloween-style
- Subtle CSS animations where appropriate (scroll reveals, hover effects)
- Fully responsive

## Pages
1. **Home** — Hero with tagline, brief intro, featured shows teaser, testimonials strip, CTA
2. **About** — Bio, philosophy, headshot placeholder
3. **Shows** — Cards for each show type (Corporate Events, Private Parties, Stage Shows, Virtual)
4. **Blog** — List of posts with excerpts
5. **Contact** — Booking inquiry form (static HTML, action pointing to Formspree as placeholder)

## Blog Posts (create 2 arbitrary example posts as markdown content files)
- Post 1: "The Psychology Behind Misdirection" — a short thoughtful post about how
  misdirection works psychologically
- Post 2: "What to Expect When You Book a Mentalist" — a practical guide for clients

## Sveltia CMS
- Configure Sveltia CMS at /admin (static/admin/index.html + config.yml)
- Use GitHub OAuth backend (not Netlify Identity — no Git Gateway dependency)
- Collections for: blog posts, shows, testimonials, site settings
- Fields appropriate for a performer's marketing site

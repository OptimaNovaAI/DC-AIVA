# DC's Future of Work + AI

Public resource page for the **OCTO AI Public Listening Session** panel on Workforce Development and AI Literacy, held May 19, 2026 at West End Library in Washington, DC.

🌐 **Live:** [dc-ai.optimanova.ai](https://dc-ai.optimanova.ai)

## About

This dashboard is the QR-code destination distributed during the panel. It houses:

- The five DC-specific facts framing the panel
- Bios for the moderator and three panelists
- Active DC programs in AI literacy and workforce development
- Audience-segmented action steps (residents, business, nonprofits, gov staff)
- Connection points for continued engagement
- Full source citations

## Stack

- Static HTML, single file, no build step
- Hosted on GitHub Pages
- Custom subdomain via CNAME
- Fonts: Fraunces (display) + Public Sans (body)
- Mobile-first, accessible (WCAG AA contrast), no tracking

## Deployment

1. Push to `main` branch
2. GitHub Pages serves from `/` (root)
3. CNAME file routes `dc-ai.optimanova.ai` to GitHub Pages
4. DNS: CNAME record `dc-ai` → `optimanovaai.github.io`

## Credits

Designed and built by [OptimaNova AI](https://www.optimanova.ai) in partnership with the DC Office of the Chief Technology Officer.

Panel team: Joe Paul (moderator), Beth Noveck, Matthias Oschinski, Chelsea Kirkland.

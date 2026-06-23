# playhalcyonreach.com

Public placeholder for **Halcyon Reach** — a 2D solo-pilot space MMO. Single-page static
site served via GitHub Pages at <https://playhalcyonreach.com>.

Edit `index.html`, push to `main`, Pages redeploys. All visuals are pure CSS/SVG — no
shipped art assets (the nebula, planet, and starfield are generated), so nothing here
depends on the game's licensed art.

## Notes

- Custom domain is pinned by `CNAME`. Apex (`playhalcyonreach.com`) is primary; `www`
  redirects to it.
- The `Private Alpha` strip fetches `halcyon-reach/halcyon-drift`'s latest release via the
  GitHub API. While that repo is private the call 404s and the badge stays bare, which is
  correct; it lights up once releases are public.
- Type: Bricolage Grotesque (display) / Hanken Grotesk (body) / JetBrains Mono (readouts).

# berketayfunakseki.com

Source for my portfolio site — **[berketayfunakseki.com](https://berketayfunakseki.com)**.

A single hand-written page: no framework, no build step, served by GitHub Pages.

## What's on it

- **Recruiter / Engineering mode** — one toggle swaps plain-language case studies for architecture diagrams, design decisions and lessons learned.
- **Live terminal** in the hero — `help`, `ls`, `open <project>`, `neofetch`, `cv`, `sudo hire-me`.
- **Job-description matcher** — paste a JD and see which of its technologies are in my stack. Runs in the browser; nothing is sent anywhere.
- Case studies for every public project, an experience timeline, my thesis (difference-in-differences on 21 Italian regions), and the CV served as JSON.
- Light/dark theme (follows the system, remembers your choice), keyboard and screen-reader friendly, respects `prefers-reduced-motion`.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | the whole site — markup, styles and scripts |
| `BerkeTayfunAksekiCV.pdf` | current CV |
| `404.html` | not-found page |
| `og-image.png` | link-preview image (1200×630) |
| `favicon.svg`, `apple-touch-icon.png` | icons |
| `robots.txt`, `sitemap.xml` | search engines |
| `CNAME` | custom domain |

## Run locally

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

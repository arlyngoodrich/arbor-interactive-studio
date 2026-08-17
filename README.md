# Arbor Interactive Studio

The V1 public home for Arbor Interactive Studio: a small, independent studio
building games, useful software, and the occasional weird little idea.

This is intentionally a plain static site. It is built from one HTML page, one
stylesheet, and a small identity asset. There is no framework, package manager,
backend, analytics, or runtime dependency.

## Local preview

Open `index.html` directly in a browser, or serve the repository with any
static file server. For example, from PowerShell:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

The intended deployment model is GitHub → Cloudflare Pages.

- Repository: `arlyngoodrich/arbor-interactive-studio`
- Framework preset: **None** / **No framework**
- Root directory: leave blank (the repository root)
- Build command: `exit 0`
- Build output directory: `.` (the repository root)
- Environment variables: none
- Custom domain: `arborinteractivestudio.com`

Cloudflare DNS, nameservers, and custom-domain configuration are intentionally
outside this repository and are not managed here.

## Content notes

- TinyConnect links to its verified public GitHub repository and `v0.1.2`
  release.
- No Arbor itch.io link is included until a public destination is verified.
- `assets/brand-sheet.jpg` is the supplied V1 brand reference. The production
  page uses the small SVG tree mark derived from that accepted identity so the
  site does not ship the full reference sheet as a logo asset.

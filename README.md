# CareNumerix Tools

Static site for a **Tools** section on [carenumerix.com](https://www.carenumerix.com/).

Suggested live paths:

- `https://www.carenumerix.com/tools/`
- `https://www.carenumerix.com/tools/housekeeping-benchmark`

This package cannot write to the existing CareNumerix host. Publish these files, then add a **Tools** link next to Services / About / Insights / Contact.

## What is included

| Path | Page |
|---|---|
| `tools/index.html` | Tools landing |
| `tools/housekeeping-benchmark.html` | Interactive housekeeping study-vs-peer model |
| `tools/styles.css` | Shared styles |

The housekeeping tool keeps the Emerson vs five-peer demo as default data. Users can edit inputs, change which row is Facility A, add peers, and print. Calculations stay in the browser.

## Publish options

### A. GitHub Pages (this repo)

1. Settings → Pages → Deploy from branch `main` / root.
2. Site will be `https://timothyjamesjalbert-design.github.io/carenumerix-tools/tools/`.
3. Optional: add a custom domain and a CNAME, or reverse-proxy `/tools` from carenumerix.com to this Pages site.

### B. Drop into the existing CareNumerix site

Copy the `tools/` folder to the web root so the URLs above resolve. Add one nav item: Tools → `/tools/`.

### C. Netlify / Cloudflare Pages

Point the project at this folder. Set the publish directory to the repo root.

## Disclaimer

Illustrative working model. Not an audit, valuation, or cost-report opinion.

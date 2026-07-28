# RudraHealth AI — Provider Dashboard

A front-end prototype of the **RudraHealth AI Provider Dashboard / Portal** — a clinical admin
panel for Opioid Use Disorder (OUD) recovery care teams. It's a self-contained static site
(HTML + CSS + vanilla JS) with Chart.js for graphs and [Lucide](https://lucide.dev) icons.

## Contents

| Path | Description |
|------|-------------|
| `index.html` | The full application (patient app + provider portal, single file) |
| `assets/chart.umd.min.js` | Chart.js library (charts) |
| `assets/css2` | Web-font `@font-face` definitions |
| `assets/Logo.png` | Brand logo |

## Running locally

No build step. Either open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Web fonts and icons load from CDNs, so an internet connection gives the intended look
(the design degrades gracefully to system fonts offline).

## Notes

- This is a **design/UX prototype** — all patient data shown is mock/sample data, not real PHI.
- The provider portal is embedded as an `iframe` (`srcdoc`) inside `index.html`.

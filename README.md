# CATNAV — Project Page

Project website for **CATNAV: Cached Vision-Language Traversability for Efficient Zero-Shot Robot Navigation**
(Aditya Potnis, Francisco Affonso, Shreya Gummadi, Naveen Kumar Uppalapati, Girish Chowdhary — UIUC FRESH).

- **Paper / arXiv:** https://arxiv.org/abs/2603.22800
- **Video:** https://x.com/aditya_potnis/status/2038397173620977962

## Structure

```
index.html        # the whole page (HTML + embedded CSS + small JS)
static/images/    # figures
static/pdf/       # paper PDF
```

Static site — no build step or dependencies.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Or just open `index.html` in a browser.

> The X video embed and the BibTeX copy button need an HTTPS context to work fully; both work when served (and on GitHub Pages), but may be limited on `file://`.

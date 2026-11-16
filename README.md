# First Time China — a practical guide

Static site. No build step at runtime, no external assets, no JavaScript dependencies.

Pages: index, apps, money, transport, connected, eating, family, changelog.

Source of truth for the HTML: `.openclaw/tmp/china-guide/` (css.py, pages_a.py, pages_b.py,
pages_c.py, build.py). Run `python3 build.py` to regenerate every page into this folder.

Editing rules:
- English copy; Simplified Chinese for mainland names, Traditional for Hong Kong/Macau/Taiwan.
- Every page carries a "Checked <month year>" badge — update it when a page is re-verified.
- Record substantive changes in changelog.html.
- No remote fonts, images, scripts or iframes: the host applies a strict CSP.

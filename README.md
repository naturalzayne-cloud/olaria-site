# Olaria by Jen — Website

The marketing website for **Olaria by Jen**, a brand by Jennifer Nxumalo offering calm,
practical money and career tools: guides, editable templates, a physical journal, a debt
subscription tool, and the Olaria budget app. Brand promise: *money with purpose*.

This is a multi-page static website (plain HTML and CSS, no build step or dependencies),
designed to be published with GitHub Pages and connected to the brand's Wix store for
products, bookings, payments, and the members-only Debt Payoff Map.

## What's in this repo

| File / folder | Purpose |
|---|---|
| `index.html` | **Home** — hero, the three doors, pillars, featured library items, the Debt Payoff Map, the app, Clarity Call, CV editing, and about |
| `olariaapp.html` | **Olaria App** landing page (app features, method, and the Privacy & Support links needed for the App Store submission) |
| `library.html` | **The Library** — the shop page listing all digital and physical products |
| `style.css` | Shared brand stylesheet used by every page |
| `img/` | Brand photography, product images, and the logo |
| `README.md` | This file |

No frameworks, no JavaScript build, no install — it runs as-is in any modern browser.

## How navigation and links work

- **Between the three site pages** (Home, Olaria App, Library): links are *relative*
  (`index.html`, `olariaapp.html`, `library.html`), so they work wherever the site is hosted.
- **Everything that lives on Wix** — product checkouts, the Clarity Call, CV editing, the
  members-only Debt Payoff Map, About, Privacy, and Support — links out to absolute URLs on
  `olariabyjenn.com`.

Destination links used:

- CV Editing service → `/career-services`
- Every Cent Financial Journal → `/product-page/2024-every-cent-fiancial-journal`
- Make 2024 Your Best Year → `/product-page/make-2024-your-best-year`
- The Career Bundle → `/product-page/the-career-bundle`
- CV Templates by Post → `/product-page/cv-templates-by-post`
- Get Hired → `/product-page/get-hired`
- Get Shortlisted → `/product-page/get-shortlisted`
- Clarity Call → `/claritycall`
- Debt Payoff Map (members' tool) → `/debt-payoff-map`

## Running it locally

Open `index.html` in any browser. That's it.

## Publishing with GitHub Pages

1. Upload `index.html`, `olariaapp.html`, `library.html`, `style.css`, `README.md`, and the `img/` folder to the repository (keep the `img` folder intact so the images load).
2. Go to **Settings → Pages**.
3. Set the source to the `main` branch (root) and save.
4. GitHub publishes the site at `https://<username>.github.io/<repository>/`.

## Before going live — checklist

- **Publish the Debt Payoff Map page on Wix.** The menu links to `olariabyjenn.com/debt-payoff-map`; that page must be published (and kept restricted to paid subscribers) for the link to work.
- **Confirm product slugs.** The checkout links above must match the real Wix product URLs.
- **Make 2024 Your Best Year** uses the Money Audit workbook image (`img/money_audit.jpg`) as a stand-in — swap it if a dedicated image exists.
- **Checkout & payments** are handled entirely on Wix. This site never collects card details.

## Disclaimer

Olaria by Jen provides educational information, guides, and tools. It is not financial,
tax, or legal advice and does not guarantee employment outcomes.

---

© 2026 Jennifer Nxumalo. All rights reserved.

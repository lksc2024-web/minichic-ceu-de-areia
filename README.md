# MiniChic — Céu de Areia

**Project type:** Fashion collection storefront redesign preview. The HTML document identifies itself as a *prévia de redesign* (redesign preview); this README does not claim a commissioned or launched client engagement.

## Experience

The repository's `index.html` contains a fashion-oriented landing experience for the *Céu de Areia* collection, with:

- A scroll-based hero section and WebGL canvas (`#heroGL`), plus a non-3D fallback
- A product runway (`#passarela`) with product details and navigation
- Editorial collection storytelling, new arrivals, a product listing, and a store-visit section
- Product-specific WhatsApp inquiry links
- Responsive CSS and visible keyboard-focus styling

The interface uses the **Marcellus** and **Jost** fonts via Google Fonts. The page includes `app.js` and an `img/` directory. These observations come from the tracked HTML; they are not independent browser-test results.

## Technical structure

| File or directory | Role |
| --- | --- |
| `index.html` | Semantic content, inline CSS, page layout, product content, and WebGL containers |
| `app.js` | JavaScript used by the interactive page; a detailed code review is still recommended |
| `img/` | Referenced image assets |

**Technologies evidenced:** HTML, CSS, JavaScript, responsive layouts, WebGL-oriented page integration.

## Local preview

From the repository root:

```bash
python -m http.server 8080
```

Open `http://localhost:8080`. An HTTP server is preferable to opening the HTML directly because scripts and assets may be subject to browser restrictions.

## Project preview

[Repository-linked Vercel preview](https://minichic-ceu-de-areia.vercel.app/) — deployment availability and content have not been independently checked.

## Verification and rights

- Test interactions, mobile layouts, reduced-motion behavior, and fallback rendering in a real browser before claiming production readiness.
- Confirm product prices, availability, brand permissions, photography rights, and any third-party asset licenses before public commercial use.
- Do not describe this preview as a delivered client project without confirmation.
- No measured conversion, accessibility, or performance results are asserted here.

# Amanat Digital Studio

Website for Amanat Digital Studio (Quetta, Balochistan) — mobile software repair, QR digital menus, websites & landing pages, and SEO.

Single-file static site (`index.html`). No build step needed.

## Order button
Each service page has an order box. "Send order on WhatsApp" opens WhatsApp with the customer's order pre-written, sent to `923308363433`.

To change the number, edit `WA_NUMBER` in `index.html` (digits only, country code first).

## Deploy on GitHub Pages
1. Push this folder to a GitHub repository.
2. Repo **Settings → Pages**.
3. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site goes live at `https://<username>.github.io/<repo-name>/`.

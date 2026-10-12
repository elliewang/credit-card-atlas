# CardFlow Atlas — Credit Card Origination & Application Management

**Designed for Wenting Wang.** A free, responsive GitHub Pages portfolio demo for a banking credit-card origination workflow.

## Features
- Executive dashboard: application volume, risk flags, pending review and approval rate
- Application create, view, update, delete, search and status filtering
- Nine-stage lifecycle from intake to servicing and analytics
- Risk and manual decision review queue
- Three fictional card products
- Customer communication: save local communication logs; launch email, phone and SMS apps (does not send automatically)
- Portfolio reports, CSV exports and JSON backup/import
- Rule-based chatbot that reads browser-local demonstration records
- Responsive navigation and mobile layout

## Publish to GitHub Pages (free)
1. Create a public GitHub repository named `cardflow-atlas`.
2. Upload `index.html`, `styles.css`, `app.js`, `.nojekyll` to the **root** of the repository.
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, `main`, `/(root)` and Save.
5. Your website URL is typically `https://YOUR_USERNAME.github.io/cardflow-atlas/`.

No Node.js, build step, backend, API key or paid hosting required.

## Data and security warning
**Portfolio demonstration only, not a banking or credit application production system.** All sample people and records are fictional. LocalStorage is not secure for real customer data. Do **not** enter SSNs, dates of birth, real credit scores, bank account numbers, identity documents or other private financial information. No authentication, encryption, actual KYC/AML verification, credit bureau lookup, underwriting, disclosures, consent tracking, credit decision, account issuance, or real notifications are implemented. Risk labels are illustrative and do not determine approvals. An operational banking implementation requires security, privacy, fair-lending, regulatory, accessibility and audit reviews. The built-in chatbot is rules-based, not connected to a language model or external services.

## Files
- `index.html`: page shell, sidebar navigation and chatbot UI
- `styles.css`: responsive styling
- `app.js`: local data, application workflow, controls, reports, and chatbot
- `.nojekyll`: serves the static site directly on GitHub Pages

© 2026 Wenting Wang — demonstration use.

# Crete-More Controlled Documents

GitHub Pages front end for controlled technical bulletin issuance and recipient review.

## Architecture
- GitHub Pages hosts only the UI.
- Supabase enforces issuance, signature acceptance, IP logging, 5-open limits, event logs, signature PDF generation, and protected document delivery.
- The confidential technical document is **not** stored in this repository.

## GitHub Pages
Enable Pages from the `main` branch / repository root.

Expected URLs:
- Recipient: `https://stallcon.github.io/crete-more-controlled-documents/?t=<token>`
- Admin: `https://stallcon.github.io/crete-more-controlled-documents/admin.html`

## Important limitation
Browser controls can block printing/download/copy and common screenshot shortcuts, but no ordinary browser can absolutely prevent OS-level screenshots or external cameras.

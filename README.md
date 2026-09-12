# Crete-More Controlled Documents

GitHub Pages front end for controlled technical bulletin issuance and recipient review.

## Current protected report revision
The protected technical bulletin was revised September 2026 to be less formula-driven and more explanatory, with added emphasis on the physical mechanism that converts moisture-state and material-substitution errors into **concrete yield change**. The live GitHub Pages viewer retrieves this protected report content from the Supabase secure backend after recipient acceptance.

## Architecture
- GitHub Pages hosts only the UI.
- Supabase enforces issuance, signature acceptance, IP logging, 5-open limits, event logs, signature PDF generation, and protected document delivery.
- The confidential technical document is **not** stored in this repository.

## GitHub Pages
- Recipient: `https://stallcon.github.io/crete-more-controlled-documents/?t=<token>`
- Admin: `https://stallcon.github.io/crete-more-controlled-documents/admin.html`

## Important limitation
Browser controls can block printing/download/copy and common screenshot shortcuts, but no ordinary browser can absolutely prevent OS-level screenshots or external cameras.

# Navarro's Paint and Body — Website Demo

A responsive, multi-page business website built with HTML5, CSS3, and vanilla JavaScript.

## Run locally
Open `index.html` in a modern browser. For a more production-like local preview, use VS Code Live Server or run `python -m http.server` from this folder.

## Client configuration
Edit `js/config.js` first. Business name, colors, contact details, social URLs, map URL, hours, and service cards are centralized there. Update the JSON-LD structured data in `index.html` when business details change.

## Pages
- `index.html` — home
- `about.html` — about and approach
- `services.html` — service overview
- `gallery.html` — responsive gallery with keyboard-accessible lightbox
- `reviews.html` — supplied customer review excerpts
- `faq.html` — accessible single-open accordion
- `contact.html` — contact details, map, validation, and mailto-based form
- `privacy.html`, `terms.html` — starter policy pages requiring owner/legal review

## Important pre-launch checklist
1. Confirm phone number, email, business hours (especially weekend hours), services, and social accounts with the owner.
2. Replace illustrative Unsplash photos in `js/main.js` and the page image URLs with actual business photos approved for use. The gallery explicitly identifies sample imagery.
3. Review the three customer review excerpts and their source links for exact wording and permission.
4. The contact form is front-end only: it validates and opens a prefilled email draft. It does not submit to a server. Connect a trusted form endpoint or backend if direct submissions are required.
5. Confirm the supplied phone number and email. The website uses `+1 210-328-1113` as provided.
6. Confirm and replace the opening hours. Public listings conflict with the supplied weekend hours, so weekend hours are intentionally shown as requiring confirmation.
7. Review the privacy and terms pages, and have the business owner approve the content before publishing.
8. Check external image licensing, optimize local copies, and configure a production domain and analytics only with owner approval.

## Images
`images/logo.png` is the logo supplied with the project. Remaining photos are remote illustrative Unsplash images and need to be replaced with approved business photography for a final client launch.

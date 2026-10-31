# Evan Kinsel portfolio

Open `dist/index.html` in a browser. No install or build step. Tailwind CSS loads from its browser package through jsDelivr, so an internet connection is required. All content, layout, and interaction code is in one HTML file. System fonts avoid additional font dependencies.

## Files
- `dist/index.html`: complete portfolio, styles, interactions, and asset comments.
- `portfolio-copy.md`: editable copy extracted from the completed page.

## Production deployment
Tailwind Play CDN is intended for development, not production: https://tailwindcss.com/docs/installation/play-cdn
This template preserves the requested CDN workflow. For production hardening, generate a static Tailwind stylesheet and replace the CDN script with a link to that stylesheet. The hosted version currently uses the requested CDN template.

## Assets and content
The Morehouse laser research poster appears as an image preview. The only poster link goes to its open-science DOI record. No resume is bundled because the supplied resumes contain the academic average the user asked to omit.

The GitHub connector verified the public repository URLs evankinsel/magplotter and evankinsel/lidar. Supplied repository descriptions inform the feature copy; no code audit is implied. Honors Scholar is the designation supported by the supplied resumes.

QuantCAD content uses process-level descriptions and resume-level outcomes. The 9,000+ thermal-test measurements and 61% gradient improvement are separate achievements. No company dataset, plot, dimension, field-strength value, or magnetic geometry is included. The presentation does not assert formal corporate clearance or declassification.

## Accessibility and interactions
Semantic landmarks, a skip link, visible focus states, reduced-motion support, native details disclosure, anchor navigation, and an Escape-dismissable mobile menu. Contact links open the visitor's email client or professional profiles. No contact form, analytics, storage, or server dependency.

## Validation
Content checks: unique IDs, valid internal anchors, no academic average or em dashes. Desktop visual inspection, mobile 390px iframe layout inspection, internal section navigation, native disclosure, and mobile menu open/close verified in the browser.

## GitHub Pages
Extract this ZIP, then upload index.html, README.md, and the assets/ folder to the root of your GitHub repository and commit them. Do not upload the ZIP as a single repository file. In repository Settings > Pages, publish from the main branch and the /(root) folder. The portfolio will be served by GitHub Pages; future commits update it.

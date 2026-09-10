# GLOBAL MINO — design and implementation handoff

Use the included homepage as the visual reference for building the full GLOBAL MINO website. Preserve its typography, palette, editorial spacing, photography treatment and visual hierarchy. This is an implemented homepage sample, not a complete website.

Live reference: https://global-mino-homepage.dmamediai7.chatgpt.site

## Included files

- `dist/index.html`: complete six-section homepage sample.
- `dist/style.css`: styling and responsive layouts.
- `dist/script.js`: navigation, scroll reveals, project placeholder dialogs and image credits.
- `dist/assets/`: local photographs used in the sample.
- `original-design-brief.txt`: the original detailed homepage design requirements.
- `homepage-preview.png`: hero screenshot only; use the live reference and HTML to review the complete page.
- `server.cjs`: optional dependency-free Node preview server. Run `node server.cjs`, then open http://127.0.0.1:4173.

## Full website to build

1. Home `/`
2. About Global Mino `/about`
3. Operations `/operations`
4. Countries: Sudan `/countries/sudan`, Cameroon `/countries/cameroon`, Central African Republic `/countries/central-african-republic`
5. Services: overview `/services`, Gold Mining `/services/gold-mining`, Mineral Exploration `/services/mineral-exploration`, Mining Consultancy `/services/mining-consultancy`
6. Projects `/projects` and Project Detail `/projects/[slug]`
7. Contact `/contact`

These paths are proposed implementation routes. The current sample uses section anchors and placeholder project dialogs. Replace those with the appropriate real routes when implementing the full site. The attached original brief requested homepage-only work as the first stage; this handoff is for extending that reference to the full site.

## Visual requirements

- Premium, institutional, Africa-focused mining company aesthetic.
- Exactly six homepage sections: Hero; About; Operations; Services; Featured Projects; Contact CTA with integrated Footer.
- No maps, GIS interfaces or dashboards.
- Palette: #101419, #1B1D20, #B88A2B, #C89D48, #F7F5F0, #D8D1C4, #FFFFFF.
- Current fonts: Libre Caslon Display for headings and DM Sans for body/navigation.
- Large editorial serif headings, restrained gold accents, cinematic photographs, asymmetric country panels, alternating service layouts.
- Desktop target 1440px; mobile target 390px. Maintain keyboard accessibility, visible focus, semantic landmarks, reduced-motion support and readable contrast.
- Preserve working mobile menu, project browsing, contact links and clear navigation. Test all routes and screen sizes.

## Content integrity

Do not invent reserves, production, revenue, employee counts, licenses, concessions, contracts, certifications, years of operation or investment values. Project information has not been provided: retain clear placeholders until supplied. Do not invent a functioning contact-form backend or claim that a message was sent when it was not.

The current GM wordmark is a provisional typographic treatment, not an official supplied logo. Photographs are illustrative, not proof of Global Mino-owned projects. Sudan and Cameroon landscape images identify those locations; other technical images include Alaska and Hawaii, and must not be presented as photographs of company operations in Africa. Replace with approved company imagery when available. Preserve the source credits and applicable photo licenses in the homepage credits dialog. Cropping/resizing does not remove attribution obligations.

## Provided company contact

Dr. Hashim Sulieman — Chief Executive Officer

+353 85 159 0630

hashim@globalmino.com

globalmino.com

Alsiteen St, Building No. 29, Alriyad, Khartoum, Sudan

## Recommended working sequence

1. Run and inspect the provided homepage before changing implementation.
2. Reuse the current visual direction and extract shared header/footer and design tokens into the chosen stack.
3. Implement the requested page structure without fabricated corporate content.
4. Replace sample anchors and placeholder dialogs with real routes where appropriate.
5. Verify desktop/mobile layouts, links, accessibility, image loading and forms before deployment.

No hosting credentials or accounts are included. The reference site is publicly viewable. Arrange deployment separately in the user's chosen hosting account.

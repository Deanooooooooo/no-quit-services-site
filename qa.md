# QA — No-Quit Services

## Gate 1 — Source / Fact Audit

PASS with notes.

- Name, category, address, phone, email, intro copy, and license/personnel line sourced from the rendered public Facebook profile.
- Sprinkler/install/repair copy sourced from Facebook public snippets and visible posts.
- No prices, warranties, certifications beyond `Jim Malone LI #27032`, review counts, or guarantees invented.
- Exact working hours unavailable; site uses "Call for current availability" instead of fixed hours.
- Testimonials unavailable: Facebook shows not yet rated and no real review text was accessible. No fake review cards were created.

## Gate 2 — Visual Result / Work Image Audit

PASS.

- Real Facebook work images were extracted through rendered browser access after direct curl failed.
- The site uses real work-in-progress sprinkler/lawn images. No stock images are used.
- Image placements preserve subject integrity and use source-matching aspect ratios.

## Gate 3 — Testimonial Audit

PASS with source limitation.

- Facebook rendered "Not yet rated (0 Reviews)".
- Search snippets did not expose real testimonial names/text, except an inaccessible Maptons snippet with a dynamic/review-style line. No testimonial cards are shown.

## Gate 4 — Copy Audit

PASS.

- Copy is specific to sprinkler systems, irrigation repair/install, landscaping and Canyon/Amarillo-area service.
- No placeholder, lorem ipsum, invented claims, or audit language appears in visitor-facing copy.

## Gate 5 — Link / Schema / SEO Head Audit

PASS local.

- Phone, email, Facebook, and Google Maps links are present.
- Title, meta description, robots, canonical, OG tags, Twitter card, one H1, and LocalBusiness schema are present.
- Canonical/OG URL use intended GitHub Pages URL and can be updated if Dean chooses a different deployment URL.

## Gate 6 — Image / Layout Audit

PASS.

- All image paths exist locally.
- No duplicate visible placement of the same image except logo brand reuse.
- Gallery uses mixed portrait/landscape layouts matched to source orientation.
- Desktop and mobile screenshots checked after CSS adjustments: no text clipping, no incoherent overlap, and no missing project images.

## Gate 7 — Map / Local SEO Audit

PASS.

- Bottom map/local SEO block is present directly above the footer.
- Exactly one visible map navigation CTA appears in the contact/map block.
- Map iframe uses business name + full address query.
- A readable address fallback is shown behind the iframe in case Google map tiles load slowly or are blocked.

## Gate 8 — Responsive Visual QA

PASS.

- Playwright full-page screenshots generated for desktop and mobile:
  - `qa-desktop.png`
  - `qa-mobile.png`
- Mobile hero type was tightened after initial QA to prevent narrow-screen clipping.

## Gate 9 — Live QA

BLOCKED until Dean approves public deployment.

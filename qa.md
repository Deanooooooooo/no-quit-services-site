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
- Re-ran image research across Facebook photo pages, mobile photo page, and two public group posts after the first version shipped with weak/repeated image use.
- Saved and inspected 50 image responses, deduped to the usable business-photo pool, and documented final decisions in `image-map.md`.
- The site uses real sprinkler/lawn/landscape project images. No stock images are used.
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
- No duplicate visible placement of any project image. Logo reuse is limited to brand/header/proof/footer.
- Old `assets/project-01.jpg` through `assets/project-04.jpg` references were removed; current visible image set is unique.
- Gallery uses natural 4:3 landscape frames plus one true 3:4 portrait frame. The vertical trench photo is no longer forced into a decorative crop.
- Desktop and mobile screenshots checked after the redesign: no text clipping, no incoherent overlap, no missing project images, and no old project asset references.

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

PASS after redeploy required.

- Public deployment approved by Dean in Telegram.
- GitHub Pages live URL: `https://deanooooooooo.github.io/no-quit-services-site/`
- After this image redesign is pushed, verify HTTP 200 and live HTML contains No-Quit Services plus the new `hero-finished-sprinklers.jpg` asset reference.

# Image Map — No-Quit Services

Source profile: `https://www.facebook.com/p/No-Quit-Services-100092019264324/`

Additional public sources checked:
- `https://www.facebook.com/100092019264324/photos/`
- `https://m.facebook.com/100092019264324/photos/`
- `https://www.facebook.com/groups/amarillobuyselltrade/posts/3462951960553985/`
- `https://www.facebook.com/groups/amarillobuyselltrade/posts/3437780903071091/`
- Search queries for `"No-Quit Services" Canyon TX Facebook photos`, phone number, and business/category variants.

Candidate audit artifact: `research/fb-candidates/contact-sheet.jpg`

## Business Facts

- Business name: No-Quit Services
- Category: Landscape Company / sprinkler system installation and repair
- Location: 307 Country Club Dr, Canyon, TX 79015
- Phone: +1 806-646-0574
- Email: cduke6424@gmail.com
- Public Facebook copy: "Over 35 years in the landscape business. When we leave, you'll know a professional has been there."
- License/personnel line found on Facebook: Jim Malone LI #27032; Christopher Duke / Jim Malone appear in public post snippets.
- Facebook snippets also mention: "Everything in Landscape", "If its in the Landscape, we do it", "Sprinkler Systems installation and repair", "We don't charge unless we fix it."
- Reviews: Facebook shows not yet rated. No real testimonial text found in accessible public sources during this build.
- Hours: Facebook rendered "Open now", but exact hours were not exposed. Do not show fixed hours.

## Final Visible Images

### `assets/logo.jpg`
- Source: Facebook profile image.
- Subject: No-Quit Services logo/mark.
- Dimensions: 949x960.
- Classification: logo / branding.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 4, relevance 5, uniqueness 5.
- Placement: header brand mark and hero proof badge only.

### `assets/hero-finished-sprinklers.jpg`
- Source: Facebook group post image, saved from `candidate-21.jpg`.
- Subject: finished green lawn with sprinkler coverage along a brick home.
- Dimensions: 2048x1536, landscape 4:3.
- Classification: hero candidate / irrigation proof.
- Scores: realness 5, sharpness 5, crop safety 5, aspect fit 5, relevance 5, uniqueness 5.
- Placement: hero image only. Chosen because it shows the finished outcome and tests cleanly in a 4:3 hero frame.

### `assets/finished-stone-walkway.jpg`
- Source: Facebook group post image, saved from `candidate-42.jpg`.
- Subject: completed low-maintenance front yard with stone walkway and rock beds.
- Dimensions: 1280x960, landscape 4:3.
- Classification: finished landscape / gallery feature.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 5, relevance 5, uniqueness 5.
- Placement: gallery lead landscape card, natural 4:3.

### `assets/lawn-trench-path.jpg`
- Source: Facebook page photo, saved from `candidate-33.jpg`.
- Subject: narrow trench/work path through lawn.
- Dimensions: 960x1280, portrait 3:4.
- Classification: service/action.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 5, relevance 4, uniqueness 5.
- Placement: portrait gallery card only. Kept vertical to avoid the previous bad crop.

### `assets/side-yard-repair.jpg`
- Source: Facebook page photo, saved from `candidate-31.jpg`.
- Subject: side yard sprinkler/sod work with sprinkler running and crew visible.
- Dimensions: 1280x960, landscape 4:3.
- Classification: service/action.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 5, relevance 5, uniqueness 5.
- Placement: gallery landscape card.

### `assets/backyard-irrigation-test.jpg`
- Source: Facebook page photo, saved from `candidate-32.jpg`.
- Subject: backyard sprinkler test near walkway and play set.
- Dimensions: 1280x960, landscape 4:3.
- Classification: service/action.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 5, relevance 5, uniqueness 4.
- Placement: gallery landscape card.

### `assets/landscape-layout-work.jpg`
- Source: Facebook group post image, saved from `candidate-44.jpg`.
- Subject: yard layout/edging work in progress.
- Dimensions: 1280x960, landscape 4:3.
- Classification: service/action / process.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 5, relevance 4, uniqueness 5.
- Placement: gallery landscape card.

### `assets/coverage-lawn-sprinklers.jpg`
- Source: Facebook group post image, saved from `candidate-28.jpg`.
- Subject: sprinkler coverage across shaded lawn.
- Dimensions: 2048x1536, landscape 4:3.
- Classification: irrigation proof / support image.
- Scores: realness 5, sharpness 4, crop safety 5, aspect fit 5, relevance 5, uniqueness 4.
- Placement: separate support image in the "Why call" section.

## Rejected / Not Used

- `candidate-01.jpg`: logo duplicate, already represented by `assets/logo.jpg`.
- `candidate-02.jpg` through `candidate-10.jpg`: 414px/480px Facebook grid thumbnails, rejected in favor of higher-resolution originals.
- `candidate-29.jpg` and `candidate-30.jpg`: same subject as `hero-finished-sprinklers.jpg`; rejected to avoid duplicate subject repetition.
- `candidate-40.jpg` and `candidate-41.jpg`: useful work-process photos but weaker than selected gallery set and one has a visible finger/awkward bottom edge.
- `candidate-43.jpg`: finished walkway variant, rejected because it repeats `finished-stone-walkway.jpg` and includes a distracting dog in the foreground.
- Existing `assets/project-01.jpg` through `assets/project-04.jpg`: removed from the public repo after the redesign to avoid stale duplicate assets.
- Facebook static UI images, cookie images, Meta icons, ad/media blobs, and unreadable `.kf` responses: rejected as non-business assets.
- Generic image-search landscaping photos: rejected because real No-Quit Facebook work photos were available.

## Layout Decisions

- No visible image file is reused across page sections.
- Landscape photos use 4:3 frames matching their source dimensions.
- The trench photo uses a 3:4 portrait card; it is not forced into a wide or decorative crop.
- The gallery uses a strict two-part layout: a 16:9-width lead row where the 4:3 landscape and 3:4 portrait resolve to the same height, followed by three equal 4:3 landscape cards.
- Mobile stacks each image full-width with the same source-matching aspect ratios.

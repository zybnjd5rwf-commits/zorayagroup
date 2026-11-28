# ZORAYA Group website preview

This branch is the review build for the ZORAYA Group website restoration.

- Git branch: `website-restoration-preview`
- Cloudflare Pages project: `zorayagroup-site`
- Preview alias: https://website-restoration-preview.zorayagroup-site.pages.dev
- Production branch: `main`

## Production protection

No production files, DNS records, SSL/TLS settings, security settings, redirect rules, or Cloudflare production configuration were changed. Only this preview branch is being updated. Do not merge or publish without Ben's separate approval.

## Preview-only indexing protection

All HTML pages use `noindex,nofollow`; this branch's `robots.txt` disallows crawling. These protections must be reviewed before any approved production release.

## Pages in this preview

- Home
- About
- Services
- Industries
- Hotels
- Palaces
- Villas
- Apartment Projects
- Office Projects
- Selected Projects
- Hotel Transformation insight
- Contact

The homepage links to the five sector pages. The sitemap includes all twelve HTML pages.

## Brand and project assets

- Original user-supplied full ZORAYA artwork is accessible in the Library as `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024). The preview header uses a proportional web-delivery copy at `images/zoraya-logo.webp`; the source artwork remains untouched. The root `favicon.png` is the matching 64 × 64 Z emblem used for browser tabs.
- The Luxury Palace project photograph from the user-supplied archive is available as `images/luxury-palace-dubai-2026.webp` and is shown on the selected-projects page.
- Dubai Hills Project | Dubai, UAE — 2025 is a joint project. Its recovered source video carries a visible “Blanc” watermark; preserve it if the video is integrated.
- Luxury Palace Project | Dubai, UAE — 2026 is a joint project.
- Palm Jumeirah Villa | Dubai, UAE — 2026 is ZORAYA's own project.
- Palm Jumeirah Majlis | Dubai, UAE — 2026 is a joint project.
- No unrelated stock or generated imagery is presented as completed ZORAYA project work.

## Remaining before production release

1. The hotel transformation article no longer embeds third-party photographs. Neutral placeholders remain until approved project photography or rights-cleared commissioned imagery is available.
2. Restore the Dubai Hills source video and poster from the recovered archive, preserving the visible “Blanc” watermark. The source video is not yet integrated into the website.
3. Restore approved photographs for Palm Jumeirah Villa and Palm Jumeirah Majlis when available. Do not substitute unrelated stock or generated images.
4. Review all pages at desktop and mobile sizes, including logo rendering, favicon, contact links, image loading, HTTPS, redirects and navigation.
5. Check the hotel article's technical and regulatory wording with the project's appointed consultants before using it as a compliance claim. The article correctly states that 60-minute fire-rated doors are not automatically required at every door.

## Current status

This is a content and navigation preview, not a production-ready release. The branch has not been published to the live site. Browser-level visual QA and Cloudflare preview deployment checks remain outstanding.


## Restoration updates — 17 November 2026

- The recovered website ZIP was inspected. It is an earlier two-page version (home and completed projects) with a small project asset set. The current preview branch remains the fuller twelve-page site; the ZIP is used as a source for verified project media rather than replacing the newer site structure.
- The approved full ZORAYA artwork is available in the Library as `Zoraya Group Luxury Marble Logo(1).png`. The preview uses a matching web-optimized copy in every page header; the separate 64 × 64 Z emblem in `favicon.png` is used for browser tabs.
- Added the recovered Dubai Hills 2025 project-video still to the project gallery. The visible “Blanc” watermark is preserved and disclosed; the full video remains archived but is not yet embedded.
- Palm Jumeirah Villa (ZORAYA project) and Palm Jumeirah Majlis (joint project) remain correctly attributed. Their cards now clearly state that project photography is still to be added.
- Added a working telephone link on the Contact page and a canonical URL to the hotel transformation article.
- Removed all Google Tag Manager and direct GA4 scripts from this preview branch only. This prevents staging visits from being recorded in the live GA4 property. The production branch and production tracking remain untouched.
- Added the approved artwork favicon reference consistently across all twelve HTML pages.

## Current verification

Static source checks confirm all twelve pages have titles, descriptions, viewport metadata, preview-only noindex directives, mobile media queries, and image alt text where images are used. WhatsApp and email links are present; the Contact page now also has a `tel:` link. Live browser rendering, actual mobile-device layout, and HTTP-to-HTTPS/redirect behavior could not be independently verified because the preview host is not accessible to the current browser inspection service. Third-party imagery has been removed from the hotel transformation article; homepage reference photography remains explicitly labelled illustrative and not project work.


## Production HTTPS and redirect audit — read only

Checked the live `zorayagroup.com` zone and Pages project without changing settings:

- Both `zorayagroup.com` and `www.zorayagroup.com` are attached to the production Pages project.
- SSL mode is `Full`; TLS 1.3 is enabled; Automatic HTTPS Rewrites is enabled.
- `Always Use HTTPS` is currently **off**.
- The minimum TLS version is currently `1.0`.
- No Cloudflare redirect Rulesets or legacy Page Rules were found for this zone.
- No DNS, SSL, security, redirect, or production deployment settings were changed. The canonical URLs in the site currently prefer `www.zorayagroup.com`.

These live settings require explicit approval before any changes are made. The preview remains on the separate Cloudflare Pages preview hostname.


## Restoration updates — 18 November 2026

- The requested archive path `/mnt/data/files/Zoraya-Group-Website-Updated.zip` was not present in this automation runtime, so it could not be re-opened in this pass. The 17 November archive inspection notes above remain the recorded comparison; the current twelve-page preview branch was used as the working source.
- Standardised primary navigation across all twelve HTML pages: Home, About, Services, Industries, Projects, Insights, Specialist Partners and Discuss a Project. Added wrap behaviour for narrower screens.
- Updated all twelve pages to use the matching square Z emblem in `/favicon.png`; the full wordmark remains in the page headers.
- Expanded Services with site coordination and handover, clearer installation and door-to-door delivery scope, and a written-quotation caveat for customs, delivery and site services.
- Added the full Hong Kong business address to Contact.
- Clarified on the homepage that MD Interior Design & Trading is an independent company, is not owned by or part of ZORAYA GROUP, and contracts and delivers its own agreed scope.
- Removed the third-party hotel photographs from the Hotel Transformation article and replaced them with clear placeholders for approved project photography or rights-cleared commissioned images.
- Static source review confirms common navigation, favicon references, page titles/descriptions/canonicals, preview noindex directives, contact-link formats and no external image URLs remaining in the Hotel Transformation article.
- Browser-level mobile rendering and live HTTPS/redirect behaviour remain unverified in this environment because external DNS resolution and preview-host access are unavailable. No production settings or files were changed.


## Restoration QA — 18 November 2026 (latest pass)

- Current preview branch head before this update: `e86fa61a19870360adaa48e9f9abfefc1ce54678`; latest successful Cloudflare preview deployment: `9ece9d7e-6510-487a-8542-c2031a3063c5`, built from that head.
- Static source audit covered all 12 HTML pages. Each has a page title, meta description, canonical URL, viewport metadata, preview-only `noindex,nofollow`, one H1, and descriptive alt text for each inline image.
- All 12 pages use the same primary navigation. Local file references, in-page/cross-page anchors and duplicate IDs were checked; no broken local references, missing anchors or duplicate IDs were found.
- Contact targets are present in source: email and WhatsApp links on the relevant pages, plus a `tel:+85255754850` link on Contact. The targets were syntax-checked; actual browser click-through remains unverified.
- Services content covers furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, 3D design and visualisation via independent specialist providers, project coordination, installation arrangements and door-to-door delivery. Customs, installation and site services remain subject to the written project scope.
- Project attribution remains explicit: Luxury Palace and Dubai Hills are joint projects; Palm Jumeirah Villa is a ZORAYA project; Palm Jumeirah Majlis is a joint project. Two real project visuals are currently available. Villa and Majlis cards remain clearly marked for photography rather than using unrelated imagery. The Blanc watermark on the Dubai Hills still is preserved.
- The exact user-supplied full logo remains available in the Library as `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024). The header uses the proportional web-delivery copy at `images/zoraya-logo.webp`; the source artwork is untouched. The square Z emblem is used for the favicon.
- The requested ZIP path `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in this runtime and no ZIP was found in the Library listing. The earlier archive inspection notes above remain historical; the archive could not be independently re-opened in this pass.
- Browser-level rendering and HTTP/HTTPS redirect checks remain unverified. Cloudflare Browser Rendering reported a network/DNS connection failure for the preview host, and this runtime could not resolve the preview or raw GitHub hosts. Cloudflare confirms the preview deployment itself completed successfully.
- The preview branch and `main` are divergent: preview is 113 commits ahead and 31 behind main. No merge or rebase was performed; the preview-only changes remain isolated.
- No production files, deployment, DNS, SSL/TLS, security, redirect settings or public profiles were changed.


## Follow-up QA — 18 November 2026

- Preview branch head at the start of this follow-up: `fa456cec19866a48f1770a8b74fcad475a1b106c`. Cloudflare's latest successful preview deployment at that point was `5f458347-b5a9-4a1e-b08a-1d0ea231d49d`, built from the same commit.
- Homepage copy now explicitly includes 3D visualisation through independent specialist providers. The design-planning step clarifies that 3D concepts and visual presentations are coordinated through independent specialists where requested.
- Industries now lists Retail & Showrooms as an industry. The previous generic “Specialist packages” tile was removed from the industry list.
- The completed-projects page metadata now says “project experience involving ZORAYA GROUP” and explicitly identifies ZORAYA projects and joint collaborations, avoiding any suggestion that every displayed project is solely owned by ZORAYA.
- Preview access is protected by the existing Cloudflare Access application “zorayagroup-site - Cloudflare Pages” for `*.zorayagroup-site.pages.dev`. Its current allow policy lists `ben.dsg@icloud.com`. A direct request to the latest deployment URL returned the Cloudflare Access sign-in page rather than the website. This is why unauthenticated desktop/mobile visual QA and browser click-through could not be completed. No Access policy was changed.
- Current read-only Cloudflare zone settings for `zorayagroup.com`: Always Use HTTPS = On; Automatic HTTPS Rewrites = On; SSL mode = Full (certificate status active); minimum TLS version = 1.2. The Always Use HTTPS setting reports a modification timestamp of `2026-11-18T02:38:12Z`; these settings were not changed by this restoration work.
- No custom redirect ruleset or legacy Page Rule was found. The apex HTTPS URL returned ZORAYA page HTML whose canonical URL points to `https://www.zorayagroup.com/`. The actual HTTP redirect status and apex-to-www redirect behaviour remain unverified; the crawler received a 403 and the browser-rendering content endpoint did not expose response headers.
- The current GitHub comparison shows preview `115` commits ahead and `31` commits behind `main`. The branches remain intentionally unmerged.
- The recovered ZIP at `/mnt/data/files/Zoraya-Group-Website-Updated.zip` remains unavailable in this runtime and was not found in the Library. The exact full logo source remains available in the Library and untouched; the site uses the matching web-delivery copy. Only the verified Luxury Palace and Dubai Hills project visuals are present; Villa and Majlis photos are still outstanding.
- No production branch, production deployment, DNS, SSL/TLS, Access, security, redirect settings or public company/social profiles were changed by this work.


## Restoration QA — 19 November 2026

- Preview branch head before this documentation update: `f33486b98fd35816c4631ed2def4aab8977d0d66`. The prior latest successful preview deployment was `26dbec54-282c-4780-b298-8c2f3565e7bb`, built from `b92767125c5be87bdcba1d90718b4a5cae32dc96`.
- Cloudflare Pages project configuration was rechecked read-only: production branch remains `main`; preview deployment inclusion is restricted to `website-restoration-preview`. The latest production deployment remains `21329fdf-8259-4429-b22f-c07768a59e44` from `2ba88009bc46c19f0f28fadb25a289f3e67b8f3a`. No production configuration or files were changed.
- GitHub comparison currently reports preview `122` commits ahead and `31` behind `main`. The branches remain divergent; no merge, rebase or force update was performed.
- The exact approved source artwork remains available in the Library as `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024). It was visually compared with the preview's `images/zoraya-logo.webp` delivery copy; the source PNG remains untouched. All 12 HTML pages reference the same full-logo asset and `/favicon.png`; the latter is a 64 × 64 Z mark consistent with the approved artwork. The unused `favicon.webp` is not referenced by any page.
- The homepage Organization JSON-LD was corrected to expose the actual logo/image URL, `https://www.zorayagroup.com/images/zoraya-logo.webp`, instead of omitting the logo field.
- Static source audit covered all 12 HTML pages: each has a title, meta description, canonical URL, viewport metadata, preview-only `noindex,nofollow`, exactly one H1, and descriptive alt text for each inline image. All pages share the same eight-link primary navigation. No broken local file references or in-page/cross-page anchors were found.
- Contact link syntax is present: email and WhatsApp targets across the relevant pages, plus `tel:+85255754850` on Contact. Actual browser click-through remains unverified.
- Services source covers furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, 3D design and visualisation through independent specialists, project coordination, installation arrangements and door-to-door delivery, with scope caveats. Home, About and Services clearly identify MD Interior Design & Trading as an independent company, not owned by or part of ZORAYA.
- Project attribution remains: Luxury Palace Project — joint; Dubai Hills Project (2025) — joint; Palm Jumeirah Villa (2026) — ZORAYA's own project; Palm Jumeirah Majlis (2026) — joint. The project page currently shows the user-supplied Luxury Palace visual and a Dubai Hills video still with its visible Blanc watermark retained. Villa and Majlis cards remain explicit photography placeholders.
- Prior conversation records confirm that approximately 100 Palm Jumeirah Villa photographs and a Majlis image were supplied earlier. Those original photo files are not present in the currently accessible conversation/library file set or connected Dropbox search results in this run. Other accessible images include unrelated screenshots and illustrative/capability concepts; none were substituted for the Villa or Majlis project photography.
- The requested archive `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is absent from this runtime and was not found in the Library or Dropbox. The earlier 17 November archive-inspection notes remain historical; the ZIP could not be reopened and independently compared during this pass.
- Browser-level rendering, actual mobile-device testing, live WhatsApp/email/telephone click-through and HTTP/HTTPS redirect checks remain unverified. The preview hostname is protected by the existing Cloudflare Access application for `*.zorayagroup-site.pages.dev`, with `ben.dsg@icloud.com` on its allow-list; the browser inspection service and this runtime cannot complete that authenticated session. Responsive CSS is present, but this is not a substitute for visual device testing.
- Open Graph and Twitter image metadata are inconsistent: only some pages currently define `og:image` and `twitter:image`. A properly sized, approved share image should be prepared before production release; no stock or illustrative image has been presented as completed ZORAYA work to solve this.
- No production branch, production deployment, DNS, SSL/TLS, Access, security, redirect settings, or public company/social profiles were changed.


## Restoration update — 20 November 2026

- Replaced the homepage hero's third-party illustrative stock interior with the verified Luxury Palace Project image already used on the Selected Projects page. The caption identifies Dubai, 2026 and the project's joint status.
- Added the Library reference image associated with the Palm Jumeirah Majlis as `images/palm-jumeirah-majlis-visualisation.webp`. The card labels it as a 3D visualisation reference, not a completed-site photograph; the project remains attributed as a joint project and completed-site photography is still pending.
- The exact requested website archive `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in this runtime, and an exact-name Dropbox search returned no result. A separate Library archive, `ZORAYA_Palace_Website_Images_4(1).zip`, was inspected and contains four palace interior JPEGs. These are treated as visualisation assets, not verified completed-site photographs.
- The Library image `zoraya group villa .png` was inspected, but prior user context does not explicitly link that specific file to the Palm Jumeirah Villa project or confirm publication suitability; it has not been assigned to that project.
- The exact approved full logo remains available in the Library as `Zoraya Group Luxury Marble Logo(1).png`. The original PNG remains untouched; the existing preview continues to use its established web-delivery copy.


## Restoration QA — 21 November 2026

- The requested archive `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in this runtime. The current conversation attachments and Library inventory do not contain that exact file, and an exact-name Dropbox search returned no result. The earlier 17 November archive inspection remains historical and could not be repeated against the exact archive during this run.
- A separate Library archive, `ZORAYA_Palace_Website_Images_4(1).zip`, was inspected. It contains four palace interior JPEGs. These are treated as visualisation material, not verified completed-site photography, and were not added to the completed-project gallery.
- The Library PDF `Al Hokair-Villa_ID_Renders.pdf` was inspected: it is a 37-page villa interior-design presentation carrying Arabian Architecture / Abolnour attribution. It is not confirmed as the Palm Jumeirah Villa project and was excluded from ZORAYA's completed-project imagery.
- The candidate image `zoraya group villa .png` and collage `JVC_Majlis_Combined.jpg` were visually inspected. Their filenames and visible content do not establish that they are the Palm Jumeirah Villa or Palm Jumeirah Majlis project photographs. They were not published or reassigned.
- The exact approved source logo `Zoraya Group Luxury Marble Logo(1).png` is available in the Library (1536 × 1024). The original PNG was inspected and left untouched. The preview continues to use its existing proportional web-delivery copy at `images/zoraya-logo.webp`.
- Standardised Open Graph and X/Twitter metadata across all twelve HTML pages. Each page now has page-specific social title/description, a large-image card declaration and a consistent logo image reference. The image URL deliberately uses the preview deployment hostname; it must be changed to the approved production asset URL before any production release.
- Current GitHub comparison: `website-restoration-preview` is 135 commits ahead and 40 behind `main`. The branches remain divergent; no merge or rebase was performed.
- Cloudflare Pages read-only configuration confirms production branch `main` and preview deployments restricted to `website-restoration-preview`. At the start of this QA pass, the latest successful preview deployment was `a49798b9-df3c-496f-9f61-fdb7d6f088dc` (20 November 2026), and the latest production deployment observed was `802c4c8a-4c61-46f5-9540-7001133a1cca` (19 November 2026). No production branch, deployment, DNS, SSL/TLS, Access, security or redirect settings were changed.
- Cloudflare Access continues to protect the preview hostname. Static source checks are possible, but authenticated live browser rendering and click-through of navigation, WhatsApp, email and telephone links remain unverified in this environment.


## Social metadata correction — 21 November 2026

- A follow-up static audit caught double-escaped ampersands in the Open Graph and X/Twitter titles/descriptions on the Hotels, Palaces, Villas and Office sector pages. Corrected the metadata so the decoded social text matches each page's actual title and meta description. No page copy or production files were changed.


## Full-logo favicon consistency — 22 November 2026

- Visually compared the approved original logo in the Library (1536 × 1024 PNG) with the existing website delivery asset at `images/zoraya-logo.webp`; the delivery asset retains the full ZORAYA wordmark and tagline.
- All twelve HTML pages previously referenced `/favicon.png`, which displays only the standalone Z mark. The preview is being updated to use the same full-logo WebP as the page header and social metadata, avoiding a separate cropped mark.
- The original PNG and the existing delivery artwork were not edited. The unused legacy favicon files remain in the repository but will no longer be referenced by the HTML pages.
- Changes are restricted to `website-restoration-preview`; production, DNS, SSL/TLS, security, redirects and public profiles were not changed.


## 3D visualisation showcase — 22 November 2026

- Added a visual showcase to `services.html` using the existing `images/palm-jumeirah-majlis-visualisation.webp` asset.
- The image is explicitly labelled as a 3D visualisation reference for a joint project, not completed-site photography. Supporting copy states that 3D presentation work is coordinated through independent specialist providers and that final specifications remain subject to approval.
- Added responsive two-column desktop / single-column mobile styling for the showcase. No new project ownership claims or image assets were introduced.


## Restoration QA — 22 November 2026

- All twelve pages reference the full approved ZORAYA logo artwork at `/images/zoraya-logo.webp` in both the header and favicon metadata; the original approved PNG in the Library remains untouched.
- The separate 64 × 64 Z-only icon is not used in page metadata because it is a cropped mark. The preview retains the full approved wordmark rather than substituting a cropped or recreated variant.
- The requested `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in this runtime. The Library ZIP inventory contains only the Palace website-image archives, not the requested website archive.
- Authenticated browser-level visual QA remains outstanding. The user-supplied Palm Jumeirah Villa exterior is now integrated; completed-site Majlis photography is still outstanding, so the Majlis card continues to use a clearly labelled 3D visualisation reference.


## Project imagery update — 22 November 2026

- Added the user-supplied Palm Jumeirah Villa exterior image from the Library as `images/palm-jumeirah-villa-2026.webp` (480 × 321 WebP delivery copy (7.9 KB)). The original PNG remains unchanged.
- Updated the Palm Jumeirah Villa project card to show the supplied exterior image and removed the missing-photography placeholder.
- Applied a shared cover-image treatment to the project-card media so the existing Palm Jumeirah Majlis 3D visualisation fills its frame cleanly; its caption continues to identify it as a visualisation reference, not completed-site photography.


## Palace imagery attribution — 22 November 2026

- Reviewed the Palace website-image archive. The interior imagery has the appearance of design visualisations rather than confirmed completed-site photographs.
- The Luxury Palace project remains attributed as a joint project, but its gallery image is now explicitly labelled as an interior visualisation reference. Completed-site photography is still required before presenting that image as a finished-project photograph.


- Updated the homepage hero caption and image alt text to identify the Luxury Palace image as a visualisation reference, consistent with the completed-projects card.


## Preview audit — 23 November 2026

- Re-inspected the current `website-restoration-preview` branch (baseline commit `8c6bb6a44855071a86a729444d1de4472e9ea9d8`) and the Cloudflare Pages project configuration. The project still uses `main` as production and includes only `website-restoration-preview` for preview deployments. The latest baseline preview deployment was `f9b8ce20-2dac-4958-adc8-0459a972e900`, with a successful deploy stage and the expected preview alias.
- The requested `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in the active workspace. The Library ZIP inventory contains only `ZORAYA_Palace_Website_Images_4.zip` and its duplicate; it does not contain the requested website archive. The available files were checked rather than assuming the archive was present.
- Re-ran a static audit across all twelve HTML pages: each page has a title, meta description, canonical URL, one H1, responsive viewport metadata, eight consistent primary navigation links, and no missing `img alt` attributes. All referenced local image assets exist in the branch. WhatsApp, email and telephone destinations are present in source and use the expected `+85255754850` / `Ben@zorayagroup.com` contact details; this is a source check, not a live click-through test.
- Reconfirmed the approved original logo file is available in the Library as `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024). The repository currently serves a visually matching but much smaller 180 × 120 WebP delivery copy at `images/zoraya-logo.webp`; the original PNG remains untouched. The WebP is adequate at the current small header display size but is not a high-resolution social-sharing image. Do not recreate or recolour the logo; use the original artwork as the source if a higher-resolution delivery asset is added later.
- Project gallery evidence remains explicitly qualified: Luxury Palace uses an interior visualisation reference; Dubai Hills uses a recovered project-video still with the visible Blanc watermark retained; Palm Jumeirah Villa uses the user-supplied exterior photograph; Palm Jumeirah Majlis uses a 3D visualisation reference. Completed-site photography for the Palace and Majlis is still outstanding. Added a visible source note to the Villa card identifying its exterior photograph as supplied by ZORAYA Group.
- The six main pages continue to describe ZORAYA's furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, project coordination and installation arrangements. MD Interior Design & Trading is explicitly described as a separate independent business, not owned by or part of ZORAYA.
- Browser-level visual, mobile-device and live contact-link checks remain unverified. The preview is protected by Cloudflare Access and the active container cannot resolve public site hostnames; no claim of an authenticated browser pass is made. The preview's `noindex,nofollow` and `robots.txt` disallow rule are intentional and must be reviewed before production publication.
- No production branch, production deployment, DNS, SSL/TLS, security, Access or redirect setting was changed.


## Optional post-installation cleaning — 23 November 2026

- Updated the homepage project-delivery sequence to mention that, where requested, ZORAYA can arrange post-installation deep cleaning through an independent local cleaning provider before handover, subject to the written project scope. This aligns the homepage with the existing Services page and does not imply that ZORAYA owns or directly employs a cleaning company.

## Client-facing portfolio copy and image handling — 24 November 2026

- Replaced the homepage portfolio teaser's internal restoration-status sentence with client-facing wording about selected project highlights, collaborations and transparent image references.
- Replaced the Projects page's internal archive-restoration note with a client-facing explanation of project attribution and the distinction between completed-site photography and design visualisation references. Updated the section heading to “Selected projects & collaborations” and refined the search/social description to match.
- Added lazy loading and asynchronous decoding to the Luxury Palace and Dubai Hills project images. The Dubai Hills caption now describes the supplied video still and visible Blanc watermark without calling the file “recovered”.
- Located and inspected the separate Library archive ZORAYA_Palace_Website_Images_4.zip (four JPEGs: dining room, living room, master living room and staircase). These are not added to the completed-project gallery because their completed-site versus visualisation status and project attribution are not established by the archive alone.
- The requested website archive /mnt/data/files/Zoraya-Group-Website-Updated.zip is not present in the current runtime or Library search. The exact approved logo PNG remains available in the Library and untouched; the repository continues to serve its existing 180 × 120 WebP delivery copy pending a way to transfer the original binary without altering it.
- No production branch, deployment, DNS, SSL/TLS, security, Access or redirect configuration was changed.

## Additional video asset review — 24 November 2026

- Reviewed the available 14.3-second vertical interior walkthrough files `VIDEO-2026-11-19-19-41-04.mp4` and `ZORAYA_GROUP_Luxury_Interiors_Enhanced.mp4`. They show a furnished interior walkthrough but do not identify a project, location, client or ownership in the footage; they are not assigned to any named completed project.
- Reviewed the available 20-second RAK Majlis videos. Their visible on-screen title identifies them as “RAK | MAJLIS”; they are treated as separate visualisation media and are not attributed to the Palm Jumeirah Majlis or presented as completed-site photography.
- No video was added to the public-facing portfolio because the project attribution and intended use are not sufficiently established. This avoids implying that an unverified video belongs to one of the four named portfolio projects.


## Restoration update — 25 November 2026

- Updated the six primary client-facing pages to reflect the confirmed operating model: ZORAYA is founder-led, operates from the UAE, serves clients in the UAE and Qatar, and the founder personally travels for client meetings and project-site visits by arrangement.
- The Contact page now invites clients to speak directly with the founder. It no longer displays the Hong Kong street address as though it were a customer-facing office; the Hong Kong business registration number remains visible.
- Standardised the service-area wording in the footers across the twelve HTML pages. The completed-projects page continues to identify project roles and distinguish completed-site photographs from visualisation references.
- Services wording continues to describe furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, project coordination, installation arrangements and delivery, subject to the agreed written scope. MD Interior Design & Trading remains identified as a separate independent provider, not owned by or part of ZORAYA.
- The exact approved original logo PNG remains accessible in the Library as `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024); it was retrieved and visually inspected, and the source file was left untouched. The repository still references its existing 180 × 120 WebP delivery copy. This is a matching, compressed web-delivery derivative, not the original PNG binary; no new logo artwork was recreated, recoloured or substituted.
- The requested archive `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is absent from the active runtime and the Library ZIP inventory. The separate Palace image archive is not the requested website archive. The earlier 17 November archive inspection note remains historical and cannot be independently repeated in this pass.
- At the start of this update, the preview branch head was `9ace912d3256a1199d8916b59f17640bc1349294`; the latest successful preview deployment was `148a3782-5fa7-4f56-aacc-63839a6f1a58`, built from that head. Cloudflare Pages read-only configuration still identifies `main` as production and restricts preview deployment inclusion to `website-restoration-preview`.
- Browser-level rendering, actual mobile-device layout, live contact-link click-through and redirect behaviour remain to be verified. The preview hostname is protected by the existing Cloudflare Access application; no Access policy was changed.
- No production branch, production deployment, DNS, SSL/TLS, security, Access, redirect settings or public company/social profiles were changed.


## Restoration QA — 26 November 2026

- Rechecked the active GitHub preview branch. Its head remains `965a3f7b0b0fee5db1885ea703d76481f28aa2a7` before this documentation update. The branch tree contains twelve HTML pages, four project-image assets, the ZORAYA logo delivery asset, favicon files, a sitemap and preview robots rules.
- The requested recovered website archive `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in the active container. The Library ZIP inventory contains only `ZORAYA_Palace_Website_Images_4(1).zip`, a separate palace-image archive. It is not a substitute for the website archive, so no archive comparison is claimed.
- Retrieved and visually inspected the exact Library source artwork `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024 RGBA). The original source file was left untouched. The repository's `images/zoraya-logo.webp` is a 180 × 120 compressed web-delivery derivative that visually retains the same full ZORAYA wordmark and tagline; no replacement or recreated artwork was introduced. The current preview continues to use that existing delivery asset. A high-resolution social-sharing asset based on the original source is still outstanding.
- Static source audit of all twelve HTML pages: each has a page title, meta description, canonical URL, viewport declaration, exactly one H1, page-specific Open Graph and X/Twitter image metadata, the same full-logo header/favicon reference, eight primary navigation links, and working source references to local image files. All image elements have alt text; all local page links resolve to files in the branch. WhatsApp and email links are present across all twelve pages; the Contact page also includes a telephone link. These are source checks, not live click-through tests.
- Reviewed the six primary pages' copy. Services cover furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, project coordination, installation arrangements and delivery coordination, subject to written scope. MD Interior Design & Trading is described as a separate independent business, not owned by or part of ZORAYA. The completed-projects page distinguishes the Luxury Palace and Palm Jumeirah Majlis visualisation references, the Dubai Hills supplied video still with its visible Blanc watermark, the Palm Jumeirah Villa exterior photograph, and the stated joint-project roles.
- The six primary pages and the wider twelve-page set retain `noindex,nofollow`; `robots.txt` disallows crawling. This is intentional for the private preview and must be reviewed before production publication. The Open Graph/X image URL currently points to the preview hostname and also needs an approved production asset URL before release.
- Cloudflare Pages read-only configuration still identifies `main` as the production branch and `website-restoration-preview` as the only included preview branch. Latest successful preview deployment observed: `46aa4d96-26a9-41e9-9102-60f7bec8fd2d`, built from commit `965a3f7b0b0fee5db1885ea703d76481f28aa2a7`. Latest production deployment observed remains `802c4c8a-4c61-46f5-9540-7001133a1cca` from 19 November 2026. No production branch, deployment, DNS, SSL/TLS, Access, security or redirect settings were changed.
- The preview hostname remains protected by Cloudflare Access. Authenticated browser rendering, actual mobile-device visual testing, navigation/contact click-through, and exact HTTP redirect status plus www/apex redirect behaviour remain unverified. An HTTP request to the apex production domain resolved to its HTTPS URL in the browser fetch, but the response status code was not exposed. The public production homepage remains the older version and still references a third-party stock interior image; production was not changed.
- GitHub reports the preview branch as 155 commits ahead and 40 behind `main`. The branches remain divergent; no merge or rebase was performed.
- Next concrete step: obtain the exact recovered website ZIP and an authenticated preview-review path (or a temporary review session approved by the account owner), then complete the source/archive comparison and visual desktop/mobile/contact-link checks. Do not merge or publish until the user approves the preview.


## Restoration QA — 27 November 2026

- Re-read the live GitHub preview branch and its complete tree at audit start. The branch head was `20ffba5fb07f0e72f45928e7c92fd677abab0147`; it contains twelve HTML pages, the shared project imagery, the existing ZORAYA logo delivery asset, favicon files, `robots.txt`, `sitemap.xml`, `README.md` and this restoration log.
- Compared the six primary page blobs against `main`: all six differ from production. GitHub reports the preview branch as diverged, 156 commits ahead and 40 behind, with merge base `3295a6439d7d82c84401213e45959aca49b41cf5`. No merge, rebase or production change was made.
- Re-ran a source-level audit across all twelve HTML pages. Each has a title, meta description, canonical URL, viewport declaration, exactly one H1, eight consistent primary navigation links, the same full-wordmark logo reference, favicon metadata, and image alt text. All local page and image references resolve to files in the branch. WhatsApp and email destinations are present on all twelve pages; the Contact page also has a telephone link. These are source checks only, not browser click-through tests.
- Re-read the six primary pages. Service copy includes furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, project coordination, installation arrangements and delivery coordination subject to the written scope. MD Interior Design & Trading is described as a separate independent business, not owned by or part of ZORAYA. The project page continues to label the Luxury Palace and Palm Jumeirah Majlis imagery as visualisation references, the Dubai Hills image as a supplied video still with the Blanc watermark visible, and the Palm Jumeirah Villa image as supplied by ZORAYA Group. Joint-project roles remain identified.
- Located and materialised the exact Library source artwork `Zoraya Group Luxury Marble Logo(1).png` (1536 × 1024, RGBA, 3,025,511 bytes; SHA-256 `fb1a26cf5a3d427f589544e468fb0c8924c187bcbd1b0d60b7c2be27cade18c8`). The original source file was inspected and left untouched. The repository still serves `images/zoraya-logo.webp` (the existing 180 × 120 full-wordmark delivery derivative) in the header and favicon metadata. The original PNG has not yet been added to the repository: the available GitHub write route accepts text/base64 payloads but does not accept the materialised container file as a binary file handle, so the original bytes could not be transferred in this run. No recreated, cropped or recoloured logo was substituted.
- The requested website archive `/mnt/data/files/Zoraya-Group-Website-Updated.zip` remains absent from the active container and Library. The Library ZIP inventory contains only the separate Palace-image archive `ZORAYA_Palace_Website_Images_4.zip` and its duplicate; neither is the recovered website archive, so no ZIP-to-repository comparison is claimed.
- Cloudflare Pages read-only configuration still identifies `main` as the production branch and `website-restoration-preview` as the only included preview branch. At audit start, the latest preview deployment was `57f55662-dc2c-44af-b3ce-e8d6d219dd4b`, built successfully from `20ffba5fb07f0e72f45928e7c92fd677abab0147`. The latest production deployment remains `802c4c8a-4c61-46f5-9540-7001133a1cca`, built from `01724bd5c03582cbb43a8bcf2b8b949b354cd3c3` on 19 November 2026.
- The preview URL remains inaccessible without the existing Cloudflare Access session; an unauthenticated browser check could not inspect it. Consequently, rendered desktop/mobile layout, live navigation and contact click-through, and preview HTTPS/redirect behaviour remain unverified. The public apex website was readable and still serves the older homepage with a third-party Unsplash interior image; production was not changed. No DNS, SSL/TLS, Access, security or redirect settings were modified.
- The six primary pages and the wider twelve-page set retain `noindex,nofollow`, and `robots.txt` disallows crawling. This remains intentional for the private preview and must be reviewed only after the user approves a release plan.
- Next concrete steps: obtain the missing recovered website ZIP for an actual archive comparison; provide a binary-capable path to add the untouched original PNG to the preview repository; and establish an authenticated preview-review session so desktop/mobile and live link tests can be completed. Do not merge or publish until the user explicitly approves the preview.


## Restoration QA — 28 November 2026

- Checked the requested recovered archive path `/mnt/data/files/Zoraya-Group-Website-Updated.zip`; it is absent from the active runtime. The complete Library ZIP inventory contains only `ZORAYA_Palace_Website_Images_4.zip` and its duplicate, not the requested website archive. Materialised and inspected the separate Palace archive: four JPEG interiors (`palace-dining-room.jpeg`, `palace-living-room.jpeg`, `palace-master-living.jpeg`, `palace-staircase.jpeg`). The images are interior visualisation-style renders; the archive alone does not establish completed-site status or project attribution, so none were added to the portfolio.

- Located, materialised and visually inspected the exact approved source artwork `Zoraya Group Luxury Marble Logo(1).png` from the Library. It is a 1536 × 1024 RGBA PNG, 3,025,511 bytes, SHA-256 `fb1a26cf5a3d427f589544e468fb0c8924c187bcbd1b0d60b7c2be27cade18c8`. The original Library file was left untouched. The preview still serves its existing `images/zoraya-logo.webp` full-wordmark delivery derivative; the available GitHub write route did not provide a binary-file transfer handle for the original PNG. No logo was recreated, recoloured or substituted. The existing `favicon.webp` and `favicon.png` Z-mark assets are now referenced separately as favicons.

- Compared `website-restoration-preview` with `main`: the preview branch is 161 commits ahead and 40 behind, with merge base `3295a6439d7d82c84401213e45959aca49b41cf5`. The 40 main-only commits include production Google Tag Manager / GA4 integration and 19 November page and sector updates. No merge or rebase was performed. GTM was not copied into the preview, to avoid mixing private preview testing with production analytics.

- Preview-only content changes in this run:
  - `36aeb555` — `index.html`: removed duplicated portfolio wording and replaced it with clear project-attribution and image-source language.
  - `a60ac55e` — `completed-projects.html`: removed duplicated introductory copy and replaced internal “photography remains to be added” wording with explicit visualisation-only labels.
  - `e782b87` — `hotel-transformation.html`: removed internal photography-pending placeholders and replaced them with client-facing scope panels and an assessment/planning framework.
  - `5c1e387` — all twelve HTML pages: changed favicon references to the existing `/favicon.webp` and `/favicon.png` assets. The full-wordmark header logo and social-sharing image references remain unchanged.

- Re-ran a static source audit across all twelve HTML pages. Each has a unique page title, meta description, canonical URL, one H1, viewport metadata, eight primary navigation links, the full-wordmark header image, both dedicated favicon references, and responsive CSS media queries. All local image files exist; all image elements have alt text; local page and anchor links resolve; WhatsApp and email links are present on every page; the Contact page also has a telephone link. No internal photography-pending or placeholder copy remains. These are source-level checks only, not rendered-browser or live click-through tests.

- Rechecked content: Services covers furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, project coordination, installation arrangements and delivery coordination subject to written scope. MD Interior Design & Trading remains identified as a separate independent business, not owned by or part of ZORAYA. Project entries continue to distinguish ZORAYA work, joint projects, supplied project-video stills and design visualisation references.

- Cloudflare Pages read-only configuration still identifies `main` as production and `website-restoration-preview` as the only included preview branch. Latest successful preview deployment at this audit point: `feee382a-b440-4361-b424-1e0ad73091c1`, built from `5c1e387057e3b4c4bdd959a47e1ba66141237ea4`. Latest production deployment remains `802c4c8a-4c61-46f5-9540-7001133a1cca`, built from `01724bd5c03582cbb43a8bcf2b8b949b354cd3c3`. No production branch, deployment, DNS, SSL/TLS, Access, security, redirect setting or public profile was changed.

- The preview retains `noindex,nofollow` on all twelve pages and `Disallow: /` in `robots.txt`; this is intentional for the private review environment and must be reconsidered only after explicit release approval. The sitemap lists the twelve canonical production URLs.

- Authenticated browser inspection remains blocked by the existing Cloudflare Access gate. The preview hostname could not be opened by the unauthenticated web fetch, and the active container could not resolve public hostnames. Therefore rendered desktop/mobile layout, live navigation and WhatsApp/contact click-through, exact HTTP status codes and the www/apex redirect behaviour remain unverified. An HTTP apex request did resolve to the HTTPS apex page in the web fetch, but its redirect status was not exposed. The www URL was not accessible through that fetch.

- Next steps: obtain the missing recovered website ZIP for a true archive comparison; establish a binary-capable route to add the untouched original PNG if it is required in the repository; and obtain an authenticated preview-review session for desktop/mobile and live contact-link checks. Do not merge or publish until the user explicitly approves the preview.

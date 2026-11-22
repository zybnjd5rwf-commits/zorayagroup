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

- Corrected the favicon reference across all twelve HTML pages to use the dedicated 64 × 64 Z emblem at `/favicon.png`. The full approved ZORAYA wordmark remains the header logo at `/images/zoraya-logo.webp`; the original Library artwork is unchanged.
- Confirmed the repository's `favicon.png` is a 64 × 64 PNG. Using the dedicated icon avoids shrinking the full wordmark into a browser-tab icon.
- The requested `/mnt/data/files/Zoraya-Group-Website-Updated.zip` is not present in this runtime. The Library ZIP inventory contains only the Palace website-image archives, not the requested website archive.
- Authenticated browser-level visual QA and original Villa/Majlis project media integration remain outstanding.


## Project imagery update — 22 November 2026

- Added the user-supplied Palm Jumeirah Villa exterior image from the Library as `images/palm-jumeirah-villa-2026.webp` (640 × 429 WebP delivery copy). The original PNG remains unchanged.
- Updated the Palm Jumeirah Villa project card to show the supplied exterior image and removed the missing-photography placeholder.
- Applied a shared cover-image treatment to the project-card media so the existing Palm Jumeirah Majlis 3D visualisation fills its frame cleanly; its caption continues to identify it as a visualisation reference, not completed-site photography.

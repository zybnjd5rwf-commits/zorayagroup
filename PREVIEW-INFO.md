# ZORAYA Group website preview

This branch is the review build for the ZORAYA Group website restoration.

- Git branch: `website-restoration-preview`
- Cloudflare Pages project: `zorayagroup-site`
- Preview alias: https://website-restoration-preview.zorayagroup-site.pages.dev
- Production branch: `main`

## Production protection

No production files, DNS records, SSL/TLS settings, security settings, redirect rules, or Cloudflare production configuration were changed during this restoration pass. Cloudflare currently reports production deployments enabled for the `main` branch; that setting remains unchanged. Only commits to this preview branch are intended to trigger preview deployments.

## Preview-only indexing protection

All six HTML pages carry `noindex,nofollow`, and this branch's `robots.txt` disallows crawling. Remove these preview-only controls before any approved production release.

## Current site scope

The branch contains Home, About, Services, Completed Projects, Industries, and Contact pages. The existing copy describes furniture sourcing and supply, custom furniture, manufacturing coordination, quality inspection, export/container coordination, project coordination, and installation arrangements. MD Interior Design & Trading is described as an independent specialist provider, not as a company owned by or part of ZORAYA.

## Restoration items still outstanding

- Integrate the exact user-supplied ZORAYA logo artwork from the Library. Do not use generated logo variants or approximate/recreate the mark. The current branch logo WebP does not decode correctly.
- Restore the original project image/video assets from the recovered archive and retain source attribution. The Dubai Hills source video contains a visible “Blanc” watermark; preserve it. The Palm Jumeirah Villa & Majlis project remains labelled as a joint project, and the recovered archive contains no dedicated image for it.
- Complete visual checks of the preview deployment at desktop and mobile sizes, including logo/favicon rendering, contact links, HTTPS, and redirects.

The production site remains live and untouched pending explicit approval of the preview.


## Asset inventory and attribution — 15 November 2026

- **Approved ZORAYA logo:** the exact user-supplied Library file is `image(3).png` (1536 × 1024, RGBA, 3,025,511 bytes; SHA-256 `fb1a26cf5a3d427f589544e468fb0c8924c187bcbd1b0d60b7c2be27cade18c8`). Keep this original artwork unchanged for the header and favicon. The current `images/zoraya-logo.webp` / `favicon.webp` asset is invalid. Do not use `favicon.png`: it is a separate Z-only mark, not the approved full logo.
- **Luxury Palace Project | Dubai, UAE — 2026:** the original user-supplied project image is in the Library as `zoraya group palace photo (1).jpg`. The recovered ZIP also contains the lower-resolution WebP derivative `images/luxury-palace-dubai-2026.webp`. Use one image only and describe it as a project visual; no photographer credit has been supplied.
- **Dubai Hills Project | Dubai, UAE — 2025:** the recovered ZIP contains `images/dubai-hills-project-2025.mp4` (40.029 seconds, 720 × 1280, H.264/AAC) and `images/dubai-hills-2025-poster.jpg` (720 × 1280). The poster and source footage carry a visible “Blanc” watermark; preserve it and do not crop, cover or remove it. Neither asset is currently in the preview branch.
- **Dubai Palm Jumeirah — Luxury Majlis Project — 2026:** this remains a joint project with a strategic partner. The recovered ZIP contains no dedicated image for it; do not substitute unrelated stock or generated imagery.
- The archive's `candidate12/15/20/25.webp` and `test28/35/45.webp` files are repeated versions of the same palace interior. Do not use them as separate project photographs.

## Static review — 15 November 2026

- The recovered ZIP contains two HTML pages; the preview branch expands the site to six pages: Home, About, Services, Completed Projects, Industries and Contact.
- All six preview pages have a title and meta description. A static link check found no missing internal page links, and each page includes responsive CSS breakpoints.
- Contact links are present for `Ben@zorayagroup.com` and WhatsApp `https://wa.me/85255754850`.
- Preview-only `noindex,nofollow` metadata and the disallow-all `robots.txt` remain in place. Do not remove them until an approved production release.
- Desktop/mobile rendering, live contact-link behaviour, HTTPS redirects and browser-level favicon/logo rendering have **not** been verified in this run.
- The preview branch is diverged from `main`; do not merge it wholesale. Review and port only necessary changes after comparing their intent.

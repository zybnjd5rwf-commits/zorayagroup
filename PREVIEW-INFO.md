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

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

- The exact user-supplied full ZORAYA logo artwork has been recovered from the Library and restored as `images/zoraya-logo.webp`. It has been resized and compressed for the header without changing the artwork.
- The Luxury Palace project photograph from the user-supplied archive is available as `images/luxury-palace-dubai-2026.webp` and is shown on the selected-projects page.
- Dubai Hills Project | Dubai, UAE — 2025 is a joint project. Its recovered source video carries a visible “Blanc” watermark; preserve it if the video is integrated.
- Luxury Palace Project | Dubai, UAE — 2026 is a joint project.
- Palm Jumeirah Villa | Dubai, UAE — 2026 is ZORAYA's own project.
- Palm Jumeirah Majlis | Dubai, UAE — 2026 is a joint project.
- No unrelated stock or generated imagery is presented as completed ZORAYA project work.

## Remaining before production release

1. Replace or clear the third-party hotel transformation photographs. Their usage rights have not been confirmed. The intended visual direction remains a visibly neglected, dated “before” room contrasted with a refined contemporary “after” room. Use user-supplied, licensed, or commissioned visuals only.
2. Restore the Dubai Hills source video and poster from the recovered archive, preserving the visible “Blanc” watermark. The source video is not yet integrated into the website.
3. Restore approved photographs for Palm Jumeirah Villa and Palm Jumeirah Majlis when available. Do not substitute unrelated stock or generated images.
4. Review all pages at desktop and mobile sizes, including logo rendering, favicon, contact links, image loading, HTTPS, redirects and navigation.
5. Check the hotel article's technical and regulatory wording with the project's appointed consultants before using it as a compliance claim. The article correctly states that 60-minute fire-rated doors are not automatically required at every door.

## Current status

This is a content and navigation preview, not a production-ready release. The branch has not been published to the live site. Browser-level visual QA and Cloudflare preview deployment checks remain outstanding.


## Restoration updates — 17 November 2026

- The recovered website ZIP was inspected. It is an earlier two-page version (home and completed projects) with a small project asset set. The current preview branch remains the fuller twelve-page site; the ZIP is used as a source for verified project media rather than replacing the newer site structure.
- The approved full ZORAYA artwork is available in the Library as `image(3).png`. The preview uses the matching web-optimized WebP copy derived from that artwork; the original Library source remains untouched. The same approved artwork is now used in every page header and as the favicon.
- Added the recovered Dubai Hills 2025 project-video still to the project gallery. The visible “Blanc” watermark is preserved and disclosed; the full video remains archived but is not yet embedded.
- Palm Jumeirah Villa (ZORAYA project) and Palm Jumeirah Majlis (joint project) remain correctly attributed. Their cards now clearly state that project photography is still to be added.
- Added a working telephone link on the Contact page and a canonical URL to the hotel transformation article.
- Removed the partially applied Google Tag Manager snippet from this preview branch only. This prevents staging visits from being recorded in the live GA4 property. The production branch and production tracking remain untouched.
- Added the approved artwork favicon reference consistently across all twelve HTML pages.

## Current verification

Static source checks confirm all twelve pages have titles, descriptions, viewport metadata, preview-only noindex directives, mobile media queries, and image alt text where images are used. WhatsApp and email links are present; the Contact page now also has a `tel:` link. Live browser rendering, actual mobile-device layout, and HTTP-to-HTTPS/redirect behavior could not be independently verified because the preview host is not accessible to the current browser inspection service. Third-party imagery in the hotel transformation article still requires a rights review before production release.

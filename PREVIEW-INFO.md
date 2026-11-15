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

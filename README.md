# Nico Zhao — Content Marketing & Social Media Portfolio

Static portfolio: no build, dependencies or credentials needed to run.

## Run

From this folder: `python3 -m http.server 8001 --bind 127.0.0.1`.

## Assets

All 21 images and 3 videos are included.

## Public deployment

Upload this folder's contents to the root of a GitHub repository. Under Settings → Pages choose Deploy from a branch → main → / (root). Keep `.nojekyll`. GitHub Pages supplies HTTPS. Check all media, navigation and email from the deployed URL. A private repository may require a paid GitHub plan for Pages. Do not put access tokens in scripts or chat.

A second option is to upload this complete folder, including assets, to a static hosting provider that supports the video file sizes.

## Editorial changes

- Broadened the positioning from a Simon-specific application to marketing, social media and content opportunities.
- Moved social results above case studies and added clear calls to action.
- Corrected the conflicting claim of 200K+ likes on a single post: the supplied figures show 133K + 73K = 206K across two selected posts. 939K + 480K = 1.419M views. These are rounded post totals, not unique reach, conversions, or account-wide results; the two provided screenshots were visually checked and match these figures. They are historical snapshots, not live metrics.
- Clarified personal deliverables and team award attribution without inventing business results.
- Added the confirmed public email lzhao25@u.rochester.edu; removed the placeholder email and nonfunctional resume link.
- Added mobile navigation, keyboard image controls, focus handling, reduced-motion support, lazy image loading and video failure feedback.

The PDF included in the source ZIP is an earlier export and does not reflect the revised site. Update it separately before sharing it with employers.

## Verified so far

Chromium checks passed for 390/768/1440px layout, mobile menu, email link, section order, keyboard lightbox, focus restoration and absence of JavaScript errors. All 21 JPEG files passed integrity checks; HTML images decoded and all three videos played in Chromium. Local page/asset requests had no HTTP errors. No public deployment has been completed.

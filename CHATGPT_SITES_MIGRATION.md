# Chip & Co. Productions — ChatGPT Sites migration

## Source and isolation
- Snapshot of the existing production website at commit `92a8a6d39c5bbd820db584a41c42da38b92e8410`.
- Source: `donniepease/chip-and-co-productions`, branch `chatgpt-sites-copy-2026-11-11`.
- This branch is a copy. **Do not edit the `main` branch or change DNS for `chipandcoproductions.com`.**
- Proposed ChatGPT Sites name: **Chip & Co. Productions**.
- Preferred ChatGPT-hosted address (subject to availability): **chipandco-studio.chatgpt.site**.
- Alternate: **chipandcoproductions.chatgpt.site**.

## Migration instructions
Create a new ChatGPT Site from this branch, preserving the layout and content as faithfully as the runtime allows. Keep the existing brand's black/ivory cinematic typography, header, slideshow, responsive layout, five collapsible numbered photography collections, portfolio lightbox, services, contact section, Instagram profile links and embeds, and the transparent Gothic C icon. Keep images linked to the existing Cloudinary CDN, preserving their original source URLs.

Retain the inquiry email `Donaldjpease@gmail.com` and phone `+1 (810) 535-5036`. Keep the five-day in-person shoot availability (subject to availability), 30% booking deposit with $150 minimum credited toward the project total, remaining balance due before final file delivery, and the three-step booking process. Do not claim payment processing is implemented: the existing CTA opens a prefilled email inquiry.

**Do not use the `CNAME` file in Sites**. It belongs to GitHub Pages and points at the original domain. Do not connect the original custom domain to the new Site or change its DNS. The original website must remain operational.

Before public publication, verify Cloudinary images, mobile layout, collection expand/collapse, lightbox, navigation, contact mailto and tel links, and Instagram embeds. Replace the copied canonical URL with the actual new ChatGPT Sites URL after it is assigned, or omit canonical until publishing; do not keep `https://chipandcoproductions.com/` as canonical on the duplicate. Keep the new site private for review, save a version, then deploy only after approval. Confirm the final URL after deployment.

## Existing files
- `index.html`: site markup, gallery data, behavior, SEO metadata
- `styles.css`: brand styling and responsive layout
- `assets/black-c-icon.svg`: transparent black Gothic C icon
- `script.js`, `images.css`: ancillary legacy files; inspect before importing
- `CNAME`: original GitHub Pages domain configuration; **exclude from ChatGPT Sites**

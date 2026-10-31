# AFRAME Studio — UGC Video Portfolio

Official AFRAME Studio UGC video portfolio by Affan (Karnataka, India).
Tagline: Make Every Frame Matter.

Live site (GitHub Pages): https://mdaffan5546-dot.github.io/aframe-studio-portfolio/

## About
AI-assisted UGC-style video ads, product demonstrations and product visuals
for beauty, skincare, fragrance, lifestyle and consumer brands worldwide.
Portfolio samples labelled Spec Ad / Planned Concept are independent
concepts, not commissioned brand campaigns.

## Updating the site
- Edit `index.html` to change text, sections or links, then commit to `main`.
- Videos are stored losslessly in `assets/` as base64 data files
  (`.mp4.b64`) because they were published through Muse's GitHub
  integration; the Pages workflow restores the exact original `.mp4`
  files (`dossier-ambery-vanilla-selfie.mp4`, `dot-and-key-sunscreen.mp4`,
  `dossier-ambery-vanilla-editorial.mp4`) on every deploy, so visitors
  simply see normal playable videos. To replace a video, ask Muse to
  re-publish it, or replace the matching `.b64` file with the base64
  encoding of your new video.
- Every push to `main` redeploys automatically via
  `.github/workflows/static.yml`.

Hosting: GitHub Pages (free). No paid hosting or subscription required.

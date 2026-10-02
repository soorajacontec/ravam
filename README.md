# RAVAM (PWA)

Upload this folder as-is to any static host served over HTTPS (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
Open the URL on your phone, then:
- Android / Chrome: tap **Install** in the app header, or menu > Install app.
- iPhone / Safari: Share > Add to Home Screen.

Test locally: `npx serve .` then open http://localhost:3000 (service workers work on localhost).

All sounds are synthesized with the Web Audio API, so there are no audio files and it works fully offline after the first load.
To change the cache after editing files, bump `VERSION` in sw.js.

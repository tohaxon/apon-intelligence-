# IELTS 6.5 — 60-Day Learning Journey
Static site: no build step, no server, no API key. Progress is stored in the browser (LocalStorage).

## Deploy (free, ~2 minutes)
**Cloudflare Pages:** Workers & Pages → Create → Pages → Upload assets → drag this whole folder → Deploy. (Git: build command empty, output directory `/`.)
**Netlify:** app.netlify.com/drop → drag this folder.
**GitHub Pages:** push these files to a repo → Settings → Pages → Deploy from branch → `main` / root.
Run locally: `python3 -m http.server 8000` and open http://localhost:8000

## Add a lesson
In `index.html`: add an entry to `DAYS` (copy Day 2), add its quiz as `QZ.dN`, its topic in `TOPIC`, new words to `V`, and `N:1` to `READY`. If you change files, bump `C` in `sw.js`.

## Status
Days 1–6 complete. Days 7–60 are outlined only. Practice material is original, not official IELTS; no score is guaranteed.

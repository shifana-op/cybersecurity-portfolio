# Shifana Sherin – Cybersecurity Portfolio

Static website (HTML, CSS, JavaScript). No build step or npm install is needed.

## Structure
- index.html – page
- css/styles.css – styles
- js/main.js – animations, 3D globe, interactions
- assets/ – profile photo, favicon
- Shifana_Sherin_Resume.pdf – resume download
- netlify.toml – Netlify settings

## Run locally
1. Extract the ZIP.
2. In the folder run: python3 -m http.server 8000
3. Open http://localhost:8000
(Opening index.html directly also works.)

## Deploy on Netlify
- Easiest: open https://app.netlify.com/drop and drag the extracted folder in.
- Or push to GitHub, then in Netlify choose "Add new site > Import from Git"; leave Build command empty and set Publish directory to "."

## Notes
- The 3D globe uses Three.js r128 loaded from cdnjs. If it is unreachable, the site still works without the globe.
- Replace the resume by overwriting Shifana_Sherin_Resume.pdf (keep the same file name).

JARVIS PHONE EDITION V1.0

Files:
- index.html: app interface and local command engine
- manifest.webmanifest: installable web app metadata
- sw.js: offline cache
- icon.svg: app icon

FREE PHONE-ONLY DEPLOYMENT:
1. On your phone, create a free GitHub account or sign in at https://github.com.
2. Create a new PUBLIC repository named jarvis-phone.
3. Upload all four files (index.html, manifest.webmanifest, sw.js, icon.svg) to the repository root.
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait for GitHub Pages to publish. Open the Pages URL on your Samsung S24 FE in Chrome.
7. Chrome menu (three dots) > Add to Home screen / Install app.

NOTES:
- Voice recognition depends on browser/device support and may require internet.
- Text commands and basic app logic run locally after the app is cached.
- This first version does NOT include an AI API connection. Free-only mode avoids API charges.
- Speech output uses an installed English (United Kingdom) voice if available. Exact male voice selection depends on Samsung/Google TTS voices installed.
- Do not put API keys in frontend files.

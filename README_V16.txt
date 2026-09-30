HANDCAPTION V16 — RESPONSIVE LIQUID GLASS

This release keeps the V15 editor foundation and adds a responsive/product-readiness layer.

NEW:
- Mobile-first responsive layout from small phones through tablets and desktop.
- Floating bottom navigation on mobile and glass sidebar on desktop.
- Landscape-phone layout handling.
- Safe-area friendly spacing for modern mobile browsers.
- Settings: System/Light/Dark theme, Reduce Motion, Compact Layout, High Contrast.
- Installable PWA manifest + service worker + offline fallback.
- Install button when the browser exposes the install prompt.
- Online/offline feedback messages.
- Toast feedback for errors and successful actions.
- Diagnostics copy option for easier bug reports.
- Feedback/share helper using the device share sheet or clipboard.
- SEO description/keywords and social metadata.
- Accessible focus-visible states and semantic controls retained.
- Glass fallback when backdrop-filter is unavailable.

IMPORTANT:
- Handwriting packs and projects remain browser-local.
- Media processing remains local to the browser.
- The service worker caches the app shell; it does not upload media.
- Keep the current V15 package as a backup before deployment.

DEPLOY:
Replace index.html, style.css, app.js and add manifest.json, sw.js, offline.html and icon.svg at the GitHub Pages root.

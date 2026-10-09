STAR 7 GLOBAL OTT — starter project
=====================================

Files
- index.html: responsive OTT web app with a dark navy/blue/gold design.
- README.txt: setup and important production notes.

Run
1. Extract the ZIP.
2. Open index.html in a modern browser, or publish the folder as a static site.
3. The demo stores watchlist, watch progress, demo profile, plan selection and content edits in the browser's localStorage.

Included working demo flows
- Home, browse, categories, search, details, series episode list
- HTML5 video player, playback progress, continue watching
- Watchlist, watch history, profile, settings, notifications
- Demo subscription confirmation
- Demo admin content add/delete and JSON backup/import
- Responsive mobile navigation

Important limitations — read before public launch
This is a functional FRONT-END DEMO, not a production streaming business and cannot honestly be called 100% production-ready.
- Login is a local demo profile. It does NOT send or verify real OTP.
- Subscription confirmation is a demo and does NOT collect payment.
- Admin gate is client-side and NOT secure. Do not use it to protect real content.
- Browser localStorage is local to one browser/device and may be cleared. It is not a shared database or cloud backup.
- The sample MP4 is a public test video, not a STAR 7 content library. Add only videos you own or are licensed to stream.
- Production requires a backend/database, server-side access control, real authentication, payment-provider integration, secure subscription verification, video storage/CDN, HLS/DASH packaging as needed, monitoring, privacy policy, and backup/restore testing.
- No service can guarantee that an app will run forever; hosting, domains, provider plans and maintenance may change.

Suggested production upgrade
Frontend: React/Next.js or keep this UI as a prototype.
Backend: Firebase Authentication + Firestore/Storage with strict security rules, or a trusted server API.
Payments: a supported payment gateway with server-side webhook verification.
Streaming: licensed content + object storage/CDN + HLS/DASH; DRM if required by rights holders.
Admin: server-verified admin roles; never embed secrets in HTML/JS.

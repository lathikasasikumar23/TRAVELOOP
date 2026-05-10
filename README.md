# TRAVELOOP
Traveloop is a travel planning SPA — a polished UI prototype in a single 2,170-line .jsx file with 13 screens, zero npm dependencies beyond React, and zero real backend. It covers auth, trip management, itinerary building, budget tracking, invoicing, packing checklists, community posts, an explore/search view, and an admin analytics dashboard. Everything is wired with manual prop-drilling and a switch(screen) router — no Redux, no React Router, no Tailwind.

**LANGUAGES USED**

Frontend — everything runs here:
1.React 18 (JSX, functional components)
2.JavaScript ES2022+ — hooks: useState, useEffect, useRef, useCallback
3.CSS3 — injected as a template-literal string into a <style> tag (no framework). Uses CSS variables, Grid, Flexbox, keyframe animations, and responsive media queries.
4.HTML5 — via JSX markup

Backend — there isn't one. The data layer is:
A hardcoded MOCK JS object simulating a database
setTimeout() to fake async API calls
No server, no database, no REST/GraphQL calls

Other / External:
Google Fonts API — loads Playfair Display, DM Sans, JetBrains Mono
Inline SVG — the Google OAuth button logo

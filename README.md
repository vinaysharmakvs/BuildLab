# BuildLab Playground

Three interactive student sample projects based on the supplied BuildLab programme.

- Creator Studio: three curated lessons, grade-dependent challenges, editable text, quiz feedback, local draft saving and text download.
- ShowTime: three sample shows, seat selection, price calculation, simulated bookings and browser-tab booking updates.
- Dream Room: five wall colours, six furniture items, pointer dragging and keyboard movement, budget feedback, local saving and plan export.

These are static browser demos. They use no live AI, database, payment or student accounts. localStorage data belongs to the current browser; it is not shared between students/devices. Cross-tab booking updates are illustrative and do not provide database transaction guarantees.

## Preview

Run `npm run dev` and open http://localhost:4173.

## Deploy on Vercel

Import this folder as a project via Git, or run `npx vercel login`, then `npx vercel --prod` from this folder.

Framework preset: Other
Build command: npm run build
Output directory: dist

No environment variables or API keys are needed. Google Fonts is optional; system fonts work if it is unavailable.

Direct project links once deployed:
- https://YOUR-DOMAIN/#creator
- https://YOUR-DOMAIN/#tickets
- https://YOUR-DOMAIN/#room

## Checks performed

JavaScript syntax and production build passed. Browser checks covered lesson generation and quiz feedback, seat selection and booking confirmation, room palette and furniture changes, keyboard movement, and local room saving. Desktop and phone layouts were inspected.

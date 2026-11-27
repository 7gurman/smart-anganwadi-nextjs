# Smart Anganwadi Monitoring System
Next.js 14 (App Router) PWA — `npm install && npm run dev`.

## Structure
- `app/page.js` — all screens (Worker: Home, Register, Growth, Children, Activities; Supervisor: Overview, Alerts, Reports) + child profile sheet
- `lib/data.js` — seed data, alert rules, localStorage hook (`useDB`)
- `lib/i18n.js` — Hindi / Punjabi labels (extend per screen)
- `public/` — manifest, service worker (offline cache), icon

## Rules
- MUAC alerts (WHO, 6-59 months): <11.5 cm severe, <12.5 cm moderate
- Center alerts: register missing, attendance <60%, present-but-not-fed, low stock

## Next steps
Replace `useDB` with an API + DB (Supabase/Postgres), add login with roles (worker / supervisor), per-center scoping, and a sync queue for offline edits.

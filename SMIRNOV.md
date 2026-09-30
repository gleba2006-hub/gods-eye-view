# Smirnov God's Eye

This fork is the real God's Eye View console.

Their HUD, layers, cockpit, sensors, and voice stack stay. Two Smirnov changes only:

- Tab title: **Smirnov God's Eye**
- Startup fly-in: **Holon** instead of Austin

Upstream: https://github.com/bilawalsidhu/gods-eye-view
This fork: https://github.com/gleba2006-hub/gods-eye-view

## Run

Needs Node 24.14+ or 26.

```bash
git clone https://github.com/gleba2006-hub/gods-eye-view.git
cd gods-eye-view
npm ci
npm run doctor
npm run dev
```

Open http://localhost:4173

No keys required to boot. Aircraft, quakes, satellites, cameras, weather work keyless. Photorealistic 3D, ships, and voice need keys from POWER UP inside the app.

Easiest path with no terminal: Pinokio 8.2+ pointed at this repo.

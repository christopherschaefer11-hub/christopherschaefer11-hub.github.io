# Big 4 Pro Sports Road Trip Planner Pro (NHL · NFL · NBA · MLB)

A 100% self-contained, single-file interactive road trip planner for sports crews, live at `https://christopherschaefer11-hub.github.io/`.

## What's New in This Release
- **Upcoming Dates Filter + Past-Date Warning Badges**:
  - **📅 Upcoming dates only (hide past games)** is enabled by default in Step 2 so the solver only suggests trips starting today or later.
  - If you uncheck the filter or select a completed month to browse historical stretches, every past trip card and game row displays a prominent **⚠️ Past Date — Trip Already Occurred** warning banner.
  - Built-in MLB schedule now includes both Late-October 2026 Fall Classic / Sports Equinox crossover games and the full upcoming **2027 MLB Regular Season (April–September 2027)**.
- **Live Big 4 API & Schedule Tools (NHL · NFL · NBA · MLB)**:
  - Upgraded the sidebar Schedule Tools panel to fetch live schedules across **all 4 leagues** (NHL, NFL, NBA, and MLB) via CORS-friendly ESPN Scoreboard APIs and the official MLB StatsAPI.
  - Export or reset any active single-sport or multi-sport schedule JSON.

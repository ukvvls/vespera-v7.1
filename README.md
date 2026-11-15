# VESPERA V7.1 — Liquid Glass

Built on VESPERA V6.3 Fusion Glass. Existing task, player/XP, fitness, assistant, notifications, language, backup, and offline PWA features are retained.

## V7 additions
- Crystal-style high-transparency liquid-glass visual treatment and translucent V icon.
- Additional accent themes: Burgundy, Silver, Ice.
- Local prayer-time calculations, prayer completion tracking, seven-day history, adhkar counters, and tasbeeh.
- Prayer settings are editable (city, latitude, longitude, UTC offset). No location API or cloud service is used.

## Important
Prayer times are estimates based on the Egyptian calculation angles (Fajr 19.5°, Isha 17.5°), standard Asr factor, and the configured coordinates/time offset. Verify with your local mosque or official calendar.

## Deploy
Upload all five files to the root of your static HTTPS hosting/repository. Existing browser data remains under the original `vespera_v5_data` localStorage key.

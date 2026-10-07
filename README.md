# 保費速查

Installable web app (PWA) for quick premium lookups from Prudential HK product manual rate tables.

- Rate data is stored only in `data.enc.json`, encrypted with AES-256-GCM (key from a passcode via PBKDF2-SHA256, 310,000 iterations). Nothing readable is in this repository.
- On first open the app asks for the passcode, then remembers it on that device and works offline.
- For internal reference only. Official quotes come from the proposal system.

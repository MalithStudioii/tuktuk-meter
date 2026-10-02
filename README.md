# 🛺 TukTuk Meter Pro

Smart GPS-based Taxi & Three-Wheeler Meter web application designed for Sri Lankan tuk-tuk drivers and transport services.

## ✨ Key Features
- **Accurate GPS Fare Calculation:** Base rate, per-km rate, and stationary waiting time tracking.
- **GPS Drift & Jitter Filtering:** Filters out inaccurate GPS noise (< 30m) and stationary jumps.
- **Screen Wake Lock API:** Prevents phone screen from dimming/locking during active trips.
- **Interactive Live Route Map:** Real-time path tracing powered by Leaflet.js with Dark Mode tiles.
- **Digital Receipt & WhatsApp Sharing:** Instant detailed bill generation with direct WhatsApp share.
- **LANKAQR & Cash Calculator:** Instant dynamic QR code generation for banking apps + cash balance calculator.
- **Trip History & Daily Summary:** Stores past trips, daily earnings, total km, and completed trip counts.
- **Night Fare & Peak Surcharge:** Automatic or manual night fare surcharge (+15%).
- **Voice Alerts:** Text-to-Speech announcements for trip start, trip end, and overspeed alerts.
- **Speed Limit Warning:** Audio and visual flashing alarm if vehicle speed exceeds 40 km/h.
- **Progressive Web App (PWA):** Installable on Android & iOS with full offline support.

## 🚀 Branches
- `main`: Stable production / Live release.
- `beta`: Development and testing of new experimental features.

## 🛠️ Tech Stack
- HTML5, CSS3 (Cyberpunk/Dark Theme)
- Vanilla JavaScript (Geolocation API, Wake Lock API, SpeechSynthesis API, Web Audio API)
- Leaflet.js & OpenStreetMap / CartoDB Dark Matter
- QRCode.js
- Service Worker & Web App Manifest

# Infuusiolaskuri

Infuusiolaskuri is a lightweight, offline‑capable PWA application for calculating infusion dosages.  
It supports automatic unit selection, active‑field highlighting, dosage guidance, and a clean dark mode optimized for clinical environments.

All calculations are performed locally in the browser — no data is sent to any server.

### Features
- Installable on Android, iOS, Windows, macOS
- Works fully offline via a service worker
- Automatically updates when online
- Includes perfusor‑style icons (192/256/512 px)

### Real‑time dosage calculations
- ml/h  
- mg/h  
- mg/kg/h  
- µg/kg/h  
- µg/kg/min  

Values update instantly as the user enters data.

### Automatic unit selection
Units switch automatically depending on the selected drug  
(e.g., mg/kg/h for mg‑based drugs, µg/kg/min for µg‑based drugs).

### Active‑field highlighting
The currently edited field is highlighted, and the alternative input is disabled to prevent conflicting entries.

### Dosage guidance
Each drug includes recommended dosing ranges and warnings.

### Dark mode
- Automatically follows the system theme (`prefers-color-scheme`)
- Designed for readability in low‑light clinical settings

## 📦 Project structure

index.html
app.js
manifest.json
sw.js
icon-192.png
icon-256.png
icon-512.png


All files must be placed in the project root.

## 

Installation on devices
Android
Open the app in Chrome

Menu → “Add to Home screen”

iOS
Open in Safari

Share → “Add to Home Screen”

Disclaimer
This tool assists with infusion calculations but does not replace clinical judgment.
Users are responsible for verifying all dosages and ensuring safe medical practice.


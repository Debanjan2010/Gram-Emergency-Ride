# Gram-Emergency Ride

**Smart Rural Emergency Transport Coordination**

Gram-Emergency Ride is a student design-thinking prototype exploring how people in rural communities could coordinate transport during an emergency. It demonstrates a simple request flow that can connect a patient or family member with nearby local drivers, while keeping official emergency services as the first point of contact for life-threatening situations.

> **Prototype only:** This project does not contact emergency services, dispatch real drivers, verify providers, or provide medical care. For a real emergency in India, call **112**, **108**, or **102** as appropriate.

## Features

- Guided emergency request and location-confirmation flow
- Simulated nearby-driver matching and request status
- App, SMS, and IVR/voice-call interaction demonstrations
- Sample nearby hospitals and health centres
- Responsive layout for mobile and desktop
- Safety notes covering official-service escalation, consent, and prototype limitations

All requests, driver activity, and communication flows are demonstrations; no real dispatch or backend service is connected.

## Run locally

No build step or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

Alternatively, run a local static server from this folder:

```powershell
py -m http.server 8000
```

Then open <http://localhost:8000>.

The page loads Tailwind CSS, Font Awesome, and the Manrope font from CDNs, so an internet connection is needed for those assets. The core page is a standalone HTML file with inline CSS and JavaScript.

## Project files

- `index.html` — page layout, styling, and prototype interactions
- `founder.jpeg` — founder photo used in the page credits

## Project credit

Created by **Debanjan Ghosh** — Founder & Developer  
**Team 5290 · Design Thinking Project · Prototype build**

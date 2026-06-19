# PureView
*pronounced purview*

A minimal AR heads-up display designed for wearable glasses. Everything visible has a purpose.

**[Launch PureView →](https://BzBuck.github.io/Pureview)**

---

### What it shows

- Compass heading with scrolling tape
- Local time and date
- Ambient temperature (via weather API)
- Speed, elevation
- Neighborhood + city name (reverse geocoded)
- Live rear camera feed
- Scalable map — tap to toggle street/satellite view

### How to use

Open on your phone in Safari. Tap **Initialize**, grant camera and location access. Add to Home Screen for a fullscreen, app-like experience.

Best used in landscape orientation.

### Stack

Plain HTML/JS. No build step, no framework, no dependencies except [Leaflet](https://leafletjs.com) for the map. Data from [Open-Meteo](https://open-meteo.com) (weather) and [Nominatim](https://nominatim.org) (geocoding).

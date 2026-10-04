# SmartPark

> Parking availability and booking interface prototype using simulated parking-lot data.

## Overview

SmartPark demonstrates a browser-based parking search and booking workflow. Users can filter facilities, compare prices and amenities, and create a mock booking.

**Current implementation:** parking availability, prices, ratings, and facilities are simulated in client-side JavaScript. There is no live sensor or booking backend.

## Features

- Search by location/area text
- Maximum-price filtering
- Amenity filtering
- Availability display
- Hourly and daily price comparison
- Mock booking workflow with cost calculation
- Responsive interface

## Tech stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Browser APIs

## Run locally

Open `SmartPark.html` in a modern browser, or serve the directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/SmartPark.html`.

## Data and limitations

The application is a prototype. Facility names, occupancy, prices, ratings, and amenities are sample data and are not live parking availability.

## Future work

- Live occupancy or sensor integration
- Backend booking API
- Authentication and booking history
- Map/GPS navigation
- Server-side validation and persistence
- Formal accessibility testing

## License

GPL-3.0

# SmartPark

> Browser-based parking search and booking prototype using simulated parking-lot data.

## Overview

SmartPark demonstrates a parking discovery and mock-booking workflow. Users can filter sample facilities by location text, maximum hourly price, and amenities, then create a local mock booking.

The current application is **client-side only**. It has no live occupancy feed, sensor integration, booking backend, authentication service, or server-side persistence.

## Features

- Search by location or parking-lot name
- Maximum hourly-price filter
- Amenity filters
- Availability display using sample data
- Hourly and daily price comparison
- Mock booking with local cost calculation
- Responsive browser interface
- Sample reviews and ratings

## Data and limitations

Parking-lot names, occupancy/availability, prices, ratings, amenities, and reviews are sample data embedded in the page.

The application does not contact a live parking provider or sensor network, and a booking is only a prototype interaction.

## Run locally

Open `SmartPark.html` directly, or serve the directory:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/SmartPark.html
```

## Roadmap

- Live occupancy/sensor integration
- Backend booking API
- Authentication and booking history
- Map/GPS integration
- Server-side validation and persistence
- Accessibility testing

## License

See [LICENSE](LICENSE).

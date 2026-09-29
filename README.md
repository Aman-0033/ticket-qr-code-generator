# Ticket QR Code Generator Worker

A high-reliability, client-side digital pass and QR code generation worker designed for event floor operations and venue management.

## Features

- **Monochromatic SaaS Design**: High-contrast, clean grayscale interface adhering strictly to venue operational aesthetics.
- **Client-Side QR Generation**: Instant, secure QR code rendering with offline resilience.
- **Viewfinder Framing**: Precision-styled digital pass framing with camera-viewfinder corner brackets.
- **Micro-Interactions**: Animated focus rings, loading states, and responsive layout for mobile and desktop scanners.
- **Input Validation & Security**: Native sanitization and error alerting for required attendee credentials.

## Tech Stack

- **HTML5 & CSS3**: Pure modern CSS with custom design tokens, radial gradients, and layered shadows.
- **Vanilla JavaScript**: ES6 class architecture with zero framework overhead.
- **QRCode.js**: Lightweight client-side QR generation engine.

## Getting Started

Open `index.html` directly in any modern browser, or serve it using any static HTTP server:

```bash
# Example using Python
python -m http.server 8000
```

## License

MIT License

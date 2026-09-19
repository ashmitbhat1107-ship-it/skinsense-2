# SkinSense

SkinSense is a browser-based UV & skin-health companion.

## Features
- UV index dashboard and gauge
- UV sensor/device simulation
- Reading history
- Climate/weather context
- Sunscreen protection tracking
- Thermal/stress monitoring
- Notifications and local profile/session storage
- AI assistant interface

## GitHub Pages
The app is a static HTML application and includes a GitHub Actions deployment workflow.

## Security note
The AI assistant currently calls the Anthropic API from browser-side JavaScript. A production deployment should route that request through a server-side/serverless proxy so an API credential is never exposed in client code. The static app does not require a backend for its non-AI features.

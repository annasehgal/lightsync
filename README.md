# LightSync

LightSync is a lightweight web application for coordinating synchronized screen displays across multiple mobile devices during live events.

## Overview

The system allows participants to open a shared link, preload display content, and activate a visual message at the same time. It is designed for environments with high network congestion (e.g., stadiums or large gatherings) and prioritizes reliability over complexity.

## Design Goals

- Minimize server load through client-side rendering
- Pre-fetch and cache display content on initial load
- Support simple broadcast-based triggering
- Provide a manual fallback trigger in case of latency
- Require no accounts or personal data

## Architecture

LightSync follows a minimal architecture:

- Mobile-first web frontend
- Lightweight backend for message configuration and trigger state
- Polling or WebSocket-based synchronization
- Static asset caching to reduce repeat requests

## Intended Use

LightSync was created to support short, coordinated visual moments at live events. The system can be adapted for concerts, campus events, conferences, or other large-scale gatherings.

## Status

Prototype in active development.

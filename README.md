# CampusPrint

A solar-powered, self-service campus printing and vending station.

## Project

CampusPrint is designed to let students submit print jobs, provide payment details, collect printouts and receive eligible rewards with minimal staff involvement. The long-term system is intended to operate outdoors using solar power and to remain useful during unreliable internet connectivity.

## Repository structure

- `src/main/java/` — Java application source code.
- `src/test/java/` — Java tests.
- `docs/` — Requirements, workflows, architecture and project decisions.
- `diagrams/` — UML, system flowcharts and architecture diagrams.
- `hardware/power/` — Solar generation, battery and power-management design.
- `hardware/electronics/` — Sensors, controllers, printer and vending electronics.
- `hardware/enclosure/` — Outdoor kiosk, umbrella, weather protection and physical layout.
- `firmware/` — Future microcontroller firmware, including ESP32 integration.
- `data/` — Database design, local storage and synchronisation documentation.
- `assets/` — Project reference images and approved design assets.

## Current stage

Initial repository setup and Java Swing learning. No hardware or external service integrations are implemented yet.

## Development principles

- Build and test the Java application in small increments.
- Design for local operation when internet connectivity is unavailable.
- Verify payments through a trusted source before releasing print jobs.
- Keep hardware and firmware work separate from the Java application.
- Document decisions and integration requirements before implementation.

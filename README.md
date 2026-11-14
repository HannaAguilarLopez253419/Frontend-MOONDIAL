# MoonDial · Frontend

Web app to compare lunar landing sites and dates. Pick a site and a time, see where the Sun and the Earth sit above the local horizon, and understand what that means for solar power and direct-to-Earth communication.

Built by team **ORYSEL** for the NASA Space Apps Challenge 2026 (*Lunar Landing Site Navigator*), Tuxtla Gutiérrez node. MoonDial is a working name.

## Features

- **Catalog**: landing sites with their data source, filters and custom coordinates.
- **Site view**: time bar with play, horizon with Sun and Earth, sunset and Earthset countdowns, verdict (Viable, Marginal, Not viable).
- **Compare**: site and date scenarios side by side, with a "What if we slip the landing?" slider.
- **About the data**: NASA sources, check against JPL Horizons, limitations and AI use.
- **Explain mode** with three levels: specialist, general public and educator.
- **English and Spanish** interface.
- **Accessible**: color-blind-friendly palette, never color alone, keyboard support.

## Stack

React · Tailwind CSS · HTML · JavaScript

## Getting started

```bash
git clone https://github.com/HannaAguilarLopez253419/Frontend-MOONDIAL.git
cd Frontend-MOONDIAL
npm install
npm run dev
```

## Data

The app reads data from the backend API or from precomputed JSON files per site. Any value labelled "Sample data" is illustrative and is not a mission-planning result. All data comes from open NASA sources and every coordinate shows its source.

## Contributing

- Work on a branch and open a pull request into `main`.
- Ask the other frontend collaborator for a review before merging.
- All code is written during the event, in this repository.

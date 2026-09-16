# GardenGuide Australia

Mobile-first Australian gardening companion and installable PWA.

## Current feature set

- Searchable plant library spanning vegetables, herbs, fruit, flowers, ornamentals and Australian native/edible plants
- Detailed sowing/propagation, depth, spacing, harvest, sunlight, watering, climate and growing tips where curated guide data is available
- Safe category-based fallback guidance for catalogue entries awaiting species-specific curation
- Australian climate zones: cool/temperate, temperate, subtropical, tropical and arid/semi-arid
- Optional browser geolocation with automatic broad climate-zone selection
- Live local temperature, seven-day rainfall total and frost-risk indicator when online
- Plant Now recommendations based on selected zone, season and available planting-guide data
- My Garden favourites
- Planting records, garden beds and basic crop-family rotation warnings
- Estimated harvest outlook
- Seed Library with A–Z, Z–A, planting-season and Plant Now-first sorting
- Common pest and disease/problem guide
- Soil-type and soil-improvement guide
- Seasonal garden-job checklist
- Browser notification permission/reminder setting
- Plant Doctor photo capture plus symptom-based safety-first triage
- Offline application shell and plant-guide data caching through the service worker

## Data quality

GardenGuide distinguishes curated plant-specific records from broader catalogue fallbacks. Planting dates always need adjustment for local frost, rainfall, elevation, microclimate and cultivar.

## Plant Doctor

The current Plant Doctor performs photo capture and guided symptom triage locally. True AI image recognition requires a secure model/backend integration; no API secret is embedded in this public client-side repository.

# Delhi Urban Acre

An interactive geospatial mapping interface and valuation index covering **290 municipal wards** (MCD, NDMC, and Cantonment) across Delhi, built to benchmark local housing rates, pricing tiers, and urban infrastructure density.

## Overview

Delhi's real estate market operates on a micro-local scale where property values vary drastically across municipal boundaries—from ₹3,000/sq.ft in outer resettlement colonies to over ₹50,000/sq.ft in prime diplomatic enclaves. This project visualizes these variations through an interactive Leaflet mapping interface combined with built-in analytics tools, including a side-by-side ward comparison engine and an EMI calculator.

## Key Features

* **Interactive Ward Mapping (290 Wards):** Leaflet-powered geospatial vector rendering across MCD, NDMC, and Cantonment administrative boundaries.
* **Tier-Based Price Indexing:** Categorizes localities into High, Medium, and Low price tiers based on estimated average rates per square foot.
* **Comprehensive Ward Drawers:** Detailed side panels displaying estimated price ranges, predominant property types, transit access, localized school directory data (DoE unaided directory), and medical facility counts.
* **Side-by-Side Ward Comparison Engine:** Benchmark any two wards head-to-head across pricing metrics, property categories, and valuation spreads.
* **Integrated EMI & Mortgage Planner:** Real-time loan breakdown modeling principal versus interest, down payment thresholds, and adjustable tenures.
* **Contextual Visual & Design System:** Custom aesthetic palette inspired by Delhi's red-sandstone heritage monuments, traditional jali motifs, and parchment revenue mapping styles.

## Tech Stack & Architecture

* **Core Application:** Single-file web application architecture (`delhi_Urban_acre.html`) containing embedded UI layout, styles, and client-side application logic.
* **Frontend Languages:** HTML5, CSS3 (Custom Design Tokens, Flexbox, CSS Grid), Vanilla JavaScript (ES6+).
* **Geospatial & Mapping:** Leaflet.js (`1.9.4`) with GeoJSON vector data layer integration.
* **UI Components:** Custom slide-out detail drawers, side-by-side ward comparison modal windows, interactive data tables, and dynamic range inputs.
* **Typography:** Google Fonts (Fraunces for display headings, Space Grotesk for monetary/numerical metrics, Inter for body text).
* **Data Sources:** Municipal ward boundary geometry and civic metadata referenced via Oorvani Foundation / OpenCity (`CC-BY-SA-4.0`).

## Getting Started

1. **Clone or Download the Repository:**
   ```bash
   git clone [https://github.com/mehrashiva13399-cyber/Delhi-Urban-Acre.git](https://github.com/mehrashiva13399-cyber/Delhi-Urban-Acre.git)

# Cooltive

**AI-powered Urban Climate & Site Intelligence Platform**
*Grow Cooler Cities, One Decision at a Time.*


## What is Cooltive?

Cooltive helps real estate developers, consulting firms, and engineers analyze a site **before and during design**, and make design decisions based on data instead of experience or manual estimation alone.

The platform ingests site data — temperature, green area coverage, building density, sun exposure, shading, wind, and more — from IoT sensors, satellite imagery, and weather APIs, then uses AI to identify areas and factors negatively affecting **Outdoor Comfort** (starting with Urban Heat Island risk).

## What it delivers

- **Site Assessment & Environmental Report** — current site status, key problem areas, contributing factors, and a data-driven Future Outlook
- **Findings & Recommendations** — ranked mitigation options (e.g. increased green cover, shading structures, material changes) compared by expected impact, feasibility, and preliminary cost
- **Scenario Comparison** — current state vs. proposed interventions, to support developer/consultant decision-making

## MVP Scope

The MVP focuses on **Urban Heat** as the first strong use case: IoT + satellite + weather data → AI-based risk classification → prescriptive, cost-aware recommendations.

## Roadmap

The architecture is designed to extend without a rebuild:
- **Year-round intelligence**: winter use cases (rainfall, humidity, air quality, water accumulation prediction) on the same data pipeline
- **Design-phase support**: pre-design site insights for engineers, reducing manual site analysis time
- **3D Architecture Simulation**: a digital twin of the project enabling virtual walkthroughs — usable both as a real estate marketing tool and, more importantly, connected to the same Analysis Engine to simulate the impact of design changes
- **Smart City expansion**: broader environmental intelligence use cases beyond individual sites

## Tech Direction

- Backend: .NET
- AI/ML: Python (satellite & sensor data processing, prediction models)
- Data sources: IoT sensors, satellite imagery (Landsat, Sentinel-3/SLSTR, ECOSTRESS), weather APIs (ERA5)

---
*This README will be expanded with setup instructions, architecture diagrams, and API documentation as the codebase develops.*

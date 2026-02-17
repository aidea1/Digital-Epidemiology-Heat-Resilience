# Digital-Epidemiology-Heat-Resilience
A Digital Twin framework for the Southwestern US identifying 'Critical Deserts' - zones where extreme heat and infrastructure latency create a 100% resource deficit. Quantifying a $49.25M systemic risk through digital epidemiology and predictive asset sensing.

[![Status](https://img.shields.io/badge/Status-Active-green.svg)]()
[![Location](https://img.shields.io/badge/Region-Southwest_US-orange.svg)]()

### Project Overview
Developed in collaboration with **Professor Michelle Williams (Stanford University)**, the **APSO (Advanced Preparedness & Shelter Operations) Resilience System** is a digital epidemiological framework designed to identify "Critical Deserts"—geographic zones where extreme heat poses an immediate lethal risk due to a total lack of operational infrastructure.


### The Problem: "The Deadly Gap"
Static resource maps are failing. Our research identifies a profound **Operational Latency**: cooling centers often appear on maps but are closed during peak heat cycles (13:00–17:00).
* **Survival Window:** At temperatures >110°F, heatstroke becomes fatal 70% more often if care is delayed by over 60 minutes.
* **Economic Risk:** Our system identifies a **$49.25 million systemic risk** in the Southwest, with each "Critical Desert" station representing a $197,000 seasonal cost in emergency ICU admissions.

### Methodology & Tech Stack
The system functions as a "Digital Twin" of the Arizona-California Heat Belt using three intelligence layers:
1. **Climatological Modeling:** 10 years of GHCN-Daily data used to establish longitudinal exposure means.
2. **Synchronous Asset Sensing:** Integration with the **Google Places V1 API** to simulate real-time operational status (e.g., verifying if a library is actually open at 3 PM on a 115°F Monday).
3. **Public Welfare Risk Score (PWRS):** A proprietary metric quantifying the intersection of environmental stress and infrastructural absence.

### Key Results
An audit of 250 primary nodes revealed:
| Location | Avg July Max | Status |
| :--- | :--- | :--- |
| Death Valley NP, CA | 121.9°F | **CRITICAL DESERT** |
| Needles Airport, CA | 116.2°F | **CRITICAL DESERT** |
| Phoenix Airport, AZ | 114.7°F | **CRITICAL DESERT** |
| Ajo, AZ | 111.9°F | **CRITICAL DESERT** |

* **100% Resource Deficit:** Every analyzed node showed zero searchable survival assets during peak heat simulations.

### The Solution: Activation over Auditing
We propose a shift from documenting heat illness to active prevention via:
* **Mobile Resilience Nodes (MRNs):** Retrofitted, solar-powered units deployed to GPS-validated deserts.
* **Algorithmic Activation:** Triggering operational mandates for state buildings based on PWRS data.

### 📂 Repository Structure
* `/data`: Contains `apso_vulnerability_deep_dive.csv` and historical GHCN datasets.
* `/map`: Contains `index.html` (Interactive Resilience Map).
* `/docs`: Full white paper and methodology details.

---
**Lead Researcher:** Akshaya Bhagavathula  
**Date:** February 10, 2026

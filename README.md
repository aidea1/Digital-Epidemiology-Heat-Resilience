# Digital-Epidemiology-Heat-Resilience

A Digital Twin framework for the Southwestern US identifying 'Critical Deserts'—zones where extreme heat and infrastructure latency create a 100% resource deficit. This project quantifies a $49.25M systemic risk through digital epidemiology and predictive asset sensing.

**Link to Interactive Map:** [aidea1.github.io/Digital-Epidemiology-Heat-Resilience/](https://aidea1.github.io/Digital-Epidemiology-Heat-Resilience/)  
**Official Website:** [www.epiaidea.com](http://www.epiaidea.com)

---

[![Status](https://img.shields.io/badge/Status-Active-green.svg)]()
[![Location](https://img.shields.io/badge/Region-Southwest_US-orange.svg)]()
[![Affiliation](https://img.shields.io/badge/Affiliation-Stanford_University-red.svg)]()
[![Affiliation](https://img.shields.io/badge/Affiliation-North_Dakota_State_University-green.svg)]()

### Project Overview
Developed in collaboration with **Professor Michelle Williams (Stanford University)**, the **APSO (Advanced Preparedness & Shelter Operations) Resilience System** is a digital epidemiological framework. It is designed to identify "Critical Deserts"—geographic zones where extreme heat poses an immediate lethal risk due to a total lack of operational infrastructure.

### The Problem: Infrastructure Latency and the Deadly Gap
Static resource maps often fail to account for **Operational Latency**: the reality that a cooling center is ineffective if it remains closed during peak heat cycles (13:00–17:00).

* **Biological Survival Window:** At temperatures exceeding 110°F, human thermoregulation reaches a breaking point. If Time to Care (TTC) exceeds 60 minutes, the probability of fatal heatstroke increases by over 70%.
* **The Resilience Deficit:** 100% of analyzed nodes showed zero searchable survival assets during peak 3:00 PM heat simulations.
* **Economic Risk:** The system identifies a **$49.25 million systemic risk** in the Southwest. Each "Critical Desert" station represents a **$197,000 seasonal risk** based on 10 emergency ICU admissions.

### Methodology and Tech Stack
The system functions as a "Digital Twin" of the Arizona-California Heat Belt using three intelligence layers:

1. **Climatological Modeling:** 10 years of GHCN-Daily data used to establish a "Longitudinal Exposure Mean".
2. **Synchronous Asset Sensing:** Integration with the **Google Places V1 API** to simulate real-time operational status during peak stress.
3. **Public Welfare Risk Score (PWRS):** A proprietary metric quantifying the intensification of social vulnerability when environmental stress meets infrastructural absence.

#### The PWRS Formula
To quantify the "Resilience Void," the following formula is applied:

$$PWRS = (Avg\_July\_MaxT \times 0.8) + (Isolation\_Factor)$$

* **$Avg\_July\_MaxT$**: The 10-year longitudinal exposure mean established via GHCN-Daily data.
* **$Isolation\_Factor$**: A **+20 penalty** applied to "zero-asset" saturation zones where no operational lifelines are detected.

### Key Results: The Lethal Corridor
An audit of 250 primary nodes identified **2,530 Critical Desert points**.

| Station Name | State | Avg July Max | PWRS | Status |
| :--- | :--- | :--- | :--- | :--- |
| Death Valley NP | CA | 121.9°F | 117.50 | CRITICAL DESERT |
| Needles Airport | CA | 116.2°F | 112.95 | CRITICAL DESERT |
| Tacna 3 NE | AZ | 115.0°F | 112.03 | CRITICAL DESERT |
| Phoenix Airport | AZ | 114.7°F | 111.74 | CRITICAL DESERT |
| Ajo | AZ | 111.9°F | 109.52 | CRITICAL DESERT |

### The Solution: Activation over Auditing
The APSO Ecosystem proposes a transition from documenting illness to active prevention:
* **Mobile Resilience Nodes (MRNs):** Deploying retrofitted, solar-powered units to GPS-validated deserts.
* **Algorithmic Activation:** Triggering "Operational Mandates" for state buildings using PWRS data to ensure they remain open during the 13:00–17:00 peak heat window.

### Repository Structure
* `/data`: Contains `apso_vulnerability_deep_dive.csv` and historical GHCN datasets.
* `/map`: Contains `index.html` (Interactive Resilience Map).
* `/docs`: Full white paper and methodology details.

### Collaboration and Credentials
* **Lead Researcher:** Akshaya Bhagavathula
* **Academic Partner:** Professor Michelle Williams, Stanford University
* **Institutional Affiliations:** Stanford University, North Dakota State University.
* **Institutional Context:** Designed as a decision-support engine for the Governor’s Office of Resiliency and DEMA.

### License
This project is licensed under the **MIT License**.

---
**Date:** February 10, 2026  
*Resilience is not a status; it is a synchronous response.*

# Digital-Epidemiology-Heat-Resilience

[cite_start]A Digital Twin framework for the Southwestern US identifying 'Critical Deserts'—zones where extreme heat and infrastructure latency create a 100% resource deficit[cite: 5, 6, 44]. [cite_start]Quantifying a $49.25M systemic risk through digital epidemiology and predictive asset sensing[cite: 7, 35]. 

**🔗 View the Interactive Map:** [aidea1.github.io/Digital-Epidemiology-Heat-Resilience/](https://aidea1.github.io/Digital-Epidemiology-Heat-Resilience/)

[![Status](https://img.shields.io/badge/Status-Active-green.svg)]()
[![Location](https://img.shields.io/badge/Region-Southwest_US-orange.svg)]()
[![Affiliation](https://img.shields.io/badge/Affiliation-Stanford_University-red.svg)]()
[![Affiliation](https://img.shields.io/badge/Affiliation-North_Dakota_State_University-red.svg)]()
### 🔬 Project Overview
[cite_start]Developed in collaboration with **Professor Michelle Williams (Stanford University)**, the **APSO (Advanced Preparedness & Shelter Operations) Resilience System** is a digital epidemiological framework designed to identify "Critical Deserts"—geographic zones where extreme heat poses an immediate lethal risk due to a total lack of operational infrastructure[cite: 5, 6].

### The Problem: "The Deadly Gap"
[cite_start]Static resource maps fail to account for **Operational Latency**: the reality that a cooling center on a map is useless if it is closed during the peak of a heat cycle (13:00–17:00)[cite: 9, 10, 41].

* [cite_start]**Biological Survival Window:** At temperatures exceeding 110°F, human thermoregulation reaches a breaking point[cite: 12]. [cite_start]If Time to Care (TTC) exceeds 60 minutes, the probability of fatal heatstroke increases by over 70%[cite: 13].
* [cite_start]**The Resilience Deficit:** 100% of analyzed nodes showed zero searchable survival assets during peak 3:00 PM heat simulations, despite historical peaks of 118°F[cite: 16, 44].
* [cite_start]**Economic Risk:** The system identifies a **$49.25 million systemic risk** in the Southwest[cite: 7, 35, 45]. [cite_start]Each "Critical Desert" station represents a **$197,000 seasonal cost** in emergency ICU admissions[cite: 36].

### 🛠️ Methodology & Tech Stack
[cite_start]The system functions as a "Digital Twin" of the Arizona-California Heat Belt using three intelligence layers[cite: 18]:

1.  [cite_start]**Climatological Modeling:** 10 years of GHCN-Daily data used to establish a "Longitudinal Exposure Mean"[cite: 19, 20].
2.  [cite_start]**Synchronous Asset Sensing:** Integration with the **Google Places V1 API** to simulate real-time operational status during peak stress (e.g., Monday at 15:00 in July)[cite: 22, 23, 24].
3.  [cite_start]**Public Welfare Risk Score (PWRS):** A proprietary metric quantifying the intensification of social vulnerability when environmental stress meets infrastructural absence[cite: 25, 26, 27].



#### The PWRS Formula
[cite_start]To quantify the "Resilience Void," we apply the following calculation[cite: 25, 26]:
$$PWRS = (Avg\_July\_MaxT \times 0.8) + (Isolation\_Factor)$$
* [cite_start]**Isolation Factor:** A $+20$ penalty for zero-asset saturation[cite: 28].

### Key Results: The Lethal Corridor
[cite_start]An audit of 250 primary nodes identified **2,530 Critical Desert points**[cite: 30, 31, 32].

| Station Name | State | Avg July Max | PWRS | Status |
| :--- | :--- | :--- | :--- | :--- |
| Death Valley NP | CA | 121.9°F | 117.50 | **CRITICAL DESERT** |
| Needles Airport | CA | 116.2°F | 112.95 | **CRITICAL DESERT** |
| Tacna 3 NE | AZ | 115.0°F | 112.03 | **CRITICAL DESERT** |
| Phoenix Airport | AZ | 114.7°F | 111.74 | **CRITICAL DESERT** |
| Ajo | AZ | 111.9°F | 109.52 | **CRITICAL DESERT** |

[cite_start]*(Data derived from `apso_vulnerability_deep_dive.csv` [cite: 33])*

### The Solution: Activation over Auditing
[cite_start]We propose a transition from documenting heat illness to active prevention via the APSO Ecosystem[cite: 37, 38]:
* [cite_start]**Mobile Resilience Nodes (MRNs):** Deploying retrofitted, solar-powered units to GPS-validated deserts[cite: 40].
* [cite_start]**Algorithmic Activation:** Triggering "Operational Mandates" for state buildings using PWRS data to ensure they remain open during peak danger windows[cite: 41].

### Repository Structure
* `/data`: Contains `apso_vulnerability_deep_dive.csv` and historical GHCN datasets.
* `/map`: Contains `index.html` (Interactive Resilience Map).
* `/docs`: Full white paper and methodology details.

### Collaboration & Credentials
* [cite_start]**Lead Researcher:** Akshaya Bhagavathula [cite: 48]
* **Academic Partner:** Professor Michelle Williams, Stanford University.
* [cite_start]**Institutional Context:** This research serves as a decision-support engine for the Governor’s Office of Resiliency and DEMA[cite: 39].

---
**Date:** February 10, 2026 [cite: 49]  
Resilience is not a status; it is a synchronous response.* [cite: 47]

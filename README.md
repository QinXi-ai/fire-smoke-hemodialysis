# Fire Smoke and Hemoglobin in US Hemodialysis Facilities

## Paper

**Annual fire smoke exposure and low hemoglobin in 7,297 United States hemodialysis facilities**

Yitao Zheng¹†, Xi Qin²†, Xin Yin³†, Zetong Wu¹, Zhaocheng Ma¹*

¹ School of Public Health, Wuhan University, Wuhan, China  
² School of Computer Science, Wuhan University, Wuhan, China  
³ Department of Biomedical Engineering, Hubei Province Key Laboratory of Allergy and Immune Related Disease, TaiKang Medical School (School of Basic Medical Sciences), Wuhan University, Wuhan, China

† Equal contribution.  
*Correspondence: Zhaocheng Ma — [mzhaocheng@whu.edu.cn](mailto:mzhaocheng@whu.edu.cn)*

## Overview

Anemia requires continuing monitoring and treatment in maintenance hemodialysis. We examined whether smokier years were associated with a greater recorded low-hemoglobin burden at US dialysis facilities, and assessed how future smoke exposure could affect the geographic footprint of today's dialysis services.

The study links public clinical reports with environmental data, evaluates the information available in annual facility-level surveillance, and maps midcentury smoke scenarios onto the existing dialysis network.

## Study design

| Component | Description |
| --- | --- |
| Design | Retrospective ecological panel study |
| Coverage | 7,297 facilities in 1,825 counties across 48 US states |
| Observation years | 2016–2019 and 2021–2022 |
| Analysis size | 39,393 facility-years; 27.2 million eligible adult hemodialysis patient-months |
| Primary exposure | Annual county-level fire-smoke PM₂.₅ concentration |
| Primary outcome | Percentage of eligible patient-months with recorded hemoglobin below 10 g/dL |
| Primary model | Patient-month-weighted regression with facility and state-by-year effects, adjusted for non-smoke PM₂.₅, annual mean temperature, and hot-day count |

Clinical outcomes came from CMS Dialysis Facility Reports. Historical facility locations were linked to county smoke and weather estimates. The source-defined fire-smoke measure includes smoke identified through plume observations, which can encompass wildfire, prescribed burning, and agricultural burning. The year 2020 was excluded because the clinical source omitted its first six months.

## Main findings

- **Annual clinical association:** Each 1 µg/m³ higher annual smoke PM₂.₅ was associated with a **0.03-percentage-point** difference in recorded low-hemoglobin burden (county-clustered nominal 95% interval: **−0.13 to 0.18**). The annual background burden was approximately **21–24%**. Supporting hemoglobin and recording outcomes also showed estimates close to zero.
- **Surveillance and uncertainty:** California contributed **68.4%** of the adjusted smoke variation used for estimation. Sensitivity analyses and 12,000 simulated outcome datasets examined how exposure concentration and spatial and temporal dependence affected inference. Interval coverage varied with the assumed error process.
- **Retrospective prediction:** A validation-selected modeling workflow including smoke reduced weighted prediction error relative to carrying forward the previous observation by **9.0% in 2021**, **8.0% in 2022**, and **6.8% when entire states were held out**. Paired comparisons within model families found little consistent additional predictive information from smoke itself.
- **Midcentury exposure:** Across 28 climate models, projected smoke concentrations at the existing dialysis network reached **2.4–3.0 times** the scenario source's historical baseline by **2046–2055**. The scenario analysis matched **6,600 facilities**, covering **95.3%** of 2022 patient-month weight.

| Emissions scenario | Median 2046–2055 smoke PM₂.₅ | Multiple of historical network baseline | Median share of matched patient-month weight in counties exceeding twice their own historical smoke exposure |
| --- | ---: | ---: | ---: |
| SSP1–2.6 | 1.020 µg/m³ | 2.4× | 56.7% |
| SSP2–4.5 | 1.167 µg/m³ | 2.7× | 69.3% |
| SSP3–7.0 | 1.305 µg/m³ | 3.0× | 77.8% |

The scenario-source historical period is 2011–2020, with a network baseline of 0.434 µg/m³. These summaries hold the observed 2022 facility distribution and patient-month weights fixed and describe future exposure at those locations.

## Interpretation

The study's contribution is twofold: it characterizes the information and uncertainty in annual aggregate surveillance of smoke and low hemoglobin, and quantifies the dialysis service footprint facing substantially higher smoke exposure under published climate scenarios. Short-term clinical responses and treatment changes require more detailed longitudinal patient records. Exploratory reanalysis of two public airway-cell wood-smoke experiments provides biological context, with responses varying by experimental system and exposure pattern.

## About this repository

Related data and analysis code will be released progressively after the paper is accepted.

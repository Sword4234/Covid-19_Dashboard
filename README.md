# 🦠 COVID-19 Global Policy & Epidemiological Dynamics Dashboard

An interactive analytics suite examining the intersection of government policy interventions, public compliance, vaccination velocity, and clinical healthcare burdens during the COVID-19 pandemic. Built with **Tableau** and integrated into a custom **JavaScript API** web application deployed via **GitHub Pages**.

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2563eb?style=for-the-badge&logo=github)](https://sword4234.github.io/Covid-19_Dashboard/)
[![Tableau Public](https://img.shields.io/badge/Tableau_Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/views/COVID19DashboardBasedOnGovernmentStringency/D1-GlobalPathogenDispersionContainmentPolicyDynamics)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

---

## 📌 Live Demo

Access the interactive web portal here:  
👉 **[COVID-19 Analytics Dashboard Live Web App](https://sword4234.github.io/Covid-19_Dashboard/)**

---

## 📖 Project Overview

This dashboard synthesizes global policy timelines against clinical transmission metrics to evaluate the real-world efficacy of non-pharmaceutical interventions (NPIs). Using the **Oxford COVID-19 Government Response Tracker (OxCGRT)** stringency index alongside international public health datasets, it analyzes:

- **Transmission Velocity vs. Policy Strictness:** How fast sovereign lockdown and restriction mandates altered infection trajectories.
- **Mobility Deviations:** Quantifying public movement behavior across retail, transit, and workplace sectors under shifting stringency tiers.
- **Vaccine Rollout & Containment Realignment:** How immunization scale enabled relaxation of containment policies.
- **Clinical Strain:** Intensive care unit (ICU) admissions and mortality metrics across differing socio-economic brackets.

---

## 🖥️ Dashboards & Analytical Modules

### 1. 🌍🛡️ Global Spread & Containment
> Evaluates geospatial pathogen dispersion alongside sovereign containment policy rollouts and identifies the top 10 disproportionately impacted nations by infection density.

- **Key Metrics:** Infection Rate per 100k, Cumulative Global Dispersion, Stringency Index Timeline.
- **Visual Models:** Geospatial Chloropleth Map, Ranked Horizontal Bar Charts, Dual-Axis Policy vs. Mobility Timelines.

<!-- Replace the path below with your uploaded image -->
![Global Spread & Containment](<img width="1279" height="779" alt="image" src="https://github.com/user-attachments/assets/ee253ea9-259b-4018-b917-3a89ee0b46e3" />
)

---

### 2. 📋🏛️ Response Stringency
> Deep dive into sovereign government response metrics, detailing the speed, duration, and severity of emergency declarations and lockdown protocols.

- **Key Metrics:** Oxford Stringency Index (0–100), School & Workplace Closures, Public Event Cancellations.
- **Visual Models:** Comparative Temporal Area Charts, Multi-Country Strictness Indices.

![Response Stringency](<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/7c6323e1-4998-426e-b495-9e16965262fa" />
)

---

### 3. 💉🚀 Vaccine Rollout
> Tracks international immunization cadence from emergency authorization to mass population coverage, contrasting procurement speeds across regions.

- **Key Metrics:** Doses Administered per 100 People, Fully Vaccinated Population Share, Rolling 7-Day Vaccination Averages.
- **Visual Models:** Uptake S-Curves, Geographic Penetration Heatmaps.

![Vaccine Rollout](<img width="1280" height="799" alt="image" src="https://github.com/user-attachments/assets/ca9bf5a3-15bc-4d58-9cfd-b52926270073" />
)

---

### 4. 🔒🚶 Stringency & Public Mobility
> Analyzes citizen compliance by tracking Google Mobility data against government restriction tiers.

- **Key Metrics:** Mobility Percent Variance (Transit, Retail/Recreation, Workplace, Residential), Policy Stringency Tiers.
- **Visual Models:** Sankey Flow Escalation Cascades, Statistical Box-and-Whisker Dispersion, Parallel Coordinate Trajectories.

![Stringency & Public Mobility](<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/f17ca185-ab29-4d49-ad5d-5125a30c90dc" />
)

---

### 5. 👥💰 Socio-Economic Factors
> Explores how baseline socio-economic determinants—such as GDP per capita, HDI, population density, and health infrastructure capacity—governed epidemic outcomes.

- **Key Metrics:** GDP per Capita, Hospital Beds per 1,000 People, Age Demographic Distributions.
- **Visual Models:** Correlation Scatter Plots, Multi-Variable Regression Clusters.

![Socio-Economic Factors](<img width="1280" height="781" alt="image" src="https://github.com/user-attachments/assets/9983ee68-56c9-4d3e-be39-996e09ab3bc3" />
)

---

### 6. 🏥💔 Clinical Burden & Mortality
> Focuses on critical acute care capacity limits, tracking hospitalization rates, ICU saturation points, and case fatality ratios (CFR).

- **Key Metrics:** ICU Capacity Utilization, Excess Mortality, Case Fatality Ratio (CFR).
- **Visual Models:** Capacity Threshold Bullet Graphs, Longitudinal Fatality Trajectories.

![Clinical Burden & Mortality](<img width="1280" height="777" alt="image" src="https://github.com/user-attachments/assets/1da30437-2f09-47d1-8212-4cc6f99e6ef5" />
)

---

## 🛠️ Architecture & Technical Implementation

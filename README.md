# LifeLane Governance Hub — TCS iON AI Hackathon 🚦

**Author:** Shreyas Padmashali | Aspiring Data Analyst  
**Project Scope:** Live Web Dashboard, Executive Presentation Deck, Root Cause Analysis & Data Architecture

---

### 🌐 Quick Access & Deliverables
* 🚀 **[Launch Live Interactive Web App](https://lifelane-signal-compass.lovable.app/)**
* 📊 **[View Executive Presentation Deck (PDF)](LifeLane_Governance_Hub_Executive_Presentation.pdf)**
* 📄 **[View 5-Whys Root Cause Analysis & Build Plan (PDF)](TCSiON_Hackathon_Task.pdf)**

---

## 📌 Project Overview
The **LifeLane Governance Hub** is an urban traffic management and data governance platform designed for the TCS iON AI Hackathon. It bridges the critical operational data gap between Emergency Medical Services (EMS) dispatchers and city traffic control authorities to eliminate emergency vehicle delays at congested intersections.

## 🔍 Problem Statement & 5-Whys Root Cause Analysis
* **The Challenge:** Emergency vehicles and ambulances lose life-saving minutes stuck at static, fixed-timer traffic intersections during trauma and cardiac calls.
* **Root Cause (5 Whys):** Traffic signal systems are governed, specified, and evaluated separately from emergency medical services. Transport and urban planning authorities operate on throughput KPIs, while health agencies own survival metrics, leaving zero integrated data infrastructure or automated priority protocols.

---

## 🛠️ Executive Dashboard Showcase & Key Insights

### 1. Dashboard Overview & Accountability Tracker
* **Visual Focus:** High-level metrics tracking average signal delay (33.0s), active emergency corridors, and an intersection-level ownership matrix.
* **Executive Insights:** Assigns clear agency ownership (e.g., State Highways vs. City Traffic Dept) and identifies outdated signal controllers (e.g., Hosur Rd & Silk Board carrying 52.7s average delay) to drive operational accountability.

![Dashboard Overview](Dashboard%20Overview.png)

### 2. Incident Timeline
* **Visual Focus:** Incident-level event timeline tracking EMS trip logs (`EMS-2026-10-4471`) against signal states (Green/Yellow/Red) and cumulative lost time.
* **Executive Insights:** Isolates exact points of friction along an emergency route. Identifies non-preempted signals (e.g., INT-1003 contributing 61s delay) to justify signal controller upgrades.

![Incident Timeline](Incident%20Timeline.png)

### 3. Predictive Forecaster
* **Visual Focus:** Hourly predicted delay heat map across the metro grid (09:00 Peak) paired with a delay vs. preemption scatter plot.
* **Executive Insights:** Enables traffic authorities to proactively deploy signal override protocols before peak congestion cycles (e.g., Monday 09:00 peak on INT-1003 reaching risk score 61).

![Predictive Forecaster](Predictive%20Forecaster.png)

### 4. Priority Simulator
* **Visual Focus:** Interactive simulation module testing rule parameters ("Mild priority" vs. "Full preemption") across historical trip data.
* **Executive Insights:** Demonstrates a **7.7% delay reduction** (lowering average delay from 30.8s to 28.5s across targeted intersections) prior to physical infrastructure deployment.

![Priority Simulator](Priority%20Simulator.png)

### 5. Signal Analytics
* **Visual Focus:** Bar chart ranking intersections by average EMS delay alongside hourly preemption trigger rate trends.
* **Executive Insights:** Highlights peak preemption trigger dips (e.g., 08:00 and 18:00 commute rush), targeting capital expenditure toward high-friction corridors like INT-1003 and INT-1005.

![Signal Analytics](Signal%20Analytics.png)

---
*Developed by Shreyas Padmashali for the TCS iON AI Hackathon.*

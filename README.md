# LifeLane Governance Hub - TCS iON AI Hackathon 🚦

**Author:** Shreyas Padmashali | Aspiring Data Analyst

**Project Type:** UI/UX Architecture, Root Cause Analysis, and Dashboard Prototyping

## 📌 Project Overview
This repository contains the data architecture, visual strategy, and business logic for the **LifeLane Governance Hub**, a project designed for the TCS iON AI Hackathon. 

The core objective was to design a data-driven solution for urban traffic congestion, specifically addressing the critical disconnect between city traffic control and emergency medical services (EMS). 

📄 **[View the complete Root Cause Analysis and Build Plan (PDF)](TCSiON_Hackathon_Task.pdf)**

## 🔍 The Problem & Root Cause
**The Problem:** Critical patients and accident victims deteriorate because their ambulances get trapped in fixed-timer signal queues. Traffic signals follow pre-set timing cycles that do not automatically adjust for approaching emergencies.

**The Root Cause (5 Whys Analysis):** Traffic signal systems are governed, specified, and evaluated separately from emergency medical services. There is no integrated data infrastructure, shared priority protocol, or accountable owner making time-critical medical response a core design requirement of traffic signal control.

## 🛠️ The Solution: LifeLane Governance Hub
A web-based governance and analytics tool that unifies emergency trip logs, signal performance data, and delay hotspots into a single shared workspace for EMS and traffic departments. 

### Core Features & Dashboard Architecture

#### 1. Dashboard Overview & Accountability Tracker
Assigns intersection ownership (e.g., State Highways vs. City Traffic Dept) to drive actionable resolutions for outdated controllers. Tracks average signal delay against active emergency corridors.
![Dashboard Overview](Dashboard%20Overview.png)

#### 2. Incident Timeline
Links live emergency trips to specific signal states (Green, Yellow, Red) and tracks cumulative lost time per intersection.
![Incident Timeline](Incident%20Timeline.png)

#### 3. Predictive Forecaster
Generates delay heatmaps across the metro grid based on 30-day EMS coordination data, allowing officials to proactively identify high-risk intersections during peak hours.
![Predictive Forecaster](Predictive%20Forecaster.png)

#### 4. Priority Simulator
Models the impact of "Mild priority" vs. "Full preemption" rules, allowing administrators to recompute historical intersection delays and test new protocols before physical implementation.
![Priority Simulator](Priority%20Simulator.png)

#### 5. Signal Analytics
Provides a breakdown of average EMS delays by specific intersections and tracks preemption trigger rates, isolating exact coordination gaps.
![Signal Analytics](Signal%20Analytics.png)

---
*Note: The final web deployment of this prototype was restricted due to a hackathon submission portal error. This repository serves as the official documentation of the data logic, root cause analysis, and UI/UX dashboards engineered during the event.*

# Paragon Geeks — Repair Intake Intelligence System

Rule-Based Classification & Decision System for Standardizing Repair Intake Workflows

---

## Business Problem

Repair intake processes are often inconsistent, relying heavily on technician judgment and unstructured customer descriptions.

This creates:
- Variability in repair classification and prioritization  
- Inconsistent time estimates  
- Limited structured data for downstream analytics  
- Inefficient routing of complex or multi-issue repairs  

A standardized, explainable intake system is required to improve consistency, scalability, and data quality.

---

## Solution

Designed and implemented a rule-based intake intelligence system that converts unstructured customer issue descriptions into structured, decision-ready outputs.

---

## Business Impact Snapshot

- Standardized repair intake by converting unstructured customer descriptions into structured operational outputs  
- Reduced subjectivity in technician triage through rule-based classification and scoring  
- Enabled consistent repair routing, prioritization, and time estimation  
- Implemented multi-issue detection (primary + secondary repair flags)  
- Designed confidence scoring framework for transparent, explainable decisions  
- Simulated real-world intake workflow for repeatable and scalable process execution  

---

Built using real-world repair workflows from **Paragon Geeks**, this system models how technicians evaluate devices at intake and converts that process into a structured, scalable decision framework.

---

## 📑 Table of Contents

- [Executive Overview](#executive-overview)
- [System Architecture](#system-architecture)
- [Business Context](#business-context)
- [Core Decision Framework](#core-decision-framework)
- [Repair Categories Modeled](#repair-categories-modeled)
- [Operational Execution Simulation](#operational-execution-simulation)
- [Confidence & Escalation Modeling](#confidence--escalation-modeling)
- [Why This Matters](#why-this-matters)
- [Operational Impact & Deployment Potential](#operational-impact--deployment-potential)
- [Technical Skills Demonstrated](#technical-skills-demonstrated)
- [How to Run](#how-to-run)

---

## Executive Overview

This project implements a rule-based operational intake system designed to standardize repair triage in a real-world electronics repair environment.

The system converts unstructured customer issue descriptions into structured, explainable outputs that support:

- Repair routing  
- Priority assignment  
- Escalation logic  
- Time estimation  
- Downstream analytics  

Structured outputs include:

- Primary repair category  
- Priority level  
- Estimated service time  
- Secondary issue flags  
- Confidence score  

The system uses a transparent, rule-based scoring framework to produce explainable outputs aligned with real-world technician decision-making.

---

## System Architecture

![Intake Decision Engine Architecture](ai_intake_system_architecture.png)

*Layered decision pipeline from customer issue → structured operational output.*

### Decision Layers

- Device type classification (phone / tablet / console / computer)  
- Weighted issue scoring engine  
- Primary category determination  
- Secondary issue detection (multi-label)  
- Escalation & priority logic  
- Confidence scoring framework  
- Time estimation mapping  

### Design Principles

- Deterministic and explainable outputs  
- Full decision traceability  
- Operational consistency  
- Extensible architecture (ML-ready)  
- Business-rule alignment  

---

## Business Context

Designed using real-world repair intake patterns from a production electronics repair environment.

The system goes beyond basic keyword matching by implementing:

- Weighted category scoring  
- Multi-issue detection  
- Priority escalation logic  
- Secondary repair flagging  
- Confidence scoring  
- Device-specific overrides  

This replicates how experienced technicians perform intake triage in practice.

---

## Core Decision Framework

The system processes input through a structured pipeline:

1. Customer Issue Description  
2. Device Type Classification  
3. Weighted Keyword Scoring Engine  
4. Primary Category Determination  
5. Secondary Issue Detection  
6. Priority & Escalation Logic  
7. Confidence Scoring  
8. Structured Operational Output  

This ensures outputs are:

- Consistent  
- Explainable  
- Operationally usable  

---

## Repair Categories Modeled

- Screen Repair  
- Battery Replacement  
- Charging Port Repair  
- Water Damage Treatment  
- Camera Repair  
- Software / Data Issue  
- Board-Level / No Power  
- Console / HDMI Repair  
- Diagnostic / General Check  

---

## Operational Execution Simulation

### Auto Demo Mode (Batch Testing)

Runs prebuilt scenarios to validate system behavior.

![Demo Output](demo%20output.png)

Outputs include:
- Category predictions  
- Confidence scores  
- Priority levels  
- Time estimates  
- Category distribution summary  

---

### Live Interactive Triage Mode

Allows real-time user input:

![Interactive Mode](ai_intake_execution_preview_.png)

Example output:

- Category: Screen Repair  
- Confidence: 0.95  
- Priority: High  
- Estimated Time: 45–60 minutes  
- Secondary Flags: Charging Port Repair  

---

## Confidence & Escalation Modeling

The system incorporates operational logic:

- Priority escalation for high-risk issues (water damage, no power)  
- Secondary issue detection for multi-repair scenarios  
- Confidence scoring based on keyword match strength  
- Time estimation mapping aligned with real repair workflows  

All outputs remain deterministic and auditable.

---

## Why This Matters

- Converts inconsistent intake into structured operational data  
- Enables downstream analytics and performance tracking  
- Supports scalable process standardization  
- Provides a foundation for future machine learning integration  

---

## Operational Impact & Deployment Potential

This system demonstrates how intake can be standardized into a structured process:

- Reduces technician subjectivity  
- Improves intake consistency  
- Flags high-risk repairs early  
- Enables structured data collection  

### Potential Extensions

- Web-based intake interface (Streamlit / Flask)  
- POS / CRM integration  
- Repair analytics dashboards  
- Historical intake tracking for ML training  

---

## Technical Skills Demonstrated

- Rule-based classification systems (Python)  
- Weighted scoring algorithms  
- Multi-label issue detection  
- Escalation & priority logic  
- Confidence scoring frameworks  
- Structured output design  
- Domain-specific feature engineering  
- CLI workflow simulation  

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/paragon-repair-intelligence-system.git
cd paragon-repair-intelligence-system
```
2. Open the notebook using Jupyter Notebook or VS Code
3. Run all cells.

4. Execute:

   ```
   run_demo_cases()
   run_interactive_mode()
   ```

Interactive mode allows custom device triage testing.
---



















# PARAGON GEEKS — Operational AI Intake Decision System  
Hybrid Explainable AI Framework for Repair Operations

## Table of Contents

- [Executive Overview](#executive-overview)
- [System Architecture & Design Principles](#system-architecture--design-principles)
- [Business Context](#business-context)
- [Operational Execution Simulation](#operational-execution-simulation)
- [Core Decision Categories](#core-decision-categories)
- [Confidence & Escalation Modeling](#confidence--escalation-modeling)
- [Operational Impact & Deployment Potential](#operational-impact--deployment-potential)
- [Business Intelligence & Academic Alignment](#business-intelligence--academic-alignment)
- [Technical Skills Demonstrated](#technical-skills-demonstrated)
- [How to Run](#how-to-run)


## Executive Overview

This project models a structured, explainable AI decision system designed to standardize intake triage within a real-world electronics repair business environment (Paragon Geeks).

Rather than relying on black-box machine learning alone, the system implements a transparent, weighted rule-based classification architecture that mirrors how experienced technicians evaluate devices at intake.

The framework transforms unstructured customer issue descriptions into structured, auditable operational outputs — including repair category, priority level, estimated repair duration, and secondary risk flags.

This project demonstrates applied AI systems design grounded in Management Information Systems, business analytics, and operational process engineering principles.

---
## System Architecture & Design Principles

The AI Intake Engine is built on modular decision layers:

- Weighted keyword classification scoring
- Multi-label issue detection
- Escalation hierarchy logic
- Confidence modeling framework
- Device-type override rules
- Secondary repair risk flagging
- Structured time-estimation mapping

Design Priorities:

- Deterministic & explainable outputs
- Auditability of decision paths
- Operational consistency
- Extensibility for ML enhancement
- Business-rule traceability

This architecture reflects enterprise-ready decision automation systems where explainability and governance are critical.

## Business Context

Designed around real intake patterns from an electronics repair environment.

Instead of generic keyword matching, this system implements:

- Weighted category scoring
- Multi-issue detection
- Escalated priority logic
- Secondary repair flagging
- Confidence scoring model
- Device-type overrides (e.g., console HDMI logic)

This mirrors how experienced technicians triage devices in real life.

---

## System Architecture

Core Components:

- `route_issue()` → Weighted classification engine
- Keyword dictionaries by repair category
- Secondary issue detection logic
- Confidence scoring framework
- Priority escalation rules
- Estimated repair time mapping
- Interactive live triage mode

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

Below is an example of the AI Repair Assistant executing structured triage logic in demo mode.

![AI Repair Assistant Demo](demo%20output.png)

This output demonstrates:

- Weighted issue classification
- Confidence scoring
- Priority escalation logic
- Secondary issue detection
- Estimated repair time mapping
- Structured operational formatting

## Example Output

**Input:**

Device: iPhone 16 Pro Max  
Issue: screen cracked and battery drains fast  

---

**Output:**

Category: Screen Repair  
Priority: High  
Secondary Flags: Battery Replacement  
Estimated Time: 45–60 minutes  
Confidence: 0.95  

---

## Why This Project Matters

This system mirrors real-world electronics repair triage operations.

It demonstrates:

- Rule-based AI classification design  
- Domain-specific keyword engineering  
- Multi-issue detection logic  
- Operational priority escalation  
- Confidence scoring systems  
- Practical business automation modeling  

Rather than relying on machine learning alone, this project shows how structured decision systems can be built using clear, auditable logic — a critical capability in business environments where explainability matters.

---

## Future Expansion Potential

This engine can be extended into:

- Web-based intake forms (Flask / Streamlit)
- CRM integration
- Repair ticket automation
- Analytics dashboards
- Machine learning enhancement layer
- Customer-facing triage tool

The architecture is intentionally modular for scalability.

---

## How to Run

1. Clone the repository:
   git clone https://github.com/KevinTurner11/paragon-geeks-ai-repair-assistant.git

2. Navigate into the project folder:
   cd paragon-geeks-ai-repair-assistant

3. Open the notebook using Jupyter Notebook or VS Code.

4. Run all cells.

5. Execute:
   run_demo_cases()
   run_interactive_mode()

Interactive mode allows custom device triage testing.
---

## Business Intelligence & Academic Alignment

This project aligns directly with competencies developed through:

- B.S. in Management Information Systems & Business Analytics
- M.S. in Data Analytics (AI & Machine Learning Focus)
- SAS Certifications in:
  - Statistical Analysis
  - Predictive Analytics
  - Enterprise Performance Management
  - Applied Data Analytics

Core competencies demonstrated:

- Decision system engineering
- Structured classification modeling
- Business process automation
- Operational workflow standardization
- Confidence scoring frameworks
- Explainable AI system design
- Domain-driven feature engineering

---

## Technical Skills Demonstrated

- Python rule-based classification systems
- Weighted scoring algorithms
- Multi-label issue detection
- Decision escalation logic
- Structured confidence modeling
- Operational decision automation
- Business logic modeling

---

## Author

Kevin Turner  
Management Information Systems & Data Analytics  
SAS Certified | Business Intelligence | AI-Focused Portfolio Development  



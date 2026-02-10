# PARAGON GEEKS — AI Repair Assistant
Hybrid Rule-Based Triage Engine  
Operational Decision Intelligence System

---

## Overview

This project simulates a real-world repair intake system for an electronics repair business.

The AI Repair Assistant applies structured rule-based logic to:

- Categorize incoming device issues
- Detect multi-symptom repair scenarios
- Estimate repair priority
- Predict repair time expectations
- Flag secondary repair risks
- Route unclear cases to diagnostic workflows

This system models operational decision automation in a small business environment.

---

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


## Demo Run Preview

![Demo Output](demo_screenshot.png)



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

## Author

Kevin Turner  
Management Information Systems & Data Analytics  
SAS Certified | Business Intelligence | AI-Focused Portfolio Development  



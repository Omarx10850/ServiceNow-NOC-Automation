# Governance, SLA Management & Process Automation
Date: March 11, 2026

Objective:

To transform the basic incident logging system into a professional, ITIL-aligned NOC management platform. The focus was on implementing accountability (SLAs), data integrity (UI Policies), and automated stakeholder communication.


Technical Implementations:
SLA Governance: Configured a custom 2-hour Resolution SLA for P1 Critical incidents. This includes specific "Start" conditions for backbone failures and "Pause" conditions for vendor-related dependencies (e.g., waiting on an ISP).

Data Quality Control: Developed UI Policies to enforce mandatory documentation. The system now prevents an incident from being "Resolved" unless a Resolution Code and Resolution Notes are provided, ensuring a high-quality knowledge base for root cause analysis.

Notification Engine: Built an automated Next Experience Notification system to alert the Network Support team immediately upon the creation of a Critical incident, reducing "Mean Time to Acknowledge" (MTTA).


Evidence of Implementation:
1. SLA Performance Tracking
This screenshot demonstrates the active 2-hour countdown timer linked to our P1 NOC simulation.

<img width="1607" height="272" alt="image" src="https://github.com/user-attachments/assets/2ccf04d9-1e3a-4a8e-a856-b6e8fdef3143" />

2. Mandatory Field Enforcement (Data Integrity)
This screenshot shows the UI Policy in action, blocking a "Resolve" attempt because the engineer failed to provide mandatory resolution details.

<img width="1633" height="735" alt="image" src="https://github.com/user-attachments/assets/37d47e25-8992-41ad-a61a-a0d1c266596c" />


### **Technical Artifacts**
* **Update Set:** `ServiceNow_NOC_Automation_Day2.xml` (Included in repository)

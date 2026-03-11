# ServiceNow NOC Automation Project

## Day 2: Governance, SLA Management & Process Automation
**Date:** March 11, 2026

### **Objective**
To transform the basic incident logging system into a professional, ITIL-aligned NOC management platform. The focus was on implementing accountability (SLAs), data integrity (UI Policies), and automated communication.

### **Technical Implementations**
* **SLA Governance:** Configured a custom **2-hour Resolution SLA** for P1 Critical incidents to track response times.
* **Data Quality Control:** Developed **UI Policies** to prevent incidents from being "Resolved" without a Resolution Code and Resolution Notes.
* **Notification Engine:** Built an automated alert system to notify the Network Support team immediately upon the creation of a Critical incident.### **Evidence of Implementation**
#### **1. SLA Performance Tracking**
This screenshot demonstrates the active 2-hour countdown timer linked to our P1 NOC simulation.

<img width="1607" height="272" alt="image" src="https://github.com/user-attachments/assets/2ccf04d9-1e3a-4a8e-a856-b6e8fdef3143" />

#### **2. Mandatory Field Enforcement**
This screenshot shows the UI Policy in action, blocking a "Resolve" attempt because the engineer failed to provide mandatory resolution details.

<img width="1633" height="735" alt="image" src="https://github.com/user-attachments/assets/37d47e25-8992-41ad-a61a-a0d1c266596c" />


### **Technical Artifacts**
* **Update Set:** `ServiceNow_NOC_Automation_Day2.xml` (Included in repository)

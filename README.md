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


Technical Artifacts:
Update Set: <?xml version="1.0" encoding="UTF-8"?><unload unload_date="2026-03-11 21:15:32">
<sys_remote_update_set action="INSERT_OR_UPDATE">
<application display_value="Global">global</application>
<application_name>Global</application_name>
<application_scope>global</application_scope>
<application_version/>
<collisions/>
<commit_date/>
<deleted/>
<description/>
<inserted/>
<name>ServiceNow_NOC_Automation_Day2</name>
<origin_sys_id/>
<parent display_value=""/>
<release_date/>
<remote_base_update_set display_value=""/>
<remote_parent_id/>
<remote_sys_id>345db329932332101e78f847dd03d605</remote_sys_id>
<state>loaded</state>
<summary/>
<sys_class_name>sys_remote_update_set</sys_class_name>
<sys_created_by>admin</sys_created_by>
<sys_created_on>2026-03-11 21:15:31</sys_created_on>
<sys_id>956873b993af72101e78f847dd03d6a2</sys_id>
<sys_mod_count>0</sys_mod_count>
<sys_updated_by>admin</sys_updated_by>
<sys_updated_on>2026-03-11 21:15:31</sys_updated_on>
<update_set display_value=""/>
<update_source display_value=""/>
<updated/>
</sys_remote_update_set>
</unload>

This file contains all business rules, SLA definitions, and notification logic created during this session.

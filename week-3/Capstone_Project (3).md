**Capstone Project: SOC Workflow Simulation**

**Scenario:**

A simulated attack scenario was created where multiple failed login attempts were generated to mimic a brute-force attack.

**Detection:**

Using Kibana:

Event ID 4625 logs were identified

Multiple login failures detected

**Triage:**

Timestamp Event Observation

02-04-2026

02:30pm 4625 Repeated failed login

**Analysis:**

The repeated login failures within a short duration indicate a possible brute-force attack attempt.

**Response**

Logs were analyzed for suspicious activity

Threat intelligence check performed

System monitored for further anomalies

**Escalation**

The incident was considered suspicious and would be escalated to Tier 2 for further investigation in a real SOC environment.

**Report**

The simulated attack demonstrated how repeated failed login attempts can indicate a brute-force attack. Detection and analysis were performed using Kibana, and appropriate monitoring actions were taken.

**Conclusion:**

potential brute-force attack was detected through multiple failed login attempts. The activity was analyzed and monitored. No immediate critical impact was observed
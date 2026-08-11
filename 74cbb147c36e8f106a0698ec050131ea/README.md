# 🤖 Autonomous AI Incident Triage Engine (ServiceNow)

An end-to-end automated incident classification and escalation workflow built inside ServiceNow using custom Scoped Application architecture, server-side JavaScript, and Flow Designer.

---

## 📌 Features & Architecture

1. **Custom Scoped Application (`Autonomous AI Incident Triage`):** Isolated application scope ensuring modularity and clean deployment.
2. **Async Server-Side Business Rule (`Execute Autonomous AI Triage`):** Triggers asynchronously upon incident creation to handle background processing without form-latency for users.
3. **Script Include (`AITriageEngine`):** Encapsulates core triage logic to parse incoming symptoms, assign proper priority metadata, and generate automated resolution plans.
4. **Source Control Integration:** Direct bi-directional synchronization with GitHub via ServiceNow Studio.

---

## 🛠️ Tech Stack & Skills
* **Platform:** ServiceNow (Washington DC / Xanadu)
* **Backend:** JavaScript (GlideRecord, Script Includes, Async Business Rules)
* **Automation:** Flow Designer / Workflow Studio
* **Version Control:** Git & GitHub via ServiceNow Studio Integration

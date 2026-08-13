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
  <img width="1824" height="854" alt="Screenshot 2026-08-13 165101" src="https://github.com/user-attachments/assets/03ea350a-b5b4-41ca-bf73-083ca83399bd" />
<img width="879" height="665" alt="Screenshot 2026-08-13 165311" src="https://github.com/user-attachments/assets/e68a4ca1-3619-4c4d-ac16-3f67f3f3cb96" />

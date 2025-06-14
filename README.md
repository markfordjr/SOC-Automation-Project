# SOC Automation Project

**🔐 Integrated SOAR with Wazuh + TheHive + Shuffle (SOAR automation)**
**Author:** Mark Ford Jr.

---

## 🚀 Overview

This project demonstrates how to build a fully automated Security Orchestration, Automation, and Response (SOAR) environment from scratch.
It integrates **Wazuh** for agent-based monitoring, **TheHive** for case management, and **Shuffle** for workflow automation.

**Key Highlights:**

* Centralized alerting with Wazuh
* Automated case creation and tracking via TheHive
* Playbooks and incident response flows using Shuffle
* Containerized deployment with **Docker Compose**

---

## 📋 Features

* **Agent-based alert detection**
* **Automated enrichment** and alert triage
* **Incident response workflows** with orchestration
* **Scalable** containerized architecture
* **Customizable playbooks** to suit specific needs

---

## ⚙️ Architecture Diagram

*Include your **Formatted‑SOC‑Automation‑Project‑Diagram.png*** here\*.

---

## 🛠️ Getting Started

### Prerequisites

* Docker & Docker Compose (v2+)
* Access to SH-Tools repository containing scripts/images (if private)

### Quick Setup

```bash
git clone https://github.com/markfordjr/SOC-Automation-Project.git
cd SOC-Automation-Project
docker-compose up -d
```

### Initialization

1. Configure Wazuh agents using `Wazuh-Install-Instructions/`
2. Configure TheHive as per `TheHive-Install-Instructions/`
3. Start Shuffle workflows to connect alert → case creation steps

---

## 🧪 Testing & Validation

* Generate test alerts (e.g., malware activity, syslog entries)
* Verify Wazuh detection and forwarding to Shuffle
* Confirm that TheHive tickets are automatically opened and populated
* Review Shuffle logs for successful playbook execution

---

## 🧩 Project Structure

```
SOC-Automation-Project/
├── docker-compose.yml         # Orchestrates all containers
├── Wazuh-Install-Instructions/
├── TheHive-Install-Instructions/
├── mac-M1-M2-M3-Instructions/ # Apple silicon specific notes
├── Formatted‑SOC‑Automation‑Project‑Diagram.png
└── README.md                  # This high-level overview
```

---

## 🔭 Future Enhancements

* Extend playbooks — add data enrichment, notification & auto-remediation
* Implement dynamic rule tuning with SIEM feedback loops
* Integrate external threat intel feeds
* Add automated reporting and dashboards

---

## 📚 Resources

* Wazuh: [official documentation](https://documentation.wazuh.com/)
* TheHive: [official documentation](https://thehive-project.org/)
* Shuffle: [GitHub repo for workflows](https://github.com/frikky/shuffle)

---

## 📞 Contact

**Mark Ford Jr.**
Email: *[you@example.com](mailto:you@example.com)*
GitHub: [markfordjr](https://github.com/markfordjr)

---

## 📝 License

This project is available under the [MIT License](LICENSE).

---

### ✅ Why This Works

* **Clear objective** and scope
* **User-friendly setup** steps
* **Professional structure** that aligns with recruiter expectations
* **Scalability & future roadmap** indicate serious thinking and vision

---

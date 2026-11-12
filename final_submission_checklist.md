# EdVyro Cybersecurity Internship: Final Submission Checklist

**Project:** Local Reconnaissance and Attack Surface Map  
**Target:** `127.0.0.1:3000`  
**Assessment Date:** 2026-11-12  

---

## Deliverables & Tasks Checklist

| Task / Phase | Requirement | Deliverable File | Status | Notes |
| :--- | :--- | :--- | :--- | :--- |
| **Phase 1** | Understand Assignment & RoE | Internal Checklist / Scope | [x] Completed | RoE, constraints, ethical boundaries verified |
| **Phase 2** | Host Environment Audit | System Inspection Log | [x] Completed | Win 11, Node v22.23.1, npm 10.9.8, Python 3.12 verified. Docker & Nmap not installed |
| **Phase 2** | Local Lab Preparation | Target Deployment (`127.0.0.1:3000`) | [x] Completed | Official OWASP Juice Shop v20.4.0 downloaded, extracted, strictly bound to `127.0.0.1:3000`, and active |
| **Phase 3** | Target Identification & Authorization | `authorization_statement.md` | [x] Drafted | Loopback target confirmed active (`127.0.0.1:3000`). Awaiting user authorization to initiate port enumeration |
| **Phase 4 (A)** | Target Reachability Verification | HTTP Check / `evidence/` | [x] Completed | Verified 127.0.0.1:3000 reachable; HTTP 200 OK |
| **Phase 4 (B)** | Port Enumeration | `command_log.txt` / Nmap logs | [x] Completed | Conservative TCP scan completed; ports 3000, 135, 445, 27017 mapped |
| **Phase 4 (C)** | Service Identification & Banners | `service_inventory.csv` | [x] Completed | OWASP Juice Shop v20.4.0 (Node.js/Express) fingerprinted |
| **Phase 4 (D)** | HTTP Header & Security Analysis | `attack_surface_report.md` | [x] Completed | Security headers audited: CSP missing, Wildcard CORS, Feature-Policy noted |
| **Phase 4 (E)** | Visible Input & Form Enumeration | Attack Surface Map | [x] Completed | Search, login, registration, feedback, photo upload inventoried |
| **Phase 5** | Attack Surface Inventory | `service_inventory.csv` | [x] Completed | 11-field CSV inventory created with evidence references |
| **Phase 6** | Risk Analysis & Recommendations | `risk_assessment.csv` | [x] Completed | 10 risk findings mapped with severity, impact, and mitigations |
| **Phase 7** | Attack Surface Architecture Diagram | `attack_surface_diagram.mmd` & `.png` | [ ] Pending | Mermaid diagram & rendered graphic |
| **Phase 8** | Documentation & Sanitized Logs | `README.md`, `command_log.txt` | [ ] Pending | Sanitized execution transcripts |
| **Phase 9** | Professional PDF Report | `attack_surface_report.pdf` | [ ] Pending | Formatted submission document |
| **Phase 10** | Quality Verification & Integrity | Sanity Check Across Artifacts | [ ] Pending | Ensure zero fabrication |
| **Phase 11** | GitHub Preparation & Proof Link | Repository Structure | [ ] Pending | Sanitized public submission ready |
| **Phase 12** | Final Completion Summary | Final Report & Metrics | [ ] Pending | Comprehensive closeout |

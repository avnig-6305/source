# CODTECH Task 4: Vulnerability Management Dashboard

## 👤 Intern Information
* **Name:** Avni Goyal
* **Intern ID:** CITS9080
* **Domain:** Cyber Security & Ethical Hacking / Python Development
* **Duration:** September 8, 2026 - October 8, 2026
* **Mentor:** CodTech IT Solutions Evaluation Team

---

## 📌 Project Overview
This project is a terminal-based **Vulnerability Management Dashboard** built using Python. It serves as a central data hub for security analysts to register, track, categorize, and prioritize security weaknesses across varying corporate network infrastructure assets. 

The application implements standard **Common Vulnerability Scoring System (CVSS)** evaluation brackets to automatically classify risks into strict structural tiers (Critical, High, Medium, Low) using structured grids.

---

## ⚙️ Features
* **Interactive Matrix Interface:** Integrates the third-party `tabulate` library to create a clean, easy-to-read command-line tabular overview.
* **Dynamic Record Intake:** Allows real-time administrative generation to add custom system vulnerabilities with designated threat weights.
* **Auto-Calibrated Severity:** Instantly maps CVSS scores to corresponding threat classification labels.
* **Aggregate Metric Tracking:** Displays persistent overhead indicators detailing Open, In-Progress, and Mitigated security data flags.

---

## 🛠️ Technology Stack
* **Language:** Python 3.x
* **External Library:** `tabulate` (for rendering data grid formatting structures)
* **Core Modules:** `sys`

---

## 🚀 How to Run the Project

1. **Install required layout libraries:**
   ```bash
   pip install tabulate
   ```

2. **Execute the dashboard module file:**
   ```bash
   python vulnerability_dashboard.py
   ```

3. **Console Management:**
   * Enter **`1`** to dynamically provision a new infrastructure bug entry into the database.
   * Enter **`2`** to force refresh terminal metrics data streams.
   * Enter **`3`** to close down administrative operations safely.


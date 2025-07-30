# 2022CYS B.Tech Dissertation - 22UCYS#10 ![](https://img.shields.io/badge/-Started-darkgreen)
![](https://img.shields.io/badge/Batch-22UCYS-green) ![](https://img.shields.io/badge/Domain-Security-blue) 
# 🎯 Deception Technology for APT Detection in Critical Infrastructure

> Final Year B.Tech Cyber Security Project – TIFAC-CORE in Cyber Security, 2025-2026  
> Group 10 | B.Tech CYS (2022–2026) | Subject Code: 20CYS495

## 🧠 Project Overview

Advanced Persistent Threats (APTs) pose significant risks to critical infrastructure by mimicking legitimate user behavior, bypassing traditional signature-based defenses. This project introduces a **deception-based security framework** to proactively detect, engage, and analyze APT tactics in real time.

## 👨‍💻 Team Members

| Name                | Roll No           |
|---------------------|-------------------|
| Chitla Vyshali      | CB.EN.U4CYS22017  |
| Dharshika S         | CB.EN.U4CYS22021  |
| Reddicherla Thanuj  | CB.EN.U4CYS22056  |
| Mothe Anurag Reddy  | CB.EN.U4CYS22069  |

**Guide**: Sreejith K  
**Domain**: Threat Intelligence & APT Research

---

## 🚨 Problem Statement

APT attackers infiltrate systems using stealthy techniques that closely resemble normal operations. Once inside, they move laterally, escalate privileges, and exfiltrate data over long periods—often undetected. Traditional detection systems generate too many low-confidence alerts, masking real threats.

This project bridges that gap using deception technology to deliver **high-fidelity, behavior-based alerts**, enabling faster, more accurate incident response.

---

## 🎯 Objectives

- Design and deploy a **realistic deception environment** (decoys, fake credentials, AD objects).
- Simulate **APT attacks** using Cobalt Strike, Empire, and Metasploit.
- Log and forward all activity to **Splunk SIEM**.
- Build **custom dashboards and alerts** for detection.
- Map findings to **MITRE ATT&CK** framework.
- Measure **detection effectiveness** and **attacker dwell time**.

---

## 🧪 Tools & Technologies

### 🛠 Tools
- **Deception Platforms**: Custom honeypots, Honeytokens
- **Red Teaming**: Cobalt Strike, Empire, Metasploit
- **SIEM**: Splunk Enterprise + Universal Forwarder
- **Virtualization**: VMware / Hyper-V
- **Directory Services**: Active Directory (Windows)

### ⚙️ Methodologies
- **Deception-First Design**
- **Adversary Emulation**
- **SIEM-Centric Tagging & Logging**
- **MITRE ATT&CK Mapping**
- **Alert Engineering**
- **Metrics-Driven Optimization**

### 💻 OS & Software
- Windows (for AD, decoy endpoints)
- Linux (for attack simulation & logging)

---

## 📈 Key Metrics

- **Time to Detect**
- **Decoy Trigger Rate**
- **Attacker Dwell Time**
- **True vs. False Positive Ratio**
- **MITRE ATT&CK Coverage**

---

## 📅 Timeline

| Phase                        | Duration        | Deliverables |
|-----------------------------|-----------------|--------------|
| 🔧 Core Setup               | July – Aug 2025 | Infra + Tools ready |
| 🕵️ Deception Integration    | Sept – Oct 2025 | First Demo, SIEM logs |
| 🎯 Simulation & Dashboards  | Nov – Dec 2025  | Splunk visuals + ATT&CK mapping |
| ✅ Finalization & Delivery  | Jan – Feb 2026  | Report, Metrics, Presentation |

---

## ❗ Challenges & Mitigations

| Challenge                     | Mitigation Strategy                                   |
|------------------------------|--------------------------------------------------------|
| Decoy Detection              | Mirror naming, inject realistic user activity          |
| False Positives              | Baseline traffic, whitelist known scanners             |
| SIEM Log Latency             | Buffered forwarders, tag prioritization                |
| SIEM Overload                | Use summary indexes, filter low-value logs             |
| Evasion of Honeytokens       | Rotate credentials, randomize decoy identities         |
| ATT&CK Technique Drift       | Automate tagging, review quarterly                     |

---

## 📌 Research Questions

- How effective are decoys in engaging real-world APT tools?
- Which TTPs are commonly triggered during simulation?
- How fast and reliable is log ingestion?
- Are dashboards accurately detecting attacker behavior?
- What MITRE ATT&CK coverage do our alerts provide?

---




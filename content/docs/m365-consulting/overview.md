---
title: "Cheatsheet Overview"
description: "Table of contents"
weight: 2
draft: false
tags:
- "M365"
- "Consulting"
---

**1. M365 Core Services & Architecture**
* **1.1. Exchange Online:** Mail flow troubleshooting, shared mailboxes, hybrid concepts.
* **1.2. SharePoint Online & OneDrive:** External sharing configurations, site architecture, sync client troubleshooting.
* **1.3. Microsoft Teams:** Meeting policies, app governance, and standardizing team creation.
* **1.4. Service-Wide:** Troubleshooting issues and data consistency across the ecosystem.

**2. Identity & Access (Entra ID)**
* **2.1. Identity Lifecycle:** Understanding the flow from HR systems to Active Directory to Entra ID (JML - Joiners, Movers, Leavers).
* **2.2. Conditional Access (CA):** Best practices for CA policies, troubleshooting sign-in logs, and managing exclusions securely.
* **2.3. Authentication:** MFA enforcement, Self-Service Password Reset (SSPR), and modern authentication protocols.

**3. Governance & Compliance (Purview)**
* **3.1. Data Loss Prevention (DLP):** Triage workflows for DLP alerts and understanding policy scoping.
* **3.2. Information Protection:** Sensitivity labels (content vs. container level) and practical deployment.
* **3.3. Data Lifecycle:** Retention policies vs. retention labels, and eDiscovery basics.

**4. Security (Defender)**
* **4.1. Defender for Office 365:** Managing "Safe Links" and "Safe Attachments" policies, and investigating phishing/spoofing alerts.
* **4.2. Defender for Endpoint (MDE):** Device onboarding basics, EDR (Endpoint Detection and Response) sensor health, and interpreting vulnerability management scores.
* **4.3. Defender for Cloud Apps (CASB):** Identifying "Shadow IT" through discovery logs and implementing session controls for unmanaged devices.
* **4.4. Defender for Identity & XDR:** Understanding how signals are correlated across the portal and using Automated Investigation and Response (AIR) to remediate threats.

**5. Other Key Services**
* **5.1. Microsoft Intune (Endpoint Management):** Configuration vs. compliance policies, device enrollment (Autopilot), and mobile application management (MAM).
* **5.2. Microsoft Copilot:** Basic data readiness concepts (oversharing risks in SharePoint) and licensing constraints.
* **5.3. Power Platform:** Core governance, environment strategies, and Power Platform DLP policies.
* **5.4. Microsoft Fabric:** OneLake architecture, capacity management, and security integration.

**6. Incident Lifecycle & Decision Logic**
* **6.1. ITIL Fundamentals:** The very basics on the ITIL Framework.
* **6.2. Issue Ownership:** Establishing a triage workflow for complex blockers before considering escalation.
* **6.3. The Escalation Framework:** Creating a standardized template for genuine decision points (Context -> Business Impact -> Recommended Options).
* **6.4. Managing Ambiguity:** How to operate when documentation is missing or incomplete.

**7. Consulting & Stakeholder Management**
* **7.1. The "Consultant Muscle":** Frameworks for reviewing solution requests against an *existing* strategy.
* **7.2. Constructive Pushback:** How to confidently say "no" to non-standard approaches while providing technical reasoning and a compliant alternative.
* **7.3. Advising:** Translating complex M365 guardrails into practical "how to do it properly" steps for delivery teams.
* **7.4. RAID/RAAIDD Logs:** Leveraging logs as a technical shield to document risks, decisions, and dependencies for accountability and clear architectural handovers.

# Enterprise Security Awareness Campaign Plan (Week 4)
**YuvaIntern Cyber Security Analyst Internship Program**

* **Author / Analyst:** Parameshwaran
* **Role:** Cyber Security Analyst
* **Track:** Cyber Security Analyst – Internship Week 4
* **Target Organization:** Apex Global Technologies (Hypothetical Enterprise Profile)
* **Scope:** 12-Week Security Awareness Campaign, Human Risk Management, Behavioral Change, & Metrics Framework
* **Framework Alignment:** NIST SP 800-50, NIST SP 800-53 Rev. 5 (AT Controls), CISA "Secure Our World" Campaign, SANS Security Awareness Maturity Model
* **Classification:** Ethical & Defensive Cybersecurity Research (Hypothetical Case Study)
* **Date:** August 2026

---

## 1. Executive Summary

While technical security controls (firewalls, EDR, SIEM) provide critical defense-in-depth, the human element remains a primary attack vector for modern cyber adversaries. Industry research indicates that over **80% of enterprise security breaches involve human interaction**, including phishing lures, stolen credentials, social engineering, and accidental data exposure.

This document presents a comprehensive **12-Week Security Awareness Campaign Plan** for a hypothetical multinational enterprise, **Apex Global Technologies**. Designed to transition the organization from compliance-driven training to a resilient cybersecurity culture, the campaign aligns with the **NIST SP 800-50** framework, **NIST SP 800-53 Rev. 5 (AT-1 through AT-4)**, **CISA's "Secure Our World" Campaign Pillars**, and the **SANS Security Awareness Maturity Model**.

The plan delivers structured learning modules, multi-channel communication strategies, creative gamification activities, an interactive 12-week execution schedule, and quantitative Key Performance Indicators (KPIs) to measure behavioral change and risk reduction.

---

## 2. Hypothetical Organization Profile

### 2.1 Organization Overview
**Apex Global Technologies** is a multinational technology enterprise delivering cloud analytics, software development, and enterprise SaaS solutions.
* **Workforce Size:** Approximately 1,200 employees operating across corporate headquarters, regional offices, and remote/hybrid work environments.
* **Workforce Segmentation:** Executive Leadership, Software Developers/Engineers, Finance/HR Personnel, Sales/Marketing Staff, and General Administrative Workforce.
* **Infrastructure:** Hybrid enterprise cloud (AWS, Azure, Microsoft 365) with remote workforce endpoint access.

### 2.2 Current Security Awareness Baseline
Prior awareness efforts relied exclusively on an annual 30-minute slide deck compliance presentation during onboarding. Consequently, employee phishing click-through rates averaged **18%**, credential hygiene was unmonitored, and incident reporting delays averaged over 4 hours.

---

## 3. Campaign Objectives

The campaign targets five strategic behavioral objectives:

```
+------------------------------------------------------------------------------------+
|                             CAMPAIGN STRATEGIC OBJECTIVES                          |
+------------------------------------------------------------------------------------+
| 1. Reduce Phishing Susceptibility: Lower click-through rate from 18% to < 5%.       |
| 2. Accelerate Threat Reporting: Increase 1-click phishing button usage by 150%.    |
| 3. Eliminate Credential Risks: Achieve 100% adoption of FIDO2 MFA & Password Mgrs. |
| 4. Enhance Data Protection: Eliminate accidental PII/PHI public cloud exposure.    |
| 5. Foster Security Culture: Elevate SANS Awareness Maturity from Level 2 to Level 4.|
+------------------------------------------------------------------------------------+
```

---

## 4. Target Audience and Employee Groups

To maximize engagement, communications and training modules are segmented by employee risk profile:

| Audience Segment | Risk Profile & Characteristics | Primary Threat Exposure | Tailored Focus & Channel |
| :--- | :--- | :--- | :--- |
| **Executive Leadership** | High-value targets with broad system access and approval authority. | Whaling, executive impersonation, wire fraud. | 15-Minute executive briefings, 1-on-1 coaching, concierge support. |
| **Finance & HR Personnel** | Handle sensitive financial transactions, employee PII, and bank accounts. | Business Email Compromise (BEC), spear-phishing, invoice fraud. | Specialized BEC workshops, smishing/vishing role-playing drills. |
| **Software Developers / IT** | Access to source code, cloud infrastructure, and CI/CD pipelines. | Secret leakage, supply-chain attacks, GitHub repo exposure. | Secure coding modules, secret scanning drills, Slack/Teams tech posts. |
| **Sales & Remote Staff** | High volume of external communications; mobile/home Wi-Fi networks. | Malicious email attachments, untrusted Wi-Fi, lost devices. | Mobile-friendly micro-videos, home network guides, digital posters. |
| **General Workforce** | Standard corporate workstation and application access. | Generic phishing, weak passwords, accidental data loss. | Gamified quizzes, intranet banners, monthly newsletter digests. |

---

## 5. Cybersecurity Awareness Risk Assessment

A human risk assessment identified four high-risk behavioral areas across the organization:

| Human Risk Area | Root Cause & Current Deficiency | Inherent Risk Rating | Target Behavioral Change |
| :--- | :--- | :--- | :--- |
| **Credential Reuse & Weak Passwords** | Employees use simple, memorized passwords across corporate and personal accounts. | **CRITICAL** | Transition to 15-character passphrases and enterprise password managers. |
| **Phishing & AiTM Link Susceptibility** | Difficulty distinguishing Adversary-in-the-Middle (AiTM) links and urgent BEC emails. | **CRITICAL** | Verification of sender domain, scrutiny of sense-of-urgency, and reporting. |
| **Delayed Incident Reporting** | Fear of reprimand or confusion regarding the proper reporting process. | **HIGH** | "No-blame" security culture supported by a 1-click Outlook reporting button. |
| **Unsecured Remote Environments** | Working over unencrypted public Wi-Fi without VPN; unlocked screens in public places. | **HIGH** | Mandatory auto-lock screens (Win+L) and VPN auto-connect enforcement. |

---

## 6. Key Awareness Topics

The campaign centers on eight core awareness topic modules aligned with **CISA "Secure Our World"** pillars and **NIST SP 800-50**:

```
+------------------------------------------------------------------------------------+
|                             8 CORE AWARENESS TOPIC MODULES                         |
+------------------------------------------------------------------------------------+
| 1. Password Security & Password Managers  | 5. Data Protection & Privacy (PII/PHI) |
| 2. Phishing & Social Engineering          | 6. Device, Endpoint & Remote Work      |
| 3. Safe Email & Web Browsing Hygiene      | 7. Incident Reporting & SOC Escalation |
| 4. Malware & Ransomware Evasion           | 8. Physical Security & Clean Desk      |
+------------------------------------------------------------------------------------+
```

---

## 7. Password Security and MFA

### Core Guidance (CISA & NIST SP 800-63B):
* **Passphrases Over Passwords:** Educate employees to use long, memorable passphrases (e.g., `BlueSky!CoffeeMorning2026`) exceeding 15 characters rather than short, complex passwords that require frequent changes.
* **Enterprise Password Managers:** Encourage the adoption of enterprise-managed password vaults to generate and auto-fill unique passwords for every application.
* **Phishing-Resistant MFA (FIDO2):** Train employees on the importance of hardware-backed FIDO2 security keys and WebAuthn prompts, explaining why legacy SMS/push notifications are vulnerable to proxy interception.

---

## 8. Phishing and Social Engineering Awareness

### Core Guidance (CISA Phishing Framework):
* **Spotting Phishing Indicators:** Train staff to inspect email headers, verify domain authenticity, identify mismatched URLs, and question unexpected urgency or financial requests.
* **Spear-Phishing & Executive Impersonation:** Educate Finance and HR teams on out-of-band verification procedures (e.g., calling the CFO directly via official internal extension) prior to executing wire transfers or modifying payroll details.
* **Vishing & Smishing:** Address SMS-based pretexting and fraudulent voice calls claiming to be IT support requesting MFA push approvals.

---

## 9. Safe Email and Internet Usage

### Core Guidance:
* **Web Browsing Hygiene:** Warn against clicking sponsored ad links in search engines, downloading files from untrusted repositories, or bypassing browser SSL/TLS certificate warnings.
* **Safe Email Practices:** Emphasize verifying external recipient addresses before sending attachments containing sensitive company data.

---

## 10. Malware and Ransomware Awareness

### Core Guidance:
* **Ransomware Vector Recognition:** Teach staff how ransomware enters networks via weaponized Office macros, zip archives, drive-by downloads, and fake software update prompts.
* **Immediate Response Action:** Educate employees that if their screen displays a ransomware notice or rapid file renaming occurs, they must immediately disconnect from Wi-Fi/Ethernet and notify the SOC.

---

## 11. Data Protection and Privacy

### Core Guidance (NIST SP 800-53 PT/DS):
* **Data Classification Awareness:** Reinforce understanding of data labels (*Public, Internal, Confidential, Restricted*) and proper handling rules.
* **Preventing Accidental Leakage:** Prohibit uploading corporate source code or customer data into unapproved public AI tools (e.g., public ChatGPT) or personal cloud storage accounts.

---

## 12. Device, Endpoint and Remote-Work Security

### Core Guidance:
* **Remote Work Security:** Mandate automatic VPN connection when accessing corporate resources from public Wi-Fi networks (airports, coffee shops).
* **Screen Lock Habit (Win + L):** Instill the automatic habit of locking computer screens whenever stepping away, even in home or private office environments.
* **Prompt Software Updates:** Reinforce the CISA "Secure Our World" message to apply operating system and application security updates promptly.

---

## 13. Incident Reporting and Response Awareness

### Core Guidance:
* **1-Click Phishing Reporting:** Promote the use of the 1-click "Report Phishing" button integrated directly into Microsoft Outlook and webmail clients.
* **"No-Blame" Security Culture:** Reassure employees that accidentally clicking a link will not lead to disciplinary action if reported immediately, reinforcing that rapid reporting mitigates organizational damage.

---

## 14. Physical Security and Clean Desk Practices

### Core Guidance:
* **Clean Desk Policy:** Mandate clearing physical documents containing sensitive data, whiteboards, and sticky notes containing passwords at the end of each workday.
* **Tailgating Prevention:** Train employees to require all individuals entering secure facilities to swipe their own physical access badges, preventing unauthorized visitors from following behind.

---

## 15. Security Awareness Communication Strategy

The campaign utilizes a **Multi-Touchpoint Communication Strategy** to ensure high visibility across diverse employee groups without inducing communication fatigue:

```
+------------------------------------------------------------------------------------+
|                         MULTI-TOUCHPOINT COMMUNICATION PIPELINE                    |
+------------------------------------------------------------------------------------+
| EXECUTIVE LEADERSHIP  -->  INTRANET & DIGITAL POSTERS  -->  SLACK / TEAMS ALERTS    |
| (Town Hall Launch)         (Weekly Banners & Guides)       (Bite-Sized Tips)       |
|                                                                    |               |
| MICRO-LEARNING PORTAL <--  SIMULATED DRILLS & DRILLS   <-----------+               |
| (2-Min Video Modules)      (Phishing Drills & Awards)                              |
+------------------------------------------------------------------------------------+
```

---

## 16. Campaign Channels and Communication Methods

| Channel | Format & Frequency | Target Audience | Primary Content Type |
| :--- | :--- | :--- | :--- |
| **Executive Town Hall** | Video Broadcast (Week 1 & 12) | All Workforce | Campaign kickoff message, culture awards, and CISO vision. |
| **Intranet & Digital Signage** | Banners & TV Slides (Weekly) | Onsite & Office Staff | Infographics, weekly security tips, CISA "Secure Our World" graphics. |
| **Slack / Microsoft Teams** | Bite-sized Posts (Bi-weekly) | Developers & Remote Staff| Short security alerts, interactive polls, quick passphrase challenges. |
| **Micro-Learning Portal** | 2-Minute Videos (Monthly) | All Workforce | Animated interactive scenarios with short 3-question knowledge checks. |
| **Targeted Workshops** | Live Interactive (Monthly) | Finance, HR, IT | Deep-dive BEC role-play, secret scanning, and clean desk sweeps. |

---

## 17. Creative Awareness Activities and Campaign Ideas

1. **"Passphrase Challenge" Contest:** Employees submit creative, secure 20+ character passphrases; winning entries earn company swag and recognition.
2. **"Spot the Phish" Live Tournament:** Gamified competition where teams analyze real-world sanitized phishing emails to identify subtle indicators.
3. **Cybersecurity Champions Network:** Select enthusiastic representatives from each department to act as local security liaisons and peer mentors.
4. **Annual Security Culture Awards:** Public recognition during Week 12 for departments with the highest reporting rates and zero simulated phishing clicks.

---

## 18. Training Content and Employee Engagement

Training content is built upon **Micro-Learning Principles** (short 2 to 3-minute modules) to fit into busy employee schedules:
* **Interactive Storytelling:** Use real-world sanitized threat scenarios rather than dry policy text.
* **Immediate Feedback Loop:** When an employee reports a simulated phishing email, an automated pop-up immediately thanks them and confirms their positive behavior.
* **Point-of-Failure Micro-Training:** If an employee clicks a simulated phishing link, they are automatically directed to a 60-second friendly, non-punitive training page explaining the specific indicator missed.

---

## 19. Campaign Schedule and 12-Week Calendar

The 12-week campaign follows a structured sequence:

| Week | Focus Module | Primary Activity & Deliverable | Target Success KPI |
| :--- | :--- | :--- | :--- |
| **Week 1** | Campaign Launch & Basics | Executive Kickoff Video & Intranet Launch | 95%+ Video view completion rate |
| **Week 2** | Password Security & Passphrases| Passphrase Challenge & Password Manager Clinic| 40% Increase in Enterprise Password Manager adoption |
| **Week 3** | MFA & FIDO2 Security | FIDO2 Hardware Token Enrollment Drive | 100% Enrollment in FIDO2 hardware MFA |
| **Week 4** | Phishing Recognition | Baseline Simulated Phishing Campaign | Click Rate < 5%; Reporting Rate > 70% |
| **Week 5** | Social Engineering & BEC | Finance/HR BEC Role-Play Workshop | 100% Attendance for Finance & HR teams |
| **Week 6** | Safe Web & Email Hygiene | Interactive Web Safety Quiz & Infographic | Quiz completion rate > 85% |
| **Week 7** | Ransomware Evasion | Developer/IT Secure Coding & Macro Briefing | Zero unapproved software installations |
| **Week 8** | Data Protection & Privacy | Interactive Data Classification Game | 100% E-learning module completion |
| **Week 9** | Device & Remote Safety | Remote Work Health-Check & VPN Audit | 100% Endpoint encryption compliance |
| **Week 10**| Incident Reporting Drive | 1-Click Phishing Report Button Drill | Report button usage increase by 150% |
| **Week 11**| Physical Security & Clean Desk | Physical Floor Sweep & Badging Audit | Zero exposed credentials / unlocked screens |
| **Week 12**| Review & Culture Awards | Executive All-Hands & Champion Ceremony | SANS Maturity Score transition to Level 4 |

---

## 20. Measurement, KPIs and Effectiveness Evaluation

Program effectiveness is measured across quantitative behavioral metrics aligned with **NIST SP 800-50**:

| Metric Domain | Key Performance Indicator (KPI) | Baseline | Target Goal | Measurement Frequency |
| :--- | :--- | :--- | :--- | :--- |
| **Phishing Susceptibility** | Simulated Phishing Click-Through Rate | 18% | **< 5%** | Monthly Simulations |
| **Threat Reporting** | Phishing Report Button Utilization Rate | 25% | **> 75%** | Continuous Real-Time |
| **Reporting Speed** | Average Time to First Phishing Report | 4 Hours | **< 15 Minutes** | Monthly Simulations |
| **Identity Hygiene** | Enterprise Password Manager Adoption | 35% | **> 90%** | Bi-Weekly Telemetry |
| **MFA Compliance** | FIDO2 Hardware MFA Enrollment | 60% | **100%** | Weekly Telemetry |
| **Training Completion** | Micro-Module Completion Rate | 50% | **> 95%** | Monthly Tracking |
| **Culture Maturity** | SANS Security Awareness Maturity Model | Level 2 | **Level 4** | Annual Assessment |

---

## 21. Roles and Responsibilities

| Role | Primary Campaign Responsibilities | Key Deliverables |
| :--- | :--- | :--- |
| **CISO / Executive Sponsor** | Strategic oversight, budget approval, Town Hall presentations. | Executive kickoff video; board updates. |
| **Security Awareness Lead** | Overall campaign design, content creation, schedule management. | 12-Week content calendar; KPI reporting. |
| **SOC / Technical Team** | Simulated phishing campaign execution; report button integration. | Phishing simulation metrics; SIEM telemetry. |
| **Corporate Communications** | Intranet design, email broadcasts, digital poster distribution. | Weekly newsletter digests; intranet banners. |
| **Security Champions** | Local department advocacy, peer mentoring, feedback collection. | Departmental Q&A sessions; clean desk sweeps. |

---

## 22. Implementation Plan

### 22.1 Execution Phases:
1. **Phase 1: Preparation (Weeks -4 to 0):** Develop content modules, integrate 1-click Outlook report button, baseline simulated phishing run, and record executive video messages.
2. **Phase 2: Execution (Weeks 1 to 12):** Roll out weekly awareness themes, launch monthly micro-learning modules, conduct simulated phishing drills, and execute gamified contests.
3. **Phase 3: Evaluation (Weeks 13 to 14):** Analyze KPI metrics, evaluate SANS maturity level, publish CISO Executive Summary, and transition to continuous annual awareness cycles.

---

## 23. Conclusion

The 12-Week Security Awareness Campaign Plan provides **Apex Global Technologies** with a structured, engaging, and measurable framework to transform workforce behavior. By aligning campaign pillars with **CISA's "Secure Our World"**, **NIST SP 800-50**, and **NIST SP 800-53**, the organization reduces human threat susceptibility, accelerates incident reporting timelines, and builds an enduring culture of security resilience.

---

## 24. References

1. **Cybersecurity and Infrastructure Security Agency (CISA).** (2023). *Secure Our World Public Awareness Campaign*. U.S. Department of Homeland Security. [https://www.cisa.gov/secure-our-world](https://www.cisa.gov/secure-our-world)
2. **National Institute of Standards and Technology (NIST).** (2003). *Building an Information Technology Security Awareness and Training Program*. NIST Special Publication 800-50. U.S. Department of Commerce. [https://csrc.nist.gov/publications/detail/sp/800-50/final](https://csrc.nist.gov/publications/detail/sp/800-50/final)
3. **National Institute of Standards and Technology (NIST).** (2020). *Security and Privacy Controls for Information Systems and Organizations*. NIST Special Publication 800-53 Revision 5 (Awareness & Training Control Family AT-1 to AT-4). [https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
4. **SANS Institute.** (2023). *SANS Security Awareness Maturity Model*. SANS Security Awareness. [https://www.sans.org/security-awareness-training/](https://www.sans.org/security-awareness-training/)
5. **Cybersecurity and Infrastructure Security Agency (CISA).** (2024). *Phishing Guidance and Phishing-Resistant Multi-Factor Authentication Advisories*. [https://www.cisa.gov/phishing](https://www.cisa.gov/phishing)
6. **National Institute of Standards and Technology (NIST).** (2024). *Digital Identity Guidelines: Authentication and Lifecycle Management*. NIST Special Publication 800-63B. [https://pages.nist.gov/800-63-3/sp800-63b.html](https://pages.nist.gov/800-63-3/sp800-63b.html)

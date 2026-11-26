# ITSOLERA SOC Internship — Task 05: Major Malware Breach Report (2025–2026)

**Programme:** ITSOLERA Cybersecurity (SOC) Winter Internship  
**Task:** 05 — Malware Breach Report: Major Cybersecurity Incidents (2025–2026)  
**Prepared by:** Rahul Kumar  
**Team:** Epsilon  
**Organization:** IT Solera Pvt. Ltd.  
**Date:** 31 March 2026  

## Objective

Review ten major cybersecurity incidents from 2025–2026, identify common attack patterns and derive practical defensive lessons for SOC teams and business leaders.

## Incidents reviewed

| # | Organization | Date | Scale / impact | Primary issue |
|---|---|---|---|---|
| 1 | Cencora | Mar 2025 | Confidential patient data | Data breach and HIPAA exposure |
| 2 | Dell Technologies | May 2025 | 49 million customer records | Partner portal API abuse |
| 3 | Prudential Financial | Feb 2025 | 2.5 million individuals | Compromised employee/contractor accounts |
| 4 | Frontier Communications | Apr 2025 | 750,000 customers | RansomHub ransomware and data theft |
| 5 | Kaiser Permanente | Apr 2025 | 13.4 million individuals | Third-party tracking pixels exposing health data |
| 6 | Europol | May 2025 | Operation Cronos material | Theft of sensitive law-enforcement data |
| 7 | Omni Hotels | Mar 2025 | Payment card and guest data | Daixin Team ransomware |
| 8 | Halliburton | Aug 2025 | Corporate and operational data | RansomHub disruption of energy operations |
| 9 | Ticketmaster / Live Nation | May–Jun 2025 | 560 million records | Snowflake account without MFA; infostealer credentials |
| 10 | Microsoft | Jan–Mar 2025 | Executive email accounts | Midnight Blizzard password spray and OAuth abuse |

## Cross-incident analysis

- **MFA gap:** Ticketmaster, Microsoft and Frontier show how one unprotected account can cause a major breach.
- **Cloud and API exposure:** Dell and Ticketmaster demonstrate that perimeter controls do not protect partner portals, SaaS platforms or APIs.
- **Ransomware evolution:** Omni, Frontier and Halliburton show the shift to double extortion and real operational disruption.
- **Healthcare targeting:** Cencora and Kaiser Permanente illustrate both direct theft and inadvertent data sharing through tracking technologies.
- **Nation-state activity:** Microsoft confirms that even mature security organisations are targets of sophisticated espionage.
- **Regulatory impact:** SEC filings, state Attorney General investigations, class actions and HIPAA scrutiny are now part of breach consequence management.

## Defensive lessons

1. Enforce MFA everywhere, including administrators, test accounts and third-party access.
2. Continuously assess vendors, contractors and cloud integrations.
3. Invest in 24/7 monitoring, user behaviour analytics and threat detection to reduce dwell time.
4. Build legal and regulatory notification requirements into the incident response plan from the start.
5. Apply stronger safeguards to healthcare data and other highly regulated information.

## Repository contents

- `Rahul_Kumar_Task_05_Report.pdf` — full report with references.
- `Rahul_Kumar_Task_05_Report.docx` — editable source document.

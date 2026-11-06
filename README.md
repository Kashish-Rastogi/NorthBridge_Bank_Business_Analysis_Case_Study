# NorthBridge_Bank_Business_Analysis_Case_Study
## Digital Customer Onboarding with KYC: Business Analysis Case Study

A Business Analyst portfolio project for **Northbridge Bank**, a fictional Canadian regional bank. It shows how a manual, email based account opening process is turned into a secure digital onboarding flow with automated identity verification and KYC checks.

> **Note:** Northbridge Bank, its people and its figures are fictional and were created for this case study. Regulatory references (FINTRAC, PCMLTFA, PIPEDA, OSFI) are real and are used to keep the case realistic. All financial figures are illustrative assumptions and are labelled as such in the documents.

---

## The Business Problem

Northbridge Bank has 400,000 retail customers and 62 branches across Ontario. About 24,000 people start an online account application each year, but the process behind it is manual:

| Problem | Current state |
| --- | --- |
| Time to open an account | Median of 4-5 days |
| Applications reaching an opened account | 65% (28% abandoned, 7% declined) |
| Manual handling per opened account | 30 minutes |
| Accounts needing rework from data entry errors | 10.7% |
| Compliance reviews | Inconsistent between staff members |

Applicants email scanned documents, and staff retypes the same data into three systems: core banking, CRM and the compliance case tool.

## The Goal

Introduce a digital onboarding flow, with photo ID and selfie verification, automated sanctions and PEP screening, and risk based routing, so that:

- **80% of applications are decided within 24 hours**
- **85% of applications end in an opened account**
- **Manual handling drops to 10 minutes or less per account**
- **Rework from data errors falls below 2%**
- **Every applicant is screened with the same rules, with 0 critical audit findings**

## Business Case Highlights

| KPI | Result |
| --- | --- |
| One time investment | CAD $950,000 |
| Net present value (5 years, 10%) | $782,545 |
| Internal rate of return | 34.5% |
| Payback period | 2.4 years |
| Benefit cost ratio | 1.50 |
| Cost per online account opened | $19.00 today, $14.44 after go live |

The sensitivity analysis shows the case depends on new customer revenue, not on cost savings. The break even point is about $85 of revenue per new account per year.

---

## Documents in This Repository

| No. | Document | What it covers | Status |
| --- | --- | --- | --- |
| 01 | [Project Brief and Business Case](docs/01_Project_Brief_and_Business_Case.pdf) | Background, problem and evidence, SMART objectives, scope, high level requirements, milestones, assumptions, constraints, proposed solution, cost benefit analysis with NPV, IRR and sensitivity, recommendation | Complete |
| 02 | [Stakeholder Analysis and RACI Matrix](docs/02_Stakeholder_Analysis_and_RACI.pdf) | Register of 21 stakeholder groups, power and impact grid, engagement strategy, RACI matrix for 18 project activities | Complete |

### Coming Next

| No. | Document | Status |
| --- | --- | --- |
| 03 | Business Analysis Plan | Planned |
| 04 | Elicitation Plan and Session Notes | Planned |
| 05 | As Is Process Map (BPMN) | Planned |
| 06 | Gap Analysis and Root Cause Analysis | Planned |
| 07 | To Be Process Map (BPMN) | Planned |
| 08 | Business Requirements Document (BRD) | Planned |
| 09 | Business Rules Catalogue (KYC, AML and risk rating) | Planned |
| 10 | Functional and Non Functional Requirements | Planned |
| 11 | User Stories with Acceptance Criteria | Planned |
| 12 | API Integration Specification and Data Mapping | Planned |
| 13 | Onboarding Funnel Analysis (SQL and Power BI) | Planned |
| 14 | Requirements Traceability Matrix and UAT Pack | Planned |

---

## Business Analysis Skills Demonstrated

- **Problem framing:** turning symptoms into a measured problem statement with sources
- **SMART objectives:** baselines, targets and a defined data source for each objective
- **Scope management:** clear in scope and out of scope boundaries
- **Financial analysis:** cost benefit analysis, NPV, IRR, payback, discounted payback, ROI, benefit cost ratio and sensitivity analysis
- **Stakeholder management:** stakeholder register, power and impact grid, engagement strategies
- **Responsibility mapping:** RACI matrix with one Accountable role per activity
- **Regulatory awareness:** FINTRAC identity verification methods, PIPEDA, OSFI Guidelines B-10 and B-13
- **Risk thinking:** assumptions and constraints that a reviewer can challenge

## Tools Used

Microsoft Word and Excel, draw.io (process diagrams), Jira and Confluence (planned for the backlog and requirements), SQL and Power BI (planned for the funnel analysis).

## How to Read This Project

1. Start with **01 Project Brief and Business Case** to understand the problem, the goal and why the bank should invest.
2. Then read **02 Stakeholder Analysis and RACI Matrix** to see who is affected and who owns each decision.
3. Follow the repository as new documents are added. Each one builds on the previous documents.

## Repository Structure

```
northbridge_kyc_onboarding/
├── README.md
└── docs/
    ├── 01_Project_Brief_and_Business_Case.pdf
    └── 02_Stakeholder_Analysis_and_RACI.pdf
```

---

## Author

**Kashish Rastogi**, Business Analyst

Feedback is welcome. Please open an issue or connect on LinkedIn.

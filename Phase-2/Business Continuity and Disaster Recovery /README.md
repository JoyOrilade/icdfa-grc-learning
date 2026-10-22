
# GRC 205: Business Continuity and Disaster Recovery

## Project Overview

This project documents a **Business Continuity and Disaster Recovery (BCDR) assessment** completed as part of the ICDFA GRC 205 assignment.

The project uses a fictional educational institution, **Northbridge**, as a case study to examine how an organisation can maintain critical operations and recover from a disruption caused by flooding and power failure.

The scenario involves a temporary closure of the main site for approximately three days. The assessment considers the impact on teaching, examinations, finance, admissions, payroll, and student records.

---

## Project Objectives

The objectives of this assessment are to:

- Conduct a **Business Impact Analysis (BIA)** to identify critical business functions.
- Assess the operational impact of service disruptions.
- Define **Recovery Time Objectives (RTOs)**, **Recovery Point Objectives (RPOs)**, and **Maximum Tolerable Downtime (MTD)**.
- Examine backup and recovery arrangements using the **3-2-1 backup principle**.
- Compare cold, warm, and hot recovery strategies.
- Develop a Business Continuity and Disaster Recovery Plan.
- Define roles and responsibilities using a **RACI matrix**.
- Create communication procedures and recovery runbooks.
- Develop a recovery schedule and tabletop exercise.
- Identify corrective actions and governance requirements.

---

## Scope of the Assessment

The assessment covers the following business functions:

| Business Function | Key Consideration |
|---|---|
| Teaching and Examinations | Continuity of classes, assessments, and examinations |
| Fees and Finance | Payment processing and financial records |
| Admissions and Registration | Application processing and student enrolment |
| Payroll | Staff payment processes and payroll records |
| Records and Certificates | Protection, availability, and recovery of student records |

---

## Key Areas Covered

### 1. Business Impact Analysis (BIA)

Identifies critical business functions, their dependencies, and the potential consequences of downtime.

### 2. Recovery Objectives

The project examines:

- **Recovery Time Objective (RTO):** The target time for restoring a service.
- **Recovery Point Objective (RPO):** The acceptable amount of data loss measured in time.
- **Maximum Tolerable Downtime (MTD):** The maximum period a business function can remain unavailable before the impact becomes unacceptable.

### 3. Backup and Recovery Strategy

Considers backup resilience, the **3-2-1 backup principle**, backup integrity, access controls, and restoration testing.

### 4. Disaster Recovery Options

Compares **cold, warm, and hot recovery arrangements** to determine their suitability for different operational needs.

### 5. Business Continuity Planning

Addresses alternative working arrangements, stakeholder communication, continuity of essential services, and recovery responsibilities.

### 6. Recovery Procedures and Testing

Covers recovery runbook considerations, a recovery schedule, tabletop exercise planning, and corrective actions to improve resilience.

---

## Key Findings and Recommendations

The assessment highlights the following considerations:

- **Examinations require priority attention.** Alternative arrangements may be needed to maintain scheduled assessments while technical recovery is underway.
- **System dependencies matter.** Shared databases and authentication services can affect multiple business functions at the same time.
- **Backups must be recoverable.** Backup availability alone is insufficient; integrity checks, restricted access, independent copies, and restoration tests are also important.
- **Recovery options should match business needs.** A warm recovery arrangement is considered a potential option, subject to cost, feasibility, testing, and acceptance of residual risk.
- **Suspicious activity requires investigation.** An unusual backup-administrator login and a failed integrity check should be investigated before recovery decisions are made.

> **Note:** These are assessment findings and recommendations. They do not establish that a real organisation has implemented or validated the proposed controls.

---

## Frameworks and Concepts

The project draws on the following frameworks and business continuity concepts:

- **NIST SP 800-34** — Contingency Planning
- **ISO 22301** — Business Continuity Management
- Business Impact Analysis (BIA)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Maximum Tolerable Downtime (MTD)
- 3-2-1 Backup Principle
- RACI Matrix
- Tabletop Exercises

---

## Project Deliverables

The assignment covers the following deliverables:

1. Business Impact Analysis.
2. Recovery objectives and prioritisation.
3. Backup and recovery strategy.
4. Comparison of disaster recovery options.
5. Business Continuity and Disaster Recovery Plan.
6. Roles and responsibilities matrix.
7. Communication procedures and recovery runbook.
8. Recovery schedule and tabletop exercise.
9. Corrective actions and governance recommendations.

---

## Skills Demonstrated

- Governance, Risk, and Compliance (GRC)
- Business Continuity Planning
- Disaster Recovery Planning
- Business Impact Analysis
- Risk Assessment and Control Recommendations
- Backup and Recovery Concepts
- Incident and Crisis Communication
- Policy and Procedure Documentation
- Security Governance and Resilience

---

## Repository Structure

The repository is organised as follows:

```text
GRC205_Business_Continuity/
├── README.md
└── GRC 205 Business Continuity Assignment.pdf
```

**Important:** Ensure that the PDF filename shown above matches the actual filename uploaded to your GitHub repository.

---

## Important Notes

- Northbridge is a **fictional organisation** used for this academic case study.
- Scenario details, recovery targets, costs, and recommendations should be interpreted in the context of the assignment.
- Proposed recovery arrangements require validation, testing, and approval before implementation in a real organisation.
- This README provides an overview and does not replace the full assignment report.
- Before making the repository public, check the assignment PDF for personal information, including your student ID and email address.

---

## Author

**Joy Orilade**

- **Programme:** ICDFA GRC Training Programme
- **Course:** GRC 205 — Business Continuity and Disaster Recovery

---

*This project demonstrates the application of business continuity, disaster recovery, risk assessment, and governance concepts to a practical case study.*

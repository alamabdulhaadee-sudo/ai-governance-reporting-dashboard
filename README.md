# AI Governance & Reporting Dashboard (Power BI)

## Overview

This project demonstrates a prototype AI governance lifecycle dashboard built in Power BI. 

The dashboard simulates how a financial institution might track AI use-cases through intake, risk review, approval, and monitoring stages while enforcing governance controls such as privacy review, legal review, and SLA compliance.

---

## Objectives

- Track AI use-case lifecycle stages
- Monitor governance review completion (Privacy & Legal)
- Categorize risk levels (Low / Medium / High)
- Measure time-to-decision against SLA thresholds
- Provide executive-level summary reporting

---

## Governance Model Assumptions

Each AI use-case progresses through the following stages:

Intake → Under Review → Approved / Rejected → Monitoring

Each use-case requires:
- Privacy Review
- Legal Review
- Risk Classification

SLA Threshold: 14 days from intake to decision.

---

## Tools Used

- Power BI (Web version)
- Excel (mock governance dataset)
- GitHub (documentation and portfolio)

---

## Project Structure
ai-governance-reporting-dashboard/
├── data/
├── reports/
├── screenshots/
├── documentation/
└── README.md

# Bambinos AI Operations Automation

### AI-Powered Student Renewal and Class Scheduling Pipeline

## Project Overview

This project focuses on re-engineering and automating the student renewal and class scheduling workflow at Bambinos.

The prototype analyzes invoice records, faculty renewal forms, booking requests, class schedule bookings, and active student-batch reference data to identify valid renewals and operational exceptions.

The goal is to reduce repetitive manual work, improve data accuracy, and help the Operations team resolve renewal issues faster.

## Problem Statement

The existing renewal process involves multiple stages:

1. Invoice payment verification.
2. Faculty renewal form submission.
3. Form approval.
4. Booking request creation.
5. Batch allocation.
6. Class scheduling.

Manual handling across these stages can result in missing forms, duplicate submissions, payment discrepancies, incorrect invoice references, and batch allocation delays.

## Proposed Solution

The prototype uses Python and Pandas to reconcile the five input datasets and classify renewal records.

### Key Features

- Invoice and faculty form reconciliation.
- Payment status validation.
- Duplicate form detection.
- Missing faculty form identification.
- Invoice reference mismatch detection.
- Batch capacity analysis.
- Renewal eligibility classification.
- Exception reporting with reason codes.
- Automated follow-up message drafting.
- Operations dashboard and Excel reporting.

## Technology Stack

- Python
- Pandas
- NumPy
- Matplotlib
- OpenPyXL
- Google Colab
- GitHub

## Prototype Results

The sample dataset contains 13 invoice records.

| Metric | Result |
|---|---:|
| Total invoices processed | 13 |
| Auto-approval eligible | 3 |
| Flagged records | 10 |
| Actionable follow-up messages | 9 |
| Automation eligibility rate | 23.08% |
| Manual review rate | 76.92% |

These results represent the sample dataset and should not be interpreted as production performance.

## Project Files

- `Bambinos_AI_Renewal_Automation.ipynb` – Python implementation and analysis.
- `Bambinos_Operations_Automation_Report.xlsx` – Operational reports,

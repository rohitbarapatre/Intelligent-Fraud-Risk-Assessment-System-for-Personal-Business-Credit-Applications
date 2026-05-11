# Intelligent Fraud Risk Assessment System for Personal & Business Credit Applications

## Overview

This project presents an end-to-end Fraud Risk Assessment System designed to analyze personal and business credit card applications using rule-based fraud detection techniques, SQL analysis, and risk scoring models. The objective of the project is to simulate how financial institutions identify suspicious applications, reduce fraud exposure, and improve operational efficiency during the credit approval process.

The project uses a simulated banking dataset and demonstrates how fraud prevention teams can evaluate customer applications using multiple verification checks such as credit bureau enquiries, utilization ratios, identity mismatches, email risk analysis, and document verification workflows.

---

## Problem Statement

Manual verification of credit applications is time-consuming and inconsistent, especially when banks process thousands of applications daily. Fraudulent applications may lead to financial losses, operational inefficiencies, and compliance risks.

This project aims to build a centralized fraud assessment framework capable of:

* Identifying high-risk applications
* Improving decision-making consistency
* Reducing false approvals
* Supporting fraud investigation teams
* Automating risk categorization

---

## Project Objectives

* Design a fraud detection framework for personal and business applications
* Build a rule-based fraud scoring system
* Perform SQL-based fraud analysis
* Identify major fraud indicators
* Improve operational decision-making
* Simulate real-world banking fraud workflows

---

## Dataset Features

The dataset includes simulated customer and business application records with the following attributes:

* Application ID
* Application Type
* Customer / Business Name
* Age
* SSN / ITIN Validation
* Credit Bureau Enquiries
* Credit Utilization Percentage
* Revolving Accounts
* Email Risk Level
* Address Mismatch
* DOB Mismatch
* Identity Verification Flags
* Fraud Indicators

---

## Fraud Detection Methodology

The system evaluates applications based on multiple fraud indicators:

### Red Flags

* Excessive credit enquiries
* High credit utilization
* Suspicious identity mismatches
* High-risk email domains
* SSN/ITIN verification failures

### Risk Scoring Logic

Applications are assigned fraud risk points based on predefined conditions.

| Risk Score | Decision          |
| ---------- | ----------------- |
| 0–3        | Approve           |
| 4–6        | Review            |
| 7+         | Reject / Escalate |

---

## Technologies Used

* Python
* Pandas
* NumPy
* SQL
* Jupyter Notebook
* Data Analysis Techniques

---

## Key Insights

* Applications with high utilization and multiple bureau enquiries show increased fraud risk.
* Identity mismatches significantly increase rejection probability.
* Email risk analysis improves early fraud identification.
* Rule-based scoring helps standardize fraud investigation processes.

---

## Conclusion

This project demonstrates how fraud risk assessment systems can support banking and financial institutions in identifying suspicious applications efficiently. By combining rule-based scoring, SQL analysis, and fraud indicators, the system improves consistency, reduces manual dependency, and enhances decision-making for fraud prevention teams.

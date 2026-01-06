# Task 1: Clinic Inventory Statistical Micro-Audit

## Objective
The objective of this task is to identify where inventory errors are most likely to occur in small healthcare clinics and design lightweight, daily statistical checks to detect and reduce inventory mismatches caused by manual processes.

---

## Where Inventory Errors Are Most Likely to Occur
In small healthcare clinics, inventory errors typically arise due to manual entry, time pressure, and lack of automated controls. The most common points where errors occur include:

- Sales entries during peak OPD hours when staff are multitasking
- Manual corrections after stock-outs or emergency dispensing
- Incorrect opening balance carried forward from the previous day
- Missed entries for free samples, doctor use, or partial strip sales
- End-of-day reconciliation being rushed or skipped due to clinic closing time

These errors usually concentrate around high-velocity medicines and busy clinic periods, leading to cumulative mismatches over time.

---

## Daily Statistical / Randomized Checks
Instead of full daily reconciliation, the following lightweight checks can be run every day with minimal effort:

- **Top Revenue Medicines Check**  
  Verify expected closing stock versus actual stock for the top 10 medicines by revenue contribution.

- **Zero or Negative Stock Flag**  
  Automatically flag medicines showing zero or negative balance while still being dispensed.

- **Sales Spike Detection**  
  Identify abnormal daily sales spikes by comparing current sales to a rolling 7-day average.

- **Random SKU Spot Audit**  
  Randomly select 3–5 medicines daily for physical verification to maintain discipline and awareness.

These checks can be implemented easily using Google Sheets formulas and require very limited staff time.

---

## How These Checks Improve Staff Compliance and SOP Discipline
- Staff become more careful knowing that daily and random checks are in place
- Errors are detected early before turning into major revenue leakage
- Random audits discourage intentional bypassing of SOPs
- Doctors are involved only when repeated or high-impact anomalies occur

This approach improves operational discipline and financial accuracy without increasing doctor workload or operational complexity.

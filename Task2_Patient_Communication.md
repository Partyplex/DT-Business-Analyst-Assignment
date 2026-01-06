# Task 2: Patient Care & Communication System Design

## Objective
The objective of this task is to design a simple, scalable patient care and follow-up communication system that reduces WhatsApp chaos, ensures timely patient responses, and minimizes unnecessary doctor involvement while preserving care quality.

---

## Key Problem in Small Clinics
In many small healthcare clinics:
- Patients directly message doctors on WhatsApp for follow-ups, reports, and routine queries
- Doctors get interrupted frequently, increasing cognitive load and burnout
- Important messages get missed or delayed due to message overload
- There is no structured way to track patient communication

The solution must work within existing tools and avoid adding operational complexity.

---

## Message Classification Framework
All incoming patient messages can be classified into two categories:

### 1. Automated Messages
Handled without doctor involvement:
- Appointment confirmations and reminders
- Medicine refill reminders
- Routine test result notifications
- Payment confirmations
- General clinic information (timings, location, availability)

### 2. Human-in-the-Loop Messages
Require staff or doctor review:
- Symptom-related follow-ups
- Adverse medication reactions
- Emergency or high-risk complaints
- Treatment modification requests

This classification ensures doctors are involved only when medically necessary.

---

## Google Sheets–Based Control System
A shared Google Sheet can act as a lightweight communication control hub with the following columns:

- Patient ID
- Patient Name
- Message Category (Automated / Review Required)
- Message Summary
- Priority Level (Low / Medium / High)
- Assigned To (Staff / Doctor)
- Status (Pending / Responded / Escalated)
- Response Time

Staff update the sheet, and doctors review only high-priority escalations.

---

## Workflow Design
1. Patient messages are first received by clinic staff or a shared number
2. Staff classify and log messages into Google Sheets
3. Automated responses are sent for routine queries
4. Only critical or high-risk cases are escalated to doctors
5. Doctors respond in scheduled review windows instead of constant interruptions

---

## Optional Automation (Future Scope)
- Google Apps Script can auto-send reminders and confirmations
- Priority-based notifications can alert doctors only for urgent cases
- Integration with HMS can auto-fill patient details into the sheet

---

## Impact of the System
- Reduces doctor WhatsApp overload
- Improves response consistency and patient satisfaction
- Creates accountability and traceability for patient communication
- Scales easily as clinic volume increases

This system prioritizes simplicity, discipline, and real-world feasibility without increasing operational burden.

# Task 2: Patient Care & Communication System Design

## Objective
In small healthcare clinics, doctors often receive a large number of patient messages on WhatsApp for follow-ups, reports, and routine doubts. The goal of this task is to design a simple patient communication system that reduces unnecessary doctor interruptions while ensuring patients still receive timely and proper responses.

---

## Problem Observed in Small Clinics
Based on common clinic workflows, most patient communication issues happen because:
- Patients directly message doctors for non-urgent queries
- Doctors get interrupted during OPD hours
- Important messages get lost among routine messages
- There is no clear tracking of patient communication

With limited staff and manual processes, this creates confusion and delays.

---

## Message Classification Approach
To manage this better, patient messages can be divided into two types:

### 1. Automated Messages
These do not require doctor involvement and can be handled by staff:
- Appointment reminders
- Medicine refill reminders
- Test result notifications
- Payment confirmations
- General clinic information

### 2. Review Required Messages
These require medical judgment and should be escalated:
- Symptom-related follow-ups
- Side effects or adverse reactions
- Emergency complaints
- Treatment change requests

This separation helps doctors focus only on critical cases.

---

## Google Sheets Control System
A simple Google Sheet can be used as a message tracking system with the following columns:
- Patient ID and Name
- Message Type
- Short message summary
- Priority level
- Assigned person (staff or doctor)
- Status of response

Clinic staff update the sheet, and doctors review only high-priority cases at fixed times.

---

## Practical Workflow
1. Patient messages are received by clinic staff
2. Messages are categorized and logged into the sheet
3. Routine messages get quick standard responses
4. Critical cases are escalated to doctors
5. Doctors respond during scheduled review windows

This avoids constant interruptions during consultations.

---

## Impact
This system:
- Reduces WhatsApp overload for doctors
- Improves response consistency
- Creates accountability for patient communication
- Works with existing tools and minimal training

From a practical clinic perspective, this approach is easy to implement and sustainable.

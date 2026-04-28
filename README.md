# Medication-Tracking-System

## Overview
This project is a Python-based medication tracking and reminder system designed for a small clinic managing patients with chronic conditions such as diabetes and hypertension. The system helps track patient medication schedules, simulate reminders, and generate reports for missed doses so the care team can follow up with patients.

## Purpose
Medication noncompliance can lead to worsening health conditions, increased hospital visits, and poorer patient outcomes. This project demonstrates how a simple Python system can support medication adherence by organizing medication schedules and identifying missed doses.

## Features
- Stores patient information including name, age, condition, and medication list
- Tracks medication details such as medication name, dosage, frequency, and time of day
- Simulates time passing using loops
- Checks the current simulated time against each patient’s medication schedule
- Sends medication reminders using print statements
- Tracks missed reminders
- Generates a missed medication report for care team follow-up
- Uses HIPAA-aware design by limiting unnecessary patient identifiers

## Technologies Used
- Python
- Loops and conditional logic
- Dictionaries and lists
- Functions
- Basic reporting logic

## How It Works
The program stores seven patients, each with at least three medications. Each medication includes its dosage, frequency, and scheduled time of day. The system simulates time passing and checks whether any patient is due for a medication reminder.

When a scheduled medication time is reached, the system prints a reminder. If the medication is missed, the system records the missed dose and includes it in a final report for the care team.

## Example Output
```text
Reminder: John D. needs to take Metformin 500mg at 8:00 AM.

Missed Medication Report:
Patient: John D.
Medication: Lisinopril
Scheduled Time: 12:00 PM
Status: Missed

HIPAA Considerations
This project is designed for educational purposes and does not use real patient data. In a real clinical setting, patient information would need to be protected using proper access controls, encryption, authentication, audit logs, and secure storage methods.
Project Goals
Demonstrate basic healthcare workflow automation
Support medication adherence monitoring
Improve care team visibility into missed doses
Apply Python programming to a real-world health informatics problem

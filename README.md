# Threat Model and Secure Configuration

## Overview
This project identifies security risks in a sample web application that supports user registration, login, and profile viewing. It documents assets, data flows, trust boundaries, STRIDE threats, risk priorities, and recommended defensive controls. The scores below are illustrative and should be updated after reviewing the actual application.

## Included files
- `Threat_Model_Report.pdf` — printable project report.
- `Threat_Model_Report.docx` — editable report.
- `threat_model_diagram.png` — data-flow and trust-boundary diagram.
- `risk_register.csv` — risk scoring table.
- `hardening_checklist.csv` — editable security checklist.
- `README.md` — project summary and submission notes.

## Scope and assumptions
This is a sample model for a web application with user registration, login, profile viewing, a web server, a database, and an external email service. Replace these assumptions with the real architecture before claiming that controls are implemented.

## Risk scoring
Risk score = Likelihood × Impact. Both use a 1–5 scale. Suggested bands: 1–4 Low, 5–9 Medium, 10–15 High, 16–25 Critical. Scores are illustrative, not the result of a live penetration test.

## Important limitations
This deliverable is a threat-modeling exercise and security plan. It does not prove that a real application is secure, and it does not claim that any listed control has been implemented. The checklist starts as “Not verified”; update it only after testing.

## Submission
Upload this folder or the ZIP to a repository or cloud folder and create one view-only/public link. Include all supporting files in the same folder/repository so one link covers the full submission.

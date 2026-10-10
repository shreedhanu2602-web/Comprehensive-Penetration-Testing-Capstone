# Comprehensive Penetration Testing Capstone — Security Lab Repo

## Purpose
An educational capstone package for documenting an authorized security assessment. The included report uses a **simulated training environment** and clearly labels example findings. It does not claim that a real external target was tested.

## Contents
- `Comprehensive_Penetration_Testing_VAPT_Report.pdf` — formal report (16 pages).
- `scripts/check_security_headers.py` — passive HTTP response-header review tool; sends one GET request only.
- `lab/scope_and_rules_of_engagement.md` — scope, permissions, exclusions, and safety rules.
- `lab/findings_register.csv` — example finding register for the simulated lab.
- `docs/remediation_plan.md` — prioritized remediation timeline.
- `docs/retest_checklist.md` — validation checklist.
- `docs/limitations.md` — evidence and scope limitations.

## Run the passive header checker
Python 3.9+:
```bash
python scripts/check_security_headers.py https://your-authorized-host.example
```
Use only a host you own or have written permission to assess. The tool performs one ordinary GET request; it does not crawl, exploit, brute-force, or bypass authentication.

## Important
The findings and scores in the report are illustrative training examples. Before presenting this as a real assessment, replace simulated evidence, scores, dates, and results with findings from your authorized lab exercises and mentor-approved scope. Never publish credentials, private keys, tokens, personal data, or unredacted screenshots.

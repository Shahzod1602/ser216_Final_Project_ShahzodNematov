# SER216 Final Project — Digital Parking Permit System

**Student:** Shahzod Nematov
**Course:** SER216 — Software Engineering
**Term:** Spring 2026
**Submission Date:** 2026-05-04

## Project Overview

A digital parking permit system for a university. The system lets students and
staff register vehicles, request parking permits, check available parking
zones, and report parking issues. Security staff verify permits and update
violation records.

The repository holds every artifact required for the final practical exam:
requirements, workflow diagram, test plan, defect analysis, and the supporting
GitHub evidence (branches, commits, pull request, merge).

## Tools Used

| Purpose             | Tool                       |
| ------------------- | -------------------------- |
| Report writing      | Google Docs                |
| Test case table     | Google Sheets              |
| Workflow diagram    | diagrams.net               |
| Version control     | Git + GitHub               |
| PDF generation      | macOS textutil / Preview   |

## Files in this Repository

```
ser216_Final_Project_ShahzodNematov/
├── README.md                    — this file
├── final_report.pdf             — final report submitted with the project
├── final_report.md              — markdown source of the report
├── diagrams/
│   └── workflow_diagram.svg     — Vehicle Registration → ... → Verification
├── tables/
│   └── test_cases.csv           — 6 test cases (system, acceptance, regression)
├── screenshots/                 — GitHub evidence screenshots
│   ├── repo_homepage.png
│   ├── readme.png
│   ├── commits.png
│   ├── branch.png
│   ├── pull_request.png
│   ├── pr_merged.png
│   └── pdf_uploaded.png
└── notes/
    └── tools_used.md
```

## Workflow

The work followed the workflow taught in SER216:

1. Capture the requirements (4 functional + 2 non-functional).
2. Draw the end-to-end workflow diagram in diagrams.net.
3. Build the test case table in Google Sheets (6 cases — 2 system, 2
   acceptance, 2 regression).
4. Analyze the supplied defect (expired permit shown for a valid permit).
5. Produce the final PDF report and push everything to GitHub through a
   feature branch and pull request.

## GitHub Workflow

1. `main` branch initialised with this README.
2. Feature branch `feature/test-plan` created for the project work.
3. At least three meaningful commits added on the feature branch.
4. Pull request opened from `feature/test-plan` → `main`.
5. Pull request reviewed and merged.
6. Final PDF uploaded and tagged inside the repository.

## Repository Link

<https://github.com/Shahzod1602/ser216_Final_Project_ShahzodNematov>

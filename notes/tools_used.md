# Tools Used

| Activity                | Tool                       | Why                                                                |
| ----------------------- | -------------------------- | ------------------------------------------------------------------ |
| Writing the report      | Google Docs                | Easy formatting, autosave, can export to PDF                       |
| Test case table         | Google Sheets / CSV        | Tabular data, easy to share, exported as CSV for the repository    |
| Workflow diagram        | diagrams.net (drawio)      | Free, web based, exports clean SVG/PNG                             |
| Version control         | Git + GitHub               | Required by the assignment; supports branches, PRs, and history    |
| PDF export              | macOS `textutil` + Preview | Convert markdown/HTML to PDF without extra installations           |

# Process Notes

1. Wrote the requirements first so the rest of the artifacts stayed aligned.
2. Drew the workflow diagram once the actors and steps were clear.
3. Built the test cases against each functional requirement (so every
   requirement is covered at least once) and added two regression tests to
   guard the duplicate-plate fix and the new expiry-display fix.
4. Did the defect analysis last because it depends on the verification flow
   and on the regression test design.
5. Pushed everything through a feature branch, opened a pull request, and
   merged into `main` to satisfy the GitHub evidence requirement.

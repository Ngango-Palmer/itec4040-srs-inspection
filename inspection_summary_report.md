# Inspection Summary Report


## Inspection Identification

- **Project:** SNU Research Grant Management System
- **Meeting Date:** 11/25/2026

## Work Product Description

Our assigned draft was the SRS in 5.zip for the SNU Research Grant Management System. Section 1.1 identifies it as Version 1.0, Release 1. Package has four use cases and mockups, plus sections on data, interfaces, and security. We utilize section IDs because the draft does not provide page numbers.

## Inspectors

| #   | Role      | Inspector | Preparation Time (hours) |
| --- | --------- | --------- | ------------------------ |
| 1   | Author    | N/A          | N/A                         |
| 2   | Moderator | Narin          | 1.5                         |
| 3   | Recorder  | Nicholas          | 2                         |
| 4   | Reader    | Palmer          | 1.5                         |
| 5   | Inspector | Kunga          | 1.5                         |
| 6   | Inspector | N/A          | N/A                         |
| 7   | Inspector | N/A          | N/A                         |
|     |           |              |                             |
## Inspection Data

| Metric                   | Value              |
| ------------------------ | ------------------ |
| Planned for Inspection   | Overview, 3.1.1-3.1.4 + related mockups, 4.3, 5.2 and 6.5, and relevant business rules + evidence       |
| Actually Inspected       | SRS overview (Main.md 1.1, 1.3, 3.0-3.1), use cases 3.1.1-3.1.4 and the mockups, 4.3 (data retention), 5.2 (software interfaces), 6.5 (security), and business rules, stakeholder evidence cited in the issue log       |
| Meeting Time             | 42 minutes, 35 seconds       |
| Total Planning Effort    | 1 hour |
| Total Overview Effort    | N/A |
| Total Preparation Effort | 6.5 hours |
| Actual Rework Effort     | N/A |

## Inspection Process Description

- Planning: We used first call to figure out what the assignment required.
  - Narin moderates, Palmer reads draft, Kunga raises findings, and Nicholas keeps logs.
- Prep: We had candidate findings ready with respective section references
- Meeting: Narin, Palmer, Nicholas, and Kunga attended recorded meeting.
  - Narin introduced issue, Palmer summarized, Kunga explained gap and why it mattered, Nicholas read back the proposed entry, then group agreed on what to keep in issue log.
- Coverage: We covered the SRS overview in Main.md, use cases 3.1.1-3.1.4 and the mockups, 4.3 on data retention, 5.2 on software interfaces, 6.5 on security, business rules and stakeholder evidence referenced in log.

## Summary of Issues

We logged 12 issues (6 major and 6 minor)
  - Introduction includes adjudication in release 1, but the supplied use cases stop at corrections.
    - Scope boundary is unclear.
  - Submission email exception points to step that does not exist. Draft leaves open where address and rank come from and who checks eligibility in release 1.
  - There is no testable behavior for overlooked Chair request.
    - Also leaves unclear which applications a Chair can open.
  - Request flow ends before applicant makes the corrections. Draft leaves open how a signed correction gets through after deadline and if unchanged files need to be reuploaded.
  - Three-year retention rule has no start date, the email interface leaves failed correction notices unaccounted for.
  - Scoring rule leaves out the 30% weight for Student Success that's stated in the email.
## Product Appraisal

**RECOMMENDATION**
- [ ] accepted as is
- [ ] conditionally accepted upon verification
- [x] reinspect following rework
- [ ] inspection not completed

**OTHER COMMENTS**
We recommend reinspecting after rework since Issue 6 leaves it unclear on how an applicant gets a new Chair signature and returns a correction after the deadline, we would like to check that workflow again once the draft is revised with the changes.


----
*Copyright © 2001 by Karl E. Wiegers. Permission is granted to use, modify, and distribute this document.*
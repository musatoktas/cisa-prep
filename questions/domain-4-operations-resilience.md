# Domain 4: Information Systems Operations and Business Resilience

Original practice questions. Try each one before opening the answer.

---

**1.** What should be completed FIRST when developing a business continuity plan?

- A. Selecting a recovery site
- B. A business impact analysis
- C. Purchasing backup equipment
- D. A full interruption test

<details><summary>Answer</summary>

**B.** The BIA identifies critical processes and recovery requirements (RTO, RPO). The recovery strategy and site are chosen based on it.
</details>

---

**2.** A recovery point objective (RPO) of one hour MOST directly determines:

- A. How quickly systems must be back online
- B. How frequently data must be backed up or replicated
- C. The size of the recovery site
- D. The number of BCP team members

<details><summary>Answer</summary>

**B.** RPO is the maximum acceptable data loss measured in time, so it drives backup or replication frequency. RTO (A) is the maximum acceptable downtime.
</details>

---

**3.** Which backup approach requires the FEWEST backup sets to restore a full system?

- A. Full backup weekly with daily incremental backups
- B. Full backup weekly with daily differential backups
- C. Daily incremental backups only
- D. Monthly full backup with daily incremental backups

<details><summary>Answer</summary>

**B.** A restore needs the last full backup plus the latest differential. Incremental schemes need the full backup plus every incremental since then.
</details>

---

**4.** What is the BEST evidence that backups are effective?

- A. The backup software reports no errors
- B. Backup tapes are stored offsite
- C. Data has been successfully restored in a test
- D. The backup policy is approved

<details><summary>Answer</summary>

**C.** Only a successful restore proves the backup can be used for recovery.
</details>

---

**5.** Which BCP test is the LEAST disruptive while still validating that recovery procedures work on the recovery systems?

- A. Checklist review
- B. Full interruption test
- C. Parallel test
- D. Walk-through only

<details><summary>Answer</summary>

**C.** A parallel test brings up the recovery site and processes alongside production without stopping it. Checklist and walk-through tests (A, D) do not exercise the systems. A full interruption test (B) is the most disruptive.
</details>

---

**6.** An emergency change was made to production at night to fix a critical failure. What should happen next?

- A. Nothing, because emergency changes are exempt from change management
- B. The change should be documented, reviewed and approved after the fact through the change process
- C. The developer who made it should be disciplined
- D. The change should be reversed until it is approved

<details><summary>Answer</summary>

**B.** Emergency changes bypass prior approval for speed but must be documented and approved retrospectively, with access logged.
</details>

---

**7.** What is the difference between incident management and problem management?

- A. There is no difference
- B. Incident management restores service quickly; problem management finds and removes the root cause
- C. Problem management handles only hardware issues
- D. Incident management is only for security events

<details><summary>Answer</summary>

**B.** Incidents are about restoring normal service as soon as possible. Problem management investigates root causes to prevent recurrence.
</details>

---

**8.** Which recovery site offers the FASTEST recovery?

- A. Cold site
- B. Warm site
- C. Hot site
- D. Reciprocal agreement with another company

<details><summary>Answer</summary>

**C.** A hot site is fully equipped and can be operational within hours. A mirrored site would be faster still, but it is not among the options.
</details>

---

**9.** An IS auditor finds that users in the finance team maintain complex spreadsheets that feed the general ledger. What is the GREATEST concern?

- A. The spreadsheets may be slow to open
- B. End-user computing may lack change control, access control and review, causing undetected errors in financial reporting
- C. Users may need more training in spreadsheet formatting
- D. The spreadsheets use too much storage

<details><summary>Answer</summary>

**B.** End-user computing often falls outside formal IT controls. When it feeds financial reporting, unreviewed errors or changes can lead to material misstatement.
</details>

---

**10.** Who should approve the business impact analysis?

- A. The IT operations manager
- B. Business process owners and senior management
- C. The external auditor
- D. The backup administrator

<details><summary>Answer</summary>

**B.** The BIA reflects business priorities and tolerances, so the business must own and approve it.
</details>

# Domain 3: Information Systems Acquisition, Development and Implementation

Original practice questions. Try each one before opening the answer.

---

**1.** What is the PRIMARY purpose of a business case for a new system?

- A. To describe the technical architecture
- B. To show that the investment delivers value that justifies its cost and risk
- C. To list the project team members
- D. To define the test plan

<details><summary>Answer</summary>

**B.** The business case justifies the investment and is the baseline for later benefits realisation. It should be revisited at key project stages.
</details>

---

**2.** An IS auditor is asked to join a system development project. Which role is MOST appropriate?

- A. Designing the application controls
- B. Approving the final system design
- C. Advising on control requirements and reviewing them at key stages
- D. Performing user acceptance testing

<details><summary>Answer</summary>

**C.** Early involvement as an adviser helps build controls in, while the auditor stays independent. Designing controls (A), approving designs (B) or doing UAT (D) would impair objectivity for later audits.
</details>

---

**3.** Who should sign off user acceptance testing?

- A. The lead developer
- B. The project manager
- C. The business owners and users of the system
- D. The IS auditor

<details><summary>Answer</summary>

**C.** UAT confirms that the system meets business requirements, so the business owns the sign-off.
</details>

---

**4.** A batch of payment records includes a field holding the sum of all account numbers in the batch. This is an example of:

- A. A check digit
- B. A hash total
- C. A record count
- D. A limit check

<details><summary>Answer</summary>

**B.** A hash total adds up a field that has no meaning as a sum (such as account numbers) to detect lost, added or changed records. A record count (C) only counts records. A check digit (A) validates a single number.
</details>

---

**5.** Which conversion approach carries the LOWEST risk of business disruption when replacing a core system?

- A. Direct cutover
- B. Parallel run
- C. Phased approach by module
- D. Pilot at one branch

<details><summary>Answer</summary>

**B.** Running old and new systems side by side lets the organisation compare results and fall back if needed. It is the most expensive, but it has the lowest disruption risk. Direct cutover (A) is the riskiest.
</details>

---

**6.** In a DevOps environment, developers can deploy their own code to production through an automated pipeline. Which control BEST reduces the risk of unauthorised changes?

- A. Removing all developer access to source code
- B. Mandatory peer review and approval in the pipeline before deployment, with logs of who approved what
- C. Annual review of the pipeline configuration
- D. Requiring developers to email the change manager after deployment

<details><summary>Answer</summary>

**B.** An enforced peer review and approval gate inside the pipeline replaces manual segregation of duties and leaves an audit trail. An annual review (C) and after-the-fact emails (D) are weak.
</details>

---

**7.** During data migration, which control BEST ensures that all records were transferred completely and accurately?

- A. Asking users if the new system looks correct
- B. Reconciling record counts and control totals between source and target
- C. Comparing screen layouts in the old and new systems
- D. Running the migration twice

<details><summary>Answer</summary>

**B.** Reconciling counts and control totals gives objective evidence of completeness and accuracy.
</details>

---

**8.** What should be the PRIMARY focus of a post-implementation review?

- A. Whether the project team worked overtime
- B. Whether the expected benefits are being achieved and the controls are working as designed
- C. The cost of the project management tool
- D. The number of change requests raised during development

<details><summary>Answer</summary>

**B.** The post-implementation review compares results with the business case and checks that controls operate. Lessons learned are a secondary output.
</details>

---

**9.** Which test is MOST important to perform after a change to one module of an application?

- A. Unit test of the changed module only
- B. Regression test to confirm that unchanged functions still work
- C. Stress test of the database
- D. Usability test of the interface

<details><summary>Answer</summary>

**B.** Regression testing makes sure the change did not break existing functionality.
</details>

---

**10.** Scope creep in a project is BEST controlled by:

- A. Adding more developers
- B. A formal change control process for requirements, with impact assessment and approval
- C. Extending the deadline whenever a new requirement appears
- D. Freezing all requirements before the business case is approved

<details><summary>Answer</summary>

**B.** Formal requirement change control assesses cost, time and risk impact before approving changes. Freezing everything before approval (D) is unrealistic and does not manage later change.
</details>

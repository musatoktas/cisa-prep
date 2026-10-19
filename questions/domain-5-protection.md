# Domain 5: Protection of Information Assets

Original practice questions. Try each one before opening the answer.

---

**1.** In a digital signature, the sender signs the message hash with:

- A. The receiver's public key
- B. The sender's private key
- C. The sender's public key
- D. A shared symmetric key

<details><summary>Answer</summary>

**B.** The sender signs with their private key and anyone can verify with the sender's public key. This proves origin (authentication), integrity and non-repudiation.
</details>

---

**2.** Which control MOST effectively prevents a terminated employee from accessing systems?

- A. Quarterly access reviews
- B. Revoking access as part of the HR termination process, on or before the last day
- C. Changing shared passwords every 90 days
- D. Monitoring logs for after-hours logins

<details><summary>Answer</summary>

**B.** Timely deprovisioning linked to the HR process is preventive. Access reviews (A) and log monitoring (D) are detective and come later.
</details>

---

**3.** Hashing a file before and after transfer provides assurance of:

- A. Confidentiality
- B. Integrity
- C. Availability
- D. Non-repudiation

<details><summary>Answer</summary>

**B.** A matching hash shows the file was not changed. Hashing does not hide content, so it gives no confidentiality.
</details>

---

**4.** What should a penetration testing team obtain BEFORE starting the test?

- A. A list of all employee passwords
- B. Written authorisation from management defining scope and rules of engagement
- C. Administrator access to every system
- D. Approval from the internet service provider

<details><summary>Answer</summary>

**B.** Without written authorisation and an agreed scope, a penetration test can be illegal and can disrupt operations.
</details>

---

**5.** A security incident is confirmed on a server that may need to be used in legal proceedings. What should be done FIRST?

- A. Rebuild the server from a clean image
- B. Preserve evidence, for example by capturing volatile data and creating forensic images, while maintaining chain of custody
- C. Notify the press
- D. Delete the attacker's files

<details><summary>Answer</summary>

**B.** Evidence must be preserved before systems are changed, or it may be lost or inadmissible. Containment should be planned so it does not destroy evidence.
</details>

---

**6.** Who should approve a user's access to a sensitive application?

- A. The user's colleague
- B. The system administrator
- C. The data or application owner, based on a business need
- D. The helpdesk

<details><summary>Answer</summary>

**C.** The owner approves based on business need and least privilege. The administrator grants access after approval. This separates approval from implementation.
</details>

---

**7.** Which control BEST protects data on lost or stolen laptops?

- A. A strong screen saver password
- B. Full-disk encryption
- C. Antivirus software
- D. A cable lock

<details><summary>Answer</summary>

**B.** Full-disk encryption keeps data unreadable even if the drive is removed. A screen saver password (A) can be bypassed by removing the disk.
</details>

---

**8.** In an infrastructure-as-a-service (IaaS) cloud model, who is typically responsible for patching the guest operating system?

- A. The cloud provider
- B. The customer
- C. The internet service provider
- D. Nobody, because cloud systems are patched automatically

<details><summary>Answer</summary>

**B.** In IaaS, the provider secures the physical infrastructure and virtualisation layer. The customer manages the guest operating system, applications and data.
</details>

---

**9.** What is the MOST effective way to reduce the risk of phishing attacks?

- A. Blocking all external email
- B. A combination of regular security awareness training and technical email filtering
- C. Changing passwords monthly
- D. Installing a firewall

<details><summary>Answer</summary>

**B.** Phishing targets people, so awareness training is essential, and technical filtering reduces how many attempts reach them. Blocking all email (A) is not practical.
</details>

---

**10.** An IS auditor reviews firewall rules and finds a rule allowing any traffic from any source to any destination on all ports. What should the auditor do FIRST?

- A. Delete the rule
- B. Determine the business reason, who approved it, and the exposure it creates, then report it
- C. Ignore it if no incident has happened
- D. Ask the network team to disable the firewall for testing

<details><summary>Answer</summary>

**B.** The auditor does not change production configurations. The auditor understands the risk, checks for approval and compensating controls, and reports. Management removes or restricts the rule.
</details>

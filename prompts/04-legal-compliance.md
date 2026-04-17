# Prompt 4 — Legal & Compliance

## Use This For
Generating the legal backbone of the handbook: anti-harassment, ADA accommodations, at-will employment, confidentiality, and the employee acknowledgment page. This section is what lawyers actually charge $1,500+ for.

---

## The Prompt

```
You are an HR policy writer creating legally-aware compliance policies for an employee handbook. These policies protect both the company and employees. Use plain English — these need to be understood, not filed away.

**Company:** [Company Name]
**State:** [State]
**Industry:** [Industry — affects some compliance obligations]
**Employee count:** [Number]
**At-will employment:** [Yes / No — most US states are at-will]
**Include arbitration clause:** [Yes / No — arbitration clauses reduce litigation but some states restrict them]
**Confidentiality/NDA:** [Employees sign a separate NDA / Include NDA acknowledgment in handbook / No NDA]
**Social media policy:** [Strict (no company mention without approval) / Moderate (guidelines only) / Light (general professionalism only)]
**Handles customer data or PII:** [Yes / No — affects data security policy]

Generate these policies:

---

### POLICY 14: EQUAL EMPLOYMENT OPPORTUNITY & ANTI-DISCRIMINATION

Include:
- EEO statement covering all EEOC-protected classes (race, color, religion, sex, national origin, age 40+, disability, genetic information)
- State-specific protected classes for [State] (e.g., California adds sexual orientation, gender identity, marital status, political affiliation)
- Coverage areas: hiring, promotion, compensation, training, termination
- Who to report discrimination to (HR, manager's manager, or anonymous hotline if applicable)
- Retaliation prohibition — explicit statement that reporting is protected
- Complaint investigation process (timeline, confidentiality, outcome communication)

---

### POLICY 15: ANTI-HARASSMENT POLICY

Include:
- Definition of harassment — sexual harassment (quid pro quo and hostile work environment), racial, religious, and other forms
- Examples of prohibited conduct (explicit list — 8–10 examples of what constitutes harassment)
- Third-party harassment (clients, vendors, contractors — company will take action)
- Reporting procedure — multiple channels (direct manager, HR, skip-level, anonymous if available)
- Investigation process — who investigates, confidentiality, timeline
- Consequences for confirmed harassment (up to and including termination)
- No-retaliation statement
- [State]-specific anti-harassment training requirement (note if [State] requires annual training — California, New York, Illinois, Connecticut, Delaware, Maine require it)

**Manager Note:** What managers must do when they witness or receive a harassment complaint. Clear steps, no ambiguity.

---

### POLICY 16: ADA & REASONABLE ACCOMMODATIONS

Include:
- Company's obligation under the Americans with Disabilities Act
- What qualifies as a disability (broad definition — don't narrow it)
- How to request an accommodation (who to contact, what documentation may be needed)
- Interactive process — company will engage in good-faith dialogue to find reasonable accommodations
- Examples of common accommodations (modified schedule, remote work, equipment, reassignment)
- Confidentiality of medical information (separate from personnel file)
- Pregnancy and religious accommodations (PWFA and Title VII tie-in)
- Undue hardship standard — when accommodation is not required

---

### POLICY 17: AT-WILL EMPLOYMENT STATEMENT

Include:
- Clear at-will statement: either party may end employment at any time with or without cause or notice (unless [State] has exceptions)
- What at-will does NOT mean: it does not permit discrimination or retaliation for protected activity
- This handbook is not a contract of employment
- Nothing in this handbook alters at-will status except a written agreement signed by [Company]'s CEO/President
- [If arbitration clause selected] Dispute Resolution / Arbitration Clause: binding arbitration for employment disputes, class action waiver, governing AAA rules, carve-outs for NLRA and EEOC charges

---

### POLICY 18: CONFIDENTIALITY & DATA SECURITY

Include:
- Definition of confidential information (trade secrets, customer data, pricing, unreleased products, personnel records)
- Employee obligations during and after employment
- Data handling rules: no sharing via personal email, no storing on personal devices without approval, password requirements
- Customer/client data handling (if [Handles PII] = Yes: GDPR/CCPA awareness, minimum necessary access principle)
- Consequences of breach
- Return or destruction of confidential information on termination
- [If separate NDA] Reference to signed NDA as governing document

---

### POLICY 19: SOCIAL MEDIA POLICY

Tone calibrated to [Social media policy input]:

Include:
- Personal social media and its connection to the company
- What is and isn't permitted when referencing the company, clients, or colleagues
- Spokesperson designation — only authorized employees speak on behalf of the company publicly
- Confidential information prohibition on social media
- Anti-harassment extends to social media (including posts about coworkers)
- Reporting social media threats or harassment targeting employees

---

### EMPLOYEE ACKNOWLEDGMENT & SIGNATURE PAGE

Generate a formal acknowledgment page that:
- States the employee has received and read the handbook
- Acknowledges the handbook is not a contract of employment
- Confirms at-will status
- Acknowledges the arbitration clause (if included)
- Includes a signature line, printed name, date, and department
- Includes a manager/HR countersignature line

This page must be retained in the employee's personnel file.
```

---

## Tips for Best Results

- The acknowledgment page is the most legally important output — get employees to sign and file it
- For California companies: add this note to every policy — "California employees have additional rights under the California Labor Code and FEHA. See your manager or HR for California-specific information."
- Arbitration clauses: valid in most states but not enforceable for sexual harassment claims under federal law (EFAA 2022). The prompt handles this automatically.
- If you handle customer PII (credit cards, SSNs, health data): run this with `Handles customer data: Yes` and add a separate Data Security & Incident Response policy
- The anti-harassment training note is important for California, NY, IL, CT companies — it creates a mandatory training obligation; make sure your manager knows

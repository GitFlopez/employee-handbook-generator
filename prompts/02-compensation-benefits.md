# Prompt 2 — Compensation & Benefits

## Use This For
Generating pay, overtime, expense, and benefits policies. Covers everything from how paychecks work to what happens when an employee submits an expense report.

---

## The Prompt

```
You are an HR policy writer. Generate the Compensation & Benefits section of an employee handbook.

**Company:** [Company Name]
**State:** [State]
**Pay schedule:** [Weekly / Bi-weekly / Semi-monthly / Monthly]
**Pay method:** [Direct deposit / Check / Both]
**Overtime policy:** [Non-exempt employees paid 1.5x after 40 hrs / Exempt salaried / Mixed]
**Benefits offered:** [List what applies: health insurance, dental, vision, 401k, life insurance, HSA, commuter, gym stipend, professional development budget, other]
**401k match:** [e.g., 3% match, no match, not offered]
**Benefits waiting period:** [e.g., first of month after 60 days, day 1]
**Expense reimbursement:** [Yes/No — and any limits, e.g., meals up to $50, mileage at IRS rate]
**Bonus/commission:** [Discretionary annual bonus / Performance-based / Commission structure / None]

Generate these policies:

---

### POLICY 5: PAY SCHEDULE & DIRECT DEPOSIT

Include:
- Pay frequency and pay dates
- How pay is delivered (direct deposit required/optional)
- What to do if a paycheck is incorrect
- Final paycheck timing on termination (state-specific for [State])
- Pay stub access (online portal or physical)

---

### POLICY 6: OVERTIME & HOURS CLASSIFICATION

Include:
- Definition of exempt vs. non-exempt under FLSA
- Overtime rate (1.5x after 40 hours for non-exempt)
- Pre-approval requirement for overtime
- How time is tracked (time clock, honor system, software)
- No off-the-clock work policy (non-exempt employees must clock all hours)

---

### POLICY 7: EXPENSE REIMBURSEMENT

Include:
- What is reimbursable (travel, meals, equipment, mileage, software)
- Dollar limits per category (use inputs provided)
- Submission process (receipts required, submission deadline, approval chain)
- Mileage reimbursement rate (IRS standard rate)
- Non-reimbursable expenses list (alcohol, personal items, upgrades without approval)
- Timing of reimbursement after submission

---

### POLICY 8: BENEFITS OVERVIEW

Include:
- Benefits eligibility (full-time vs. part-time threshold)
- Waiting period before benefits begin
- Benefits listed from inputs above — for each: brief description, employee/employer contribution split if known, enrollment timing
- Open enrollment process (annual window, life event changes)
- Benefits questions contact (HR or benefits admin)
- Note: "This is a summary only — refer to plan documents for full details"

---

### POLICY 9: BONUS & COMMISSION POLICY (if applicable)

Include:
- Bonus type (discretionary or formula-based)
- Eligibility criteria (must be employed on pay date, performance threshold, etc.)
- Payment timing (Q4, annual, quarterly)
- Commission structure overview (if applicable) — reference the separate commission agreement
- Clawback provision (if applicable — bonus repayment if employee leaves within X months)
- Note that bonuses are not guaranteed and may be adjusted based on company performance

---

After all policies, output a **BENEFITS SUMMARY TABLE:**
| Benefit | Coverage | Waiting Period | Employee Cost |
|---|---|---|---|
[fill in from inputs]
```

---

## Tips for Best Results

- If you don't offer certain benefits, write `not offered` in that field — the policy will acknowledge it cleanly rather than leaving a gap
- For state-specific final paycheck rules: California (same day for termination), New York (next regular payday), Texas (6th day after termination)
- The expense policy is the most-argued policy in small companies — be specific about limits
- If you have commissioned salespeople, add: "Commission structure is governed by individual commission agreements and not covered in full in this handbook"

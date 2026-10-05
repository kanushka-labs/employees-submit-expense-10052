# Product-wide

Rules that apply to more than one feature.

## Requirements

- P1 Every claim is in the company currency and its amount is stored to the cent. Applies to: all.
- P2 Every submission, approval, rejection and edit of a claim is recorded in an audit log with who made it and when. Applies to: F1, F2, F3.
- P3 Expense records are kept for seven years after the claim is paid. Applies to: all.
- P4 People sign in through the organization's single sign-on. \[org default\] Applies to: all.
- P5 An employee sees only their own claims, a manager the claims of their team, and finance the approved claims across the company. Applies to: F1, F2, F3. *assumed*
- P6 A claim carries a category, and a cost centre where the company charges departments for the spend. Applies to: F1, F2, F3. *assumed*
- P7 A submitted, approved or rejected claim notifies the people it concerns by email. Applies to: F1, F2, F4. *assumed*

## Decisions

- Approved claims reach payroll as a file finance downloads and loads, not as a call to a payroll system.
- Receipt details — amount, merchant and date — are read by an agent from the attached receipt, and the employee confirms them before submitting.
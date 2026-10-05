# Expense claims

## Problem Statement

Employees claim expenses on paper or in a spreadsheet, managers approve them over email, and finance re-keys the approved amounts into payroll. Nobody can see what is waiting on whom, receipts go astray between the desk and finance, and every re-key is a chance to pay the wrong person the wrong amount.

## Solution

One web application: an employee records a claim with the receipt attached and submits it, the approver sees the claims waiting on them and decides each one with a reason, and finance pulls the approved claims into a single file for payroll. Everyone involved can see where a claim stands, so nobody has to chase.

## Actors

- Employee — submits expense claims with receipts attached and follows what happens to them.
- Manager — sees the claims their team has submitted and approves or rejects them.
- Finance — sees the approved claims across the company and exports them to payroll.

## Features

- F1 [Submit expense claims](features/F1-submit-expense-claims.md)
- F2 [Approvals](features/F2-approvals.md)
- F3 [Payroll export](features/F3-payroll-export.md)
- F4 [Notifications](features/F4-notifications.md)

## Product-wide

The rules that span the features — currency, audit, retention, sign-in and visibility — are in [Product-wide](product-wide.md).

## Out of Scope

- No mobile application; the product is a web application. \[org default\]
- No budgets, spend limits or expense reporting.
- No corporate card feeds, bank reconciliation or receipt forwarding by email.


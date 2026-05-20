## Project: Smart Operation Lab 

# Title: 002 - General ledger

In this document we discuss the general ledger and all this component (FiscalYear,ChartOfAccount,GeneralLedgerEntry)
who are the base for financial area and management control of the sistem.

## Fiscal year
Is the period use for open and close the fiscal balance of the company

Rules: - startDate \<= endDate - No overlap allowed
## Plan of account
The properties of the account is rapresented by PlanOfAccount table in the database.dbml
Hierarchy inferred automatically from 7-digit Italian account codes.

Rules: - Only leaf accounts allow postings - Parent balances = recursive
sum of child balances

Example: 1000000 1010000 1011000 1011001

Hierarchy generated from trailing zeros.

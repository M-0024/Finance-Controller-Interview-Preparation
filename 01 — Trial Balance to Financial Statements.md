# 01 — Trial Balance to Financial Statements

## Part A: Debit & Credit for Beginners (start here if this is new)

Forget everyday banking language. A debit card *pays out*, a credit *adds in* — but accounting uses these words for something else entirely: they're just the names of the **left side** and **right side** of a ledger. Nothing more.

The real rule is about **account type**, not the transaction:

| Account type | Normal side | Why |
|---|---|---|
| Assets — what the company owns or is owed | Debit | Debit is the "home side" for anything the company has a claim on |
| Expenses — money spent running the business | Debit | Same family as assets — resources going out |
| Liabilities — what the company owes others | Credit | Credit is the "home side" for anything owed away |
| Equity, Revenue | Credit | Money that belongs to owners or came in from sales |

**Applied to the two accounts that confuse people most:**

- **Accounts Receivable (AR)** — a customer hasn't paid yet, but owes you. That unpaid amount is a *resource the company has a right to collect* — exactly like cash in a drawer, just not collected yet. A resource the company owns = **Asset → Debit**. AR represents the *promise*, not the cash itself.
- **Accounts Payable (AP)** — you bought something but haven't paid the vendor. That unpaid amount is an *obligation you owe someone else* — an IOU you've written. An obligation = **Liability → Credit**.

**One-line memory hook:**
> Owed *to* you → Debit (it's yours, an asset). Owed *by* you → Credit (it's not yours, a liability).

**Increase vs. decrease also depends on account type** — this is the part that trips people up next:

| Account type | Increases with | Decreases with |
|---|---|---|
| Assets | Debit | Credit |
| Expenses | Debit | Credit |
| Liabilities | Credit | Debit |
| Equity / Revenue | Credit | Debit |

Example — a customer buys on credit, then pays later:

1. **Sale on credit:** Debit AR ↑ (new resource, a claim to collect) / Credit Revenue ↑ (income earned)
2. **Cash collected:** Debit Cash ↑ (resource increases) / Credit AR ↓ (the claim is used up — it converts to cash)

Notice AR *decreases* on the credit side in step 2 — because for an asset, credit means decrease. Every transaction touches at least two accounts, one debit and one credit, of equal amount. That's why it's called double-entry.

---

## Part B: The Core Flow (memorize this)

```
Trial Balance
   ↓
Classify Accounts (Income / Expense / Asset / Liability / Equity)
   ↓
Adjusting Entries (accruals, prepayments, depreciation, provisions)
   ↓
Profit & Loss Statement
   ↓
Balance Sheet
   ↓
Cash Flow Statement
   ↓
Financial Analysis
```

**Golden rule:** Total Debits must equal Total Credits *before* you touch the statements. If the Trial Balance doesn't tie out, a Controller investigates the gap — never forces a balance.

## What the Trial Balance Actually Is

It's simply every ledger account balance, listed once, split into its debit or credit column. It is **not** the P&L and **not** the Balance Sheet — it's the raw material both are built from.

Before preparing statements, review the Trial Balance for:
- Missing accounts
- Incorrect classifications
- Unusual balances
- Duplicate entries
- Suspense accounts
- Period-end adjustments still outstanding

## Classifying the Accounts

| Category | Typical accounts |
|---|---|
| Income | Revenue, other income |
| Expenses | COGS, employee costs, rent, utilities, D&A, finance costs, tax |
| Assets | Cash, AR, Inventory, Prepayments, PPE, Intangibles |
| Liabilities | AP, accrued expenses, loans, tax payable, provisions |
| Equity | Share capital, reserves, retained earnings, current-year profit |

## Adjusting Entries Before Closing

| Adjustment | Entry |
|---|---|
| Accrued expense (incurred, not yet invoiced) | Dr. Expense / Cr. Accrued Liability |
| Prepaid expense (paid in advance) | Dr. Prepaid Asset / Cr. Cash → then Dr. Expense / Cr. Prepaid Asset over time |
| Depreciation | Dr. Depreciation Expense / Cr. Accumulated Depreciation |
| Provisions | Recognize where an obligation exists and the amount is reasonably estimable |

**Other period-end closing checks:** bank reconciliation, AR reconciliation, AP reconciliation, intercompany reconciliation, fixed asset reconciliation, tax reconciliation, accrual review, prepayment review, suspense account review.

## How the Two Statements Link

```
Revenue and Expenses → P&L → Net Profit → Retained Earnings → Balance Sheet
```

Depreciation touches both statements simultaneously:
- Depreciation Expense → hits the P&L
- Accumulated Depreciation → reduces net PPE on the Balance Sheet

## Interview-Ready Answer

> "The Trial Balance is the starting point for preparing the financial statements. Before finalizing anything, I'd review it for completeness and accuracy, post any necessary period-end adjustments — accruals, prepayments, depreciation, provisions — then classify accounts into income, expenses, assets, liabilities and equity to build the P&L and Balance Sheet."

**Next:** see `02-ebitda-vs-ebit.md` for how the P&L numbers build up to Net Profit.

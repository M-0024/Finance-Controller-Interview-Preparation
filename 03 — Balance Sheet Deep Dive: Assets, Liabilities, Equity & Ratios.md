# 03 — Balance Sheet Deep Dive: Assets, Liabilities, Equity & Ratios

## The Fundamental Equation

```
Assets = Liabilities + Equity
```

The Balance Sheet is a snapshot at a single point in time — unlike the P&L, which covers a period.

## Anatomy

| Assets | Liabilities | Equity |
|---|---|---|
| **Non-current:** PPE, Intangibles, Long-term Investments | **Non-current:** Long-term Loans, Lease Liabilities, Long-term Provisions | Share Capital |
| **Current:** Cash, AR, Inventory, Prepayments, other current assets | **Current:** AP, Accrued Expenses, Short-term Borrowings, Tax Payable | Reserves + Retained Earnings + Current-Year Profit |

## How Net Profit Reaches the Balance Sheet

```
P&L → Net Profit → Retained Earnings → Balance Sheet (Equity)
```

**Scenario:** *"The company made ₹10M profit this year. Where does it appear?"*
> Profit first appears on the P&L. It then increases retained earnings/equity on the Balance Sheet, subject to any dividends or other equity movements.

## Journal Entry Scenarios (Common Interview Traps)

| Scenario | Entry | Statement Impact |
|---|---|---|
| Machinery purchased for cash (₹1M) | Dr. PPE ₹1M / Cr. Cash ₹1M | Total assets unchanged initially (one asset swaps for another) |
| Depreciation recognized subsequently | Dr. Depreciation Expense / Cr. Accumulated Depreciation | Reduces profit (P&L) and net PPE (Balance Sheet) |
| Accrued expense (invoice not yet received) | Dr. Expense / Cr. Accrued Liability | Expense recognized in the correct period under accrual accounting |
| Prepaid expense (e.g. 12 months' rent paid upfront) | Dr. Prepaid Asset / Cr. Cash → then Dr. Expense / Cr. Prepaid Asset monthly | Asset converts to expense over time |

**Why recognize an accrued expense before the invoice arrives?** Under accrual accounting, an expense belongs to the period in which it was *incurred*, not the period in which it's invoiced or paid.

## Analyzing the Balance Sheet — Five Lenses

| Lens | What to check |
|---|---|
| **1. Liquidity** | Current Ratio, Quick Ratio, Cash position |
| **2. Working Capital** | Current Assets − Current Liabilities |
| **3. Receivables** | AR aging, overdue balances, DSO, collection trends |
| **4. Payables** | AP aging, DPO, payment trends, supplier concentration |
| **5. Debt & Leverage** | Debt-to-Equity, Net Debt, Net Debt/EBITDA, Interest coverage |

## Key Ratios

| Ratio | Formula |
|---|---|
| Current Ratio | Current Assets ÷ Current Liabilities |
| Quick Ratio | Quick Assets (excl. inventory) ÷ Current Liabilities |
| Working Capital | Current Assets − Current Liabilities |
| DSO (Days Sales Outstanding) | Avg AR ÷ Revenue × No. of Days |
| DPO (Days Payable Outstanding) | Avg AP ÷ COGS × No. of Days |
| Debt-to-Equity | Total Debt ÷ Equity |
| Net Debt/EBITDA | (Total Debt − Cash) ÷ EBITDA |

## Worked Example (ABC Manufacturing Ltd.)

| Metric | Value |
|---|---|
| Current Assets | ₹140M |
| Current Liabilities | ₹65M |
| Working Capital | ₹75M |
| Current Ratio | 2.15x |

**Interpretation to say out loud:**
> "The company has positive working capital of ₹75M and a current ratio of approximately 2.15x. I'd want to look further at the *quality* of current assets — particularly receivables and inventory — rather than relying on the ratio alone."

## The Controller's Non-Negotiable: Investigate, Don't Force

If Total Assets doesn't equal Total Liabilities + Equity, a Controller never plugs the gap. Investigate:
- Missing or incorrectly posted account
- Opening balance issue
- Unrecorded retained earnings movement
- Suspense account
- Duplicate or missing journal entry
- Incorrect account classification

**Next:** see `04-variance-and-scenario-analysis.md` for the "revenue up, profit down" walkthrough and more journal-entry scenarios.

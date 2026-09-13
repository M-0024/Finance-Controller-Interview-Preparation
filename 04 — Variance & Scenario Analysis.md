# 04 — Variance & Scenario Analysis

## What Variance Analysis Is

Comparing actual results against a benchmark — and, critically, investigating *why* the gap exists rather than just reporting it.

Benchmarks used:
- Actual vs Budget
- Actual vs Forecast
- Actual vs Prior Year

**Example:**

| | Budget | Actual | Variance |
|---|---|---|---|
| Operating Expense | ₹10M | ₹12M | ₹2M unfavorable |

Possible causes to investigate:
- Higher volume
- Price increase
- FX movement
- One-time expenses
- Incorrect accrual
- Timing differences
- Accounting misclassification

**Interview-ready definition:**
> "Variance analysis compares actual financial results with budgeted or expected results and identifies the reasons for significant deviations."

---

## Signature Scenario: "Revenue Increased, So We Must Be Doing Better"

**Don't** accept that logic. Structured response:

1. Run a margin & variance analysis (Actual vs Budget vs Prior Year)
2. Check Gross Margin — did COGS outpace revenue growth?
3. Check EBITDA Margin — did operating expenses rise disproportionately?
4. Check EBIT — did depreciation/amortization increase?
5. Check PBT/Net Profit — finance costs, tax, one-off items?

**Interview line:**
> "I wouldn't conclude the business is performing better simply because revenue increased. I'd run a variance and margin analysis across COGS, opex, D&A, finance costs, tax and one-off items to isolate the driver of the profit movement."

### Worked Example

| Metric | Prior Year (₹M) | Current Year (₹M) | Variance (₹M) |
|---|---|---|---|
| Revenue | 260 | 300 | +40 |
| Gross Profit | 120 | 130 | +10 |
| EBITDA | 70 | 75 | +5 |
| EBIT | 58 | 60 | +2 |
| Net Profit | 48 | 45 | −3 |

Revenue grew ₹40M but Net Profit *fell* ₹3M. Root-cause checklist to talk through:
- COGS increased → gross margin down
- Employee/opex increased → EBITDA down
- Higher depreciation → EBIT down
- Higher finance cost or tax → net profit down
- One-off/exceptional items

The core Controller question: **"Why did profit decline despite revenue growth?"**

---

## More Journal Entry Scenarios

**Scenario: Machinery purchased for ₹1M cash**

```
Dr. PPE/Machinery ₹1M
Cr. Cash ₹1M
```
Impact: PPE ↑, Cash ↓. Total assets unchanged initially. Depreciation is then recorded separately:
```
Dr. Depreciation Expense
Cr. Accumulated Depreciation
```
This reduces profit and the carrying value of PPE going forward.

**Scenario: Accrued expense — electricity, invoice not yet received**

```
Dr. Electricity Expense ₹20K
Cr. Accrued Expense/Payable ₹20K
```
Recognized because the expense belongs to the period incurred, not when the invoice arrives.

**Scenario: Prepaid expense — 12 months' insurance paid upfront (₹120K)**

At payment:
```
Dr. Prepaid Insurance ₹120K
Cr. Cash ₹120K
```
Each month (₹120K ÷ 12 = ₹10K):
```
Dr. Insurance Expense ₹10K
Cr. Prepaid Insurance ₹10K
```
After one month: P&L expense = ₹10K, Balance Sheet prepaid asset = ₹110K.

**Scenario: Trial Balance doesn't balance**

Never force it. Investigate: missing debit/credit account, incorrect posting, opening balance issue, retained earnings, suspense account, duplicate/missing journal entry.

**Next:** see `05-analysis-frameworks.md` for the five-lens company analysis structure and the full ratio glossary.

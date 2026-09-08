# Finance-Controller-Interview-Preparation
### Financial Statements, Analysis & Scenario-Based Case Study

A structured, interview-ready reference for Finance Controller / Senior Finance Analyst interviews — covering the full flow from Trial Balance to management-level financial analysis, with worked examples, formulas, and scenario answers.

---

## 📌 Why This Repo Exists

Controller interviews rarely stop at definitions. They test whether you can take a **raw Trial Balance**, turn it into **financial statements**, and then **explain what the numbers mean** to management. This repo documents that entire thought process — the way an interviewer expects to see it demonstrated live, on a whiteboard or in Excel.

---

## 🗂️ Repo Structure

```
finance-controller-interview-prep/
│
├── README.md                          ← you are here
├── 01-trial-balance-to-statements.md   ← TB → P&L → Balance Sheet flow
├── 02-ebitda-vs-ebit.md                ← margin analysis & interpretation
├── 03-balance-sheet-deep-dive.md       ← assets, liabilities, equity, ratios
├── 04-variance-and-scenario-analysis.md← revenue-up-profit-down & journal entries
├── 05-analysis-frameworks.md           ← 5-lens company analysis, ratio glossary
├── 06-interview-qna.md                 ← rapid-fire Q&A bank
└── case-study/
    └── ABC-Manufacturing-FY25-26.xlsx  ← full worked Excel case study
```

---

## 1. The Core Flow (Memorize This)

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
Financial Analysis (Profitability → Liquidity → Efficiency → Leverage → Cash)
```

**Golden rule:** Debit must equal Credit *before* you touch the statements. If the Trial Balance doesn't tie out, a Controller investigates the gap — never forces a balance.

---

## 2. Profit & Loss — Build Order

| Line Item | Formula |
|---|---|
| Gross Profit | Revenue − COGS |
| EBITDA | Gross Profit − Operating Expenses |
| EBIT | EBITDA − Depreciation & Amortization |
| PBT (Profit Before Tax) | EBIT − Finance Costs |
| Net Profit | PBT − Tax |

**Key ratios to quote instantly:**
- Gross Margin = Gross Profit ÷ Revenue
- EBITDA Margin = EBITDA ÷ Revenue
- Net Profit Margin = Net Profit ÷ Revenue

---

## 3. EBITDA vs EBIT — The Question You *Will* Get Asked

| | EBITDA | EBIT |
|---|---|---|
| Stands for | Earnings Before Interest, Tax, Depreciation & Amortization | Earnings Before Interest & Tax |
| Includes D&A impact? | No | Yes |
| Best used for | Comparing operating performance across companies, regardless of financing/tax/depreciation policy | Assessing profitability after asset consumption |

**Relationship:** `EBITDA − D&A = EBIT`

> ⚠️ Interview trap: EBITDA is **not** cash flow. It ignores working capital movement, capex, interest, and tax. Say this explicitly — it signals Controller-level maturity, not just AP/analyst-level knowledge.

---

## 4. Balance Sheet Anatomy

```
Assets = Liabilities + Equity
```

| Assets | Liabilities | Equity |
|---|---|---|
| Non-current: PPE, Intangibles, Long-term Investments | Non-current: Long-term Loans, Lease Liabilities | Share Capital |
| Current: Cash, AR, Inventory, Prepayments | Current: AP, Accruals, Short-term Debt, Tax Payable | Reserves + Retained Earnings + Current-Year Profit |

**Analyze it through 5 lenses:** Liquidity → Working Capital → Receivables → Payables → Debt/Leverage.

---

## 5. Journal Entry Scenarios (Common Interview Traps)

| Scenario | Entry | Statement Impact |
|---|---|---|
| Machinery purchased for cash | Dr. PPE / Cr. Cash | Total assets unchanged initially; depreciation reduces profit + net PPE later |
| Accrued expense (invoice not received) | Dr. Expense / Cr. Accrued Liability | Expense recognized in the correct period (accrual accounting) |
| Prepaid expense | Dr. Prepaid Asset / Cr. Cash → then Dr. Expense / Cr. Prepaid Asset monthly | Asset converts to expense over time |
| Profit recognition | Net Profit flows P&L → Retained Earnings → Equity | Links the two statements |

---

## 6. "Revenue Up, Profit Down" — The Signature Controller Scenario

**Don't** assume growth = better performance. Structured answer:

1. Run a margin & variance analysis (Actual vs Budget vs Prior Year)
2. Check Gross Margin — did COGS outpace revenue?
3. Check EBITDA Margin — did operating expenses rise disproportionately?
4. Check EBIT — did depreciation/amortization increase?
5. Check PBT/Net Profit — finance costs, tax, one-off items?

**Interview line:**
> "I wouldn't conclude the business is performing better simply because revenue increased. I'd run a variance and margin analysis across COGS, opex, D&A, finance costs, tax, and one-off items to isolate the driver."

---

## 7. The Five-Lens Company Analysis Framework

| Lens | What You Check |
|---|---|
| Profitability | Revenue growth, Gross/EBITDA/EBIT/Net margins |
| Liquidity | Current Ratio, Quick Ratio, Cash position |
| Efficiency | DSO, DPO, Inventory Turnover |
| Leverage | Debt-to-Equity, Net Debt/EBITDA, Interest Coverage |
| Cash Flow | Operating / Investing / Financing / Free Cash Flow |

Say this five-lens framework verbatim when asked *"How would you analyze a company?"* — it reads as Controller-level structure, not memorized definitions.

---

## 8. Controller Mindset (Close Every Answer With This)

```
Accuracy → Completeness → Compliance → Reconciliation → Analysis → Control → Management Insight
```

> "What happened → Why did it happen → What is the financial impact → What should management do?"

---

## 9. Worked Case Study Snapshot — ABC Manufacturing Ltd. (FY 2025–26)

| Metric | ₹M |
|---|---|
| Revenue | 300 |
| Gross Profit | 130 (43.3% margin) |
| EBITDA | 75 (25% margin) |
| EBIT | 60 (20% margin) |
| Net Profit | 45 (15% margin) |
| Working Capital | 75 |
| Current Ratio | 2.15x |

Full Trial Balance → P&L → Balance Sheet → ratio build-out is in `case-study/ABC-Manufacturing-FY25-26.xlsx`, including a Trial Balance reconciliation exercise (the TB is deliberately unbalanced by ₹65M to practice the investigate-don't-force approach).

**Excel functions to reference when asked:** `SUMIFS`, `XLOOKUP`, `INDEX/MATCH`, `IFERROR`, `Pivot Tables`, `Power Query`, plus a visible **Control Checks** tab (TB difference, BS difference, P&L tie-out — all expected to equal zero).

---

## 10. Quick-Fire Q&A Bank

| Question | One-Line Answer |
|---|---|
| Why check the Trial Balance first? | Financial statements are only as reliable as the underlying ledger balances. |
| EBITDA vs EBIT? | EBITDA excludes D&A; EBIT includes it. |
| Is EBITDA cash flow? | No — it ignores working capital, capex, interest, and tax. |
| Balance Sheet doesn't balance — what now? | Investigate via reconciliation, journal entries, opening balances, suspense accounts — never force it. |
| Revenue up, profit down — why? | Run variance/margin analysis across COGS, opex, D&A, finance cost, tax. |

---

## 🔗 Related Repos in This Prep Series
- `P2P-Process-Interview-Prep` (Ariba, PR-to-PO, vendor onboarding)
- `RTR-Explained` (Record to Report deep dive)
- `Finance-FP&A-Analysis-Explained`
- `AP-Dashboard-Interview-Prep`

---

*Maintained as part of an ongoing interview-prep and knowledge-retention series ahead of Finance Controller / Finance Transformation-track interviews.*

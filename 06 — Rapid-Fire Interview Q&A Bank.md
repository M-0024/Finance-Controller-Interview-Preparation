# 06 — Rapid-Fire Interview Q&A Bank

## Trial Balance & Accounting Basics

**Q: Why check the Trial Balance first, before preparing statements?**
A: Financial statements are only as reliable as the underlying ledger balances — you need Debits to equal Credits before anything built on top of it can be trusted.

**Q: Why is Accounts Receivable a debit, and Accounts Payable a credit?**
A: AR is a resource the company has a right to collect — an asset, which lives on the debit side. AP is an obligation the company owes to someone else — a liability, which lives on the credit side. "Owed to you" = debit; "owed by you" = credit.

**Q: What is an accrued expense, and why record it before the invoice arrives?**
A: An expense incurred but not yet invoiced or paid. Under accrual accounting, it belongs to the period in which it was incurred — not the period of payment.

## EBITDA / EBIT

**Q: Why is EBITDA different from EBIT?**
A: EBITDA excludes depreciation and amortization; EBIT includes them. EBITDA − D&A = EBIT.

**Q: Is EBITDA the same as cash flow?**
A: No. EBITDA ignores working capital movements, capital expenditure, interest, and taxes.

**Q: Why would a company prefer to highlight EBITDA over Net Profit?**
A: EBITDA strips out financing structure, tax jurisdiction, and depreciation policy, making operating performance easier to compare across companies — but it can also flatter a company with heavy debt or aging assets.

## Balance Sheet

**Q: What would you do if the Balance Sheet doesn't balance?**
A: Investigate the difference through reconciliation, journal entries, opening balances, retained earnings, and suspense accounts. Never force the numbers to balance.

**Q: The company made ₹10M profit this year. Where does it appear?**
A: First on the P&L as Net Profit, which then flows into Retained Earnings/Equity on the Balance Sheet.

**Q: What happens when a company buys machinery for ₹1M cash?**
A: Dr. PPE / Cr. Cash. Total assets are unchanged initially — one asset (cash) converts into another (PPE). Depreciation recognized later reduces both profit and net PPE.

## Analysis & Scenarios

**Q: Revenue increased but profit decreased. Why?**
A: Run a variance and margin analysis to check whether COGS, operating expenses, D&A, finance costs, tax, or one-off items increased disproportionately to revenue.

**Q: How would you analyze a company overall?**
A: Five lenses — profitability, liquidity, efficiency, leverage, and cash flow. (See `05-analysis-frameworks.md` for the full breakdown.)

**Q: What's the difference between variance analysis and trend analysis?**
A: Variance analysis compares actual vs a benchmark (budget/forecast/prior year) and explains the deviation. Trend analysis looks at how a metric moves across multiple periods to spot a direction (growing, declining, stable).

## Excel / Tooling

**Q: What Excel functions would you use for this kind of analysis?**
A: SUM, SUMIF, SUMIFS, XLOOKUP, INDEX/MATCH, IF, IFERROR, ROUND, ABS, Pivot Tables, Conditional Formatting, Power Query. For larger datasets: Power Query for cleaning/transformation, Pivot Tables for analysis, and formula-based control checks for validation.

## Closing / Mindset Question

**Q: What's your overall approach as a Controller when reviewing numbers?**
A:
> "I would start by validating the Trial Balance and ensuring all necessary period-end adjustments and reconciliations are completed. Then I'd review the P&L to understand revenue growth, gross margin, EBITDA, EBIT and net profitability. I'd analyze the Balance Sheet focusing on working capital, receivables, payables, liquidity and leverage. I'd also review cash flow, because profitability doesn't necessarily mean strong cash generation. Finally, I'd perform actual-versus-budget and year-on-year variance analysis, investigate the root causes of material deviations, and provide management with actionable insights."

**The mindset to close every answer with:**
```
Accuracy → Completeness → Compliance → Reconciliation → Analysis → Control → Management Insight
```
> "What happened → why did it happen → what is the financial impact → what should management do?"

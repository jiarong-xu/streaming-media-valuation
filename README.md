# Streaming Media Valuation

**Jiarong Xu | Financial Statement Analysis · Financial Modeling · DCF Valuation**

How does the transition to streaming translate into cash generation and shareholder value?

This project examines **Paramount, Netflix and Warner Bros. Discovery (WBD)** through historical financial analysis, business-driver forecasts and discounted cash flow valuation. Netflix provides a streaming-focused benchmark; Paramount and WBD combine streaming growth with film production and declining legacy television businesses.

Each analysis connects a business question to an Excel model and a written explanation of its assumptions, formulas, results and limitations. The three standalone company models, reports and cross-company comparison are complete.

## Explore the Project

| Company | Central question | Excel model | Analysis report |
| --- | --- | --- | --- |
| Paramount | Can DTC growth offset legacy TV contraction while funding operating investment? | [Download model](models/Paramount_Valuation.xlsx) | [Read report](report/Paramount_Analysis_Report.md) |
| Netflix | How do regional membership, monetization and operating leverage translate into free cash flow? | [Download model](models/Netflix_Valuation.xlsx) | [Read report](report/Netflix_Valuation_Report.md) |
| Warner Bros. Discovery | Can Streaming and Studios offset Networks decline after investment and financial claims? | [Download model](models/WBD_Valuation.xlsx) | [Read report](report/WBD_Valuation_Report.md) |

[Read the cross-company comparison](report/Streaming_Media_Comparison.md) for a synthesis of operating drivers, cash generation, leverage and valuation sensitivity.

Start with a report for the analytical narrative, or download an Excel model and open **Summary** for its main inputs and outputs.

## Valuation Scope and Results

All three models use a **31 December 2025 retrospective baseline**, five explicit forecast years **2026–2030**, and a stable period beginning in **2031**. They use subsequently published FY2025 disclosures and archived March 2026 LSEG / Refinitiv Workspace inputs. They therefore do not reconstruct decisions using only information available at year-end 2025.

| Default assumption or result | Paramount | Netflix | WBD |
| --- | ---: | ---: | ---: |
| WACC | 6.5636% | 9.8412% | 8.1842% |
| Perpetual growth rate | 0.5% | 2.5% | 2.0% |
| **Base value per share** | **$16.94** | **$45.32** | **$3.33** |
| Bull operating case | $23.53 | $52.84 | $5.07 |
| Bear operating case | $9.76 | $32.46 | $4.03 |
| Terminal value / Base operating value | 87.7% | 74.5% | 66.4% |

Per-share estimates are in USD; financial schedules generally use USD millions. Each company's operating scenarios hold its stated WACC and perpetual growth rate fixed. Company-specific assumptions and accounting definitions remain distinct: these outputs are not a harmonized ranking, and nominal share prices do not measure relative cheapness. Netflix uses the model's split-adjusted share basis.

The estimates depend on simplified investment, financial-claim and dilution assumptions. They are historical analytical references, rather than current price targets or trading recommendations. Subsequent transaction consideration, financing and unmodelled synergies are outside scope.

## Company Analyses

### Paramount

**Question.** Can growth in direct-to-consumer revenue compensate for television decline and support cash flow after the required operating investment?

**Approach.** Forecast DTC, TV Media and Filmed Entertainment separately, apply revenue-based cost estimates, estimate after-tax operating profit and project operating assets and liabilities from revenue. The default investment assumptions use historical-average ratios. The workbook also examines holding 2025 ratios and transitioning gradually toward the historical averages.

**Interpretation.** The Base reference is **$16.94 per share** after the included debt and book-value non-controlling-interest deductions. The default investment method implies a substantial first-year asset rebuild and negative 2026 FCFF, making the investment assumption particularly consequential.

**Accounting considerations.** The August 2025 transaction splits FY2025 into Predecessor and Successor periods. Their revenue sum of **$28,891 million** is distinct from supplemental pro forma revenue of **$29,394 million**. Forecast segment bases reconcile to external consolidated revenue. Historical consolidated costs are allocated by revenue share under disclosure constraints; those allocations are not independently disclosed segment costs. The forecast tax proxy remains **16.2176%**.

### Netflix

**Question.** How much cash flow can regional membership growth, monetization and operating leverage support after taxes and reinvestment?

**Approach.** Forecast regional revenue from average memberships and average monthly revenue per membership (ARM), then estimate consolidated operating profit, taxes and revenue-linked net operating investment. The 2030 driver extension and the original forecast tax paths are explicitly identified in the report.

**Interpretation.** The Base estimate is **$45.32 per share**. Terminal value contributes **74.5%** of operating value, so long-run profitability and investment assumptions materially affect the result. The model separates actual revenue from estimated operating drivers.

**Accounting considerations.** FY2025 financial statements and regional revenue are disclosed actuals; membership and ARM inputs from 2025 onward are analyst estimates. The provider's standardized historical series is retained, with material differences from GAAP explained. Content amortization and content investment require special care: PP&E purchases alone do not capture Netflix's content spending.

### Warner Bros. Discovery

**Question.** Can Streaming and Studios growth offset Networks decline and produce sufficient cash flow after reinvestment and financial claims?

**Approach.** Combine subscriber and annual-ARPU forecasts for Streaming with Studios growth, Networks revenue-line forecasts, Corporate costs and inter-segment eliminations. Estimate an operating-profit proxy from adjusted EBITDA after D&A and recurring SBC. Retain EBITDA-linked operating investment, recalibrated to the 2025 financial base. Estimated recurring SBC is **2.0136% of revenue**.

**Interpretation.** The Base estimate is **$3.33 per share**, including current and noncurrent debt, finance leases, equity NCI and redeemable NCI. **Bear exceeds Base** because the retained investment method implies more asset release under weaker EBITDA. Higher terminal growth also lowers Base value when the implied return on operating assets is below WACC. These relationships expose the method's sensitivity; the scenarios are not an ordered valuation range.

**Accounting considerations.** The 2022 operating comparison uses pro forma combined figures, while year-end balance sheets remain actual. Forecast operating profit is a normalized proxy, not GAAP EBIT. Goodwill, acquisition-related intangibles and noncash accounting changes limit how confidently EBITDA-linked NOA changes can be interpreted as cash investment or release.

## Valuation Framework

The models follow a common sequence while retaining company-specific operating and accounting assumptions:

1. Establish historical financial inputs and reporting scope.
2. Forecast business drivers, revenue, expenses and operating taxes.
3. Estimate net operating investment and FCFF.
4. Discount five explicit cash flows and a normalized stable-period value.
5. Adjust for included financial assets, debt and other claims to derive per-share value.
6. Examine operating scenarios and valuation sensitivities.

The central investment identities are:

$$
NOA_t = OperatingAssets_t - OperatingLiabilities_t
$$

$$
FCFF_t = NOPAT_t - (NOA_t - NOA_{t-1})
$$

NOA is net operating assets; NOPAT is the model's after-tax operating-profit measure; FCFF is free cash flow to the firm. Increasing NOA represents estimated net investment and reduces FCFF. Because investment is estimated through NOA, a separate depreciation add-back and capex deduction are not appended to the same calculation. The reports explain the classifications and noncash effects that limit this approximation.

Stable-period reinvestment is recalculated consistently with growth, rather than increasing only the terminal-value denominator's growth assumption. Detailed discounting, tax and equity-bridge formulas appear in each company report.

## Data and Workbook Guide

Inputs come from company annual reports, SEC filings, earnings releases and the original LSEG / Refinitiv Workspace exports. Each report's **Input References** identifies the relevant source definitions, dates and pages. WACC values are archived project snapshots, not current market measurements. Forecast business drivers and normalization choices are analyst estimates unless identified otherwise.

The workbooks retain source-input sheets and distinguish them from historical analytical schedules, forecast assumptions and valuation calculations. Source exports may present years in descending order; analytical schedules use chronological years. Reported cash flow, standardized historical figures and model FCFF can differ in definition and should not be treated as interchangeable.

Use **Summary** for the overview and **Sensitivity** for model controls and native Excel What-If Data Tables. Control locations and available scenarios differ by workbook and are documented in the reports. After changing inputs, ensure Excel recalculates the workbook and Data Tables.

## Project Origin

Developed from a UC San Diego Financial Statement Analysis group project. **Jiarong Xu prepared the original financial models and valuation calculations for all three companies.** The original group project also included teammates' written analysis and presentation contributions. This repository presents the revised models and accompanying analytical reports.

The [cross-company comparison](report/Streaming_Media_Comparison.md) brings together business drivers, cash conversion, leverage, investment assumptions and valuation sensitivity, while explaining the accounting and modelling differences that limit direct comparisons.

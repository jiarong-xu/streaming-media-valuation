# Streaming Media Valuation

**Jiarong Xu**

Financial modeling and valuation of streaming and media businesses, with completed Paramount, Netflix and Warner Bros. Discovery analyses.

This project studies how the transition to streaming affects traditional media businesses' operating performance, cash generation and valuation. Its intended scope covers Netflix, Paramount and Warner Bros. Discovery (WBD). The three standalone models and reports for **Paramount, Netflix and Warner Bros. Discovery (WBD)** are complete. The final cross-company comparison remains to be completed.

## Start Here

| File | Contents |
| --- | --- |
| [Paramount valuation model](models/Paramount_Valuation.xlsx) | Historical inputs, segment forecasts, NOPAT, net operating assets, FCFF, DCF, operating scenarios and sensitivity analysis. |
| [Paramount analysis report](report/Paramount_Analysis_Report.md) | Business interpretation, assumptions, formulas, valuation results, limitations and input references. |
| [Netflix valuation model](models/Netflix_Valuation.xlsx) | Regional revenue drivers, operating forecast, NOA-based FCFF, DCF and sensitivity analysis. |
| [Netflix valuation report](report/Netflix_Valuation_Report.md) | Accounting basis, assumptions, formulas, results and input references. |
| [WBD valuation model](models/WBD_Valuation.xlsx) | Segment forecasts, SBC, EBITDA-linked investment, FCFF, DCF and scenario sensitivities. |
| [WBD valuation report](report/WBD_Valuation_Report.md) | Period definitions, assumptions, formulas, financial claims and method limitations. |

Download an Excel model and open **Summary** first. For Paramount, **Business History** presents reported operating data and revenue reconciliations. **Assumptions** contains the operating paths. **Sensitivity** contains the model controls and native Excel What-If Data Tables. Those tables may require automatic calculation or manual recalculation after inputs change.

## Paramount: Scope and Results

The completed Paramount component organizes historical data, forecasts revenue for DTC, TV Media and Filmed Entertainment, estimates operating profit and NOPAT, projects net operating assets, and derives FCFF and discounted cash flow value. Operating scenarios and sensitivity analysis examine how business performance, investment assumptions and discount rates affect the result.

This is a **retrospective analysis with a 31 December 2025 valuation baseline**, using disclosed FY2025 data and historical LSEG / Refinitiv Workspace inputs from March 2026. It does not claim that all information was available at the valuation baseline. Explicit forecasts cover **2026–2030**, with a normalized stable period beginning in **2031**.

| Default input or result | Value |
| --- | ---: |
| Base illustrative value per period-end share | **$16.94** |
| Bull operating case | $23.53 |
| Bear operating case | $9.76 |
| WACC | 6.5636% |
| Perpetual growth | 0.5% |
| Forecast tax proxy | 16.2176% |
| Operating value | $30,260.47 million |
| Equity reference after book-value NCI deduction | $18,774.47 million |
| Period-end shares | 1,108 million |

The default uses reconciled external segment revenue, the Base operating case and historical-average operating investment ratios. Bull and Bear change revenue paths and SG&A assumptions while holding WACC, terminal growth, tax and the selected investment method constant. These are analyst scenarios, not probabilities or management guidance.

## Paramount: Method and Key Assumptions

- **Operating forecast:** Segment revenue growth assumptions feed revenue-based cost estimates and SG&A. Consolidated historical costs are allocated by revenue share under disclosure limitations. These allocations do not represent independently disclosed segment costs or observed segment margin differences.
- **Taxes:** Forecast NOPAT uses the arithmetic mean of 2020–2024 effective tax rates, approximately 16.2176%. This proxy excludes the abnormal 2025 ETR and is not a statutory rate or a complete cash-tax forecast.
- **Operating investment:** The default estimates operating assets and operating liabilities from their 2020–2025 average annual ratios to revenue. Net operating assets equal operating assets less operating liabilities. FCFF equals NOPAT less the change in net operating assets, without appending a separate depreciation add-back and capex deduction to the same net-investment estimate.
- **Discounting:** WACC is the historical 6.5636% LSEG / Refinitiv Workspace snapshot attributed to PSKY.O on 5 March 2026, rather than a newly measured end-2025 rate. All five explicit forecast cash flows are discounted to end-2025. Terminal value uses normalized 2031 FCFF and 0.5% perpetual growth, measured at end-2030 and discounted five years.
- **Equity bridge:** The model adds included financial assets, deducts included debt and deducts $1,194 million of non-controlling interests using 2025 book value as a claim-value proxy. The resulting equity reference is divided by period-end shares.

Terminal value contributes approximately **87.7%** of operating value. Results are sensitive to terminal assumptions and the operating asset/liability ratios used to estimate reinvestment. The workbook also examines holding 2025 investment ratios and transitioning gradually to historical averages. Acquisition accounting and the split between 2025 Predecessor and Successor periods limit historical comparability. The financial-claim bridge and dilution treatment remain simplified, and subsequent acquisitions, financing and unmodelled synergies are excluded. The per-share results are assumption-dependent historical illustrations, not a current investment recommendation.

## Paramount: Data Sources

The [report's input references](report/Paramount_Analysis_Report.md#input-references) identify source definitions, dates and printed pages. Sources include Paramount Skydance's FY2025 Form 10-K, the original LSEG / Refinitiv Workspace historical exports dated 4 March 2026, the separately attributed WACC snapshot dated 5 March 2026, and the cited Damodaran FCFF and stable-growth framework. The workbook retains source-export worksheets for traceability.

The 2025 reported-period revenue sum and supplemental pro forma revenue have different accounting scopes. The forecast uses reconciled external segment revenue totaling $28,891 million, as explained in the report.

## Netflix

Netflix is the streaming-focused benchmark in this project. The analysis forecasts regional revenue from membership and monetization estimates, then estimates operating profit, taxes, net operating investment and FCFF.

The model uses an **end-2025 retrospective baseline**, **2026–2030 explicit forecasts** and **2031 stable growth**. FY2025 financial statements and regional revenue are actual disclosures; memberships and ARM from 2025 onward are analyst estimates. The historical financial analysis retains the provider’s standardized series, with material differences from GAAP explained in the report.

At the archived **9.8412% WACC** and **2.5% terminal growth**, the Base estimate is **$45.32 per share**. Bull and Bear operating cases, holding those valuation parameters fixed, are **$52.84** and **$32.46**. About **74.5%** of operating value comes from terminal value. These are assumption-dependent retrospective estimates; no current market-price recommendation is presented.

- [Excel model](models/Netflix_Valuation.xlsx) — open the Summary worksheet first.
- [Analysis report](report/Netflix_Valuation_Report.md) — methods, formulas, accounting basis, assumptions and input references.

The model retains the regional membership × ARM revenue framework, the original forecast tax-rate paths and the NOA-based FCFF approach. The 2030 extension is explicitly identified as an analyst assumption. Change WACC, terminal growth and the operating case on the Sensitivity worksheet.

## Warner Bros. Discovery

WBD provides the leveraged media-transition case in this project. The model connects Streaming subscribers and annual ARPU, Studios growth, Networks revenue decline, Corporate costs and inter-segment eliminations to adjusted operating profit, investment and FCFF.

The **end-2025 retrospective baseline** uses actual FY2025 disclosures, **2026–2030 explicit forecasts** and **2031 stable growth**. The 2022 historical operating comparison uses pro forma combined figures; year-end balance sheets remain actual. Forecast taxes and D&A ratios retain the original analyst paths. Net operating investment remains EBITDA-linked, recalibrated to the corrected 2025 base. Future recurring SBC expense is estimated at **2.0136% of revenue**.

At the archived **8.1842% WACC** and **2.0% terminal growth**, the default Base estimate is **$3.33 per share**. Bull and Bear operating scenarios give **$5.07** and **$4.03**, holding WACC, terminal growth and the SBC ratio fixed. Bear exceeds Base because the retained investment method implies greater asset release under weaker EBITDA; these are business scenarios, not an ordered valuation range. Higher terminal growth also reduces value under the low implied return on the model’s operating asset base. The report explains these limitations, including goodwill and other noncash accounting effects.

- [Excel model](models/WBD_Valuation.xlsx) — open Summary first.
- [Analysis report](report/WBD_Valuation_Report.md) — formulas, assumptions, period definitions and input references.

The estimate includes current and noncurrent debt, finance leases, equity NCI and redeemable NCI. It excludes acquisition synergies, transaction consideration and subsequent deal financing. It is not a current market-price recommendation.

## Project Origin and Authorship

The original project was a group assignment. I completed the original financial models and valuation calculations for Netflix, Paramount and Warner Bros. Discovery. This repository currently publishes the revised Paramount, Netflix and WBD models and analyses. Other group members' writing or presentation contributions are not represented as my work.

## Remaining Work

- Develop the final cross-company comparison using clearly aligned periods, definitions and valuation assumptions.

The completed standalone models and reports for all three companies are included at this stage.

# Streaming Media Valuation

**Jiarong Xu**

Financial modeling and valuation of streaming and media businesses, starting with Paramount.

This project studies how the transition to streaming affects traditional media businesses' operating performance, cash generation and valuation. Its intended scope covers Netflix, Paramount and Warner Bros. Discovery (WBD). The current published analysis covers **Paramount only**. The Netflix and WBD analyses and the final cross-company comparison remain to be completed.

## Start Here

| File | Contents |
| --- | --- |
| [Paramount valuation model](models/Paramount_Valuation.xlsx) | Historical inputs, segment forecasts, NOPAT, net operating assets, FCFF, DCF, operating scenarios and sensitivity analysis. |
| [Paramount analysis report](report/Paramount_Analysis_Report.md) | Business interpretation, assumptions, formulas, valuation results, limitations and input references. |

Download the Excel model and open **Summary** first. **Business History** presents reported operating data and revenue reconciliations. **Assumptions** contains the operating paths. **Sensitivity** contains the model controls and native Excel What-If Data Tables. Those tables may require automatic calculation or manual recalculation after inputs change.

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

## Method and Key Assumptions

- **Operating forecast:** Segment revenue growth assumptions feed revenue-based cost estimates and SG&A. Consolidated historical costs are allocated by revenue share under disclosure limitations. These allocations do not represent independently disclosed segment costs or observed segment margin differences.
- **Taxes:** Forecast NOPAT uses the arithmetic mean of 2020–2024 effective tax rates, approximately 16.2176%. This proxy excludes the abnormal 2025 ETR and is not a statutory rate or a complete cash-tax forecast.
- **Operating investment:** The default estimates operating assets and operating liabilities from their 2020–2025 average annual ratios to revenue. Net operating assets equal operating assets less operating liabilities. FCFF equals NOPAT less the change in net operating assets, without appending a separate depreciation add-back and capex deduction to the same net-investment estimate.
- **Discounting:** WACC is the historical 6.5636% LSEG / Refinitiv Workspace snapshot attributed to PSKY.O on 5 March 2026, rather than a newly measured end-2025 rate. All five explicit forecast cash flows are discounted to end-2025. Terminal value uses normalized 2031 FCFF and 0.5% perpetual growth, measured at end-2030 and discounted five years.
- **Equity bridge:** The model adds included financial assets, deducts included debt and deducts $1,194 million of non-controlling interests using 2025 book value as a claim-value proxy. The resulting equity reference is divided by period-end shares.

Terminal value contributes approximately **87.7%** of operating value. Results are sensitive to terminal assumptions and the operating asset/liability ratios used to estimate reinvestment. The workbook also examines holding 2025 investment ratios and transitioning gradually to historical averages. Acquisition accounting and the split between 2025 Predecessor and Successor periods limit historical comparability. The financial-claim bridge and dilution treatment remain simplified, and subsequent acquisitions, financing and unmodelled synergies are excluded. The per-share results are assumption-dependent historical illustrations, not a current investment recommendation.

## Data Sources

The [report's input references](report/Paramount_Analysis_Report.md#input-references) identify source definitions, dates and printed pages. Sources include Paramount Skydance's FY2025 Form 10-K, the original LSEG / Refinitiv Workspace historical exports dated 4 March 2026, the separately attributed WACC snapshot dated 5 March 2026, and the cited Damodaran FCFF and stable-growth framework. The workbook retains source-export worksheets for traceability.

The 2025 reported-period revenue sum and supplemental pro forma revenue have different accounting scopes. The forecast uses reconciled external segment revenue totaling $28,891 million, as explained in the report.

## Project Origin and Authorship

The original project was a group assignment. I completed the original financial models and valuation calculations for Netflix, Paramount and Warner Bros. Discovery. This repository currently publishes the revised Paramount model and analysis. Other group members' writing or presentation contributions are not represented as my work.

## Remaining Work

- Complete and publish the Netflix analysis.
- Complete and publish the Warner Bros. Discovery analysis.
- Develop the final cross-company comparison using clearly aligned periods, definitions and valuation assumptions.

Only the completed Paramount files are included at this stage.

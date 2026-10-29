# Paramount Skydance: Streaming Transition and Valuation

**Analyst: Jiarong Xu**  
**Valuation baseline: 31 December 2025**  
**Explicit forecast: 2026–2030; stable period begins in 2031**  
**Units: USD millions, except per-share values and stated percentages**

[Download the Excel model](../models/Paramount_Valuation.xlsx).

## Purpose, approach and result

This analysis examines whether the growth of Paramount's direct-to-consumer business can offset the contraction of legacy television and support future operating cash flow. It combines business analysis with a segment revenue forecast, revenue-based cost estimates, an operating investment schedule and a discounted cash flow valuation.

The Base calculation gives operating value of **$30,260.47 million**. After the included financial-asset/debt adjustments and a **$1,194 million non-controlling-interest deduction**, the model gives an equity reference of **$18,774.47 million**, or **$16.94 per period-end share**. Non-controlling interests use their 2025 book value as an estimate of claim value. Other investment, claim and dilution assumptions remain simplified, so this is an illustrative reference rather than a completed common-share fair value. No share-price upside or BUY recommendation is inferred from it.

The baseline is end-2025, but the analysis uses FY2025 disclosures and the original project's March 2026 market-data snapshot. It is a retrospective valuation, not a claim about information available on 31 December 2025. The model does not incorporate subsequent acquisitions, associated financing or unmodelled synergies.

## 1. Business question

Paramount combines DTC, legacy TV and Filmed Entertainment. DTC can grow through subscriptions, pricing, advertising and retention, but content and distribution costs determine how much growth becomes profit. Legacy television contributes revenue and cash generation while facing structural pressure on advertising and distribution. Film releases and licensing add volatility.

The central question is therefore not simply whether streaming revenue grows. It is whether growth and cost discipline can offset television decline while financing the operating assets needed to generate that revenue. The model examines this relationship without assuming the investment conclusion in advance.

### Operating evidence and its interpretation

| Metric, USD millions | 2023 | 2024 | 2025 reported-period sum |
| --- | ---: | ---: | ---: |
| TV Media revenue | 20,085 | 18,779 | 17,059 |
| DTC revenue | 6,736 | 7,632 | 8,584 |
| Film revenue | 2,957 | 2,955 | 3,329 |
| TV Media Adjusted OIBDA | 4,791 | 4,348 | 3,695 |
| DTC Adjusted OIBDA | (1,663) | (497) | 230 |
| Film Adjusted OIBDA | (119) | (96) | (232) |
| CFO from continuing operations | 384 | 752 | 649 |
| Cash capex, spending magnitude | 328 | 263 | 296 |
| **CFO less cash capex** | **56** | **489** | **353** |

Source: FY2025 Form 10-K, Note 19, printed II-115–116; cash-flow statement II-55. Segment revenues precede consolidation eliminations. The 2025 sum joins distinct accounting periods and is not a fully comparable pro forma earnings statement. Adjusted OIBDA excludes specified items and is distinct from GAAP EBIT and model FCFF.

DTC revenue increased approximately 12.5% from 2024 to the 2025 combined presentation. Subscription revenue rose from 5,506 to 6,583, while advertising fell from 2,114 to 1,999. The business is therefore not growing uniformly: subscription monetization contributed more than advertising. Paid-only Paramount+ subscribers increased from 76.1 million to 78.9 million, approximately 3.7%. The earlier 77.5 million 2024 figure included 1.4 million free trials and should not be mixed into a paid-only growth calculation. Source: II-25–26.

The DTC OIBDA period sum of 230 provides directional evidence of improved profitability, but purchase accounting and expense comparability prevent treating the change as a clean same-basis cash-profit improvement. TV Media revenue and Adjusted OIBDA are lower in the displayed periods; this matters because TV remains the largest revenue contributor. Film's higher 2025 reported-period revenue did not produce a positive OIBDA sum. The film perimeter also changes with Skydance, so it should not be read as organic like-for-like growth.

Historical continuing CFO less cash capex of 353 is a cash-conversion reference, not unlevered FCFF. It incorporates financing, tax and working-capital effects differently from the forecast. The company reports more detailed segment expenses, but they do not map automatically into the original forecast's allocated COGS and SG&A categories. The workbook therefore presents disclosed OIBDA alongside the original cost-estimation method rather than silently treating them as equivalent.

## 2. Historical data and accounting scope

The original working model already includes FY2025 financial inputs, followed by forecasts beginning in 2026. Historical input columns run in descending order, 2025 to 2020, and the working schedules reverse them to chronological order. The 2020–2024 forecast-tax window is an intentional estimation choice, not a 2024 valuation baseline.

The August 7, 2025 transaction divides the year into Predecessor and Successor reporting periods. Their arithmetic sums provide the original provider-based input series; they are not a single audited, consistently measured full-year income statement. Purchase accounting also limits the comparability of historical operating asset values.

### Revenue reconciliation

| FY2025 revenue measure | Amount | Use in this analysis |
| --- | ---: | --- |
| Predecessor, January 1–August 6 | 16,622 | Reported period |
| Successor, August 7–December 31 | 12,269 | Reported period |
| **Arithmetic period sum** | **28,891** | Consolidated historical revenue base retained in the model |
| Pre-close Skydance scope adjustment | 503 | Reconciliation to supplemental pro forma revenue |
| **Supplemental pro forma revenue** | **29,394** | Separately labelled company context; not substituted into the forecast calibration |

The $503 million is a revenue-scope adjustment, not a depreciation, amortization or cash-flow add-back. The source is the FY2025 Form 10-K's supplemental pro forma revenue reconciliation, printed II-20. Film revenue is reconciled on II-27–28.

### Segment sales and internal transactions

The company-reported segment revenues already include internal transactions. The provider export labels those segment totals “External Revenue,” which does not agree with the source's consolidation presentation. Adding the separately listed internal revenues again double-counts them. The reviewed forecast instead starts with each business's revenue from external customers:

| Business | Company-reported segment revenue | Internal revenue | External revenue used in the forecast |
| --- | ---: | ---: | ---: |
| DTC | 8,584 | — | 8,584 |
| TV Media | 17,059 | (50) | 17,009 |
| Film | 3,329 | (31) | 3,298 |
| **Total** | **28,972** | **(81)** | **28,891** |

$$
ExternalRevenue_i=ReportedSegmentRevenue_i-InternalRevenue_i
$$

The model forecasts these external bases separately, then adds them. Internal sales are excluded at source rather than forecast as a new revenue stream. Consequently, the 2025 forecast bases reconcile to consolidated reported-period revenue without an arbitrary allocation of a remaining difference. The archived inputs totalled 29,053, exceeding the reconciled external bases by 162: 81 of internal revenue was already embedded in segment totals, and another 81 had been added explicitly.

The underlying source export is preserved. A clearly labelled archived-input comparison is available in Sensitivity, but external revenue is the default and the basis of results in this report. Source: FY2025 Form 10-K, Note 19, printed II-115. This correction does not add the separate 503 pro forma scope adjustment.

FY2025 balance-sheet amounts used in the bridge are cash and short-term investments **3,274**, selected long-term investments **92**, debt **13,658** and period-end shares **1,108 million**. Period-end shares are distinct from the weighted-average shares used in EPS.

## 3. Revenue and cost assumptions

The following inputs are analyst estimates retained from the original Excel, not management guidance:

| Growth assumption | 2026 | 2027 | 2028 | 2029 | 2030 | 2031 stable year |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| DTC | 10% | 8% | 6% | 2% | 4% | 0.5% |
| Legacy TV | −8% | −7% | −6% | −5% | −4% | 0.5% |
| Filmed Entertainment | 3% | 2% | 2% | 2% | 2% | 0.5% |

The 2029 DTC assumption is 2%, matching the original calculation. Its increase to 4% in 2030 is retained; this is not described as a smooth decline in growth. In the stable period, all businesses grow at the same 0.5%, freezing the final forecast mix. This is a simplifying closure assumption, including an assumed stabilization of legacy TV, rather than evidence that television contraction will end in 2031.

For business $i$ and year $t$:

$$
Revenue_{i,t}=Revenue_{i,t-1}(1+g_{i,t})
$$

Historical consolidated cost of sales is allocated to each segment using its revenue share. The model does not claim these are independently disclosed segment expenses:

$$
AllocatedCOGS_{i,y}=COGS_{group,y}\frac{Revenue_{i,y}}{Revenue_{group,y}}
$$

The forecast then applies each segment's calibrated cost ratio to its own sales. DTC uses the 2022–2025 average; legacy TV and Film use 2020–2025. The resulting ratios are **68.7514%** for DTC and **66.4512%** for legacy TV and Film. Because the original allocation is proportional to revenue, differences in those calibrated ratios principally reflect the different historical windows, not observed segment margin differences.

$$
COGS_{i,t}=Revenue_{i,t}\times c_i
$$

SG&A uses the original 2020–2025 mean of annual SG&A/revenue ratios, **22.5255%**. The forecast tax proxy is the original arithmetic mean of 2020–2024 effective tax rates, **16.2176%**. It excludes the abnormal 2025 effective tax rate. A historical ETR average is an estimation proxy, not a statutory tax rate or a full cash-tax forecast.

### Operating scenarios

The workbook contains one operating forecast linked to a Base / Bull / Bear selector. These scenarios change operating assumptions while holding the selected WACC, terminal growth, tax and investment method constant. The original report's Bull/Bear growth paths and SG&A adjustments are retained through 2029; each 2030 Bull/Bear growth rate repeats its 2029 value as an explicit extension assumption. Base retains its original five-year path.

| Driver, 2026 / 2027 / 2028 / 2029 / 2030 | Base | Bull | Bear |
| --- | --- | --- | --- |
| DTC growth | 10 / 8 / 6 / 2 / 4% | 12 / 10 / 8 / 7 / 7% | 8 / 6 / 4 / 3 / 3% |
| TV growth | −8 / −7 / −6 / −5 / −4% | −6 / −5 / −4 / −3 / −3% | −10 / −9 / −8 / −7 / −7% |
| Film growth | 3 / 2 / 2 / 2 / 2% | 5 / 3 / 3 / 3 / 3% | 2 / 0 / 0 / 0 / 0% |
| SG&A/revenue adjustment | None | −1.5 percentage points | +2.0 percentage points |

These represent different combinations of streaming monetization, television decline, film performance and operating leverage. They are not probabilities or company guidance. Lower financing risk is not automatically assumed in the Bull case: operating-case comparisons use the same 6.5636% WACC and 0.5% terminal growth, separating business performance from discount-rate choices.

## 4. Operating profit, investment and FCFF

EBIT is operating profit before interest and tax. NOPAT is the model's after-tax operating profit, before financing payments. With forecast total revenue equal to the sum of the three business forecasts:

$$
EBIT_t=Revenue_t-\sum_i COGS_{i,t}-SGA_t
$$

$$
SGA_t=s\times Revenue_t,\qquad NOPAT_t=EBIT_t(1-\tau)
$$

Here $s=22.5255\%$ and $\tau=16.2176\%$, using full-precision ratios in Excel. The retained tax equation would imply a tax benefit for negative EBIT; all years in the delivered Base forecast have positive EBIT. A loss scenario would require explicit consideration of whether tax losses could be used.

The operating investment schedule uses selected operating assets (OA) and operating liabilities (OL), following the original classifications. Net operating assets (NOA) are their difference:

$$
NOA_t=OA_t-OL_t
$$

The original 2020–2025 mean annual ratios imply $OA/Revenue=1.514776$ and $OL/Revenue=0.576344$. Forecasts hold those intensities constant:

$$
OA_t=aRevenue_t,\qquad OL_t=lRevenue_t
$$

$$
\Delta NOA_t=NOA_t-NOA_{t-1},\qquad FCFF_t=NOPAT_t-\Delta NOA_t
$$

FCFF is cash flow available to capital providers before financing payments. An increase in NOA is estimated net investment and reduces cash flow; a reduction releases cash. This is a net-operating-asset method. A separate depreciation add-back and capex deduction are not appended, because doing so alongside the same net investment would duplicate adjustments. Its equivalence to a detailed cash-flow schedule depends on the selected classifications and the absence of unadjusted acquisition, foreign-exchange, disposal and other noncash balance changes.

Under the default historical-average investment method, the first forecast year raises NOA from **19,436.00** in 2025 to **26,733.70** in 2026. Consequently:

$$
FCFF_{2026}=2449.03-(26733.70-19436.00)\approx-4848.67
$$

The large negative cash flow reflects the original assumption that operating investment intensity returns to its historical average immediately. It is not a reported cash outflow or an independently established capital-spending commitment. The 2025 accounting reset makes this calibration particularly consequential.

Historical NOPAT and FCF rows in the workbook are analytical reconstructions, not reported cash flows. The abnormal 2025 ETR distorts those historical rows; they are not used as the terminal cash-flow anchor. Forecast NOPAT uses the separate 2020–2024 tax proxy described above.

### Alternative operating investment assumptions

The historical-average method remains the default; the workbook also allows two alternatives. These choices affect inferred cash investment and subsequent FCFF rather than changing the reported 2025 assets.

| Investment method | Forecast assumption | Base operating case: per-share reference |
| --- | --- | ---: |
| **Historical average, default** | Apply 2020–2025 mean annual OA/revenue and OL/revenue ratios immediately | **$16.94** |
| Hold 2025 | Maintain the 2025 OA/revenue and OL/revenue ratios | $23.58 |
| Gradual transition | Move linearly from 2025 ratios to historical averages by 2030 | $17.68 |

For the gradual method, with $t=1$ for 2026 through $t=5$ for 2030:

$$
a_t=a_{2025}+(\overline a-a_{2025})\frac{t}{5},\qquad
l_t=l_{2025}+(\overline l-l_{2025})\frac{t}{5}
$$

Here $a=OA/Revenue$ and $l=OL/Revenue$. The hold-2025 method sets $a_t=a_{2025}$ and $l_t=l_{2025}$ instead. Each method retains its 2030 ratios in the stable year, so terminal reinvestment is recalculated consistently.

Historical ratios mix accounting bases and can imply an abrupt asset rebuild; 2025 ratios can themselves be distorted by acquisition accounting and may not represent sustainable cash investment. Gradual convergence is an analyst transition rule, not a demonstrated spending plan. None is selected because it produces a preferred share value. Goodwill, content assets and noncash acquisition adjustments make a detailed investment roll-forward more informative than treating all changes in accounting NOA as cash.

## 5. Stable-period calculation beginning in 2031

The five explicit forecast cash flows are:

| Year | FCFF |
| --- | ---: |
| 2026 | (4,848.67) |
| 2027 | 2,664.65 |
| 2028 | 2,560.01 |
| 2029 | 2,711.64 |
| 2030 | 2,336.15 |
| **2031 normalized stable year** | **2,211.92** |

The stable year uses $g=0.5\%$ for each business, retains the 2030 segment cost ratios, SG&A and tax assumptions, and holds operating asset/liability intensities constant. Therefore revenue, NOPAT and NOA each grow at 0.5% from their 2030 levels:

$$
Revenue_{i,2031}=Revenue_{i,2030}(1+g)
$$

$$
NOPAT_{2031}=NOPAT_{2030}(1+g),\qquad NOA_{2031}=NOA_{2030}(1+g)
$$

$$
FCFF_{2031}=NOPAT_{2030}(1+g)-gNOA_{2030}
$$

Using the model's full-precision amounts:

$$
FCFF_{2031}\approx2329.862091\times1.005-25919.266454\times0.005=2211.915070
$$

NOPAT rises to **2,341.51**, while required net operating investment becomes **129.60**. FCFF is not simply 2030 FCFF multiplied by 1.005, because the explicit forecast's prior-year asset change differs from the investment required for stable growth. At constant intensities and margins, cash flows from 2031 onward can then grow at 0.5% under this closure assumption.

## 6. Discounting and the financial-claim bridge

WACC is the blended return required by lenders and shareholders. The model retains **6.5636%**, attributed in the original project to the LSEG / Refinitiv Workspace snapshot for PSKY.O on **5 March 2026**. It is a documented historical input used in a retrospective estimate, not a newly measured end-2025 or current market rate. The growth assumption is **0.5%**, and $WACC>g$ is required.

Terminal value represents cash flows from 2031 onward, measured at the end of 2030:

$$
TV_{2030}=\frac{FCFF_{2031}}{WACC-g}
$$

With $t=1$ for 2026 and $t=5$ for 2030, the operating value at end-2025 is:

$$
V_{operations,2025}=\sum_{t=1}^{5}\frac{FCFF_{2025+t}}{(1+WACC)^t}+\frac{TV_{2030}}{(1+WACC)^5}
$$

The summation adds the five explicit cash flows once each. The terminal term starts with 2031, so it does not count 2030 twice. Terminal value is discounted five years because its measurement date is end-2030, not because the first terminal payment occurs five years after 2025.

| Valuation component | Amount |
| --- | ---: |
| PV of 2026–2030 FCFF | 3,714.81 |
| PV of terminal value | 26,545.66 |
| **Operating value** | **30,260.47** |
| Add cash and short-term investments | 3,274.00 |
| Add selected long-term investments | 92.00 |
| Operating value plus included financial assets | 33,626.47 |
| Less included debt | (13,658.00) |
| Less non-controlling interests, book-value proxy | (1,194.00) |
| **Equity reference after book-value NCI deduction** | **18,774.47** |
| Period-end shares, millions | 1,108.00 |
| **Illustrative reference per share** | **$16.94** |

$$
V_{equity,reference}=V_{operations}+Cash+IncludedInvestments-IncludedDebt-NCI_{proxy}
$$

$$
P_{reference}=\frac{30260.469026+3274+92-13658-1194}{1108}\approx16.94
$$

The operating forecast uses consolidated business cash flows before attributing earnings to subsidiary minority owners. Non-controlling interests (NCI) represent those other owners' claims. They are therefore deducted when converting the value of the consolidated businesses into the parent shareholders' equity reference, rather than added to it. The workbook links this deduction to the reported 2025 NCI balance of **1,194** in Bal_Input_Para!B124; it is not included in the separate debt deduction of 13,658. NCI is not also deducted from forecast NOPAT or included as an operating liability.

The ideal deduction is the economic value of the minority claim. This model uses its book value as a transparent estimation proxy, which can differ from market value. The parent's book shareholders' equity is not added to the DCF value: the cash-flow valuation already estimates the economic value being attributed to shareholders. Other investment, senior/contingent-claim and dilution assumptions remain simplified. Pension and other operating-liability classifications remain as originally modelled. An undated archived market price is excluded from the comparison.

### Sensitivity and operating-case results

The following per-share sensitivities use the external-revenue Base forecast and historical-average investment method. Changing terminal growth recalculates stable-year revenue, profit and net investment before applying Gordon growth; only changing the terminal-value denominator would be inconsistent with the model.

| WACC / terminal growth | 0.0% | 0.5% | 1.0% |
| --- | ---: | ---: | ---: |
| 5.5636% | $22.02 | $23.26 | $24.78 |
| **6.5636%** | $16.30 | **$16.94** | $17.71 |
| 7.5636% | $12.10 | $12.42 | $12.79 |

These are test ranges around an archived input, not estimates of the “correct” WACC or probabilities of different outcomes. The workbook's wider five-by-five grid and its operating/investment comparisons use native two-input Excel What-If Data Tables linked to the same model inputs and final output.

At the archived 6.5636% WACC, 0.5% terminal growth and default investment method:

| Operating case | Per-share reference |
| --- | ---: |
| Base | $16.94 |
| Bull | $23.53 |
| Bear | $9.76 |

The operating-case spread illustrates the combined impact of revenue paths and SG&A discipline. The investment-method spread answers a different question: how the same operating assumptions translate into cash flow under different net-asset requirements. The two should not be treated as interchangeable risk measures or added together.

## 7. Interpretation

Terminal value accounts for **87.7%** of operating value. The model's result depends strongly on its discount rate, the stable-period closure and the historical asset-intensity calibration. A 0.5% perpetual growth assumption is modest positive nominal growth; it does not itself make the valuation conservative or precise.

The original Base growth paths and cost-calibration choices are retained, while the segment revenue bases are reconciled to external customers. The model includes all five explicit cash flows and builds a matching stable year, rather than selecting assumptions to reproduce an earlier target price. The analysis supports examining DTC monetization, television decline and reinvestment together. It does not establish a current investment recommendation.

The main remaining research needs are a detailed post-transaction cash-investment roll-forward and a fuller financial-claim/dilution valuation. The external-revenue reconciliation, linked operating scenarios and investment/WACC/g comparisons now make the principal assumptions visible, but do not eliminate estimation uncertainty.

## Using the workbook

Start on **Summary** for the selected assumptions, results and FCFF chart. **Business History** contains reported segment performance, cash-flow references and the revenue reconciliation. **Assumptions** holds editable operating paths. On **Sensitivity**, C4/C5 set active WACC and terminal growth, C18 selects the investment method, C19 selects external revenue or the archived-input comparison, and C20 selects Base/Bull/Bear. Changing these controls updates the single operating and valuation build. Scenario comparison uses the archived WACC shown in Sensitivity C3.

The source-export tabs remain unchanged for traceability. The income summary's after-tax subtotal is labelled before equity-method results and NCI; it is not parent net income. Historical NOPAT/FCF estimates should be read alongside the separately labelled reported cash-flow data.

## Input references

| Input or method | Reference |
| --- | --- |
| Reported-period revenue, supplemental pro forma reconciliation and Film scope | Paramount Skydance FY2025 Form 10-K, printed II-20 and II-27–28 |
| Segment/internal revenue and reported OIBDA | FY2025 Form 10-K, Note 19, printed II-115–116 |
| Historical continuing CFO and cash capex | FY2025 Form 10-K, printed II-55 |
| DTC subscription, advertising and paid subscriber definitions | FY2025 Form 10-K, printed II-25–26 |
| 2025 year-end cash, debt, investments, shares and NCI | FY2025 Form 10-K, consolidated balance sheet, equity statement and investment/debt notes; original provider-export row definitions retained |
| Historical financial and segment series | Original LSEG / Refinitiv Workspace exports, 4 March 2026; workbook source worksheets retain field names, units and descending years |
| Historical tax proxy | Income Fore, C40:G40; mean of 2020–2024 annual ETRs |
| Cost and SG&A calibration | Income Fore, E11:H11, C18:H18, C25:H25 and C37:H37 |
| Operating asset and liability intensities | NOPAT NOA, C10:H11; 2020–2025 annual-ratio averages |
| WACC | Original project Workspace attribution, PSKY.O, 5 March 2026; 6.5636% |
| Forecast growth and 2031 closure | Analyst assumptions displayed in Income Fore and DCF Valuation |
| FCFF and terminal-value framework | Aswath Damodaran, Free Cash Flow to the Firm and stable-growth valuation |

- [Paramount Skydance FY2025 Form 10-K](https://www.sec.gov/Archives/edgar/data/2041610/000204161026000011/psky-20251231.htm)
- [Damodaran: financial measures and FCFF](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/definitions.html)
- [Damodaran: FCFF valuation models](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/lectures/fcff.html)

The workbook uses full precision. Displayed examples and totals are rounded. Notes beside the calculation schedules explain scope, dates and the stable-year assumptions.

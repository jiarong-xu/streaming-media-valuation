# Netflix: Operating Forecast and DCF Valuation

## Purpose and analytical question

This analysis examines how Netflix's regional scale, monetization and operating costs translate into free cash flow and equity value. Netflix provides the streaming-focused benchmark within a comparison of Netflix, Paramount and Warner Bros. Discovery. Its subscription platform differs from the other companies' combinations of streaming, film studios and legacy television.

The central question is whether continued membership and monetization growth can support the cash flows implied by a standalone valuation, after allowing for taxes and the investment required to grow the business. The model separates regional revenue drivers, consolidated expense assumptions and net operating investment so readers can see how each affects value.

The Base case produces **$45.32 per share**. At the same WACC and terminal growth rate, the Bull and Bear operating cases produce **$52.84** and **$32.46**. These are model estimates, not current trading recommendations. No undated share price is used to calculate upside or downside.

## Valuation date, scope and units

The valuation baseline is **31 December 2025**. The explicit forecast covers **2026–2030**; **2031** is the first stable-growth year. Cash flows are discounted at year-end. Monetary amounts are in **USD millions**, memberships and shares are in **millions**, and per-share values are in USD.

This is a **retrospective analysis** using subsequently published FY2025 disclosures and an archived March 2026 Workspace WACC input. It is not an investment decision reconstructed using only information available on 31 December 2025. The model represents Netflix on a standalone basis; it does not forecast an acquisition of WBD, related financing, integration costs or transaction synergies.

The preserved Workspace financial export is dated **4 March 2026**. Its financial input columns run from 2025 backwards to earlier years. The analytical schedules reverse those years into chronological order. The provider's statement-date label of 30 December does not redefine the company's fiscal year-end of 31 December.

## Historical financial and accounting basis

### Reported operating context

The FY2025 annual report shows the following consolidated results. Annual-report values presented in thousands have been divided by 1,000 here. These reported figures provide operating context; they are not substituted indiscriminately for the provider's standardized historical analysis.

| USD millions | 2023 | 2024 | 2025 |
| --- | ---: | ---: | ---: |
| Revenue | 33,723.30 | 39,000.97 | 45,183.04 |
| Operating income | 6,954.00 | 10,417.61 | 13,326.60 |
| Net income | 5,407.99 | 8,711.63 | 10,981.20 |
| Operating cash flow | 7,274.30 | 7,361.36 | 10,149.27 |
| Purchases of property and equipment | 348.55 | 439.54 | 688.22 |
| Operating cash flow less PP&E purchases | 6,925.75 | 6,921.83 | 9,461.05 |

Sources: FY2025 Form 10-K, printed pp.39 and 41. Revenue and operating income increased faster than the expense base between 2023 and 2025. That supports examining operating leverage, but it does not guarantee that the same improvement continues indefinitely.

### Standardized historical series

The workbook retains the original Workspace standardized historical financial series. A difference from GAAP is not, by itself, a transcription error. Two distinctions matter:

- **2020 operating profit:** the provider reports pre-nonrecurring operating profit of approximately 5,686.29 and separately classifies a 1,101.00 COVID-related nonrecurring expense. Deducting that item gives approximately 4,585.29, the GAAP operating-income amount. The model's historical operating series uses the pre-nonrecurring measure.
- **2020–2022 tax and net-income presentation:** the provider places certain tax-related effects in separate after-tax items. For 2022, its net income before those items is 4,122.95; adding the separately presented 368.98 gives approximately 4,491.93, consistent within rounding with reported net income of 4,491.92. Accordingly, that provider subtotal is not labelled final GAAP net income.

The historical operating tax proxy retains the supplied calculation of provider tax expense divided by the schedule's pre-tax income. The numerator can reflect standardized adjustments while pre-tax income reflects the reported amount. It is therefore a proxy, not a claim that every historical rate is a GAAP ETR or a cash tax rate. Forecast tax rates are separately specified analyst assumptions; no historical average is automatically substituted for those paths.

The cash-flow amounts in the first table also differ in definition from model FCFF. Reported operating cash flow includes cash taxes, financing-related interest effects and noncash adjustments, whereas this valuation applies an operating tax proxy to EBIT and estimates reinvestment from changes in NOA.

### Content accounting

Content amortization is included in cost of revenues. Cash payments for content are classified within operating cash flow, while the balance sheet carries net content assets and content liabilities. In 2025, content amortization was approximately **16,422.17**, additions to content assets were **17,096.62**, and the cash-flow statement showed a further **610.84** outflow from changes in content liabilities. PP&E purchases alone are therefore not a measure of all content investment.

The annual report identifies judgment in estimating viewing patterns and amortization. This matters because a revenue-based NOA forecast approximates net investment without explicitly forecasting each content vintage, payment schedule or amortization curve. Sources: FY2025 Form 10-K, pp.28, 38 and 41, and Note 1.

## Revenue forecast

### Regional volume and monetization

For region $r$ and forecast year $t$:

$$
Revenue_{r,t}=Average\ memberships_{r,t}\times ARM_{r,t}\times12
$$

ARM is average monthly revenue per paid membership, expressed as an analyst monetization proxy. It is not the advertised plan price. It can reflect pricing, plan mix, advertising, geography, extra-member revenue and foreign-exchange effects. Because memberships are measured in millions, the identity produces USD millions.

Netflix stopped regularly reporting memberships and ARM during 2025. Consequently, **2025 membership and ARM estimates are not company-disclosed actuals**, even though FY2025 regional and consolidated revenue are actual disclosed figures. Those estimated drivers are not used to overwrite actual 2025 revenue. Scenario changes also leave actual 2025 financial statements fixed.

| Disclosed regional revenue, USD millions | 2025 |
| --- | ---: |
| UCAN | 19,957.15 |
| EMEA | 14,514.65 |
| LATAM | 5,357.52 |
| APAC | 5,353.72 |
| Total | 45,183.04 |

Source: FY2025 Form 10-K, printed p.21. Earlier regional streaming totals can differ from consolidated revenue because of the legacy DVD business, which ended in 2023.

### Base-case inputs

The 2026–2029 membership and ARM assumptions follow the preserved original assumption exhibits, with each model year linked to the matching exhibit year. The 2030 extension repeats each driver's 2028-to-2029 percentage growth:

$$
Driver_{2030}=Driver_{2029}\times\frac{Driver_{2029}}{Driver_{2028}}
$$

This is an additional analyst assumption, not company guidance. It does not introduce an extra margin improvement.

| Average memberships, millions | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| UCAN | 92.70 | 93.90 | 95.00 | 95.80 | 96.61 |
| EMEA | 114.90 | 122.30 | 129.00 | 134.80 | 140.86 |
| LATAM | 60.30 | 63.60 | 66.40 | 68.70 | 71.08 |
| APAC | 68.20 | 74.70 | 81.10 | 87.10 | 93.54 |

| Monthly ARM proxy, USD | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| UCAN | 19.05 | 19.62 | 20.21 | 20.71 | 21.22 |
| EMEA | 11.75 | 12.10 | 12.40 | 12.71 | 13.03 |
| LATAM | 8.14 | 8.31 | 8.47 | 8.64 | 8.81 |
| APAC | 7.39 | 7.50 | 7.61 | 7.73 | 7.85 |

For example, 2026 UCAN revenue is $92.7\times19.05\times12=21,191.22$. The four regional forecasts sum to **49,330.20** in 2026. No separate advertising-revenue overlay is added, which would risk counting monetization growth twice.

These regional driver inputs are estimates constrained by disclosure availability. They are not independently observed future membership counts or management revenue forecasts. FX and advertising effects are embedded in the monetization proxies rather than separately forecast.

## Costs, operating taxes and NOPAT

Netflix does not disclose the cost detail needed for a fully separate profit model for each geographic region. Costs are therefore forecast at the consolidated level:

$$
EBIT_t=Revenue_t-Cost\ of\ revenues_t-Other\ operating\ expenses_t
$$

The provider's original SG&A grouping includes sales and marketing, technology and development, and general and administrative expense. The public model calls this **other operating expenses**, so readers do not mistakenly conclude that technology expense has been omitted.

| Base-case ratio | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| Cost of revenues / revenue | 50.5% | 49.5% | 49.0% | 48.5% | 48.5% |
| Other operating expenses / revenue | 18.8% | 18.6% | 18.4% | 18.2% | 18.2% |
| Forecast operating tax rate | 14.0% | 14.0% | 14.5% | 15.0% | 15.0% |

The cost assumptions imply improved operating leverage through 2029. In 2030 the expense ratios and tax rate remain at 2029 levels. These ratios retain the original active Base path and the archived tax-rate path; they are analyst assumptions informed by history, not exact forecasts supplied by Netflix.

Operating taxes and NOPAT are calculated as:

$$
Operating\ tax_t=EBIT_t\times\tau_t
$$

$$
NOPAT_t=EBIT_t-Operating\ tax_t=EBIT_t(1-\tau_t)
$$

Here $\tau_t$ is the selected forecast operating tax-rate proxy. In the Base case, 2026 EBIT is **15,144.37**, operating tax is **2,120.21**, and NOPAT is **13,024.16**. A tax rate is multiplied by operating profit to obtain a tax amount before being deducted.

Applying a consolidated ETR proxy to operating profit is a simplifying tax allocation. It does not independently forecast jurisdictional taxable income, credits, withholding, deferred taxes or stock-compensation tax benefits. A loss-making stress case would also require examining whether the assumed tax benefit can actually be used. No statutory 21% rate is imposed on this model.

## Investment and FCFF

The original operating-investment framework is retained:

$$
OA_t=Total\ assets_t-Cash\ and\ short\!\text{-}term\ investments_t
$$

$$
OL_t=Total\ liabilities_t-Short\!\text{-}term\ debt_t-Long\!\text{-}term\ debt_t
$$

$$
NOA_t=OA_t-OL_t
$$

Operating leases remain on the operating side: lease-related assets are included in OA and operating lease liabilities in OL. The equity bridge therefore does not deduct those same lease liabilities again as financing debt.

| Base-case investment assumption | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| OA / revenue | 100.0% | 98.0% | 97.0% | 96.0% | 96.0% |
| OL / revenue | 30.0% | 29.0% | 29.0% | 28.0% | 28.0% |
| Implied NOA / revenue | 70.0% | 69.0% | 68.0% | 68.0% | 68.0% |

The 2025 closing NOA anchor is **32,015.96**. Forecast OA and OL equal forecast revenue multiplied by the selected ratios. The model then calculates:

$$
\Delta NOA_t=NOA_t-NOA_{t-1}
$$

$$
FCFF_t=NOPAT_t-\Delta NOA_t
$$

For 2026, closing NOA is **34,531.14**, so net investment is **2,515.18**. FCFF is therefore $13,024.16-2,515.18=10,508.98$.

This is an accrual-based net-investment proxy. It includes more than conventional working capital and can be affected by deferred taxes, FX, content recognition, acquisitions, stock compensation and other noncash balance-sheet changes. It is not an independently reconciled cash capex forecast. Because net investment is already deducted through $\Delta NOA$, depreciation and amortization are not separately added back and capex is not deducted again.

The schedule does not calculate a 2020 FCFF figure without an opening 2019 NOA balance. This avoids treating an unavailable opening investment amount as zero.

### Base-case forecast

| USD millions | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| Revenue | 49,330.20 | 52,930.97 | 56,389.55 | 59,570.12 | 62,955.29 |
| NOPAT | 13,024.16 | 14,521.08 | 15,717.46 | 16,861.32 | 17,819.49 |
| Closing NOA | 34,531.14 | 36,522.37 | 38,344.89 | 40,507.68 | 42,809.59 |
| FCFF | 10,508.98 | 12,529.85 | 13,894.93 | 14,698.53 | 15,517.58 |

## Discounting and terminal value

The retained WACC is **9.8412%**, attributed to an **8 March 2026** LSEG/Refinitiv Workspace snapshot in the preserved valuation notes. This is an archived input, not a newly retrieved current WACC or an observed end-2025 rate. The terminal growth rate remains **2.5%** for Netflix.

The stable year holds 2030 margins, tax rate and investment intensity while growing revenue at $g$:

$$
NOPAT_{2031}=NOPAT_{2030}(1+g)
$$

$$
\Delta NOA_{2031}=g\times NOA_{2030}
$$

$$
FCFF_{2031}=NOPAT_{2030}(1+g)-g\times NOA_{2030}
$$

The Base case gives $17,819.49\times1.025-42,809.59\times0.025=17,194.74$. Stable-year FCFF exceeds 2030 FCFF because growth, and hence the required net investment, falls to the terminal rate. That release of investment demand is a model transition assumption, not an additional unexplained profit increase.

Terminal value sits at **end-2030**:

$$
TV_{2030}=\frac{FCFF_{2031}}{WACC-g},\qquad WACC>g
$$

$$
Operating\ value=\sum_{t=1}^{5}\frac{FCFF_{2025+t}}{(1+WACC)^t}+\frac{TV_{2030}}{(1+WACC)^5}
$$

The 2030 FCFF is included once in the explicit five-year sum; the terminal numerator starts in 2031. The workbook displays an unavailable valuation if WACC is not greater than $g$.

## Equity bridge and result

| USD millions, except per-share value | Base |
| --- | ---: |
| PV of 2026–2030 FCFF | 50,239.98 |
| PV of terminal value | 146,488.07 |
| Operating value | 196,728.05 |
| Add cash and short-term investments | 9,062.36 |
| Less short- and long-term debt | (14,462.84) |
| Less noncontrolling interests in the provider equity bridge | — |
| Common equity value | 191,327.57 |
| Period-end shares, millions | 4,222.16 |
| **Implied value per share, USD** | **45.32** |

$$
Common\ equity\ value=Operating\ value+Financial\ assets-Debt-NCI
$$

$$
Value\ per\ share=\frac{Common\ equity\ value}{Period\!\text{-}end\ shares}
$$

The provider's total equity including minority interests equals parent equity, so the NCI difference is zero. No Paramount NCI amount is carried into Netflix. Debt uses carrying amounts, consistent with the original balance-sheet inputs; market-value debt is not separately estimated.

Cash and short-term investments are excluded from operating assets and added back once. No additional investment value is inserted without separately identifying and excluding the same asset from operations. Book shareholders' equity is not added to the DCF equity value: doing so would count the same business assets again.

Netflix completed a ten-for-one stock split in November 2025. The provider's 4,222.16 million period-end share count is already split-adjusted; it must not be divided or multiplied by ten again. The model uses period-end shares rather than weighted-average EPS shares. It does not separately value outstanding options, forecast future buybacks or assume a fully diluted share count. Stock compensation remains within operating costs, but the effect of changes in future claims is not fully modelled. Source: FY2025 Form 10-K, cover, p.42 and Note 1.

## Scenarios and sensitivity

Base, Bull and Bear use the archived membership, ARM, expense, tax and NOA-intensity assumptions. The active Base cost path follows the original forecast and its matching written exhibit. All 2030 extensions follow the rule above. Changing the operating-case selector recalculates the same forecast build; it does not select a hardcoded valuation.

For the operating comparison below, **WACC remains 9.8412% and terminal growth remains 2.5%** in every case. This separates operating assumptions from discount-rate assumptions. The archived notes' separate examples of Bull/Bear WACC and terminal rates are not automatically combined with these operating scenarios.

| Operating case | Implied value per share |
| --- | ---: |
| Base | $45.32 |
| Bull | $52.84 |
| Bear | $32.46 |

The workbook's WACC and terminal-growth sensitivity uses native Excel two-variable What-If Data Tables linked to the actual model inputs. Base operating assumptions give the following per-share values:

| WACC / terminal growth | 1.5% | 2.0% | 2.5% | 3.0% | 3.5% |
| --- | ---: | ---: | ---: | ---: | ---: |
| 8.8412% | 47.80 | 50.21 | 53.00 | 56.27 | 60.14 |
| 9.3412% | 44.50 | 46.54 | 48.87 | 51.58 | 54.75 |
| 9.8412% | 41.60 | 43.34 | 45.32 | 47.58 | 50.20 |
| 10.3412% | 39.03 | 40.53 | 42.21 | 44.13 | 46.33 |
| 10.8412% | 36.74 | 38.03 | 39.48 | 41.12 | 42.98 |

The terminal value contributes approximately **74.5%** of operating value. The valuation therefore depends substantially on the continuation of operating margins, the assumed tax rate, reinvestment intensity, terminal growth and the required return. The assumptions should be judged together: higher growth requires additional operating investment rather than automatically becoming distributable cash.

## Interpretation and model limits

Netflix's 2023–2025 reported results show expanding operating profitability and stronger operating cash generation. The Base forecast assumes further cost leverage through 2029, then holds expense ratios constant. International membership assumptions contribute more growth than the mature UCAN market, while ARM proxies incorporate pricing and monetization.

The resulting $45.32 estimate is conditional on that operating path and the archived discount rate. It is not sufficient to establish that the shares are mispriced without a dated, consistent market comparison. A low estimate relative to an old market quote would not, by itself, establish that DCF is unsuitable or that the market is wrong.

The main limits are estimated membership/ARM paths after the disclosure change, aggregate expense modelling, standardized historical accounting differences, a simplified operating tax rate, NOA as a proxy for cash reinvestment, fixed period-end shares and the large terminal contribution. A more detailed extension could forecast content cash spending, content liabilities, amortization and tax cash flows separately, but that would be an additional model rather than a silent replacement of the existing method.

## Workbook use

Open **Summary** for the result. **Forecasting and Assumptions** contains the regional build, consolidated profit forecast and NOA/FCFF calculations. **Assumptions** contains active and Base/Bull/Bear driver paths. **DCF cal** shows discounting and the equity bridge. **Sensitivity C4, C5 and C6** control WACC, terminal growth and the operating case respectively; C3 centres the WACC grid without overwriting the active WACC. The four preserved provider input sheets retain the source information, with chronological mirrors for the analytical schedules.

## References

| Input or method | Reference |
| --- | --- |
| 2025 regional revenue and membership/ARM disclosure change | [Netflix FY2025 Form 10-K](https://www.sec.gov/Archives/edgar/data/1065280/000106528026000034/nflx-20251231.htm), printed pp.20–21 |
| Consolidated 2023–2025 revenue, costs, operating income, taxes and net income | FY2025 Form 10-K, p.39 |
| CFO, content additions and amortization, content liabilities and PP&E purchases | FY2025 Form 10-K, p.41; content policy discussion p.28 and Note 1 |
| Cash, investments, assets, liabilities, debt, equity and shares | FY2025 Form 10-K, p.42 and cover |
| Content amortization judgments and stock split | FY2025 Form 10-K, p.38 and Note 1 |
| Historical regional revenue and membership drivers through 2024 | Netflix FY2024 and earlier Forms 10-K, regional revenue tables; [Netflix annual reports](https://ir.netflix.net/financials/annual-reports-and-proxies/default.aspx) |
| 2020–2022 GAAP comparison | Netflix FY2022 Form 10-K, printed p.38, consolidated statements of operations |
| Standardized historical series and financial balance inputs | Preserved LSEG/Refinitiv Workspace export, 4 March 2026, original Netflix financial-input worksheets; USD millions |
| Forecast memberships, ARM, expense, tax and OA/OL ratios | Preserved Netflix valuation notes, Exhibits 1–5, and supplied active Base forecast; analyst assumptions |
| WACC of 9.8412% | Preserved valuation notes attributing NFLX.O TR.WACC to the 8 March 2026 Workspace snapshot; not a current retrieval |
| 2030 extension and stable-year reinvestment | Explicit analyst assumptions and formulas in this report and the workbook |

## Project origin and contribution

Developed from a UC San Diego Financial Statement Analysis group project. Jiarong Xu prepared the financial models and valuation calculations for Netflix, Paramount and Warner Bros. Discovery. The original project also included teammates' written analysis and presentation contributions. This portfolio version presents the revised model, its assumptions and an updated explanation of the valuation.

# Warner Bros. Discovery: Operating Forecast and DCF Valuation

## Purpose and analytical question

This analysis examines whether growth in WBD's Streaming business and the performance of its Studios business can offset declining Global Linear Networks revenue, after allowing for operating costs, taxes, investment and financial claims. WBD provides a leveraged media-transition comparison with Netflix and Paramount.

The model links segment forecasts to adjusted operating profit, estimated stock-based compensation (SBC), net operating assets (NOA) and free cash flow to the firm (FCFF). The purpose is to make the relationship between business assumptions, reinvestment and parent-shareholder value visible.

The default Base estimate is **$3.33 per share**. At the same WACC and terminal growth rate, Bull operating assumptions produce **$5.07** and Bear assumptions produce **$4.03**. The Bear result exceeding Base is a consequence of the retained investment method: lower EBITDA reduces the projected asset base and creates an estimated release of investment. These are conditional operating scenarios, not a ranked price range or probabilities.

## Scope, date and accounting basis

The valuation uses an **end-2025 retrospective baseline**, with five explicit forecast years **2026–2030** and a stable period beginning in **2031**. Cash flows are discounted at year-end. Monetary values are in **USD millions**, subscribers and shares are in **millions**, annual ARPU is in **USD per subscriber**, and per-share values are in USD.

FY2025 values come from actual financial disclosures. They are not a mechanical multiplication of FY2024 by an assumed growth rate. The source Workspace export is dated **4 March 2026**, with descending year columns. Its statement-date label does not replace WBD's 31 December fiscal year-end. The analytical schedules use chronological years.

The analysis uses subsequently published FY2025 information and an archived March 2026 WACC. It is therefore not a reconstruction of an investment decision using only information known at year-end 2025. It is a standalone operating valuation, excluding transaction consideration, separation proceeds, acquisition synergies and subsequent transaction financing. No undated trading price is used to calculate upside or downside.

### The 2022 structural break

The WarnerMedia/Discovery combination created a reporting break in 2022. Segment operating comparisons use the **2022 pro forma combined** columns in the FY2023 annual report, while year-end 2022 assets and liabilities remain actual balance-sheet values. These are explicitly different bases.

The 2022 Streaming revenue of 9,693 is paired with pro forma cost of revenues of 8,188 and SG&A of 3,568, giving adjusted EBITDA of **(2,063)**. Networks pro forma revenue of 23,186 is paired with cost of revenues of 10,154 and SG&A of 2,981, giving adjusted EBITDA of **10,051**. This avoids mixing full-year pro forma revenue with costs for only the actual consolidation period, or using D&A as SG&A.

The displayed 2022 segment revenue totals and eliminations leave a **49** difference to group pro forma revenue of 43,095. It is shown as a derived corporate/other reconciliation amount, not assigned an invented segment margin. The forecast calibration is anchored on 2025; this transition-year residual does not drive future investment assumptions.

### Recent operating context

| USD millions, unless stated | 2023 actual | 2024 actual | 2025 actual |
| --- | ---: | ---: | ---: |
| Streaming revenue | 10,154 | 10,313 | 10,876 |
| Studios revenue | 12,192 | 11,607 | 12,619 |
| Networks revenue | 21,244 | 20,175 | 17,656 |
| Consolidated revenue | 41,321 | 39,321 | 37,296 |
| Group adjusted EBITDA | 10,200 | 9,032 | 8,744 |
| Year-end Streaming subscribers, millions | 97.7 | 116.9 | 131.6 |

Sources: FY2025 Form 10-K, segment discussion and Note 23; FY2023 Form 10-K for the historical transition. Studios totals include its small distribution and advertising revenue lines as well as content and other revenue. Corporate revenue and inter-segment eliminations reconcile segment revenue to the consolidated total.

In 2025, reported operating cash flow was **4,319** and PP&E purchases were **1,231**, giving company-defined free cash flow of **3,088**. That cash-flow definition differs from the model's normalized NOPAT-minus-change-in-NOA approach. Historical NOA changes can include impairments, amortization, FX and other noncash effects and are not presented as reported operating cash flow.

## Segment forecast methods

### Streaming: subscriber volume and monetization

The model retains the subscriber-driven forecast:

$$
AverageSubs_t=\frac{EndingSubs_{t-1}+EndingSubs_t}{2}
$$

$$
SubscriberRevenue_t=AverageSubs_t\times AnnualARPU_t
$$

Annual ARPU is a monetization proxy calibrated to distribution plus advertising revenue. Historical values derived from a beginning/end subscriber average are not identical to a company-calculated KPI based on daily-average subscribers. Because the forecast ARPU is annual, the revenue formula does **not** multiply it by twelve again.

If $q_t$ is non-subscriber revenue as a share of total Streaming revenue:

$$
StreamingRevenue_t=\frac{SubscriberRevenue_t}{1-q_t}
$$

$$
NonSubscriberRevenue_t=StreamingRevenue_t-SubscriberRevenue_t
$$

The denominator matters: a share of total revenue is not simply added as that same percentage of subscriber revenue. Non-subscriber revenue represents content and other revenue; advertising is already included in the subscriber-related monetization measure and is not added twice.

| Streaming Base assumption | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| Ending subscribers, millions | 145 | 155 | 163 | 170 | 175 |
| Annual ARPU proxy, USD | 86 | 88 | 90 | 92 | 94 |
| Non-subscriber revenue share | 3.6% | 3.6% | 3.5% | 3.5% | 3.5% |
| Cost of revenues / revenue, excluding D&A | 67.5% | 67.0% | 66.5% | 66.0% | 65.5% |
| SG&A / revenue | 19.0% | 18.5% | 18.0% | 17.8% | 17.6% |

For example, 2026 average subscribers are $(131.6+145)/2=138.3$. Subscriber-related revenue is $138.3\times86=11,893.80$, and total Streaming revenue is $11,893.80/(1-0.036)=12,337.97$.

The active original Base path is retained where draft exhibits differ, including the 2027 non-subscriber share of 3.6%. Subscribers, monetization and expense assumptions are analyst estimates, not representations that WBD disclosed these exact future outcomes. Separate Streaming SG&A paths were not provided in the linked case framework, so that ratio path is held constant across the operating cases.

### Studios: revenue growth, mix and expense ratios

Studios forecasts use a revenue-growth path because release slates, licensing and games are too irregular for a credible unit-by-unit forecast with the available disclosures:

$$
StudiosRevenue_t=StudiosRevenue_{t-1}(1+g_{studio,t})
$$

Base growth is **2%, 3%, 2%, 2%, 2%**. Content is 93% of total forecast Studios revenue; the remaining 7% groups other, distribution and advertising revenue. The 2025 anchor of **12,619** includes every disclosed revenue category.

Base cost ratios are **60.0%, 59.5%, 59.2%, 59.0%, 58.8%**. SG&A ratios retain the active supplied forecast: **19.5%, 19.0%, 18.5%, 18.2%, 18.0%**. Some separate draft input sheets contain different Base SG&A estimates; they are not automatically substituted for the path actually linked in the valuation. A revenue mix is a descriptive allocation, not a separately forecast margin for each revenue category.

### Global Linear Networks: revenue-line forecasts

Distribution, advertising, content and other revenues are projected separately from their 2025 levels:

$$
Revenue_{line,t}=Revenue_{line,t-1}(1+g_{line,t})
$$

These are composite revenue drivers. The model does not invent separately observed subscriber households, affiliate fees, audience impressions or advertising CPMs.

| Networks Base assumption | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| Distribution growth | −6% | −5% | −4% | −3% | −2% |
| Advertising growth | −8% | −6% | −5% | −4% | −3% |
| Content growth | 0% | 1% | 1% | 1% | 1% |
| Other growth | −5% | −3% | −2% | −2% | −2% |
| Cost / revenue, excluding D&A | 49.0% | 49.5% | 50.0% | 50.5% | 51.0% |
| SG&A / revenue | 16.0% | 16.0% | 16.2% | 16.5% | 16.8% |

For each operating segment:

$$
SegmentAdjustedEBITDA=Revenue-Costs_{ex\ D\&A}-SG\&A
$$

Percentages are first multiplied by revenue to obtain expense amounts. A cost ratio is not deducted directly as though it were a dollar expense. Historical 2025 Networks SG&A is **2,765**, matching the results release and giving segment adjusted EBITDA of **6,412**.

### Corporate and eliminations

Corporate is modelled as a cost centre, with Base adjusted EBITDA of **(1,050), (1,025), (1,000), (975), (925)**. Revenue eliminations are **(3,900), (3,950), (4,000), (4,050), (4,100)**; expense eliminations are **(3,550), (3,630), (3,700), (3,770), (3,840)**.

Both elimination amounts are signed reductions:

$$
EliminationEBITDA=RevenueEliminations-ExpenseEliminations
$$

Thus 2026 elimination EBITDA is $-3,900-(-3,550)=-350$. Consolidated adjusted EBITDA sums the three operating segments, Corporate and elimination EBITDA once. Consolidated revenue sums gross segment revenue, revenue eliminations and the small Corporate revenue amount. Corporate revenue is held at its 2025 level of **2** during the explicit forecast; Corporate profitability is governed by the separately specified cost-centre assumption.

## From adjusted EBITDA to an operating-profit proxy

WBD adjusted EBITDA excludes more than depreciation. The model explicitly estimates recurring SBC rather than treating that excluded expense as costless:

$$
SBC\ ratio=\frac{751}{37,296}=2.0136\%
$$

$$
SBC_t=Revenue_t\times SBC\ ratio
$$

The numerator is the employee SBC adjustment excluded from the 2025 adjusted EBITDA reconciliation, not an assertion that total company-wide SBC disclosed elsewhere is exactly 751. The recurring ratio is a new analyst estimate. Forecast SBC remains an expense in this model; a second mechanical SBC cash-flow add-back is not applied.

$$
D\&A_t=AdjustedEBITDA_t\times d_t
$$

$$
OperatingProfitProxy_t=AdjustedEBITDA_t-D\&A_t-SBC_t
$$

Base D&A ratios retain **48.5%, 47.5%, 46.5%, 45.5%, 44.5%**. The corrected 2025 historical ratio is approximately **65.0%**. Moving immediately to 48.5% therefore assumes a substantial normalization of amortization intensity; it is not a smooth continuation from the actual historical ratio. Content amortization already included in segment costs is not deducted a second time as an extra D&A line.

The proxy is **not GAAP EBIT**. For 2025, adjusted EBITDA of 8,744 less D&A of 5,684 and excluded SBC of 751 gives **2,309**. Further deductions of restructuring 399, transaction/integration costs 166, facility consolidation 10, impairment/amortization of content fair-value step-up 784, capitalized content interest amortization 40, and impairments/dispositions 172 total **1,571**, reconciling to GAAP operating income of **738**. These remaining items are not separately forecast; the valuation assumes normalized operations rather than a full GAAP projection.

### Operating taxes

$$
NOPAT_t=OperatingProfitProxy_t(1-\tau_t)
$$

The original Base normalized tax path is retained at **20%, 20%, 20.5%, 21%, 21%**. Historical loss-year and discrete-item tax rates are shown separately and are not automatically extended. The provider's WACC tax assumption can differ from this operating tax proxy because they serve different calculations. A normalized ETR is not a jurisdiction-by-jurisdiction cash-tax schedule; loss scenarios would require assessing tax-benefit usability.

## Net operating investment and recalibration

The original EBITDA-linked NOA method is retained. The selected 2025 balance-sheet construction is:

$$
OA_{2025}=100,085-4,566-697=94,822
$$

$$
OL_{2025}=62,938-288-32,962-19=29,669
$$

$$
NOA_{2025}=94,822-29,669=65,153
$$

The provider's liability total includes redeemable NCI of 19, which is removed along with financing debt. Equity NCI of 1,228 already sits outside liabilities and is not subtracted from OL again. Finance leases are treated as financing; operating lease assets and liabilities remain in operations.

The correctly calibrated 2025 multiples are $94,822/8,744\approx10.8442x$ for OA and $29,669/8,744\approx3.3931x$ for OL. The forecast preserves the original paths' **relative** changes from their 2025 anchors, rather than retaining absolute multiples calibrated to an overstated EBITDA denominator.

If $u_t$ and $v_t$ are the selected relative-intensity paths, with 2025 equal to 100%:

$$
a_t=a_{2025}u_t,\qquad l_t=l_{2025}v_t
$$

$$
OA_t=a_tAdjustedEBITDA_t,\qquad OL_t=l_tAdjustedEBITDA_t
$$

| Recalibrated Base multiple | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| OA / adjusted EBITDA | 10.72 | 10.59 | 10.52 | 10.46 | 10.39 |
| OL / adjusted EBITDA | 3.42 | 3.45 | 3.46 | 3.47 | 3.49 |

The Assumptions worksheet shows the relative paths directly. This recalibration changes the calibration base while retaining the original method and intended proportional improvements. It is an analyst estimation approach, not evidence that accounting asset balances must move with EBITDA.

$$
NOA_t=OA_t-OL_t,\qquad \Delta NOA_t=NOA_t-NOA_{t-1}
$$

$$
FCFF_t=NOPAT_t-\Delta NOA_t
$$

An increase in NOA is estimated net investment and reduces FCFF; a decrease releases investment. No separate depreciation add-back and capex deduction are appended, which would duplicate the net-investment adjustment. For 2026, Base NOPAT is **2,972.49** and NOA falls from **65,153.00** to **63,464.23**. The estimated release of **1,688.77** raises model FCFF to **4,661.26**.

Goodwill, acquisition-related intangibles, content assets, deferred taxes, FX and impairment make changes in accounting NOA an imperfect cash-investment proxy. In particular, carrying acquisition goodwill forward in EBITDA-linked asset ratios does not establish that organic growth requires proportional future goodwill spending. Historical reconstructions and forecast releases should not be read as actual proceeds from asset disposals. The 2022 FCFF cell is left unavailable without a matching opening balance.

### Base forecast

| USD millions | 2026E | 2027E | 2028E | 2029E | 2030E |
| --- | ---: | ---: | ---: | ---: | ---: |
| Revenue | 37,856.15 | 38,739.36 | 39,472.41 | 40,283.40 | 41,132.50 |
| Adjusted EBITDA | 8,694.94 | 8,920.07 | 9,124.18 | 9,300.70 | 9,542.14 |
| D&A | 4,217.05 | 4,237.03 | 4,242.74 | 4,231.82 | 4,246.25 |
| Estimated recurring SBC | 762.28 | 780.06 | 794.82 | 811.15 | 828.25 |
| NOPAT proxy | 2,972.49 | 3,122.38 | 3,248.86 | 3,363.61 | 3,529.43 |
| Closing NOA | 63,464.23 | 63,699.76 | 64,437.36 | 64,950.10 | 65,883.16 |
| Model FCFF | 4,661.26 | 2,886.85 | 2,511.26 | 2,850.86 | 2,596.37 |

## Terminal value and discounting

The retained WACC is **8.1842%**, attributed to the original **10 March 2026** Workspace snapshot for WBD.O. It is an archived project input, not a new current-market retrieval. Terminal growth remains **2.0%**.

The stable year assumes consolidated revenue, EBITDA, SBC and NOPAT grow at the same $g$, with 2030 margins, tax, D&A ratios and investment intensity held constant. Applying one group-wide stable rate also assumes the legacy network decline eventually stabilizes. This is a terminal closure assumption rather than evidence that the decline ends in 2031.

$$
FCFF_{2031}=NOPAT_{2030}(1+g)-gNOA_{2030}
$$

For Base, $3,529.43\times1.02-65,883.16\times0.02=2,282.36$. This need not equal 2030 FCFF multiplied by 1.02: stable growth changes the required net investment relative to the last explicit year's actual model change.

$$
TV_{2030}=\frac{FCFF_{2031}}{WACC-g},\qquad WACC>g
$$

$$
OperatingValue_{2025}=\sum_{t=1}^{5}\frac{FCFF_{2025+t}}{(1+WACC)^t}+\frac{TV_{2030}}{(1+WACC)^5}
$$

Only forecast FCFF for 2026–2030 enters the explicit sum. The terminal numerator starts in 2031; terminal value sits at end-2030 and is discounted five years. The workbook returns an unavailable valuation when WACC is not greater than $g$.

## Financial claims and parent equity value

| USD millions, except per-share value | Base |
| --- | ---: |
| PV of 2026–2030 FCFF | 12,591.86 |
| PV of terminal value | 24,904.65 |
| Operating value | 37,496.51 |
| Add cash and short-term investments | 4,566.00 |
| Add selected associates/JV investments | 697.00 |
| Less current debt including finance leases | (288.00) |
| Less noncurrent debt including finance leases | (32,962.00) |
| Less equity NCI, book-value proxy | (1,228.00) |
| Less redeemable NCI, book-value proxy | (19.00) |
| Common equity value | 8,262.51 |
| Period-end shares, millions | 2,480.00 |
| **Implied value per share** | **$3.33** |

$$
ParentEquity=OperatingValue+Cash+IncludedInvestments-IncludedDebt-NCI_{equity}-NCI_{redeemable}
$$

$$
Price=\frac{ParentEquity}{PeriodEndShares}
$$

The debt deduction totals **33,250**, comprising reported debt of **32,567** and finance lease liabilities of **683**. The latter consist of 149 current and 534 noncurrent, as disclosed in Note 12. Operating lease liabilities of **3,511** remain in OL and are not deducted again in the equity bridge.

NCI represents outside owners' claims on consolidated businesses. Both the equity and redeemable components are deducted once from consolidated value; they are not added back and are not separately removed from consolidated NOPAT. Book values are estimation proxies rather than independently estimated market values. Parent book equity is not added to the DCF value, which would count the underlying assets again.

The included financial assets are excluded from OA and added back once. The 697 associate/JV balance uses its carrying amount as a proxy. Other financing/operating classifications, including pension and receivables-program obligations, remain as in the original selected balance-sheet definitions; the model does not claim a complete market-value appraisal of every financial claim. In particular, the disclosed revolving receivables program remains within operating liabilities under this classification rather than being reclassified into the debt deduction.

Period-end shares are used instead of weighted-average EPS shares. The recurring SBC expense estimate does not constitute a complete option/RSU valuation or a forecast of future share issuance, buybacks and dilution.

## Scenarios, sensitivities and interpretation

Base, Bull and Bear change the original subscriber, ARPU, segment growth, expense, tax, corporate, elimination and relative-investment paths. All cases retain the corrected 2025 financial anchors and the same approved calibration method. Their quoted values hold **WACC at 8.1842%**, **g at 2.0%** and **SBC/revenue at 2.0136%**.

| Operating case | Default estimate | Excluding future SBC expense, comparison only |
| --- | ---: | ---: |
| Base | $3.33 | $7.28 |
| Bull | $5.07 | $9.57 |
| Bear | $4.03 | $7.19 |

The zero-SBC column illustrates the cost assumption's effect; it is not the selected case or an assertion that future compensation is free. All other definitions and the NOA recalibration are unchanged.

**Why Bear exceeds Base:** Base closes 2030 with NOA of approximately **65,883**, whereas Bear closes with approximately **39,818**. The weaker business path produces lower profit, but the EBITDA-linked investment schedule also assumes substantial asset release during the forecast. Its valuation effect can offset some of the earnings decline. That release is a model assumption, potentially affected by noncash write-downs; it is not proven cash available to shareholders. The scenario names therefore describe business assumptions, not a guaranteed ordering of valuations.

The native Excel WACC/g sensitivity table recalculates terminal reinvestment as well as the discounting denominator:

| WACC / terminal growth | 1.0% | 1.5% | 2.0% | 2.5% | 3.0% |
| --- | ---: | ---: | ---: | ---: | ---: |
| 7.1842% | 6.81 | 6.42 | 5.96 | 5.40 | 4.71 |
| 7.6842% | 5.46 | 5.03 | 4.53 | 3.94 | 3.21 |
| 8.1842% | 4.30 | 3.85 | 3.33 | 2.72 | 2.00 |
| 8.6842% | 3.29 | 2.83 | 2.31 | 1.70 | 0.99 |
| 9.1842% | 2.40 | 1.94 | 1.43 | 0.83 | 0.14 |

**Why higher terminal growth reduces value here:** the Base terminal operating-profit proxy earns only about **5.36%** of the model's closing 2030 NOA, below the **8.1842%** required return. At those fixed ratios, more growth requires investment at a low implied return, reducing value. It would be inconsistent to increase $g$ only in the terminal denominator while leaving investment unchanged. The low implied return may itself reflect the model's use of goodwill and acquisition-related carrying values as investment proxies.

Terminal value represents approximately **66.4%** of Base operating value. Substantial leverage means a modest change in operating value can create a much larger proportional change in the residual equity value. The $3.33 result is conditional on these methods and assumptions; it is not a current sell recommendation or a claim that transaction prices must equal this standalone estimate.

The most useful further development would be a cash-investment schedule separating recurring content cash costs, content liabilities, organic capital spending, working capital, goodwill and noncash purchase-accounting effects. That would be a separately documented extension of the method, not an unannounced replacement of this model.

## Using the workbook

Start on **Summary**. **Forecasting and Assumptions** contains the original segment structure and the operating-to-FCFF build. **Assumptions** contains active and Base/Bull/Bear paths. **Business History** explains actual/pro forma periods, financial claims and the adjusted-profit reconciliation. **DCF Cal** shows the five-year discounting, stable year and equity bridge.

On **Sensitivity**, C4 controls WACC, C5 terminal growth, C6 the operating case and C7 the SBC/revenue estimate. C3 centres the WACC grid without overwriting active C4. Native two-variable Data Tables compare WACC/g, operating cases/WACC and operating cases/SBC. The source sheets retain the provider field names and primary input values, with chronological mirrors for the builds.

## Input references

| Input | Reference |
| --- | --- |
| 2025 revenue, segment operating results and subscriber count | [WBD FY2025 Form 10-K](https://www.sec.gov/Archives/edgar/data/1437107/000143710726000020/wbd-20251231.htm), printed pp.43–47 and Note 23, pp.122–124; supplied Q4/FY2025 results release, pp.2–6 |
| 2022 pro forma segment revenues, costs, SG&A, adjusted EBITDA and D&A | Supplied WBD FY2023 Form 10-K, MD&A segment tables, pp.38–42; consolidated pro forma comparison |
| Adjusted EBITDA, SBC and the GAAP operating-profit reconciliation | FY2025 Form 10-K, Note 23, p.124; SBC total-award disclosures separately in Note 15 |
| 2025 balance sheet and period-end shares | FY2025 Form 10-K, consolidated balance sheet; supplied results release, p.8; preserved Workspace balance-sheet export |
| Finance and operating lease amounts | FY2025 Form 10-K, Note 12, p.96 |
| Reported operating cash flow and PP&E purchases | Q4/FY2025 results release, pp.6 and 9; FY2025 cash-flow statement |
| Provider historical financial series and descending years | Original LSEG/Refinitiv Workspace export, 4 March 2026; preserved source worksheets |
| Forecast segment, tax, D&A and investment paths | Supplied WBD FY2030 assumption workbooks and active original forecast; analyst assumptions |
| WACC 8.1842% | Original project notes attributing WBD.O TR.WACC to 10 March 2026 Workspace snapshot; not a current retrieval |
| SBC/revenue estimate and relative-intensity recalibration | Explicit analyst estimates and formulas described above |

## Project origin and contribution

Developed from a UC San Diego Financial Statement Analysis group project. Jiarong Xu prepared the financial models and valuation calculations for WBD, Netflix and Paramount. The original project also included teammates' written analysis and presentation contributions. This portfolio version presents the revised calculations, assumptions, input references and interpretation.

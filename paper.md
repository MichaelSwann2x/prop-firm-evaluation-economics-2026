# Evaluation Economics and Trader Outcomes in Retail Proprietary Trading Firms: Futures and CFD Structures Compared

## Abstract

This paper examines the economic structure of retail proprietary trading firm evaluation programs in both futures and CFD markets. Using publicly disclosed firm statistics and multi-firm backend datasets covering more than 300,000 accounts, the analysis quantifies pass rates, payout conversion, average payout size relative to account capital, and the revenue contribution of evaluation fees versus profit splits. The study contrasts exchange-cleared futures programs with OTC CFD programs on pricing transparency, drawdown mechanics, and counterparty characteristics. Separate attention is given to the role of evaluation accounts as low-capital simulators for new day traders and to the capacity of experienced traders to extract sustained value under firm risk rules. Results indicate that approximately 14 percent of evaluation purchases reach funded status and approximately 7 percent of all purchasers ever receive a payout, with average payouts near 4 percent of funded account size. Futures programs publish higher per-participant advancement rates when multiple attempts are considered. Firm sustainability rests on high evaluation failure rates that fund infrastructure and the smaller cohort of retained profitable traders. The findings support a hybrid model in which fee income from the majority of participants subsidizes capital allocation to the minority that demonstrate consistent risk adherence.

Keywords: proprietary trading, prop firm, evaluation challenge, futures, CFD, pass rate, payout rate, drawdown rules, retail trading

## 1. Introduction

Retail proprietary trading firms offer evaluation contracts that grant access to simulated capital after a trader meets profit and risk criteria. Successful completion leads to a funded account under which the trader retains a high percentage of subsequent profits. The model has expanded rapidly since 2020, producing a market estimated in the low billions of dollars in annual primary revenue depending on scope of measurement.

Two dominant instrument classes exist. Futures programs route orders against exchange-listed contracts with centralized clearing and a public order book. CFD programs operate on over-the-counter contracts in which the firm or its liquidity provider serves as counterparty. These structural differences affect price formation, overnight costs, leverage availability, and the precise definition of drawdown limits.

This paper compiles and analyzes the most transparent quantitative evidence available as of September 2026. The objectives are to establish baseline conversion rates from evaluation purchase to funded status and to first payout, to compare futures and CFD risk architectures, and to assess the sustainability implications for firms facing both inexperienced participants who treat evaluations as paid simulators and experienced participants who treat them as capital-efficient scaling vehicles.

## 2. Data Sources and Method

Primary quantitative inputs are drawn from two sources. First, FPFX Technology backend data covering more than 300,000 accounts across approximately 100,000 traders and 10 firms, reported exclusively by Finance Magnates. The dataset states that 14 percent of traders obtained a funded account and that approximately 45 percent of those funded accounts produced at least one payout, equating to 7 percent of all traders. Average payout size was reported as 4 percent of plan size. Average spend per trader across challenge attempts was approximately 800 dollars.

Second, Topstep official 2025 disclosures for its Trading Combine program. Of all Combines initiated in 2025, 16.8 percent were successfully completed. Of individual participants who entered one or more Combines, 51.8 percent advanced to funded status on at least one attempt. Of participants who reached the funded level, 33.3 percent received at least one payout. Of Express Funded Account participants, 0.71 percent were called to a Live Funded Account.

Supplementary industry estimates for market size and on-chain payout volumes are taken from Track360 analyses and Payout Junction blockchain-verified settlement data. These sources are used only for context on scale and capital outflow; conversion rates rest on the two primary datasets above.

No original account-level data were collected. All figures are therefore secondary and subject to the sampling frames and definitions of the original reporters. Pass rates are reported both on an attempt basis and on a unique-participant basis where the distinction is available.

## 3. Evaluation Conversion Funnel

The multi-firm FPFX sample provides the broadest available view of end-to-end outcomes. Fourteen percent of evaluation purchases result in a funded account. Of those funded accounts, roughly 45 percent generate a payout. Compounding the two stages yields an overall payout rate of approximately 7 percent of original purchasers. Average payout size of 4 percent of account capital implies that a trader who reaches payout on a 100,000 dollar account receives approximately 4,000 dollars before any profit-split adjustment.

Topstep data illustrate the effect of measuring unique participants rather than individual evaluation starts. The 16.8 percent Combine completion rate is an attempt-level statistic. When the denominator shifts to unique individuals who entered at least one Combine, the advancement rate rises to 51.8 percent. This indicates that persistence across multiple attempts materially improves the probability of eventually reaching funded status. Once funded, the payout conversion of 33.3 percent remains well below 50 percent, confirming that funded status itself is not a guarantee of cash extraction.

Across both datasets the dominant termination event is a drawdown breach rather than failure to reach the profit target. Daily loss limits and maximum drawdown limits account for the majority of account closures in both futures and CFD programs.

## 4. Futures versus CFD Structural Comparison

Futures evaluation programs operate on exchange-listed contracts. Pricing is determined by a central limit order book visible to all participants. Clearing is performed by the exchange clearing house. Drawdown rules in major futures programs commonly use end-of-day trailing or static limits that update only at the close. Data fees are explicit but typically modest or subsidized by the firm. Position sizing is constrained by exchange margin requirements and firm-imposed contract limits.

CFD evaluation programs operate on OTC contracts. The firm or its designated liquidity provider is the counterparty. Price feeds are proprietary to the platform vendor. Spreads can expand materially during high-volatility periods. Overnight financing charges apply. Drawdown tracking is frequently performed on an intraday peak-to-valley basis, which can convert unrealized equity spikes into permanent reductions of the remaining drawdown buffer. Leverage is often higher and more flexible than exchange margin schedules.

Neither architecture eliminates the core risk of breaching firm-imposed loss limits. Futures programs offer greater price transparency and the absence of overnight financing on most contracts. CFD programs offer continuous trading hours and lower minimum notional sizes. The practical consequence for evaluation outcomes is that the precise mathematical definition of the drawdown limit (end-of-day versus intraday peak) changes the set of equity paths that survive.

## 5. New Day Traders and Evaluation Accounts as Simulators

A substantial share of evaluation volume originates from participants with limited or no prior live-account experience. For this cohort the evaluation functions as a paid simulator that also contains an embedded option on capital if the profit and risk criteria are met. The cash outlay for a typical mid-size evaluation is measured in hundreds of dollars, far below the capital required to trade equivalent size on a live brokerage account.

The conversion statistics demonstrate that the majority of these accounts do not progress beyond the evaluation stage. The average expenditure of approximately 800 dollars across multiple attempts indicates that many participants purchase three or more evaluations before either succeeding or exiting. From the firm perspective this cohort generates high-margin fee revenue with no requirement to allocate real capital or to pay profit splits.

From the participant perspective the simulator can still serve a pedagogical function. The hard daily and maximum loss limits force explicit position-sizing decisions that many beginners never confront on small live accounts. The risk is that repeated evaluation purchases become a substitute for systematic skill development rather than a temporary bridge to live capital.

## 6. Experienced Traders and Firm-Level Sustainability

Experienced traders alter the revenue composition. Once a participant demonstrates the ability to meet profit targets while remaining inside drawdown limits on a repeatable basis, the firm begins to earn from the profit-split share rather than solely from evaluation fees. Public statements from operators indicate that a modest number of consistently profitable funded accounts can generate more net revenue over a twelve-month horizon than a large volume of failed evaluations.

Firms have responded with rule layers designed to limit asymmetric extraction. Consistency rules that cap the contribution of any single trading day to total profit in a payout period are now common. High-frequency tick scalping, latency arbitrage, and cross-account hedging are prohibited and monitored. Trailing drawdowns that lock to unrealized peaks reduce the value of large intraday swings that are subsequently given back.

These constraints do not eliminate the ability of skilled traders to extract value. They do raise the minimum process quality required for sustained payout eligibility. Firm sustainability therefore depends on maintaining a sufficient volume of evaluation fee income while retaining enough skilled traders to generate ongoing profit-split revenue. Concentration risk arises if too large a share of skilled capital migrates to a small number of firms or if coordinated multi-account strategies become material relative to total payout capacity. Most operators mitigate this risk through gradual account scaling, identity-level capital ceilings, and continuous rule enforcement.

## 7. Discussion and Implications

The retail prop firm model is a hybrid of skill filtration and fee-based revenue. High evaluation failure rates supply the margin that supports infrastructure, affiliate acquisition costs, and the payouts that flow to the minority of successful participants. Futures programs currently provide the most transparent attempt-level and participant-level statistics. CFD programs dominate instrument breadth and continuous-session access.

For new day traders the evaluation remains a rational low-capital entry point only when treated as deliberate practice with a defined exit criterion. For experienced traders the same instruments can function as a capital-efficient scaling mechanism provided the specific drawdown definition and consistency rules of the chosen firm are incorporated into the trading process.

The data available as of September 2026 do not support claims of either universal exploitation by firms or of easy capital access for the average retail participant. They support a more precise statement: the probability of reaching a payout from a single evaluation purchase is low, the probability rises with persistence, and the economic viability of the firms themselves rests on the continued willingness of the majority cohort to purchase evaluations that do not convert.

## 8. Limitations

All conversion rates are secondary. The FPFX sample covers ten firms and is not a census of the entire industry. Topstep figures apply only to its own program and to the 2025 calendar year. On-chain payout volumes capture only settlements that occur on public blockchains and therefore understate total capital returned to traders. No account-level longitudinal data were available to measure time-to-payout distributions or survival curves after the first withdrawal. Future work would benefit from firm-level disclosures that report both attempt-level and unique-participant rates under identical definitions.

## References

FPFX Technology data as reported by Finance Magnates, 2024. Exclusive analysis of more than 300,000 accounts across 10 firms: 14 percent funded rate, 7 percent overall payout rate, average payout 4 percent of plan size.

Topstep, 2025 Trader Performance Statistics. Official disclosure: 16.8 percent of Trading Combines completed, 51.8 percent of individual participants advanced at least once, 33.3 percent of funded-level participants received a payout, 0.71 percent of Express Funded participants called to Live Funded Account.

Payout Junction, on-chain settlement statistics through September 2026. Aggregate verified payout volume approximately 986 million dollars in the trailing twelve months.

Track360 industry analyses, 2026. Retail prop trading revenue and firm-count estimates.

## Appendix: Summary Conversion Table

Metric | Value | Source
--- | --- | ---
Funded rate (multi-firm) | 14 percent | FPFX / Finance Magnates
Overall payout rate (multi-firm) | 7 percent | FPFX / Finance Magnates
Average payout size | 4 percent of account | FPFX / Finance Magnates
Average spend per trader | ~800 dollars | FPFX / Finance Magnates
Topstep Combine completion (attempt) | 16.8 percent | Topstep 2025
Topstep participant advancement | 51.8 percent | Topstep 2025
Topstep funded-to-payout | 33.3 percent | Topstep 2025
Topstep Express-to-Live | 0.71 percent | Topstep 2025

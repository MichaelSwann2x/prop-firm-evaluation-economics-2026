# Evaluation Economics and Trader Outcomes in Retail Proprietary Trading Firms: Futures, CFD, and Multi-Asset Structures Compared

## Abstract

This paper examines the economic structure of retail proprietary trading firm evaluation programs across futures, CFD, and emerging multi-asset and crypto segments. Using publicly disclosed firm statistics and multi-firm backend datasets covering more than 300,000 accounts, the analysis quantifies pass rates, payout conversion, average payout size relative to account capital, and the revenue contribution of evaluation fees versus profit splits. The study contrasts exchange-cleared futures programs with OTC CFD programs and crypto-native evaluation models on pricing transparency, drawdown mechanics, counterparty characteristics, and regulatory exposure. Separate attention is given to the role of evaluation accounts as low-capital simulators for new day traders, the capacity of experienced traders to extract sustained value under firm risk rules, and the differing perspectives of firm operators, retail participants, and regulatory observers. Results indicate that approximately 14 percent of evaluation purchases reach funded status and approximately 7 percent of all purchasers ever receive a payout, with average payouts near 4 percent of funded account size. Futures programs publish higher per-participant advancement rates when multiple attempts are considered. Firm sustainability rests on high evaluation failure rates that fund infrastructure and the smaller cohort of retained profitable traders. The findings support a hybrid model in which fee income from the majority of participants subsidizes capital allocation to the minority that demonstrate consistent risk adherence. Differing opinions within the industry are presented without resolution: some operators view the high failure rate as necessary risk filtration, while certain trader communities and external analysts characterize the same statistics as evidence of structural extraction.

Keywords: proprietary trading, prop firm, evaluation challenge, futures, CFD, crypto prop, pass rate, payout rate, drawdown rules, retail trading, market structure

## 1. Introduction

Retail proprietary trading firms offer evaluation contracts that grant access to simulated capital after a trader meets profit and risk criteria. Successful completion leads to a funded account under which the trader retains a high percentage of subsequent profits, typically 70 to 90 percent. The model has expanded rapidly since 2020, producing a market estimated in the low billions of dollars in annual primary revenue depending on the scope of measurement used by different research groups.

Three instrument classes now dominate the retail evaluation market. Futures programs route orders against exchange-listed contracts with centralized clearing and a public order book. CFD programs operate on over-the-counter contracts in which the firm or its liquidity provider serves as counterparty. Crypto and multi-asset programs add digital assets, often with continuous trading hours and distinct volatility profiles. These structural differences affect price formation, overnight costs, leverage availability, the precise definition of drawdown limits, and the regulatory constraints that apply in different jurisdictions.

This paper compiles and analyzes the most transparent quantitative evidence available as of September 2026. The objectives are fourfold. First, to establish baseline conversion rates from evaluation purchase to funded status and to first payout. Second, to compare futures, CFD, and crypto risk architectures. Third, to assess the sustainability implications for firms facing both inexperienced participants who treat evaluations as paid simulators and experienced participants who treat them as capital-efficient scaling vehicles. Fourth, to present the main competing interpretations of the observed statistics without privileging any single viewpoint.

The analysis is limited to secondary data. No proprietary account-level files were obtained. Where coverage is incomplete, particularly for crypto-specific conversion rates, the gap is noted rather than filled with unsupported estimates.

## 2. Data Sources and Method

Primary quantitative inputs are drawn from two sources. First, FPFX Technology backend data covering more than 300,000 accounts across approximately 100,000 traders and 10 firms, reported exclusively by Finance Magnates. The dataset states that 14 percent of traders obtained a funded account and that approximately 45 percent of those funded accounts produced at least one payout, equating to 7 percent of all traders. Average payout size was reported as 4 percent of plan size. Average spend per trader across challenge attempts was approximately 800 dollars.

Second, Topstep official 2025 disclosures for its Trading Combine program. Of all Combines initiated in 2025, 16.8 percent were successfully completed. Of individual participants who entered one or more Combines, 51.8 percent advanced to funded status on at least one attempt. Of participants who reached the funded level, 33.3 percent received at least one payout. Of Express Funded Account participants, 0.71 percent were called to a Live Funded Account.

Supplementary industry estimates for market size and on-chain payout volumes are taken from Track360 analyses and Payout Junction blockchain-verified settlement data. These sources are used only for context on scale and capital outflow. Conversion rates rest on the two primary datasets above.

No original account-level data were collected. All figures are therefore secondary and subject to the sampling frames and definitions of the original reporters. Pass rates are reported both on an attempt basis and on a unique-participant basis where the distinction is available. Where data for crypto-specific programs are thinner, the paper notes the limitation rather than extrapolating.

## 3. Evaluation Conversion Funnel

The multi-firm FPFX sample provides the broadest available view of end-to-end outcomes. Fourteen percent of evaluation purchases result in a funded account. Of those funded accounts, roughly 45 percent generate a payout. Compounding the two stages yields an overall payout rate of approximately 7 percent of original purchasers. Average payout size of 4 percent of account capital implies that a trader who reaches payout on a 100,000 dollar account receives approximately 4,000 dollars before any profit-split adjustment.

Topstep data illustrate the effect of measuring unique participants rather than individual evaluation starts. The 16.8 percent Combine completion rate is an attempt-level statistic. When the denominator shifts to unique individuals who entered at least one Combine, the advancement rate rises to 51.8 percent. This indicates that persistence across multiple attempts materially improves the probability of eventually reaching funded status. Once funded, the payout conversion of 33.3 percent remains well below 50 percent, confirming that funded status itself is not a guarantee of cash extraction.

Across both datasets the dominant termination event is a drawdown breach rather than failure to reach the profit target. Daily loss limits and maximum drawdown limits account for the majority of account closures in both futures and CFD programs. Consistency rules that restrict the share of profit attributable to any single trading day further reduce the set of equity paths that qualify for payout even after the profit target has been met.

A simple expected-value illustration follows from these figures. Assume an evaluation fee of 400 dollars, a 14 percent probability of reaching funded status, a subsequent 45 percent probability of receiving a payout, and an average payout of 4,000 dollars on a 100,000 dollar account before the profit split. The unconditional expected payout is approximately 252 dollars (0.14 times 0.45 times 4,000). Net of the evaluation fee the expected value is negative for a single attempt. Persistence across multiple attempts changes the calculation only if the trader’s probability of success rises with experience; the data do not directly measure that learning effect.

## 4. Futures versus CFD Structural Comparison

Futures evaluation programs operate on exchange-listed contracts. Pricing is determined by a central limit order book visible to all participants. Clearing is performed by the exchange clearing house. Drawdown rules in major futures programs commonly use end-of-day trailing or static limits that update only at the close. Data fees are explicit but typically modest or subsidized by the firm. Position sizing is constrained by exchange margin requirements and firm-imposed contract limits. The transparency of the price tape reduces one class of model risk for the trader: the reference price used to mark the simulated account cannot be adjusted by the firm after the fact.

CFD evaluation programs operate on OTC contracts. The firm or its designated liquidity provider is the counterparty. Price feeds are proprietary to the platform vendor. Spreads can expand materially during high-volatility periods. Overnight financing charges apply. Drawdown tracking is frequently performed on an intraday peak-to-valley basis, which can convert unrealized equity spikes into permanent reductions of the remaining drawdown buffer. Leverage is often higher and more flexible than exchange margin schedules. The practical consequence is that an equity path that would survive an end-of-day trailing rule may breach an intraday peak rule even if the trader closes the day with a net profit.

Neither architecture eliminates the core risk of breaching firm-imposed loss limits. Futures programs offer greater price transparency and the absence of overnight financing on most contracts. CFD programs offer continuous trading hours and lower minimum notional sizes. The mathematical definition of the drawdown limit changes the set of surviving equity paths more than the underlying instrument class itself.

## 5. Crypto and Multi-Asset Evaluation Programs

Crypto-native and multi-asset prop programs have grown in parallel with the broader expansion of digital-asset trading. These programs typically offer continuous 24/7 markets, higher realized volatility, and in some cases direct exchange connectivity rather than pure simulation. Drawdown rules often mirror CFD structures, with intraday monitoring and tight daily limits relative to the volatility of the underlying assets.

Data coverage for crypto-specific conversion rates remains thinner than for futures or traditional CFD programs. Public firm disclosures are less standardized, and independent backend datasets of comparable scale to the FPFX sample have not been released for the crypto segment. Available operator statements and community-tracked samples suggest that pass rates sit in a similar 5 to 15 percent range for first attempts, but the higher volatility of crypto instruments increases the frequency of daily loss limit breaches relative to equity-index futures or major FX pairs.

From a structural standpoint, crypto programs introduce two additional considerations. First, the continuous nature of the market removes the natural daily reset that exists in most futures and FX sessions, which can prolong the period during which a trader remains exposed to an open risk limit. Second, the regulatory status of digital-asset products varies sharply by jurisdiction, creating potential discontinuities in the legal treatment of simulated versus live capital and in the enforceability of payout obligations.

## 6. Taxonomy of Failure Modes

The conversion statistics alone do not reveal the proximate causes of account termination. Industry commentary and firm-level disclosures converge on a short list of dominant failure modes.

Daily loss limit breaches constitute the largest single category. A trader who experiences an early adverse move often increases size or frequency in an attempt to recover, converting a manageable intraday deficit into a hard rule violation. Maximum drawdown breaches form the second category; these typically occur later in the evaluation when cumulative equity erosion finally hits the overall limit. Consistency rule violations appear after the profit target has been reached: a single large winning day can render a subsequent payout request ineligible even though the account remains solvent. Time-limit expirations and inactivity rules account for a smaller residual share.

The relative frequency of these modes differs by instrument class. Futures programs with end-of-day trailing rules experience fewer intraday peak breaches but remain exposed to overnight gap risk on contracts that are not flattened at the close. CFD programs with intraday peak tracking convert more equity paths into daily limit violations. Crypto programs, by virtue of continuous trading and higher volatility, elevate the incidence of daily loss breaches relative to both futures and traditional CFD products.

## 7. New Day Traders and Evaluation Accounts as Simulators

A substantial share of evaluation volume originates from participants with limited or no prior live-account experience. For this cohort the evaluation functions as a paid simulator that also contains an embedded option on capital if the profit and risk criteria are met. The cash outlay for a typical mid-size evaluation is measured in hundreds of dollars, far below the capital required to trade equivalent size on a live brokerage account.

The conversion statistics demonstrate that the majority of these accounts do not progress beyond the evaluation stage. The average expenditure of approximately 800 dollars across multiple attempts indicates that many participants purchase three or more evaluations before either succeeding or exiting. From the firm perspective this cohort generates high-margin fee revenue with no requirement to allocate real capital or to pay profit splits.

From the participant perspective the simulator can still serve a pedagogical function. The hard daily and maximum loss limits force explicit position-sizing decisions that many beginners never confront on small live accounts. The risk is that repeated evaluation purchases become a substitute for systematic skill development rather than a temporary bridge to live capital. Industry commentary is divided on whether this educational value outweighs the cumulative cost of repeated failures. Firm operators often emphasize the discipline imposed by the rules. Some independent analysts and trader communities argue that the same rules function primarily as a revenue mechanism once the average number of attempts is taken into account.

## 8. Experienced Traders, Scaling Paths, and Extraction Dynamics

Experienced traders alter the revenue composition. Once a participant demonstrates the ability to meet profit targets while remaining inside drawdown limits on a repeatable basis, the firm begins to earn from the profit-split share rather than solely from evaluation fees. Public statements from operators indicate that a modest number of consistently profitable funded accounts can generate more net revenue over a twelve-month horizon than a large volume of failed evaluations.

Scaling paths formalize the retention of skilled traders. Typical structures begin with a modest funded account and increase capital after successive profit thresholds are met, subject to continued adherence to risk rules. The profit split itself may improve with scale. These mechanisms align the firm’s interest with the trader’s continued success, provided the trader remains inside the risk envelope.

Firms have simultaneously layered rules designed to limit asymmetric extraction. Consistency rules that cap the contribution of any single trading day to total profit in a payout period are now common. High-frequency tick scalping, latency arbitrage, and cross-account hedging are prohibited and monitored. Trailing drawdowns that lock to unrealized peaks reduce the value of large intraday swings that are subsequently given back. Payout buffers that require a minimum retained equity balance further constrain the speed at which capital can be withdrawn.

These constraints do not eliminate the ability of skilled traders to extract value. They do raise the minimum process quality required for sustained payout eligibility. Firm sustainability therefore depends on maintaining a sufficient volume of evaluation fee income while retaining enough skilled traders to generate ongoing profit-split revenue. Concentration risk arises if too large a share of skilled capital migrates to a small number of firms or if coordinated multi-account strategies become material relative to total payout capacity. Most operators mitigate this risk through gradual account scaling, identity-level capital ceilings, and continuous rule enforcement.

## 9. Regulatory and Jurisdictional Variation

Regulatory treatment of retail prop evaluation programs is not uniform. In the United States, futures programs that clear through regulated exchanges operate under established commodity and futures frameworks, although the simulated nature of the evaluation stage creates interpretive questions about when activity crosses into regulated brokerage. CFD programs face greater restrictions for U.S. retail participants following product intervention measures in multiple jurisdictions. Crypto programs encounter the least settled regulatory environment, with classification of digital-asset products and the status of simulated accounts still evolving in major markets.

Offshore jurisdictions have hosted a large share of CFD and multi-asset prop operators. This geographic distribution affects both the legal enforceability of payout claims and the supervisory intensity applied to marketing, capital adequacy, and client-fund segregation. Several high-profile firm closures between 2024 and 2026 illustrated the practical consequences of limited recourse when an operator ceases operations. The frequency of such events has sharpened the distinction, in trader commentary, between firms that maintain transparent banking and payout rails and those that do not.

Disclosure practices also vary. A minority of firms publish cohort-level conversion statistics. Most do not. The absence of standardized, audited funnel metrics leaves participants dependent on secondary sources and firm marketing materials whose incentives are not always aligned with complete transparency.

## 10. Competing Interpretations of the Observed Statistics

The same conversion numbers support multiple interpretations.

One view, frequently expressed by firm operators and some risk-management practitioners, treats the 14 percent funded rate and 7 percent payout rate as evidence of effective risk filtration. Under this interpretation the evaluation is a screening mechanism that protects firm capital from participants who have not yet demonstrated the ability to operate inside defined risk limits. The high failure rate is therefore a feature of the product rather than a defect. The educational value of the simulator is cited as a secondary benefit for the majority who do not progress. Operators who hold this view often emphasize that skilled traders who remain funded generate ongoing profit-split revenue that can exceed the contribution of evaluation fees over multi-year horizons.

A second view, common in segments of the retail trading community and among certain independent analysts, treats the same statistics as evidence of structural extraction. Under this reading the combination of evaluation fees, multiple attempts, tight drawdown rules, and consistency constraints produces a product whose expected value is negative for the average participant and only becomes positive for a small minority of highly disciplined traders. The pedagogical argument is acknowledged but subordinated to the observation that the average participant spends several hundred dollars without reaching a payout. Proponents of this view frequently call for mandatory disclosure of cohort funnels analogous to loss-rate statistics required in other retail leveraged products.

A third perspective, closer to regulatory commentary in some jurisdictions, focuses on disclosure and marketing. The concern is less with the conversion rates themselves than with whether the probability of success and the precise operation of drawdown and consistency rules are communicated with sufficient clarity at the point of purchase. Calls for standardized cohort funnels, similar to loss-rate disclosures required in other retail leveraged products, appear in this literature. Under this frame the policy question is not whether the product should exist but whether the informational prerequisites for informed consent are met.

These three interpretations are not mutually exclusive. A product can simultaneously function as a risk filter, generate substantial fee revenue from non-converting participants, and raise legitimate questions about the adequacy of pre-purchase disclosure. The data presented in this paper do not adjudicate among the views; they supply the quantitative baseline against which each claim can be tested.

## 11. Discussion and Implications

The retail prop firm model is a hybrid of skill filtration and fee-based revenue. High evaluation failure rates supply the margin that supports infrastructure, affiliate acquisition costs, and the payouts that flow to the minority of successful participants. Futures programs currently provide the most transparent attempt-level and participant-level statistics. CFD programs dominate instrument breadth and continuous-session access. Crypto programs add volatility and continuous trading but currently lack conversion data of comparable quality.

For new day traders the evaluation remains a rational low-capital entry point only when treated as deliberate practice with a defined exit criterion. For experienced traders the same instruments can function as a capital-efficient scaling mechanism provided the specific drawdown definition and consistency rules of the chosen firm are incorporated into the trading process.

The data available as of September 2026 do not support claims of either universal exploitation by firms or of easy capital access for the average retail participant. They support a more precise statement: the probability of reaching a payout from a single evaluation purchase is low, the probability rises with persistence, and the economic viability of the firms themselves rests on the continued willingness of the majority cohort to purchase evaluations that do not convert. Whether that arrangement is viewed as efficient risk allocation or as extraction depends on the interpretive frame applied to the same numbers.

## 12. Limitations

All conversion rates are secondary. The FPFX sample covers ten firms and is not a census of the entire industry. Topstep figures apply only to its own program and to the 2025 calendar year. On-chain payout volumes capture only settlements that occur on public blockchains and therefore understate total capital returned to traders. Crypto-specific conversion data remain sparse. No account-level longitudinal data were available to measure time-to-payout distributions or survival curves after the first withdrawal. Future work would benefit from firm-level disclosures that report both attempt-level and unique-participant rates under identical definitions, and from independent datasets that cover crypto and multi-asset programs at a scale comparable to the existing multi-firm samples.

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
Average spend per trader | approximately 800 dollars | FPFX / Finance Magnates
Topstep Combine completion (attempt) | 16.8 percent | Topstep 2025
Topstep participant advancement | 51.8 percent | Topstep 2025
Topstep funded-to-payout | 33.3 percent | Topstep 2025
Topstep Express-to-Live | 0.71 percent | Topstep 2025

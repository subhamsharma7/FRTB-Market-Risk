FRTB Standardised Approach: 

Introduction: In FRTB, there are two ways of calculating the market risk capital charge.
i) Standardised approach (SA) ii) Internal models approach (Advanced)

In SA, we have 7 risk classes, and under each risk class, we have Sensitivities Based Method (SBM), DRC, and RRAO, and under SBM, we calculate delta, vega, and curvature risk charges.
This post is about Delta Risk charge under the EQUITY risk class.

According to "Minimum capital requirements for market risk" Jan 2019 version:
Delta equity spot: the sensitivity is measured by changing the equity spot price by 1 percentage point (ie 0.01 in relative terms) and dividing the resulting change in the market value of the instrument (Vi) by 0.01 (ie 1%) as follows, where:
i) k is a given equity;
ii) EQk is the market value of equity k; and
iii) Vi is the market value of instrument i as a function of the price of equity k.

Important points to remember:
i) Risk factors in the case of the equity risk class are the spot prices.
ii) Sensitivities for each risk class are expressed in the reporting currency of the bank.
iii) Risk factor shocks are given as risk weights for each bucket.
iv) The prescribed risk weights and correlations have been calibrated to the liquidity adjusted time horizon related to each risk class.
v) Sensitivities to the same risk factor must be netted to give a net sensitivity across all instruments in the portfolio to each risk factor.

Info related to  code:
i) Sensitivities are assumed as given 
ii) Bucket number
    a) 1-4 fall under large market cap, emerging market economy
    b) 5-8 fall under large market cap, advanced economy
    c)  9 fall under small market cap, emerging market economy
    d) 10 fall under small market cap, advanced economy
    e) 11 for other sectors
    e) fall under either index bucket bucket number 12 or 13 (non-sector specific)

iii) WSk = Risk weight x net sensitivities
iv) Intrabucket capital charge is calculated for all three intrabucket correlation scenario.# FRTB-Market-Risk

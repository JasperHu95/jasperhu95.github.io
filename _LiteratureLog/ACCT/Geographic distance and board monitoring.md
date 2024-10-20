# Geographic Distance and Board Monitoring: Evidence from the Relocation of Independent Directors

Link: [Geographic distance and board monitoring: Evidence from the relocation of independent directors - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0929119920302467)

## Summary

This paper investigates the effect of geographic distance on the monitoring role of independent directors (IDs) using a sample of 233 relocations of IDs in China. It finds that greater geographic distance between IDs and firm headquarters reduces meeting attendance and dissenting opinions, thus diminishing the effectiveness of board monitoring. The study also demonstrates that geographic distance exacerbates issues such as tunneling activities, earnings management, and lower pay-performance sensitivity for CEOs. However, distant IDs may provide valuable advisory roles, as evidenced by positive market reactions to mergers and acquisitions (M&As) in provinces to which these IDs relocate. The findings suggest that while distant IDs are less effective monitors due to higher information acquisition costs, they may still offer some advisory benefits.

## Introduction
The paper begins by discussing the established literature on geographic distance in corporate finance, which shows that proximity can reduce information asymmetry between firms and stakeholders. Several studies highlight the importance of geographic distance for various aspects of corporate governance, including investor behavior, firm policies, and monitoring effectiveness. The mixed results in the literature regarding the role of distant IDs motivate the study, which leverages exogenous changes in geographic distance resulting from the relocation of IDs to examine how distance affects their monitoring behavior and effectiveness.

## Institutional Background
The independent director (ID) system in China was formally initiated in 2001 with the guidelines issued by the China Securities Regulatory Commission (CSRC). These guidelines mandate that at least one-third of the directors in listed firms be independent, and from 2003, firms are required to disclose the attendance and dissenting opinions of IDs. IDs are appointed for a term of three years, with the possibility of reappointment for a second term. This regulatory framework provides a unique environment to explore how geographic distance impacts the monitoring role of IDs in China’s listed firms.

## Literature Review
The study builds on several streams of research:

1. **Geographic Distance and Information Asymmetry:** 
   Prior studies suggest that geographic proximity reduces the cost of acquiring soft information, thereby decreasing information asymmetry (Ivkovic & Weisbenner, 2005; Massa & Simonov, 2006; Ke et al., 2010). Malloy (2005) and Bae et al. (2008) found that local analysts have an information advantage, which leads to more accurate earnings forecasts.

2. **Geographic Distance and Investor Behavior:** 
   Coval and Moskowitz (1999, 2001) documented that U.S. investment managers prefer to hold stocks of firms headquartered near them due to familiarity and information advantages. Other studies have explored the effects of proximity on firm investment policies, bank lending, and acquisition decisions (Kang & Kim, 2008; Knyazeva & Knyazeva, 2012).

3. **Independent Directors and Monitoring:** 
   Wan (2008) found that while local directors possess more firm-specific information, they may be less effective monitors due to their closer ties with management. Masulis et al. (2012) examined the roles of foreign directors and concluded that they are less effective monitors but better advisors in cross-border acquisitions.

4. **Contradictory Evidence on Geographic Distance and IDs:** 
   The role of geographic distance on the monitoring function of IDs is ambiguous. Alam et al. (2014) observed that distant directors may rely more on public information and less on soft, firm-specific information. This study aims to resolve the mixed evidence by examining the exogenous relocations of IDs.

## Hypotheses
The paper proposes the following hypotheses based on the literature review:

- **H1:** Geographic distance reduces the monitoring effectiveness of IDs due to higher information acquisition costs.
- **H2:** Geographic distance enhances the independence of IDs, potentially making them more effective in challenging management.

## Research Design
The research design centers around a regression analysis to test the effect of geographic distance on the monitoring activities of IDs. The dependent variables include meeting attendance and dissenting opinions, and the main independent variable is geographic distance.

### Regression Equation
The basic regression model is specified as:

$$
\text{Attend}_{fit} (\text{Opinion}_{fit}) = \beta_0 + \beta_1 \times \text{Distance}_{fit} + \sum_j \beta_{2j} \times \text{Control}_{j,fit} + \epsilon_{fit}
$$

Where:
- $\text{Attend}_{fit}$: The percentage of board meetings attended by ID $i$ in year $t$ for firm $f$.
- $\text{Opinion}_{fit}$: The percentage of dissenting opinions expressed by ID $i$ in year $t$ for firm $f$.
- $\text{Distance}_{fit}$: Equals 1 if the geographic distance between ID $i$ and firm $f$ is greater than the average distance over the director’s tenure.
- Control variables include firm size (Lnsize), return on assets (ROA), Tobin's Q, number of board meetings, director compensation, board size, whether the board chairman is also the CEO, ownership concentration, firm leverage, and whether the firm is a state-owned enterprise (SOE).

### Robustness Checks
To ensure the robustness of the results, the authors conduct several additional tests:

1. **Change Model:** 
   This model tests whether changes in geographic distance from year $t-1$ to year $t$ affect the dependent variables. The equation is:
   $$
   \Delta\text{Attend}_{fit} = \beta_0 + \beta_1 \times \Delta\text{Distance}_{fit} + \sum_j \beta_{2j} \times \Delta\text{Control}_{j,fit} + \epsilon_{fit}
   $$
   
   The results confirm that geographic distance negatively affects meeting attendance and dissenting opinions.
   
2. **Difference-in-Differences (DID) Model:** 
   To address the potential endogeneity of relocations, the authors employ a DID approach. The model is:
   $$
   \text{Attend}_{fit} = \beta_0 + \beta_1 \times \text{Distant}_{fit} \times \text{Post}_{t} + \beta_2 \times \text{Distant}_{fit} + \beta_3 \times \text{Post}_{t} + \sum_j \beta_{4j} \times \text{Control}_{j,fit} + \epsilon_{fit}
   $$
   
   Where:
   - $\text{Distant}_{fit}$ equals 1 if the relocation increases the distance between ID $i$ and firm headquarters.
   - $\text{Post}_{t}$ equals 1 for years after the relocation.
   
3. **Placebo Test:** 
   Random relocation years are assigned to each ID to test whether the results are spurious. The placebo test finds no significant results, supporting the validity of the main findings.

4. **Effect of High-Speed Railways:** 
   The presence of high-speed railways ($\text{Rail}_{fit}$) between the ID's location and the firm headquarters is included as an additional variable. The study finds that high-speed railways mitigate the negative effects of geographic distance on meeting attendance.

## Empirical Results

The paper presents the following key empirical findings:

1. **Meeting Attendance:** 
   Distant IDs attend fewer meetings, with a 2% decrease in attendance compared to local IDs. The negative impact of distance is stronger in SOEs.

2. **Dissenting Opinions:** 
   Distant IDs are less likely to express dissenting opinions, suggesting that geographic distance reduces their monitoring effectiveness.

3. **Monitoring Effectiveness:** 
   Firms with distant IDs experience more tunneling activities, higher levels of earnings management, lower pay-performance sensitivity for CEOs, and lower investment efficiency.

4. **Advisory Role:** 
   After relocations, firms are more likely to engage in M&As in provinces where IDs have relocated, with positive market reactions to these deals. This indicates that distant IDs may still provide valuable advisory support.

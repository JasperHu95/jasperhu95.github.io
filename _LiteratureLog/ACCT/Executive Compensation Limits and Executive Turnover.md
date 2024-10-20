# Executive Compensation Limits and Executive Turnover

The link: [Executive Compensation Limits and Executive Turnover | Management Science (informs.org)](https://pubsonline.informs.org/doi/full/10.1287/mnsc.2023.4812)

## Summary
This paper investigates the consequences of limiting executive compensation on voluntary executive turnover and firm value by examining a Chinese government policy that restricts executive pay at central state-owned enterprises (CSOEs). The findings suggest that the policy led to an increase in voluntary executive turnover, particularly among higher-quality executives, resulting in firm value losses. This highlights the critical role of executive compensation in retaining talent and the potential negative impacts of regulatory interventions on firm value.

## Introduction
The introduction discusses the significant debate surrounding executive pay, particularly during economic downturns, which often leads to political pressure for compensation restraints. The study utilizes a Chinese government policy from 2009 that restricted executive pay at CSOEs as a natural experiment to understand the effects of such interventions. The research aims to explore whether restricting executive pay impacts firm value and executive turnover, considering both the managerial power hypothesis and the efficient contracting hypothesis.

## Institutional Background
China's state-owned enterprise (SOE) system has undergone substantial reforms, particularly in the last three decades. The State-Owned Assets Supervision and Administration Commission (SASAC) was established to manage CSOEs, which are among China's largest enterprises. The pay restriction policy, implemented in 2009, aimed to curb perceived excesses in executive compensation at CSOEs by capping salaries and performance-based bonuses. This policy provided a unique setting to study the effects of pay regulation on executive turnover and firm performance.

## Hypothesis
The paper reviews literature on executive compensation, highlighting two main perspectives: the managerial power hypothesis, which suggests executives use their influence to extract excessive pay, and the efficient contracting hypothesis, which argues that executive pay reflects optimal matching of managerial talent to firm needs. The study hypothesizes that limiting executive pay would lead to increased turnover, especially among more talented executives, and potentially harm firm value due to the disruption of optimal executive-firm matching.

### Literature Review

1. **Assortative Matching**: Gabaix and Landier (2008) and Terviö (2008) suggest that executive pay is the outcome of matching managerial talent with firm size, where more talented managers are paired with larger firms.
2. **Incentive Contracts**: Jensen and Meckling (1976) and Holmström (1979) highlight the importance of compensation structures in incentivizing and retaining management.
3. **Managerial Power**: Bebchuk and Fried (2005) argue that CEOs exercise power over corporate boards to secure excessive pay.
4. **Regulatory Intervention**: Cheng et al. (2017) find that high CEO pay reflects a firm's success in securing scarce CEO talent rather than a governance failure.
5. **Other Perspectives**: Murphy (2013) and others discuss the impact of government intervention on executive pay and its unintended consequences.

## Research Design

The research employs a difference-in-difference (DiD) methodology to compare affected CSOEs with non-affected firms. The study examines the impact of the pay restriction policy on executive compensation, turnover, and firm value. Key variables include compensation ($\text{Ln(COMPEN)}$), turnover, and firm value ($\text{TOBIN'S Q}$). Control variables encompass firm size, leverage, growth, return, volatility, board size, and proportion of independent directors.

### Regression Equation

The primary regression equation used is:
$$
Y = \beta_0 + \beta_1 \text{CSOE} + \beta_2 \text{POST} + \beta_3 (\text{CSOE} \times \text{POST}) + \gamma \text{ControlVariables} + \epsilon
$$


- **Dependent Variables**: 
  - $ Y $: $\text{Ln(COMPEN)}$, $\text{TURNOVER}$, $\text{TOBIN'S Q}$
- **Key Independent Variables**:
  - **CSOE**: Dummy variable indicating whether the firm is a central state-owned enterprise.
  - **POST**: Dummy variable indicating the period after the policy implementation (post-2009).
  - **CSOE × POST**: Interaction term to capture the differential effect of the policy on CSOEs.

### Control Variables
- **$\text{Ln(SIZE)}$**: Natural log of total assets.
- **LEVERAGE**: Long-term liabilities divided by total assets.
- **GROWTH**: Yearly sales growth.
- **RETURN**: Annual stock return.
- **VOLATILITY**: Annualized standard deviation of daily stock returns.
- **BOARD**: Board size.
- **INDEPENDENT**: Proportion of independent directors.
- **DUALITY**: Dummy variable indicating if the CEO and chair positions are held by the same person.
- **AGE**: Executive age.
- **FEMALE**: Dummy variable indicating if the executive is female.
- **TENURE**: Executive tenure.

### Robustness Tests
The authors use several methods to ensure the robustness of their findings:
1. **Propensity Score Matching**: To create a matched sample of CSOEs and non-CSOEs with similar attributes before the policy implementation.
2. **Dynamic Effects Model**: To test the parallel trend assumption underlying the DiD research design.
3. **Alternative Turnover Definitions**: Including reclassifying turnovers based on firm performance and examining simultaneous CEO and chair turnovers.
4. **Dropping Cases with Unidentified Next Positions**: To ensure results are not driven by turnovers with unknown subsequent employment.
5. **Matched Sample Analysis**: Comparing matched samples to confirm the impact of the policy on compensation and turnover.

## Empirical Results
1. **Impact on Compensation**: The policy effectively reduced executive compensation at CSOEs by about 6% relative to non-CSOEs.
2. **Pay-for-Performance Sensitivity**: There was a significant reduction in pay-for-performance sensitivity post-policy, indicating weakened incentive structures.
3. **Executive Turnover**: Voluntary executive turnover increased by approximately 20% in proportional terms, particularly among higher-quality executives based on past performance metrics.
4. **Career Outcomes**: Post-policy, a significant proportion of departing executives moved to non-CSOE firms, suggesting the pay restrictions drove them to seek better compensation elsewhere.
5. **Firm Value and Performance**: The policy led to a 4%-7% decrease in firm value for CSOEs relative to non-CSOEs, with more pronounced negative effects associated with the departure of higher-quality executives.

## Conclusion
The study concludes that restricting executive compensation can have unintended negative consequences on executive retention and firm value, emphasizing the need for regulatory caution. The findings support the notion that compensation contracts are crucial for retaining talent and that mandated constraints can distort optimal executive-firm matching, ultimately harming shareholders.


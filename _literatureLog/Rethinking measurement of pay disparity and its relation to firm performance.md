# Rethinking Measurement of Pay Disparity and Its Relation to Firm Performance

Link: [Rethinking Measurement of Pay Disparity and Its Relation to Firm Performance | The Accounting Review | American Accounting Association (aaahq.org)](https://publications.aaahq.org/accounting-review/article-abstract/95/1/343/4347/Rethinking-Measurement-of-Pay-Disparity-and-Its)

## Summary

The paper explores the relationship between firm-level pay disparity and subsequent firm performance. Using detailed compensation data, the author finds that simple CEO-to-mean employee pay ratios (Simple Pay Ratio, SPR) have no significant relationship with firm performance. Instead, Rouen develops new measures to separate pay disparity into explained (driven by economic factors) and unexplained (interpreted as inequitable or unfair) components. The study shows that **unexplained pay disparity** (UPR) is negatively related to firm performance, while **explained pay disparity** (EPR) is positively related.

## Introduction

The study is motivated by two key factors:
1. Growing interest in understanding how firm-level pay disparity impacts firm performance, driven by rising income inequality.
2. The **Securities and Exchange Commission (SEC)** rule requiring firms to disclose the ratio of CEO pay to median employee pay. This disclosure raised concerns about the comparability of pay ratios across firms and industries.

Past research has produced mixed results:
- Studies finding a **positive relationship** between pay disparity and performance often rely on **Tournament Theory**, which suggests that larger pay disparities motivate employees to strive for promotion.
- Studies reporting a **negative relationship** often align with **Equity Theory** or **Rent Extraction Theory**, arguing that perceived unfairness in pay can harm employee morale and reduce productivity.

Rouen argues that these conflicting findings may stem from a failure to separate pay disparity driven by economic factors (income inequality) from disparity perceived as unfair (income inequity).

## Institutional Background

The **SEC's 2015 rule** mandated public firms to disclose their CEO-to-median employee pay ratios. The motivation was to increase transparency regarding pay structures within firms. However, the rule allows firms discretion in identifying the median employee, which complicates comparisons. Rouen asserts that for CEO pay ratios to be informative, they must be adjusted to reflect economic determinants of both CEO and employee pay. Without such adjustments, the raw pay ratio can be misleading.

## Literature Review and Hypothesis Development

The literature review covers several important theories and empirical studies:

1. **Tournament Theory**:
   - Greater pay disparity increases the value of promotion, motivating employees to work harder. Studies such as Lazear and Rosen (1981), Main et al. (1993), and Lee et al. (2008) support this theory, finding a positive relationship between pay disparity and firm performance.

2. **Equity Theory**:
   - Employees compare their compensation with others within the firm. Large pay gaps can cause dissatisfaction, leading to lower performance, as seen in Akerlof and Yellen (1990) and Bloom and Michel (2002).

3. **Rent Extraction Theory**:
   - Top managers may extract rents by paying themselves excessive compensation, harming firm performance. Bebchuk and Fried (2004) show how rent extraction can lead to a negative relationship between pay disparity and performance.

4. **Income Inequity vs. Inequality**:
   - Trevor, Reilly, and Gerhart (2012) suggest that while income inequality (fair pay based on performance) might not harm firm performance, income inequity (unfair pay) can.

Based on these theories, Rouen formulates two hypotheses:
- **H1a**: Unexplained pay disparity (UPR) is negatively related to firm performance.
- **H1b**: Explained pay disparity (EPR) is positively related to firm performance.

## Research Design

Rouen uses detailed compensation data from the **U.S. Bureau of Labor Statistics (BLS)** and the **Execucomp database**. The analysis covers firms in the **S&P 1500 index** between 2006 and 2013. The study creates measures for explained and unexplained pay disparity using regression models that account for firm, industry, and macroeconomic factors.

### Regression Models

1. **Employee Pay Model**:
   The explained employee pay is modeled as follows:

   $$
   \text{Mean Pay}_{i,j,t} = \alpha + \sum \beta_{\text{Est}} \cdot \text{Establishment Factors}_{i,j,t} + \sum \gamma_{\text{Macro}} \cdot \text{Macroeconomic Factors}_{i,j,t} + \sum \delta_{\text{Firm}} \cdot \text{Firm Factors}_{i,t-1} + \text{Industry Fixed Effects} + \text{Year Fixed Effects} + \epsilon 
   $$

   Where:
   - **Mean Pay** is the average employee compensation for firm $i$ at time $t$.
   - **Establishment Factors** include variables related to the workforce composition (e.g., percentage of R&D or technology employees).
   - **Macroeconomic Factors** include regional wages and economic conditions.
   - **Firm Factors** include lagged firm size, profitability, and industry characteristics.

2. **CEO Pay Model**:
   The explained CEO pay is modeled as:

   $$
   \text{CEO Pay}_{i,t} = \alpha + \beta_1 \text{Adj ROA}_{i,t} + \beta_2 \text{ROA Var}_{i,t} + \beta_3 \text{Ret}_{i,t} + \beta_4 \text{Ret Var}_{i,t} + \cdots + \text{Industry Fixed Effects} + \text{Year Fixed Effects} + \epsilon 
   $$

   Where:
   - **Adj ROA** is the adjusted return on assets.
   - **Ret** is the firm’s stock return.
   - **ROA Var** and **Ret Var** capture the volatility in these performance measures.

3. **Pay Disparity Measures**:
   The **Simple Pay Ratio (SPR)** is the CEO-to-mean employee pay ratio. The **Economic Pay Ratio (EPR)** is calculated as:

   $$
   \text{EPR} = \frac{\text{Explained CEO Pay}}{\text{Explained Employee Pay}} 
   $$

   The unexplained pay disparity (UPR) is the difference between the raw pay ratio and the explained ratio:

   $$
   \text{UPR} = \text{SPR} - \text{EPR} 
   $$

4. **Primary Regression**:
   The main regression to examine the relationship between pay disparity and firm performance is:

   $$
   \text{Performance}_{i,t+1} = \alpha + \beta_1 \text{UPR}_{i,t} + \beta_2 \text{EPR}_{i,t} + \gamma X_{i,t} + \epsilon_{i,t}
   $$

   Where **Performance** is the firm’s future performance, measured as industry-adjusted return on net operating assets (Adj RNOA) or stock returns. **X** is a set of control variables including firm size, R&D intensity, and leverage.

### Robustness Checks

To ensure the robustness of the results, Rouen implements several techniques:

1. **Two-Stage Least Squares (2SLS)**:
   This instrumental variable approach addresses potential endogeneity by using industry-adjusted pay ratios as instruments.

2. **Propensity Score Matching (PSM)**:
   Firms with similar characteristics but different pay disparity levels are matched to control for observable factors that could confound the results.

3. **Alternative Performance Measures**:
   The main findings are tested using both **Adj RNOA** and **stock returns** as performance measures to ensure consistency.

4. **Industry-Adjusted Pay Ratios**:
   Following Bebchuk et al. (2011), pay ratios are adjusted by the industry median to account for industry-specific effects.

5. **Hedge Portfolio Analysis**:
   A hedge portfolio that is long on firms with low UPR (high EPR) and short on firms with high UPR (low EPR) is constructed, showing significant abnormal returns.

## Empirical Results

The empirical findings show:
1. **No significant relationship** between the unadjusted Simple Pay Ratio (SPR) and firm performance.
2. **Unexplained pay disparity (UPR)** is negatively associated with firm performance, suggesting that perceived unfair pay can harm company outcomes.
3. **Explained pay disparity (EPR)** has a positive impact on performance, indicating that when pay differences are justified by economic factors, they incentivize employees and enhance firm value.

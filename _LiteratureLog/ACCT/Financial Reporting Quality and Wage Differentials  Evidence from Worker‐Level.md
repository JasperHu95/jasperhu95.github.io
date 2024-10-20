# Financial Reporting Quality and Wage Differentials: Evidence from Worker-Level Data

Link: [Financial Reporting Quality and Wage Differentials: Evidence from Worker‐Level Data - CHOI - 2023 - Journal of Accounting Research - Wiley Online Library](https://onlinelibrary.wiley.com/doi/full/10.1111/1475-679X.12477)

## Summary

The paper investigates how financial reporting quality (FRQ) affects wage differentials using employer-employee matched data from the U.S. Census Bureau. The authors propose that low financial reporting quality introduces risks for workers, who in turn demand compensating wage differentials. The study finds that firms with low FRQ pay wage premiums, consistent with workers bearing higher risks associated with job performance measurement and turnover. The paper employs three distinct empirical methodologies: regressing wages on financial reporting quality, analyzing wage changes for workers switching firms, and a structural approach that isolates financial reporting quality from performance-related volatility. The findings suggest that financial reporting quality significantly influences labor costs, with the wage premiums ranging between 0.9% and 2.8% of annual wages.

## Introduction
The introduction highlights the importance of wages as a substantial portion of firm expenses, explaining that around 21% of wage variation is due to firm-specific characteristics, not worker attributes. The authors suggest that low financial reporting quality creates uncertainties in employee compensation (especially in performance-based pay) and increases job turnover risk. Workers, aware of these risks, demand compensating wage differentials. The introduction sets the stage for investigating whether and how firms with poor financial reporting quality pay wage premiums, through both performance pay risk and turnover risk.

## Institutional Background
The institutional background discusses the use of U.S. Census Bureau data, which contains detailed employer-employee matched data. This data allows the authors to analyze worker characteristics like education, experience, and gender, along with firm-level financial reporting data from Compustat. The use of absolute abnormal accruals as a proxy for financial reporting quality is based on models from prior literature (Jones 1991, Dechow et al. 1995), allowing the authors to capture both intentional and unintentional financial reporting errors.

## Literature Review
The paper draws from a broad literature concerning the relationship between financial reporting quality (FRQ) and economic outcomes, specifically in labor markets. Key references include:

- **Financial Reporting and Wage Differentials**: Biddle et al. (2009) investigated how financial reporting quality impacts firm-level capital investment, suggesting that firms with better reporting have higher investment efficiency. Baik et al. (2019) explored the relation between financial reporting and employee wages, finding significant wage differentials associated with reporting quality.

- **Compensating Wage Differentials**: The work of Rosen (1986) discusses how job characteristics influence wage levels, suggesting that workers receive higher pay for taking on riskier jobs. This concept applies to the risks posed by low FRQ.

- **Performance Measurement Risks**: Studies by Holmstrom (1979) and Banker and Datar (1989) address the implications of noisy performance measures on incentive plans, supporting the idea that low FRQ creates wage premiums due to performance measurement risks.

- **Turnover Risk**: Jacobson et al. (1993) and Couch and Placzek (2010) document that turnover is costly for workers, justifying wage differentials in firms with low FRQ.

## Hypothesis
The paper posits two main hypotheses:
1. **H1**: Firms with low financial reporting quality pay wage premiums due to the increased risks workers face, such as noise in performance measurement or turnover risk.
2. **H2**: The wage premiums due to low financial reporting quality are higher in firms or industries with more performance-based compensation plans.

These hypotheses build on literature that connects financial reporting quality to economic outcomes, particularly in labor markets.

## Research Design

### Regression Model
The main regression model used is:

$$
\text{Ln(Wages}_{i,t}) = \beta_{\text{FRQ}} \times \text{Financial Reporting Quality}_{f(i,t),t-1} + \beta_f \times X_f(i,t) + \beta_i \times X_{i,t} + \theta_i + \psi_{f(i,t)} + \epsilon_{i,t}
$$

Where:
- $ \text{Ln(Wages}_{i,t}) $: Natural logarithm of the wages for worker $ i $ at time $ t $.
- $ \text{Financial Reporting Quality}_{f(i,t),t-1} $: Measure of the firm-level financial reporting quality, lagged by one year.
- $ X_f(i,t) $: Vector of firm-level characteristics (size, Tobin’s Q, leverage, return on assets).
- $ X_{i,t} $: Vector of worker characteristics (age, experience, education).
- $ \theta_i $: Worker fixed effects.
- $ \psi_{f(i,t)} $: Firm fixed effects.
- $ \epsilon_{i,t} $: Error term.

### Variable Definitions
- **Dependent Variable**: Wages (transformed using the natural logarithm).
- **Independent Variable**: Financial Reporting Quality measured through absolute abnormal accruals.
- **Control Variables**: Worker characteristics (age, education, experience) and firm characteristics (size, leverage, return on assets).

### Robustness Checks
The authors implemented several methods to ensure the robustness of their findings:
1. **Alternative Measures of Financial Reporting Quality**: Examined wage differentials using other indicators like total accruals and the standard deviation of accruals.
2. **Two-Stage Procedure**: Estimated time-invariant wage premiums and assessed the association between average financial reporting quality and wage premiums.
3. **Switcher Test**: Analyzed wage changes among workers who switch firms with varying levels of financial reporting quality.
4. **Structural Approach**: Separated the effects of financial reporting quality from performance-related volatility to address potential endogeneity issues.
5. **Event-Based Analysis**: Assessed wage responses to specific accounting shocks, such as the collapse of Arthur Andersen and announcements of internal control weaknesses.

## Empirical Results
The empirical results are summarized as follows:
1. **Wage Premiums for Low FRQ**: Firms with low financial reporting quality pay higher wages. Workers in the lowest quartile of financial reporting quality earn about 27% more than those in the highest quartile.
2. **Channels of Impact**: Wage premiums are larger in firms with higher performance pay sensitivity, indicating risks from performance measurement are a key driver. Additionally, wage premiums correlate with higher turnover risk in firms with low FRQ.
3. **Switching Firms**: Workers switching from low FRQ firms to higher quality firms experience smaller wage increases compared to those switching from high to low FRQ firms.
4. **Robustness**: Results remain consistent across different measures of financial reporting quality and when controlling for potential confounding factors.
# Public Company Audits and City-Specific Labor Characteristics

Link: [Public Company Audits and City‐Specific Labor Characteristics - Beck - 2018 - Contemporary Accounting Research - Wiley Online Library](https://onlinelibrary.wiley.com/doi/full/10.1111/1911-3846.12344)

## Summary

The paper examines how two city-level labor characteristics—average educational attainment and the number of accountants in a city—affect the quality of audits conducted by local audit offices. The study finds that human capital, as proxied by these city-specific characteristics, is positively associated with audit quality. The effect is stronger for non-Big 4 audit firms, which are more reliant on local labor markets compared to Big 4 firms, which benefit from national networks. Companies in cities with higher educational levels and larger accounting labor pools are more likely to select non-Big 4 auditors, and non-Big 4 audit fees increase with higher education levels, reflecting improved audit quality.

## Introduction
The introduction discusses the importance of audit offices in determining audit quality. Previous research has documented significant interoffice variation in audit outcomes, often influenced by factors such as industry expertise and office size. Building on this literature, the authors argue that city-specific labor characteristics, particularly average educational attainment and the number of accountants, also play a critical role in shaping audit quality. These characteristics serve as proxies for human capital, which is expected to positively impact the audit process, especially for non-Big 4 firms, which are more dependent on local labor markets. Big 4 firms, with their national networks, are expected to be less affected by local conditions.

## Institutional Background
The institutional background emphasizes the decentralized nature of the audit industry, where auditors typically operate in close proximity to their clients. Similar to other industries that rely on local labor markets, such as traditional retailers, auditors depend on skilled labor in the cities where their offices are located. Human capital, represented by educational attainment and the availability of skilled professionals (such as accountants), is thus a critical factor in audit quality. Unlike other service industries, the quality of audits hinges on the availability of highly educated and specialized workers in the local labor market.

## Hypothesis (Literature Review and Hypothesis Development)
### Literature Review
1. **Audit Quality and Audit Offices**:
   - Prior research highlights the significant variation in audit outcomes across different audit offices. Francis and Yu (2009), Reichelt and Wang (2010), Choi et al. (2010), and Francis et al. (2013) show that audit offices differ in quality based on industry expertise and office size.
   
2. **Human Capital and City Productivity**:
   - Becker (1962) and other studies in urban economics demonstrate that human capital, in the form of education and skills, is a key driver of productivity. Glaeser and Marmé (2001) and Rosenthal and Strange (2004) provide evidence that higher educational attainment and larger labor pools lead to greater productivity.
   
3. **Geographic Characteristics of the Audit Industry**:
   - Ettredge et al. (2014) emphasize the geographic decentralization of the audit industry, where auditors and clients are often located in the same city, meaning that local labor characteristics directly influence audit quality.
   
4. **Audit Office Flexibility**:
   - Big 4 audit firms have national networks that allow them to move resources across offices to mitigate the effects of local labor shortages, as highlighted by Bills et al. (2016).

### Hypotheses
1. **H1**: Audit quality improves (i.e., abnormal accruals and estimation errors decrease) as city-level human capital increases, with a stronger effect for non-Big 4 offices.
2. **H2**: The accuracy of auditor going-concern opinions increases as city-level human capital improves, with non-Big 4 offices benefiting more significantly.
3. **H3**: Companies are more likely to choose non-Big 4 auditors in cities with higher levels of human capital.
4. **H4**: Audit fees are not expected to show a clear relationship with human capital, though the relationship may differ between Big 4 and non-Big 4 auditors.

## Research Design
### Regression Models and Variable Definitions
1. **Audit Quality Model (H1)**:
   $$
   EQ = \beta_0 + \beta_1 EDUCATION + \beta_2 ACCTLQ + \sum_{j=3}^{6} X_{CITYCONTROLS} + \sum_{k=7}^{23} X_{FIRMCONTROLS} + \text{Industry FEs} + \text{Year FEs} + \epsilon
   $$
   - **Variables**:
     - **EQ**: Measures of audit quality, including abnormal accruals, absolute working capital accruals, and accrual estimation errors.
     - **EDUCATION**: The percentage of a city’s population with at least a Bachelor’s degree.
     - **ACCTLQ**: A labor quotient representing the concentration of accountants in a city relative to the national average.

2. **Going-Concern Accuracy Model (H2)**:
   $$
   Pr(GCERROR = 1) = \alpha_0 + \alpha_1 EDUCATION + \alpha_2 ACCTLQ + \sum_{j=3}^{6} X_{CITYCONTROLS} + \sum_{k=7}^{23} X_{FIRMCONTROLS} + \text{Industry FEs} + \text{Year FEs} + \epsilon
   $$
   - **Variables**:
     - **GCERROR**: An indicator variable equal to 1 if a Type 1 or Type 2 error occurs in the going-concern opinion.

3. **Auditor Choice Model (H3)**:
   $$
   Pr(NONBIG4_{t+1} = 1) = \gamma_0 + \gamma_1 EDUCATION + \gamma_2 ACCTLQ + \sum_{j=3}^{6} X_{CITYCONTROLS} + \sum_{k=7}^{23} X_{FIRMCONTROLS} + \text{Industry FEs} + \text{Year FEs} + \epsilon
   $$
   - **Variables**:
     - **NONBIG4**: An indicator variable equal to 1 if the company is audited by a non-Big 4 firm.

4. **Audit Fees Model (H4)**:
   $$
   LNAUDITFEE = \delta_0 + \delta_1 EDUCATION + \delta_2 ACCTLQ + \sum_{j=3}^{6} X_{CITYCONTROLS} + \sum_{k=7}^{24} X_{FIRMCONTROLS} + \text{Industry FEs} + \text{Year FEs} + \epsilon
   $$
   - **Variables**:
     - **LNAUDITFEE**: The natural log of audit fees.

### Robustness Checks

1. **Propensity Score Matching (PSM)**: To control for selection bias and ensure that client characteristics do not drive the results, propensity score matching is used.

2. **Multilevel Mixed Modeling**: This method accounts for different levels of grouping in the data (e.g., city, firm) to provide more accurate estimates.

3. **Instrumental Variables (IV) Estimation**: The authors use two-stage least squares (2SLS) with lagged human capital variables and the presence of a land-grant college as instruments for educational attainment to control for endogeneity.

4. **Chow Test**: This test is applied to compare the differences between Big 4 and non-Big 4 firms in the regression models, assessing whether the effects of human capital vary across these groups.

### Empirical Results

The empirical results provide evidence in support of the hypotheses:

1. **Audit Quality**: Higher educational attainment in a city is associated with better audit quality, particularly for non-Big 4 firms. Big 4 firms also benefit, but to a lesser extent.
2. **Going-Concern Accuracy**: Non-Big 4 auditors exhibit greater accuracy in going-concern opinions in cities with higher education levels, while Big 4 firms show little change.
3. **Auditor Choice**: Companies in cities with higher educational levels and a larger pool of accountants are more likely to choose non-Big 4 auditors.
4. **Audit Fees**: Non-Big 4 audit fees increase with higher education levels, reflecting higher audit quality, but fees decrease when the supply of accountants increases, indicating some offsetting effects.
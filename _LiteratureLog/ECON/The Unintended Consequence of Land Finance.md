# The Unintended Consequence of Land Finance: Evidence from Corporate Tax Avoidance



The link of paper: [The Unintended Consequence of Land Finance: Evidence from Corporate Tax Avoidance | Management Science (informs.org)](https://pubsonline.informs.org/doi/full/10.1287/mnsc.2021.4191)

## Summary

This paper investigates the impact of reduced land transfer revenue on corporate tax avoidance in China. The study finds that a decrease in land transfer revenue leads local governments to strengthen tax enforcement, thereby reducing corporate tax avoidance. This effect is more pronounced in cities with higher land finance dependence, greater government intervention, and stronger political promotion incentives. Additionally, this effect is moderated for politically connected firms. The study also explains this mechanism through the increased intensity of tax enforcement.

## Introduction
Local governments in many developing countries, including China, typically rely on land finance to support infrastructure construction and promote local economic growth. However, heavy reliance on land finance is risky due to the high volatility of land markets. This study explores the impact of land finance on corporate tax behavior, particularly tax avoidance. While the determinants of corporate tax avoidance have been widely studied, the role of local governments in corporate taxation has been less examined. This study fills this gap by analyzing the relationship between local government land finance and corporate tax behavior.

## Institutional Background
Land finance refers to local governments obtaining fiscal revenue through the sale of land use rights, land leasing, and land collateral borrowing. Since 1998, Chinese local governments have been granted statutory rights to sell land and retain all revenue. This has led local governments to eagerly tap this new source of financing to fill their coffers. However, the volatility of land markets and limited land supply make land finance an unstable and unsustainable revenue source. When land transfer revenue decreases significantly, local governments face serious fiscal pressure and must strengthen tax enforcement to generate revenue from other sources.

## Literature Review and Hypothesis

### Literature Review
This study builds on a rich body of literature, covering several areas:

1. **Determinants of Corporate Tax Avoidance**:
   - **Shareholders and Creditors**: Studies by Chen et al. (2010) and Hasan et al. (2014) find that the interests of shareholders and creditors influence corporate tax avoidance.
   - **Executives**: Armstrong et al. (2012) and Koester et al. (2016) find that executive incentives and characteristics also affect corporate tax avoidance.
   - **Financial Analysts and Auditors**: Chen and Lin (2017) and McGuire et al. (2012) examine the roles of financial analysts and auditors in corporate tax avoidance.
   - **Labor and Customers**: Chyz et al. (2013) and Cen et al. (2017) analyze the impact of labor and customers on corporate tax avoidance.
   - **Public Opinion and Political Environment**: Mills et al. (2013) and Baloria and Klassen (2017) explore how public opinion and the political environment affect corporate tax avoidance behavior.

2. **Role of Local Governments**:
   - **Fiscal Conditions of Local Governments**: Esteller-Moré (2005) finds that local governments have lower incentives to collect taxes and devote less effort to it when they receive unconditional grants from the central government.
   - **Regional Decentralization in China**: Maskin et al. (2000) and Li and Zhou (2005) study China's regional decentralization system, finding that local officials focus on measurable economic development indicators to enhance their promotion prospects, affecting their tax policies.

3. **Impact of Land Finance**:
   - **Effects of Land Market on Corporate Behavior**: Gan (2007) and Chaney et al. (2012) find that changes in the land market affect corporate investment and market valuation.
   - **Characteristics of China's Land Market**: Wu et al. (2015) and Gu et al. (2019) explore the features of China's land market and its impact on corporate behavior.

### Hypothesis
Based on the literature, the study proposes the following hypotheses:
- Hypothesis 1: In regions where land transfer revenue decreases, local governments will strengthen tax enforcement, leading to reduced corporate tax avoidance.
- Hypothesis 2: This effect will be more pronounced in cities with higher land finance dependence, greater government intervention, and stronger political promotion incentives.
- Hypothesis 3: Politically connected firms will be less affected by the decrease in land transfer revenue.

## Research Design
### Data Sources
The study uses annual survey data of industrial firms from 1999 to 2012 provided by the **National Bureau of Statistics (NBS)** of China, covering all industrial firms with annual sales exceeding RMB 5 million. These firms account for more than 85% of China's industrial value-added. Additionally, city-level data comes from the China City Statistics Yearbook and China Land and Resources Statistics Yearbook, while personal information on government officials is obtained from the China Stock Market and Accounting Research (CSMAR) database.

### Variables

- **Dependent Variable**:
  - **Tax Avoidance (RPRO)**: Measured by the sensitivity of the reported accounting profit to the imputed profit based on the national income accounting system.
    - Reported Accounting Profit (RPRO): The pre-tax accounting profit of firms, calculated from financial statements. For unlisted firms, this data is usually not publicly available, so NBS data is used.
    - Imputed Profit (PRO): Calculated based on the national income accounting system, using the formula: $$ \text{PRO} = Y - \text{MED} - \text{FC} - \text{WAGE} - \text{CURRD} - \text{VAT} $$
    where $ Y $ is gross output, $ \text{MED} $ is intermediate inputs, $ \text{FC} $ is financial charges, $ \text{WAGE} $ is total wage bill, $ \text{CURRD} $ is current depreciation, and $ \text{VAT} $ is value-added tax. The correlation between reported accounting profit and imputed profit is used to measure tax avoidance; a stronger correlation indicates lower tax avoidance.
- **Independent Variable**:
  - **Land Transfer Revenue Loss ($\Delta$LANDloss)**: Defined as the year-over-year change in the ratio of local government land transfer revenue to local GDP.
- **Control Variables**:
  - **Financial Charges (FINANCE)**: The ratio of a firm's financial charges to its total assets, serving as a proxy for access to credit markets.
  - **Firm Size (SIZE)**: The natural logarithm of the number of employees.
  - **Sales Revenue Ratio (RSALE)**: The ratio of a firm's sales to its gross output.
  - **State-Owned Enterprise (SOE)**: A binary variable equal to 1 if the firm is state-owned, and 0 otherwise.

The regression model is as follows:
$$
\text{RPRO}_{i,t} = (\beta_0 + \beta_1 \times \Delta\text{LANDloss} + \beta_2 \times \text{FINANCE} + \beta_3 \times \text{SIZE} + \beta_4 \times \text{RSALE} + \beta_5 \times \text{SOE} + \lambda_{i,t}) \times \text{PRO}_{i,t} + \alpha_1 \times \Delta\text{LANDloss} + \alpha_2 \times \text{FINANCE} + \alpha_3 \times \text{SIZE} + \alpha_4 \times \text{RSALE} + \alpha_5 \times \text{SOE} + \lambda_{i,t} + \mu_i + \epsilon_{i,t}
$$
where $\Delta\text{LANDloss}$ represents the change in land transfer revenue, $\lambda_{i,t}$ includes industry and city fixed effects, and $\mu_i$ represents year fixed effects.

### Robustness Checks

To ensure the robustness of the results, the study employs various methods:

1. **Difference-in-Differences (DID) Analysis**:
   - **Exogenous Shocks**: Uses the **2006 North Korean nuclear test** and the **2011 Fukushima nuclear accident** as exogenous shocks to analyze their impact on corporate tax avoidance.
   - **Model Specification**: Conducts DID analysis by comparing firms in affected cities with those in unaffected cities, verifying the significant impact of land transfer revenue reduction on corporate tax avoidance.

2. **Alternative Variables and Samples**:
   - Uses alternative measures of land transfer revenue loss (e.g., $\Delta$LAND1loss and $\Delta$LAND2loss) to verify the robustness of the results.
   - Excludes specific cities (e.g., Beijing, Shanghai, Tianjin, and Chongqing) and reanalyzes the data to ensure the generalizability of the results.

3. **Control for Potential Omitted Variables**:
   - Uses budget pressure variables (e.g., local government budget deficits) as control variables to rule out the impact of local government budget pressure on land transfer revenue and tax enforcement.
   - Employs propensity score matching to ensure the comparability of treatment and control groups at both city and firm levels.

4. **Hypothesis Testing**:
   - Tests the parallel trend assumption to ensure that treatment and control groups have similar trends before the exogenous shocks, verifying the validity of the DID analysis.
   - Conducts placebo tests by randomly selecting pseudo-treatment and pseudo-control groups to verify the non-randomness of the observed results.

## Empirical Results

1. **Relationship between Land Transfer Revenue Reduction and Corporate Tax Avoidance**: Empirical results show that a reduction in land transfer revenue significantly decreases corporate tax avoidance. This result is robust across various model specifications and alternative samples.
2. **Mechanism of Tax Enforcement Intensity**: Further analysis finds that the reduction in land transfer revenue leads to decreased corporate tax avoidance through strengthened tax enforcement. Increased tax audits and the number of tax officers support this mechanism.
3. **Cross-Sectional Analysis**: The impact of land transfer revenue reduction on corporate tax avoidance is more pronounced in cities with higher land finance dependence, greater government intervention, and stronger political promotion incentives. Politically connected firms are less affected.

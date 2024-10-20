# Competence vs. Independence: Auditors' Connections with Members of Their Clients' Business Community

Link: [Competence vs. Independence: Auditors' connections with members of their clients’ business community - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165410124000326)

## Summary

This paper investigates how auditors' social connections within their clients' business community impact audit quality. Prior research shows that auditors' social ties with clients' management harm audit quality by compromising independence. However, this study focuses on whether connections within a client’s business community could improve auditor competency and lead to better audit quality, particularly in China’s relationship-based economy. Using data from Chinese listed companies, the study finds that auditors with strong business and government connections deliver higher-quality audits, as indicated by fewer financial irregularities. Robustness tests reveal that these connections do not facilitate concealment of financial irregularities, and the benefits of enhanced auditor competency outweigh the potential risks to independence.

## Introduction

The introduction reviews prior literature on social ties between auditors and their clients' executives, showing that these ties often reduce audit quality by impairing independence (Guan et al., 2016; He et al., 2017). However, the paper suggests that auditors' connections within a client’s broader business community could provide them with valuable information, potentially improving their competency. This is particularly relevant in countries like China, where companies rely heavily on relationship-based contracting (Rajan and Zingales, 1998; Wong, 2016). The study explores whether these connections help auditors gain deeper insights into their clients' businesses, thereby improving audit quality. The authors also acknowledge the potential risk that such ties could threaten auditor independence, leading to a trade-off between competency and independence.

## Literature Review and Hypothesis Development

The literature review focuses on how auditors' social ties affect audit quality. Previous research, such as **Guan et al. (2016)** and **He et al. (2017)**, shows that auditors’ close ties with their clients’ management often impair their independence, leading to lower audit quality. This study extends the literature by focusing on social ties within the client’s business community rather than just the client’s management. **DeFond and Zhang (2014)** suggest that access to more information could enhance an auditor’s competency, while **Gao and Huang (2016)** argue that social connections might compromise independence.

In relationship-based economies like China, social networks are crucial for enforcing contracts (Allen et al., 2005). **Rajan and Zingales (1998)** highlight that social relationships in such economies help mitigate information asymmetry, and **Wong (2016)** emphasizes the role of local knowledge in understanding business operations. These findings lead to the hypothesis that auditors with strong ties in the client’s business community will improve audit quality by gaining better insights into their clients’ operations, despite the potential threat to independence.

The main hypothesis is:
- **H1**: Auditors with stronger social networks within their clients' business communities provide higher-quality audits.

## Research Design

### Data Source

The study uses data from Chinese listed companies spanning 2005 to 2018. China offers a unique setting for this analysis because of its detailed auditor identity and social network data, along with its relationship-based economy where social connections are highly relevant for business transactions.

### Variable Definitions

- **Dependent Variable**: The primary measure of audit quality is the incidence of financial irregularities ($\text{FinIrreg}$), which equals 1 if a company's financial statements contain material errors or are sanctioned for financial misrepresentation by the CSRC.
  
- **Independent Variable**: The main independent variable is the strength of the auditor's social networks within the client’s province ($\text{Network}$). It is computed as the average of the auditor’s business connections ($\text{Network(Bus)}$) and government connections ($\text{Network(Gov)}$), where both are binary variables indicating whether the auditor has above-median connections in each category.

- **Control Variables**: The analysis includes controls such as auditor industry specialization, company size ($\log(\text{Size})$), state ownership (SOE), leverage (Leverage), accounts receivable ratio (AR), and fixed effects for province, industry, and year.

### Regression Model

The hypothesis is tested using a linear probability model where financial irregularities ($\text{FinIrreg}$) are regressed on the auditors' social networks and control variables. The regression equation is as follows:

$$
\text{FinIrreg}_{it} = \alpha + \beta_1 \text{Network}_{it} + \gamma \text{Controls}_{it} + \text{Fixed Effects} + \epsilon_{it}
$$

Where:
- $\text{FinIrreg}_{it}$ is a binary variable for financial irregularities,
- $\text{Network}_{it}$ represents the auditor’s local business and government ties,
- $\text{Controls}_{it}$ includes firm-level and auditor-level control variables.

## Empirical Results

### Main Findings

1. **Effect on Financial Irregularities**: Auditors with strong local connections reduce the probability of financial irregularities by 2.1 percentage points, representing a significant improvement in audit quality.
2. **Effect on Other Audit Quality Measures**:
   - Auditors with strong social networks are more likely to issue going-concern opinions (GCs), which indicates greater auditor independence.
   - Their clients experience lower stock price crash risk, implying that auditors help prevent the accumulation of undisclosed bad news.
   - Earnings response coefficients (ERCs) are higher for clients audited by connected auditors, suggesting the market perceives these clients' earnings as more credible.

## Robustness Checks

The authors conducted several robustness tests to ensure the validity of their results:

1. **Alternative Proxies for Audit Quality**: In addition to financial irregularities, the authors used going-concern opinions (GCs), stock price crash risk (Crash Risk), and earnings response coefficients (ERCs) as alternative audit quality measures. These proxies showed consistent results, reinforcing the conclusion that strong auditor connections improve audit quality.

2. **Placebo Tests**: The authors conducted placebo tests by analyzing auditors’ connections in neighboring provinces ($\text{Network(NeighborProv)}$) and outside the client’s province ($\text{Network(OutProv)}$). These placebo variables did not have a significant impact on financial irregularities, confirming that the positive effect on audit quality is specific to auditors' local connections within the client’s business community.

3. **Fixed-Effects Models**: The study includes multiple fixed-effects models to control for province, year, and industry-specific factors. The results remained robust across different specifications, further validating the conclusions.

4. **Sub-Sample Analysis**: The effects of auditors' local connections were stronger in provinces where relationship-based contracting is more prevalent, suggesting that these ties are more valuable in settings where formal contracts are less relied upon.

## Conclusion

This study contributes to the literature by highlighting the positive role of auditors' social networks within their clients' business communities in improving audit quality, especially in relational economies like China. The findings suggest that while social connections could potentially impair independence, the benefits of enhanced competency outweigh these risks. The study encourages future research to explore the balance between auditor competency and independence in other contexts, particularly in emerging economies where social networks play a significant role in business operations.
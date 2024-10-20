# The Geographic Decentralization of Audit Firms and Audit Quality

Link: [The geographic decentralization of audit firms and audit quality - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165410119300278)

## Summary

This paper examines how the **geographic decentralization** of audit firms impacts **audit quality**, focusing on Big 4 accounting firms. Decentralization increases the proximity between auditors and their clients, improving local knowledge and audit efficiency. However, it also reduces proximity between auditors within the same firm, potentially limiting knowledge sharing, monitoring, and resource allocation. The authors demonstrate that small audit offices benefit from being geographically close to large offices within the same firm, as proximity enhances **audit quality**. This effect is driven by improved **monitoring**, **knowledge sharing**, and, to a lesser extent, **resource sharing**. The research is supported by econometric models that reveal a strong relationship between proximity and audit outcomes.

## Introduction
The paper begins by highlighting the decentralized nature of Big 4 accounting firms. Each practice office operates with significant autonomy, which allows auditors to develop in-depth knowledge of local clients. However, this structure may create **frictions** between offices, limiting interactions such as **knowledge transfer** and **monitoring**. The goal of the study is to assess how proximity between large and small offices affects audit quality, building on prior literature that has found large offices generally provide **higher-quality audits**.

## Institutional Background
The Big 4 audit firms operate as geographically decentralized networks of offices, with individual offices managing client engagements. This structure benefits auditors through enhanced **local market knowledge** and **client proximity**, allowing for more effective audits. However, this comes at the cost of reducing interaction between auditors across different offices, which can hinder **internal knowledge sharing** and **monitoring** processes. **Regional Managing Partners (RMPs)** play a key role in monitoring offices, particularly in larger offices, to maintain consistent audit quality across regions.

## Hypotheses and Literature Review
### Office Size and Audit Quality
- **Francis and Yu (2009)**: Larger audit offices are associated with lower client abnormal accruals and higher likelihoods of issuing going concern opinions.
- **Francis et al. (2013)**: Larger offices exhibit lower restatement rates, indicating higher audit quality.
- **Choi et al. (2010)**: Office size correlates positively with audit quality, as measured by abnormal accruals and audit fees.
  

These studies establish that office size is a key determinant of audit quality. The paper seeks to extend this research by exploring how audit quality "spills over" from large offices to nearby small offices.

### Geographic Proximity and Monitoring
- **Coval and Moskowitz (1999)**: Geographic proximity improves monitoring, with closer distance facilitating better oversight.
- **Malloy (2005)**: Analysts provide more accurate earnings forecasts for geographically proximate firms.
- **Kedia and Rajgopal (2011)**: The SEC is more likely to investigate companies located near their offices.
  
### Hypotheses
- **H1**: Audit quality in small offices improves when they are closer to a large office within the same firm.
- **H2a**: Proximity's impact on audit quality is stronger when a **Regional Managing Partner (RMP)** is located in the large office, enhancing monitoring.
- **H2b**: Proximity has a greater impact when the large office possesses **industry-specific knowledge** relevant to the small office.
- **H2c**: Proximity mitigates **capacity constraints** for small offices experiencing rapid growth.

## Research Design
### Data and Sample
The sample consists of **firm-year observations** from **Big 4 audit firms** between 2004 and 2015, focusing on non-financial U.S. firms. The authors use **Audit Analytics** and **Compustat** data to assess audit quality and calculate geographic distances between audit offices.

### Regression Model
The core regression model is designed to test whether geographic proximity between offices improves audit quality:

$$ \text{AuditQuality}_{ijt} = \alpha + \beta_1 \times \text{Proximity (Same Firm)}_{jt} + \mathbf{X}'\gamma + \epsilon_{ijt} $$

Where:
- **AuditQuality** is measured by:
  - **Abnormal Accruals**: The absolute value of discretionary accruals.
  - **Restatement**: A dummy variable indicating whether the client restated financial statements.
- **Proximity (Same Firm)**: The distance between the small office and the nearest large office within the same audit firm.
- **Control Variables** include:
  - **Ln Client Size**: Logarithm of client size.
  - **Debt**: Client leverage.
  - **Revenue Growth**: Client's revenue growth rate.
  - **Tenure**: Length of auditor-client relationship.

### Robustness Checks
To ensure the results are robust, the authors implement several tests:
- **Placebo Test**: Introducing the variable **Proximity (Any Firm)**, measuring the distance to any large audit office regardless of firm affiliation, to rule out the possibility that proximity to urban centers is driving results.
- **Fixed Effects Models**: Controlling for **industry** and **year** effects.
- **Difference-in-Differences Analysis**: Used to evaluate changes in audit quality following RMP consolidations in Big 4 firms, providing further evidence of the monitoring effect.

## Empirical Results
The empirical results confirm the hypotheses:
1. **Proximity to Large Offices Improves Audit Quality**:
   - Small offices located closer to large offices show lower **abnormal accruals** and fewer **restatements**.
   - This effect is strongest when the small office is within 185 kilometers of a large office.
   
2. **Monitoring by RMPs**:
   - The presence of an **RMP** in the large office strengthens the positive impact of proximity on audit quality. This emphasizes the importance of monitoring roles in geographically dispersed firms.

3. **Knowledge Sharing**:
   - Proximity's effect is stronger when the large office has relevant **industry-specific experience**, facilitating better knowledge transfer.

4. **Capacity Constraints**:
   - The data does not support the hypothesis that proximity helps alleviate **capacity constraints** in small offices. Resource sharing seems to be a less significant factor compared to monitoring and knowledge transfer.

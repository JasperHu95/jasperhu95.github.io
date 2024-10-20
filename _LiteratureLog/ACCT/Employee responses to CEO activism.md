# Employee Responses to CEO Activism

Link: [Employee responses to CEO activism - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165410124000314)

## Summary

This paper investigates the impact of CEO activism, where CEOs publicly engage in socio-political issues such as climate change, LGBT rights, and diversity. The study finds that employee satisfaction increases when the activism aligns with employees' ideologies. Furthermore, aligned CEO activism attracts ideologically similar and productive inventors, leading to improved firm-level innovation. These outcomes suggest that CEO activism can positively influence organizational culture, productivity, and firm value when aligned with the employees' beliefs.

## Introduction
CEO activism refers to the growing trend of corporate leaders taking public stances on socio-political issues, which has become increasingly common in recent years (Chatterji and Toffel, 2019; Larcker et al., 2018). While previous studies have largely focused on investor and customer reactions to these public stances, little attention has been paid to the responses of employees. Given the importance of human capital to firm performance, this paper aims to fill this gap by providing large-scale empirical evidence on employee responses to CEO activism.

## Institutional Background
The paper draws on a dataset of CEO activism events from S&P 500 companies between 2011 and 2019. These events were collected from news articles and Twitter posts, with the majority of activism stances being of a liberal nature. The study also utilizes employee satisfaction data from Glassdoor to measure how activism affects employees' perceptions of their firms. The institutional context highlights the increasing role of CEOs in shaping corporate culture and influencing employees through public socio-political engagements.

## Hypothesis
The paper develops two main hypotheses based on existing theories and literature:

1. **Hypothesis 1**: When CEO activism aligns with the ideological beliefs of the firm’s employees, it will lead to higher employee satisfaction.
2. **Hypothesis 2**: When CEO activism misaligns with employee ideologies, it may either result in no significant response or potentially a negative response.

### Literature Review
The literature on CEO activism and employee behavior builds on several key theoretical frameworks:
- **Social Identity and Influence Theories**: CEO activism can drive alignment between employees and their organization, leading to improved retention and recruitment of employees who share similar values (Hambrick and Wowak, 2021).
- **Melloni et al. (2019)**: Suggests that employees derive non-monetary benefits from working under CEOs whose ideological beliefs match their own, thereby increasing job satisfaction.
- **Negative Reactions**: When CEO activism contrasts with employee beliefs, it can lead to tension and reduced morale (Noguchi, 2018).
  

The paper's hypotheses emerge from this literature, focusing on whether aligned activism leads to improved employee satisfaction and innovation, while misaligned activism has no or negative effects.

## Research Design
The empirical strategy employs multiple regression models to estimate the relationship between CEO activism and employee satisfaction, using Glassdoor ratings as a proxy for employee satisfaction. The general regression equation is:

$$
Employee\_Satisfaction_{i,t} = \alpha + \beta_1 CEO\_Activism_{i,t-1} + X_{i,t-1} + \epsilon_{i,t}
$$

Where:
- $Employee\_Satisfaction_{i,t}$ is the overall employee satisfaction for firm $i$ in year $t$ (measured via Glassdoor ratings).
- $CEO\_Activism_{i,t-1}$ is the number of CEO activism events for firm $i$ in the previous year.
- $X_{i,t-1}$ represents control variables including firm size, stock return, R&D intensity, leverage, and other CEO and firm characteristics.
- $\epsilon_{i,t}$ is the error term.

To better capture the nature of CEO activism, the authors decompose the activism events into those that are aligned or misaligned with employee ideologies:

$$
Employee\_Satisfaction_{i,t} = \alpha + \beta_1 Aligned\_CEO\_Activism_{i,t-1} + \beta_2 Misaligned\_CEO\_Activism_{i,t-1} + X_{i,t-1} + \epsilon_{i,t}
$$

### Variables:
- **Dependent Variable**: Employee satisfaction measured through Glassdoor overall company ratings.
- **Independent Variables**: 
  - The number of CEO activism events, split into categories of "aligned" and "misaligned" activism based on the ideological match with employees.
  - Activism topics (e.g., diversity, environment, social issues).
- **Control Variables**: Firm size, return on assets (ROA), R&D/sales, leverage, corporate social responsibility (CSR) index, and whether the firm is listed on the Fortune 100 Best Companies to Work For.

### Robustness Checks:
Several methods are employed to ensure the robustness of the results:
1. **CEO Turnover**: The analysis focuses on changes in CEO activism before and after CEO turnovers to mitigate the impact of individual CEO characteristics.
2. **Exclusion of Outliers**: The results are tested by excluding highly vocal CEOs who participate in a disproportionate number of activism events.
3. **Entropy Balancing**: This technique is used to ensure the treatment (activism) and control groups are well-matched on observable characteristics.
4. **Fixed Effects**: The model includes year and industry fixed effects to account for time-invariant unobservable factors.
5. **Pre-trend Analysis**: The authors check for differences in employee satisfaction trends prior to CEO activism to confirm the direction of causality.

## Empirical Results

1. **Positive Employee Responses**: Aligned CEO activism is associated with higher overall employee satisfaction. In contrast, misaligned activism has an insignificant effect.
2. **Less Dispersion in Ratings**: Companies with more aligned CEO activism events have less dispersion in their employee satisfaction ratings, indicating greater consensus among employees.
3. **Subcategories of Activism**: Employees respond more positively to activism related to workplace issues such as diversity and pay equality than to broader social or political issues.
4. **Impact on Innovation**: Aligned CEO activism not only boosts employee satisfaction but also attracts talented and ideologically aligned inventors, leading to higher innovation outcomes (more patents and citations).
5. **Labor Market Signaling**: The study finds that CEO activism is a reliable signal of company practices, with firms engaging in diversity-related activism actually hiring more underrepresented employees and reducing gender pay gaps.

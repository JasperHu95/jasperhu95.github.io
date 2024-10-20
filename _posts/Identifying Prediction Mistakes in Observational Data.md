# Identifying Prediction Mistakes in Observational Data

Link: [EconPapers: Identifying Prediction Mistakes in Observational Data*](https://econpapers.repec.org/article/oupqjecon/v_3a139_3ay_3a2024_3ai_3a3_3ap_3a1665-1711..htm)

## Summary

This paper develops an econometric framework to identify systematic prediction mistakes made by decision makers in high-stakes settings (e.g., judges in pretrial release decisions). It provides a statistical test to detect such mistakes and methods to estimate systematic biases. Applying this framework to New York City pretrial release data, the paper finds that a significant portion of judges exhibit systematic prediction mistakes regarding defendant characteristics. The analysis explores the potential benefits of replacing human judges with algorithms to minimize errors.

## Introduction
The paper addresses the challenge of determining whether decision makers (e.g., judges, doctors, managers) make systematic prediction errors. These errors are examined in various contexts, including criminal justice, healthcare, and hiring. The increasing use of machine learning in decision-making highlights the importance of understanding prediction biases. The authors propose a framework to evaluate decision makers' implicit predictions by comparing them to those made by predictive models.

## Institutional Background
The study focuses on the pretrial release system in New York City, where judges decide whether to release defendants based on failure-to-appear risk. The analysis involves testing whether judges’ decisions align with expected utility maximization, given available information like race, age, and charge severity. Judges’ decisions were analyzed under different assumptions about which characteristics affect utility functions.

## Literature Review
The paper draws on several key areas of existing research:

1. **Decision Making vs. Machine Learning**: Previous studies compare human decision-making with predictive models across various contexts. For instance, Kleinberg et al. (2018) analyze judge decisions in pretrial release, while Mullainathan and Obermeyer (2022) examine medical diagnostics. These studies use machine learning to identify biases in human predictions. This paper extends these comparisons to a broader econometric framework, providing tools for evaluating systematic prediction mistakes under less restrictive assumptions.

2. **Econometric Frameworks**: The proposed framework builds on microeconomic theories of state-dependent stochastic choice (e.g., Caplin and Dean, 2015) and the statistical analysis of moment inequalities (e.g., Canay and Shaikh, 2017; Molinari, 2020). This literature offers methodologies for evaluating decision consistency with expected utility maximization, but earlier studies have limitations in handling missing data problems common in observational settings.

3. **Risk Assessments in Criminal Justice**: Research by Arnold, Dobbie, and Hull (2022), Stevenson (2018), and Dobbie and Yang (2019, 2021) explores the use of risk assessment tools in criminal justice systems across the U.S. These studies highlight how such tools can aid in reducing prediction errors related to failure-to-appear and pretrial misconduct.

4. **Behavioral Decision Making**: The literature on behavioral decision making (e.g., Camerer and Johnson, 1997; Grove et al., 2000) provides a foundation for understanding systematic biases in predictions. This paper also references works on bounded rationality, such as Gabaix (2014), which explains deviations from rational decision-making due to limited cognitive capacity.

## Hypothesis
1. **Literature Review**: Existing literature demonstrates that decision makers often deviate from optimal decision-making due to biases, limited attention, or inaccurate beliefs. In pretrial settings, judges have been found to make discriminatory decisions based on defendant characteristics like race, despite the availability of more accurate risk assessments.

2. **Hypothesis**: The paper hypothesizes that judges make systematic prediction mistakes that lead to suboptimal release decisions. Specifically, judges' decisions may violate expected utility maximization due to biases or misperceptions of failure-to-appear risks based on defendant characteristics.

## Research Design
The paper uses a set of moment inequalities to test whether judges’ decisions align with expected utility maximization. The primary equation is:
$$
\text{max}_{d \in D_1 (x_I)} \mu_1 (x_I, d) \leq \text{min}_{x \in D_0 (x_I)} \mu_0 (x_I, d)
$$

Here, $ \mu_1 (x_I, d) $ and $ \mu_0 (x_I, d) $ represent the expected utility associated with release (1) and detention (0), respectively, for a given set of characteristics $ x_I $.

- **Dependent Variable**: The release decision (coded as 0 for detention, 1 for release).
- **Independent Variables**: Demographic information (race, age), criminal history, and charge severity (felony vs. misdemeanor).
- **Instrument**: Judge leniency, defined as the leave-one-out average release rate, serves as an instrument for evaluating systematic prediction mistakes. The quasi-random assignment of judges ensures the validity of this instrument.

## Empirical Results
1. **Systematic Mistakes Identification**: At least 20% of judges make systematic prediction mistakes regarding failure-to-appear risks, even after controlling for defendant characteristics. This finding remains robust across different bounding strategies.

2. **Bias in Decision Making**: The results suggest that judges' decisions are often inconsistent with maximizing expected utility, indicating biases related to race and age.

3. **Impact of Algorithmic Replacement**: The paper finds that replacing human judges with algorithmic decision rules, particularly in cases where systematic mistakes are identified, can reduce prediction errors and improve decision outcomes.
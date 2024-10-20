# Predicting and Preventing Gun Violence: An Experimental Evaluation of READI Chicago

Link: [Predicting and Preventing Gun Violence: An Experimental Evaluation of READI Chicago - Final Paper - University of Chicago Crime Lab](https://crimelab.uchicago.edu/resources/readi-paper/)

## Summary

This paper presents the findings from a randomized controlled trial evaluating the Rapid Employment and Development Initiative (READI) in Chicago, aimed at reducing gun violence through an 18-month program combining subsidized employment and cognitive behavioral therapy (CBT). The study involved 2,456 men identified as high-risk for gun violence. While there was no statistically significant change in the overall serious violence index, specific results indicated that participants referred by outreach workers saw substantial reductions in shooting and homicide arrests. The study suggests a benefit-cost ratio between 4:1 and 18:1, highlighting the program's potential effectiveness.

## Introduction
The introduction outlines the pressing issue of gun violence in U.S. cities, particularly its impact on Black men who face a disproportionately high risk of homicide. It discusses the shortcomings of aggressive policing strategies and the need for community-based interventions that can reduce violence without imposing high social costs. The authors introduce READI as a targeted approach to engage high-risk individuals through employment and therapy, aiming to address both the identification of high-risk individuals and the means to effectively reduce their involvement in gun violence.

## Institutional Background
READI operates in five of Chicago's neighborhoods with the highest levels of gun violence. The program seeks to identify and support men at high risk of gun violence using multiple referral methods, including a machine learning algorithm based on arrest and victimization records, community outreach workers, and screening among recently incarcerated individuals. This multifaceted approach aims to overcome the challenges of engaging a population that is often disconnected from social services.

## Literature Review
The authors extensively review previous studies and frameworks relevant to community-based interventions aimed at reducing gun violence. Notable references include:

1. **Targeted Policing and CVIs**: Studies by Sherman and Rogan (1995), Braga et al. (2001), and Skogan et al. (2008) discuss targeted policing strategies that focus on hot spots and individuals at high risk of violence. These studies generally support the idea that focused policing can reduce crime but may have mixed results on violence specifically.

2. **Effectiveness of Interventions**: Research by Braga, Papachristos, and Hureau (2014) and Butts et al. (2015) evaluates community interventions like violence interruption, which involves mediating disputes within communities to prevent violent confrontations. The results are characterized as mixed, with some success in reducing violence but challenges in consistent application and evaluation.

3. **Tertiary Prevention**: The paper discusses newer forms of CVIs that include preventative services offered to individuals at high risk of involvement in gun violence. This approach aligns with tertiary prevention models but, as the authors note, lacks causal evidence proving its effectiveness.

4. **Combining Jobs and Enhanced Services**: Transitional jobs programs are discussed with a focus on whether they reduce crime and violence. Studies cited include those by Redcross et al. (2016) and research by Cummings and Bloom (2020) that suggest combining job opportunities with CBT might be more effective.

## Research Design
### Regression Equation
The authors use a regression model to analyze the impact of the READI program on gun violence involvement. The primary outcome variable is a standardized index that combines three specific measures of violence:

- Shooting and homicide victimizations
- Shooting and homicide arrests
- Arrests for other serious violent crimes

The regression equation can be represented as:
$$
Y_i = \beta_0 + \beta_1 \text{Treatment}_i + \epsilon_i
$$
### Variable Definitions

- **Treatment**: Binary variable indicating whether the participant was in the treatment group (received READI) or control group.
- **Outcome Measures**: Various metrics of involvement in serious violence, as noted above.

### Robustness Checks

- **Multiple Testing Adjustment**: Given the multiple outcome measures, the authors adjust for multiple hypothesis testing using techniques that control the family-wise error rate.
- **Subgroup Analysis**: They perform subgroup analyses to understand how the intervention impacts different groups, such as those referred by outreach workers versus algorithmic identification.
- **Control for Confounders**: The study design inherently controls for potential confounders by using random assignment, ensuring that any observed effects can be attributed to the intervention rather than pre-existing differences between groups.

## Empirical Results

1. **Primary Outcome**: No significant impact on the overall serious violence index (p = 0.26).
2. **Shooting and Homicide Arrests**: Participants had 65% fewer shooting and homicide arrests (adjusted p = 0.13), suggesting a potential effect that requires further validation.
3. **Victimization Rates**: Participants experienced a 12% reduction in shooting and homicide victimizations.
4. **Social Cost Savings**: READI generated estimated social savings between $182,000 and $916,000 per participant (p = 0.03), translating to a benefit-cost ratio of 4:1 to 18:1.
5. **Heterogeneous Effects**: Participants referred by outreach workers showed significant reductions in both arrests and victimizations, with reductions of 79% and 43% respectively (adjusted p = 0.03 and p = 0.08).

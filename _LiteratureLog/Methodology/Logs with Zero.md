# Logs with Zeros? Some Problems and Solutions

Link: [Logs with Zeros? Some Problems and Solutions* | The Quarterly Journal of Economics | Oxford Academic (oup.com)](https://academic.oup.com/qje/article/139/2/891/7473710)

This paper by Jiafeng Chen and Jonathan Roth addresses the problems that arise when applying logarithmic transformations to outcome variables that are weakly positive but may equal zero (e.g., earnings). In such cases, researchers often apply "log-like" transformations, such as $log(1 + Y)$ or $arcsinh(Y)$, which are well-defined at zero but behave similarly to log for large values of $Y$. The authors argue that such transformations lead to misleading interpretations, particularly when the outcome can be zero, as the average treatment effects (ATEs) for these transformations are arbitrarily sensitive to the units of the outcome. The paper proposes several alternative methods to handle these issues and provides empirical examples to illustrate the solutions.

## Introduction

The introduction sets the stage by identifying a common challenge in empirical economics: when studying outcomes like earnings, which can equal zero, standard log transformations (e.g., $log(Y)$) are undefined. As a result, researchers often turn to "log-like" transformations, such as $log(1 + Y)$ or $arcsinh(Y)$. However, the authors argue that these transformations should not be interpreted as percentage changes, especially when treatment effects impact the extensive margin (i.e., when treatment moves individuals from zero to nonzero outcomes). The chapter introduces the central problem of unit dependence in these transformations and sets the agenda for exploring better alternatives.

## Sensitivity to Scaling for Log-like Transformations

### Overview of the Problem
Researchers often use $log(1 + Y)$ or $arcsinh(Y)$ transformations when the outcome can equal zero. However, the authors argue that these transformations are problematic because the estimated ATEs for these transformations depend on the scaling of the outcome variable. 

### Theoretical Background
The chapter begins by establishing that for any continuous, increasing function $m(Y)$ that behaves like $log(Y)$ for large values of $Y$, the ATE for $m(Y)$ is arbitrarily sensitive to the units of $Y$. This is particularly true when the treatment affects the extensive margin.

### Log Transformations' Limitations
While $log(Y)$ can approximate percentage changes when $Y$ is strictly positive, $log(1 + Y)$ and $arcsinh(Y)$ cannot be similarly interpreted, especially when $Y = 0$ for some individuals.

### Intensive vs. Extensive Margins
The authors highlight that "intensive margin" refers to changes in the magnitude of $Y$ for individuals with nonzero outcomes, while "extensive margin" refers to individuals transitioning from zero to nonzero. The relative weight placed on these two margins is determined implicitly by the units of $Y$ in log-like transformations.

### Numerical Examples
Through simulations, the authors demonstrate how rescaling the outcome (e.g., from dollars to cents) can drastically change the ATE estimates, highlighting the arbitrariness of log-like transformations.

### The Impact of Extensive Margin
If treatment shifts individuals from zero to nonzero outcomes, researchers can manipulate the magnitude of the ATE by rescaling the outcome. This shows that log-like transformations are unreliable when there is a nonzero extensive margin effect.

### Poisson Regression as an Alternative
The authors suggest that Poisson regression can estimate ATEs directly in levels and express them as percentage changes, avoiding the scaling issues associated with log-like transformations.

### Comparison to Existing Literature
The chapter concludes with a comparison to previous work, emphasizing the wide use of arcsinh transformations and the misinterpretation of their ATEs as percentage effects.

## The Trilemma

In the third chapter, the authors introduce a fundamental trilemma when dealing with zero-valued outcomes: no treatment effect parameter can satisfy all three of the following conditions simultaneously:
1. The parameter is an average of individual-level treatment effects, i.e., $E[g(Y(1), Y(0))]$ where $g$ is increasing in $Y(1)$.
2. The parameter is invariant to rescaling of the units of the outcome.
3. The parameter is point identified from the marginal distributions of the potential outcomes.

The chapter elaborates that researchers must make trade-offs among these properties. For example, $log(1 + Y)$ satisfies the first and third properties but is sensitive to rescaling, violating the second property.

## Alternative Approaches

This chapter explores various approaches that researchers can adopt to estimate treatment effects when outcomes may equal zero, each addressing the trilemma in different ways:

### Percentage Changes in Levels
One alternative is to use Poisson regression to express the ATE in levels as a percentage change, which avoids the scaling sensitivity problem. This method estimates the ATE in a way that is both point identified and scale-invariant.

### Explicit Calibration of Margins
Researchers can explicitly choose how much weight to place on the extensive margin versus the intensive margin. For example, researchers might value a change from zero to one unit as being equivalent to a certain percentage change on the intensive margin.

### Separate Estimates for Intensive and Extensive Margins
Another approach is to estimate separate effects for the intensive and extensive margins using methods like Lee bounds. This allows researchers to disentangle the effects on individuals whose outcomes remain positive from those whose outcomes shift from zero to positive.

The authors illustrate the practical importance of these alternatives through replications of recent empirical studies that applied arcsinh or $log(1 + Y)$ transformations.

## Empirical Applications

The fifth chapter presents three empirical applications to demonstrate how the alternative approaches can be applied in practice across different study designs:

### Randomized Controlled Trial (RCT)

The first example comes from Carranza et al. (2022), where the authors study how certification affects weekly hours worked. The original analysis uses arcsinh transformations, but the authors reanalyze the data using Poisson regression to express the treatment effect as a percentage change in levels. This avoids the unit dependence issue of the arcsinh transformation.

### Difference-in-Differences (DiD)
In Sequeira (2016), the authors examine how tariff reductions affect bribes. The original study uses $log(1 + Y)$ to estimate the effects, but the authors show that this approach leads to unit-dependent results. They suggest that Poisson regression can better capture the percentage change in bribes and avoid the sensitivity to unit scaling.

### Instrumental Variables (IV)

The final example comes from Berkouwer and Dean (2022), where the authors use an IV approach to estimate the effect of adopting energy-efficient stoves on household spending. The original study uses arcsinh transformations, but the authors apply Lee bounds to separately estimate the effects on the intensive and extensive margins.

## Conclusion

In the conclusion, the authors reiterate that log-like transformations such as $log(1 + Y)$ or $arcsinh(Y)$ are not suitable for interpreting treatment effects as percentage changes, particularly when the outcome can equal zero. They advocate for alternative approaches, including Poisson regression, explicit calibration of intensive versus extensive margins, and methods like Lee bounds for separating margin effects. These alternatives provide more robust and interpretable treatment effect estimates, especially in settings where the outcome can equal zero.
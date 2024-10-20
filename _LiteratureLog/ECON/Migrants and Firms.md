# Migrants and Firms: Evidence from China

Link: [Migrants and Firms: Evidence from China - American Economic Association (aeaweb.org)](https://www.aeaweb.org/articles?id=10.1257/aer.20191234)

## Summary

This paper examines how rural-urban migration shapes urban production in developing countries, focusing on Chinese manufacturing firms from 2000 to 2006. The authors exploit exogenous variation in rural-urban migration induced by agricultural income shocks to estimate the causal effects. They find that increased migration leads to more labor-intensive production, a reduction in productivity, and the adoption of labor-intensive technologies and product varieties. The study also shows that lower labor costs result from migration, but firms reduce capital intensity, leading to a decline in value added per worker. Low-productivity, labor-intensive firms tend to survive and grow more than capital-intensive firms after migration shocks.

## Introduction
The paper addresses the limited empirical evidence on how rural-urban migration influences urban production in developing countries. Past studies point to several factors affecting firm productivity, such as limited access to capital, inputs, technology, and international markets. The research explores whether an influx of rural migrant labor reduces the incentive for firms to adopt productivity-enhancing technologies. Using longitudinal data from Chinese manufacturing firms, the paper estimates the causal effect of rural migration on urban production, particularly focusing on labor costs, employment, capital allocation, and technological innovation.

## Institutional Background
The study is set against the backdrop of a significant migration period in China, during which more than 45 million rural workers moved to cities between 2000 and 2006. This internal migration was driven by agricultural income shocks caused by changes in global commodity prices, pushing rural workers to seek employment in urban areas. The rural-urban migration policies, such as the household registration system (hukou), and China's rapid industrialization created unique conditions for studying the effects of such labor flows on urban production.

## Hypothesis (Literature Review)
The authors build their hypotheses based on key contributions from the literature:

1. **Productivity and Labor Markets**: Hall and Jones (1999) identify lower productivity per worker in developing countries, driven by issues like limited access to capital, technology, and inputs.
   
2. **Rural-Urban Migration and Productivity**: Lewis (1954) theorized that economic development involves moving rural workers into manufacturing, which could disincentivize firms from adopting productivity-enhancing technologies. Lewis (2011) further discussed how an abundance of cheap labor may delay technological upgrades.
   
3. **Labor and Technological Substitution**: The paper cites evidence (e.g., Lewis, 2011) that low-skilled migrant inflows may lead firms to adopt labor-intensive technologies rather than capital-enhancing innovations, which could reduce productivity.
   
4. **Internal Migration Effects**: Studies on internal migration within China (De Sousa and Poncet, 2011; Ge and Yang, 2014) yield mixed results regarding the impact on wages and productivity. This study addresses the need for more detailed empirical analysis.
   
5. **Structural Transformation**: The movement of labor from agriculture to manufacturing is central to structural transformation models (Alvarez-Cuadrado and Poschke, 2011), where increased labor supply from rural areas can support industrialization.

## Research Design

### Regression Equation and Variable Definitions
The authors use a shift-share instrumental variable approach to estimate the effects of rural-urban migration on urban production. The baseline regression model is:

$$
\Delta y_{id} = \alpha + \beta m_d + \varepsilon_{id}
$$

Where:
- $ \Delta y_{id} $: Represents the change in outcome variables (such as labor cost, employment, capital-labor ratio) for firm $ i $ in destination $ d $ between 2000 and 2006.
- $ m_d $: The immigration rate at destination $ d $, measured as the flow of migrants divided by the baseline population in 2000.

**Key Outcome Variables Include**:
1. **Labor Cost**: Measured as the log of total compensation per worker (including social security and housing benefits).
2. **Employment**: Measured as the log of the number of employees.
3. **Capital-to-Labor Ratio**: Measured as the log of fixed assets divided by employment.
4. **Value Added per Worker**: Measured as the log of the ratio of value added to employment.

### Shift-Share Instrument
The authors use agricultural income shocks as an instrument to predict migration flows. The shock ($ s_o $) is constructed using a combination of baseline cropping patterns and international commodity price innovations, capturing exogenous fluctuations in rural income. These shocks are interacted with historical migration patterns to generate the instrument $ z_d $, which predicts migration flows to urban areas.

$$
z_d = \sum_{o \in \Theta} \lambda_{od} s_o
$$

Where:
- $ \lambda_{od} $: Represents the historical migration share from origin $ o $ to destination $ d $.
- $ s_o $: The agricultural income shock at origin $ o $.

### Robustness Checks

1. **Exclusion of Specific Industries**: They exclude industries that process agricultural goods to avoid potential biases from direct rural-urban linkages in production chains.
2. **Industry Fixed Effects**: Industry fixed effects are included to control for sector-specific trends that might influence outcomes.
3. **Geographic Distance Control**: To reduce local demand effects, migration flows within 300 kilometers are excluded from the analysis.
4. **Control for Market Access**: A variable representing market access is included, based on the weighted population of rural areas relative to their distance from urban centers.
5. **Firm Characteristics**: The analysis explores whether the effects vary based on firm characteristics, such as capital intensity or productivity, to detect heterogeneity in treatment.
6. **Spatial Correlation of Standard Errors**: The authors address spatial correlation using the Conley (1999) method to adjust standard errors, ensuring accurate inference.

### Empirical Results

1. **Labor Cost and Employment**: A 10 percentage point increase in the migration rate leads to a 1.5% decrease in labor compensation per worker and a 2.9% increase in employment.
2. **Capital-to-Labor Ratio**: Migration reduces the capital-to-labor ratio by 4.3%, suggesting that firms do not adjust capital to the increased availability of labor.
3. **Productivity**: A 10 percentage point increase in migration results in a 4.4% decline in value added per worker.
4. **Innovation**: Migration reduces patenting activity by 10%, especially in capital-intensive technologies, leading firms to focus on labor-intensive products.

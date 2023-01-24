# ANOVA - Analysis of variance
## What is ANONA Test?
An Analysis of variance-ANOVA is a test that is used to test whether there exist statistically significant difference between the mean values of more than two groups.
## Assumptions for the ANOVA hypothesis test
1. Sample data are randomly selected from populations and randomly assigned to each of the treatment groups. Each observation is thus independent of any other observation — randomness and independence..
2. Normality. Values in each sampled groups are assumed to be drawn from normally distributed populations. We can use normal probability plot or Q-Q plot to check normality.
3. Homogeneity of variance. All the c group variances are equal, that is σ₁² = σ₂² = σ₃² = … = σ𝒸². As a rule of thumb, if the ratio of the largest to the smallest sample standard deviation is less than 2, we consider the equal standard deviations assumption as fulfilled.
## The simple outline of ANOVA test:
F test for differences in more than two means

H₀: μ₁= μ₂ = μ₃ = … = μ𝒸

H₁: Not all μᵢ’s are equal, where i = 1, 2, 3, …, c.

Level of significance = α

### Given a soil dataset , we want to test whether there exist statistically significant association between soil pH value, Depth and contour
![1](https://user-images.githubusercontent.com/107842949/179838346-94d33e97-9fca-49ba-bda5-98079032fe07.JPG)
## Cleaning the dataset
Check if there exist nul values
![2](https://user-images.githubusercontent.com/107842949/179838517-fe08af25-0ce5-4f1f-81df-69e4494de929.JPG)
## Relationship Between Depth, Contour and pH Value
![3](https://user-images.githubusercontent.com/107842949/179838809-6d939703-bd7a-4af9-8059-a8a3ce915968.JPG)
## Conclusion
In the case of Depth, the p-value is smaller than the critical value of 0.05.Therefore we can conclude that there is statisticaly significant association of Depth on the Soil pH value.

In the case of Contour, the p value is greater than the critical value of 0.05. Therefore, we can conclude that there is no statisticaly significant association of Contour on the Soil pH value.

In the case of intercept of Depth and Contour,the p value is greater than the critical value of 0.05. Therefore, we can conclude that there is no statisticaly significant association between intercept of Depth and Contour on the Soil pH value.

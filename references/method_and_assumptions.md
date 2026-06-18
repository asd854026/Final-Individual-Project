# Method and Assumptions

## Statistical Method

This project uses a one-way ANOVA to compare mean BMI percentile (`BMIPCT`) across five student weight perception groups.

## Hypotheses

- H0: The mean BMIPCT is the same across all PerceptionOfWeight groups.
- Ha: At least one PerceptionOfWeight group has a different mean BMIPCT.

## Alpha Level

The alpha level is 0.05. If the ANOVA p-value is below 0.05, the decision is to reject H0.

## Why ANOVA Fits This Question

- `PerceptionOfWeight` is a categorical explanatory variable with five groups.
- `BMIPCT` is a quantitative response variable.
- The research question compares mean BMI percentile across more than two groups.

## Assumption Considerations

- Independence: The records are treated as independent student survey responses for this class project.
- Quantitative response: `BMIPCT` is numeric and ranges from 0 to 100.
- Group sizes: All five groups have usable sample sizes, from 207 to 7,351.
- Equal variance: Group standard deviations are not identical, so results should be interpreted cautiously. The course-required method is still one-way ANOVA.
- Normality: With a cleaned sample size of 12,853, ANOVA is reasonably robust for this beginner-level project, but the result should still be described as statistical association.

## Post-Hoc Test

Because the ANOVA result is statistically significant, Tukey HSD post-hoc comparisons are used to compare pairs of weight perception groups.

## Result Used in the Project

The ANOVA result is statistically significant: F = 1556.65, p < 0.001. The decision is: Reject H0.

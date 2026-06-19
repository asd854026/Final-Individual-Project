# Project Cycle 4

## Project Repository

GitHub link:https://github.com/asd854026/2026-Spring-Stat2-Cycle4/tree/main

## Presentation Video

YouTube link:

## Research Question

Do students' perceptions of their weight reflect their actual BMI percentile?

## Dataset

This project uses the `YRBS_2007.csv` dataset provided for the final individual statistics project. The dataset contains 14,041 student survey records and 103 variables related to student demographics, behaviors, health measures, and survey design fields.

## Variables

- `PerceptionOfWeight`: categorical explanatory variable coded from 1 to 5.
- `BMIPCT`: quantitative response variable measuring BMI percentile.

`PerceptionOfWeight` was recoded as:

| Code | Category |
|---:|---|
| 1 | Very underweight |
| 2 | Slightly underweight |
| 3 | About the right weight |
| 4 | Slightly overweight |
| 5 | Very overweight |

## Method

One-way ANOVA was used to compare mean BMI percentile across the five perceived weight groups. Because the ANOVA result was statistically significant, Tukey HSD post-hoc comparisons were also used.

## Main Results

After cleaning, the analysis dataset contained 12,853 students. The one-way ANOVA found a statistically significant difference in mean BMI percentile across perceived weight groups, F = 1556.65, p < 0.0001. The highest mean BMI percentile was in the `Very overweight` group (92.30), while the lowest mean BMI percentile was in the `Slightly underweight` group (36.53). Tukey HSD found 10 statistically significant pairwise comparisons out of 10.

## Conclusion

Students' perceived weight category is associated with their actual BMI percentile. Students who perceived themselves as overweight generally had higher BMI percentiles than students who perceived themselves as underweight or about the right weight. This conclusion should be stated cautiously because the data show association, not causation.

# Recoding Rules

## Source File

The original data file is `data/raw/YRBS_2007.csv`.

## Variables Selected

Only two variables are selected for this project:

- `PerceptionOfWeight`
- `BMIPCT`

## Cleaning Steps

1. Select only `PerceptionOfWeight` and `BMIPCT`.
2. Drop rows with missing values in either variable.
3. Keep only valid `PerceptionOfWeight` codes: 1, 2, 3, 4, and 5.
4. Keep only valid `BMIPCT` values from 0 to 100.
5. Recode `PerceptionOfWeight` into readable category labels.
6. Save the cleaned file as `data/processed/weight_perception_bmipct_cleaned.csv`.

## PerceptionOfWeight Recoding

| Original Code | Recoded Label |
|---:|---|
| 1 | Very underweight |
| 2 | Slightly underweight |
| 3 | About the right weight |
| 4 | Slightly overweight |
| 5 | Very overweight |

## Cleaning Counts

- Original rows: 14,041
- Rows missing at least one analysis variable: 1,188
- Invalid PerceptionOfWeight values after dropping missing rows: 0
- Invalid BMIPCT values after dropping missing rows: 0
- Final cleaned rows: 12,853
- Total rows removed from the analysis file: 1,188

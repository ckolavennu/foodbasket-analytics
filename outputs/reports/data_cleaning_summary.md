# Data Cleaning Summary

## Dataset

Raw dataset: `data/raw/food_prices_raw.csv`  
Processed dataset: `data/processed/food_prices_cleaned.csv`

## Cleaning Steps Completed

1. Loaded the raw food price dataset using Python and Pandas.
2. Checked dataset shape, column names, and data types.
3. Checked for missing values across all columns.
4. Standardised text fields such as item names, categories, store, and location.
5. Converted collection date into datetime format.
6. Converted quantity and price into numeric data types.
7. Created a calculated `price_per_unit` column.
8. Reordered columns for readability.
9. Exported the cleaned dataset as a processed CSV file.

## Notes

The dataset uses item-level grocery prices collected manually from Lotus's Malaysia. Some items use the closest available product size where the original planned quantity was not available. These cases are documented in the notes column.

The `price_per_unit` column should be interpreted carefully because units differ across items
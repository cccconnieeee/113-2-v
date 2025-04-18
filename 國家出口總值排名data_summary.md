
# Dataset Summary Report

This report summarizes the dataset `國家出口總值排名前三名.csv`, which contains information about the top 30 export destinations of Taiwan for a given period.

---

## Dataset Overview

- **Period Covered**: 113年1-8月
- **Observations**: 30
- **Variables**: 7 main variables (+ parsed time fields)
- **Purpose**: To analyze Taiwan’s top export markets by value and percentage.

---

## Variable Summary

### 1. `period`
- **Type**: Character
- **Description**: The reporting period, e.g., "113年1-8月".
- **Example**: "113年1-8月"

### 2. `gregorian_year`
- **Type**: Integer
- **Description**: Gregorian year converted from ROC year.
- **Example**: 2024

### 3. `month_range`
- **Type**: Character
- **Description**: Month range extracted from the period.
- **Example**: "1-8月"

### 4. `ranking`
- **Type**: Integer
- **Description**: Rank based on export value.
- **Range**: 1 to 30

### 5. `country`
- **Type**: Factor (Categorical)
- **Description**: Destination country of export.
- **Example**: "美國", "中國大陸"

### 6. `export_value_ntd`
- **Type**: Numeric
- **Description**: Export value in New Taiwan Dollars (thousands).
- **Example**: 2,418,574,929

### 7. `percentage`
- **Type**: Numeric (Double)
- **Description**: Share of each country's exports as a percentage of total.
- **Range**: ~1.0 to 24.48

### 8. `note`
- **Type**: Character
- **Description**: Notes or annotations.
- **Example**: Usually empty (NA)

---

## Suggested Next Steps

- Add more periods for time series analysis.
- Visualize top 10 countries over time.
- Explore export concentration and diversification trends.


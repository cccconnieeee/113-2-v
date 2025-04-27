# Taiwan Exports to the United States - Parsed Data

## Dataset Description
This dataset contains Taiwan's exports to the United States, broken down by major product categories. Dates have been converted from the Taiwanese Minguo calendar to Gregorian dates, and column names have been cleaned to tidy, English snake_case format.

---

## Variables

| Variable Name          | Class   | Meaning |
|:-----------------------|:--------|:--------|
| date                   | Date    | Year and month (parsed from Minguo year) |
| total_usd_thousand     | Numeric | Total export value to the U.S. (in thousand USD) |
| animal_products        | Numeric | Live animals and animal products export value |
| plant_products         | Numeric | Plant products export value |
| fats_oils              | Numeric | Animal/vegetable fats and oils export value |
| prepared_foods         | Numeric | Prepared foods; beverages; tobacco export value |
| mineral_products       | Numeric | Mineral products export value |
| chemical_products      | Numeric | Chemical products export value |
| plastics_rubber        | Numeric | Plastics, rubber and articles thereof export value |
| furs                   | Numeric | Furskins and artificial fur articles export value |
| wood_products          | Numeric | Wood and wood products export value |
| paper_products         | Numeric | Pulp, paper, paper products; printed material export value |
| textiles               | Numeric | Textiles and textile articles export value |
| footwear_accessories   | Numeric | Footwear, headgear, and accessories export value |
| nonmetal_products      | Numeric | Articles of stone, plaster, cement, asbestos, mica, etc. export value |
| jewelry_metals         | Numeric | Jewelry and precious metal products export value |
| base_metals            | Numeric | Base metals and articles thereof export value |
| machinery_equipment    | Numeric | Machinery and electrical equipment export value |
| transport_equipment    | Numeric | Transport equipment export value |
| optical_instruments    | Numeric | Optical instruments, watches, musical instruments export value |
| other_exports          | Numeric | Other export categories not specified above |

---

## Example Data

| date       | total_usd_thousand | animal_products | plant_products | fats_oils | ... |
|------------|--------------------|-----------------|----------------|-----------|-----|
| 2001-01-01 | 2362807             | 13964           | 1857           | 367       | ... |
| 2001-02-01 | ...                | ...             | ...            | ...       | ... |

---

## Notes
- The original `year_month` variable has been parsed using string extraction and converted into a proper date format (YYYY-MM-DD).
- Column names have been standardized to English snake_case to comply with tidyverse and R for Data Science practices.

---

## Suggested Summarization Methods

| Variable Name          | Suggested Summary Method |
|:-----------------------|:--------------------------|
| date                   | Time trend plots, count of records per year/month |
| total_usd_thousand     | Mean, median, total sum, trend over time |
| animal_products        | Mean, total sum, seasonal pattern analysis |
| plant_products         | Mean, total sum, seasonal pattern analysis |
| fats_oils              | Mean, total sum, check for outliers |
| prepared_foods         | Mean, total sum, seasonal trend |
| mineral_products       | Mean, total sum, variance over time |
| chemical_products      | Mean, total sum, highlight major changes |
| plastics_rubber        | Mean, total sum, correlation with machinery_equipment |
| furs                   | Mean, detect extreme months (outliers) |
| wood_products          | Mean, total sum, detect any structural breaks |
| paper_products         | Mean, total sum, plot time series |
| textiles               | Mean, total sum, trend analysis |
| footwear_accessories   | Mean, total sum, detect declining trend if any |
| nonmetal_products      | Mean, total sum, variance check |
| jewelry_metals         | Mean, total sum, highlight spikes |
| base_metals            | Mean, total sum, trend analysis |
| machinery_equipment    | Mean, median, total sum, key driver analysis |
| transport_equipment    | Mean, total sum, trend comparison with machinery_equipment |
| optical_instruments    | Mean, total sum, plot time series |
| other_exports          | Mean, variance, detect any unusual months |

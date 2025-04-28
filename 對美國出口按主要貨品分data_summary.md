# 📄 Data Summary Codebook

## Dataset Description

This dataset records Taiwan's exports to the United States, broken down by major product categories.  
- **Unit**: Thousand US Dollars (千美元)  
- **Period**: From year 90 in ROC calendar (approx. 2001 AD), monthly data.

---

## Variables

| Variable Name | Type | Description |
| :------------ | :--- | :----------- |
| 年份 | string | Year in ROC calendar format (e.g., "90年" = 2001) |
| 總計(千美元) | numeric | Total export value to the U.S. (in thousand USD) |

### Export Values by Product Category

| No. | Variable Name | Type | Description |
| :-- | :------------ | :--- | :----------- |
| 1 | 活動物；動物產品(千美元) | numeric | Exports of live animals and animal products |
| 2 | 植物產品(千美元) | numeric | Exports of plant products |
| 3 | 動植物油脂(千美元) | numeric | Exports of animal and vegetable fats |
| 4 | 調製食品；飲料及菸酒(千美元) | numeric | Exports of prepared food, beverages, and tobacco |
| 5 | 礦產品(千美元) | numeric | Exports of mineral products |
| 6 | 化學品(千美元) | numeric | Exports of chemical products |
| 7 | 塑膠、橡膠及其製品(千美元) | numeric | Exports of plastics, rubber, and related products |
| 8 | 毛皮及其製品(千美元) | numeric | Exports of furs and related products |
| 9 | 木及木製品(千美元) | numeric | Exports of wood and wooden products |
| 10 | 紙漿；紙及其製品；印刷品(千美元) | numeric | Exports of pulp, paper products, and printed materials |
| 11 | 紡織品(千美元) | numeric | Exports of textiles |
| 12 | 鞋、帽及其他飾品(千美元) | numeric | Exports of footwear, hats, and other accessories |
| 13 | 非金屬礦物製品(千美元) | numeric | Exports of non-metallic mineral products |
| 14 | 珠寶及貴金屬製品(千美元) | numeric | Exports of jewelry and precious metal products |
| 15 | 基本金屬及其製品(千美元) | numeric | Exports of basic metals and their products |
| 16 | 機械及電機設備(千美元) | numeric | Exports of machinery and electrical equipment |
| 17 | 運輸工具(千美元) | numeric | Exports of transportation equipment |
| 18 | 光學及精密儀器；鐘錶；樂器(千美元) | numeric | Exports of optical, precision instruments, clocks, musical instruments |
| 19 | 其他(千美元) | numeric | Other exports |

---

## Notes
- **Year Conversion**: ROC year + 1911 = Gregorian year (e.g., 90 + 1911 = 2001).
- **Unit Reminder**: All export values are in **thousand USD**. To get actual USD, multiply by 1,000.
- **Data Use Cases**: Suitable for trend analysis, product structure studies, growth rate calculations, and economic reporting.

---


# Business Analysis Excel Project

This repository contains analysis built from **`Business Analysis Excel Project.xlsx`**.  
It includes cleaned datasets, formulas/pivots, and charts or dashboards created in Microsoft Excel.

Tip: Replace placeholder sections (TODO) with your actual project details before publishing to GitHub.


## Project Goals
- Clean and prepare raw data for analysis.
- Explore trends with pivot tables, formulas, and charts.
- Derive key metrics (KPIs) like totals, averages, growth %, etc.
- Build a dashboard for insights.


## How to Use
1. Clone or download this repo.
2. Open **`Business Analysis Excel Project.xlsx`** in Excel (or LibreOffice/Google Sheets if compatible).
3. Explore the sheets listed below (Data Dictionary + Preview).
4. (Optional) Publish dashboard screenshots in the `assets/` folder and link them in this README.


## Repo Structure (suggested)
```
.
├── Business Analysis Excel Project.xlsx   # Main workbook
├── assets/                                # Screenshots of charts or dashboard (optional)
├── data/                                  # Any exported CSVs (optional)
└── README.md                              # This file
```


## Sheets & Data Dictionary
### Sheet: Row Data
| Column | Type |
|---|---|
| Year | Decimal/Float |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Decimal/Float |
| Expenses (₹) | Decimal/Float |
| Profit (₹) | Decimal/Float |
| New Customers | Decimal/Float |
| Unnamed: 8 | Decimal/Float |
| Unnamed: 9 | Decimal/Float |
| Proper() | Text |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_Row_Data.csv)

### Sheet: Data Cleaning
| Column | Type |
|---|---|
| Year | Decimal/Float |
| Month | Text |
| Region | Text |
| Product | Text |
| Length | Text |
| Remove Space | Text |
| Length.1 | Text |
| Sales (₹) | Decimal/Float |
| Expenses (₹) | Decimal/Float |
| Profit (₹) | Decimal/Float |
| New Customers | Decimal/Float |
| Unnamed: 11 | Decimal/Float |
| Unnamed: 12 | Decimal/Float |
| Unnamed: 13 | Decimal/Float |
| Year.1 | Decimal/Float |
| Month.1 | Text |
| Region.1 | Text |
| Product.1 | Text |
| Length.2 | Decimal/Float |
| Remove Space.1 | Text |
| Length.3 | Decimal/Float |
| Sales (₹).1 | Decimal/Float |
| Expenses (₹).1 | Decimal/Float |
| Profit (₹).1 | Decimal/Float |
| New Customers.1 | Decimal/Float |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_Data_Cleaning.csv)

### Sheet: Maths Formulas
| Column | Type |
|---|---|
| Year | Integer |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Integer |
| Expenses (₹) | Integer |
| Profit (₹) | Integer |
| New Customers | Decimal/Float |
| Unnamed: 8 | Decimal/Float |
| Count of Features of New Customer | Text |
| Quantity Of Product A | Text |
| Count Of Sales | Text |
| Unnamed: 12 | Decimal/Float |
| Unnamed: 13 | Decimal/Float |
| Unnamed: 14 | Decimal/Float |
| Unnamed: 15 | Decimal/Float |
| Unnamed: 16 | Text |
| Unnamed: 17 | Text |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_Maths_Formulas.csv)

### Sheet: Statistics Formulas
| Column | Type |
|---|---|
| Year | Integer |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Integer |
| Expenses (₹) | Integer |
| Profit (₹) | Integer |
| New Customers | Integer |
| Unnamed: 8 | Decimal/Float |
| Unnamed: 9 | Decimal/Float |
| Unnamed: 10 | Decimal/Float |
| Unnamed: 11 | Text |
| Unnamed: 12 | Text |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_Statistics_Formulas.csv)

### Sheet: XLOOKUP
| Column | Type |
|---|---|
| Year | Integer |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Integer |
| Expenses (₹) | Integer |
| Profit (₹) | Integer |
| New Customers | Integer |
| Unnamed: 8 | Decimal/Float |
| Unnamed: 9 | Decimal/Float |
| Unnamed: 10 | Text |
| Unnamed: 11 | Text |
| Unnamed: 12 | Text |
| Unnamed: 13 | Text |
| Unnamed: 14 | Text |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_XLOOKUP.csv)

### Sheet: 2022
| Column | Type |
|---|---|
| Year | Text |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Decimal/Float |
| Expenses (₹) | Decimal/Float |
| Profit (₹) | Decimal/Float |
| New Customers | Decimal/Float |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_2022.csv)

### Sheet: 2023
| Column | Type |
|---|---|
| Year | Text |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Decimal/Float |
| Expenses (₹) | Decimal/Float |
| Profit (₹) | Decimal/Float |
| New Customers | Decimal/Float |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_2023.csv)

### Sheet: 2024
| Column | Type |
|---|---|
| Year | Text |
| Month | Text |
| Region | Text |
| Product | Text |
| Sales (₹) | Decimal/Float |
| Expenses (₹) | Decimal/Float |
| Profit (₹) | Decimal/Float |
| New Customers | Integer |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_2024.csv)

### Sheet: Pivot Tables
| Column | Type |
|---|---|
| Unnamed: 0 | Text |
| Unnamed: 1 | Text |
| Unnamed: 2 | Text |
| Unnamed: 3 | Text |
| Unnamed: 4 | Text |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview2_Pivot_Tables.csv)

### Sheet: Dashboard
No preview available for this sheet (empty or unreadable).


## Analysis Notes (TODO)
- Key KPIs: e.g., Revenue, Profit, Expenses, Growth %, Customer Segments.
- Top Insights: e.g., Best-performing product/category/region; peak months; cost-saving opportunities.
- Methods Used: Pivot Tables, VLOOKUP/XLOOKUP, INDEX-MATCH, SUMIFS, COUNTIFS, Power Query, Conditional Formatting.


## Dashboard / Charts (TODO)
Add screenshots here (store images in `assets/` and reference like this):

```
![Dashboard Overview](assets/dashboard_overview.png)
```


## Reproducibility (TODO)
- Steps to rebuild the analysis from raw data (if applicable).
- Any assumptions or data cleaning rules (e.g., missing values, date formats).
- Version Info: Excel version, add-ins used (Power Query/Power Pivot).


## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for improvements or bug fixes.


## License
This project is licensed under the MIT License. See the `LICENSE` file (or update this section if you prefer another license).

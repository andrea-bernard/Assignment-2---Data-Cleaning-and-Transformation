# Assignment-2---Data-Cleaning-and-Transformation
Data Cleaning and Transformation
Cleaned a 34-row product dataset in Excel: handled missing values, fixed
inconsistent text, removed duplicates, split/merged columns, and applied
number + conditional formatting.

What was done
1.	Missing values: Price set to `0`.
2.	Inconsistent data : Standardized Product Name casing (`PROPER`) fixed "Electroni" → "Electronics" typo (Find & Replace).
3.	Duplicates : Removed 3 exact duplicate rows.
4.	Split : `Product ID` → `Manufacturing Date` + `Country Code` (Text to Columns; year assumed as 2026).
5.	Merge : `Brand Name` + `Product Name` → `Product Brand`.
6.	Formatting : Price as currency; Manufacturing Date as `dd-mm-yyyy`.
7.	Conditional formatting : data bars on Price; highlight rule for Category = "Electronics".
Tools
Excel — Text to Columns, Remove Duplicates, Find & Replace, Conditional
Formatting , `PROPER`, `DATE`.

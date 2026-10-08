# Assignment - 2
Assignment 2 - Data cleaning and transformation



Steps 

1. Checked the original dataset
- Opened the Excel worksheet and reviewed all columns and records.
- Identified missing values, inconsistent values, and unnecessary columns.
- Reviewed the following columns:
  - Country code
  - Product Name
  - Brand Name
  - Price ($)
  - Quantity
  - Category
  - Column7
  - Month
  - DD-MM-YYYY

 2. Removed unnecessary column
- Identified `Column7` as an unnecessary column.
- Removed `Column7` from the dataset because it contained only `Unknown` values and did not provide useful information.

 3. Cleaned missing values
- Checked the dataset for missing values and values represented as `Unknown`.
- Reviewed the `Brand Name` and `Category` columns for incomplete or unknown entries.
- Replaced or corrected values where the appropriate information was available.
- Ensured that the remaining missing values were handled consistently.

4. Cleaned the Country Code column
- Reviewed the country codes to ensure they followed a consistent two-letter format.
- Examples include:
  - US
  - UK
  - IN
  - AU
  - DE
  - CA
  - ES
  - CN
  - IT
  - RU
  - FR
  - BR

5. Cleaned the Price column
- Checked the `Price ($)` column for numeric values.
- Ensured that prices were stored as numbers rather than text.
- Verified that the dollar values were consistent and suitable for calculations.

6. Cleaned the Quantity column
- Checked the `Quantity` column for numeric values.
- Ensured that quantities were stored as numbers and could be used for calculations and analysis.

7. Standardized Product and Brand names
- Reviewed the `Product Name` and `Brand Name` columns.
- Ensured that product and brand names were consistently formatted.
- Checked for missing brand names and corrected them where possible.

8. Standardized Category values
- Reviewed the `Category` column for inconsistent and `Unknown` values.
- Standardized category names such as:
  - Electronics
  - Fashion
  - Kitchen
  - Outdoor
  - Accessories
- Corrected incomplete category names where required.

9. Cleaned the Month column
- Reviewed the `Month` column.
- Standardized the month values into a consistent format such as:
  - 28-JAN
  - 15-FEB
  - 3-MAR
  - 11-APR
  - 22-MAY
  - 7-JUN

10. Standardized the Date column
- Reviewed the `DD-MM-YYYY` column.
- Converted the date values into a consistent date format.
- Ensured that all dates followed the same `DD-MMM-YYYY` format.
- Examples:
  - 28-JAN-2016
  - 15-FEB-2016
  - 3-MAR-2016
  - 11-APR-2016
  - 22-MAY-2016

11. Checked the final dataset
- Reviewed the cleaned worksheet after making all changes.
- Checked for remaining blank cells, `Unknown` values, inconsistent formatting, and incorrect data types.
- Ensured that the dataset was organized and ready for further analysis.

12. Applied Conditional Formatting
- Applied Conditional Formatting to the `Price ($)` column.
- Used `Data Bars` to visually compare product prices.
- The length of each bar represents the relative price of the product.
- Higher-priced products have longer data bars, making it easier to identify high and low prices quickly.

13. Applied Conditional Formatting to Category
- Applied conditional formatting to the `Category` column.
- Used cell highlighting to make specific category values easier to identify.
- This helps visually distinguish categories such as Electronics, Fashion, Kitchen, Outdoor, and Accessories.



### Final Result

Data Bars were used in the Price column to visually compare prices, while category values were highlighted 
for easier identification. The formatted table is now easier to read, filter, analyze, and interpret.

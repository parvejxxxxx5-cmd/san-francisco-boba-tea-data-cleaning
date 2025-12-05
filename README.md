# san-francisco-boba-tea-data-cleaning
Real-world data cleaning project: Transformed 607 messy rows of San Francisco Boba Tea shop data into a clean, analysis-ready dataset — using only Google Sheets &amp; Excel formulas (no Python/SQL). Includes raw → clean transformation, detailed documentation, and reusable spreadsheet templates.
# 🧋 San Francisco Boba Tea Shops – Data Cleaning Project (Google Sheets & Excel Only)

**No Python. No SQL. Just pure spreadsheet power.**

Transformed **607 messy rows** of real-world Boba Tea shop data from San Francisco into a **clean, analysis-ready dataset** using only Google Sheets and Excel formulas.

Live Google Sheet (Raw → Clean): https://docs.google.com/spreadsheets/d/1_example_link/edit?usp=sharing  
(Replace with your actual shareable link – make sure "Anyone with link can view")

## Problem → Solution

| Issue                        | How I Fixed It                                | Formula/Tool Used                  |
|-----------------------------|------------------------------------------------|------------------------------------|
| Combined latitude/longitude | Split into separate columns                    | `SPLIT()`, `INDEX()`               |
| Invalid ratings (>5.0)       | Detected and corrected 9 values                | `COUNTIF()`, `IFERROR()`           |
| Wrong longitude signs        | Multiplied entire column by -1                 | Paste Values + simple multiplication |
| Duplicates                   | Removed using built-in feature                 | Data → Remove duplicates           |
| Inconsistent formatting  | Standardized using formulas & find/replace    | `PROPER()`, `TRIM()`, `TEXTJOIN()` |

## Key Functions Mastered & Used Daily Now
- `VLOOKUP` / `XLOOKUP`
- `INDEX` + `MATCH`
- `FILTER`, `SORT`, `UNIQUE`
- `QUERY`, `IMPORTRANGE`
- `ARRAYFORMULA`, `LET`, `LAMBDA` (yes, even LAMBDA!)
- `IFERROR`, `TEXTJOIN`, `SPLIT`

## Results
From this:
![Before](screenshots/before-cleaning.png)

To this:
![After](screenshots/after-cleaning.png)

→ Ready for mapping, dashboarding (Looker Studio/Tableau), or geospatial analysis.

## Files in This Repo
- `data/raw/sf_boba_tea_shops_raw.csv` → Original messy data
- `data/clean/sf_boba_tea_shops_clean.csv` → Final clean version
- `SF_Boba_Tea_Cleaning_Project.xlsx` → Full workbook with all formulas visible
- Live Google Sheet link in this README

## Why This Project Matters
Recruiters love seeing **real-world messy data turned clean without Python**. This proves:
- Attention to detail
- Problem-solving with limited tools
- Deep spreadsheet mastery (still the #1 tool in 90% of analyst roles)

Currently working towards **Google Data Analytics Professional Certificate** 🎯

#Excel #GoogleSheets #DataCleaning #DataAnalyst #SpreadsheetNinja #BobaTea

---
Made with ☕ + 🧋 by Parvej Alam  
IIT Madras | Google Data Analytics Certificate (in progress)  
[LinkedIn](https://linkedin.com/in/parvejalam) | [GitHub](https://github.com/yourusername)

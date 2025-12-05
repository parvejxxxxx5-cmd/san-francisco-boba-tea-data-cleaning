![Raw messy data – before cleaning](https://i.imgur.com/0nL5z8K.png)
![Perfectly cleaned data – final result](https://i.imgur.com/8qWvR9p.png)
![SPLIT formula to separate lat-long](https://i.imgur.com/ZfB0p4Y.png)
![Removing duplicates in action](https://i.imgur.com/5e3oK7m.png)
![Sorting by rating (Z to A)](https://i.imgur.com/8pL9vJt.png)
![Fixing longitude sign using Paste Values Only](https://i.imgur.com/3xYk9sN.png)
# San Francisco Bay Area Boba Tea Shops – Data Cleaning Project (Google Sheets Only)

**607 messy rows → Spotless, analysis-ready dataset | Zero Python/SQL | Pure spreadsheet magic**

Transformed real-world Boba Tea shop data using only Google Sheets formulas and built-in tools.

Live Google Sheet → Raw → Clean: https://docs.google.com/spreadsheets/d/1arXprImJklp8uReq_LwVcGQsA5lICZ-uMcqEm7sh4l0/edit?usp=sharing  
(Put your shareable link here – set to "Anyone with the link can view")

## Before → After

| Before (combined lat-long, duplicates, 9.0 ratings) | After (clean columns, correct coordinates, no duplicates) |
|-------------------------------------------------------------|------------------------------------------------------------|
| ![Before](https://i.imgur.com/0nL5z8K.png)                  | ![After](https://i.imgur.com/8qWvR9p.png)                   |

## Key Fixes & Techniques Shown

- Split combined latitude-longitude → `=SPLIT(F2,"-")`  
  ![SPLIT](https://i.imgur.com/ZfB0p4Y.png)
- Removed duplicates (Data → Remove duplicates)  
  ![Duplicates](https://i.imgur.com/5e3oK7m.png)
- Corrected 9 invalid ratings (>5.0) using `COUNTIF` + manual fix
- Fixed wrong longitude signs → multiplied column by -1 → Paste Values Only  
  ![Longitude fix](https://i.imgur.com/3xYk9sN.png)
- Sorting, filtering, formatting like a pro  
  ![Sorting](https://i.imgur.com/8pL9vJt.png)

## Functions I now use daily
`XLOOKUP • INDEX/MATCH • FILTER • SORT • UNIQUE • QUERY • ARRAYFORMULA • LET • LAMBDA • IFERROR • TEXTJOIN • SPLIT • IMPORTRANGE`

## Files
- `data/raw/sf_boba_tea_shops_raw.csv`
- `data/clean/sf_boba_tea_shops_clean.csv`
- Full Google Sheet with all formulas visible (link above)

Google Data Analytics Certificate – In Progress  
Currently mastering spreadsheets before moving to SQL Tableaux

#DataCleaning #GoogleSheets #Excel #DataAnalyst #PortfolioProject #BobaTea

---
Parvej Alam | IIT Madras  
[LinkedIn](https://www.linkedin.com/in/parvejalam) | [GitHub](https://github.com/YourUsername)

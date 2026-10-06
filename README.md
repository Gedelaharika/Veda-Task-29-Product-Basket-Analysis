# Veda Task 29 - Product Basket Analysis

## Objective
To identify products that are frequently purchased together and provide business recommendations based on product basket patterns.

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset
Online Retail II Dataset - Year 2009-2010

## Data Preparation
The following cleaning steps were performed:
- Removed records with missing Customer ID
- Removed cancelled invoices
- Checked invalid quantities
- Removed missing product descriptions
- Removed duplicate product entries within the same invoice

## Analysis
Products were grouped by Invoice ID to identify products purchased together.

Product combinations were generated using pairs of different products, excluding self-pairs.

## Results

- Total Invoices Analyzed: 19,215
- Unique Product Pairs Found: 2,363,449

### Top 10 Product Pairs

| Rank | Product 1 | Product 2 | Purchase Count |
|---|---|---|---:|
| 1 | RED HANGING HEART T-LIGHT HOLDER | WHITE HANGING HEART T-LIGHT HOLDER | 722 |
| 2 | STRAWBERRY CERAMIC TRINKET BOX | SWEETHEART CERAMIC TRINKET BOX | 622 |
| 3 | WOODEN FRAME ANTIQUE WHITE | WOODEN PICTURE FRAME WHITE FINISH | 554 |
| 4 | HOME BUILDING BLOCK WORD | LOVE BUILDING BLOCK WORD | 522 |
| 5 | HEART OF WICKER LARGE | HEART OF WICKER SMALL | 491 |
| 6 | 60 TEATIME FAIRY CAKE CASES | PACK OF 72 RETRO SPOT CAKE CASES | 478 |
| 7 | 60 TEATIME FAIRY CAKE CASES | PACK OF 60 PINK PAISLEY CAKE CASES | 468 |
| 8 | LUNCH BAG SPACEBOY DESIGN | LUNCH BAG SUKI DESIGN | 454 |
| 9 | WHITE HANGING HEART T-LIGHT HOLDER | WOODEN FRAME ANTIQUE WHITE | 442 |
| 10 | PACK OF 60 PINK PAISLEY CAKE CASES | PACK OF 72 RETRO SPOT CAKE CASES | 409 |

## Recommendations

1. Create bundle offers for products frequently purchased together.
2. Use cross-selling recommendations at checkout based on common product pairs.
3. Place frequently paired products near each other in the online store.
4. Offer discounts on complementary products to increase basket size.
5. Promote popular product combinations through email and marketing campaigns.

## Key Insight
The most frequently purchased product pair was RED HANGING HEART T-LIGHT HOLDER and WHITE HANGING HEART T-LIGHT HOLDER, which appeared together in 722 invoices.

## Conclusion
Product basket analysis helps identify purchasing patterns and can support bundle creation, cross-selling, product placement, and targeted marketing strategies.
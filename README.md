# India E-Commerce Sales Analysis

## Overview
Analysis of 1,400+ Amazon product listings to answer 7 business questions
around pricing, discounting, and customer satisfaction strategy.

## Business Questions Answered
1. Does higher discount = higher rating?
2. Which categories are over-discounted but under-rated?
3. Which categories drive the most engagement?
4. Which category has the best price-to-rating ratio?
5. Do more expensive products get rated higher?
6. What discount threshold maximises customer rating?
7. Which categories have the highest rating consistency?

## Dataset
- Source: Amazon Sales Dataset — Kaggle (karkavelraja)
- Rows: ~1,400 products
- Categories: 9
- Total reviews analysed: 23.6M+

## Tools Used
- Microsoft Excel — data cleaning, calculated columns, pivot tables, charts

## Key Findings
1. Low-discount products (<20%) rate highest at 4.16 vs 4.06
   for heavily discounted ones — discounting more does not earn trust
2. Car&Motorbike: 42% avg discount but lowest rating (3.8)
   — most over-discounted, under-rated category
3. Electronics drives 59% of all reviews but ranks mid-table
   on rating — massive reach, unmet expectations
4. Toys&Games delivers best price-to-rating ratio (34.9)
   Electronics worst (2,513) — highest cost, average satisfaction
5. Price barely predicts rating — Luxury scores only 0.09pts
   higher than Budget products
6. Rating peaks at 0-10% discount (4.21) and falls to 4.02
   at 70%+ — optimal discount range is under 20%
7. OfficeProducts wins on quality AND consistency — highest
   rating (4.31) with lowest standard deviation (0.15)

## Files
- amazon_project.xlsx — cleaned dataset with pivot tables and charts

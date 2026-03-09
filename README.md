# Ames Housing Sale Price Analysis

**Author:** Christina Craig  
**Tools:** Python · pandas · NumPy · Matplotlib · Seaborn  
**Dataset:** Ames Housing Dataset (2006–2010, Ames, Iowa)

---

## Overview

This project uses descriptive statistics and data visualization to explore what factors influence home sale prices in Ames, Iowa. The dataset contains 1,460 home sales recorded between 2006 and 2010, with 80 features covering physical characteristics, condition ratings, and sale details.

The analysis focuses on four key questions:

1. How is sale price distributed across the dataset?
2. Do different foundation types correlate with different price ranges?
3. How strongly does lot size correlate with sale price?
4. Does combining lot size with above-ground living area improve that correlation?

---

## Key Findings

- **Sale prices are right-skewed**, with most homes selling in the $100k–$200k range. The mean (~$180,921) is pulled upward by a small number of high-value outliers.
- **Foundation type clusters by price range.** Concrete block and brick & tile foundations are the most common in Ames, likely because the soil depth and water table support traditional dug foundations. Poured concrete foundations tend to appear at higher price points.
- **Lot area alone has a weak positive correlation with sale price** (r = 0.264). Large lots do not reliably command higher prices — location and condition matter far more.
- **Combining lot area with above-ground living area** into a single engineered feature (`Lot_and_House`) only slightly imp

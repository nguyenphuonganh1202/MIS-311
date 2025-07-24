# 🥿 Project: Predicting Shoe Price from Shoe Attributes

## 📌 Context and Objective  
This project analyzes how various shoe attribute such as brand, color, and size affect the price of shoes. The goal is to uncover pricing patterns and brand positioning based on descriptive statistics, helping support decisions in pricing strategy, product planning, and retail analysis.

## 📊 Dataset Overview  
The dataset includes the following variables:

<img width="544" height="324" alt="image" src="https://github.com/user-attachments/assets/40fbd0d3-c7c7-406d-a8b7-efc826788b07" />

- **Price** *(numeric)*: Final selling price of the shoe (dependent variable).  
- **Brand** *(categorical)*: Shoe brand (e.g., Crocs, Toms, Nike).  
- **Color** *(categorical)*: Color of the shoe.  
- **Size** *(numeric)*: Shoe size (e.g., 2.0, 3.0).  

## 🔍 Summary Statistics  

| Statistic     | Value     |
|---------------|-----------|
| Mean Price    | 212.92    |
| Median Price  | 214.00    |
| Mode Price    | 347.00    |
| Min Price     | 80.00     |
| Max Price     | 350.00    |

### 📈 Brand-wise Average Prices

| Brand         | Average Price |
|---------------|----------------|
| Toms          | 129.00         |
| FILA          | 160.83         |
| Vanilla Moon  | 164.50         |
| Nike          | 168.00         |
| Lavie         | 172.00         |

These numbers show that **Toms** has the most budget friendly options, while **Nike** and **Lavie** are in the mid-range segment.

## 🧠 Insights  

- **Brand** has a strong influence on pricing.  
- **Size** is relatively constant across the dataset, and likely does not affect price.  
- **Color** variation was not analyzed quantitatively but may be explored in future versions.

## ✅ Conclusion and Implications

This analysis reveals that **brand identity is the most influential factor** in determining shoe price among the given variables. 

- **Toms** positions itself as the most affordable brand, while **Nike** and **Lavie** are in the mid-range segment.
- **Shoe size** shows little variation, suggesting it has minimal pricing impact.
- **Color** may influence consumer perception, though further analysis is required.

**Implications for Retailers:**
- Use brand-based pricing insights to optimize pricing strategies.
- Target promotional efforts by brand segment (e.g., discount high-priced brands to boost volume).
- Monitor pricing benchmarks to avoid underpricing or overpricing compared to competitors.

For deeper insights, regression models or clustering techniques could be implemented in future analysis.





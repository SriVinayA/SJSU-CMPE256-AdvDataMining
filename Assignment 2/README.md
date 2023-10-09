## Starbucks Hot Beverages Sales Analysis

### Objective
A newly opened Starbucks coffee shop manager aims to increase customer loyalty. To achieve this, the manager collected data on the sale of hot beverages at popular times on a typical Wednesday, with the goal of offering sales coupons based on visit times.

### Dataset Description
- **PTIndex:** Popular Times Index, ranging from 1 (6am-7am) to 11 (8pm-9pm).
- **HBIndex:** Hot Beverages index, ranging from 1 (Coffee type 1) to 9 (Coffee Of the Day).

### Analysis Steps

1. **Data Exploration & Cleaning:** Loaded the dataset and structured it to isolate the relevant sales data.
2. **Data Aggregation:** Aggregated the sales data by the "PTIndex" to determine the total sales for each time slot.
3. **Data Visualization:** Visualized the sales distribution across time slots, identifying PTIndex 3 as notably popular.
4. **Hierarchical Clustering:** Applied hierarchical clustering using three different linkage methods:
   - Single Linkage
   - Complete Linkage
   - Average Linkage

### Key Insights

- **PTIndex 3 (Late Morning):** Identified as the most popular time based on sales data.
- **Beverage Preferences:** "Café Americano" and "Café Mocha" were notably popular during the most popular time slots.
- **Clustering Results:**
  - **Single Linkage:** Produced two clusters, recognizing PTIndex 3 as distinctively popular.
  - **Complete Linkage:** Divided the time slots into three clusters, offering a more granular view.
  - **Average Linkage:** Provided even more granularity with four clusters, still highlighting PTIndex 3's distinct popularity.

### Recommendations

1. Offer coupons during the late morning rush to capitalize on the peak crowd.
2. Promote popular beverages like "Café Americano" and "Café Mocha" alongside the coupon offers.
3. Consider gathering more extensive data for more robust insights and tailor promotions based on specific days and customer preferences.

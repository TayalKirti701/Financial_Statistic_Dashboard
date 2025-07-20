# Financial_Statistic_Dashboard


# Dynamic Dashboard Analysis for Income Sources and Profits by Country

## Overview
This project consists of two interactive and visually appealing dashboards that analyze income sources and profits by country. Both dashboards are dynamic, controlled by a year-selection slicer to allow filtering and customization of the data for different years.

---

## Dashboard 1: Income Sources Analysis
![Income Sources][https://github.com/TayalKirti701/Financial_Statistic_Dashboard/tree/main/Images/Income_Sources.png](https://github.com/TayalKirti701/Financial_Statistic_Dashboard/blob/main/Images/Income_Source.png)]
### Features:
1. **Dynamic Web Chart for Income Sources**:
   - A detailed analysis of all income sources based on the "Income sources" and "Income Breakdowns" columns.
   - Displays the percentage of each income source using "Counts".
   - Highlights the source with the highest value in the "Income" column.

2. **Creative Doughnut Chart**:
   - Visualizes the achieved percentage of income against the "Target Income" column.

3. **Title and Description**:
   - A clear, descriptive title and accompanying description explaining the purpose of the dashboard.

4. **Key Metrics**:
   - Displays the total income amount and the target value based on the "Income" and "Target Income" columns.

5. **Line Chart**:
   - Visualizes income trends by months using the "Month" and "Income" columns.

6. **Income Sources Summary**:
   - Displays the total count and percentage breakdown of income source items using the "Counts" column.

7. **Average Monthly Income**:
   - Calculates and displays the average income per month using the "Income" column.

8. **Bar Chart**:
   - Shows monthly operating profits and the total profit amount using the "Operating profit" column.

9. **Marketing Strategies Analysis**:
   - Compares and analyzes the performance of two marketing strategies using the "Marketing Strategies" column.

10. **Dynamic Yearly Control**:
    - All charts and metrics are controlled by a year-selection slicer to enable interactive filtering using the "Year" column.

---

## Dashboard 2: Profit Analysis by Country

### Features:
1. **Dynamic Map Chart**:
   - A visually engaging map that dynamically displays profits by country using the "Country" and "Amount" columns.

2. **Profit Analysis**:
   - Highlights the profit value from each country using the "Amount" column.
   - Clearly identifies the most profitable country with distinct visuals.

3. **Tax Details**:
   - Provides detailed insights into various types of taxes affecting profits.

4. **Creative Doughnut Chart**:
   - Visualizes the percentage of profits achieved with a modern, circular-edge design using the "Amount" and "Target" columns.

5. **Dynamic Yearly Control**:
   - The map and all associated metrics update based on the selected year in the slicer using the "Year" column.

---

## Development Steps:
1. **Data Preparation**:
   - Use the "Data Tables" sheet for the dataset, which includes columns for income sources, monthly income, operating profits, marketing strategies, country-wise profits, and targets.
   - Ensure the data includes a "Year" column for filtering.

2. **Dynamic Filtering**:
   - Implement a slicer feature to enable year-based filtering.

3. **Chart Types**:
   - Leverage doughnut charts, line charts, bar charts, and map visualizations.
   - Use creative design techniques for an engaging UI/UX.
  
4. **Pivot Table**:
    - Explore income by source, month, strategy with aggregation and drill-down
    - View profit summaries by year and country

4. **Calculations**:
   - Perform required calculations for percentages, averages, and totals dynamically in the tool or backend.

---

## Code Structure

- **Components**:
  - Yearly Slicer
  - Dynamic Charts (Doughnut, Line, Bar, Map)
  - KPI Cards (Total Income, Target, etc.)


## 🛠 Installation

### 1. Clone or Download the Project Files:
If using Git:
```bash
git clone https://github.com/TayalKirti701/Financial_Statistic_Dashboard.git
```

Or manually download .xlsx file from repository

### 2. Open the Dashboard Files:
  **Open these sheets in Microsoft Excel**
  - Income Sources
  - Geographically


---


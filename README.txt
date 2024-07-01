# Annual Bonus Analysis

![Tableau](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/Tableau_Logo.png/320px-Tableau_Logo.png)

## Overview

The Annual Bonus Analysis project aims to determine which employees are eligible for bonuses based on their performance. We have a small dataset containing information about employees, including order details, regions, representatives, items sold, units, and unit prices. By analyzing this data in Tableau, we can identify top performers and allocate bonuses accordingly.

## Dataset

The dataset consists of the following columns:

- `OrderDate`: Date of employee orders
- `Region`: Employee region (East, West, or Central)
- `Rep`: Representative name
- `Item`: Item sold by the employee
- `Units`: Number of units sold
- `Unit Price`: Price of each unit

## Project Steps

1. **Data Preparation in Tableau**:
   - Import the CSV file into Tableau.
   - Arrange the data by adding the `Region` and `Rep` columns to the Columns shelf.

2. **Calculating Revenue**:
   - Create a calculated field to compute the revenue for each employee:
     ```
     Total_Revenue = Units * Unit Price
     ```

3. **Visualizing Total Revenue**:
   - Add the new data measure "Total Revenue" to the Rows shelf.
   - Create a graph to visualize revenue across all employees.

4. **Region-Specific Analysis**:
   - Divide the data by region to determine bonuses for each region.
   - Color-code each region differently for clarity.

5. **Ranking Employees**:
   - Order the data in the chart in ascending order to highlight top performers within each region.

## Usage

1. Clone this repository.
2. Install Tableau (if not already installed).
3. Open the provided CSV file in Tableau.
4. Follow the steps outlined above to analyze the data and make informed decisions about bonuses.

## Limitations

- The analysis is based solely on the provided dataset. Consider additional factors (e.g., tenure, customer satisfaction) for a more comprehensive bonus allocation.

## Future Enhancements

- Explore interactive dashboards to allow stakeholders to explore the data further.
- Incorporate feedback from managers or HR to fine-tune bonus criteria.

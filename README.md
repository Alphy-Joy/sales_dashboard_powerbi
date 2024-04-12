
# E-commerce Sales - Dashboard


## Problem Statement


This dashboard provides users with insights into their sales performance. It shows the total profit generated over three years, the average shipping time, and the total sales volume. Using a bar graph, sales figures are presented by month.

The top 5 best-selling products are highlighted, and sales locations are displayed on a map. Payment method usage is visualized through pie charts, as well as the most profitable sales channels.

For detailed analysis by year, slicers for 2021, 2022, and 2023 are available. Additionally, users can filter products by categories using the category-wise slicer.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is an excel file and json file for location.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Removed the unwanted columns.
- Step 5 : Added new columns for sales amount,cost amount,profit and shipping days and calculated them respectively.
- Step 6 : In the model view, 1 to Many relationship  was established bewteen Product and sales table and also bewteen in and sales table.
- Step 7 : In report view,canvas background and  tilte of the dashboard was added
- Step 8 : Three card visuals were added to the canvas, one representing Total sales, other representing Total profit and the final one representing Average Shipping Days.

![cards](https://github.com/Alphy-Joy/sales_dashboard_powerbi/assets/52252867/fc7058b5-2402-4bf7-88ff-eea402f2dc9a)

- Step 9 : A pie chart was added to visualize the payment methods and a donut chart was added to represent the profit channels. 

![pie_donut](https://github.com/Alphy-Joy/sales_dashboard_powerbi/assets/52252867/a7cc1989-b97b-4683-b134-ea4a75a3d1ef)


- Step 10 : Using a stacked bar chart top 5 selling products are shown and a stacked column chart is used to represent the sales amount by month. 

![bar_column](https://github.com/Alphy-Joy/sales_dashboard_powerbi/assets/52252867/da3ec68e-890c-44cb-8a42-7d31f307dde9)

- Step 11 : A map is included in the dashboard to visualize the sales by states.
- 
![states](https://github.com/Alphy-Joy/sales_dashboard_powerbi/assets/52252867/2f483607-7445-43e8-ace6-a5e8c45c03da)

- Step 12 : Visual filters (Slicers) were added for  "Years", & "category".
![slicers](https://github.com/Alphy-Joy/sales_dashboard_powerbi/assets/52252867/090e9ef7-ee0c-4dde-bef5-8cde99fc724e)
  
 # Snapshot of the Dashboard(Power BI Desktop)       


![dashboard](https://github.com/Alphy-Joy/sales_dashboard_powerbi/assets/52252867/c60bf3f2-15ab-4009-b116-b4eeacce7f39)

   

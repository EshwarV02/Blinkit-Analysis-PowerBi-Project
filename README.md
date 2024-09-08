 # Blinkit-Analysis-PowerBi-Dashboard

## Problem Statement

This dashboard helps Blinkit a online grocery delivery platform that operates on a marketplace business model to  understand their business and their customers better.It helps the company to better know about their total sales, their average sales  which helps them to get better understanding about their business and also  insights to make better decesion in order to make the busniness run well. The dasboard  also helps the company to know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these areas be it the quality of the item, delivery time, behavioral issues, leading towards customer satisfaction. Since by using this dashboard they have identified this problem, they can further work on factors responsible for making growth and better their margins.

Since, average customers  rating is 3.9, they must work on improving their services. 

## Business Requirement: Chart Requirements
1. Total Sales by Fat Content
Objective: Analyze the impact of fat content on total sales.
Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary by fat content.
Chart Type: Donut Chart.

2. Total Sales by Item Type
Objective: Identify the performance of different item types in terms of total sales.
Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary by item type.
Chart Type: Bar Chart.

3. Fat Content by Outlet for Total Sales
Objective: Compare total sales across different outlets segmented by fat content.
Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary by outlet and fat content.
Chart Type: Stacked Column Chart.

4. Total Sales by Outlet Establishment
Objective: Evaluate how the age or type of outlet establishment influences total sales.
Chart Type: Line Chart.
Sales by Outlet Size
Objective: Analyze the correlation between outlet size and total sales.
Chart Type: Donut/Pie Chart.

5. Sales by Outlet Location
Objective: Assess the geographic distribution of sales across different locations.
Chart Type: Funnel Map.

6. All Metrics by Outlet Type
Objective: Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, Average Rating) broken down by different outlet types.
Chart Type: Matrix Card

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : To solve this the error values where removed 
- Step 6 : Null values, were checked filling it in cases where it was making a difference
 Step 7: A rounded rectangle was used to create a design that can be used for company logo and tagline 
- Step 8 : In the report view, under the insert tab, two text box were added to the canvas, in one of them name of the company was
mentioned & in the other one company's tagline was written.


![Snap](https://github.com/user-attachments/assets/8f9d646d-071d-4bfe-b1eb-6ef0444e0861)
- Step 9: After desgining the rounded rectangle another card was created beside it having 2 rows and 2 columns 
- Step 10 : Created 4 KPI's using DAX which helped us to create measures 
a ) Total sales

b) Avg sales

c) Total items 

d) Avg customer rating 

# Measures
 Metrics = {

("Total Sales", NAMEOF('BlinkIT Grocery Data'[Total Sales]), 0),

("Avg Sales", NAMEOF('BlinkIT Grocery Data'[Avg Sales]), 1),

("No  of Items", NAMEOF('BlinkIT Grocery Data'[No  of Items])2),

("Avg Rating", NAMEOF('BlinkIT Grocery Data'[Avg Rating]), 3)
}

# Snap of KPI's
![Snap2](https://github.com/user-attachments/assets/144c87ca-a343-4192-a593-2fc581155ba1)

- Step 11: After designing the cards for Kpi's, created another rounded rectangle in which 4 charts were to be made
- Step 12: First Chart was a donut chart that was used to determine the total fat content in the items that were ordered where regular or high. 
- Step 13: Created a clustered Bar chart to determine the amount of fat in the product that was delivered from each outlet.
- Step 14: Also made a stacked column chart to determinr different types of items which were delivered to their customers holded how much amount of the total sales.
- Step 15: Created a slicer to easily toggle between the KPI'S
- Step 16: Selected another rounded rectangle for more different charts.
- Step 17: Created a Line chart to determine the developent each outlet made since it was started through each year from 2012 - 2022
- Step 18: Copy pasted the donut chart made earlier by using different values to it for detemining Outlet Size in terms of sales, ratings bifurcated in 3 different types
- Step 19: A matrix card was created to determine outlet type with different values to the outlet type as column 
- Step 20: Finally the last step was to add slicers to next to the logos to easily get insights.

  
![Snap3](https://github.com/user-attachments/assets/219499ca-a65f-4a69-9d6c-8f05c2c34715)



## Final Screenshot

![Screenshot](https://github.com/user-attachments/assets/8aa5b972-848c-47ee-ad12-2ce570dc72d9)



    
        

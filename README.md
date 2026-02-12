PART 1: Launching Power BI & Loading Data 
Step 1: Open Power BI Desktop 
● Click Start 
● Open Microsoft Power BI Desktop 
● Wait for the startup screen 
Step 2: Load the Dataset 
1. Click Home Tab 
2. Click Get Data 
3. Select Text/CSV
4. Browse and select: 
Week1_Basic_Sales_Data.csv 
5. Click Load 
Step 3: Verify Data in Data View 
1. Click the Data View icon (table icon on the left) 
2. Check: 
○ Are all columns visible?  Yes, all columns are visible. 
○ Is “Date” formatted as Date? Yes, but it was set long date format
○ Is “Sales” formatted as Decimal Number? Yes Sales was formatted as decimal.
If Data Type is Incorrect: 
1. Click the column 
2. Go to Column Tools 
3. Change Data Type accordingly: 
○ Date → Date 
○ Sales → Decimal Number 
○ Product/Category/Region → Text 
PART 2: Exploring the Interface 
View 
Purpose
Report View 
Create dashboards and visuals
Data View 
See raw data
Model View 
Manage relationships



Switch back to Report View. 
PART 3: Creating Auto-Generated Visuals 
Step 1: Quick Visualization 
1. Drag Sales into canvas 
2. Power BI automatically creates a visual 
Question: 
● What type of chart was created? It generated a column chart with one bar.
● What does it show?  It shows the total (Sum) of Sales for the entire dataset. Since no category field was added, Power BI aggregated all sales values together and displayed them as a single bar representing the overall sales amount.
Step 2: Create a Sales by Region Chart 
1. Click blank canvas 
2. Select Clustered Column Chart
3. Drag: 
○ Region → X-axis 
○ Sales → Values 
Question: 
● Which region has highest sales?  West Region has the highest sales,
Step 3: Sales by Category 
1. Insert a Pie Chart 
2. Drag: 
○ Category → Legend 
○ Sales → Values 
Question: 
● Which category dominates? The electronics category dominates the whole pie chart. 
● Is the distribution balanced? No, the distribution is not balanced.
Step 4: Sales Over Time 
1. Insert Line Chart 
2. Drag: 
○ Date → X-axis 
○ Sales → Values 
Question: 
● Is there growth? No,because the sales are decreasing. 
● Any noticeable trend? Yes, there's a clear downward trend.
PART 4: Basic Data Insight Interpretation Students must now interpret visuals. 
Question: 
● Which region contributes most revenue?  The West Region contributes the most revenue.
● Which product category performs best? The electronics category perform best.
● Are sales consistent across dates? No, sales are not consistent. The line chart shows that sales decreased from 2024 to 2025, indicating a downward trend.
● What business recommendation can you suggest? A good business recommendation is to focus on improving sales in lower-performing regions like North and investigate the decline in 2025 while continuing to invest in the high-performing Electronics category.

LABORATORY QUESTIONS 
Part A – Technical Questions 
1. What are the five columns in the dataset? The five columns in the dataset are Sales, Region, Category, Year, and Product.
2. What data type is assigned to the “Sales” column? >The Sales column is a numeric (decimal number/currency) data type. 
 3. Which Power BI view allows you to see raw data?
>The Data View allows me to see raw data.
4. What chart type is best for showing trends over time? 
>A Line Chart is best for showing trends over time.
5. What aggregation is automatically applied to Sales?
>Power BI automatically applies Sum aggregation to the Sales field.
Part B – Analytical Questions 
6. Which region has the highest total sales? The West Region has the highest total sales.
7. Which category has the lowest performance? The Office Supplies category has the lowest performance.
8. Are sales increasing, decreasing, or stable? Sales are decreasing (from 2024 to 2025).
9. If you were a manager, which region would you prioritize?
> I would prioritize the North Region, since it generates the lowest revenue and has room for improvement.
10. Provide one actionable recommendation based on the data. 
>One actionable recommendation is to implement targeted promotions in the North region to increase revenue.
ENHANCEMENT SECTION 
Advanced Exploration 
Students must perform the following: 
Task 1: Add a Card Visualization 
1. Insert Card 
2. Drag Sales 
3. Format: 
○ Increase font size 
○ Change title to “Total Sales” 
Question: 
● What is the total sales amount? 220K is the total sales.
Task 2: Add Slicer 
1. Insert Slicer 
2. Drag Region 
3. Test filtering 
Question: 
● What happens to other visuals when you click a region? > When you click a region, all the other visuals on the report automatically update to display data only for the selected region.
● Why is filtering important in BI? 
>Filtering is important in Business Intelligence because it allows users to focus on specific data segments, making analysis more detailed, relevant, and easier to interpret for better decision-making.
Task 3: Sort Sales 
1. Click Region Chart 
2. Click three dots (…) 
3. Sort by Sales Descending 
Question: 
● Does sorting improve readability? Yes, sorting improves readability because it arranges the regions from highest to lowest sales, making it easier to quickly identify the top- and lowest-performing regions.
● Why? Sorting helps because it allows users to compare values more clearly and detect differences at a glance without confusion.
Task 4: Identify Outliers 
● Which region is significantly higher or lower? The North region is significantly lower compared to the other regions.
● What might explain that difference? This difference might be explained by lower customer demand, fewer sales opportunities, weaker marketing efforts, or a smaller market size in that region.

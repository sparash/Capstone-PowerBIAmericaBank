# Capstone-Project 2

Please find below Capstone Project 2:

 

Dataset: Please fetch the dataset from the attached file in this email or download it from attached files or from here!

Objectives:

·         Load and clean the datasets in Power BI.

·         Create relationships between the datasets.

·         Create new measures and quick measures using DAX.

·         Visualize the sales performance against targets.

·         Analyze the data to gain insights into branch performance and manager efficiency.

Steps:

1.       Load Data into Power BI:

o    Open Power BI Desktop.

o    Load the datasets: Branch Data, Daily Sales Target, Sales Data, and Target Data.

o    Ensure that the datasets are correctly imported and visible in the Data view.

2.       Data Cleaning and Transformation:

o    In the Power Query Editor, check for and handle any missing values or duplicates in each dataset.

o    Format the Date column in the Sales Data dataset to ensure it's recognized as a date type.

o    Create a new column in the Sales Data table to extract the day from the Date column (optional, if needed for analysis).

3.       Create Relationships:

o    Go to the Model view.

o    Create relationships between the datasets:

§  Connect Branch in the Sales Data table to Branch in the Branch Data table.

§  Connect Pizza Type in the Sales Data table to Pizza in the Target Data table.

§  Connect Date in the Sales Data table to Day in the Daily Sales Target table.

4.        Visualizations:

o    Branch Performance Dashboard:

§  Create a table visual showing Branch, Manager, and Manager Location from the Branch Data table.

§  Add a bar chart to show the total sales by each branch using Branch and the new measure [Total Sales].

o    Daily Sales Target:

§  Create a line chart to compare the daily sales against the daily targets. Use Date from the Sales Data table, the new measure [Total Sales] for sales, and Target from the Daily Sales Target table.

o    Pizza Sales vs. Target:

§  Create a clustered column chart to show the sales quantity for each pizza type against the sales target. Use Pizza Type from the Sales Data table, the new measure [Total Quantity Sold], and Sales Target from the Target Data table.

o    Time Analysis:

§  Create a pie chart or donut chart to show the distribution of sales across different time ranges using Time Range and the new measure [Total Sales].

5.       Analysis and Insights:

o    Add cards to display key metrics such as [Total Sales], [Total Quantity Sold], and [Average Sales per Day].

o    Use slicers to filter data by Branch, Manager, and Pizza Type to analyze specific segments of the data.

o    Create a matrix visual to show the sales performance of each branch by manager.

6.       Formatting and Customization:

o    Customize the visuals with appropriate titles, labels, and colors for better readability.

o    Ensure the dashboard is user-friendly and interactive by enabling drill-throughs and tooltips.

7.       Publish and Share:

o    Save your Power BI report.

o    Publish the report to the Power BI Service.

Deliverables:

Please share Power BI report file (.pbix) containing the cleaned data, relationships, new measures, and visualizations latest by 6:00 PM today.
A dashboard summarizing key insights and performance metrics.

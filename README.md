# Marketing Campaign & Customer Analysis 📊

🚀 The Challenge

The marketing team was struggling to correlate campaign costs with actual revenue using static Excel sheets. They lacked visibility into which customer demographics were actually driving sales, leading to inefficient budget allocation.

💡 The Solution

I built a centralized Power BI analytical suite comprising two dashboards: Customer Segmentation and Campaign Performance. The solution ingests data from Excel, transforms it via Power Query, and utilizes complex DAX measures to calculate real-time ROI.

🔍 Dashboard 1: Customer Segmentation

Goal: Understand who our best customers are.

Key Insights:

Income vs. Status: Identified that while "PhD" holders earn more on average, the "Married" segment drives the highest total volume of sales.

Product Preferences: The heatmap revealed a strong correlation between the "Single" status and "Electronics/Gadgets" purchases (simulated data).

Demographic Filtering: Enabled dynamic slicers (Age 24-80) allowing the team to isolate specific generations (Gen Z vs. Boomers).

📈 Dashboard 2: Campaign ROI Tracker

Goal: Track where the money is going and what brings it back.

Key Features:

Real-time ROI: Calculated that revenue is currently ~3x the campaign cost.

Smart Narratives: Implemented dynamic text boxes that automatically generate sentences like "Families with no children responded better to the campaign" based on the underlying data context.

Success Rate KPI: A visual gauge showing a 15.10% conversion rate against the 20% target.

🛠️ Technical Implementation Details

Data Modelling: Built a Star Schema model to ensure high performance and correct filtering direction.

DAX Measures: Used CALCULATE, DIVIDE (for safe division), and Time Intelligence functions to compare performance periods.

UX/UI: Designed with a consistent color palette and "Card" visuals for immediate readability on mobile devices.



📥 Try it yourself

You can inspect the data model and DAX measures by downloading the source file below.
(Note: Data has been download from open source)
[Download .pbix file](./Marketing_Campaign.pbix)

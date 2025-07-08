COVID 19 Data Analysis


Problem Statement
Public health authorities and researchers need a clear, data driven picture of how COVID 19 spread around the globe, how quickly recoveries occurred, and how fatality rates evolved. Raw daily case counts exist, but they are fragmented across multiple files and noisy. This project consolidates, cleans, and visualises those data so that trends are immediately interpretable by policy makers and citizens alike.




Objectives


•	Aggregate worldwide time series data (confirmed, deaths, recovered) into a tidy, country level format.
•	Visualise pandemic growth, recoveries, and mortality with intuitive charts (line plots, stacked areas, heatmaps).
•	Compare the trajectories of selected countries side by side.
•	Export cleaned datasets and high resolution images for reuse in reports, dashboards, or presentations.




Requirements


•	Johns Hopkins University CSSE time series (confirmed, deaths, recovered) in CSV format.
•	Python 3.7 +, 2 GB RAM minimum.
•	pandas, numpy, matplotlib, seaborn (all installable via pip).
•	Jupyter Notebook, Google Colab, or VS Code with Python extension.
	
	
	
	
	
Tools Used


•	Python 3.x – data wrangling & scripting
•	Pandas + NumPy – tabular manipulation & aggregation
•	Matplotlib – publication quality plotting
•	Seaborn – statistical plots & heatmaps
•	Jupyter Notebook  – interactive analysis environment






Step by Step Process
1.	Project Setup
Begin by preparing your working environment. Install all necessary Python libraries and set up your workspace using a tool like Jupyter Notebook, Google Colab, or VS Code.
2.	Data Acquisition
Obtain the latest COVID-19 time-series datasets from Johns Hopkins University GitHub repository. Download the files for confirmed cases, deaths, and recoveries.
3.	Load Data
Import the datasets into your environment. Ensure all files are read correctly and are ready for processing.
4.	Clean and Aggregate
Process the data by grouping it by country to consolidate information. Remove irrelevant columns such as latitude and longitude. Then, reformat the data so that dates become the index, and ensure the date format is consistent and usable for plotting.
5.	Visualize Global Trends
Create a line chart showing the global progression of confirmed cases, recoveries, and deaths over time. This offers a high-level view of the pandemic's timeline.
6.	Compare Country Trends
Select a few countries of interest and compare their case trends on a single line plot. This helps understand how different regions were affected at different times.
7.	Create Stacked Area Chart
Visualize how confirmed cases, recoveries, and deaths contributed cumulatively to the total case count using a stacked area chart. This emphasizes the scale and balance of outcomes.
8.	Generate Heatmap
Use a heatmap to illustrate the latest confirmed case numbers for the top 15 affected countries. Apply a log scale for better visual differentiation between high and low case counts.
9.	Export Outputs
Save the generated visualizations as high-quality images and export the cleaned datasets for further analysis or inclusion in external reports.
10.	Presentation and Sharing
Combine your findings, visuals, and exported data into a presentable format such as a report or GitHub repository for easy access by others.
	
	
	
	






 
Expected Output
•	Notebook / Script that runs end to end with zero errors.

•	Four publication ready plots:

1.	Global Cumulative COVID 19 Cases (line plot)
2.	Country wise Confirmed Cases Comparison (line plot)
3.	Stacked Area Chart of Global Cases
4.	Top 15 Countries Heatmap
•	Cleaned CSV files (cleaned_confirmed_data.csv, etc.) for quick re analysis.
Run the notebook, generate the visuals, and you’ll have a concise, data driven story of the pandemic’s spread, recovery, and impact across the world.
________________________________________


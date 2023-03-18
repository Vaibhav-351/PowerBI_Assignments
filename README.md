
Power BI Assignment 5

1.	Explain DAX.
Ans - Data Analysis Expressions (DAX) is a syntax language that comprises formulae and expressions that are used in data manipulation. Functions, constants, and operators are used in DAX to create expressions. In simpler terms, DAX is the advanced version of MS Excel with high-end data manipulation and management capabilities. It is developed by Microsoft to interact with its business intelligence and data modeling tools like PowerPivot, Power BI. Power BI is a robust analytics tool by Microsoft that offers several features and functions using DAX as a language.

2.	Explain datasets, reports, and dashboards and how they relate to each other?
Dataset is a collection of raw data from one or multiple data sources which the Analyst uses to clean, Analyze, Visualize, get insight and create reports and Dashboards. It is a raw form of data which contains attributes which when processed might help in understanding the task and draw conclusions. There are multiple types of Dataset such as Table, Links, Trees, Network, Geo-spatial etc.,
Reports is a page or series of pages which contains multiple tiles depicting some values or graphs in form of visualizations which are colourful and interactive. It can convey the performance of Business. If streaming data is supplied, dynamic changes are reflected in Visualizations in reports. Multiple reports are created for different areas of Business and the reports are watched closely by stakeholders.
Dashboards are also a form of reports. The unique thing is it a summarized form of report. It contains the same elements as reports have. But the important key information alone is added to dashboard from multiple reports. For example, we may create multiple individual reports on Facebook, Instagram, LinkedIn data how people interact with our Business page. A Dashboard for same case might try to depict "How to Digital media covers audience and accounts for Business?" which may contain some tile or visuals from the reports created individually on Facebook, Instagram or LinkedIn data.
Relation between these three is in hierarchical Manner. From processed Dataset we create multiple reports and from multiple reports, we create unique Dashboards. Of course both reports and Dashboards are accessible to stakeholders. Dataset is processed is Power BI desktop and Reports and Dashboards are accessed by stakeholders through Power BI service/Mobile.


3.	How reports can be created in power BI, explain two ways with Navigation of each.
Ans - There are 3 primary sections in home page which is used to create contents in Reports
•	Canvas - The center blank white is the canvas where visuals will appear
•	Fields Pane - Contains queries and columns of the dataset
•	Visualization Pane - To edit and format visualizations
Reports can be created in two ways
•	Select the fields first then visualizations after
•	Select the type of visual first then the fields after
METHOD 1
step 1 - Select 2 columns from Field Pane to visualize the data in 2D chart.
step 2 - When clicking them, a suitable visual will appear in the canvas area.
step 3 - Drag them and position them properly. Use formatting options in Visualization Pane for Customization.
step 4 - If you want to change the type of graph, select the chart tile in canvas and click the required type of graph in Visualization Pane.
METHOD 2
step 1 - Select the chart type. An empty tile will appear in Canvas.
step 2 - Click and drag the Columns to Fields and Values field in Visualization pane.
step 3 - If we want to categorize the 2D plot with category as 3rd Dimension, the drop the column in Legend Field
step 4 - Use formatting options in Visualization Pane for Customization.
Click File-->Save and type the name of the report. Now once we save our Report in Power BI desktop, it is time to publish it in Power BI service. Click on "Publish" option in Home Tab. Type the Name of report and select the workspace on which you want to publish the report. Now we have created a report for the stakeholders in workspace.


4.	How to connect to data in Power BI? How to use the content pack to connect to google analytics? Mention the steps.


•	To Connect to a Data source, click on "Get Data" option in Home Tab
•	click Get Data
•	In the Services box, click Get
•	From the menu of online services, select Google Analytics, and then click Connect
•	Enter the Google Analytics account, property, and view that you want to connect to. Then sign in with your
•	Google Analytics credentials.
•	To permit Power BI to connect to Google Analytics, click Accept
•	When the import process completes, you will see a new dashboard, report, and model in the Navigation Pane. Select the dashboard to view your imported data.

5.	How to import Local files in Power BI? Mention the Steps.

•	Step1: In the home tab, click on "Get Data". Select the type of file from the list available.

 

•	Step2: click on required file format and click on: -
Load button: If data cleaning is not required and directly visualization can be start
Transform data: If “data cleaning is required before visualization.
“.
	Perform data cleaning and then click on “close and apply data” to load the cleaned data.
•	Step3: Use different visualization tiles to create dashboard and reports



6.	In Power BI visualization, what are Reading View and Editing view?
Ans - There are two modes of interacting with the visualizing in reports
•	Reading view
•	Editing view
In Reading mode, users can only view or interact with the published reports in Power BI service. Clients in the workspace are restricted with Reading mode. But still users can view the visualizations changing dynamically, identify patterns/trend, get insights, query the reports.
Editing mode is generally used by Report designers or Analysts who collect data and create reports. Only they can add or delete tiles or visualizations from the reports. A much of modification priviledge is granted in this view.




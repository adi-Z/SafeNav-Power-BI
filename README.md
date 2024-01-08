SafeNav Project

Executive Summary
SafeNav is a comprehensive initiative analyzing Ottawa's traffic collision data from 2017 to 2022. The project leverages temporal analysis to enhance safety strategies and understand the factors impacting road incidents. The objective is proactive intervention in traffic safety measures, aiming to reduce accidents and make informed decisions.


Key Assumptions
- The data provided by the City of Ottawa is accurate and reliable.
- Temporal analysis can reveal hidden patterns within traffic collision data.


Project Scope and Purpose
The SafeNav project aims to uncover patterns, enhance safety strategies, and understand factors impacting road incidents in Ottawa. The scope encompasses exploring temporal patterns and identifying high-risk zones for proactive traffic safety measures.


Research Methods and Tools
Data Cleaning and Feature Engineering: Ensuring data quality and relevance.
Data Transformation: Using Power Query Editor for efficient data manipulation.
Predictive Modelling: Employing Python and machine learning to anticipate trends and high-risk zones.
Data Visualization and Analysis: Utilizing Power BI for creating insightful dashboards.


Project Stakeholders
Esin Bilgin Savkli: Data preparation and modeling.
Arit Akpan: Data visualization and analysis.
Eduardo Manotas: Predictive modeling.
Julia Saavedra: Recommendations based on data insights.


Data Analysis Overview
Accidents (2017-2022): 71,040 reported accidents, 13,290 injuries, 140 fatalities.
Key Findings: Temporal trends, seasonality and environmental conditions are identified as significant influencers.
Visualization Techniques: Smart Narrative, Maps, Card Visualizations, Slicers, Tree Map, Key Influencer, Line Charts, Clustered Bar Charts, and Stacked Column Charts.

Risk Clustering
Utilizing Python libraries (Scikit-learn and GeoPandas) for Geo clustering, the city was divided into 2413 grids categorized into five clusters based on accident and injury counts.



How to Use: Power BI (Data Cleaning, Feature Engineering,Data Analysis and Visualization)
Steps for Using the `.pbix` File and CSV Data Source
1. Prerequisites:
  - Ensure you have Power BI Desktop installed. You can download it from the [Microsoft Power BI website](https://powerbi.microsoft.com/en-us/desktop/).
   - A software to open CSV files, like Microsoft Excel or a text editor, if you want to view or modify the CSV data source.

2. Downloading the Files:
   - Navigate to the GitHub repository where the `.pbix` and CSV files are located.
   - Find the `.pbix` file and the CSV file in the list of files.
   - Download each file by clicking on the file name and then clicking the “Download” button or the appropriate option.

3. Opening the CSV File (Optional):
   - If you wish to view or edit the CSV file, locate it on your computer and double-click to open it in your preferred software (like Excel).
   - Make any necessary changes and save the file if needed.

4. Opening the `.pbix` File:
   - Locate the downloaded `.pbix` file on your computer.
   - Double-click the `.pbix` file to open it. It should automatically launch Power BI Desktop.
   - If the file doesn't open automatically, open Power BI Desktop, and then go to “File” > “Open” and navigate to the `.pbix` file.

5. Linking the CSV File in Power BI (if modified):
   - If you’ve made changes to the CSV file, you might need to update the data source in Power BI.
   - In Power BI Desktop, go to “Home” > “Transform Data” > “Data Source Settings.”
   - Find the CSV file in the list, select it, and then click “Change Source” to locate and select your updated CSV file.
   - Close the data source settings and apply the changes.

6. Interacting with the Power BI Dashboard:
   - Explore the various tabs and visualizations in the Power BI report.
   - Use slicers or filters, if available, to interact with the data.
   - Hover over visual elements for additional details or insights.

7. Saving Changes (if applicable):
   - If you make any changes or adjustments in Power BI Desktop, remember to save the `.pbix` file to retain those changes.

How to Use: Geo Clustering and Forecasting
Steps for Using the `.ipynb` File and CSV Data Source
1. Install Jupyter Notebook: If not already installed, install it either via Anaconda or using pip (`pip install notebook`).

2. Launch Jupyter Notebook: Open Jupyter Notebook from Anaconda Navigator or by typing `jupyter notebook` in your command line.

3. Open the `.ipynb` File: In Jupyter Notebook's interface, navigate to the directory containing your `.ipynb` file and open it.

4. Place the CSV File Correctly: Ensure the CSV file is in the same directory as your `.ipynb` file, or note its path if it's in a different location.

5. Run the Code: In your Jupyter Notebook, run the code cell that reads the CSV file (e.g `pd.read_csv('Traffic_Collision_Data.csv')`).

6. View the Output: Check the output of the code cell to confirm that the file has been opened successfully.




Conclusion & Recommendations
The analysis provides insights for targeted safety measures during winter, Fridays, and afternoons. A Power BI dashboard offers consultative access to these observations, with recommendations focusing on environmental conditions, seasons, and days with high accident counts.


Recommendations Highlight
Environment: Addressing clear and snowy conditions.
Season: Focusing on winter and fall.
Day of Week: Targeting specific days with higher accident occurrences.


Dashboard Usage
The Power BI dashboard allows filtering by main categories for in-depth analysis and decision-making.


Acknowledgments
Gratitude to the project team for their dedication and to the City of Ottawa for providing the data.






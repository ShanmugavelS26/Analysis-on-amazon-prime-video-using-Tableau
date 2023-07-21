# Analysis-on-amazon-prime-video-using-Tableau

Analysis on Amazon Prime Videos using Tableau Introduction: Amazon Prime Video is a popular streaming service offered by Amazon, providing subscribers with a wide range of movies, TV shows, and original content. This analysis, conducted using Tableau, aims to gain insights into Amazon Prime Video's content library, user engagement, and viewer preferences. By examining factors such as content genres, release years, viewer ratings, and user behavior, we can identify popular shows, analyze viewer patterns, and provide recommendations for content selection and user experience improvements. This analysis will help Amazon Prime Video understand its strengths and areas for growth in the competitive streaming industry.

# Dataset: 

The dataset used for this analysis is available on Kaggle. It consists of listings of all the movies and TV shows available on Amazon Prime, along with details such as cast, directors, ratings, release year, and duration. The dataset can be found here Data Collection and Preparation: Relevant data related to Amazon Prime Video was gathered, such as content details (genres, ratings, release years), user engagement metrics (views, ratings, reviews), and user behavior data. The data was structured in a suitable format, such as CSV or Excel, for import into Tableau.

# Data Cleaning: 

The dataset was preprocessed and cleaned using the pandas library to ensure data quality and consistency. The following steps were performed:

Imported the necessary libraries, such as pandas and numpy. Read the CSV file into a DataFrame using pd.read_csv(). Conducted an initial inspection of the data, including checking the first few rows, obtaining summary statistics, checking data types, and identifying missing values and duplicates. Created a copy of the DataFrame for cleaning using .copy(). Handled missing values by replacing them with appropriate values or dropping rows/columns as needed. Ensured data consistency by converting data types and formatting datetime values where necessary. Saved the cleaned DataFrame to a new file, such as an Excel file, using .to_excel() or a suitable method.

# Connect Data to Tableau: 

The cleaned dataset was then connected to Tableau for further analysis and visualization. The dataset was imported into Tableau, specifying the appropriate data source option (e.g., CSV, Excel, or a database), and the data types were assigned correctly.

# Data Exploration and Visualization: 

Using Tableau's intuitive drag-and-drop interface, various dashboards and visualizations were created to explore the dataset and gain insights into Amazon Prime Video's content library, user engagement, and viewer preferences. Filters, grouping, and aggregation functions were utilized to identify patterns and trends within the data.

# Export as Packaged Workbook: 

The visualizations and dashboards created in Tableau were exported as a packaged workbook, ensuring that the interactive and dynamic nature of the analysis was preserved.

# Publish the Reports: 

The exported packaged workbook was published to Tableau Server, making the reports and visualizations accessible to users via the web. This facilitated sharing and collaboration on the analysis findings.

Tableau dashboard public link - https://public.tableau.com/views/Analysisonamazonprimevideos/Amazonvideoanalysisdashboard?:language=en-US&:display_count=n&:origin=viz_share_link

Demo link - https://drive.google.com/file/d/1MKENEXvEI_61Nn99z6eAO3yE2IcCd0Ds/view?usp=sharing

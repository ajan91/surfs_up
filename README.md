# surfs_up

# Overview + Purpose

**Overview**
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

**Purpose**
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

# Deliverable 1: Determine the Summary Statistics for June 
In Step 1, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June.
In Step 2, convert the June temperatures to a list.
In Step 3, create a DataFrame from the list of temperatures for the month of June.
In Step 4, generate the summary statistics for the June temperatures DataFrame.

**Deliverable 1 Products**
1. A working query is written to retrieve the June temperatures from the date column of the Measurement table. 
2. The temperatures are added to a list.
3. The list of temperatures is converted to a Pandas DataFrame.
4. Summary statistics are generated for the DataFrame.

# Deliverable 2: Determine the Summary Statistics for December
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. 

**Deliverable 2 Products**
1. A working query is written to retrieve the December temperatures from the date column of the Measurement table.
2. The temperatures are added to a list.
3. The list of temperatures is converted to a Pandas DataFrame.
4. Summary statistics are generated for the DataFrame.

# Deliverable 3: A written report for the statistical analysis
A report that describes the key differences in weather between June and December and two recommendations for further analysis.

The analysis contains the following:
- Overview of the analysis: Explain the purpose of this analysis.
- Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.  
- Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

**Deliverable 3 Products**
1. Structure, Organization, and Formatting.
2. The written analysis has the following structure, organization, and formatting:
  - There is a title, and there are multiple sections.
  - Each section has a heading and subheading.
  - Links to images are working and displayed correctly.
3. Analysis
The written analysis has the following:

1. Overview of the statistical analysis:
- The purpose of the analysis is well defined.

2. Results:
- There is a bulleted list that addresses the three key differences in weather between June and December.
**June Temps
Count of 1700
Mean of 74.94
Std of 3.26
Min of 64.00
25% of 73.00
50% of 75.00
75% of 77.00
Max of 85.00**
    
**December Temps
Count of 1517
Mean of 71.04
Std of 3.75
Min of 56.00
25% of 69.00
50% of 71.00
75% of 74.00
Max of 83.00**

3. Summary:
- There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December.

In conclusion, we can deduce the following from our Data:
- The Standard deviation is 3.25 in June and 3.75 in Decemeber. This illustrates that the difference between the two seasons is 0.5.
- We can illustrate that, based on statistics of minimum and maximum, of perceptionation which temporal periods are ideal for business and potential vistors. This could be able to maximise profit when it comes to maintaining a buisness that will succeed. For example, if the perceptiation in December were higher, the likelihood of vistors would be low, showing the need to redirect funds toward June, where there could be a higher profit margin. 

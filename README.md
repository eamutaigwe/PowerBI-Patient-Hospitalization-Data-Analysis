**Patient-Hospitalization-Data-Analysis**

**Goal**
To perform an extract-transform-load (ETL) process and in-depth analysis on a patients’ hospitalization dataset from the EPIC electronic health record system and ultimately develop an interactive dashboard solution that provides insights into health conditions, associated costs (including patients’ out-of-pocket costs and health insurance company offset), and hospitalization duration.

**Specific Objectives**

+ Determine the total bill and total portion covered by Anthem Insurance Company
+ Identify hospitals with the highest total patient charge over the years under review
+ Compute total hospital stay and determine health conditions with the longest hospital stay
+ Determine the most frequent health conditions over the years under review
+ Identify health conditions with the highest patient charge
+ Represent analysis results as graphs and charts on an interactive dashboard
+ Provide actionable insights and recommendations

**Methodology**

1. First, I uploaded an Excel file containing patients’ hospital stay information and associated costs to Power BI. 
2. Next, I employed applicable DAX function to compute additional relevant metrics for deeper insights into healthcare costs.
3. Furthermore, I used descriptive statistical tools and functions to perform the analysis, including sum, count, and percentage.
4. Finally, key findings were represented using charts and graphs and presented on an interactive dashboard.

**Key Insights**

+ Overall, the patients presented with 101 health conditions which resulted in 3 million days of hospitalization from 2009 to 2012. The duration of hospital stay across patients varies widely from one day to over a month.

+ Over the years under review, $5.89 billion was incurred as patients’ hospital bills, out of which Anthem Insurance Company covered 75%($4.42 billion). This was a huge way of offsetting patients’ hospital costs.

+ Looking at the health conditions with the longest hospital stay, heart failure and kidney diseases ranked in the top 5 across the years under review, with the highest incidence in 2009.
  
+ However, intestinal and respiratory conditions generated the highest total patient charge.

+ Ironically, Good Samaritan Hospital generated the highest patient bills over the years.

* Finally, the most frequent health conditions across the years under review include pneumonia and kidney diseases with fluctuations over the years, except for heart disease which ranked highest in 2009 and 2010. Of note, 2010, specifically July witnessed a remarkable reduction in hospitalizations due to pneumonia, following a significant spike in the disease just in the preceding months.

**Recommendations**

+ It would be of more financial relief if the health insurance company covered more than 75% of these conditions

+ The Ministry of Health should investigate the root cause of heart disease prevalent among the population

+ It would be beneficial to investigate the distribution of patients by the hospitals to determine the reason behind the high patient cost generated in the Good Samaritan Hospital, if this hospital admitted more patients giving rise to the high hospital bills

# Hospital Emergency Room Visit Analysis

### For Easy Access
[Project Overview](project-overview)

[Tools](toolsl)

[Exploratory Data Analysis](exploratory-data-analysis)

[Data Analysis](results/findings)

[Results/Findings](results/findings)

[Recommendations](recommendations)

[View Dashboard](view-dashboard)


### Project Overview

This is an analysis about a hospitals Emergency Room (ER) operations, performance and swift  delivery of care to patients.
I analyzed the wait time and satisfaction score of patients amomgst other trends that would help me gain deeper understanding of the efficiency of the hospitals emergency room.

### Tools

- Excel
  - Dataset was in Excel
- Tableau
  - Analysis
  - Visualization
 
### Data Cleaning and Preparations

With Tableau, I created aggregate calculations and measure to find average age and other KPI's

### Exploratory Data Analysis

The analysis answered questions such as

1. What is the average wait time per patient?
2. What is the average Patient Satisfaction Score?
3. What is the total number of patients referred to the ER by various departments?

### Data Analysis

Calculated Fields for Patients Age Group

``` Tableau

IF [Patient Age] > 60 THEN "Senior"
ELSEIF [Patient Age] >= 25 THEN "Adult"
ELSEIF [Patient Age] >= 19 THEN "Young Adult"
ELSEIF [Patient Age] < 19 THEN "Minor"
END

```

### Results/Findings

I leveraged Tableau for exploratory data analysis and visualization.

#### The KPIs and metrics derived from the hospital's ER data include:

- Number of ER patients- 9,216
- Average Age of ER patients- 40yrs
- Average patient wait time- 35.26mins
- Average patient satisfaction score- 4.99

#### Top 3 Department referral to ER
 - No referral- 5400
 - General Practice- 1,840
 - Orthopedics- 995

#### Number of Patients by Race
  - Top 2 races visiting the ER are White and African American
  - Least 2 races visiting the ER are Native Americans and Pacific Islanders

#### Average Patient Wait Time By Month
 - Maximum- 36.67mins in February
 - Minimum- 34.50mins in October


### Recommendations

1. Cross  Training: Healthcare professionals in the ER, irrespective of their areas of specialty should be cross trained to handle multiple roles during peak periods.

2. Adequate Planning: Leveraging this analysis, ER should plan ahead and adjust staffing levels to meet current demands, while working on preventing understaffing during busy periods.


### View DashboardDashboard

To view and interact with dashboard, [click here.]()


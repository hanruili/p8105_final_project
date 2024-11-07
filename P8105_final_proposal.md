P8105_final_proposal
================
Yujing FU
2024-11-06

# Proposal for P8105

## Group Members

\[Yujing Fu\] (yf2735) \[Meitong Zhou\] (mz3084) \[Hanrui Li\] (hl3859)
\[Mingye Xie\] (mx2286) \[Zihan Zhao\] (zz3166)

## Project Title

Analyzing Rat Activities in NYC: A Public Health and Environmental Study

How rodent activities have influence on public health

## Motivation

Our project aims to investigate the correlation between rat activity and
the distribution of food scrap drop-off locations across New York City.
This research is motivated by the public health implications of rat
infestations, which can pose health risks, and the potential for food
scrap programs to influence pest activity. By analyzing these factors in
relation to time, geography, and environmental variables, we hope to
reveal patterns that could inform urban public health policies and
environmental sustainability initiatives.

## Intended Final Products

Interactive Dashboards: Visual representations of rat activity and food
scrap locations by neighborhood, with time-based filters. Statistical
Report: A written analysis highlighting findings and insights derived
from data analysis. Predictive Model: A model that estimates the
likelihood of rat activity based on various environmental and
socioeconomic factors.

## Anticipated Data Sources

All data for this analysis covers the period from January 2020 to August
2024, aligning with our research focus and ensuring consistency across
datasets.<br>

1.  **Rodent Inspection Data in NYC**: Provides detailed records of
    rodent inspection results across New York City, is the main dataset
    of our study.<br> [Data
    Source](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj/about_data)

2.  **Food Scrap Drop-Off Locations in NYC**: Details the locations for
    food scrap drop-off points across NYC neighborhoods, allowing us to
    analyze their correlation with rat activity patterns.<br> [Data
    Source](https://data.cityofnewyork.us/Environment/Food-Scrap-Drop-Off-Locations-in-NYC/if26-z6xq/about_data)

3.  **Socioeconomic Data**:

    - **Zillow Observed Rent Index (ZORI)**: Measures typical observed
      market rent across NYC, which helps in understanding how rent
      levels might relate to rat activity in various neighborhoods. ZORI
      captures rental trends in a repeat-rent index, reflecting the
      overall rental market. <br> [Data
      Source](https://www.zillow.com/research/data/)
    - **Zillow Home Value Index (ZHVI)**: Reflects typical home values
      across regions, showing property values and their changes in
      different neighborhoods.<br> [Data
      Source](https://www.zillow.com/research/data/)

## Planned Analyses, Visualizations, and Coding Challenges

**Data Analysis**

Time Series Analysis: Analyze rat activity over time by examining
inspection data on a monthly or quarterly basis. Create trend charts to
identify high-risk months and compare weekday versus weekend patterns.

Geographic Analysis: Map inspection data across NYC to highlight areas
with high rat activity.

Regression Model: We hypothesized that rat activity would be associated
with food scrap drop-off location, seasonal variation, and socioeconomic
factors. To test our hypothesis, we planned to use regression analysis
to explore the associations between food scrap drop-off, seasonal
variation, socioeconomic factors, and rat activity.

**Visualizations**

We plan to use both plot/table and dashboard.

*PLOT/TABLE*

Statistical table by area: Summarize the frequency of rodent activity
and distribution of food scrap drop-off in different boroughs (eg
Manhattan, Brooklyn, etc.)

Time period table by season: Displays rodent activity data in different
seasons (spring, summer, fall, winter), and counts inspection results by
month.

Statistical table by socioeconomic factors: Combined with socioeconomic
data (such as rent, and housing price, etc.) to count rat infestation
activities by region.

*DASHBOARD*

Heatmap of Rodent Activity: Map rodent activity inspection data onto a
map of NYC to create a heatmap or scatter plot to show the geographic
distribution of rodent activity and identify high-risk areas.

Rodent Activity Over Time: Show a time series plot of rodent activity,
showing the pass/fail rate of rodent inspections by month or quarter to
observe trends in rodent activity over time to see if there are seasonal
or long-term trends.

Rodent activity and socioeconomic factors: Generate a scatter plot or
bar chart showing the relationship between socioeconomic factors and
rodent activity frequency.

**Coding Challenges**

First of all, the amount of data about Rodent inspection is huge, with
more than 2.6 million data points. We predicted that it would be
difficult to organize this huge database. At the same time, we will use
multiple databases to merge. How to merge the multiple databases one by
one is also a difficulty we need to overcome.

Secondly, in this study, we may use regression analysis, but we may
encounter multicollinearity problems in the process, which requires us
to think about reasonable optimization methods.

## Planned Timeline

Weeks 1-2: Data Collection and Preprocessing Weeks 3-4: Initial Analysis
and Exploratory Data Visualization Weeks 5-6: Regression Modeling and
Statistical Testing Weeks 7-8: Dashboard Development and Final
Visualizations Weeks 9-10: Final Report and Presentation Preparation

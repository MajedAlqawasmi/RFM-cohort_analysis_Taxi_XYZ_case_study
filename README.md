# Taxi XYZ Case Study (Iteration 1)
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) October 2021
<br/><br/>
##  Tableau data transformation, visualisations & dashboards to answer business questions & provide RFM & cohort analysis for Giant taxi company

## Table of content

- [Project Description](https://github.com/MajedAlqawasmi/RFM-cohort_analysis_Taxi_XYZ_case_study/blob/main/README.md#project-Description)
- [Data](https://github.com/MajedAlqawasmi/RFM-cohort_analysis_Taxi_XYZ_case_study/blob/main/README.md#data)
- [Process & Tools](https://github.com/MajedAlqawasmi/RFM-cohort_analysis_Taxi_XYZ_case_study/blob/main/README.md#process--tools)
- [Key Take Aways](https://github.com/MajedAlqawasmi/RFM-cohort_analysis_Taxi_XYZ_case_study/blob/main/README.md#key-take-aways)

## Project Description
This project shall: 
- answer specific questions through visualisations
- perform RFM & cohort data analytics
- provide business insights based on findings 

## Data
Three data frames can be found here [here](https://github.com/MajedAlqawasmi/RFM-cohort_analysis_Taxi_XYZ_case_study/tree/main/data)

## Process & Tools

**Process**
An iterative/agile approach circled through the following steps:

- **Github:** set up Github repo to use for this project. <br/>
- **Project management:** Using Trello
- **Data cleaning & wrangling & EDA in Python:** using Pandas / numpy <br/>
- **RFM & cohort analysis data preparation, Visualization & dashboards:** using Tableau

## Key Take Aways

Here's the answer to important business questions:
- **Recommend a Driver’s Lifetime Value (i.e. the value a driver to  over the entire projected lifetime of a driver). [7556$](https://public.tableau.com/views/UberCaseStudy_16329672122770/AVGdrivervalue?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 
- **What are the main factors that affect a driver’s lifetime value?** Recency, Frequency & Monetary value. The correlation between those three and drivers' life time can be seen in those three charts: [Recency](https://public.tableau.com/views/UberCaseStudy_16329672122770/DriverlifetimeVSrecency?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link), [Frequency](https://public.tableau.com/views/UberCaseStudy_16329672122770/DriverlifetimeVSfrequency?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link), [Monetary](https://public.tableau.com/views/UberCaseStudy_16329672122770/DriverlifetimeVSMonetary?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 
- **What is the average projected lifetime of a driver? That is, once a driver is onboarded, how long does he/she typically continue driving with XYZ_TAXI.** [57 days](https://public.tableau.com/views/UberCaseStudy_16329672122770/averagelifespan?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 
- **Explore how drivers churn once they start driving with XYZ_TAXI Are there any predictive indicators for driver churn?** RFM tiers together with median life expectency can be a solid indicator of direver churn and therefore used in logistic regression model to predict that in iteration 2 of this project. Nonetheless, here are some [cohort analysis](https://public.tableau.com/views/UberCaseStudy_16329672122770/cohortanalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) initial [forcast](https://public.tableau.com/views/UberCaseStudy_16329672122770/Churnforcast?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) of individual drivers.
- Do all drivers act alike? Are there specific segments of drivers that generate more value for XYZ_TAXI than the average driver? Indeed some segmetns are more lucrative than others [high-revenue new drivers](https://public.tableau.com/views/UberCaseStudy_16329672122770/segmentrevenue?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) are on the top and therefore worth investing more in them. 

For more exploration of the finding check out with [this dashboard](https://public.tableau.com/views/UberCaseStudy_16329672122770/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 

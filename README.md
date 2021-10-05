# # Taxi XYZ Case Study
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) October 2021
<br/><br/>
##  Tableau data transformation, visualisations & dashboards to answer business & provide RFM & cohort analysis for Giant taxi company

## Table of content

- [Project Description](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#project-Description)
- [Data](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#data)
- [Process & Tools](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#process--tools)
- [Key Take Aways](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#key-take-aways)

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

- **Github:** set up our Github repo to use for this project. <br/>
- **Project management:** Using Trello
- **Data cleaning & wrangling & EDA in Python:** using Pandas / numpy <br/>
- **RFM & cohort analysis data preparation, Visualization & dashboards:** using Tableau

## Key Take Aways

Here's the answer to important business questions:
- **Recommend a Driver’s Lifetime Value (i.e. the value a driver to  over the entire projected lifetime of a driver). [7556$](<div class='tableauPlaceholder' id='viz1633451591891' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ub&#47;UberCaseStudy_16329672122770&#47;AVGdrivervalue&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='UberCaseStudy_16329672122770&#47;AVGdrivervalue' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ub&#47;UberCaseStudy_16329672122770&#47;AVGdrivervalue&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1633451591891');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>) 
- **Should they put some restriction on products/?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ProductsProfitCustomerServicewise?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) is the a list of the worst products in terms of profit ration and customer service combined
- **Other advices to Superstore strategy** This [chart](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModeProfitabilityTimeline?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) shows an issue with the profitability of two of the ship modes (First class & Same day), and this [chart](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/TheDiscountProblem?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) and more accurately [this interactive scatter plot](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModediscountscatterplot?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) show that profit ratio and discounts offered negatively correlate so the reason for prfot stagnation in those two ship modes is the increased discount offers. **Therefore I'd like to recommend a restriction on discounts offered for First class & Same day ship modes and an increase of the overall price.**  

The answer to Tableau challenge, Part 3:
- **Daily profit in Euros:** intergrated in [this dashboard](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModesSegmentsProfitabilityperCity?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) or single days since 2016 tabled [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/DailyProfitinEuro?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

● What are the main factors that affect a driver’s lifetime value? worksheet tableau
● What is the average projected lifetime of a driver? That is, once a driver is onboarded, how long does he/she typically continue driving with XYZ_TAXI. worksheet tableau
● Explore how drivers churn once they start driving with XYZ_TAXI Are there any predictive indicators for driver churn? cst RFM tiers/last worksheet + cohort analysis
● Do all drivers act alike? Are there specific segments of drivers that generate more value for XYZ_TAXI than the average driver?  high-revenue new drivers
● What relevant business uses does this metric have? investment in high-revenue new drivers

# Looking at Toxic Waste Releases in Baltimore City, MD by Facility
## Background
For our final project, we thought it would be interesting to look at toxic waste released in Baltimore over 4 years from 2016-2019. We'll take a look at Baltimore City data from [The Toxics Releases Inventory (TRI) Program,](https://www.epa.gov/toxics-release-inventory-tri-program/tri-data-and-tools) which is a program under the [U.S. EPA](https://www.epa.gov/) that "tracks the industrical management of toxic chemicals that may cause harm to human health and the environment."

## Business Question
***How has the amount of toxic waste released in Baltimore City changed over 4 years and which facilities are top contributors?***

## Data Sources
We'll use the [basic data files](https://www.epa.gov/toxics-release-inventory-tri-program/tri-basic-data-files-calendar-years-1987-2019?) from the Toxics Releases Inventory (TRI) online. We'll be looking at the facility name, address, industry sector, chemical classification, and overall quantity of chemicals released by the facility. 

## Data Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pO4eHJu2X2zCqgOJj5fzHiShNbOVi-Ks?usp=sharing)
We will be conducting two python analyses to look at total released by facility vs. total released overall in Baltimore City. For this first part of the python analysis, we used pandas and plotly express to conduct analysis related to the final project. We first looked at the total amount released by facility per year. However, since the amount varies from less than 10 thousand to 1 million, the graphs were not as relevant. We then decided to look at the total amount released by facilities in Baltimore City over four years.

![image1](https://github.com/katiesunsg/toxicwaste-baltimorecity/blob/main/totalreleasedpythonbargraph.png)

From there, we took the top 7 facilities that had released a significant amount of toxic chemicals to be reflected on the graph to see the overall amount of chemicals released over 4 years. We can see that the Grace Davidson-Curtis Bay Works facility was the top contributor with just over 2 million pounds of toxic waste released from 2016-2019. 

![image2](https://github.com/katiesunsg/toxicwaste-baltimorecity/blob/main/sortedtopfacilitiespython.png)

## Summary
This data analysis will be useful for our final project as it shows us the top 7 facilities out of the total 35 facilities operating in Baltimore City. In terms of our general recommendations, we plan to present a recommendation to promote source reduction and energy recycling to the [Baltimore Office of Sustainability](https://www.baltimoresustainability.org/) which is a Baltimore City department that is "strengthening community through collaborative social, environmental, and economic planning and action."

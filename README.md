# What's in my food?

# Abstract
Our idea is to use the open food facts database to analyze the nutrition quality of countries by their food composition. 
We would like to try to link our results with societal pathologies such as diabetes, heart attacks or obesity.
With our findings, we would like to show whether the difference in the food contents of different countries make significant changes to their population health.
Today those questions are crucial because our generation is faced with how the health of the society is in danger due to the composition of our food.

# Research questions
- What's the average nutriment quantity per 100g?
- Where are the most sugary and fatty foods found?
- Which food composition element is more directly linked with the pathologies we want to study? If at all?
- Do populations which have more of such pathologies (diabetes & high cholesterol) consume these types of food?
- Is possible to clearly quantify the cholesterol levels (ask people working in medicine)?

# Dataset
Our main dataset will be the open foods facts database. 
The set contains 685395 items and 173 features, with about a quarter of the values representing european products. Since this is an openly participative dataset, we can expect a lot of items having few features entered (and thus a lot of NaN!)
We also need to select the most relevant features for our research. 
We would also like to link our findings to legitimate medical, such as diabetes rates per country, and nutritionalinformation, such as what constitutes a healthy food.
Up until milestone 2, we have used data from the world health organization as well as the international diabetes federation. 
Since we needed to pay for the WHO data, we found a website using some of their data that we could download for free. 
The IDF data on diabetes was available freely.
We also used a database that linked all countries to their alpha code, in different languages: 
One problem we came up with during this milestone was that a food item could be sold in more than one country. 
Also, many countries were inputed in different languages, so we needed to find a way to group everything together - that's how the codes came in handy.
In Milestone 3 we added some data about heart attacks. 
We also needed to find some json data to outline countries on a world map. 
In order to analyse our data more thoroughly, we also had to include alpha3 country codes and continent codes. 

[WHO](https://ourworldindata.org/obesity)
[IDF](http://diabetesatlas.org/resources/2017-atlas.html)
[IHD](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3819990/)

# Report for milestone 3
LaTeX report found in repository - report.pdf

# Workload separation
Simon: Project description, data search, data clean, find way to group countries by code, code for world maps, write report.

Zoé: Data search/ cleaning/ analysis, plots, correlation tables, linear regression, code commenting, touch up report.

Both will work on the presentation.

# Internal milestones up until milestone 3
- Find an additional illness to compare to
- Clean data
- Create world map
- Scatter plots, correlation, linear regression
- Comment code
- Write report

# Internal milestones up until project milestone 2
- Clean the data.
- Choose relevant features. 
- Reduce the dataset with only european countries.
- Build dataset from medical information (from pdf)
- Explore the dataset.
- Analyze the data to try to answer our research questions (using graphs etc.)

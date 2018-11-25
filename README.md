# What's in your food?

# Abstract
Our idea is to use the open food facts database to analyze the nutrition quality of countries by their food composition. 
We would like to try to link our results with societal pathologies such as diabetes or high cholesterol levels.
With our findings, we would like to show which countries have the best food habits and whether the difference in the food contents make significant changes to the population health.
Today those questions are crucial because our generation is faced with how the health of the society is in danger due to the composition of our food.

# Research questions
- What kind of foods are considered to be healthy?
- Where are the most sugary and fatty foods found?
- Which food composition element is more directly linked with the pathologies we want to study?
- Do populations which have more of such pathologies (diabetes & high cholesterol) consume a these types of food?
- Is possible to clearly quantify the cholesterol levels (ask people working in medicine)?

# Dataset
List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. 
Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

Our main dataset will be the open foods facts database. 
The set contains 685395 items and 173 features, with about a quarter of the values representing european products. Since this is an openly participative dataset, we can expect a lot of items having few features entered (and thus a lot of NaN!)
We also need to select the most relevant features for our research. 
We would also like to link our findings to legitimate medical, such as diabetes rates per country, environmental information , such as environmental friendly carbon footprints, and nutritional information, such as what constitutes a healthy food.
Up until milestone 2, we have used data from the world health organization as well as the international diabetes federation. 
Since we needed to pay for the WHO data, we found a website using some of their data that we could download for free. 
The IDF data on diabetes was available freely.
We also used a database that linked all countries to their alpha code, in different languages: 
One problem we came up with during this milestone was that a food item could be sold in more than one country. Also, many countries were inputed in different languages, so we needed to find a way to group everything together - that's how the codes came in handy.


# A list of internal milestones up until project milestone 2
- Clean the data.
- Choose relevant features. 
- Reduce the dataset with only european countries.
- Build dataset from medical information (from pdf)
- Explore the dataset.
- Analyze the data to try to answer our research questions (using graphs etc.)

# Questions for TAa
- Is it acceptable to work only with a part of the dataset? (European countries)
- How do we ensure data coherence in a participative database, in which a lot of feature information may be missing?
- Which medical and environmental databases are considered to be legitimate? 
- Can we create a database from a pdf representing the data we want to use? 

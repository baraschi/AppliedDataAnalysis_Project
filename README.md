# What's in your food?

# Abstract
Our idea is to use the open food facts database to analyze the nutrition quality in Europe by their food composition. 
We would like to try to link our results with societal pathologies such as diabetes or high cholesterol levels.
We would also like to check the carbon footprint of each food item and present a classification of which item is the most valuable for the environment. With our findings, we hope to extract the healthiest food options which are also the friendliest for the environment.

To summarize, we would like to show which countries have the best food habits and whether the difference in the food contents make significant changes to the population health, as well as which products are the kindest to the environment.
Today those questions are crucial because our generation is faced with environmental questions, such as how mass farming and a highly increasing population rate affect which foods we eat and how the health of the society is in danger due to the composition of our food.

# Research questions
- Where are the most sugary and fatty foods found?
- Which food composition element is more directly linked with the pathologies we want to study?
- Do populations which have more of such pathologies (diabetes & high cholesterol) consume a these types of food?
- How it is possible to clearly quantify the cholesterol levels (ask people working in medicine)?
- Which food products are more environmentally safe?

# Dataset
List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.
Our main dataset will be the open foods facts database. The set contains 685395 items and 173 features, with about a quarter of the values representing european products. Since this is an openly participative dataset, we can expect a lot of items having few features entered (and thus a lot of NaN!)
We also need to select the most relevant features for our research. 
We would also like to link our findings to legitimate medical, such as diabetes rates per country, and environmental information , such as environmental friendly carbon footprints, found online. 

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

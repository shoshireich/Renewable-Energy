# Renewable-Energy
## Abstract
Renewable energy is a vital aspect in reducing greenhouse gas emissions and mitigating climate change. Countries around the world have varying degrees of renewable electricity production. Here, a country's percentage of renewable energy is compared to its level of wealth, as well as its knowledge in the field of energy engineering and power technology. Energy data from the United Nations, GDP data from the World Bank, and jounral contribution data from the Scimago Journal are combined in order to create a visual of how a country's renewable electricity production relates to its GDP and energy expertise. 

## Methods
The following three datasets are used:
- Energy data from the United Nations for the year of 2013 that includes energy supply, energy supply per capita, and % renewable electricity production.
- GDP data from the World Bank that includes countries' GDP from 1960 to 2015.
- Data from the Scimago Journal that ranks countries based on their journal contributions in energy engineering and power technology.

In order to successfully merge the datasets into one dataframe, columns of interest are selected, columns are renamed, and values are converted. Countries are renamed to ensure the same name is used across all three datasets. The data is then narrowed down to only include the last 10 years (2006-2015) of GDP data and only the top 15 countries by Scimago Journal's rank.

## Results and Discussion
The bubble chart below shows a country's percentage of electricity production that comes from renewable sources vs the country's rank from the Scimago Journal. The size of the bubble corresponds to each country's 2015 GDP. The color of the bubbles corresponds to the continent.

<img src="https://github.com/shoshireich/Renewable-Energy/blob/master/RenewablevsRank.png" width="90%">

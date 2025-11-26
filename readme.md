# Share of people who are undernourished - Data package

This data package contains the data that powers the chart ["Share of people who are undernourished"](https://ourworldindata.org/grapher/prevalence-of-undernourishment?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on November 26, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Share of people who are undernourished – UN FAO
Share of the population whose daily food intake does not provide enough energy to maintain a normal, active, and healthy life.

Last updated: March 17, 2025  
Next update: March 2026  
Date range: 2000–2023  
Unit: percent  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data. “Share of people who are undernourished – UN FAO” [dataset]. Food and Agriculture Organization of the United Nations, “SDG Indicators” [original data].
Source: Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World In Data

### What you should know about this data
* [Hunger](https://ourworldindata.org/hunger-and-undernourishment) has been a severe problem throughout history. For most people, growing enough food to feed their family was a daily struggle. Food shortages, malnutrition, and [famines](https://ourworldindata.org/famines) were common around the world.
* This data estimates the share of people who are undernourished — those whose daily energy (calorie) intake is too low to support a normal, active, and healthy life.
* Undernourishment is determined solely by whether a person gets enough calories. It does not account for the quality or diversity of their diet. Therefore, it is only one aspect of malnutrition, a broader term that captures other deficiencies, such as micronutrients.
* Minimum calorie needs vary by sex, age, body size, and activity level. Researchers use demographic data to account for these differences in each country's estimates.
* The data is published by the Food and Agriculture Organization of the United Nations (FAO). It is based on a statistical model that combines national food supply data, demographic projections, and, where available, household food consumption surveys. To reduce short-term variability on country-level data, the FAO sets the values for a given year to the average of the last three years.
* Many countries, especially high-income ones, are shown at 2.5% because the FAO reports values between 0% and 2.5% as "<2.5%", due to uncertainty at very low levels of undernourishment.
* The world has made significant progress in reducing undernourishment. However, this data shows we are still far from ending hunger: nearly 1 in 10 people globally don't get enough to eat. Hunger worsened during the COVID-19 pandemic and remains a major challenge.

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2025)?
### Sustainable Development Goals
Goal 2: End hunger, achieve food security and improved nutrition and promote sustainable agriculture.

Target 2.1: By 2030, end hunger and ensure access by all people, in particular the poor and people in vulnerable situations, including infants, to safe, nutritious and sufficient food all year round.

Indicator 2.1.1: Prevalence of undernourishment

- Definition: The prevalence of undernourishment (PoU) (French: pourcentage de sous-alimentation; Spanish: porcentaje de sub-alimentación; Italian: prevalenza di sotto-alimentazione) is an estimate of the proportion of the population whose habitual food consumption is insufficient to provide the dietary energy levels that are required to maintain a normal active and healthy life. It is expressed as a percentage.
- Concepts: Undernourishment is defined as the condition by which a person has access, on a regular basis, to the amount of food that are insufficient to provide the energy required for conducting a normal, healthy and active life, given his or her own dietary energy requirements. Though strictly related, “undernourishment” as defined here is different from the physical conditions of “malnutrition” and “undernutrition” as it refers to the condition of insufficient intake of food, rather than to the outcome in terms of nutritional status. In French, Spanish and Italian the difference is marked by the use of the terms alimentation, alimentación, or alimentazione, instead of nutrition, nutrición or nutrizione, in the name of the indicator. A more appropriate expression in English that would render the precise meaning of the indicator might have been “prevalence of under-feeding” but by now the term “undernourishment” has long been associated with the indicator. While the undernourishment condition applies to individuals, due to conceptual and data-related considerations, the indicator can only be referred to a population, or group of individuals. The prevalence of undernourishment is thus an estimate of the percentage of individuals in a group that are in that condition, but it does not allow for the identification of which individuals in the group are, in fact, undernourished.

### Source

#### Food and Agriculture Organization of the United Nations – SDG Indicators
Retrieved on: 2025-03-17  
Retrieved from: http://www.fao.org/faostat/en/#data/SDGB  


    
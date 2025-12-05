# Share of children in employment - Data package

This data package contains the data that powers the chart ["Share of children in employment"](https://ourworldindata.org/grapher/incidence-of-child-labour?tab=table&overlay=download-data&v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website. It was downloaded on November 29, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:
tab: table
overlay: download-data

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


## Children in employment
Share of children aged 7-14 years involved in economic activity for at least one hour in the reference week of the survey.
Last updated: September 8, 2025  
Next update: September 2026  
Date range: 1994–2016  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
International Labour Organization, UNICEF, and World Bank (2025) – processed by Our World in Data

#### Full citation
International Labour Organization, UNICEF, and World Bank (2025) – processed by Our World in Data. “Children in employment – ILO” [dataset]. International Labour Organization, UNICEF, and World Bank, “World Development Indicators 122” [original data].
Source: International Labour Organization, UNICEF, and World Bank (2025) – processed by Our World In Data

### How is this data described by its producer - International Labour Organization, UNICEF, and World Bank (2025)?
Children in employment refer to children involved in economic activity for at least one hour in the reference week of the survey.

### Limitations and exceptions:
Although efforts are made to harmonize the definition of employment and the questions on employment in survey questionnaires, significant differences remain in the survey instruments that collect data on children in employment and in the sampling design underlying the surveys. Differences exist not only across different household surveys in the same country but also across the same type of survey carried out in different countries, so estimates of working children are not fully comparable across countries. For detailed source information, see footnotes at each data point.

### Statistical concept and methodology:
Data are from household surveys by the International Labor Organization (ILO), the United Nations Children's Fund (UNICEF), the World Bank, and national statistical offices. The surveys yield data on education, employment, health, expenditure, and consumption indicators related to children's work. Since children's work is captured in the sense of "economic activity," the data refer to children in employment, a broader concept than child labor (see ILO 2009a for details on this distinction).

Household survey data generally include information on work type - for example, whether a child is working for payment in cash or in kind or is involved in unpaid work, working for someone who is not a member of the household, or involved in any type of family work (on the farm or in a business).

In line with the definition of economic activity adopted by the 13th International Conference of Labour Statisticians, the threshold set by the 1993 UN System of National Accounts for classifying a person as employed is to have been engaged at least one hour in any activity relating to the production of goods and services during the reference period. Children seeking work are thus excluded. Economic activity covers all market production and certain nonmarket production, including production of goods for own use. It excludes unpaid household services (commonly called "household chores") - that is, the production of domestic and personal services by household members for a household's own consumption.

Country surveys define the ages for child labor as 5-17. The data here have been recalculated to present statistics for children ages 7-14.

### Source

#### International Labour Organization, UNICEF, and World Bank – World Development Indicators
Retrieved on: 2025-09-08  
Retrieved from: https://data.worldbank.org/indicator/SL.TLF.0714.ZS  


    
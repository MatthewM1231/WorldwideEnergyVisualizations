# Worldwide Energy Consumption Visualizations
Visualizations from Worldwide Energy Consumption dataset found here: https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption?resource=download. Visualizations display various trends in energy consumption metrics, macroeconomic trends regarding energy, and global greenhouse gas emission trends. Credit goes to Our World in Data as well as Hannah Ritchie, Pablo Rosado, Edouard Mathieu, Max Roser for collecting, aggregating, and documenting the original data used for this project.

Final poster summarizing findings can be found in the Menon_FinalPoster.pdf file

## Visualization 1: World Fuel Mix from 1965 - 2022 in Terrawatt Hours of Energy
Utilized data within WorldEnergyConsumption-All.csv and Microsoft Excel to create a multi-series line graph displaying the consumption of different fuel mixes from the years 1965 to 2022 including oil, coal, natural gas, hydroelectric, nuclear, wind, and solar energy. The consumption is measured in Terra-Watt Hours, and consumption of all sources appears to increase over time at different rates, with with fossil fuels outcompeting clean energy sources in consumption for the entire timespan.

## Visualization 2: GDP vs. Energy Consumption per Capita in 2018 (Log-Scale Adjusted, Color = Population)
Utilized data within WorldEnergyConsumption-All.csv and R Studio to create a scatter plot, where each point represents an individual countrie's GDP on the x-axis and energy consumption per capita in Kilo-watt hours per person on the y-axis. Additionally, color factors were used where each point is colored based on it's respective population. The trend line within the plot shows a notable increase in energy consumption per capita as GDP increases, with higher populated countries also appearing to see greater gross domestic products without much of an effect on their energy consumption per capita. Countries with notably high or low GDPs and energy per capita consumption metrics are also labeled. The code used to generate this visualization can be found in the DSA202-ConsumptionvsGDPViz.Rmd file.

## Visualization 3: Worldwide Shares of Renewable Electricity Generation in 2022
Utilized data within WorldEnergyConsumption-2022.csv and Tableau Public to create a map visualization that represents the ratio of electricity consumed in each country that comes from renewable sources out of all the electricity consumed in each country. This ratio is a calculated field that is useful in describing the progress of different countries towards relying more on renewable energy sources. The highest ratios of renewable electricity shares can be found in Canada, the northern countries of South America, the Nordic Countries as well as New Zealand, with the lowest ratios being found in African countries and the Middle East.

## Visualization 4: Countries with Highest CO2 Emissions (Megatonnes) in 2022
Utilized data within WorldEnergyConsumption-2022.csv and Microsoft Excel to create a bar chart that shows the greenhouse gas emissions in megatonnes of the countries with the 10 highest carbon dioxide emission rates in 2022.

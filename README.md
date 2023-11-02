# Introduction:
The pursuit of happiness is a fundamental aspect of human well-being, and understanding the factors that contribute to happiness is of great interest to researchers and policymakers worldwide. The World Happiness Report provides a comprehensive assessment of happiness levels and its determinants across different countries. In this data analysis project, we aim to delve into the World Happiness Report from 2020 and 2021, exploring trends, patterns, and key insights regarding global happiness.
# [Interactive Notebook]()
# Objective:
The primary objective of this project is to analyze the World Happiness Report data spanning from 2020 and 2021 and gain a deeper understanding of the factors influencing happiness levels worldwide. By conducting exploratory data analysis, we seek to uncover trends, patterns, and correlations within the dataset, identifying key factors associated with happiness and exploring their changes over time.

# Research Questions
"Does GDP per capita have a significant impact on the happiness score of countries?"

"Is there a correlation between social support and happiness?"

"Does healthy life expectancy influence happiness?"

"Is freedom to make life choices associated with happiness?"

"Is generosity related to happiness?"

"Does perceptions of corruption impact happiness?"

"What are the regional variations when it comes to the variables affecting happiness?"

"what are the regional variations in the happiness score?"

"What are the top happiest countries and the least countries per the factors that affect happiness score"?

"What are the ten top happiest countries and the 1o least happy countries"?

#understanding the datasets

Here is an explanation of some important columns to the project that will be found in the datasets:Certainly! Here's an explanation of the additional columns you mentioned in the World Happiness Report dataset, including the "sub regions" column:

Country name: This column contains the name of each country or region included in the report. It identifies the specific geographical entity for which the happiness scores and other factors are reported.

Regional indicator: This column categorizes countries into different regions or geographic areas based on their shared characteristics. It provides an additional level of grouping or classification beyond individual countries. The regional indicator helps in analyzing happiness trends and patterns across different parts of the world.

Ladder score: The ladder score column represents the overall happiness score or subjective well-being score of each country. It is a numeric value derived from surveys that ask individuals to rate their life satisfaction or happiness on a scale from 0 to 10. The ladder score provides a standardized measure of happiness, allowing for cross-country comparisons.

Logged GDP per capita: This column represents the logarithm of the Gross Domestic Product (GDP) per capita of each country. It measures the economic output per person and indicates the average income or wealth of individuals in that country. Taking the logarithm helps in normalizing the data and addressing the skewed distribution of GDP values.

Social support: The social support column quantifies the perceived availability of assistance and support from family, friends, and social networks within a country. It measures the strength of social relationships and the level of social cohesion. Higher values indicate a greater sense of social support and well-being.

Healthy life expectancy: This column represents the average life expectancy at birth in each country. It reflects the overall health and well-being of the population and is influenced by factors such as healthcare, sanitation, and lifestyle. Higher values indicate longer life expectancies and better health outcomes.

Freedom to make life choices: This column measures the extent to which individuals within a country have the freedom to make life choices. It considers factors such as political and civil liberties, human rights, and individual autonomy. Higher values suggest a greater degree of freedom to choose one's path in life.

Generosity: The generosity column quantifies the propensity of individuals within a country to engage in charitable acts and exhibit kindness and benevolence towards others. It measures the willingness to help others and contribute to the well-being of society. Higher values indicate higher levels of generosity.

Perceptions of corruption: This column indicates the perceived level of corruption within a country. It measures the extent to which corruption is perceived to exist in public institutions and society as a whole. Higher values suggest a higher perceived level of corruption.

These columns provide insights into various factors that contribute to the overall happiness scores reported in the World Happiness Report. Analyzing these columns helps in understanding the relationship between economic factors, social support, health, freedom, generosity, perceptions of corruption, and happiness levels across different countries and regions.

# Methodology:
Data Collection: We will gather the World Happiness Report data for the years 2020 to 2021, including various factors such as GDP per capita, social support, life expectancy, freedom, generosity, and perceptions of corruption.

Data Preprocessing: We will perform necessary data cleaning, handle missing values, and ensure consistency in formatting. Additionally, we may need to harmonize the data across different years for meaningful comparisons.

Exploratory Data Analysis: Through statistical techniques, visualizations, and descriptive analysis, we will uncover interesting insights about happiness trends over the two-year period. We will examine the distribution of happiness scores, identify countries with high and low happiness levels, and investigate how different factors contribute to overall happiness.

Temporal Analysis: We will explore how happiness scores and the contributing factors have changed over time. This will involve examining trends, identifying significant fluctuations, and understanding any country-specific patterns.

Correlation Analysis: OLS will investigate the relationships between various factors and happiness levels. This analysis will help identify which factors have the strongest associations with happiness and whether these associations differ across years.

Comparative Analysis: By comparing happiness scores and factors across different countries and regions, we will uncover variations in happiness levels and explore potential reasons for these differences.

Visualization and Reporting: Results will be presented using clear and insightful visualizations, including charts, graphs, and maps, to facilitate easy interpretation. A comprehensive report summarizing the findings and insights from the analysis will be produced.

8.For the analyses we will use the Separate Analysis for Each Year. In this approach, you would perform individual analyses for each year's dataset separately. This approach allows you to focus on the specific trends, patterns, and factors influencing happiness scores within each year.

By conducting this data analysis project on the World Happiness Report from 2020 and 2021, we aim to contribute to the understanding of global happiness trends, identify key determinants of happiness, and provide valuable insights for policymakers, researchers, and individuals seeking to enhance well-being worldwide.

# Data source :
The data sources for this data analysis project were obtained from Kaggle, a popular platform for data scientists and analysts to share and discover datasets. Kaggle hosts a wide range of datasets contributed by the community, including the World Happiness Report dataset. 2020 data was obtained from: https://www.kaggle.com/datasets/londeen/world-happiness-report-2020 2021 data was obtained from:https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021 Sub regions data were obtained from:https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region

#Summary and findings

This project undertook an in-depth analysis of the World Happiness Score spanning the years 2020 to 2021, with a central focus on identifying the factors that influence global happiness levels and exploring regional variations in these determinants. The findings from this study have yielded profound insights into the evolving landscape of happiness on a worldwide scale during this two-year period.

To substantiate our research, we employed the Ordinary Least Squares (OLS) method as a robust statistical tool. Through rigorous analysis, we were able to validate several hypotheses that deepen our understanding of the dynamics of happiness:

1.A significant positive relationship exists between Gross Domestic Product (GDP) per capita and the happiness scores of nations.

2.There is a noteworthy positive correlation between social support and happiness.

3.Healthy life expectancy significantly influences happiness in a positive manner.

4.Freedom to make life choices is positively associated with happiness levels.

5.Generosity does not exhibit a statistically significant relationship with happiness.

6.There is a substantial negative impact of the perception of corruption on happiness.

Regional Variations We initiated our exploration by compiling a summary of the top ten happiest countries for the year 2020. This list prominently featured nations such as Finland, Denmark, Switzerland, Iceland, Norway, Netherlands, Sweden, New Zealand, Austria, and Luxembourg. On the contrary, the top ten unhappiest countries in 2020 included Afghanistan, South Sudan, Zimbabwe, Rwanda, the Central African Republic, Tanzania, Botswana, Yemen, Malawi, and India.

To provide visual evidence for the regional variations, we employed bar plots, revealing a stark contrast in happiness distribution across the globe. Sub-Saharan Africa emerged as a region with a notable concentration of lower happiness scores, while Northern America, albeit with fewer countries, exhibited higher happiness levels.

# Key Contributing Factors

Our analysis delved into several key factors contributing to happiness:

1.Gross Domestic Product (GDP) per capita: Western Europe consistently claimed the highest GDP per capita, while Sub-Saharan Africa consistently ranked at the bottom in both 2020 and 2021.

2.Social Support: Australia and New Zealand consistently secured the top positions for social support scores across both years, whereas Sub-Saharan Africa and Southern Asia countries reported consistently lower scores.

3.Healthy Life Expectancy: Australia and New Zealand consistently boasted the highest healthy life expectancy scores, while Sub-Saharan African countries consistently recorded the lowest scores in both 2020 and 2021.

4.Freedom of Making Life Choices: Australia and New Zealand offered the most freedom for individuals to make life choices, whereas Northern Africa consistently scored the lowest in both years.

5.Generosity: Australia and New Zealand exhibited the highest levels of generosity in 2020, while Southeast Asian countries took the lead in 2021. Conversely, Northern Africa consistently reported the lowest levels of generosity for both years.

6.Perception of Corruption: Eastern Europe consistently grappled with higher perceptions of corruption, while Australia consistently had the lowest perception of corruption in both years.

# Top Ten Countries Based on Contributing Factors

1.Gross Domestic Product (GDP) per capita: Luxembourg secured the highest ranking in GDP for both 2020 and 2021, with Burundi consistently at the bottom.

2.Social Support: Iceland claimed the top spot in 2020, with Central African countries consistently ranking the lowest. In 2021, Afghanistan ranked the lowest in this category.

3.Life Expectancy: Singapore maintained the highest score, while Central Africa and Chad recorded the lowest scores in both 2020 and 2021, respectively.

4.Freedom of Making Life Choices: Uzbekistan excelled in this category, while Afghanistan consistently ranked at the bottom in both years.

5.Generosity: Myanmar emerged as the most generous country in 2020, while Indonesia claimed the top spot in 2021. Greece consistently reported the lowest generosity scores.

6.Corruption: In 2021, Croatia experienced an increase in corruption perception, while Singapore remained the least corrupt nation. Bulgaria struggled with corruption perception in 2020.

7.Analysis for 2020 and 2021

There were noteworthy fluctuations in specific factors between 2020 and 2021:

-Corruption: While Bulgaria struggled with corruption perception in 2020, Croatia experienced an increase in corruption perception in 2021. Singapore maintained its status as the least corrupt nation.

-Generosity: Myanmar was recognized as the most generous country in 2020, while Greece continued to report the lowest generosity scores in both years.

In conclusion, this comprehensive analysis has illuminated the regional disparities and contributing factors that shape happiness scores across the globe during the years 2020 and 2021. This understanding can serve as a valuable compass for policymakers and organizations to formulate strategies aimed at promoting happiness and enhancing the overall quality of life on a global scale.

# Recommendations
Based on the findings of this analysis, several recommendations can be made:

1.Policy Emphasis on Happiness Factors: Governments should pay attention to the factors that significantly contribute to happiness, such as GDP per capita, social support, healthy life expectancy, and freedom to make life choices. Policies aimed at improving these factors can lead to higher levels of happiness among their citizens.

2.Regional Disparities: Efforts should be made to address regional disparities in happiness. Regions like Sub-Saharan Africa and southern Asia consistently ranked lower in happiness scores. International organizations and governments should work together to implement programs and policies that uplift these regions.

3.Corruption Perception: Countries should focus on reducing corruption and improving public trust. Perception of corruption negatively affects happiness. Transparency and anti-corruption measures can lead to increased happiness levels.

4.Generosity: Encouraging a culture of generosity and charitable giving can enhance happiness. Governments and organizations can promote philanthropic activities and community engagement.

5.Healthcare Investments: Investing in healthcare and promoting healthy lifestyles can increase healthy life expectancy, a key factor in happiness. Providing access to quality healthcare services should be a priority.

6.Freedom and Life Choices: Countries should prioritize individual freedoms and the ability to make life choices. Policies that protect civil liberties and promote personal autonomy can positively impact happiness.

7.Continued Monitoring: Regular monitoring and analysis of happiness scores and contributing factors are essential. This allows for the evaluation of policy effectiveness and the identification of evolving trends.

In conclusion, understanding the factors that influence happiness and addressing regional variations is crucial for the well-being of societies worldwide. By implementing these recommendations, governments and organizations can work towards fostering greater happiness and improving the quality of life for their populations.

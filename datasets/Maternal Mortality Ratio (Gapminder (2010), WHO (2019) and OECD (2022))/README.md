# Maternal Mortality Ratio (Gapminder (2010), WHO (2019) and OECD (2022))

Claudia Hanson has reconstructed the historical estimates for Gapminder in 2010. The work is documented here: https://web.archive.org/web/20220327041441/https://www.gapminder.org/documentation/documentation/gapdoc010.pdf and can be accessed here: https://docs.google.com/spreadsheets/d/14ZtQy9kd0pMRKWg_zKsTg3qKHoGtflj-Ekal9gIPZ4A/pub#

Gapminder has reconstructed the historical data for the following 13 countries: Australia, Belgium, Denmark, Finland, Germany, Ireland, Japan, Malaysia, Netherlands, Sri Lanka, Sweden, the United Kingdom, and the United States. 

The OECD data is available for all 38 OECD members between 1960 and 2020, although coverage varies markedly between countries. The data is available here: https://stats.oecd.org/index.aspx?queryid=30116.

The original source of the World Bank data is: WHO, UNICEF, UNFPA, World Bank Group, and the United Nations Population Division. Trends in Maternal Mortality: 1990 to 2017. Geneva, World Health Organization, 2019. The data is available here: https://data.worldbank.org/indicator/SH.STA.MMRT.

We combined time-series for countries which had available in both the Gapminder and OECD datasets. When there were overlapping datapoints between the OECD and Gapminder datasets we preferentially used the Gapminder data.

Malaysia and Sri Lanka both had data from Gapminder and WHO, however, we found that the values for these two time-series were not well-aligned so we used only the WHO data.

For the United States there are missing data in both the OECD and Gapminder datasets between 2008 and 2017. For these years we supplement the time-series with the WHO dataset.
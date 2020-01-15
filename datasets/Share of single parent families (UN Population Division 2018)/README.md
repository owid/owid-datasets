# Share of single parent families (UN Population Division 2018)

The variable for the share of single parent families is taken from the <a href="https://population.un.org/Household/index.html#/countries/840">United Nations Database on Household Size and Composition (2018)</a>. 

The UN database pulls from 4 different sources: 
1) Demographic and Health Surveys (DHS); 
2) the Demographic Yearbook (DYB) of the United Nations; 
3) IPUMS-International;
4) Labor Force Surveys (LFS) of the European Union, Eurostat. 

Where a country time series was composed of multiple sources, we favoured the source covering the most years. In cases where there was a tie between sources, we favoured the DYB, then IPUMS, DHS, and lastly LFS estimates. The DYB covered the largest number of countries and the LFS the least.  

Where multiple country-year observations came from the same source, we favoured the observation with the reference date occurring later in the year. This is true for Senegal in 2013 and Tanzania in 2004.

The source for each observation can be found in the metadata spreadsheet <a href="https://owid.cloud/app/uploads/2020/01/un-single-parent-final-metadata-stan.csv">here</a>. 

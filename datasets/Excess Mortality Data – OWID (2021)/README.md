# Excess Mortality Data – OWID (2021)

All-cause mortality data is from the Human Mortality Database (HMD) Short-term Mortality Fluctuations project and the World Mortality Dataset (WMD). Both sources are updated weekly.

We do not use the data from some countries in WMD because they fail to meet all three of the following data quality criteria: 1) estimated coverage of at least 85% of deaths; 2) at least four years of historical data; and 3) data published either weekly or monthly. The full list of excluded countries and reasons for exclusion can be found in this spreadsheet: https://docs.google.com/spreadsheets/d/1JPMtzsx-smO3_K4ReK_HMeuVLEzVZ71qHghSuAfG788/edit?usp=sharing.

HMD has deaths data for all ages and broken down by broad age groups, while WMD has data for all ages only.

We used the raw weekly or monthly deaths data from HMD and WMD to calculate P-scores. The P-score is the percentage difference between the number of weekly or monthly deaths in 2020–2021 and the average number of deaths in the same period over the years 2015–2019 (for a small minority of countries only 2016–2019 are available). For Week 53 2020, which ended on 3 January 2021, we compare the number of deaths to the average deaths in Week 52 over the years 2015–2019, because only one previous year (2015) had a Week 53.

We calculate the number of weekly deaths for the United Kingdom by summing the weekly deaths from England & Wales, Scotland, and Northern Ireland.

For important issues and caveats to understand when interpreting excess mortality data, see our excess mortality page at https://ourworldindata.org/excess-mortality-covid.

For a more detailed description of the HMD data, including week date definitions, the coverage (of individuals, locations, and time), whether dates are for death occurrence or registration, the original national source information, and important caveats, see the HMD metadata file at https://www.mortality.org/Public/STMF_DOC/STMFmetadata.pdf.

For a more detailed description of the WMD data, including original source information, see their GitHub page at https://github.com/akarlinsky/world_mortality.
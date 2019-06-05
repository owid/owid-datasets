# Political Regimes — V-Dem (2019)

For each year 1900–2018, the V-Dem Project (v9, 2019), variable "Regimes of the world – the RoW measure (D) (v2x_regime)", classifies each country as one of four possible regimes:

0. Closed autocracy
1. Electoral autocracy
2. Electoral democracy
3. Liberal democracy

The V-Dem Project makes these classifications based on a number of other measures. For details, see p. 254 of their "V-Dem Cookbook v9".

The dataset "Political Regimes — V-Dem (2019)" simply reproduces this v2x_regime classification. (For how this dataset was produced, see: https://drive.google.com/open?id=1eFZmRChBFmeAXLx0tQ965YOHlXe6WQH_.)

Below are just some notes on several peculiar "countries" in the V-Dem Project dataset.

First, there are three separate Palestines, namely:

- "Palestine/British Mandate"  (v2x_regime coding available for the years 1914–48): coded as 0 (closed autocracy) every year.
- "Palestine/Gaza" (1948–66 and 2007–18): 0 every year.
- "Palestine/West Bank" (1948–49 and 2003–18): 0 in 1948–49, 2008–12, and 2015–18; 1 in all other years.

We at OWID have decided to drop Palestine/British Mandate for 1948.

Second, there are Somalia and Somaliland:

- Somaliland (1900–2018): Coded as 0 in 1900–2002; 1 in 2003–09 and 2013–18; and 2 in 2010–12.
- Somalia (1900–2018): 1 in 1956–69 and 1980–83; 0 in all other years.

Thus, in this dataset, "Somalia" excludes Somaliland.

Third, there are Tanzania and Zanzibar:

- Zanzibar (1905–2018): 0 in 1905–94 and 1 in 1995–2018 = 1. 
- Tanzania (1915–2018): 0 in 1915–61, 1 in 1962–94, 2 in 1995–2000, 1 in 2001–07, 2 in 2008, 1 in 2009, 2 in 2010–15, 1 in 2016–17, 2 in 2018.

Thus, in this dataset, "Tanzania" excludes Zanzibar.

Fourth, for 1990 and before, "Yemen" refers to North Yemen. There are separate data for "South Yemen" for the years 1900–90.
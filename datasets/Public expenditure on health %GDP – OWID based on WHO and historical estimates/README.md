# Public expenditure on health %GDP – OWID based on WHO and historical estimates

Definitions

The definition used by the World Health Organization (WHO) stipulates: “Public health expenditure consists of recurrent and capital spending from government (central and local) budgets, external borrowings and grants (including donations from international agencies and nongovernmental organizations), and social (or compulsory) health insurance funds.”

In some studies and reports, capital expenditure is not included as part of total expenditure (public or private). This is the case, for example, with OECD figures. However, in this dataset we take the WHO definition as a basis, and hence capital expenditures are included.

Whether reporting agencies include capital expenditure as part of healthcare expenditure depends on the System of Health Accounts (SHA) that is in place. The OECD figures use the SHA 2011, which is the latest revision. The WHO figure use a previous version.

While it is widely accepted that the SHA 2011 is superior to previous versions, many countries still use previous versions. This means there is a tradeoff between coverage across countries, and data quality. In the interest of coverage, we have chosen to rely on WHO definitions.

Handling of underlying sources

This dataset was constructed by combining four sources. These are Lindert (1994), OECD (1993), OECD.stat. and the WHO Global Health Expenditure Database (WHO GHED)

These four sources were combined as follows.

For the period 1995-2015 we report the figures as published in WHO GHED.
For the period 1970-1994, we extended the recent figures (from WHO GHED) backwards by using the rates of change as reported in OECD.stat.
For the period 1960-1969, we continue extending backwards by using the rates of change as reported in OECD (1993)
For the period 1880-1930, we report observations from Lindert (1994).
To be precise, the process of extrapolation consisted in taking the earliest available observation from WHO GHED, and then successively extending the series backwards; first by using the year-by-year rate of change implied by the estimates in OECD.stat, for the period 1970-1994; and then using the year-by-year rate of change in OECD (1993), for the period 1960-1969. Here is an example:

WHO_(year-1)= WHO_year x [OECD.stat_(year-1)]/[OECD.stat_(year)]

Backward extrapolation was necessary because the levels in the estimates from WHO GHED, OECD.stat and OECD (1993) do not exactly coincide for the overlapping years. This is partly because OECD.stat data does not include capital expenditure.

The implicit assumption in our constructed dataset, then, is that the estimates from these three series have different levels, but common trends. Empirically, the validity of this assumption is supported by the trends in the overlapping years.
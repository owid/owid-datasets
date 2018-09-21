# Social Expenditure in the long run - Lindert 2004; OECD 1985; OECD (SOCX).

Definitions

Social spending includes, among others, the following areas: health, old age, incapacity-related benefits, family, active labor market programmes, unemployment, and housing. In some studies and reports, education is included in social spending. This is not the case in this dataset.

Handling of underlying sources

This dataset was constructed by combining three sources. These are the OECD Social Expenditure Database (OECD SOCX), OECD (1985) and Lindert (2004).

These three sources were combined as follows. For the period 1980-2016 we report the figures as published in OECD SOCX. For the period 1960-1979, we extended the recent figures (from OECD SOCX) backwards by using the rates of change as reported in OECD (1985). And for the period 1880-1930, we took observations from Lindert (2004).

To be precise, the data for the period 1960-1979 was obtained by relying on the earliest available observation from OECD SOCX, and then successively extending the series backwards by using the year-by-year rate of change implied by the estimates in OECD (1985). Here is an example:

OECD_SOCX_(Year-1) = [OECD_SOCX_(Year)] x [OECD_1985_(year-1)]/[ OECD_1985_(year)]

Backward extrapolation for the period 1960-1979 was necessary because the levels in the estimates from OECD SOCX and OECD (1985) do not exactly coincide for the overlapping years. The implicit assumption, then, is that the estimates from OECD SOCX and OECD (1985) have different levels, but common trends.

In this visualization (https://ourworldindata.org/grapher/various-measures-of-social-expenditure-as-share-of-gdp?country=AUS) you can see how the various underlying sources compare to our constructed series.

Further remarks

According to the Manual to the OECD Social Expenditure Database (SOCX), the OECD defines social expenditure as “The provision by public and private institutions of benefits to, and financial contributions targeted at, households and individuals in order to provide support during circumstances which adversely affect their welfare, provided that the provision of the benefits and financial contributions constitutes neither a direct payment for a particular good or service nor an individual contract or transfer”

The series on Social expenditure for France and Denmark in OECD(1985) are not complete. However, Lindert (2004) uses the data available to estimate social expenditure in 1960 and 1970. Therefore, we use his estimations to extrapolate backwards for those two points in time.

In OECD (1985) social expenditure figures include expenditure on education. To ensure consistency with Lindert (2004) and OECD (SOCX), we subtracted education.
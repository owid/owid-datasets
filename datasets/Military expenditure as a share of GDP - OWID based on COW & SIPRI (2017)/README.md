# Military expenditure as a share of GDP - OWID based on COW & SIPRI (2017)

The National Material Capabilities dataset, from the Correlates of War (COW) Project, contains long-run estimates of the military power of countries.

The COW data series on military expenditure ends in 2012 and it is measured in current currency units; specifically British Pounds up to the year 1914, and US Dollars thereafter. This reflects the fact that the COW data was originally intended for cross-country comparisons at specific points in time, rather than for tracking changes in military expenditure over the long-run.

Considering this, at Our World in Data we have produced a new dataset, based on the COW data, which does allow for comparisons both across countries and time. Here is a description of what we have done. 
<ol>
	<li>We first took the COW dataset and used historical exchange rates from the Bank of England to unify the entire series into a single currency (nominal British Pounds).</li>
	<li>Then we converted this series into shares of GDP. For this we used historical cross-country estimates of nominal GDP, also available in British Pounds from the CEPII research centre.</li>
	<li>Finally, we extended the series forward up until 2016 by appending data from SIPRI, as published in the World Bank's World Development Indicators <a href="https://data.worldbank.org/indicator/MS.MIL.XPND.GD.ZS?page" rel="noopener" target="_blank">here</a>.</li></ol>
Please note that we use exchange rates from the Bank of England because the original exchange rates used to produce the COW estimates are not available. While we are aware that this introduces noise to the series, we believe that this does not affect trends or levels in any systematic way. It simply adds to the margin of error that historical estimates already had.

Also note that the entity 'World' shows values from SIPRI for the period 1960-2016. 
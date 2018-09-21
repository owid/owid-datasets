# Penn World Table 9.0 - OWID's team elaboration

Penn World Table is a database with information on relative levels of income, output, input and productivity, covering 182 countries between 1950 and 2014. A brief presentation on the project is available on voxeu.org http://voxeu.org/article/recasting-international-income-differences-next-generation-penn-world-table . New versions of the Penn World Table are updated regularly. The most recent one, employed to build this dataset, was published in 2015.

List of variables and how these were manipulated:

PWT's country names were modified according to OWID standardized country names.

Total GDP (output):Output-side real GDP at chained PPPs (in unit 2011US$). Calculated multiplying PWT(9.0)'s variable "rgdpo" by 1.000.000.

Total GDP (expenditure): Expenditure-side real GDP at chained PPPs (in unit 2011US$). Calculated multiplying PWT(9.0)'s variable "rgdpe" by 1.000.000.

Population: Population. Calculated multiplying PWT(9.0)'s variable "pop" by 1.000.000.

Living Standard GDP per Capita: Per Capita expenditure-side real GDP at chained PPPs. Calculated dividing Total GDP (expenditure) by Population.

Persons Engaged: Number of persons engaged. Calculated multiplying PWT(9.0)'s variable "emp" by 1.000.000.

Work Hours Per Person: Average annual hours worked by persons engaged. Present in PWT(9.0)'s as "avh".

Work Hours: Total number of work hours. Calculated multiplying "Work Hours per Person" by "Persons Engaged".

Labour Productivity: Labour Productivity. Calculated dividing "Total GDP (output)" by "Total number of work hours".

Share Of Labour Compensation: Share of labour compensation in GDP at current national prices. Present in PWT(9.0) as "labsh".

GDP Price Level: Price level of CCON (PPP/XR), price level of USA GDPo in 2011=1. Present in PWT(9.0) as "pl_con".

rgdpe: Expenditure-side real GDP at chained PPPs (in mil. 2011US$). Present in PWT(9.0) as "rgdpe".

rgdpo: Output-side real GDP at chained PPPs (in mil. 2011US$). Present in PWT(9.0) as "rgdpo".

pop: Population (in millions). Present in PWT(9.0) as "pop".

emp: Number of persons engaged (in millions). Present in PWT(9.0) as "emp".

ctfp: TFP level at current PPPs (USA=1). Present in PWT(9.0) as "ctfp".

cwtfp: Welfare-relevant TFP levels at current PPPs (USA=1). Present in PWT(9.0) as "cwtfp".

rtfpna: TFP at constant national prices (2011=1). Present in PWT(9.0) as "rtfpna".

rwtfpna: Welfare-relevant TFP at constant national prices (2011=1). Present in PWT(9.0) as "rwtfpna".

Statcap: Statistical capacity indicator (source: World Bank, developing countries only). Present in PWT(9.0) as "Statcap".
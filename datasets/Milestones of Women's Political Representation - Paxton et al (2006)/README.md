# Milestones of Women's Political Representation - Paxton et al (2006)

Data description:
Paxton’s data is downloaded from the Inter-university Consortium for Political and Social Research (ICPSR). It provides country-level data on the start and end year of sovereignty; year in which universal suffrage was granted to all women; the year the first woman was elected to parliament; and percentage share of women in parliament for the years 1893-2003. OWID updates their data through to 2017 using Inter-parliamentary union (IPU) statistical archives and the World Bank’s World Development Indicator (WDI) variable on women’s share in parliament (main sources). 
Data from 2003 onwards was derived from various other sources. IPU’s statistical archives were used to derive figures on the share of women in parliament (from 2004-2017); the CIA World Factbook provided data on the year of sovereignty and universal suffrage, alongside various additional sources which are listed below. Moreover, data extension to 2017 means that our dataset consists of five additional countries: Libya, Montenegro, Serbia, South Sudan and Timor, which gained independence after 2003.

Data construction:
Paxton et al (2006) describes women’s political representation as the share of sovereign countries which satisfied the five representation milestones in any given year. Therefore, we have constructed this dataset which indicates the status of sovereign countries using the values "Yes" and "No". More specifically, if the year of universal suffrage is less than 1990 for the United States, we coded ‘Universal suffrage to women’ in the United States in 1990 as Yes. Note that the United States had gained sovereignty by then. 
In addition, our dataset doesn’t consider these milestones as ordered achievements in women’s political representation. Paxton et al (2006) assumed that a country can only elect a woman MP once the universal suffrage has been granted. However, there are countries whereby a female MP was elected prior to gaining universal suffrage. Therefore, we calculate values for each milestone independently and map countries as per the original source definition of sovereign.

Additional data sources: 
This section provides detailed information on the sources used by variables and countries.

Year of sovereignty 
CIA’s World Factbook Independence field is used to determine the year of sovereignty for Libya, Montenegro, Serbia, South Sudan, Timor, American Samoa, Hungary and Iran. Likewise, we determine end of sovereignty for Libya and Serbia and Montenegro using the same source. Available at: https://www.cia.gov/library/publications/the-world-factbook/fields/2088.html [accessed 16th August 2017].
Year of universal suffrage
Kuwait, Oman and Qatar: UNICEF Gender Equality Profiles. Available at: https://www.unicef.org/gender/gender_62215.html [accessed 16th August 2017].
Libya, Serbia (mentioned as Serbia and Montenegro), Montenegro (mentioned as Serbia and Montenegro), South Sudan (mentioned as Sudan), Timor and American Samoa. IPU’s Women in Politics. Available at: http://www.ipu.org/PDF/publications/wmn45-05_en.pdf [accessed 16th August 2017].
Saudi Arabia and United Arab Emirates. CIA’s World Factbook Suffrage field. Available at: https://www.cia.gov/library/publications/the-world-factbook/fields/2123.html [accessed 16th August 2017].
Brunei: Wikipedia.
Year of first woman elected to parliament
Timor, Latvia and American Samoa: IPU’s Women in Politics. Available at: http://www.ipu.org/PDF/publications/wmn45-05_en.pdf [accessed 16th August 2017].
Oman, Palau, Saudi Arabia, Qatar, UAE and Tanzania: IPU’s Women in Parliament Annual Reviews.
Serbia, Montenegro, Nigeria and South Sudan: IPU’s Parline. Available at: http://www.ipu.org/parline-e/parlinesearch.asp [accessed 16th August 2017].
Kuwait: The Guardian. Available at: https://www.theguardian.com/world/2009/may/17/kuwait-women-elected-parliament [accessed 16th August 2017].
Libya: Libyan House of Representatives. Available at: https://www.temehu.com/house-of-representatives.htm [accessed 16th August 2017].
Sierra Leone: Pathways of Women’s Empowerment, Institute of Development Studies, University of Sussex, UK. Available at: https://assets.publishing.service.gov.uk/media/57a08ac5ed915d3cfd00092c/CS_Women_and_Politics_SL.pdf [accessed 16th August 2017].
Share of women in parliament 
IPU’s Statistical Archive (http://www.ipu.org/wmn-e/classif-arc.htm) for all countries from 2004 to 2017. For each year, we take the share of women in lower house of the parliament. This definition matches both with WDI and IPU’s Women in Parliament 1945-1995. They use the share of women in single house for unicameral parliaments and lower house for bicameral parliaments. Moreover, for consistency, data is taken from December every year. If December data is missing, we take the next latest month of the corresponding year.
Handling data issues: 
For years 1997 - 2003, there is an overlap between Paxton’s dataset and WDI data measuring the share of women in parliament. For most countries, the values match exactly. However, there are 20-40 countries each year where the Paxton and WDI values do not match. As the more complete and comprehensive dataset, we have taken Paxton’s dataset as our primary source in such cases for the period 1997-2003. Nonetheless, we use WDI to fill the remaining gaps. For the same reasoning, we choose manually collected data from IPU’s statistical archive over WDI for the years 2004-2016.
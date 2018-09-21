# Women’s Political Representation using Paxton et al (2006), IPU (2017) & WDI (2017) 

Data construction:
Paxton et al (2006) provides data on five milestones of women’s political representation from 1893 to 2003. Our dataset updates their data through to 2017 using Inter-parliamentary union (IPU) statistical archives and the World Bank’s World Development Indicator (WDI) variable on women’s share in parliament (main sources).

Paxton’s data is downloaded from the Inter-university Consortium for Political and Social Research (ICPSR). It provides country-level data on the start and end year of sovereignty; year in which universal suffrage was granted to all women; the year the first woman was elected to parliament; and percentage share of women in parliament for the years 1945-2003. Data from 2003 onwards was derived from various sources. IPU’s statistical archives were used to derive figures on the share of women in parliament (from 2004-2017); the CIA World Factbook provided data on the year of sovereignty and universal suffrage, alongside various additional sources which are listed below. Moreover, this data extension to 2017 means our dataset consists of five additional countries: Libya, Montenegro, Serbia, South Sudan and Timor, which gained independence after 2003. Paxton et al (2006) describes women’s political representation as the share of sovereign countries which satisfied the five representation milestones in any given year. We have therefore derived the number of sovereign countries generated in any given year, as well as the number which have attained each of the five milestones.

To overcome methodological differences, the attainment of milestones was assessed in two ways. Firstly, the number and share of sovereign countries were assessed relative to ‘ordered’ milestones. This results from Paxton et al’s (2006) assumption that a country only has an elected woman MP after universal suffrage is granted. However, there were 17 countries - Australia, Belgium, Brazil, Canada, Guinea-Bissau, Hungary, Ireland, Netherlands, Norway, Portugal, Samoa, Saudi Arabia, Socialist Federal Republic of Yugoslavia, South Africa, USSR, United Kingdom, and the United States – whereby a female MP was elected prior to gaining universal suffrage. Secondly, we assessed the number and share of sovereign countries which independently satisfied five milestones.

Additional information on data sources: 
This section provides detailed information on the sources used by variables and countries.

Sovereignty 
CIA’s World Factbook Independence field is used to determine the year of sovereignty for Libya, Montenegro, Serbia, South Sudan, Timor, American Samoa, Hungary and Iran. Likewise, we determine end of sovereignty for Libya and Serbia and Montenegro using the same source. Available at: https://www.cia.gov/library/publications/the-world-factbook/fields/2088.html [accessed 16th August 2017].
Universal Suffrage
Kuwait, Oman and Qatar: UNICEF Gender Equality Profiles. Available at: https://www.unicef.org/gender/gender_62215.html [accessed 16th August 2017].
Libya, Serbia (mentioned as Serbia and Montenegro), Montenegro (mentioned as Serbia and Montenegro), South Sudan (mentioned as Sudan), Timor and American Samoa. IPU’s Women in Politics. Available at: http://www.ipu.org/PDF/publications/wmn45-05_en.pdf [accessed 16th August 2017].
Saudi Arabia and United Arab Emirates. CIA’s World Factbook Suffrage field. Available at: https://www.cia.gov/library/publications/the-world-factbook/fields/2123.html [accessed 16th August 2017].
Brunei: Wikipedia.
First woman elected to parliament
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
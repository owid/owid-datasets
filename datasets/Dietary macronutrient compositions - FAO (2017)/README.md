# Dietary macronutrient compositions - FAO (2017)

Dietary compositions calculated by the OWID author (Hannah Ritchie) based on food supply statistics from the UN Food and Agricultural Organization database: FAOstat.

The FAO provide annual figures from 1961 by country on daily caloric supply, fat supply (in grams), and protein supply (in grams). To calculate the daily per capita supply of carbohydrates, we assumed an energy density by macronutrient of 4 kcal per gram of both protein and carbohydrate and 9 kcal per gram of fat (based on established nutritional guidelines reported by the FAO). The daily supply of carbohydrates was therefore calculated as:

((Daily supply of kcal)-(Daily supply of protein * 4 + Daily supply of fat * 9)) / 4

The quantity of calories from each macronutrient was then calculated based on the energy density figures given above (e.g. calories from protein was calculated by multiplting the daily supply of protein in grams by 4).

The share of calories derived from each macronutrient could then be calculated by dividing the number of calories derived from a given macronutrient by the total daily caloric supply.

Protein of animal origin includes protein supplied in the form of all meat commodities, eggs and dairy products, and fish & seafood. Protein of plant origin was dervied as the difference between total protein supply and that of animal origin.

References:

UN Food and Agricultural Organization FAOstat food balance sheets. Available at: http://www.fao.org/faostat/en/#home [accessed 31st July 2017].

Chapter 3: Calculation Of The Energy Content Of Foods - Energy Conversion Factors. Food and Agriculture Organization of the United Nations. Available at: http://www.fao.org/docrep/006/Y5022E/y5022e04.htm [accessed 31st July 2017].
# EDA_fatal_shootings

## **GOAL** - EDA of the Washington Post’s data on Fatal Police Shootings.

- check what is the scale of the phenomenon
- find any patterns related to fatal shootings

## **Method and techniques:**
- investigation of the dataset - what kind of features are available, their types, distribution
- cleaning (handling missing values, duplicates, outliers)
- visualisation with matplotlib, seaboarn, plotly
- geopandas - for generating missing GPSs
- prophet - for predicting what number of police shooting will be present until the end of year 2021 and during 2022
- k-means clustering for checking if there is any similarity present across the region of victims’ death.

## **CONCLUSIONS:**

*Ethnicity*
- I successfully conducted prediction of ethnicity of the victim for whom the race were unknown.
- Ethnicity analysis could at first sight lead to wrong conclusions: the highest amount of victims are of white race, however, taking into account the whole population of US, the most common race of the victim is black, then hispanic.

*Time of shots*
- There is no trend of the highest/lower amount of the victim in terms of part of the year/season/Bank Holiday - so the total amount of the victim/month is random.
- A cummulative sum of the number of victims/year is stable year to year with hope for the smaller amount of the victim for 2021.

*Geographical analysis*
- I was able to localize GPS of the place of death based on the city name and state.
- Geographical distribution of data needs to be performed carefully with the population and total area of the state took into account. 
- The most dangerous cities are Los Angeles, Miami and Houston.

*Other conclusions*
- Typical victim was: white man, age 37, armed with gun.
- Only 15% of the cases were recorded, however only in 60% of the cases, police officer was under attack.
A majority of victims were armed, that may cause police officer to act in self-defense.

## **CALL TO ACTION**

There could be some solutions taken into account while providing new strategy to limit the number of fatal shootings:
>* more police officers should be on duty in more dense cities 
>* body camera should be considered as a must-have tool during duty 
>* police officer should have trainings about cultural and race differences to better act in difficult situations with other race groups

Taking into account how many fatal police shootings take place in other well-developed countries as European countries: Switzerland (0!), Denmark (0!), Poland, Portugal, just to name a few, US has a tremendeous amount of victims. 

It could be caused by a 40-year-old law that allows police to shoot person when he 'thinks or sense' that his life is on threat. Maybe that is an issue - the law should be more restricted for police officer, that would also make them to think how to act differently. 

(Source: https://worldpopulationreview.com/country-rankings/police-killings-by-country, https://en.wikipedia.org/wiki/List_of_killings_by_law_enforcement_officers_by_country, https://www.prisonpolicy.org/blog/2020/06/05/policekillings/, https://www.aclu.org/blog/criminal-law-reform/reforming-police/supreme-court-gives-police-green-light-shoot-first-and, https://www.americanbar.org/news/abanews/publications/youraba/2018/november-2018/legal-fact-check--what-is-the-legal-standard-for-deadly-force-in/).



# Coursera_Capstone - Exploring the Ethnic Diversity of Restaurants in Mississauga

### Introduction
Canada is a country shaped by its immigrants and their descendants. Toronto, Vancouver and Montreal attract nearly 63% of the immigrant population, with most visible minorities living in urban centres. Toronto accounts for nearly 70% of the immigrant population among the three cities.
Mississauga is a city in the province of Ontario, west of Toronto — the provincial capital. Mississauga was initially called Toronto Township when it was purchased from the First Nations people (called Mississaugas) for 1000 pounds in 1805 but it wasn’t until 1974 that it was called Mississauga. Though historically most immigrants to Canada were from Europe, recently more numbers are observed from Asia, including Middle East Asia. Due to its proximity to Toronto, it is the sixth most populous city in Canada and it is popularly known to be a multi-cultural and a diverse city.
Mississauga specifically has 53.7% visible minorities. The three largest visible minorities in Mississauga are South Asians, Blacks and East Asians. Knowing this information, I want to perform an exploratory data analysis of the restaurants in Mississauga and see if the multicultural characteristic of the city is reflected in the diversity of the restaurants. I want to explore the multiculturalism and diversity of the city of Mississauga by using Foursquare API, and city of Mississauga census data.
Why Mississauga? As an immigrant to Canada, my family moved to Mississauga, it’s where I went to school and it is home to many other landed immigrants.

#### Problem: 
What insights can I gather from exploring the restaurants in Mississauga?


#### Interest: 
This project gives insight into the diversity of the city of Mississauga. Here I chose a venue type, restaurant, to see if and how much the variety of restaurants and their cuisine type is a reflection of the diversity of population.


The restaurants and immigrant population is divided into 6 groups, namely, European, South Asian, East Asian, Black, Middle Eastern and Latin American. The ‘non’-ethnic restaurants have been selectively excluded. For clarification, ‘European’ include all of Europe, including Russia, and Greece. Middle East includes north African and parts of Asia, ‘Latin’ includes South America, and Mexico and ‘Black’ includes Caribbean and Middle and Southern continent of Africa.

### Data Source:

##### Mississauga Data:

Data Source: https://www.geonames.org/postalcode-search.html?q=mississauga&country=CA&adminCode1=ON

Description: This contains the neighbourhoods within the city of Mississauga and their corresponding longitude and latitude as well as their zip code. This data source was used to find all restaurants by neighbourhood in Mississauga.

##### Restaurants in Mississauga:

Data Source: Foursqaure API

Description: This API will render all the venues in the city of Mississauga and the categories of each venue. This will help us with the data on the restaurants within the city. The search query term was ‘Food’. In the Foursquare API ‘Venue Category Hierarchy’ documentation, the term ‘Food’ yields all restaurants of a location inclusive of all ethnicities and cuisines.

##### Mississauga Population: 

Data Source: https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page.cfm?Lang=E&Geo1=CSD&Code1=3521005&Geo2=PR&Code2=01&Data=Count&SearchText=mississauga&SearchType=Begins&SearchPR=01&B1=All 

Description: I scarped this website for population data. It is the census profile  by Stats Canada for the city of Mississauga as of 2016 where I find the population of the city by the 'Ethnic Origin'.




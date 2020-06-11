# Coursera_Capstone - Restaurants in Mississauga as a measure of the city's diversity 
The contains all the projects associated with Coursera Data Science Capstone

### Introduction
Mississauga is a city in the province of Ontario, west of Toronto - the provincial capital. Due to its proximity to Toronto, it is the sixth most populous city in Canada and it is popularly known to be a multi-cultural and a diverse city. I want to explore the multiculturalism and diversity of the city of Mississauga by exploring the restaurants and gather the insights using the tools of Foursquare API, and City of Mississauga Neighbourhoods data. I want to explore the different variety of restaurants and find out if there is any correlation between types of restaurants and the immigrant/visible minority population. 

Why Mississauga? As an immigrant to Canada, my family moved to Mississauga and it is home to many landed immigrants to Canada. I want use restaurants as a measure of the diversity in the city of Mississauga. 

Mississauga was initially called Toronto Township when it was purchased from the First Nations people (called Mississaugas) for 1000 pounds in 1805 but it wasn’t until 1974 that it was called Mississauga. Toronto is among the three cities in Canada that attracts nearly 70% of the immigrant population. Though historically most immigrants to Canada were from Europe, recently more numbers are observed from Asia, including Middle East Asia. 

Canada is a country shaped by its immigrants and their descendants. Toronto, Vancouver and Montreal attract nearly 63% of the immigrant population, with most visible minorities living in urban centres, and Mississauga specifically has 53.7% visible minorities. As of 2011, the three largest visible minorities in Canada are South Asians, Chinese and Blacks and as of 2016, South Asian followed by Blacks and Chinese are the top 3 visible minorities in Peel Region. Mississauga accounts for 52% of the Peel region’s population. Knowing this information, I want to compare the types of restaurants in Mississauga and see if the multicultural characteristic of the city is reflected in the diversity of the restaurants. 

Problem: Can I use 'Restaurants' as a measure of diversity in the city of Mississauga? Is there a correlation between top 5 restaurant types (defined by cuisine) and the top 5 immigrant groups/visible minorities residing in the city? 

Interest: This project gives insight into the diversity of the city of Mississauga. Diversity can be measure by various metrics like population by country of origin of the residents in the city or the language spoken by the residents but here I chose a venue type, ‘Restaurants’, to see if and how much the variety of restaurants and their cuisine type is a reflection of the diversity in the city. This is of interest to those who want to explore the diversity of the city and also for those who want to know want to know if the statement made by the Canadian PM, "Diversity is Canada's Strength" really holds true when it comes to small businesses such as restuarants. 


### Data Source:

##### Mississauga Data:

Data Source: https://www.geonames.org/postalcode-search.html?q=mississauga&country=CA&adminCode1=ON

Description: this contains the neighbourhoods within the city of Mississauga and their corresponding longitude and latitude as well as their zip code. 

##### Restaurants in Mississauga:

Data Source: Foursqaure API

Description: This API will render all the venues in the city of Mississauga and the categories of each venue. This will help us with the data on the restaurants within the city. 

##### Mississauga Population: 

Data Source: https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page.cfm?Lang=E&Geo1=CSD&Code1=3521005&Geo2=PR&Code2=01&Data=Count&SearchText=mississauga&SearchType=Begins&SearchPR=01&B1=All 

Description: There are two sites that I scarped for data. One is the census profile  by Stats Canada for the city of Mississauga as of 2016 where I find the population of the city by the place of birth of immigrants.

Data Source: https://www.peelregion.ca/planning-maps/CensusBulletins/2016-immigration-ethnic-diversity.pdf 

Description: This is another census report for the same year 2016 by the Peel Region ‘2016 Census Bullitin Immigration and Ethnic Diversity’. Peel is the county that Mississauga resides in as of 2016. 


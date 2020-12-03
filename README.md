# Group 7 Final Project

## Background

Coronavirus Disease 2019(COVID-19) has caused an unprecedented threat to people’s health status on a global scale. And in our data visualization, we want to focus on the largest country in South America: Brazil, which is the world’s fifth-largest country by area and the sixth most populous. Until today, a total of almost 6.4 million COVID cases have been confirmed while 5.3 million of them have already recovered. 

## Objectives

We aim to thoroughly understand and visualize Brazil’s COVID cases evolution in multiple dimensions: chronologic, geographic and demographic and  to explore different pandemic modes in different regions, ethnicity groups and periods.

## Explored Directions

1. Covid spread within the first months
2. Mortality Rate and Cases per City and State
3. Impact of demographic factors (population / gdp) on mortality rate
4. Impact of human measures (testing capabilities / lockdown) on moratality rate
5. In-depth analysis of Covids development in Sao Paulo
6. Creation a clustering algorithm

## Description of Story

-Is it not an alarming situation by "John Bolsonaro". 
-Eight months later Brasil is the third countries in terms of COVID cases and the second one in term of COVID deaths, but how do brazil arrive to this alarming situtaion? 
-Beginning: north west of Brazil and around the south coast, in less than 2 month( 3rd april to 22 april) may some "region" with low population from the northest  end up with more than 3000 cases per 100k, 2 months later the virus has spread around all the country, mainly present in the south shore cities
-Continue our analysis: we observe a clear difference between the south and the north. north: more cases by 100k but less death, south: less cases but much more deaths, but south cities have much more gdp and population.
Important trend notice the almost perfect correlation between cases and deaths, intriguant? 
slide 5: what is the date? cause interpretion of the slide on state will change.
-Get dipper into this and try to understand how each state is performing in terms of cases absolute cases, SP curve is higher for any value of x --> probably mainly due to population , but that still does not explain the high death cases
- Focus on Sao Paulo: we can see that the mortality rate is higher in the coastal zone, the one of the metropole where are most of the population concentrated and the richer, Still don't explain the differnce between mortality per k and cases per k, but explain a bit better where the mortality per k is higher- big cities in this state, which mainly include Regional Capital and Metropole cities. Digging deeper in Sao Paulo, we could also find a positive correlation between population and daily morality rate.
- Apart from deomgraphic and geographic locations, how will human measures like test, treatment and lockdowns affect COVID situation in Brazil?
-beginning no test:no cases but high death, start introducing test: high case but low death, More cases means the virus spread fatser? More cases and more deaths means that the virus has evolved in a less virulent way?  more detected cases not neccesarilly means more cases, deaths might have lowered even if cases were higher because active cases might decrease, or testing might have permit to allow people to know if they are infected and then not transfer them to susceptible/weak people.
-Preferntial treatment for capital: Brasilia has much more cases than Sao Paulo while it has a much lower daily mortality. Is it due to the fact that people in the capital are more preferential for governement's treatment?  Explain first graph about the spread in covid in the north?
-Effect of lockdown: cases higher even after highlit the differnce between actual cases and tested cases+ incubation period, deaths explains by the same phenomena of incubation and that during the lockdown the Brazilian goverment appears to prepare enough for the cases resurgence. 
-Clustering: we used machine learning algorithum as k-means method to train and divide our cases into an optimized number of four clusters. And we find that the fourth cluster of cities in red which we predict to suffer most from the virus actually have the highest mortality rate.




## Datasets
1.	https://www.kaggle.com/unanimad/corona-virus-brazil	
2.  https://www.ibge.gov.br/geociencias/organizacao-do-territorio/15774-malhas.html?=&t=acesso-ao-produto
3.  https://www.ibge.gov.br/estatisticas/sociais/populacao/9103-estimativas-de-populacao.html?=&t=resultados
4.  https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9088-produto-interno-bruto-dos-municipios.html?=&t=downloads
5.  https://sidra.ibge.gov.br/Tabela/3563
6.  http://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/leiintbr.def

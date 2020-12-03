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

"_It is not an alarming situation_" - Jair Bolsonaro, President of Brazil (26th January 2020)

Eight months later Brazil has reached a grim winners podium, ranking third in terms of total COVID cases and second in COVID related deaths worldwide. Through this visual analysis we want to retrace the spread and influential factors that played a role during the last months of this pandemic.

Looking at the procedural spread of Covid, one can see that the disease originated in international hubs - São Paulo and Rio de Janeiro - quickly reaching the capital - Brasilia. Following small-scale, local, expansions in these areas, the hotspot of the pandemic, however, moved towards Brazil's lowly populated northern region. After two months, the Virus reached most of Brazil, hitting the highly populated southern shore especially hard. After a closer look at these differing trends, the South, maily a rich region of Brazil, has one of the highest mortality rates. Notwithstanding, this region has the lowest number of cases per one hundred thousand inhabitants in the whole country!

When looking at the southern states, São Paulo distinguishes itself from the other states by having a significantly higher population and relatively low number of cases per 100.000 inhabitants. In addition, when comparing the development of the pandemics across this region, we can see that São Paulo by far outgrew other states in terms of cumulative number of cases as well as in the speed of the spread.

Now focusing on São Paulo, we can observe that mortality rate is higher in the coastal zone, where the state's metropolises and thus the majority of the population is concentrated. Although this doesn't explain the difference between the high rate of mortality and low number of cases per 100.000 inhabitants, it shows that the mortality is higher in big regional capitals and metropolitan cities. Furthermore, we could also find a positive correlation between population and daily mortality rate, which explains our initial findings.

By looking at São Paulo's daily trends, we identified an interesting phenomena. While a usual country's deaths peak around two or three weeks after cases have peaked, this trend was shown reversely. Thus indicating that there was an external factor influencing these trends. 

Local news suggest that the testing rate in São Paulo was [significantly scaled up around the 14th of May](https://g1.globo.com/sp/sao-paulo/noticia/2020/04/20/sp-tera-testagem-em-massa-para-coronavirus-a-partir-de-15-de-maio-segundo-vice-governador.ghtml), which could mean a more even distribution of COVID tests among heavy- and mild-symptoms. Thus, offering a possible situation for the decrease in mortality. On the other hand, there is also an interesting distribution of testing across Brazil. Brasilia has considerably more cases than São Paulo, while at the same time having a much lower daily mortality. News on the 18th of June say that while [São Paulo had only tested 1.31% of the population, Brasilia reached 10% of its inhabitants](https://agenciabrasilia.df.gov.br/2020/06/18/df-ja-testou-10-da-populacao-para-covid-19/), exceeding numbers even from the United States. The question that arises is whether Brasilia had a preferential treatment for being the capital of the country.

When the testing rate scaled up and hence more cases detected, Brazilian government took more stringent actions such as a lockdown.  Daily trends of cases, deaths and mortality, for São Paulo graphically show the effect of lockdown in the state. According to the state government, [São Paulo passed 3 million COVID-19 tests](https://www.saopaulo.sp.gov.br/ultimas-noticias/governo-de-sao-paulo-atualiza-informacoes-sobre-o-combate-ao-coronavirus-4/) on the 14th of August, having a daily increase of 3000% in testing. This highlights the difference between tested cases before and after the lockdown, where mortality decreased but the number of cases increased. 

Finally, we used a machine learning algorithm based on k-means to divide the cities in Brazil into clusters, trying to categorize them based on their COVID-19 and demographic statistics. Clusters 3 and 4 represent cities that still have a high number of cases and deaths, but a low mortality rate. Cities in cluster 4 are specifically Rio and São Paulo, highly populated and dense cities. On the other hand, group 3 consists of medium sized cities, maily capitals of states, that are spread throughout the country. Clusters 1 and 2 consist of small towns, with low daily cases and deaths. However, cluster 2 shows a higher mortality rate than 1.

## Datasets
1.	https://www.kaggle.com/unanimad/corona-virus-brazil	
2.  https://www.ibge.gov.br/geociencias/organizacao-do-territorio/15774-malhas.html?=&t=acesso-ao-produto
3.  https://www.ibge.gov.br/estatisticas/sociais/populacao/9103-estimativas-de-populacao.html?=&t=resultados
4.  https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9088-produto-interno-bruto-dos-municipios.html?=&t=downloads
5.  https://sidra.ibge.gov.br/Tabela/3563
6.  http://tabnet.datasus.gov.br/cgi/deftohtm.exe?cnes/cnv/leiintbr.def

# **Watch Out: Do the Airbnb Prices in Amsterdam Increase Rapidly?**
### *To what extent does the neighbourhood popularity influence the prices of listings in Amsterdam?*

### **Research Motivation**
Airbnb is one of the largest platforms for sharing accomodations worldwide and is operating in 100,000 cities and towns around the world (Airbnb, 2021). Admiak (2018) found that most of the listings in European cities, are centered around major tourist cities. Airbnbs in these cities are evidently located and spread over different neighbourhoods. According to Can (1992), the price of a listing will be determined based on two characteristics: the physical characteristics, such as number of bath and bedrooms, and by variables related to the neighbourhood. Neighbourhoods thus play a significant role in determining the price of a listing. In many cities, there are up-and-coming neighbourhoods. Airbnb hosts who are aware that a particular neighbourhood is becoming more popular, could obviously benefit from this change in popularity. A price increase of a few euros will most likely not be noticed by people who book an Airbnb. The question which arises from this is therefore whether the popularity of neighbourhoods affects the price of listings. This research is conducted over the city Amsterdam, and could in the future also be conducted over other cities. 

### **Repository Overview**
Provide an overview of the directory structure and files, for example:

├── README.md
├── data
├── gen
│   ├── analysis
│   ├── data-preparation
│   └── paper
└── src
    ├── analysis
    ├── data-preparation
    └── paper

### **Running Instructions**
The running instructions can be found [here](https://github.com/sannejansen/Airbnb_Holmes/blob/my_project/Project%20documentation.md).
 
### **Method, Results and Conclusion**
We decided to look at a possible causal relationship between the popularity of a neighbourhood and the price of a listing in Amsterdam. Therefore we have the price difference percentage over time by neighbourhood, compared to all neighbourhoods. After conducting our research we have come to a number of conclusions. Since it was not possible to analyze the number of listings in a given district over time, we made the following assumption: the popularity of a neigbourhood depends on the number of listings in that particular neighbourhood. By making this assumption, these are the five most popular neighbourhoods in Amsterdam:
1. Centrum-West
2. De Baarsjes - Oost-West
3. Centrum-Oost
4. De Pijp - Rivierenbuurt
5. Westerpark

As can be seen in the following table:

| Neighbourhood | Number of Listings in Neighbourhood |
| ------------- | ------------- |
| **Centrum-West** | **870** |
| **De Baarsjes – Oud-West** | **803** |
| **Centrum-Oost** | **618** | **618** |
| **De Pijp– Rivierenbuurt** | **553** |
| **Westerpark** | **371** |
| Zuid | 366 |
| Oud-Oost | 313 |
| Oud-Noord | 251 |
| Bos en Lommer | 248 |
| Oostenlijk Havengebied – Indische Buurt | 205 |
| Ijburg – Zeeburgereiland | 160 |
| Watergraafsmeer | 147 |
| Noord-West | 136 |
| Slotervaart | 101 |
| Noord-Oost | 93 |
| Geuzenveld – Slotermeer | 83 |
| Buitenveldert – Zuidas | 56 |
| De Aker – Nieuw Sloten | 50 |
| Gaasperdam – Driemond | 44 |
| Osdorp | 36 |
| Bijlmer-Centrum | 33 |
| Bijlmer-Oost | 19 |
 

The mean of the prices of the listings in a specific neigborhood from the first week are compared to the prices of the listings in the same neigborhood in the last week of this year, to measure percent change in the price. The results are as followed:
| **Neigborhood** | **% Price Change** |
| ------------ | -------------|
| Centrum-West  |	-17.58% |
| De Baarsjes – Oud-West |	-13.80% |
| Centrum-Oost	| -20.73% |
| De Pijp – Rivierenbuurt |	-4.76% |
| Westerpark |	-5.80% |
| Zuid	| -21.33% |
| Oud-Oost | -14.53% |
| Oud-Noord	| -12.06% |
| Bos en Lommer | -11.18% |
| Oostenlijk Havengebied – Indische Buurt | -14.07% |
| Ijburg – Zeeburgereiland |	-3.80% |
| Watergraafsmeer |	-1.50% |
| Noord-West | -6.64% |
| Slotervaart | -59.27% |
| Noord-Oost | +2.62 |
| Geuzenveld – Slotermeer |	-7.97% |
| Buitenveldert – Zuidas |	-13.98% |
| De Aker – Nieuw Sloten | -6.85% |
| Gaasperdam – Driemond	| +3.81% |
| Osdorp | -22.07% |
| Bijlmer-Centrum | +2.19% |
| Bijlmer-Oost |	-16.57% |


After seeing these results, it can be concluded that most of the listings were priced lower at the end of the year, compared to the beginning, also in the popular neigborhoods. In this case it cannot be concluded that the popularity of a neigborhood affects the price of a listing. A possible explanation for the decrease in price, might be COVID-19. In order to keep attracting people, it is possible that the prices have been reduced during this period. To get a better insight, it would be interesting to redo the analysis, with data unaffected by COVID-19.

### **Literature**
- Admiak, C. (2018). Mapping Airbnb supply in European cities. *Annals of Tourism Research*, 71(c), 67–71. [https://doi.org/10.1016/j.annals.2018.02.008](https://doi.org/10.1016/j.annals.2018.02.008)
- Airbnb. (2021, December 31). *About us*. Airbnb Newsroom. Retrieved from [https://news.airbnb.com/about-us/](https://news.airbnb.com/about-us/)
- Can, A. (1992). Specification and estimation of hedonic housing price models. *Regional Science and Urban Economics*, 22(3), 453–474. [https://doi.org/10.1016/0166-0462(92)90039-4](https://doi.org/10.1016/0166-0462(92)90039-4)


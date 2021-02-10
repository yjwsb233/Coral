# Coral Mapping Project Proposal
Welcome to the page of Haiqi's Coral Reef mapping project! Below is an image of __coral bleaching__, which happens when corals are met with external stimuli, such as elevated temperature, and begin to die. In this [link](https://oceanservice.noaa.gov/facts/coral_bleach.html#:~:text=Warmer%20water%20temperatures%20can%20result,bleaches%2C%20it%20is%20not%20dead), you can find a brief introduction to coral bleaching provided by the National Oceanic and Atmospheric Administration.
![alt text](https://github.com/yjwsb233/Coral/blob/main/Pasted_image_at_2017_04_18_03_43_PM.0.jpeg)

## Introduction
As a scuba diver myself, I am very concerned by the increased rate of coral bleaching happening around the world. In several of my dives in Bali, Indonesia, I noticed many bleaching corals. I have recently watched the Netflix documentary _Chasing Coral_ (2017) and felt the need to learn more about the factors contributing to the death of corals besides global warming. While global warming is the main cause of coral bleaching, I beleive it is possible to gain some insight into other causes of global bleaching by looking at the __global demographic distribution and other anthropogenic threats__. Of course, many of the factors are interrelated and may contribute to global warming in different ways, so this project will provide insight into which factors might be the most significant. The __scale__ of my project would therefore be global, but there would also be specific case studies focusing on certain areas where bleaching is more severe. 

## Data 
### Coral Bleaching
I was lucky to find a dataset of global coral bleaching on the Harvard Dataverse website. The dataset, titled [__Coral Bleaching Data__](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/KUVQKY/PAMLRZ), consists of coral bleaching data spanning from the year 1963 to 2012. Although each year has a different number of data entries, I believe it is still possible to compare the bleaching status of corals in the same place inn different times. Obviously, one of the drawbacks of the dataseet is that it does not include any information after 2012, which means that some of the hottest years for corals are not recorded here. What is more, the fact that there is no recent data means that the dataset will not be able to show the impact of the pandemic on the global environment and, as a result, on coral reefs around the world. Despite this, however, the dataset is still comprehensive enough to demonstrate how coral reefs respond to different environments. It also provides the latitudes and longitudes of the places where coral surveys were conducted, which means that a map could easily be created to show the extent to which coral bleaching occurs across the globe. Below is an map I created based on the severity of coral bleaching in 2010.
![alt text](https://github.com/yjwsb233/Coral/blob/main/download%20(1).png)

### Population Distribution 
The second dataset that I will use is a GeoJSON file that documents the the population og each country in the world from 1960 to 2019. The dataset was created by Yoh because it seems that we are unable to find an exisdting GeoJSON file of world population on the Internet. It is very helpful in the sense that it covers the whole time span that the coral bleaching dataset covers. What is more, this file has a gelospatial component, which means that it can be combined to other datasets with information about different countries. For example, by pairing the this GeoJSON file with a plastic generation by country dataset using country code as a key field, we can generate a chloropleth map that shows the countries with more plastic generation in darker colors, as shown in the above map.

### Pollution and Other Anthropogenic Threats to the Environment
To find out the relationship between coral bleaching and anthropogenic factors, it will be useful to look at factors such as pollution. I found a very user-friendly website called [Our World in Data](https://ourworldindata.org/air-pollution), on which there is information about air pollution, plastic generation, water use and a lot more other topics. The website has downloadble csv files that often contains information that spans over a decade, which helps provide useful comparison with the coral bleaching dataset.  

## Intended output
In terms of visualizations, I will try to produce intereactive maps that allow people to zoom in to different parts of the world. I also want to try to produce a more sophisticated version of the map shown above to see if there is a correlation between a specific factor and coral bleaching.

## Presentation
[Link](https://docs.google.com/presentation/d/1z0hzVbu3L1AY3euGS2-rqUir-C0i2YAvGQFS517Eh3I/edit?usp=sharing) to Google slide

## Python data exploration
[uploaded GitHub file](https://github.com/yjwsb233/Coral/blob/main/Week%205%20Data%20Exploration%20(1).ipynb)

[Jupyter Hub](https://jupyter.idre.ucla.edu/user/haiqi@ucla.edu/notebooks/21W-DH140/Weeks/Week04/Week%205%20Data%20Exploration.ipynb#)

## Conclusion
So far, I believe that the project has taken shape and it is going in the right direction. My main focus now would be to produce better visualizations with the programming knowledge we learned in class. Overall, I believe this project would turn out great. 

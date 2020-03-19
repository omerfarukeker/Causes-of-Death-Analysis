# Causes-of-Death-Analysis
Our World in Data's causes of death dataset is examined in this repository. All codes are in the the notebook, please check the .ipynb file in the commits. Link for accessing the data:

https://ourworldindata.org/causes-of-death

The dataset consists of 34 different cause of death counts by country per year. It covers the years from 1990 to 2017. 

Let's start exploring the dataset. Visualise top 10 causes of death for Turkey in the latest available year, 2017:
![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/1.png)

Also display their percentage in pie graph:
* Almost 4 out 10 deaths in Turkey are caused by Cardiovasculare diseases in 2017

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/2.png)

Top 10 countries with the highest execution numbers

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/3.png)

Top 20 countries which suffered from terrorism the most. Our dataset Entity column contains a mix of country, continent, region, territory information too such as Sub-Saharan Africa, South America etc.

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/4.png)

Deadliest year was 2017, however this could be related to increase of the world population each year. We need to check death rate per year.

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/5.png)

Find world population per year from the internet and plot year vs death rate (%):
* 1994 was the deadliest year with almost 4% of the population was died

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/6.png)

Lets examine what was the cause for this high death rate in 1994. Conflict line of the heatmap shows an interesting light colour on year 1994 (the lighter the colour the higher the number of deaths)

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/7.png)

Conflict graph shows that 1994 was the year where the deadliest conflicts took place in the world. Bosnian War in Europe may have contributed to it significantly.

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/8.png)

Death by terrorism peaked in 2014, and has been declining since then, however no effect was observed on 1994 death toll

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/9.png)

Let's find out which country suffers from what disease the most. First, change our dataset's country names to the exact matches with the pycountry country names

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/10.PNG)

It is obvious that Cardiovascular Disease dominate death toll all over the world, how would the World map look if we took them out?

* It appears that the second most leading cause of death in rich countries like USA, Canada, Europe, Japan and Australia is Dementia (mainly caused by Alzheimer's disease). This could be due to the high frequency of elder people in their population.
* Conflict is leading cause for war territories like Syria and Palestine
* For Russia and their neighbours like old SSCB countries, Eastern European countries leading cause is Digestive diseases like Ulcer, Cirrhosis, Hepatitis. It could be related to excessive consumption of alcohol.
* Diarrheal diseases causes deaths mostly in the mid African region
* HIV/AIDS deaths are the most frequent in the South African region
* Some of the South American countries have Homicide as the leading cause for death
* Lower respiratory infections like Tuberculosis, Pneumonia is the leading cause for mainly South American countries like Brazil and Argentina.
* China, India and surrounding countries suffers from Respiratory diseases like Asthma and Lung Cancer etc.
* The countries where road accidents are one of the leading cause of death are in the Gulf region like Iran, Saudi Arabia, UAE. It could be related to their habit of car stunt driving.
* Greenland is the only country where suicide is the leading cause of death.

![](https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/11.PNG)

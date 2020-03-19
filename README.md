# Causes-of-Death-Analysis
Our World in Data's causes of death dataset is examined in this repository. All codes are in the the notebook, please check the .ipynb file in the commits. Link for accessing the data:

https://ourworldindata.org/causes-of-death

The dataset consists of 34 different cause of death counts by country per year. It covers the years from 1990 to 2017. 

Let's start exploring the dataset. 

Top 10 causes of death for Turkey in the latest available year, 2017:
<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/1.png">
</p>

Percentages in pie graph:
* Almost 4 out 10 deaths in Turkey are caused by Cardiovasculare diseases in 2017

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/2.png">
</p>

Top 10 countries with the highest **execution** numbers

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/3.png">
</p>

Top 20 countries which suffered from **terrorism** the most. Our dataset Entity column contains a mix of country, continent, region, territory information too such as Sub-Saharan Africa, South America etc.

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/4.png">
</p>

Deadliest year appears to be **2017**, however this is due to the increase of the world population each year. We need to check death rate per year.

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/5.png">
</p>

Find world population per year from the internet and plot year vs death rate (%):
* **1994** was the deadliest year with almost 4% of the population was died

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/6.png">
</p>

Lets examine what was the cause for this high death rate in 1994. Conflict line of the heatmap shows an interesting light colour on year 1994 (the lighter the colour the higher the number of deaths)

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/7.png">
</p>

Conflict graph shows that **1994** was the year where the deadliest conflicts took place in the world. Bosnian War in Europe may have contributed to it significantly.

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/8.png">
</p>

Death by terrorism peaked in 2014, and has been declining since then, however no effect was observed on 1994 death toll

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/9.png">
</p>

Let's find out which country suffers from what disease the most

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/10.PNG">
</p>

It is obvious that Cardiovascular Disease dominate death toll all over the world, how would the World map look if we took them out?

* It appears that the second most leading cause of death in rich countries like USA, Canada, Europe, Japan and Australia is Dementia (mainly caused by Alzheimer's disease). This could be due to the high frequency of elder people in their population.
* **Conflict** is leading cause for war territories like Syria and Palestine
* For Russia and their neighbours like old Soviet Union countries, Eastern European countries leading cause is **Digestive diseases** like Ulcer, Cirrhosis, Hepatitis. It could be related to excessive consumption of alcohol.
* **Diarrheal** diseases causes deaths mostly in the mid African region
* **HIV/AIDS** deaths are the most frequent in the South African region
* Some of the South American countries have **Homicide** as the leading cause for death
* **Lower respiratory infections** like Tuberculosis, Pneumonia is the leading cause for mainly South American countries like Brazil and Argentina.
* China, India and surrounding countries suffers from **Respiratory diseases** like Asthma and Lung Cancer etc.
* The countries where **road accidents** are one of the leading cause of death are in the Gulf region like Iran, Saudi Arabia, UAE. It could be related to their habit of car stunt driving.
* Greenland is the only country where **suicide** is the leading cause of death.

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/11.PNG">
</p>

Let's now group the diseases by their historical increasing or decreasing trends. Calculations will be based on deaths per 100000 for particular disease.

Following diseases show monotonic decrease trend over years:

* Even though Digestive and Respiratory diseases were dropping constantly for period of time, they started to enter an increasing trend since 2013. Still way better as compared to 90s
* Suicide rates are dropping since mid-90s
* Peak in the Heat graph could be a mistake in the dataset or it is a very distinguishing event happened in 2010 which caused this sudden jump

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/12.png">
</p>

Following are the death causes exhibiting an increasing or no trend over time:

* Dementia, Kidney, Cancer, Parkinson, and Diabetes diseases have been increasing since the beginning of our data span (1990)
* Drug and alcohol use disorders are correlated with Liver disease trend
* HIV/AIDS related deaths rate started to decline since 2005
* Natural disasters show no trend as expected

<p align="center">
  <img src="https://github.com/omerfarukeker/Causes-of-Death-Analysis/blob/master/Causes%20of%20Death%20Graphs/13.png">
</p>

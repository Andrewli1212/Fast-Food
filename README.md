# Group3-project1

**What is this project about?**
We are a group of investors looking to open a new fast-food restaurant somewhere in the United States. Our goal was to gather and analyze data that would help us determine the best location to open a fast-food restaurant. We primarily looked at three different datasets (1) Population in each state, (2) Number of restaurants in each state (3) Household income for every state. Based on these three data sets, we plotted different bar graphs, scatter plots as described below that helped us determine the best location.

**Population vs Number of Fast-food restaurants:** 
We first looked at the total size of population in every state and the total number of fast-food restaurants for each state by plotting separate bar graphs. For better visualization, we combined the population and restaurant data set for every state by plotting a Scatter chart as shown below: 
 
 ![](Output/q1c.png)

From the above plot, we were able to conclude that the number of restaurants is positively correlated to the population for any given state. In other words, the number of restaurants increases as the population increases.

**Ratio of percentage change in population to the number of fast-food restaurants in every state:** 
We dived a little deeper and determined the percentage change in population to the number of fast-food restaurants for every state.

Ratio of percentage change in population = (Total number of restaurants/population) *  100
            
![](Output/q2a.png)

From the above bar graph, it is evident that in states where the population is lower, the ratio of restaurants to the total population seems to be higher. As the population varies, the number of fast food restaurants varies accordingly i.e. states, where the population is lower, the number of restaurants too are lower and vice-versa.

**Comparing average household income to the total population and the number of fast-food restaurants in each state:** 

![](Output/q3c.png)

The above scatter plot shows that the median household income is slightly negatively correlated to the Total number of restaurants. i.e. With the increase in household income, there is a decline in the number of fast-food restaurants for a given state.

![](Output/q3b.png)

Based on the above bar graph, the median household income seems to be around $63,000. Florida seems to be a potential place of interest for opening a restaurant as the population is averagely high and the household income is below the median. 
            
**Best location in Florida to open a restaurant:** 

Below are maps plotted using Geoapify APIs showing the number of fast-food restaurants across the state of Florida, number of universities/colleges in Tallahassee as well as the hotels in Naples. 

![](Output/map_plot2_florida.png)
**Figure 1:** Map showing fast-food restaurants across Florida.

![](Output/Tallahassee.png)
**Figure 2:** Map showing universities/colleges in Tallahassee.

![](Output/Naples.png)
**Figure 3:** Map showing hotels in Naples.

Based on the above maps, we chose Tallahassee and Naples as potential places to open fast-food restaurant(s) as the number of fast-food restaurants in Tallahassee and Naples is lower compared to other places across the state (Pic a). Tallahassee being a college-town has a high student population because of many universities  (Pic b) and opening fast-food restaurants in Tallahassee would be the most prospective option.

**Implications:**
It is evident that there are an abundance of fast food restaurants in the United States, but there are still plenty of locations to add more. These findings can be used to look in to other specific states outside of Florida. For future research, we can do more research on specific fast food restaurant’s yearly revenue and revenue changes. Other points of new research could include demographics from specific states, such as ethnicity and race. These could factor in to the success of a fast food restaurant.
                                                                                                                                                                                                                                              
**Project folder structure:**
This project contains following directories and files:

1. "Group3-project1" is the main project folder
2. A "Resources" folder that contains the following CSV files:

- FastFoodRestaurants.csv    (Source: https://www.kaggle.com/datasets/datafiniti/fast-food-restaurants)
- state_demographics.csv     (Source: https://www2.census.gov/programs-surveys/cps/tables/time-series/historical-income-households/h08.xls)

3. Project1.ipynb - Main python jupyter notebook file

4. configy.py - python configuration file that contains API keys

5. An "Output" folder that contains following image files:
    - q1a.png
    - q1b.png
    - q1c.png
    - q2a.png
    - q2b.png
    - q3a.png
    - q3b.png
    - q3c.png
    - map.png
    - map_plot2_florida.png
    - Florida_School.png


**Appendix**

https://www.kaggle.com/datasets/datafiniti/fast-food-restaurants
https://www2.census.gov/programs-surveys/cps/tables/time-series/historical-income-households/h08.xls
https://www2.census.gov/programs-surveys/popest/tables/2020-2022/state/totals/NST-EST2022-POP.xlsx
https://corgis-edu.github.io/corgis/datasets/csv/state_demographics/state_demographics.csv

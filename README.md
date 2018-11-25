# Looking at crime in NYC

# Abstract
With more then 8.5 million inhabitants, New York City is the 10th biggest city in the world.

It thus consists of a lot of people on a small space and so the chances are big that people get irritated by each other.
Some people might express this by ignoring you in the hallway, others might just shoot a bullet through your head.

It's obvious that we would prefer the first neighbour, rather than the second one.
But when moving to NYC, it can be hard to choose a good place to live, especially when you still want something afordable.

In this project we want to give people who want to move to NYC in the long term some insight when looking for a good place to establish themselves.

We will look at how the crime rates for each region evolved through time and if this has an influence on the housing prices for specific regions. You might assume that safer regions have higher housing prices but you might just as well be missing some spots with a good cost/crime ratio.

When people are buying a place in NYC, they probably want to build out a life there with eventually maybe children. Of course you don't want your child to become the next Charles Manson so that's why we will also have a look if there is a correlation between school results and crime rates in several regions

Using visualizations and insightful data groupings, we hope to make the search for housing easier for future citizens of NYC


# Research questions
* Looking at the five boroughs of NYC (Bronx, Manhattan, Brooklyn, Queens and Staten Island), which region is more prone to crime in comparison with the others

* How have crime rates been evolving through the past years. In addition to examining overall crime rates and trends based solely on the numbers, we will also examine the frequency of specific types of crimes. The crime data given provides information on the severity of the crime, categorizing them as either felonies, violations, or misdemeanors (in decreasing order of severity). We will investigate which regions of the city are most prone to violent crime (as well as petty crime, and so on), and look at how those regions have shifted and evolved over time.

* How are school graduation and dropout rates distributed over NYC and how do they correlate to crime rates in those same areas - especially over the course of several years? 

* How are housing prices distributed over NYC and is it indeed the case that cheaper neighbourhoods have a higher crime rate?


# Dataset
Just like Switzerland, NYC also has a website full of open data. We have a rich array of datasets 
which we can group and work with.

Opendata.cityofnewyork:
    https://opendata.cityofnewyork.us/
    
    
* Crime:
https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
This dataset provides information about all crimes reported to the NYPD from 2006-2017 including the location of the crimes, demographical information, and severity of the crime. The data is very large; as such, we will need to be creative in determining the best way to visualize subsets of it. For example, viewing data on the daily or monthly scale would make map visualizations much easier than over the span of the entire decade.

* School Results:
https://infohub.nyced.org/reports-and-policies/citywide-information-and-data/graduation-results
This dataset has information about the aggregated graduation rates of students in NYC boroughs from 2001 to 2013 for each NYC Borough. Education is widely accepted to be extremely important and pivotal in determining quality-of-life and this dataset allows us to compare the state of education in each borough to the appropriate crime rates. 

* Housing Prices:
    We found a dataset with all projects, starting from 01/01/2014
    It consists of the number of units in each project/building and for each unit it is assigned for which kind of income it would be afforable. This allows us to look where more low income units are available in comparison with high income units.
    Since the data only starts from 2014, it will probably not be useful to do some temporal analysis on the data.
    The advantage of this dataset is that it is pretty small (<1MB) so we don't need a lot processing power.
    https://data.cityofnewyork.us/Housing-Development/Housing-New-York-Units-by-Building/hg8x-zxpr


# A list of internal milestones up until project milestone 2
NEEDS TO BE REDEFINED!!!

* Do data cleaning on all datasets of interest
* Examine libraries and techniques for temporal visualizations
* Narrow down our plan for a cohesive and interesting analysis that would cater
  to the average concerned Swiss citzen (or any citzen for that matter)
* Develop a narrative for our data
* Develop/find a skeleton for our data story website
* Determine ways to present the full crime dataset to the readers, including creative filtering mechanisms

# Questions for TA
NEEDS TO BE REDEFINED!!!
* Would you recommend changing our scope? 
* From previous experiences with students doing projects of this sort on Swiss
society, what should we look out for and what might be some particularly
interesting avenues for analysis?
* What visualization framework would you recommend for larger datasets like the one we are using?

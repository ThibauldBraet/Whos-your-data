# Trends in Swiss Society

# Abstract
It's hard to work for social good when we don't know what is good for society.

Despite the availability of data, it's still difficult for the average
concerned citizen to draw any meaningful conclusions from it. Someone might ask
questions like "I wonder if my governments spending is benefiting me?" or "Has
my the party I voted for actually improved my quality of living in any
measurable way?" But, without the skills and tools to analyze data, they're left
reliant on news sources that are often biased and don't provide them with useful
conclusions.

In this project, we hope to address several such questions, with the end goal of
making it easy for those interested to come to conclusions of their own. Topics
of interest include: 
>"How have changes in political power affected the swiss standard of living and
>lifestyle (e.g. crime rates, incomes, education rates, etc.)"

and
>"How has Swiss federal and cantonal spending changed historically and what
>effects have these changes had on Swiss society (i.e. employment, travelling
>time between City centres, health, etc.)?"

Using visualizations and insightful data groupings, we hope to make these
questions more approachable to the average person. 

# Research questions
* How can we make data-based conclusions on Swiss society as approachable as
possible through the use of visualizations and meaningful analysis?

* How have historical changes in political power within Switzerland affected
the lifestyle of the average citizen? Metrics for lifestyle include mean
household income, crime rat, employment rate, income inequality, etc. 

* What are some trends in Swiss federal and cantonal spending? How have focuses
changed in recent years and what quantifiable effects have these changes had?

* How have crime rates and types changed over time? Crime is an issue that plagues
every human society that has ever existed and making visualizations and
conclusions about crime within Switzerland - considered a relatively safe
environment - would be quite interesting.

# Dataset
The data sets below have varying formats so it will take some data cleaning
to get them to mesh. With this in mind, we have a rich array of datasets 
which we can group and work with.

Opendata.swiss:
      https://opendata.swiss/en/

* Politcal Power
  As both federal and cantonal parliaments hold significant power in the swiss
  government, it is worth looking at both of them when deciding which parties
  are 'in control' so to speak. 
  * Federal Parliament:
   This data set is simply a list of every member of the federal assembly,
   beginning in the 19th century. As it contains party-affiliation for each
   member, this can be leveraged to develop a sense of party control in the
   upper and lower chambers of the assembly.
   https://www.parlament.ch/en/ratsmitglieder
  * Cantonal Parliament:
   This data is more organized, so to speak, but there is more junk formatting
   making data cleaning slighlty more difficult. It contains over 20 years of
   cantonal parliamentary data.
   https://opendata.swiss/en/dataset/kantonale-parlamentswahlen-ins-kantonale-parlament-gewahlte-frauen-und-manner-nach-parteien

* Violent Crime:
  * With over 20 years of data for every type of violent crime, these data sets
   are both useful in drawing conclusions on the temporal presence of crime in
   Switzerland.
  * Adults
   https://opendata.swiss/en/dataset/erwachsene-verurteilungen-aufgrund-von-gewaltstraftaten1
  * Minors
   https://opendata.swiss/en/dataset/jugendliche-verurteilungen-aufgrund-von-gewaltstraftaten1

# A list of internal milestones up until project milestone 2
* Do data cleaning on all datasets of interest
* Examine libraries and techniques for temporal visualizations
* Narrow down our plan for a cohesive and interesting analysis that would cater
  to the average concerned Swiss citzen (or any citzen for that matter)
* Develop a narrative for our data
* Develop/find a skeleton for our data story website

# Questions for TAa
* Would you recommend changing our scope? 
* From previous experiences with students doing projects of this sort on Swiss
society, what should we look out for and what might be some particularly
interesting avenues for analysis?

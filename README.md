# P6-Make-Effective-Data-Visualization

##Summary
This project is a grading project for a course 'Make Effective Data Visualization', a part of Udacity's nanodegree.The chart can be seen[ here](http://bl.ocks.org/bhavya16/raw/00d1e9a61b1cd07fe1f4825f8b232988/)
The visualization analyzes data on loans, taken from the peer-to-peer lending marketplace called Prosper. It focuses on few main pieces of data on loans originated from 2009 to 2013: prosper rating, which provides a measure of loan risk;Occupation and the Income Range.

##Design
The raw data file contins data of individual loans. Since my focus was state level data from where i belong to i.e for Virginia State, I used R scripts to aggregate data and to generate necessary CSV files that I used for my visualizations..Also i have selected the Ocupations on which i wanted to work on.
I did not use any Javascript framwork, like Backbone, or React, to organize my code. I simply splitted into several functions, each of these functions draws single visualization.
When exploring the many variables in the raw Prosper loan data, I thought "what information would I be most interested in if I was thinking of finding what kind of person are likely to default?" So,for getting my questions answered i chose to select few variables of my interest like Occupation,Income Range ,ProsperScore and made a viaualization based on those variables.

Findings:
* Ocuupations which has the high income Range are less likely to default with the high Credit Score with the exception of Professionals
* Electrical Engineers having moderate Income level are less likely to default.
* Doctors,Military Enlisted and Electrical Engineers dont have the record of being in a default List
The writeup is available [here](https://github.com/bhavya16/P6-Make-Effective-Data-Visualization/blob/master/index.html)

###Feedback
I shared the visualization http://bl.ocks.org/bhavya16/raw/00d1e9a61b1cd07fe1f4825f8b232988/ and I received the following feedback from my colleagues and some friends:

* Figure legend is missing. What do the blue and red dots mean? What does the area represent?
* The title should reflect the content of figure.
* In the y axis, it says income, but the title only emphasizes occupation. also the x axis label is missing

##Resources
To better learn how dimple.js works and get examples for specific functionality, I examined many of the examples provided on the dimple.js site (http://dimplejs.org/examples_index.html).

https://d3js.org/

To perform data cleaning and aggregation, I used pandas in Python and R.

# DisneyMoviesAnalysis
This project started after diving deep on the dataset used on datacamp.com for this guided project https://www.datacamp.com/projects/740 Disney Movies and Box Office Success
I wanted to dive deep into the original dataset. From here I created I first notebook where I made an analysis on best selling movies and most prolific directors, but more importantly discovering all the problems related to the reliability of the original dataset. 
The original dataset used in the datacamp excercice is a modified version of this https://data.world/kgarrett/disney-character-success-00-16 
Basically the authors used import.io to scrape the data and build the dataset. 

The first consideration is about the best selling movies and can be found on this post on my blog http://www.lovabledata.com/probability-and-statistics/best-selling-disney-movies-from-1935-until-2016-python-business-analysis-with-code/
The related notebook is DisneyMoviesAndDirectorsAnalysis.ipynb 
I cleaned and merged three tables (1) Disney characters (2) box office success (3) annual gross income and plotted the results on a barplot with matplolib

Other two notebook will be deployes.
One always focused on DataViz will analyze ho changed through the time Dinsey Revenue Streams and the second one will analyze a pitfall that I think is present in the datacamp project.


Note about the Revenue Streams Data. 
From 2016 Disney Reports Changed the format of the main revenue streams.

In particular, the first change was between 2015 and 2016 in fact in 2016 they started aggregating "Consumer Products" and "Interactive". https://thewaltdisneycompany.com/app/uploads/q4-fy15-earnings.pdf
https://thewaltdisneycompany.com/walt-disney-company-reports-fourth-quarter-full-year-earnings-fiscal-2017/

Another change was made between 2018 and 2019. Here they changed the budget line "Parks and Resorts" into "Parks, Experiences and Products"
https://thewaltdisneycompany.com/the-walt-disney-company-reports-fourth-quarter-and-full-year-earnings-for-fiscal-2019/

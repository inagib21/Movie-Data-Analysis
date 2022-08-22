# Movie Data Analysis For Microsoft
![Microsoft](https://upload.wikimedia.org/wikipedia/commons/9/96/Microsoft_logo_%282012%29.svg)

by Nagib Gonzalez


## Overview

For this project we will be working with Microsoft to help them create original video content. We will be working with various datasets to see what insights we can get from the films that are doing the best in the box office. To measure success of the films we will be looking into the return on investment (ROI) and profitability.
## Business Problem:

Microsoft is looking to venture into the movie producing business. From a finacial standpoint we will be looking into some of the 


The first question that we would like to ask is what genres should we focus on making? 

The second question that we would like to ask is what should our budget be for the films? 

The third question that we would like to ask is what should our expected return be given our budget? Lets begin with looking at the different datasets that  help us answer our questions. 
## Data
We will be working with data from two sources.

The Internet Movie Data Base (IMDB): ![IMDb](https://upload.wikimedia.org/wikipedia/commons/6/69/IMDB_Logo_2016.svg)

IMDb is the world's most popular and authoritative source for movie, TV and celebrity content. Find ratings and reviews for the newest movie and TV shows. The table that I used in this  database was the movie basics which contained the movie titles and genres. 

The Numbers: ![The Numbers](https://github.com/inagib21/dsc-phase-1-project-v2-4/blob/master/numbers-logo-r.svg)

The Numbers provides detailed movie financial analysis, including box office, DVD and Blu-ray sales reports, and release schedules.  This data set provides the financial data that we will be working with including production budget and worldwide gross. From this data set we were able to find the ROI percentage and profit.

## Methods
In this analysis we focused on ROI which was calculated (worldwide gross / production budget) x 100. We also focused on profit which was calculated (world wide gross - production budget).

As a measure of central tendency due to the skewness of the distributions and the high number of outlier movies we used median instead of mean for the majority of the project. I did make a visualization which shows the average budget per genre but the median is also displayed.
## Results

![Genre ROI](https://github.com/inagib21/Movie-Data-Analysis/blob/main/GenreWithHighestROI.png)
The Genre with the highest ROI was Mystery, followed by News and Animation.


![Genre Profit](https://github.com/inagib21/Movie-Data-Analysis/blob/main/Genrewithhighestprofit.png)

The Genres with the highest profit were Animation, followed by Adventure and Sci-Fi.

![Average Budget Per Genre](https://github.com/inagib21/Movie-Data-Analysis/blob/main/Avgbudget.png)

The average budget for all genres was about 50 million.
## Conclusion


In the first visualization, we looked at return on investment. The formula for that is( ROI = World Wide Gross/ Production Budget x 100). We saw that the Mystery genre had the highest return with 300% ROI followed by News and Animation which were about 275% ROI. 


The second visualization looked at the highest profiting genres. The formula we used for that was world wide gross subtracted by the production budget. The highest profiting genres were Animation, Adventure, and Sci-Fi. Those genres profited between 200 and 250 million dollars. The Mystery genre profited close to 75 million dollars while the News genre did not make it on our top ten list. After observing these two charts and to answer our first question on which genres we should make I would suggest that the genres which should focus on making are Animation, Adventure, and Sci-Fi. These genres have an ROI above 250% and a profit of over 200 million dollars. Although the Mystery genre had the highest ROI in terms of percentage, the profit margins were about 125 million dollars less than Animation, Adventure, or Sci-Fi.
The third visualazition looked at the average budget per genre. The average budget for all genres was about 50 million dollars. The median amount for Adventure and Animation was closer to 100 million dollars while the Sci-Fi median was closer to 50 million. For the adventure budget, it is interesting to see that there were several outliers that were over 300 million dollars. To answer our second question about our movie budget I would recommend spending anywhere from 75 to 150 million if we make an Animation or Adventure film. If we decide to make a Sci-Fi film I would suggest that you can spend less starting at 50 million dollars and try not to spend over 150 million.


To answer our third question on what our expected return should be, I believe that it would make sense to have a portfolio of three movies with the genres that were recommended Animation, Adventure, and Sci-Fi. I would suggest we spend a maximum of 150 million per movie totaling 450 million for all thre movies. on that 450 million dollar investment, we should aim for a return of 250-275 percent which is a profit of 1.125-1.237 billion dollars.

## For More Information
Please feel free to look at this Jupyter notebook which contains the code behind these visualizations https://github.com/inagib21/Movie-Data-Analysis/blob/main/student.ipynb 

You can also check out my presesentation for this analysis https://github.com/inagib21/Movie-Data-Analysis/blob/main/movie%20data%20analysis%20presentation%20(2).pdf

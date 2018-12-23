This repository contains the R code used to create a model to determine if the sentiment of newspapers can aid us in predicting recession. 
The final paper is labeled “The Role of Media in Causing a Recession.” If you want to follow my work run through the files in the following
order:
1.	News Paper Scraper
  : 	This file will pull newspaper text from newspaperarchive.com and build the data set you will get sentiment scores from
2.	Sentiment Scoring and Visualization 
  : This file scores the newspaper text base on sentiment files from http://www.sca.isr.umich.edu/tables.html. 
    It also graphs the scores over time.
3.	Yield Curve Calculation
  :	The best predictor of recessions is the yield curve. This file transforms the yield on 1 month to 30 year T bills into Slope, 
    Curve, and Intersect.
4.	Final Logit Model
  :	This file contains the final model that predicts recessions based on the data series from the “Dataset.xlsx” file

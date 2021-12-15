# Bias in Hate Speech Detection: The Issue with Positive Speech

This repository comprises the results, data, and code of our final project for the class Decoding Biases in AI of the 2021 fall semester at Sciences Po. 
Our project sought to identify how a hate speech detection algorithm, Google’s Perspective API, deals with positive speech by minority groups. Given the prevalent use of trigger words, for example by describing bad experiences or through reclaimed slurs, these groups often fall into the sights of hate speech detection. We sought to understand what triggers the algorithm and how this can be problematic. Our final report can be found here:
LINK RESULTS

# CODE
This [folder](#data) contains the code we used to conduct our analysis. 

##AI_Biases_Notebook.ipynb
This python notebook contains the code used to scrape the tweets using the minet library, as well as the code to create scatter texts and frequency lists we relied upon in our analysis.

##RScript Applying Perspective
This R script contains the code used to calculate Perspective’s toxicity score for our tweet data sets. 

##RScript Cleaning Data
This R script was used to clean our data sets from irrelevant symbols like # and @. 

# DATA
Here you will find the final cleaned data sets we used in our analysis as well as the interactive scatter texts in html format. The words in the title reflect the reference group, described in full in our report.

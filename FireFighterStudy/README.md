#  Abstract

The traditional way to conduct nutrition research is to have participants recall what they have eaten for one specific day during doctor's visit. The one-day recall of food-log, however, could be highly unrelaible and may not be able to accurately mirror a person's diet. 
Using the firefighters dataset from the Time-Restricted Eating study, we try to analyze how many days of food records would be sufficient to reflect an accurate picture of a participants’ diet. 

In order to answer this question, we worked with the firefighters dataset in a Time-restricted Eating study. The firefighter study includes two periods: the baseline period and intervention period. In our study, we mainly analyze data from baseline period.



For each person do repeated (1k+ times per person) random subsampling of (A) from 1, 3, 7, 10, 14 days randomly distributed through the data and (B) from 1, 3, 7, 10, 14 days consecutively starting at a random location.  Calculate the % overlap in top k food items between the subsample and all data.  Show the distribution of overlaps for each # days subsample and method of subsample.

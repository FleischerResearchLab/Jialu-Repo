#  Abstract

The traditional way to conduct nutrition research is to have participants recall what they have eaten for one specific day during doctor's visit. The one-day recall of food-log, however, could be highly unrelaible and may not be able to accurately mirror a person's diet. In order to overcome this deficiency and make nutrition research more efficient, we designed this study to analyze how many days of food records would be sufficient to reflect an accurate picture of a participants’ diet using the firefighters dataset from the Time-Restricted Eating study in Pandas Lab.

According to the result, a random one day food-log can only reveal 22% of a person's diet, while a random 10 day food-log can reveal 74% of a person's diet. The patterns seems quite obvious: as we increase the number of days we want to sample, the result food-log reveal more about a person's diet.

# Dataset

The dataset we analyzed in this study is from Panda Lab at Salk Institue. It contains food logs of 136 firefighters throughout the Time-Restricted Eating study. This firefighter study includes two periods: the baseline period and intervention period. In our study, we mainly analyze data from baseline period.

We do not include the dataset in this repository. It can only be shared under Dr. Panda's permission.

# Methods

In this study, we compare different sampling method.
1. We randomly sample 1, 3, 7, 10 days of record from the baseline period, and compare the overlap between the most k frequent food item of the sample and the most k frequent food items of the entire baseline period.
2. We consecutively sample 1, 3, 7, 10 days with the starting day being randomly selected, and compare the overlap between the most k frequent food item of the sample and the most k frequent food items of the entire baseline period.


1. We 

For each person do repeated (1k+ times per person) random subsampling of (A) from 1, 3, 7, 10, 14 days randomly distributed through the data and (B) from 1, 3, 7, 10, 14 days consecutively starting at a random location.  Calculate the % overlap in top k food items between the subsample and all data.  Show the distribution of overlaps for each # days subsample and method of subsample.

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
3. We applied a Monte-Carlo way to do the comparison. Rather than treating the entire baseline as the ground truth (like what the previous two methods does), we iteratively regard the result of each choice of days sampled (1,3,7,10) as the "ground truth", and calculate the overlap score between that and the results of other choices of days sampled.

For each comparison, we calculate the result for each participant, repeat for 1000 times, average the results across the 1000 iterations and then average the results across the population.



# Getting Started


## Use this script to analyze other diet-related dataset

Open Firefighters.ipynb and follow the instruction inside. Be sure to adjust related dataframe or code to fit your own data.

## Replicate the analysis or result

Open Firefighters.ipynb and select "Cell -> Run All" from the pull down menus. All cell should be runned automatically.

# Author

Jialu Sui

# Acknowledgement

Thanks Dr. Panda for sharing this amazing dataset with us.

Thanks Professor Fleischer for helping and guiding me throughout the summer.

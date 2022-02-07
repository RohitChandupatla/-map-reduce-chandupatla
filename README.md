# map-reduce-food_preference

• I'm currently learning on a **map reduce** project with a new data source in order to gain new abilities and gain relevant insight.

## Data set reference

• I discovered the Kaggle  [**Food Preference 2019**](https://www.kaggle.com/vijayashreer/food-preferences) Survey dataset. </br>

## About Data
• The participants in this year's **Food Preference** Survey came from a variety of countries and demographics.

#### • What age group like to consume a higher percentage of food?

• From the initial dataset, I'll map to key-value pairs: **Age**, count. Then, I'll use the terminal **"sort"** to get them sorted in case they aren't. Then, I'll **reduce** all the key-value pairs for one Age to a single value: Age, count Of age.

## Powershell Command
```
cat Food_Preference.csv | python MyMapper.py > Foodoutput.txt
```
#### You may now execute this command on your local system to retrieve the sorted and reduced data after receiving the mapper output.

```
cat Food_Preference.csv | python MyMapper.py | sort  | python MyReducer.py > CHANDUPATLAoutput.txt
```
## Summary
**According to the report, those between the ages of 20 and 25 prefer the food the most.** </br>

![Scatter](/image/Scatter.PNG)

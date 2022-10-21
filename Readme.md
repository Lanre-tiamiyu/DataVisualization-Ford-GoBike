## Data Visualization - Ford GoBike

### Dataset

Ford-goBike-dataset-exploration is a project doing exploratory visualization on the bike trip dataset. The dataset, 201902-fordgobike-tripdata.csv, is downloaded from [Ford GoBike](https://s3.amazonaws.com/fordgobike-data/index.html "Ford GoBike") and licensed by [Ford GoBike](https://assets.fordgobike.com/data-license-agreement.html "Ford GoBike"). 

This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019. 

## Table of Contents

- `ford-gobike-dateset-exploration-part1.ipynb` : The Jupyter Notebook version of exploratory visualization

- `ford-gobike-dateset-exploration-part1.html` : The html version of exploratory visualization

- `ford-gobike-dateset-exploration-part2.ipynb` : The Jupyter Notebook version of explanatory visualization

- `ford-gobike-dateset-exploration-part2.html` : The html version of explanatory visualization

- `ford-gobike-dateset-exploration-slides.html` : The html presentation of the key finding and recommendation

- `201902-fordgobike-tripdata.csv` : The original dataset

- `fordgobike_clean.csv` : The cleaned dataset used for explanatory visualization 

## Summary of Findings

### Univariate exploration: 
- The ride duration exhibts a log normal distribution with most of the rides having a duration between 5 and 15 minutes. Most of the rides take place during weekdays with a daily bimodal distribution with peaks at 8am and 5pm suggesting the the rides are used mainly to go to and from work.

- There is a pattern that rides tends to decrease in weekends. This suggests that most of the rides are used to go and from work.

- The distribution is bimodal, with one peak around 8 am. and another at about 5 pm. which adds more strength to the idea that the rides are mainly used to go to and from work.

- There are about 3 times more males than females using the rides.

### Bivariate exploration:
- The ride duration exhibts more variance in the weekends and the variance tend to decrease with age. The average ride duration is less for subscribers than for casual customers. Also, subscribers to `bike_share_for_all_trip` have less average ride duration than non subscribers to this option. Females tend to have more average ride duration than men. During the day, the average ride duration decrease before and after the working hours.

- Although the number of rides generally decrease during weekends, but this is only valid for subscribers. While casual customers and subscribers to `bike_share_for_all_trip` option seem to have similar number of rides during the whole week.

### Multivaraite exploration

- There is less variance in the ride duration with age for females than for males. Also, the same behaviour happens with casual customers compared to subscribers.

- Average ride duration is highest for casual customers then subscribers who are not member of `bike_share_for_all_trip` then those who are member in this option.

## Key Insights
---

- The higher ride frequencies for the morning (8th and 9th hrs) and evening (17th and 18th hrs) can be linked to rush hours where people leave for work and come back later in the evening.

- Weekend trips take a longer duration as compared to trips taken during the week.

- Customer user type trips take a longer duration compared to subscriber user type.

- Weekend trips take a longer duration as compared to trips taken during the week.

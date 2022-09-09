# (Ford GoBike System Data)
## by (Deborah Odebunmi)


## Dataset

>This data set on Ford GoBike includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset includes information on 183,412 trips and features such as the user type, gender, station details and trip duration amongst others.

> The data set had to be cleaned before performing any analysis on it. The data types for the start time and end data columns were changed. Member_gender, birth_year and bike_share_for_all_trip columns were also re-classified as categorical variables. Outliers and null values were removed from the dataset. New columns like generation and rider age(this was derived from the birth year column), start day, start month, start hour (extracted from the start_time) amongst others that will also aid my analysis were also included to the dataframe.


## Summary of Findings

> From the analysis I carried out, I was able to discover the following:
* There are more millenials who use thr bike sharing system compared to the other generations
+ There are also more customers using this service on weekends, compared to subscribers. I assume the customers use it for fun/recreation while subscribers use it for work/to transport to their offices or work places
+ Between 10am and 5pm, there are little or no rides by customers on every day of the week
+ There are more males who use this sharing system compared to the other genders
+ There are also more subscribers of this service than customers
+ The busiest day of the week is Thursday for both customers and subscribers, perhaps, something special happens on Thursdays...
+ Subscribers use the bike sharing services mainly at 8am and 5pm, which is likely because this falls around work opening and closing hours. 


## Key Insights for Presentation

> For my presentation, my focus is on the distribution of riders across different generations. This is visualised as a bar chart. This is followed by a bar chart showing the distribution of rides across the different week days.

My next presentation is a box and violin plot showing the ride duration in seconds across the different generations. This gives a summary view of ride durations for each generation, and also provides a view on what values ride durations are centered in the most across the five generations. I also present a clustered bar chart showing the number of riders for each gender across the different generations.

Lastly, I presented heatmaps showing usage per hour for the different user types on different weekdays. This reveals Thursdays as the busiest day of the week, with subscribers have peak hours of 8am and 5pm (likely because of work opening and closng hours)
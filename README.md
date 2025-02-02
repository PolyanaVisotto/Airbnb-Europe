# Airbnbs in Europe | Analysis for Python for Sustainability at Leuphana Universitat 

Deal all, 
This repository and Jutyper Notebook was created taking as a basis our previous classes during "Python for Sustainability". 
In each section of my analysis you can find the details about how I processed the information. The notes assisted me mainly in understanding the question in itself and keeping track of the steps. 

**Disclaimer**
All analysis were done before the 31st of January mid-night. Please take into account that I also included a bit of the project that was realized later on (exercise 6). 
To be fair with everyone, this can also not be counted as it was mainly my personal exploratory attempt. 

**The questions answered were**: 
1) Data Analysis with focus on merging the dataframes, creating new columns, changing the name of some columns, removing the first one
2) Advanced section suggested: Create one column for all the private or shared category
3) Exploratory questions (almost all questions)
4) Exercise 1: Understanding the differences between three cities (comparison prices)
5) Exercise 2: Prices are bigger during the weekend?
6) Exercise 3: Comparison superhost prices to non-superhost ones.
7) Exercise 3b: What if we would like to compare superhosts to non-superhosts for each city?
8) Exercise 6: To determine if there is a pattern between room_type and superhost status. 

**My overall observations**: 
When analyzing the proportion of listings, London and Rome stand out with approximately 9,000 listings each, followed by Paris with around 6,000. A key pattern emerges when comparing listing activity between weekdays and weekends—four out of ten cities see more trips during the week, while the rest experience higher demand over the weekends. These weekend-favored cities also tend to have higher fares and, interestingly, a greater overall number of listings compared to those with a weekday predominance. This suggests that cities visited more frequently on weekends may be more popular travel destinations.

Among all cities, Rome has the highest proportion of superhosts, with around 83% of its listings managed by these highly-rated hosts. Rome also leads in properties rented as entire homes or apartments.

Regarding guest satisfaction and ratings, cleanliness scores are generally high, averaging between 9 and 10, though some outliers dip as low as 2. Capacity analysis through a boxplot reveals that most listings accommodate between 2 to 4 guests, with a maximum capacity of 6.

Examining price distribution across weekends and weekdays, we observe that weekend prices tend to be more concentrated below €1,500 per night, whereas weekday prices extend up to €1,800 per night. However, it is important to note that the graph plotted may not be perfectly weighted due to certain methodological challenges. Nonetheless, both distributions exhibit a clear right-skewed pattern. In contrast, guest satisfaction ratings display a left-skewed distribution, indicating a stronger concentration of positive feedback and high ratings.

To further investigate pricing trends, three cities—Vienna, Rome, and Berlin—were chosen as references. Vienna consistently had the highest prices, followed by Berlin. In all three cities, weekday fares were noticeably lower than those on weekends.

Finally, comparing superhosts to non-superhosts, it appears that superhosts tend to attract more guests, likely due to their lower fares and closer proximity to city centers. Among all cities, Berlin, Budapest, and London exhibited the most significant differences in the superhost vs. non-superhost dynamic, suggesting that in these locations, superhost status plays a crucial role in pricing and occupancy rates.



**Credits**: I would like to acknowledge that Chat Gpt was used mainly to solve specific erros in programming. This is specifically visible in the last project as I attempted to follow its advice to solve a missmatch between the length of the cities list etc. 

# Final Project for Intro to Data Science

## Fall 2023

Team members: 


- Student 1: [kouame koffi](mailto:kkoffi4206@floridapoly.edu)




**Summary**

Our project investigates the main characteristics of Space Launches in recent years.
We will be using the data available at: 
<https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-01-15/launches.csv> 


# Introduction 

The exploration of space has always symbolized a major achievement for humanity, arousing our curiosity and inspiring entire generations to explore the immensity of the unknown. Space launches mark crucial milestones in our quest to understand the universe, constantly pushing the boundaries of science and technology.

This project undertakes an in-depth analysis of space launch data, with the aim of revealing several parameters such as:

- How many launches were occurred in each year?

- What was the first artificial satellite launched into the space?

- Which space agency launched the the first space station, and when did it occur? 

- How many launches were conducted by US and Russia?

- Which countries or space agencies have been the most active in terms of space launches?

Let’s dig deeper and answer these pressing questions!
Our project studies around 5726 space launch reviews with characteristics such as tag, JD, mission, agency etc. This is our final project for the Introduction to Data Science course (Fall 2023) which will give you an overview of our analysis.

# Necessary libraries 

library(tidyverse)
library(scales)

# Launches dataset

[launches](file:///C:/Users/kouar/Downloads/1.photo.png)

## Which years within the specified range had a higher or lower number of "Thor Burner 2" launches?

To better understand the number of "Thor Burner 2" per year, we used ggplot with bar plot for the visualization that counts the number of "Thor Burner 2" per launch_year showing only  1967 to 1974 to give you an idea of what launch_year has the most selection of Thor Burner 2.
So, through the graph, we see that in 1967, there were more space launches during this period.Also, year 1967 has a higher number of "Thor Burner 2", 1969 and 1973 have the same lower number of "Thor Burner 2" launches.

Notice: The bar plot provides a visual comparison of launch frequencies across the selected years, helping to identify trends or patterns.


Figure.1 ![](file:///C:/Users/kouar/Downloads/2.photo.png)



## How to find the agency with the highest number of launches ? 

This code uses ggplot2 to create a horizontal bar plot where each bar represents an agency, and the length of the bar corresponds to the total number of launches by that agency. Adjust the head() function to change the number of top agencies displayed in the plot.
Notice: The agency with the highest number of launches is US agency and its number of launches is 2444.

Figure.2 ![](file:///C:/Users/kouar/Downloads/fig.2.png)

We can use bar plot to specify more the agencies launches.

Figure.3 ![](file:///C:/Users/kouar/Downloads/4.photo.png)

Note that there were 41 agencies.


## Compare the number of successful launches with the number of failures. 

This code creates a bar plot with two bars, one for successful launches and one for failures. The height of each bar represents the count of launches with the respective outcome. Adjust the aesthetics and labels as needed.

Figure.4 ![](file:///C:/Users/kouar/Downloads/Figure.4.png)
































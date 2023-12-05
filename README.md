
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

[launches](file:///C:/Users/kouar/Downloads/table_launches.png)

## Which years within the specified range had a higher or lower number of "Thor Burner 2" launches?

To better understand the number of "Thor Burner 2" per year, we used ggplot with bar plot for the visualization that counts the number of "Thor Burner 2" per launch_year showing only  1967 to 1974 to give you an idea of what launch_year has the most selection of Thor Burner 2.
So, through the graph, we see that in 1967, there were more space launches during this period.Also, year 1967 has a higher number of "Thor Burner 2", 1969 and 1973 have the same lower number of "Thor Burner 2" launches.

Notice: The bar plot provides a visual comparison of launch frequencies across the selected years, helping to identify trends or patterns.


Figure.1 ![](file:///C:/Users/kouar/Downloads/graph_image1.png)

On October 4, 1957, the Soviet Union launched the earth's first artificial satellite, Sputnik I. The successful launch came as a shock to experts and citizens in the United States, who had hoped that the United States would accomplish this scientific advancement first.The Sputnik launch marked the start of the space age and the US-USSR space race, and led to the creation of the National Aeronautics and Space Administration (NASA).
We can get more information [here](https://guides.loc.gov/sputnik-and-the-space-race#:~:text=On%20October%204%2C%201957%2C%20the,Earth%20in%20around%2098%20minutes.)
![](file:///C:/Users/kouar/Downloads/graph_image2.png)

## How to find the agency with the highest number of launches ? 

This code uses ggplot2 to create a horizontal bar plot where each bar represents an agency, and the length of the bar corresponds to the total number of launches by that agency. Adjust the head() function to change the number of top agencies displayed in the plot.
Notice: The agency with the highest number of launches is US agency and its number of launches is 2444.

Figure.2 ![](file:///C:/Users/kouar/Downloads/graph_image3.png)

We can use bar plot to specify more the agencies launches.

Figure.3 ![](file:///C:/Users/kouar/Downloads/graph_image4.png)

Note that there were 41 agencies.


## Compare the number of successful launches with the number of failures. 

This code creates a bar plot with two bars, one for successful launches and one for failures. The height of each bar represents the count of launches with the respective outcome. Adjust the aesthetics and labels as needed.

Figure.4 ![](file:///C:/Users/kouar/Downloads/graph_image5.png)




# Conclusion:

In summary, our in-depth analysis of space launches revealed crucial patterns and trends by examining key parameters such as launch label, agency, year, variant, categories and type. Exploration of beacons and agencies highlighted the diversity of missions, illustrating collaborative efforts within the space community. The multi-year analysis identified temporal trends and technological advancements, while examining variants, categories and launch types offered insight into the different methodologies used, from satellites to crewed missions. In conclusion, data fusion has enriched our understanding of the complexities of space missions, contributing not only to the current state of space exploration, but also a solid basis for informed decisions and future advancements in the exciting field of space launches.


# Futur Works

Certainly, there remains a vast realm of exploration within this dataset. Key areas of focus include the integration of diverse data sets, encompassing weather conditions and geopolitical events, to provide a comprehensive view of the factors influencing space mission success. Predictive analytics, powered by machine learning today, is poised to play a central role in predicting mission success and optimizing risk management. Real-time monitoring systems and adaptive planning strategies will improve mission flexibility and responsiveness to dynamic conditions. The development of sophisticated space traffic management systems is imperative to cope with the increasing frequency of launches and ensure safe coordination in Earth's orbit.


# Datasets Cited

Thanks to [Dr.Rei Sanchez-Arias](https://github.com/reisanar/final_project_ds) for providing us with [dataset](). 

The data we used is available at: https://github.com/matoboh/final_project_ds



























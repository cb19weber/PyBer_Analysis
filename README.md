# PyBer_Analysis

## Overview of Project
Week five of the Data Analytics bootcamp provided the opportunity to work with a new python library: Matplotlib. Additionally, the project will require continued building on skill development using the Pandas library and jupyter notebook, as well as offer an introduction to the SciPy and NumPy libraries. The goal of the week is to begin building some greater muscle memory with the basic syntax of the language as well as to harness Matplotlib to design and publish rich visualizations to communicate the story of the underlying data.

### Purpose
The specific purpose of the project in this module is to examine a dataset for ride-sharing services to determine how to improve access and affordability for underserved neighborhoods. The project will require importing the datasets into a Pandas DataFrame, using Pandas to merge and summarize the datasets, and then implement Matplotlib to build a few visualizations that effectively communicate the story of the data. Telling that story will require the use of NumPy to obtain statistical descriptions of the data, and then to use the stats to build furhter visualizations that flesh out some of the nuances within the data.

## Analysis and Challenges

### Analysis of Outcomes Based on Module
The scatter-plot visual really communicated the greatest amount of information, while at the same time being very succinct.
<p align="center">
  <img src="https://github.com/cb19weber/School_District_Analysis/blob/main/Resources/size_summary_original.png" />
</p>
A few extremely notable points going on here. First, we can see a pretty clear, linear, relationship between the number of rides on a given day and the average fare per ride. This actually represents what most economists would consider to be a demand curve. As average fare decreases, riders demand more rides. As average fare <i>increases</i>, riders demand fewer rides. Riders are seen here as evaluating the trade-off of a more expensive ride-share service against finding some other mode of transportation.

Secondarily we can see above that more rides occur in more heavily populated areas. Which makes sense. More people need rides, and therefore more rides occur. In a rural area with fewer citizens, there are bound to be fewer rides requested, and as population increases through suburban to urban areas, demand for rides also increases.

But hold on for a moment; in all of this economics discussion, what we don't see is a supply curve. Or do we? Traditionally, we would expect a supply curve to run in a similar linear fashion as the demand curve, but inverted. Instead, what we see in PyBer's data is an inverted supply curve. This is really the crux of the story on display here. What the graphic above shows is a <i>constrained</i> supply curve.

Many economists love to share their fondness of ride-sharing apps. They represent one of the truest forms of what is referred to as a <i>perfect market</i>, where there are many suppliers all selling the same product/service to many customers. But while ride-sharing may represent a perfect market in isolation, when a grander scope is used, it becomes much less perfect. Certainly drivers would <i>prefer</i> to earn higher average fares. But in more highly concentrated population centers, competition increases. Just like there are more people demanding rides, there are also more people willing to supply rides. As such, in urban areas, where supply and demand intersect to find market equilibrium is around the $25 fare. There is a standard deviation of just under $12 for urban centers representing higher fares at peak demand times and lower fares at off-peak times.

The challenge faced for lesser populated areas is that the same algorithm used to determine fares is used as what would be in higher populated areas. Since there are fewer drivers in rural and suburban areas, supply is determined by PyBer to be low. Since there are fewer drivers available, the ride-sharing algorithm calculates costs to be higher, and therefore charges a higher rate. But we can see from the larger urban dataset that market equilibrium is probably reached at a lower rate.

### Analysis of Outcomes Based on Challenge

### Challenges and Difficulties Encountered

## Results

## final project - evictions in allegheny county - part 3

### summary

[Part 1](https://julia-pascale.github.io/pascale-portfolio/finalproject_part1.html) - I identified my data sources and began to sketch out what the story could be. <br>  

[Part 2](https://julia-pascale.github.io/pascale-portfolio/finalproject_part2.html) - I dug further into the data sources that were available and showed my draft visualizations to some patient test subjects! <br>  

[Part 3](https://carnegiemellon.shorthandstories.com/evictions-in-pittsburgh/index.html) - I created a story with graphics and data visualizations about evictions in Allegheny County, how they happen, who they happen to, and what we can do about it.

### Process

After I storyboarded with my test subjects, I had a lot of feedback to sort through, and then it was time to make the final versions of the visualizations and decide what order to put them all in. The most insightful information that I shared with my test users was all about money - specifically they were interested in property values and expenditures, as well as eviction filings. Naturally this was the most difficult to work with! The data that I ended up using came from: <br>  
(1) the Bureau of Labor Statistics, which publishes expenditure data by income every year. <br>  
(2) the Create Lab at CMU. Anne Wright sent me so much data and she was so helpful. I had the datasets from a Google sheet that they pull from to report counts to the Eviction Lab, and she also sent me all of the evictions in Allegheny County from 2008 to 2018 which she had from an AOPC purchase. This dataset included claim amounts, how the case was decided, the plaintiff and defendant, the dates, but only the zip codes, not the property addresses. It was messy but once I deduplicated it, it was fascinating. I made a pivot table with it that showed me useful trends - I found how many times landlords appeared in eviction filings, a number of tenants who had been evicted multiple times, and the typical claim amounts. <br>
(3) WPRDC, which has an "assessments" dataset that includes sale price, previous sale price, dates, addresses, and a homestead tax flag for every property in the county. I cut it down to only include properties that had sold since 2010, and Homestead properties, and for another cut just the 10 zip codes with the most evictions just to make it more manageable, but once I started working with pivot tables I was able to come to conclusions about all of the county's properties. I wanted to learn how much equity landlords make from their properties. I know they don't sell them, they rent them out, but knowing about comparable sale prices tells us about the equity in unsold properties. <br>

### Map failures
Failure is part of the process! I wanted to use maps to talk about the geographic inequity of eviction. I identified the zip codes that had the most evictions by looking at the Eviction Lab's website, and then I decide to see how many children are in those zip codes, and how many people of color. The problem with this was that I only had children and race data by census tract, so I had to do a spatial join to get it for zip code boundaries, and I just couldn't get this join to work for the longest time! Here are some of my failed maps: 

The kicker is that once I went to the trouble of figuring out all my joins (I was joining 2020 census data to 2016 tracts, so there were lots of holes), my users did not respond to them anyway. 

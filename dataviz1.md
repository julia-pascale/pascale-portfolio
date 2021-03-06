
## Visualizing Government Debt

### OECD's bar graph
#### Debt to GDP Ratio for Selected Countries - visualized by OECD
<iframe src="https://data.oecd.org/chart/6BgS" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6BgS" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

### Flourish chart 1
#### Debt to GDP Ratio for Selected Countries - grid of line graphs
<div class="flourish-embed flourish-chart" data-src="visualisation/8558160"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Flourish chart 2 
#### Debt to GDP Ratio for Selected Countries - line chart race
<div class="flourish-embed flourish-chart" data-src="visualisation/8558477"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
To make this chart, I trimmed the data to include only those countries that had data available in 2007 and 2019. I calculated which of these experienced the greatest change in GDP to debt ratio, and visualized only those that had greater than average change. I included the OECD average for context. While I like the way it looks, the format requires that the number of countries depicted be smaller, otherwise it looked like a confusing mess - if it were important that all of the countries be shown, or that the timeframe go back to the 90s, I would not have chosen this style. My other considerations (besides which countries to trim) when making this chart were about colors. Specifically, I wondered if the countries with the highest ratios also needed to be colored differently, or if they stand out enough without extra color. After trying it a few different ways, I decided that additional color [does help](https://user-images.githubusercontent.com/98070047/151734347-c4d9bd1b-13c4-4edd-9b39-4c5aec38c7cd.png) the viewer interpret which country has the highest debt to GDP ratio (Japan), but it is most important for the benchmark information that helps contextualize the reader: in this context, this is probably the line for the US and the OECD average. As a result I decided to leave color off Japan. I chose to use green and blue after trying it out with red because of the negative connotations of red. [I also tried brighter and darker blues and greens](https://user-images.githubusercontent.com/98070047/151734365-38c9030e-6236-4bfa-a6d5-1220a76fd814.png).

One final thought about the second Flourish chart: making this animated visualization was a good opportunity for me to practice using Flourish and to clean and trim a dataset, but I think the end result is a case of the data serving the visualization and not the visualization serving the data - I prioritized finding a way to make this particular type of visualization work, even if it didn't end up being the best possible way to display these data. 

After exploring the OECD debt data across 3 visualizations, I think that the bar graph is the easiest to interpret from a glance, but it also shows less information, because it depicts only a point-in-time. The option to toggle background bars is also a good feature, because it allows the viewer to contextualize the data, and it's visually appealing to provide ground features. While they are more difficult to interpret quickly, the line charts both show change over time, which adds an additional dimension of information. The other strength of the bar graph over the grid of line graphs is that the viewer can tell the relative differences between the countries very easily. With the grid of line graphs, it is more difficult to make a comparison between countries. That is why I chose the line race, so that the viewer would be able to look at the lines on the same axes. Because the data is a ratio, it works well in this format - it would not work if the data was a raw dollar amount of debt, for example. 

[back to portfolio](README.md)

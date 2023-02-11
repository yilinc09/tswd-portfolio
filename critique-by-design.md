## Step one: find a data visualization
I am curious to study the relationship between unemployment and inflation in the United States. I briefly touched on the concept of their relationship in an undergraduate economics class, and it is stated by economists that there should be a trade-off between unemployment and inflation. The relationship between inflation and unemployment has historically had an inverse correlation. This hypothesized relationship is represented by the economic model, the Philips Curve. 

However, concepts cannot always reflect the more complicated real-world situations. In 1970s, there is a period of increased rate of both unemployment and inflation. This violation of the proposed inverse correlation happened again from 2009 onwards: the unemployment rate and inflation rate rise together and then fall together. Therefore, it is always helpful to dig into the time series data and investigate the trend across time.

I found a blog [_Trade off between unemployment and inflation_](https://www.economicshelp.org/blog/571/unemployment/trade-off-between-unemployment-and-inflation/) from Economics Help.org that discusses on this topic. Here is the data visualization graph from the article that is used to assist the reader in understanding the trends between inflation and unemployment:

<img src="chart.jpeg" width="680" height="550">

## Step two: critique the data visualization

This section will critique the selected visualization using Stephen Few's Data Visualization Effectiveness Profile. The effectiveness of the visualization is assessed through seven criteria, which are further divided into two general categories: _informative_ (Usefulness, Completeness, Perceptibility, Truthfulness, Intuitiveness) and _emotive_(Aesthetics, Engagement). In the [spreadsheet](https://yilinc09.github.io/tswd-portfolio/Data%20Visualization%20Effectiveness%20Profile.pdf), each criteria is ranked on a scale of 1-10 where 0 being the least degree and 10 being the most degree of effectiveness. Explanations and reasonings on how I evaluated the given criteria are provided below:

### 1. Usefulness - 8

In general, this visualization is useful for the intended audience to understand. The audiences who browse this article are mostly attracted by the title and would like to acquire more information on this topic. Using the time-series line graph in this case is a good choice because the viewers can easily catch the changes and trends of the unemployment and inflation over time. The audience can also easily compare how these two economic variables relate to each other. In terms of communicating valuable information, that's where I deducted two points from the grading scale because the visualization does not directly show off in which time period the trade-off happens.

### 2. Completeness - 8

The data visualization has everything necessary to make it understandable. The x-axis represents the years and the y-axis represents the percentage rate. The data points are clearly labeled and easy to read. However, the only point is the visualization uses too much data which causes the line zigzagging around and makes the overall comparison between the two data trends less significant. On the other hand, we can provide more information such as the gap between two rates and highlight period where inverse relationship between two variables occurs.

### 3. Perceptibility - 6

The reader could not understand the information with minimal effort because it requires a much closer look to find out how changes in one variable results the changes in other variable. As mentioned earlier, time-series line graph is the appropriate visualization type to clearly show the pattern of changes multiple variables over time. In terms of how the visualization shows the comparison between the two variables, the visualization uses two different colors to help the viewer distinguish between the two variables, but the meandering trendline makes it difficult to compare the variables.


### 4. Truthfulness - 10

The data used to create the visualization is accurate and reliable because the data is sourced from [Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org/) as cited in the graph. In addition, the methodology employed in creating the graph is valid because time series line graph effectively represents changes in unemployment and inflation over time and provides a clear representation of the relationship between them. Therefore, the visualization has represented the main idea in the most complete and truthful manner without making comparisions that are incorrect.

### 5. Intuitiveness - 5

It is easy to understand what information shows from the line chart, but the relationship between the two variables is difficult to tell with minimal effort. The similar reasoning has been explained in the above criteria section. Since line chart is a commonly used data visualization technique, there are no additional instruction provided in interpreting the information.

### 6. Aesthetics - 4
While the overall aesthetic of the visualization needs more work, I'll start evaluating the good parts. The use of colors in the graph is effective. The blue and red line stands out clearly against the white background and is easy to distinguish from each other. However, the x-axis and y-axis seems to be less aesthetic and expressive. The x-axis labels are crowded together, making it not pleasant to look at. Providing unnecessary information, such as month and day, would potentially distract audiences. Labelling with the year intervals should be sufficient. The y-axis title is ambiguous. The "%" is just a unit of measurement but does not provide any information describing the number. There are also many small twists and turns in the line makes it harder to make comparison.

### 7. Engagement - 10

Overall, the graph will lead the viewer to learn more about the topic from the conclusions they drawn from the graph. It will inspire viewers to investigate why movements in unemployment and inflation sometimes violate the relationship prescribed in economic theory - how do recession periods affect their relationship and how did the stagnation shown in the graph around the 1970s actually occur? People can use this graph as a basis to discuss the data and share their insights with others.


### Overall observations about the data visualization

The two trendlines are the first thing that stood out to me. Using contrasting colors was a great choice which made it easy for me as an audience to differentiate between the two variables. The horizontal grid is also a good choice that stood out to me, as it makes it easier to backtrack data values farther away from the y-axis. 

However, the x-axis and y-axis didn't quite work well. The x-axis labels contain unnecessary information such as month and day, making the whole picture visually unpleasant and distracting. The y-axis title is vague providing no information describing the data but only the unit of measurement. The title is too simple to convey any information. At the same time, too many small upside downs in both curves gave me a hard time to compare and interpret how the two variables relate to each other.

If I were to make a visualization built upon the same dataset, I would label the x-axis with year intervals and change the position of labelling to the bottom instead of y=0. I would re-name the y-axis title as _Percentage Rate (%)_ and move the legend into the figure so the audience does not need to take their eyes off the lines to find the corresponding color representation. Due to the large time span, I would probably use quarterly data instead of monthly to do the comparison and find an alternative to make the transition between the two data points smoother.

### Audience Analysis
**Who is the primary audience for this tool?**
  * People who are interested in understanding the relationship between inflation and unemployment. 
  * People who need to leverage their relationship to make relevant business decisions.

**Do you think this visualization is effective for reaching that audience? Why or why not?**

The line graph format is a common and well-understood visual representation of time-series data, and the appropriate units of x-axis and y-axis makes it easy to understand the data being presented. The use of colors, labels, and design add to the overall engagement of the graph and make it an effective tool for communicating the data to this audience. The main failure of this visualization stems from the inability to clearly communicate the relationship between unemployment and inflation.


### Final thoughts: 
**How successful what this method at evaluating the data visualization you selected?**

In general, this method can be considered as a useful tool for evaluating the effectiveness of my selected data visualization. It helped me evaluate the visualization from multiple dimensions and gave me a more holistic understanding of the topic. As I evaluate it more deeply, it made me more aware of what information I want this visualization to communicate, and what this visualization lacks in terms of effective storytelling. Although the standard details of some criteria seems to be overlapping, it is still able to provide me a more complete picture on the redesign process of the visualization.

**How does this method compare to the Good Charts method?**

The Data Visualization Effectiveness Profile method is focused on evaluating existing visualizations and determining their effectiveness. The DVEP framework provides a systematic and structured approach to evaluating the quality of visualizations, making it a useful tool for data visualization experts and researchers. The method quantifies each metric through a scale, providing clarity and facilitating understanding. However, applying the DVEP can be time-consuming.

The Good Charts method, on the other hand, is a more focused and practical approach to evaluating data visualizations. The metrics of this method provide a simple and straightforward way to evaluate the quality of data visualizations, making it a useful tool for data visualization practitioners. The Good Charts method is well-suited for those who want to improve the quality of their visualizations in a practical and straightforward manner.

**Are there measures you feel are missing or not being captured here?**

I don't feel any missing measures that needed to be captured at this point.

**What would you change?  Provide 1-2 recommendations (color, type of visualization, layout, etc.)**
* Change both axes with more appropriate labels and titles
* Change monthly information to annualy

## Step three: sketch out a solution

### Redesign Ideas

In order to effectively communicate the idea behind the original visualizations, I made the following alterations to my preliminary sketches:

* **X-axis**
  * The x-axis will be labeled with years
  * A title will be added to the x-axis as "Years"
  * ticks will be placed in unit of years
  * The x-axis label will be positioned at the bottom of the graph

* **Y-axis**
  * The title will be renamed to "Rate(%)"
  * The y-axis labels will be represented as integers
 
* **Legend**
  * The legend, previously located at the very bottom of the visualization, will now be positioned right below the title. This change is intended to make the legend to be the second most eye-catching aspect for the audience.
  * To provide additional clarity regarding the line representation, I have also added the name at the end of each line.

* **Title**
  * Change the title to "U.S. Unemployment vs. Inflation"

* **Citation**
  * In addition to the existing source name, I hyperlinked the corresponding source url.

* **Add More Information**
  * In order to ensure that the information remains up-to-date, I will extend the timeline in the original visualization, which originally ended in 2010, to the latest end point of 2022.

* **Remove Unnecessary Information**
  * Eliminate the monthly data and replace it with the average data for each year.

### Sketch

<div class="flourish-embed flourish-chart" data-src="visualisation/12717169"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Step four: Test the solution

### Interviews

**Can you tell me what you think this is?**
  
- Male, mid 20's: Overall it's a good design. Line chart is always effective in visualizing time series data.
- Female, mid 20's: it's a graph that compare and contrasts the US annual inflation rate with unemployment rate ranging from 1975 to 2022.

**Can you describe to me what this is telling you?**

- Male, mid 20's: This visualization is trying to tell the relationship between unemployment and inflation
- Female, mid 20's: This tell me that piror to 1983, the inflation is high yet the unemployment rate is relavtively low. From 1983 to 2022, the unemployment rate has been higher than the inflation rate. In 2022, the inflation rate seems to sky rocket and passing the unemployment rate.

**Is there anything you find surprising or confusing?**

- Male, mid 20's: The relationship between the two variables is not evident from the data and information presented in the visualization.
- Female, mid 20's: Nothing is surprising to me, because both the inflation rate and unemployment rate in 2008 and 2020 reflects the global pandemic

**Who do you think is the intended audience for this?**

- Male, mid 20's: People who are interested in economics
- Female, mid 20's: the intented auidence is for socialists to analyze the relationship between unemployment rate and inflation rate

**Is there anything you would change or do differently?**

- Male, mid 20's: it would be more readable if there are labels included for the major events
- Female, mid 20's: I would add a subtitle to clarify the their relationships.

### Reflections

**Similarities & Differences**
- All recognize the line chart format as effective for visualizing time series data.
- All suggest adding labels or a subtitle to clarify the relationship between the two variables, indicating that they believe the relationship is unclear from the information presented.
- All believe that the intended audience for the visualization is related to economics.
- All recognize that the events of 2008 and 2020 in the data are related to the global pandemic.

The interviewees may have slightly different perspectives on the purpose and effectiveness of the visualization, and have different ideas for how to improve it.

**What patterns in the feedback emerge? What did you learn from the feedback?** 

From the feedback of the interviews, it becomes clear that there is a focus on making the visualization clarity and more understandable for the intended audience. All interviewees suggest adding additional information or clarification to the visualization to make it easier to understand, highlighting the importance of clarity in visualizations. Additionally, both interviewees recognize the line chart format as an effective way to visualize time series data. This highlights a general understanding of best practices for data visualization. The interviewees also believe that the intended audience and focus of the visualization is related to economics, indicating that the visualization is targeted towards a specific subject area. Lastly, all interviewees consider major events in the data, with one suggesting adding labels to highlight these events and the other suggesting adding a subtitle to clarify the relationship between the two variables. This suggests a recognition of the importance of context in data visualization.


## Step five: Build your solution

### Design Modification

- Add a subtitle to clarify the message of this visualization
- Change annually data to quarterly data
- Highlight the Time of Recession

### Final Data Visualization

<div class="flourish-embed flourish-chart" data-src="visualisation/12717395"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

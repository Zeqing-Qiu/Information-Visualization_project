<font size=5 ><b>Information Visualization for Coastal Flooding in Honolulu, Hawaii, During the 21st Century</b></font>

-----


<div ><img src=pics/Githublink.png width=5% /><a href="https://github.com/Zeqing-Qiu/Information-Visualization_project" style="color:Navy;"><u>View this paper and relevent code</u></a> on GitHub </div>

<div ><img src=pics/Article_link.png width=5% /><a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2018JC014741" style="color:Navy;"><u>Source of the Visualization </u></a></div>

-----

## Introduction
>There is a magic in graphs. The profile of a curve reveals in a flash a whole situation — the life history of an epidemic, a panic, or an era of prosperity. The curve informs the mind, awakens the imagination, convinces.&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ——Henry D. Hubbard

The saying above reveals the irreplaceable importance of Information Visualization. To emphasize it, we choose this visualization from a state-of-the-art paper discussing the Frequency of Coastal Flooding in Honolulu, Hawaii, During the 21st Century. In recent years, the frequency of small floods in many areas is increasing, and its cumulative impact may exceed rare extreme cases. Therefore, it is of great significance to verify whether the repeated small floods are related to the rising trend of sea level and to quantify the impact of sea level rise on the trend of flood events in the next few years. 

&emsp;&emsp;Our first sub-visualization shows the trend of sea level change in Honolulu over the years, and the second sub-visualization shows the days when the water level exceeds the limit over the years. And for purchasing a better visualization and more distinguishing insights, we raise these five aspects for improvement:

&emsp;&emsp;&emsp;&emsp;<font size=2.5 ><b>·</b> Color Visualization Trick</font>

&emsp;&emsp;&emsp;&emsp;<font size=2.5 ><b>·</b> Avoid Overlapping and Non-direct Look-up</font> 

&emsp;&emsp;&emsp;&emsp;<font size=2.5 ><b>·</b> Avoid Vertical Texts</font> 

&emsp;&emsp;&emsp;&emsp;<font size=2.5 ><b>·</b> Ink-ratio in Visualization</font> 

&emsp;&emsp;&emsp;&emsp;<font size=2.5 ><b>·</b> Convenience and Emphasizing</font> 

&emsp;&emsp;Besides, with regard to social impact in this visualization, we consider three basic aspects: to take advanced strategies before minor impacts occur, to use the predicted results to formulate policies to prevent future flood and to reveal the impact of sea-level rise through reasonable analysis to break rumors and alleviate people's panic. 



-----
## Illustration on Information Visualization

+ <font size=3 color=#3F7FBF><b>Settings of Story</b></font> 

    Except the historic big flooding events, the topic of recurrent minor flooding has also received considerable attention, because the frequency of such events is increasing in many areas, and the **cumulative impact of frequent minor events can exceed that of rare extremes**. The potential for cumulative impact over many minor events is particularly important for Honolulu, because despite the geographical risk for damaging surge from tropical storms, the harbor tide gauge has not recorded an hourly nontidal surge >60 cm since the record began in 1905.

    &emsp;&emsp;It can be expected that the flood disasters in Hawaii and the surrounding areas of the Pacific Ocean are becoming more and more serious, so it is of great significance to **verify** whether the recurrent minor flooding is **related to the tendency of rising sea level** and to **quantify** the impact of sea level rise on the tendency for flooding events in future years. 
     
+ <font size=3 color=#3F7FBF><b>Detailed Explanations and Insights on Visualization</b></font> 

    At the first step to build predict model which is also the most important thing is that, we should analyse the **trend of changes in hourly sea level** of each year(1905 to 2017, Figure (a)) and the number of days per year for which sea level **exceeds a prescribed threshold** in Honolulu(Figure (b)). Then as a result some conclusions could be drawn and steps could be taken in advance to **avoid unnecessary loss**.
    <div align="center"><img src=pics/old.png width=60% /></div>


+ <font size=3 color=#000079>Figure (a)</font> 

    First thing to mention is that, the first visualization is to set the mean higher high water **(MHHW)** which is a vertical datum defined as the average of daily maximum water levels during the U.S. National Tidal Datum Epoch to be **the meaning of 0 on Y axis**. To be more understandable, it means that the values of hourly sea level each year is to **be compared with the value of MHHW** in Figure (a). 

    The visual variables (Position, color, size, etc) for Figure (a):
    Visual Variables | Data Type or Variation|
    :----------------|:-----------------------|
    blue solid line  |The records of fluctuation of hourly sea level corresponding to the time on X axis|
    black solid line |Fitting trend based on the records of hourly sea level of year|
    orange dot       |The highest observed hourly water level|
    black dashed line| 35 cm above MHHW minor threshold|


    &emsp;&emsp;The **factors** affecting sea level fluctuation include the decadal climate fluctuation,  planetary waves and ocean vortices. In simple terms, climate change, the movement of nearby celestial bodies and the creation of ocean eddies all contribute to recorded sea level fluctuations. 

    &emsp;&emsp;Hence, the highest observed hourly water level represented by the orange dots is **caused by a combination** of seasonally high tides and a variety of ocean processes. All of these phenomena lead to changes in sea level at different times, which can occasionally produce a set of high-water events. 

    &emsp;&emsp;Figure (a) also shows that the highest water levels tend to cluster together. This means that as sea level continues to rise, the time of high water threshold will **tend to be concentrated**. In addition to these times, the water threshold is **usually low**. 

+ <font size=3 color=#000079>Figure (b)</font> 

    Figure (b) shows the number of **exceedance days** per year (Nxd) above the 35 cm threshold.
    
    The visual variables (Position, color, size, etc) for Figure (a):
    Visual Variables |Data Type or Variation|
    :-----------------|-----------------------|
    blue bars        |The number of exceedance days between 1905 and 2016|
    orange bars      |Emphasize the booming number of exceedance days in 2017|


    &emsp;&emsp;Tallying the exceedance days in calendar years reveals the **anomalous nature of 2017** compared to previous years, as no other year experienced more than four exceedance days above the 35cm threshold, yet there are 15 exceedance days in 2017. 

    &emsp;&emsp;Since the first exceedance day in the 1960s, Figure (b) shows that the number of exceedance days in 1980~2000 **increased by 60%** compared with that in 1960~1980, and the number of exceeding days in 2000~2020 **increased by 200%** again. Moreover, when the tidal amplitude decreases, the frequency exceeding MHHW appears to stop over a longer period of time, even as the mean sea level continues to rise. However, after the **minimum change in the long term**, it is likely that the threshold will **increase rapidly** in the short term. 

    &emsp;&emsp;The results show that in Honolulu, the number of days above the threshold will shift **from occasional to chronic**. Over time, this transition will occur more rapidly at higher thresholds, possibly within the next decade.

+ <font size=3 color=#000079>Replicate Visualization</font> 

    This replicated graph is made to better make improvements.
<div align="center"><img src=pics/replicate.png width=60% /></div>

-----

## What is the Effectiveness of this Visualization?
<font size=4 >&emsp;&emsp;——based on the <a href="https://askingthelot.com/what-is-the-definition-of-cognitive-theory/" style="color:Navy;">Cognitive Theory</a></font>

+ <font size=3 color=#3F7FBF><b>Use bold type/lines only to emphasize something</b></font> 

    We can say that information is competing for our attention, so it is nature that bold objects will be recognized as important however meaningless objects with bold mark will stimulus the conflict in comprehension process in brain. 
    <div align="center"><img src=pics/bold.png width=60% /></div>

    &emsp;&emsp;So Figure (a) just use one bright noticeable mark to emphasize the highest observed sea level in 2017, while Figure (b) just paint the bar with the largest number of exceedance days noticeable red color distinguished from other bars.


    


-----
## What Improvements for this Visualization can be Proposed?

+ <font size=3 color=#3F7FBF><b>Choose the right Type of Graph</b></font> 

    One size does not fit all, right ones will best tell the story and answer key questions generated by data all of it connecting with main purpose while wrong types of graphs will only interfere with the readers efforts to read the graph. 

    &emsp;&emsp;The <a href="https://www.tableau.com/learn/articles/data-visualization-tips#:~:text=1%2 0Choose%20the%20right%20charts%20and%20graphs%20for,clues.%20...%206%20Apply%20text%20carefully%20and%20intentionally" style="color:Navy;">line chart</a> connects several distinct data points, which askes our brain to process it as one continuous evolution. The result is a simple, straightforward way to visualize changes in one value relative to another, so it just fit for information visualization for such data that has distinct temporal characteristics as shown in Figure (a). 

    &emsp;&emsp;However, Thousands of data were used in the original image and the original visualization was extremely dense visualized that caused a great obstacle to observation and analysis. 

    &emsp;&emsp;For improvements, We still choose line chart while the new one is not quite the same as the original one, with the mean values of the maximum and minimum values as the two lines respectively. The trend of the two lines reflected the fluctuation of sea level. We still set a linear trend, which represents the mean of the overall change of sea level annually, reflecting a general rising trend of sea level in the past 100 years.  

+ <font size=3 color=#3F7FBF><b>Color Visualization Trick</b></font> 

    In a common sense, we are used to match red with hot and popular and blue with cold and less necessary, because red represents flames yet blue correlates with water. 
    <div align="center"><img src=pics/red_and_blue.png width=30% /></div>

    &emsp;&emsp;Therefore, we choose blue to show the observed sea level record plainly while choose conspicuous red to apply to emphasize element: painting both the highest observed sea level point in Figure (a) and the bar represent largest number of exceed days in Figure (b) with conspicuous red.

+ <font size=3 color=#3F7FBF><b>Avoid Overlapping and Non-direct Look-up</b></font> 

    In Figure (a), the legend element (the rectangle element with four lines of words and icons in the lower right) is overlapped with the visualization, audience could not clearly identify the changes of sea level from 2000 to 2017 in the bottom right corner for it is covered by the legend. 

    &emsp;&emsp;Besides, using too much legends will force readers go back and forth between the graph and the legend, they have to process other elements in the graph and their working memory may overload.

    &emsp;&emsp;Therefore, to avoid overlapping and non-direct look-up, we eliminate the legends to only one containing one necessary explanation, and transform other original legends into the visualization as text variables.

+ <font size=3 color=#3F7FBF><b>Avoid Vertical Texts</b></font> 

    We should also notice that the y-axis labels in the original graph are vertical, besides, the y-label of Figure (b) lacks a unit, which may confuse the audience.

    &emsp;&emsp;Therefore, we rotate the y-axis labels and add unit in consideration of both the convenience and readability.

+ <font size=3 color=#3F7FBF><b>Ink Ratio in Visualization</b></font> 

    In Information Visualization, there is a concept called <a href="https://infovis-wiki.net/wiki/Data-Ink_Ratio" style="color:Navy;">ink ratio</a> introduced by Edward Tufte, 1983. It represents the non-erasable ink used for the presentation of data. So if we take the data-ink into consideration, we should erase the unnecessary part of the graph. 
    <div align="center"><img src=pics/ratio.png width=55% /></div>

    &emsp;&emsp;When applying to this visualization, we should remove the grid and the top and right border lines.   

+ <font size=3 color=#3F7FBF><b>Convenience and Emphasizing</b></font>

    Besides, we should always highlight the important elements to emphasize. For instance, using bold type, conspicuous colors and adding some annotations or labels. Therefore, in Figure (b) we add a number to show the exactly number of exceedance in 2017, on the purpose of emphasizing and convenient for the audience reading this visualization.



+ <font size=3 color=#3F7FBF><b>How does the Improved Visualization Look Like?</b></font>
  
    Below is the improved visualization. 
    <div align="center"><img src=pics/new.png width=80% /></div>

-----
## What is the Impact on Society?
First, according to the results of the visualization, the sea level around Honolulu will rise year by year, increasing the probability of future flooding in Honolulu which may also leading to serious **impact on many industries**, such as fishing and tourism. In the second half of this century, there is likely to be a rapid shift from occasional to prolonged overshoot, suggesting that **adaptation and mitigation strategies** may need to be initiated before any mild impacts occur in affected areas. 

&emsp;&emsp;This visualization is not limited to Honolulu or the state of Hawaii, but also to countries and cities around sea areas. By analyzing this visualization, local governments can devise policies and strategies that will **prevent cities from disaster** in the future.

&emsp;&emsp;Moreover, the good and the bad are mixed on the Internet, it is difficult to tell the true from the false. Especially because of the outbreak of the disaster, the network will always be accompanied by some false information, thus bringing some unnecessary panic. Through this visualization, we can reasonably analyze a series of impacts brought about by sea level rise,  thus greatly **cracking rumours** and **alleviating panics and worries** about floods.


## How to Purchase a Perfect Visualization?
>The goal is to turn data into information, and information into insight.
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ——Carly Fiorina

From this span of analysis and revise on information visualization, we have several insights on how to purchase a better visualization. As the wisdom above reveals that, Information Visualization is tool for audience better understand the information and capture insights that plain text can not show. To achieve this purpose, we could consider these following aspects: 


&emsp;&emsp;1. From the reader’s perspective. Visualization serves for audience. So every action we take should reader-first, avoid issues like overlapping, non-direct look-up and vertical texts, besides, we should add some labels, bold formats, annotations appropriately for a better reader experience.


&emsp;&emsp;2. From the professional perspective. Professionals should use their expertise when creating visualizations. choose right graph type based on their functions, increase the data-ink ratio, care for the color blind and apply cognitive theory to purchase a perfect visualization.


&emsp;&emsp;3. From the practice perspective. We should think highly of revising and getting feedback. Show your template to your colleague and non-professionals, ask for their suggestions and revise your visualizations to purchase a perfect one.

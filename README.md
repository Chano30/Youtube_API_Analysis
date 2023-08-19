# Youtube_API_Analysis
![plot](https://github.com/Chano30/Youtube_API_Analysis/blob/master/images/compilation.png)

## Data Used

**Data** - Youtube API, Channel Cong TV\
**Data Cleaning & Analysis** - Jupyter lab, Python\
**Data Visualization** - Matplotlib, Seaborn


## Questions
1. What are the average views per video?
2. Are likes and comments has a factor for views?
3. How long are usually the videos?
4. When are the day most frequent uploads?
5. What year did the channel go viral?

## Summary of Findings
* For more than 12 years, CongTV has accumulated 516 videos from 2008 - 2023 regardless the year 2010 - 2013
* The top most viewed video, title "The junie boy prank" with almost 14 million views
* most of the videos views averaging on 2 million - 4 million
* likes and comments are correlating to views, when this are huge, then videos accumulating more views
* The most frequent upload days are thursday and friday
* In year 2020, most of the videos of CongTV Channels go viral averaging to 5million views

## Limitations
* Using the `playlistId` of Youtube API the 2 videos of CongTV are missing, This videos are can be found in `searchList` since the API has a request limitation I sticked to this data.

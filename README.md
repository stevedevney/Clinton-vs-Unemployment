# Clinton-vs-Unemployment
2016 Democratic vote vs Unemployment by county. 

I am looking to compare the how likely a county was to vote democratic or republican vs the unemployment rate. 
My thought is that the more likely a county voted democratic in 2016 the higher the unemployment rate is. 

I am using r in the analysis. The vote data comes from Deleetdk on github at: "https://github.com/Deleetdk/USA.county.data/blob/master/data/USA_county_data.RData"
I pulled the unemployment data from: "https://www.bls.gov/web/metro/laucntycur14.txt"

You can see the code, but the data is a rolling of the past 12 months by county. AKA, the Unemployment office only survays an area about 1 time per year, so some of the data is as old as may 2019, while others is newer. I didn't correct for this problem at all. 

What was found was the higher the unemployment the more likely that county was to vote for Clinton in 2016. 

image is here: 
![Plot of Clinton vs Unemployment](https://github.com/stevedevney/Clinton-vs-Unemployment/blob/master/%20Clinton%20vs%20Unemployed.pdf)

Started working on a project I wanted to do since I were a young sports journalist: Analyze referees' calls. 
I find it very amusing that the sport itself finds the courage to do such an open research about its own inconsistencies. 
I think it shows a clear message of sports civilization, because I firmly believe that we should not curse the refs for any 
mistakes that they make. A ref's mistake is just part of the game, nothing more and nothing less. 
I have cleaned my basic dataset, a set that contains info about all the close games played since March 2015. The sample is 
already big and allows for valid conclusions concerning the behavior of referees, as game time approachs to the end. 

10-08-2017

Have been trying to plot something that's really not easy for me: the behavior of the referres as time is nearing to the end. My hunch is that as we go towards the end especially of close games, referees are more inclined to not blow any whistle at all, leaving the game to become much more physical. Data shows this but I really can't programmatically show it. I'd need to cluster time and create three time clusters: whistles when time is less than 10 seconds, less than 60 seconds and between 120 and 60 seconds. I want to show that in the final ten seconds, incorrect non calls are many more than in the previous two clusters. 

Another thing I want to show-- up till now unsuccessfully-- is the distribution of incorrect calls between home and away teams. It is widely believed that home teams are advantaged, but my data shows that this is pretty much balanced. My dataframe columns though are a bit messy when it comes to clearly identify which is the home and which is the away team and which one got the favored whistle. I would probably need to extract a specific word from a column and then somehow try to compare if the disadvantaged team --which has its own columns-- happened to be the home or the away one. 

Basically, those two are the challenges I face if I want to get something more out of a very informative dataset. 

I created a gif showing one of the most common incorrect non calls referees make: travelling. Especially in the NBA rules are much more lenient when it comes to this specific rules, as they mostly want to let the offensive game be played more freely. But sometimes they overdo it!  
# Kickstarting with Excel

## Overview of Project
### Purpose
<p>For this project we are trying to help Louise determine which factors will assist her to successfully reach her fundraising goal for her play *Fever*. We will use Kickstarter data over a certain range of years to gather data and figure out what would be the best course of action for Louise</p>

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
<p>We can see there is a peak in May for successful outcomes, but it slowly decreases until December. It then increases again between Jan-Feb and March-May. Additionally, months with a higher number of successful campaigns also come with a hgiher number of failed campaign so we must take that into account. For example, May had 111 successful but on the other hand had 52 failed. One thing we should consider is the success rate based on launch date which would've been 68% for May (111/111+52. I won't consider cancelled plays as there are a small amount making them somewhat negligible). But if we look at success rates for months like January and December, they may seem to have low number of successes, but the rate is 63% (56/56+33) and 51% (37/37+35), respectively. That could be one deceiving aspect of this chart because the viewer can't understand the rate at which the campaigns are succeeding.</p>

![outcomesVlaunch](https://github.com/mooshak21/kickstarter-analysis/blob/main/Resources/OutcomesLaunchPivot.png)
![outcomesVlaunch](https://github.com/mooshak21/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png "Theater Outcomes vs. Launch Date")

### Analysis of Outcomes Based on Goals
<p>We can conclude that having a fundraising goal of $35K-40K is around the max amount that would work. We can conclude this because the chart plateaus in that range and then sharply decreases in regards to percentage successful. Based on my data, the highest success rates occur in the <$1000 and $1000-$4999 ranges with 74% and 70% success rates, respectively. The price range from $40000-$44999 provides a 63% success rate as well, but there are only 8 entries within that range, so that might not be the best place to look.</p>
  
![outcomesVgoals](https://github.com/mooshak21/kickstarter-analysis/blob/main/Resources/OutcomesGoalsPivot.png) 

![outcomesVgoals](https://github.com/mooshak21/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png "Outcomes vs Goals")

### Challenges and Difficulties Encountered
<p>No Real challenges on my end. I feel like the instructions were very clear and made the process much easier. All I had to look up was the function:<br>
COUNTIF - https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842</p>

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
<p>1. The best time to start your kickstarter for a play is definitely in May as there is a peak in the graph at that time for successful plays.<br>
2.The worst time to start your kickstarter for a play is definitely in October as there is a peak in the graph at that time for failed plays.</p>




- What can you conclude about the Outcomes based on Goals?
<p>Other than what was mentioned before, there is not much consistency with the data that we can take information away from. Kickstarters obviously succeed more at the lower fundraising goals (<$1000), but then success rate dips around $5K and rises again around $25K</p>




- What are some limitations of this dataset?
<p>One limitation I can think of is the lack of information of "largest donation made". For example, if we saw that one play received majority of the money that was funded from one person, we can kind of see that as an outlier because that won't happen in everyone's case. Another limitation is the inclusion of the live kickstarters. Having those included in our charts/analysis doesn't really help because we want to know about successes and failures.</p>

- What are some other possible tables and/or graphs that we could create?
<p>Like I mentioned before, something that might give more insight than Outcomes vs Launch Date would be Outcome Rates vs. Launch Date. This would give more insight into the time periods that have the higher percentages of successful campaigns rather than just showing the number of each outcome.</p>

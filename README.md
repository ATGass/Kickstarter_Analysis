# Module 1 Challenge - The keys to a successful kickstarter campaign
## Discovery
The overarching goal is to help Lousie have a successful kickstarter campaign to fund her play. She was close to her goal but didn't end up reaching it. She would like to know how launch dates and the fundraising goal can effect the chances of a campaign being full-funded. 

## Process
In order to find the effects of launch dates and fundraising goals, we used excel and the kickstarter data to find the best launch dates and goal range. 
We only used theater data for the launch date and plays for fundraising goals. This was done to ensure that the data analyzed was as close to Lousie's play as possible. I didn't run into any challenges but I did initially forget to filter the data by the subcategory for the fundraising goal piece and it made a huge difference in my data set.
### Launch Date
To find the best time to launch a campaign we looked at the results of theater campaigns by their results over time. This allowed us to see exactly which months would be the best for Lousie to launch her campaign.
### Fundraising Goals
In order to porperly sort data we first needed to use a countif formula. This formula allowed us to filter data that fit into our criteria. In this case we need plays separated out into different rows and columns based on their end result (successful, failed, or cancelled) and based on their fundraising goal. Each cell's formula aligned with the fundraising goal range as the row and the result as the column. Once that table was created we used the sum funtion to calculate the toal of each row in order to find the percentage of the end result per fundraising goal range.

## Findings
### Launch Date Findings
May seems to be the best time to launch a theater campaign. There have been 111 successful campaigns while 52 have failed during that month. Realistically anytime between April and July will give the highest rate of success compared to any other month in the year. Lousie should know that theater campaigns only have a 61% success rate overall.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82982180/121748022-eab88600-cacd-11eb-84f7-367560abc90b.png)
### Fundraising Goals
Overall the lower that the fundraising goal is, the better chances it has of being successful. The data shows a spike of successful campaigns between $35,000 and $45,000 but there were only a total of 9 campaigns for that range which makes the data not have a stong foundation to reccomend Lousie to have her fundraising goals that high.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82982180/121748176-26ebe680-cace-11eb-9174-e71fe7e7c2b0.png)

## Results
### Theater Outcomes by Launch Date Conclusions
* April to July are the very best months to launch a campaign in. Nearly all other months have a success rate that is less than the theater average of 61%
* May looks like an obvious choice and while it is the very best month to launch a campaign, the success rate is not much higher than June. June has had 11 less successful campaigns but has a success rate of 65.63% compared to May's success rate of 66.87%.
### Outcomes based on Goals Conclusions
* The lower the funding goal is, the higher the odds are of success.
### Limitations
* The total number of campaigns limits the reliability of certain filtered results. We can't help the data set that we were given, but a larger set would have helped give more actionable results.
* We don't know how the kickstarter campaigns did after the kickstarter was over. The fund raising portion is really only the first step in the process of creating a play or film. We don't know what campaigns that were successful went on to do in terms of ratings or audience turn out and other metrics that might help guide Louise to have a better overall expierence than just the fund raising portion.
### Other Charts & Graphs
There are two charts the I feel would help add to these findings.
#### Play Outcomes by Launch Date
We took a look at Theater Outcomes by Launch Date but if Lousie is looking into plays specifically then there are other sub categories within the theater parent category. The other sub categories within the theater category could potentially alter the outcome of the best timing to launch a campaign.
![Play_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82982180/121824695-ab2b9e80-cc73-11eb-825b-e8caf2cdc86f.png)
There are only a few differnces between this chart and the related theater chart but the differences are impactful. To start with, June has a higher sucess rate than May does eventhough May has more successful campaigns in total. The other impactful difference is that in December there are actually more failed campaigns than there are successful ones. For theater campaigns as a whole, it's a close 50/50 of successful and failed campaigns, but here we see that plays actaully have a worse track record for December. 
#### Play Outcomes by Campaign Length
I do think that the timing of campaigns are impactful but the length of the campaign can also play a powerful role in the overall success and we didn't take a look at that. The median number of days per campaign was 30 days and that also applied to success only and failed only campaigns. However, the mean between the different outcome types does differ between successful and failed campaigns. 
![OutcomesBasedOnLengthOfTime](https://user-images.githubusercontent.com/82982180/121825647-3eb39e00-cc79-11eb-81c2-357bf1b61718.png)
This finding wasn't as impactful as I'd hoped it would be. Naturally, I assumed that failed campaigns would have had a shorter length and that helped contribute to the failure of the campaign. As seen in the chart above, the average failed campaign lenth is actually longer than successful campaigns. I'm glad I pursued this possibility so that we can assure Louise that a 30 day window should be the appropriate amount of time for a successful campaign. 
# Kickstarting a Theater Project

## Successful Kickstarter Requirements

### This report serves to break down what's required to kickstart a theater project successfully.

  Kickstarter projects can be categorized in multiple ways. The approach we have taken involves analyzing the outcomes of Kickstarter programs based on both the start date of the campaigns, and the goal set for the campaigns. We narrowed the focus of our analysis to primarily deal with Theater related Kickstarter projects.

## Types of Analysis and Results

### Analysis of Outcomes Based on Launch Date

  Initial Analysis was to determine the ideal launch date for our campaign on Kickstarter. Ideal timeframe appears to be Launches made between May and August, with May being the best month. This was determined by absolute number of successful campaigns by month, as well as absolute number of failed campaigns and cancelled campaigns by month to ensure the success chance wasn't just a result of an increase in campagins initiated in May. In the Resoruce folder in this respoitory, a graph labelled "Theater_Outcomes_vs_Launch.png" shows that May has an increase in successful campaigns in May, without a meaningful increase in failed or cancelled campaigns at the same time.

  This increase isn't just restricted to May; June, July, and August also demonstrate an increase in success, though each month has less of an increase over normal as compared to the month previously. Again, these analysis are shown to be due to success chance rather than sheer numbers by examining failed and cancelled campaigns as well, which do not deviate from expecetd normal during these timeframes.

### Analysis of Outcomes Based on Goals

  Another metric we used to determine potential success was the size of the campaign launch by funding goal. While there was no linear correlation between campaign goal and success rate, the data definitvely shows that small goals are more likely ot succeed when the goal is under 9,000USD. 9,000USD and 10,000USD have a success rate nearly matching the smallest campaigns, with a rather rapid drop off past 10,000USD.

### Challenges and Difficulties Encountered

  The only true difficulty encountered was handling the metrics calculations for campaigns that had never recieved a contribution. Since their donor/pledge amount was 0, ratio formulas would fail on a divide by zero error, which was handled by assigning the result a 0 in the calculations.

## Results

  Our most significant source of error is likely to be the sample breadth of our data. Also, the data coming from around the world and not just the one country may skew the data, as some countries value theater more than others, and may therefore pledge more. Our data does not consider the country of origin for deciding the success rate.

  Further refinement of the data may yield charts showing success rate by country for theater, which would help resolve some of the errors described above. We could also use a heurisitc to seperate campaigns by ambitiousness, and analyse the results against this estimated metric. That may account for the multiple peaks of success when examining outcomes versus goals set.

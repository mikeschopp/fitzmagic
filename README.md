# fitzmagic

Looking to build out a scoring methodology to show variance among quarterbacks. Inspired by the bearded wonder, Ryan Fitzpatrick.

My intended methodology is to first clean up a decade of NFL game logs by QBs, filtering out anyone without at least 10 attempts. I then only looked at QBs with at least 10 total starts.

Then, I looked at the standard deviation of all passer ratings to get a sense of average volatity.

To score per quarterback, I simply took the QB's individual STDEV and then divided by the average, giving a higher weight to QBs with more volatility.

I wanted to add values for QBs that didn't typically do well but had the potential for greatness. To do that, I added an average passer rating, and divided that by the QB's passer rating. This would score up QBs with bad averages by high volatlity.

For a given security (Nifty50 in this case), define a level of correction (30% in this case; 0.7 in loop)

The output will tell us the following about every instance when the markets corrected by x%:

The date the market formed a top

The date the market corrected by x% (Correction level is user input)

The number of days it took to touch that x% drop

What would be the 6,12,18,24 month return if we had bought at the x% drop?

The date the market formed the bottom

The days it took to reach the bottom (form the top)

The days it took to reach back to its previous top (So if you had bought at the top before the correction, you had negative returns for these many days)

What would be the 6,12,18,24 month return if we had bought at the market bottom?

What would be the 6,12,18,24 month return if we had bought 2 months after the market bottom?

Scatter plot: y axis = no days to recovery; x axis = no. days to reach bottom

This was pre ChatGPT so you will find loops instead of vectorization.

I have not attached the input files due to confidentiality.

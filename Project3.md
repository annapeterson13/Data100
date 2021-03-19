## Project 3 Deliverable

Below is a histogram of the population count of each administrative region in Costa Rica, which I took the logarithm of.

![](Project3Plot1.png)

Now here is a different plot, but with the same data. It shows population density of each administrative region in Costa Rica, also through a logarithm.

![](Project3Plot2.png)

Here I combine the two to show a comparison in shape.

![](Project3Plot3Pink.png)

Below is the same overlapping histogram plot, but with different variables: Topographical Data and Population Density.

![](Project3Plot4.png)

Here I've created a Regression Line model comparing topography in Costa Rica and the population density of each second administrative region. The R-Squared value is 0.0, which essentially means there is no relationship between topography and population in Costa Rica. To me, this is surprising because Costa Rica is a very mountainous terrain and I would expect more people at lower elevations and fewer people at high elevations. But, I suppose that because Costa Rica is *so* mountainous that there is no room for preference, and people are relatively equally scattered.

![](Project3RegressionModelPlot1.png)
![](Summary1Project3.png)

Now I add the variables Urban Cover and Bare Cover to the reggression model, and still obtain an R-Squared value of 0. This likely for the same reasons.
![](Project3RegressionPlot2.png)
![](Summary2Project3.png)

Finally, I've added each variable from the lulc file and plotted the regression line. The R-Squared value is now .8, which is a much higher coorelation now that we've added new factors/varibles to the mix. 
![](Project3RegressionPlot3.png)
![](Summary3Project3.png)

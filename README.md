Monte Carlo Approach and how to use HEC Ras Controller in Hec-Ras simulations is discribed in Breaking the HEC-RAS Code: A User's Guide to Automating HEC-RAS book 
and alsoin https://www.kleinschmidtgroup.com/ras-post/learn-how-to-automate-hec-ras-the-monte-carlo-method. I used this idea to simulate Monte Carlo approach in 
ice jam modelling in 1D Hec-Ras model.I took a part of the code form the book and  made some modifications.
In each simulation all of  the ice jam parametrs are changed, taken from Normal Distribution, when the user sets a range of values.
In addition in each simulation  there are also changed: discharges as external and internal boundaries , water level as a downstream boundary and various location 
of ice jam and ice cover.
As a result we get each of cross sections with simulated water level. This results are sorted and afterwards taken to create a final table, wich contains exceedance 
probability of water levels values for each of cross section. This results can be taken to exceedance probability innudation maps.

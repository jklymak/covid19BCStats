# Statistics for BC COVID 19 outbreak and some plots.

See <https://jklymak.github.io/covid19BCStats/> for updates!

Source: mostly <http://covid-19.bccdc.ca> plus press reports before 15 Mar.  

This is a time series plot of COVID 19 cases in British Columbia, Canada, and Vancouver Island.  The goal is to see what the growth rate is, and whether actions by the government are having an effect on that growth rate.  

Exponential growth is fit as $C = C_0 e^{\frac{t-t_0}/\tau}$ where $C_0$ is the number of cases at time $t_0$.  "Doubling time" is the number of days it takes for cases to double, which is simply $t_{double} = \log(2)\tau$.  The fit is made over the last 7 days.  The straight lines on the logarithmic plot are what would happen over time if the growth rate of infections did not slow down, and the levels they saturate at are the populations of BC and Vancouver Island respectively.  

This is provided with no warranty, and was quickly cobbled together for my own interest.  If you need this data for something serious, please do due dilligence and look the data up yourself!  There is no warranty express or implied.  I am also not at *all* trained in epidemiology, so do not assume my interpretation of the data has any meaning or value.  

That said, any suggestions or corrections gratefully accepted.  Or pointers to better databases and analyses!

![Cases](docs/images/Cases.png)
![Cases](docs/images/VancouverIsland.png)

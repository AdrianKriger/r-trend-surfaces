# Trend Surface Analysis with R (Cape Flats Aquifer)

**Welcome to this Trend Surface Analysis with R Tutorial!** 

In this set of exercises, we will explore the concepts and applications of trend surface analysis, focusing on 1st and 2nd order trend surfaces and empirical smooth functions. We also delve into the various flavors of Kriging; a powerful geostatistical interpolation method.

The goal of Trend surface analysis is to **help us identify and model the underlying trend or pattern in spatial data, while interpolation techniques enable us to estimate values at unsampled locations based on nearby data points**. Through this hands-on exercise and a real-world example, you will gain a deeper understanding of spatial interpolation techniques and their applications in various fields, which includes geology, environmental studies, agriculture, urban planning, remote sensing, climate studies, geomorphology, archaelogy, health studies and seismology.

We will start by understanding the principles of trend surface analysis, a technique used to model spatial trends and variations in data. You will learn how to fit **1st and 2nd order trend surfaces** to a dataset and interpret the results to identify underlying patterns.

Next, we'll explore **empirical smooth functions** to analyze spatial data. You will be introduced to different smoothing techniques, like the generalized additive model and minimum-curvature surface (thin-plate spline) to reveal trends and patterns in noisy datasets.

We end with Kriging. Kriging is a geostatistical interpolation method that provides optimal estimates of unknown values based on spatial autocorrelation. We will cover **Ordinary Kriging, Generalized Least Squares-Regression Kriging and Universal Kriging**, understanding their assumptions, implementation, and the benefits they offer in different scenarios.

For these set of exersices we use a dataset that is well-suited to illustrate the concepts of trend surface: a set of observations of the elevation above mean sea level of the top of the Cape Flats aquifer, South Africa measured at ~ 30 wells [harvested from Table Mountain groundwaterinfo](https://tablemountain.groundwaterinfo.africa/index.php/view/map/?repository=tmwsa&project=1_water_source_areas).


|**WARNING!**|
"|**Please take care with the application of this dataset. 69$%$ of the datapoints are synthetic. I made them up. Only 29 of the wells are authentic. The entire dataset is for illustrative purposes only. A more authoritive collection of data is required for a truly definitive result.**|  

These Notebooks are based on the work of [D.G. Rossiter](https://cals.cornell.edu/david-rossiter) and are subject to copywrite. _No sale nor payment to access_

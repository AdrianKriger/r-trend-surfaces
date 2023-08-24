---
layout: default
title: Home
nav_order: 1
description: "Trend Surface Analysis with R."
---

# Trend Surface Analysis with R (Cape Flats Aquifer)
{: .fs-9 }

In this set of exercises, we explore the concepts and applications of trend surface analysis, focusing on 1st and 2nd order trend surfaces and empirical smooth functions. We also delve into the various flavors of Kriging; a powerful geostatistical interpolation method.

<iframe src="{{site.baseurl | prepend: site.url}}/img/plotly.html" style="width: 800px; height: 400px; border: 0px"></iframe>

The goal of Trend surface analysis is to **help us identify and model the underlying trend or pattern in spatial data, while interpolation techniques enable us to estimate values at unsampled locations based on nearby data points**. Through this hands-on exercise and a real-world example, you will gain a deeper understanding of spatial interpolation techniques and their applications in various fields, which includes geology, environmental studies, agriculture, urban planning, remote sensing, climate studies, geomorphology, archaelogy, health studies and seismology.

For these set of exersices we use a dataset that is well-suited to illustrate the concepts of trend surface: a set of observations of the elevation above mean sea level of the top of the Cape Flats Aquifer, South Africa measured at ~29 wells [harvested from Table Mountain groundwaterinfo](https://tablemountain.groundwaterinfo.africa/index.php/view/map/?repository=tmwsa&project=1_water_source_areas). 

<!--<div class="alert alert-danger">
  <strong>WARNING!:</strong> 
**Please take care with the application of this dataset. xx% of the datapoints are synthetic. I made them up. Only 29 of the wells are authentic. _The entire dataset is for illustrative purposes only. A more authoritive collection of data is required for a truly definitive result._**</div>-->

**WARNING!**  
**Please take care with the application of this dataset. 69% of the datapoints are synthetic. I made them up. Only 29 of the wells are authentic. _The entire dataset is for illustrative purposes only. A more authoritive collection of data is required for a truly definitive result._**

These notebooks are based on the work of [D.G. Rossiter](https://cals.cornell.edu/david-rossiter) and are subject to copywrite. _No sale nor payment to access_

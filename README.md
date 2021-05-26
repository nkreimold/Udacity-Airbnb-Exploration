<p align="center">
  <a href="https://www.airbnb.com/">
    <img src="https://1000logos.net/wp-content/uploads/2017/08/Airbnb-Logo-768x279.png" alt="AirBNB logo">
  </a>
</p>


The repository must have a README.md file that 
communicates the libraries used, 
the motivation for the project, 
the files in the repository with a small description of each, 
a summary of the results of the analysis, 
and necessary acknowledgements


## Table of contents

- [Project Motivation](#project-motivation)
- [Libraries](#libraries)
- [Files included](#files-included)
- [Analysis Results](#analysis-results)
- [acknowledgements](#acknowledgements)


## Project Motivation

Airbnb is a very popular way to travel. It is even more interesting when you compare different markets.
Seattle and Boston are very different locales on the surface, so I wanted to dive in and see what separates them.
The Questions I was interested in answering:

- What causes someone to pay more in each market for an airbnb?
- What causes hosts to price their Airbnb how they do and are the priced appropriately?
- Can we create a model predicting when a property will be booked?


## Libraries

The following libraries are used in this analysis:
- numpy
- pandas
- matplotlib
- datetime
- calendar
- sklearn

## Files Included

- Analysis.ipynb: jupyter notebook with analysis

For each of Seattle and Boston:
- calendar.csv: day level booking detail
- listings.csv: detailed information about Airbnb Listings 
- reviews.csv: review detail for each property


## Analysis Results

Overall, our findings were:

- Boston is more expensive than Seattle, which was to be expected given their average rent prices
- There is more of a market for super-premium properties in Boston, as the tail on the distribution is quite large
- People are more likely to visit Boston in the fall, and Seattle in the summer, as this is when the respective Airbnb's are most expensive
- Outside of this, things most likely to influence prices are number of bedrooms, if you get the entire property, and if the host is a superhost.
- The average booked is actually higher than the average available, indicating that there is a surplus of lower price options in each market
- Models couldn't capture whether a booking would occur very well, so maybe some sampling or further variable work would improve it.


## Acknowledgements

Thanks to Airbnb and Kaggle for the data in this analysis!

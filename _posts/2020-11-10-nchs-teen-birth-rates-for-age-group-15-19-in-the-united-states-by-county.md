---
title: NCHS - Teen Birth Rates for Age Group 15-19 in the United States by County
created: '2020-11-10T16:18:12.888846'
modified: '2021-04-30T02:10:09.955725'
state: active
type: dataset
tags:
  - County Teen Birth Trends
  - County Trends On Teen Births
  - Nchs
  - Teen Births
  - U S Teen Birth Rate
  - United States
groups: []
csv_url: 'https://data.cdc.gov/api/views/3h58-x6cd/rows.csv?accessType=DOWNLOAD'
json_url: 'https://data.cdc.gov/api/views/3h58-x6cd/rows.json?accessType=DOWNLOAD'
layout: post

---
This data set contains estimated teen birth rates for age group 15–19 (expressed per 1,000 females aged 15–19) by county and year.

DEFINITIONS

Estimated teen birth rate: Model-based estimates of teen birth rates for age group 15–19 (expressed per 1,000 females aged 15–19) for a specific county and year. Estimated county teen birth rates were obtained using the methods described elsewhere (1,2,3,4). These annual county-level teen birth estimates “borrow strength” across counties and years to generate accurate estimates where data are sparse due to small population size (1,2,3,4). The inferential method uses information—including the estimated teen birth rates from neighboring counties across years and the associated explanatory variables—to provide a stable estimate of the county teen birth rate.
Median teen birth rate: The middle value of the estimated teen birth rates for the age group 15–19 for counties in a state.
Bayesian credible intervals: A range of values within which there is a 95% probability that the actual teen birth rate will fall, based on the observed teen births data and the model.

NOTES

Data on the number of live births for women aged 15–19 years were extracted from the National Center for Health Statistics’ (NCHS) National Vital Statistics System birth data files for 2003–2015 (5).

Population estimates were extracted from the files containing intercensal and postcensal bridged-race population estimates provided by NCHS. For each year, the July population estimates were used, with the exception of the year of the decennial census, 2010, for which the April estimates were used.

Hierarchical Bayesian space–time models were used to generate hierarchical Bayesian estimates of county teen birth rates for each year during 2003–2015 (1,2,3,4).

The Bayesian analogue of the frequentist confidence interval is defined as the Bayesian credible interval. A 100*(1-α)% Bayesian credible interval for an unknown parameter vector θ and observed data vector y is a subset C of parameter space Ф such that
1-α≤P({C│y})=∫p{θ │y}dθ,
where integration is performed over the set  and is replaced by summation for discrete components of θ.  The probability that θ lies in C given the observed data y is at least (1- α) (6).

County borders in Alaska changed, and new counties were formed and others were merged, during 2003–2015. These changes were reflected in the population files but not in the natality files. For this reason, two counties in Alaska were collapsed so that the birth and population counts were comparable. Additionally, Kalawao County, a remote island county in Hawaii, recorded no births, and census estimates indicated a denominator of 0 (i.e., no females between the ages of 15 and 19 years residing in the county from 2003 through 2015). For this reason, Kalawao County was removed from the analysis. Also , Bedford City, Virginia, was added to Bedford County in 2015 and no longer appears in the mortality file in 2015. For consistency, Bedford City was merged with Bedford County, Virginia, for the entire 2003–2015 period. Final analysis was conducted on 3,137 counties for each year from 2003 through 2015. County boundaries are consistent with the vintage 2005–2007 bridged-race population file geographies (7).

SOURCES

National Center for Health Statistics. Vital statistics data available online, Natality all-county files. Hyattsville, MD. Published annually.

For details about file release and access policy, see NCHS data release and access policy for micro-data and compressed vital statistics files, available from: http://www.cdc.gov/nchs/nvss/dvs_data_release.htm.

For natality public-use files, see vital statistics data available online, available from: https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm.

National Center for Health Statistics. U.S. Census populations with bridged race categories. Estimated population data available. Postcensal and intercensal files. Hyattsville, MD

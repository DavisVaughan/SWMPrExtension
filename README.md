
![](swmpr_logo.png)
#### *Julie Padilla, jpadilla@limno.com*, [LimnoTech](www.limno.com)

[![Travis-CI Build Status](https://travis-ci.org/padilla410/SWMPrExtension.svg?branch=master)](https://travis-ci.org/padilla410/SWMPrExtension)

<!-- README.md is generated from README.Rmd. Please edit that file -->



# Overview 

The System Wide Monitoring Program ([SWMP](http://nerrs.noaa.gov/RCDefault.aspx?ID=18)) was implemented by the National Estuarine Research Reserve System ([NERRS](http://nerrs.noaa.gov/)) in 1995 to provide continuous monitoring data at over 140 continuous monitoring stations in 28 estuaries across the United States.  SWMPrExtension (pronounce "swamper extension") is an R package that provides additional functions to organize and analyze SWMP data and is intended as a companion package for [SWMPr](https://github.com/fawda123/SWMPr) (pronounced "swamper"). Currently, there is no citation for SWMPrExtension.

[SWMPr](https://github.com/fawda123/SWMPr) is an R package for retrieving, organizing, and analyzing estuary monitoring data from SWMP. SWMPr can be cited as follows:

*Beck MW. 2016. SWMPr: An R package for retrieving, organizing, and analyzing environmental data for estuaries.  The R Journal. 8(1):219-232. https://journal.r-project.org/archive/2016-1/beck.pdf*

# Installing the package

This package is not currently available on CRAN, but will be in the near future

The development (unstable) version of this package can be installed from Github:


```r
install.packages('devtools')
library(devtools)
install_github('padilla410/SWMPrExtension')
library(SWMPrExtension)
```

# Using the package

Documentation for SWMPrExtension is currently in development.

A quick summary of the SWMPr package can be found [here](https://github.com/fawda123/SWMPr). A detailed manuscript describing full use of the SWMPr package is available from the [R Journal](https://journal.r-project.org/archive/accepted/beck.pdf). All source materials for the manuscript are available [here](https://github.com/fawda123/swmpr_manu).

SWMPrExtension adds several functions to existing concepts in SWMPr and introduces a new concept called "Reporting".

<h3>Analyze</h3>
<table>
<tr><td><code>annual_range.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>historical_daily_range.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>historical_range.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>raw_boxplot.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>seasonal_barplot.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>seasonal_boxplot.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>threshold_identification.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>threshold_percentile_plot.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>threshold_plot.swmpr</code></td><td>Working...</td></tr>
<tr><td><code>threshold_summary.swmpr</code></td><td>Working...</td></tr>
</table>

<h3>Retrieve</h3>
<table>
<tr><td><code>import_local_nut</code></td><td>Working...</td></tr>
</table>

<h3>Misc</h3>
<table>
<tr><td><code>assign_season</code></td><td>Working...</td></tr>
</table>

<h3>Reporting</h3>
<table>
<tr><td><code>get_reserve</code></td><td>Working...</td></tr>
<tr><td><code>get_shp_name</code></td><td>Working...</td></tr>
<tr><td><code>get_site_code</code></td><td>Working...</td></tr>
<tr><td><code>get_site_coordinates</code></td><td>Working...</td></tr>
<tr><td><code>get_sites</code></td><td>Working...</td></tr>
</table>

--- 
title: "R Exercises for the NOAA Satellite Course"
author: "Cara Wilson, Jennifer Sevadjian, and  Dale Robinson"
date: "8 March 2020"
bibliography: book.bib
description: 'A compilation of R exercises used in the NOAA Satellite Course. '
documentclass: book
github-repo: dhr-sc
link-citations: yes
site: bookdown::bookdown_site
biblio-style: apalike
url: http\://coastwatch.pfeg.noaa.gov/
---

# Preface{-}  
These exercises are materials for the NOAA Satellite Training Course offered each year by regional nodes of NOAA's CoastWatch program. They demonstrate techniques to extract data from the ERDDAP data servers using the rerddapxtracto library written in R. 


## NOAA CoastWatch/OceanWatch Program{-}  

NOAA CoastWatch/OceanWatch provides easy access for everyone to global and regional satellite data products for use in understanding, managing and protecting ocean and coastal resources and for assessing impacts of environmental change in ecosystems, weather, and climate.  

![](images/cw_logo_80.png)  <span style="color:blue;font-size:30px;">[CoastWatch](https://coastwatch.noaa.gov/)</span>


## CoastWatch West Coast Regional Node and PolarWatch{-}  

These course materials were developed and are distributed by the [West Coast Node](https://coastwatch.pfeg.noaa.gov/) of NOAA CoastWatch and by [PolarWatch](https://polarwatch.noaa.gov/). Information about the courses and services offered by West Coast Node can be found at the following links:  

| <button>[Courses](https://coastwatch.pfeg.noaa.gov/courses/satellite_course.html)</button> <button>[Data Catalog](https://coastwatch.pfeg.noaa.gov/data.html)</button> <button>[Data Server](https://coastwatch.pfeg.noaa.gov/erddapinfo/index.html)</button> <button>[Xtractomatic](https://coastwatch.pfeg.noaa.gov/xtracto/)</button>




cp poes/data/AT202007* /ERDData3/poes_data/2020/1day/

cp poes/data/AT202008* /ERDData3/poes_data/2020/1day/
cp poes/data/AT202009* /ERDData3/poes_data/2020/1day/

cp -v poes/data/2020/hday/AT202009* /ERDData3/poes_data/2020/hday/

cp poes/data/2017/hday /ERDData3/poes_data/2017/hday


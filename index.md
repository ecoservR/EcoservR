---
title: EcoservR
---

## Welcome
EcoservR is a tool for mapping natural capital assets and ecosystem services. It is a re-write of [Ecoserv-GIS](https://www.nature.scot/snh-research-report-954-ecoserv-gis-v33-toolkit-mapping-ecosystem-services-gb-scale) and is currently being developed and tested at [Liverpool John Moores University](https://www.ljmu.ac.uk/) in collaboration with [Natural Capital Solutions](http://www.naturalcapitalsolutions.co.uk/), [Forest Research](forestresearch.gov.uk/), and the [Cheshire Wildlife Trust](https://www.cheshirewildlifetrust.org.uk/). The work is supported by [Defra](https://www.gov.uk/government/organisations/department-for-environment-food-rural-affairs) and the Natural Capital Working Group in the Liverpool City Region.

### Jump to...

+ [The Ecoserv approach](#the-ecoserv-approach)
+ [Environmental baseline](#environmental-baseline)
+ [Ecosystem services](#ecosystem-services)
+ [Can I use EcoservR?](#ecoservr-release)
+ [Get in touch](#get-in-touch)


# The Ecoserv approach

EcoservR is an updated version of [Ecoserv-GIS](https://www.nature.scot/snh-research-report-954-ecoserv-gis-v33-toolkit-mapping-ecosystem-services-gb-scale), a toolkit originally developed by [Durham Wildlife Trust](https://durhamwt.com/) for mapping habitats and ecosystem services in the UK using widely available national datasets. The toolkit generates an environmental baseline classifying over 200 habitat types, and uses spatial models to map their capacity to provide a range of ecosystem services, as well as the demand for them.

We decided to re-write Ecoserv-GIS in the R language to eliminate the dependency on proprietary software and workflows that were no longer supported. [R](https://www.r-project.org/) is a free, open-source software widely used in the environmental sciences and with growing geospatial capabilities. EcoservR currently supports 7 of the 9 original Ecoserv-GIS ecosystem services. Its applicability is currently restricted to England, but we are planning support for the whole of Great Britain in the coming year. 

<br>

<div display="block" class="row-full-img-right" id="baseline" markdown="1">
   <div class="main-content-right" markdown="1">
   
# Environmental baseline

Obtaining a natural capital asset map is a first step towards understanding and measuring the value of benefits derived from nature. EcoservR produces a detailed habitat map based on a range of nationally-available and mostly free datasets.

<a class="linkbutton" href="{{ site.github.url }}/basemap"> Learn more </a>

  </div>
  <p class = "disclaimer">Background image contains Ordnance Survey data © Crown copyright and database rights 2020 Ordnance Survey (100025252)</p>
</div>

<div display="block" class="row-full-img-left" id="services" markdown="1">
  <div class="main-content-left" markdown="1">

# Ecosystem services

EcoservR measures and maps a range of ecosystem services. Capacity and demand maps can be analysed to identify opportunities and "pinch points", to plan and deliver interventions where they are best suited and most needed. The current toolkit includes:

+ __Carbon storage__
+ __Air purification__
+ __Water purification__
+ __Pollination__
+ __Local climate regulation__
+ __Noise regulation__
+ __Accessible nature__

<a class="linkbutton" href="{{ site.github.url }}/ecoservices" style="float:right;"> Learn more </a>

<br style="clear:both" />

  </div>
</div>

<div display="block" class="row-full-img-right" id="netgain" markdown="1">
   <div class="main-content-right" markdown="1">
# Measuring change

A powerful feature of EcoservR is the ability to calculate projected change - gains and losses - in the delivery of ecosystem services arising from a given intervention. Our spatial models are very sensitive, meaning that effects can be detected beyond site level to local and landscape scales. So whether you are trying to meet environmental net gain targets for a new build or want to measure the impact of planting a new woodland at the neighbourhood and city scale, EcoservR will provide robust, evidence-based figures to support your assessment.

<a class="linkbutton" href="{{ site.github.url }}/interventions"> Learn more </a>
  
  </div> 
</div>

# EcoservR release

We are currently beta-testing the tool with a few organisations. EcoservR will be released as an R package in the summer 2021. It will be free to use and open-source.

Watch this space!

<br>


<div display="block" class="row-full" id="contact" markdown="1">
  <div class="main-content" markdown="1">
# Get in touch

Questions or feedback? Please get in touch with us at ecoservR *at* gmail.com

</div>
</div>

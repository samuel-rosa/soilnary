---
title: "Rationale"
author: "Alessandro Samuel-Rosa"
date: "21 May 2016"
output: html_document
---

Production of up-to-date, high resolution global soil information seems to be gaining momentum. The Food and 
Agriculture Organization ([FAO][fao]) of the United Nations ([UN][un]), through the Global Soil Partnership 
([GSP][gsp]), along with many other national and international organizations, is working hard to convince 
decision and policy makers, as well as the scientific community as a whole, of the importance of high quality
soil information to deal with some of the major issues of our time. For that end, FAO has been supporting the
implementation of joint efforts that could lead to the adoption of global development goals focused on the
sustainable use of soil resources. The primary basis to reach this goal is soil data. However, as it has been
identified by FAO, soil data is "*fragmented, partly outdated, heterogeneous and difficult to compare, not 
easily accessible, and not responding to users needs*", some of it under threat of being lost forever.

Multiple organizations have been working on the development of soil databases. Most of them focus on the 
national level, which is operationally less complex than working at the regional or global levels due to the 
use of standard procedures for soil description and analysis. Developing fully functional regional or global 
soil databases requires not only rescuing and collating legacy soil data -- which is a very difficult task --, 
but also the tedious and complex work of [*standardization*][sta] and *harmonization*. Soil data 
standardization and harmonization guarantee that a soil database can accommodate any soil data irrespective of 
its origin, that is, the method of sampling, description, analysis, classification, mapping, measurement units, 
and so on.

One of the few organizations working to rescue, collate and harmonize legacy soil profile description 
and analytical data at the global level is [ISRIC][isric] World Soil Information, accredited by the 
International Council of Science ([ICSU][icsu]) as the World Data Centre for Soils. Recently, ISRIC announced 
the World Soil Information Service ([WoSIS](http://www.isric.org/data/wosis)), a centralized, user–focused, 
comprehensive and accessible database resulting from the compilation of almost 100,000 profiles from around the 
world. At the current development level, ISRIC has been able to standardize all soil property data with regard 
to naming conventions and measurement units, as well as the description of analytical methods 
([Ribeiro et al, 2015](http://www.isric.org/sites/default/files/isric_report_2015_03.pdf)).

Building comprehensive and functional regional or global soil databases requires more than collating,
standardizing and harmonizing the existing soil data. Developers must go beyond to guarantee that the soil 
database is easily accessible for both downloading and entering new soil data. Several tools can be used for 
that end, such as web-based interactive viewing platforms (see [GeoNode][geonode]), applications for mobile 
devices (see [SoilInfo App][soilinfo]), and so on. However, truly guaranteeing developing database 
accessibility requires accounting for the linguistic diversity among users. This is where 
**internationalization** and **localization** comes in.

Internationalization and localization are concepts developed in the field of computing refering to the 
adaptation of computer software to different languages and regional differences (read more about it in 
[Wikipedia][wiki]). For computer software developers, the goal is to make their software usable and accessible
to people that speak languages other than that with which the computer software has been documented. 

[fao]: http://www.fao.org/home/en/
[un]: http://www.un.org/
[gsp]: http://www.fao.org/globalsoilpartnership/en/
[sta]: https://en.wikipedia.org/wiki/Standardization
[isric]: http://www.isric.org/
[icsu]: http://www.icsu.org/
[geonode]: http://geonode.org/
[soilinfo]: http://soilinfo.isric.org/
[wiki]: https://en.wikipedia.org/wiki/Internationalization_and_localization

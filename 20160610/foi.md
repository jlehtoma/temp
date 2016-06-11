---
title: "Subscription costs to scientific publishers in Finland 2010-2015"
author: Leo Lahti
date: "2016-06-11"
output: 
  md_document:
    variant: markdown_github
---





Publisher subscription costs in Finland 2010-2015
===========


## Background

Following [Tim Gowers successful FOI request on the subscription costs
for scientific journals in
UK](http://gowers.wordpress.com/2014/04/24/elsevier-journals-some-facts/),
we made a similar request in Finland together with the [Open Knowledge
Finland association and other Open Science
advocates](https://www.facebook.com/groups/241398182642057/permalink/411482855633588).

After the Finnish universities turned down my FOI request in summer
2014, we appealed in court, which decided the case positive for us in
August 2015. The Finnish Ministry of Education [Open Science
Initiative](http://openscience.fi) then organized the [data release]()
as summarized [elsewhere]().

Related data have been collected in a few countries, as summarized in
Stuart Lawson's [recent
post](http://stuartlawson.org/2016/06/publicly-available-data-on-international-journal-subscription-costs).
However, Finland is now one of the first countries (after US and UK)
where the subscription fees are available at the level of individual
publishers.

Below we present a preliminary analysis of this data collection based
on automated document generation with rmarkdown (see [source
code](https://github.com/antagomir/temp/blob/master/20160610/foi.Rmd)).


## Overall subscription costs 2010-2015




 * Total costs for Finland 2010-2015: 128.9 million EUR
 * [Total costs by subscription category](table/cost_by_category.csv)
 * [Total costs by agreement type](table/cost_by_type.csv)


<img src="figure/foi-totalcosts-1.png" title="plot of chunk foi-totalcosts" alt="plot of chunk foi-totalcosts" width="430px" /><img src="figure/foi-totalcosts-2.png" title="plot of chunk foi-totalcosts" alt="plot of chunk foi-totalcosts" width="430px" />


### Costs by publisher

 * 244 publishers ([table of annual costs by publisher](table/cost_by_publisher_year.csv))

<img src="figure/foi-totalcosts2b-1.png" title="plot of chunk foi-totalcosts2b" alt="plot of chunk foi-totalcosts2b" width="430px" />




Total costs paid to scientific publishers by Finland 2010-2015. The annual increase is indicated.

![plot of chunk foi-costbytime](figure/foi-costbytime-1.png)


Top-10 publishers (out of 244) correspond to 77% of the overall costs.

![plot of chunk foi-timebypublisher2](figure/foi-timebypublisher2-1.png)


### Costs by organization

 * 62 organizations ([table of annual costs by organization](table/cost_by_organization_year.csv))


<img src="figure/foi-totalcosts2-1.png" title="plot of chunk foi-totalcosts2" alt="plot of chunk foi-totalcosts2" width="430px" />


![plot of chunk foi-timebyorganization2](figure/foi-timebyorganization2-1.png)



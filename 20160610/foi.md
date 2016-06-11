---
title: "Subscription costs to scientific publishers in Finland 2010-2015"
author: Leo Lahti
date: "2016-06-11"
output: 
  md_document:
    variant: markdown_github
---





Scientific journal subscription costs in Finland 2010-2015
===========


## Background

Following [Tim Gowers successful FOI request on the subscription costs
for scientific journals in
UK](http://gowers.wordpress.com/2014/04/24/elsevier-journals-some-facts/),
we made a similar request in Finland together with the [Open Knowledge
Finland association and other Open Science
advocates](https://www.facebook.com/groups/241398182642057/permalink/411482855633588).

After the Finnish universities [turned down my FOI request in summer
2014](https://github.com/okffi-science/2014-tietopyynto-lisenssimaksut),
we appealed in court, which decided the case positive for us in August
2015. The Finnish Ministry of Education [Open Science
Initiative](http://openscience.fi) then organized the [data release]()
as summarized [elsewhere](). Here, we present a preliminary analysis
of the data, including [reproducible source
code](https://github.com/antagomir/temp/blob/master/20160610/foi.Rmd)).

With this data release, Finland is one of the first countries (after
US and UK) where the subscription fees have been released at the level
of individual publishers. For a summary on other countries, see Stuart
Lawson's [recent
post](http://stuartlawson.org/2016/06/publicly-available-data-on-international-journal-subscription-costs).



## Overall subscription costs 2010-2015



Based on the data collected by the Ministry of Education, Finland paid
128.9 million EUR subscription and other
fees on scientific publishing during 2010-2015. It seems to me that
open access publishing fees are not included, as I could not find some
major open access players (PLoS, BMC) from the list.

Information is also available on the [agreement
type](table/cost_by_type.csv), organization type, and [subscription
category](table/cost_by_category.csv).


<img src="figure/foi-totalcosts-1.png" title="plot of chunk foi-totalcosts" alt="plot of chunk foi-totalcosts" width="430px" /><img src="figure/foi-totalcosts-2.png" title="plot of chunk foi-totalcosts" alt="plot of chunk foi-totalcosts" width="430px" />


### Costs by publisher

Overall, the Finnish data covers 244 publishers ([table of annual costs by publisher](table/cost_by_publisher_year.csv)).

The figure shows the absolute and relative figures paid to the top publishers during 2010-2015. Over one third of the total costs go to Elsevier, which is often [criticized](https://gowers.wordpress.com/2014/04/24/elsevier-journals-some-facts/) for its huge [profit margins](http://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0127502).

<img src="figure/foi-totalcosts2b-1.png" title="plot of chunk foi-totalcosts2b" alt="plot of chunk foi-totalcosts2b" width="430px" />




Total costs paid to scientific publishers by Finland 2010-2015. The annual increase is indicated. Top-10 publishers (out of 6) correspond to NaN% of the overall costs.



<img src="figure/foi-costbytime-1.png" title="plot of chunk foi-costbytime" alt="plot of chunk foi-costbytime" width="420px" /><img src="figure/foi-costbytime-2.png" title="plot of chunk foi-costbytime" alt="plot of chunk foi-costbytime" width="420px" />


### Costs by organization

 * 62 organizations ([table of annual costs by organization](table/cost_by_organization_year.csv))


<img src="figure/foi-totalcosts2-1.png" title="plot of chunk foi-totalcosts2" alt="plot of chunk foi-totalcosts2" width="430px" />


![plot of chunk foi-timebyorganization2](figure/foi-timebyorganization2-1.png)



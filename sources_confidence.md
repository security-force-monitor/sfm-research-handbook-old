# Sources and Confidence

Every piece of data in Security Force Monitor has a source and is assigned a confidence score.

## Sources
### Citation format {#source_citation_format}

Every data point in Security Force Monitor must have one or more sources associated with it. A source should be recorded in this format:

> Title of article or website page. Name of publishing organization \(country of organization\). Date. url. Internet Archive link: url

For example:

> Army parades oil bunkers in Kaduna. Premium Times \(Nigeria\). 8 May 2013. [http://www.premiumtimesng.com/regional/nwest/133295-army-parades-oil-bunkers-in-kaduna.html](http://www.premiumtimesng.com/regional/nwest/133295-army-parades-oil-bunkers-in-kaduna.html)   
> Internet Archive link: [https://web.archive.org/web/20140912060820/https://www.premiumtimesng.com/regional/nwest/133295-army-parades-oil-bunkers-in-kaduna.html\#sthash.Fc0DTTxe.dpbs](https://web.archive.org/web/20140912060820/https://www.premiumtimesng.com/regional/nwest/133295-army-parades-oil-bunkers-in-kaduna.html#sthash.Fc0DTTxe.dpbs)

### Country information {#source_country_information}

We include the country information because there could be a publication with the same name based in another country - for example there is a publication based in Nigeria named [The Guardian](https://guardian.ng/) as well as a publication based in the United Kingdom named [The Guardian](https://www.theguardian.com/uk).

### Date {#source_date}

For the date we always use the ISO standard which means DAY MONTH YEAR

### Which archived URL to use {#source_which_archive_url}

If the website you are using has been archived previously, use the oldest archive date url. For example, if the url was saved 2 times, once in 2011 and once in  2013, use the url from 2011.

You may come across a source citation that includes a link that is not available online anymore and there is no link for the Internet Archive. In this case, you can still try to look up the link in the Archive as someone could have saved it. For example, see the following citation:

> Army, Navy Redeploy Senior Officers. This Day \(Nigeria\). 13 February 2014. [http://www.thisdaylive.com/articles/army-navy-redeploy-senior-officers/171306/](http://www.thisdaylive.com/articles/army-navy-redeploy-senior-officers/171306/)

If you try to access the link, you'll get nowhere. When you look up the link in the Internet Archive, however, you'll find that it's been saved two times and you are thus able to access it. When you do that, don't forget to update the source citation so others can access the article without searching for it in the following way:

> Army, Navy Redeploy Senior Officers. This Day \(Nigeria\). 13 February 2014. [http://www.thisdaylive.com/articles/army-navy-redeploy-senior-officers/171306/](http://www.thisdaylive.com/articles/army-navy-redeploy-senior-officers/171306/) Internet Archive link: [https://web.archive.org/web/20140307081703/http://www.thisdaylive.com/articles/army-navy-redeploy-senior-officers/171306](https://web.archive.org/web/20140307081703/http://www.thisdaylive.com/articles/army-navy-redeploy-senior-officers/171306)

In this specific case you could also find the article on the AllAfrica.com server by looking up the title of the article in Google. This is because the parent website of the article is one of the websites archived by AllAfrica.com. However, if the article came from a source that AllAfrica.com doesn't cover, you'd still be able to access it via the Internet Archive \(if it's been saved there before\).

## Confidence {#source_confidence}

Each data point has a confidence score attached to it. The confidence scores only relate to the specific data point to which they are attached.

For instance, a wide variety of sources could agree on ``` 1 Division``` as the name of an organization. A confidence score of ```High``` could be assgned to this data point. However, if there is only one source for ```One Division``` as an alias, a confidence score of ```Low``` would be merited.

Confidence scores are determined first by what is agreed about the overall structure and nature of the security forces by highly reputable sources \(government, major reports/books and other sources of high quality information\).

The Confidence scores assigned to each data point are  also influenced by the number of confirming sources and the source type. In general, government sources are weighed as more reliable than non-government sources. **However** there is no _gold standard_ source. Government sources make spelling errors, contain conflicting information, just as non-government sources do \(media, civil society, etc.\).

All data points begin with a confidence score of ``` Low``` until a confluence of sources merit the designation of ```Medium```. The gap between upgrading the confidence score of a data point from ```Low``` to ```Medium``` is smaller than  when moving from ```Medium to High```.

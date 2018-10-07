# About

This is a submission to the [Force 2018 Conference](https://www.force11.org/meetings/force2018) taking place on 11-12 October 2018 in Montreal. It was submitted shortly prior to the submission deadline on May 1, 2018.

# What areas does your talk cover?

- [ ] Research Techniques
- [X] Publishing
- [ ] Data Publishing
- [X] Global Perspectives
- [ ] Research and Schol Comms Policy
- [X] General - Scholarly Communication
- [ ] Other:

# What is the title of your talk?

Research published over the last week

# What is your talk about? (1 paragraph)

*Please supply one paragraph describing your talk and how it relates to the theme of Engagement. (Please also declare any conflicts of interest. )*

With thousands of research publications coming out each day, it is hard to keep or even get an overview. I will provide a guided tour around research from various fields that was published over the week prior to the session, highlighting (i) how to find such publications, (ii) what can be learned from them in such a short time span, (iii) how to engage with them and (iv) lessons that authors, readers, publishers and others involved in scholarly communication can draw from the experience. The talk will be given on the basis of https://github.com/Daniel-Mietchen/events/blob/master/FORCE-2018-research-published-last-week.md .

# Anything else we should know? 

This talk is closely related to the one at https://github.com/Daniel-Mietchen/events/blob/master/FORCE-2018-research-performed-last-week.md , and I would strongly prefer the two to be scheduled back to back in the same room, either before a session covering scholarly communication more broadly, or before a break.

# Query examples

## Wikidata

```SPARQL
SELECT ?work ?title ?date_time WHERE {
  VALUES (?earliest) {("2018-10-03T00:00:00Z"^^xsd:dateTime)}
  VALUES (?latest) {("2018-10-10T00:00:00Z"^^xsd:dateTime)}
  ?work wdt:P577 ?date_time .
  hint:Prior hint:rangeSafe true .
  FILTER (?date_time >= ?earliest)
  FILTER (?date_time <= ?latest)
  ?work wdt:P1476 ?title ;
        wdt:P356 ?doi .
} 
ORDER BY DESC(?date_time)
LIMIT 100
```

[Try it!](https://query.wikidata.org/#SELECT%20%3Fwork%20%3Ftitle%20%3Fdate_time%20WHERE%20%7B%0A%20%20VALUES%20%28%3Fearliest%29%20%7B%28%222018-10-03T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime%29%7D%0A%20%20VALUES%20%28%3Flatest%29%20%7B%28%222018-10-10T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime%29%7D%0A%20%20%3Fwork%20wdt%3AP577%20%3Fdate_time%20.%0A%20%20hint%3APrior%20hint%3ArangeSafe%20true%20.%0A%20%20FILTER%20%28%3Fdate_time%20%3E%3D%20%3Fearliest%29%0A%20%20FILTER%20%28%3Fdate_time%20%3C%3D%20%3Flatest%29%0A%20%20%3Fwork%20wdt%3AP1476%20%3Ftitle%20%3B%0A%20%20%20%20%20%20%20%20wdt%3AP356%20%3Fdoi%20.%0A%7D%20%0AORDER%20BY%20DESC%28%3Fdate_time%29%0ALIMIT%20100)

# PubMed/ PMC

* https://www.ncbi.nlm.nih.gov/pubmed/?term=%22last+7+days%22%5BPDat%5D
* https://www.ncbi.nlm.nih.gov/pubmed/?term=%22last+7+days%22%5BEDat%5D
* https://www.ncbi.nlm.nih.gov/pmc/?term=(%22viruses%22%5BMeSH+Terms%5D+OR+%22viruses%22%5BAll+Fields%5D+OR+%22virus%22%5BAll+Fields%5D)+AND+(%222018%2F10%2F03%22%5BPDat%5D+%3A+%222018%2F10%2F10%22%5BPDat%5D)&cmd=DetailsSearch

# Twitter

* https://twitter.com/search?f=tweets&vertical=default&q=((doi%20AND%2010)%20OR%20doi.org%20OR%20pmid%20OR%20pmcid%20OR%20arxiv)%20AND%20(published%20OR%20new%20OR%20paper%20OR%20journal%20OR%20article%20OR%20preprint%20OR%20today%20OR%20yesterday%20OR%20week)
* https://twitter.com/arXiv_trend

# Google

* via ORCID: https://www.google.com/search?num=100&ei=z4C5W63BPIKCwgSKmZuoCA&q=site%3Aorcid.org+%22oct+2018%22+doi

# See also 

* [FORCE-2018.md](FORCE-2018.md)
* [Bims: Biomed news](http://biomed.news/)
* [Today's publications](https://github.com/fnielsen/scholia/issues/513)

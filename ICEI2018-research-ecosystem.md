# About

This file hosts a contribution to the [10th International Conference on Ecological Informatics](http://icei2018.uni-jena.de/) taking place on 24-28 September 2018 in Jena and specifically the Session S1.6 ["Semantics for biodiversity and ecosystem research"](https://icei2018.uni-jena.de/session/s1-6-semantics/) at 10:30 - 12:15 on Thursday 27 September 2018 in Lecture Hall 4.

# Title of the abstract/talk

Visualizing the research ecosystem of ecosystem research via Wikidata

# Name of the authors

* Daniel Mietchen
* Finn Årup Nielsen
* Egon Willighagen

# e-mail-address (please mark corresponding author)

* daniel.mietchen[at]virginia.edu*
* faan[at]dtu.dk
* egon.willighagen[at]maastrichtuniversity.nl

# Affiliations

* Data Science Institute, University of Virginia, Charlottesville, VA, USA
* Cognitive Systems, DTU Compute, Technical University of Denmark, Copenhagen, Denmark
* Department of Bioinformatics - BiGCaT, Maastricht University, Maastricht, The Netherlands

# Keywords (max. 5)

- Wikidata
- SPARQL
- research system
- visualization
- bibliometrics

# Submission abstract

Like research in general, biodiversity and ecosystem research takes place in a sociotechnical ecosystem that connects researchers, institutions, funders, databases, locations, publications, methodologies and related concepts with the objects of study and the world around them. Schemas for describing such concepts are growing in breadth and depth, number and popularity, as are mechanisms to persistently and uniquely identify the concepts, the schemas, their relationships or any of their components. In parallel, more and more data &mdash; and particularly metadata &mdash; are being made available under open licenses, which facilitates discoverability, reproducibility and reuse, as well as data integration.

Wikidata is a community-curated open knowledge base in which concepts covered in any Wikipedia &mdash; and beyond &mdash; can be described in a structured fashion that can be mapped to RDF and queried using SPARQL as well as various other means. Its community of close to 20,000 monthly contributors oversees a corpus that currently comprises nearly 50 million 'items', i.e. entries about concepts. These items are annotated and linked via almost 5000 'properties' that describe relationships between items or between items and external entities or that express specific values. The items and properties have persistent unique identifiers, to which labels and descriptions can be attached in about 300 natural languages. For instance, Q61457 represents the item for 'acetaldehyde' and Q183339 '*Antilope cervicapra*', while P3063 stands for the property of 'average gestation period', and P3117 for 'DSSTOX substance identifier'. Besides taxa, chemical compounds, toxicology, geomorphological features or ecological interactions, Wikidata also contains information about researchers and many components of their research ecosystems, including a growing body of publications and databases, particularly in the life sciences.

A range of open-source tools is available to interact with Wikidata &mdash; to enter information, curate and query it. One of them is Scholia, a frontend to Wikidata's SPARQL endpoint. Available via https://tools.wmflabs.org/scholia/ , it can be used to explore research publications and how they relate to authors, institutions, funders and other parts of the research ecosystem, as well as to taxa, metabolic networks, or geolocations. 

In this presentation &mdash; which will be given on the basis of https://github.com/Daniel-Mietchen/events/blob/master/ICEI2018-research-ecosystem.md &mdash; we will use Scholia as a starting point for exploring how information about biodiversity and ecosystem research is represented in Wikidata and how it can be explored, curated and reused.

# Notes from drafting
Points to consider including
- link to session
- link to biodiversity and ecosystem research
- open data
- data integration
- Wikidata
- multilingual
- taxon names vs. commons names
- Wikibase
- games, e.g. file candidates
- Scholia
- taxa, habitats and nature of ecological interactions
- validation
- SDGs
- Each of these items has a persistent unique identifier, e.g. Q52105 for 'habitat'. The items are annotated and linked via about 5000 'properties' (likewise with persistent identifiers) that describe relationships between items &mdash; e.g. P171, 'parent taxon' &mdash; or between items and external entities &mdash; e.g. Mount Kilimanjaro (Q7296) has the Smithsonian volcano ID (P1886) of '222150' &mdash; or that express specific values, e.g. that *Antilope cervicapra* (Q183339) has an average gestation period (P3063) of 5-6 months.

# See also 

* [ICEI2018.md](ICEI2018.md)
* [ICEI2018-citizen-science.md](ICEI2018-citizen-science.md)
* [Wikimedia projects and citizen science](https://www.wikidata.org/wiki/User:Daniel_Mietchen/ECSA_2018)
* [EPA CompTox and Wikidata](http://chem-bla-ics.blogspot.bg/2017/01/epa-comptox-dashboard-ids-in-wikidata.html)
* [Global map of national parks, per Wikidata](https://twitter.com/SciHiBlog/status/987984942050217984)
* [Map of geolocated topics co-occurring with taxa as the main subject of scholarly publications](https://query.wikidata.org/#%23defaultView%3AMap%0ASELECT%0A%20%20%3Flocation%20%3FlocationLabel%0A%20%20%3Fgeo%0A%20%20%3Fexample_work%20%3Fexample_workLabel%0AWITH%20%7B%0A%20%20SELECT%0A%20%20%20%20%3Flocation%20%3Fgeo%0A%20%20%20%20%28SAMPLE%28%3Fwork%29%20AS%20%3Fexample_work%29%0A%20%20WHERE%20%7B%0A%20%20%20%20%23%20Find%20works%20that%20are%20marked%20with%20main%20subject%20of%20the%20topic.%0A%20%20%20%20%3Fwork%20wdt%3AP921%20%3Ftopic%20.%0A%20%20%20%20%3Ftopic%20wdt%3AP31%20wd%3AQ16521%20.%0A%20%20%20%20%0A%20%20%20%20%23%20Identify%20co-occuring%20topic%20that%20is%20geo-locatable.%20%0A%20%20%20%20%3Fwork%20wdt%3AP921%20%3Flocation%20.%0A%20%20%20%20%3Flocation%20wdt%3AP625%20%3Fgeo%20.%0A%20%20%7D%0A%20%20GROUP%20BY%20%3Flocation%20%3Fgeo%0A%7D%20AS%20%25results%0AWHERE%20%7B%0A%20%20INCLUDE%20%25results%0A%20%20%0A%20%20%23%20Label%20the%20results%0A%20%20SERVICE%20wikibase%3Alabel%20%7B%0A%20%20%20%20bd%3AserviceParam%20wikibase%3Alanguage%20%22en%2Cda%2Cde%2Ces%2Cfr%2Cjp%2Cnl%2Cno%2Cru%2Csv%2Czh%22.%0A%20%20%7D%0A%7D%0A)
* [Ozymandias](http://iphylo.blogspot.com/2018/08/gbif-challenge-entry-ozymandias.html)
  - [vimeo video](https://vimeo.com/285864743)

# History

The conference had a call for proposals with an [April 15 deadline](http://icei2018.uni-jena.de/calls/), by which I submitted the abstract, which received the submission number 143. On May 15, I was [notified of its acceptance](https://github.com/Daniel-Mietchen/events/issues/339#issuecomment-389138931).

*[About](#about)・[Abstract](#abstract)・[Contact](#contact)*

# Opening up the research data life cycle

## Abstract

More and more aspects of the research data life cycle involve some form of sharing - be it the protocols used to generate the data, the software to analyze it, metadata about the data, the data itself or other aspects of its life cycle, from ethical review to citizen science. This talk zooms in on some examples in different stages of different data life cycles and explores how the changing dynamics of data sharing interact with the dynamics of doing research more generally.

## The research data life cycle

- exists in many versions
- key components:
  - plan・get permissions・get funding・get infrastructure・collect metadata・collect data・process data・analyze data・share data・archive data・preserve data・delete data
  - every "・" is an opportunity to rinse, repeat, improve and share

## Opening up the research ecosystems

In the following, I am trying to sketch out a vision for open research ecosystems, roughly on the 2030 timescale, as per the [UN's Sustainable Development Goals](https://sustainabledevelopment.un.org/sdgs) and several ongoing strategy processes (e.g. [National Institute of Dental and Craniofacial Research (NIDCR)](https://nidcr2030.ideascale.com/), [Wikimedia](https://2030.wikimedia.org/), [Gathering for Open Source Hardware (GOSH)](https://openscience.ub.uni-bielefeld.de/1025/how-to-make-open-science-hardware-ubiquitous-by-2025)) and [What we know about the future](https://meta.wikimedia.org/wiki/Template:Strategy/Wikimedia_movement/2017/navbox).

Some things that I am missing in current research ecosystems:
- **Map**: How to map any research ecosystem?
  - [map of science based on paper clickstream data from a decade ago](https://doi.org/10.1371/journal.pone.0004803.g005)
    - neither data nor tools are open
    - not updatable
    - no zoom
  - [map of topics co-occurring with "Zika virus" in the literature](https://query.wikidata.org/#%23defaultView%3AGraph%0A%23defaultView%3ATable%0Aselect%20distinct%20%3Ftopic1%20%3Ftopic1Label%20%3Ftopic2%20%3Ftopic2Label%20where%20{%0A%20%20{%20%3Fwork%20wdt%3AP921%2Fwdt%3AP31*%2Fwdt%3AP279*%20wd%3AQ202864%20.%20}%0A%20%20union%20{%20%3Fwork%20wdt%3AP921%2Fwdt%3AP361%2B%20wd%3AQ202864%20.%20}%0A%20%20union%20{%20%3Fwork%20wdt%3AP921%2Fwdt%3AP1269%2B%20wd%3AQ202864%20.%20}%0A%20%20%3Fwork%20wdt%3AP921%20%3Ftopic1%2C%20%3Ftopic2%20.%20%0A%20%20filter%20(wd%3AQ202864%20!%3D%20%3Ftopic1%20%26%26%20wd%3AQ202864%20!%3D%20%3Ftopic2%20%26%26%20%3Ftopic1%20!%3D%20%3Ftopic2)%0A%20%20SERVICE%20wikibase%3Alabel%20{%0A%20%20%20%20bd%3AserviceParam%20wikibase%3Alanguage%20%22en%2Cfr%2Cde%2Cru%2Ces%2Czh%2Cjp%22.%0A%20%20}%0A}%0A%0A)
    - from [Scholia profile for topic "Zika virus"](https://tools.wmflabs.org/scholia/topic/Q202864)
    - open data, open tools, open API, updatable
    - "zooming" possible by changing the topic
    - still mainly limited to "papers", since citation metadata to, from and between other research objects is scarce at best
- **How to map research that is being *performed now* or *planned for the near future*?**
  - some inspiration: real-time [visualization](http://wikistream.wmflabs.org/#namespace=article&robot=true&user=true&wiki=all) and [sonification](http://listen.hatnote.com/#en,fa,ar,sa,es,de,ru,jp,zh,ko) of Wikimedia edits
  - What about [doing this for research](https://github.com/sparcopen/open-research-doathon/issues/34)? 
    - [As it happens](https://www.youtube.com/watch?v=LwW1-X3glak)? 
    - [All along the research cycle](https://doi.org/10.3897/rio.1.e7547)?
  - with appropriate filtering, something like this could serve as the basis for researchers, funders, public and others to engage with a given research topic
  - particularly relevant in the case of public health emergencies, which also provide a context where "open by default" is actually within reach
  - works best if data and metadata are [FAIR](https://doi.org/10.1038/sdata.2016.18) by default
  - publicly versioned [machine actionable data (or project) management plans](https://doi.org/10.3897/rio.3.e13086) as a way to connect research projects (past, ongoing and future) with relevant individuals, communities, institutions and their respective resources and workflows
- **Queriability**: How can data from different parts of the research ecosystems best be integrated in a way that allows to address issues that cut across research fields?
  - Wikidata as a hub for structured open knowledge across domains, with biomedicine being one of the pilot areas
- **Ethics**: making ethics data FAIR
  - [talk on the topic](https://github.com/Daniel-Mietchen/events/blob/master/PIDapalooza.md)
  - [further notes](https://github.com/Daniel-Mietchen/datascience/blob/master/ethics.md)
- **Sustainability**: How to better align the priorities within the research ecosystems (open or not) with the needs of humanity as a whole?
- **Lean administration**: How can openness be used to reduce bureaucracy?
  - e.g. [self-organized fund allocation](https://doi.org/10.1007/s11192-016-2110-3)
- **Effective policies**: How can different policies and infrastructures be made better aware of each other?

# About

This page ( https://github.com/Daniel-Mietchen/events/blob/master/3rd-BEXIS-2-User-and-Developer-Conference.md ) hosts a presentation that will be given on 15 June 2017 at 7am UTC. It is a contribution to the [3rd BEXIS 2 User and Developer Conference](http://fusion.cs.uni-jena.de/bexis2userdevconf2017/) taking place on 16 June 2017 in Jena, with an associated workshop on June 15. BEXIS (also BExIS) stands for "[Biodiversity Exploratories Information System](https://www.bexis.uni-jena.de/)" and is a research environment for managing the entire data life cycle for biodiversity data.

# Some of my activities in this space

- helping to improve [data sharing in public health emergencies](https://doi.org/10.2471/BLT.17.192096)
- working on [making data mangement plans machine actionable, versioned and public](https://doi.org/10.3897/rio.3.e13086)
- helped shape the [Open Science Prize](http://openscienceprize.org/)
- helping to explore [technical aspects of preprint services in the life sciences](https://doi.org/10.3897/rio.3.e11825)
- helping to [collect citations for the sum of human knowledge](https://meta.wikimedia.org/wiki/WikiCite_2017)
- contributing to [data science policy in the European Union](https://github.com/FAIR-EG/consultation)
- helping to [organize events around modernizing scholarly communication](https://www.force11.org/group/force2017-organizing-committee/program-committee)
- editing an open-science [journal](http://riojournal.com/browse_articles) that aims to make entire research processes visible, not just the results
- running a [bot](https://commons.wikimedia.org/wiki/User:Open_Access_Media_Importer_Bot) that feeds openly licensed multimedia from PubMed Central into Wikimedia Commons
- editing the [Topic Pages](http://collections.plos.org/topic-pages) collection at PLOS Computational Biology

# Contact

- [@EvoMRI](https://twitter.com/EvoMRI)
- email: daniel.mietchen[at]()virginia.edu
- ORCID: [0000-0001-9488-1870](http://orcid.org/0000-0001-9488-1870)

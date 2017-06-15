*[About](#about)・[Abstract](#abstract)・[Contact](#contact)*

# Opening up the research data life cycle

## Abstract

More and more aspects of the research data life cycle involve some form of sharing - be it the protocols used to generate the data, the software to analyze it, metadata about the data, the data itself or other aspects of its life cycle, from ethical review to citizen science. This talk zooms in on some examples in different stages of different data life cycles and explores how the changing dynamics of data sharing interact with the dynamics of doing research more generally.

## The research data life cycle

- can be framed in many ways ([UVA example](http://data.library.virginia.edu/data-management/lifecycle/))
- key components: plan **・** get permissions **・** get funding **・** get infrastructure **・** collect metadata **・** collect data **・** process data **・** analyze data **・** *publish* **・** preserve data **・** reuse metadata **・** find data **・** access data **・** reuse data **・** reproduce data **・** delete data
- exact arrangement does vary
- frequent 'rinse and repeat'

## What does it mean to open it up?

- no single *publishing* step within the cycle, since every intermediate step is an opportunity to share
- [video](https://www.youtube.com/watch?v=LwW1-X3glak)

# Some of my activities in this space

- helping to improve [data sharing in public health emergencies](https://doi.org/10.2471/BLT.17.192096)
- working on [making data mangement plans machine actionable, versioned and public](https://doi.org/10.3897/rio.3.e13086)
- helped shape the [Open Science Prize](http://openscienceprize.org/)
- helping to explore [technical aspects of preprint services in the life sciences](https://doi.org/10.3897/rio.3.e11825)
- helping to [collect citations for the sum of human knowledge](https://meta.wikimedia.org/wiki/WikiCite_2017)
- contributing to [data science policy in the European Union](https://github.com/FAIR-EG/consultation)
- helping to [organize events around modernizing scholarly communication](https://www.force11.org/group/force2017-organizing-committee/program-committee)
- editing an open-science [journal](http://riojournal.com/browse_articles) that aims to make entire research processes visible, not just the results
- running a [bot](https://commons.wikimedia.org/wiki/User:Open_Access_Media_Importer_Bot) that feeds openly licensed multimedia from PubMed Central into Wikimedia Commons for reuse on Wikipedia and elsewhere
- editing the [Topic Pages](http://collections.plos.org/topic-pages) collection at PLOS Computational Biology

## How to discover research that is being *performed now* or *planned for the near future*?

- **Actual need** 
  - [Zika example](https://www.statnews.com/2016/02/16/zika-data-sharing/)
  - [further notes on emergency response](https://github.com/Daniel-Mietchen/datascience/blob/master/emergency-response.md)
- **Some inspiration** 
  - real-time [visualization](http://wikistream.wmflabs.org/#namespace=article&robot=true&user=true&wiki=all) and [sonification](http://listen.hatnote.com/#en,fa,ar,sa,es,de,ru,jp,zh,ko) of Wikimedia edits
  - What about [doing this for research](https://github.com/sparcopen/open-research-doathon/issues/34)? 
    - As it happens (e.g. as per the video above)
    - [All along the research cycle](https://doi.org/10.3897/rio.1.e7547)?
  - with appropriate filtering, something of this kind could serve as the basis for researchers, funders, the public and others to engage with a given research topic
  - particularly relevant in the case of public health emergencies, which also provide a context where "open by default" is actually within reach
  - works best if data and metadata are [FAIR](https://doi.org/10.1038/sdata.2016.18) by default (see [open consultation](https://github.com/FAIR-Data-EG/consultation/issues))
  - publicly versioned [machine actionable data (or project) management plans](https://doi.org/10.3897/rio.3.e13086) as a way to connect research projects (past, ongoing and future) with relevant individuals, communities, institutions and their respective resources and workflows
- **Queriability**: How can data from different parts of the research ecosystems best be integrated in a way that allows to address issues that cut across research fields?
  - Wikidata as a hub for structured open knowledge across domains, with biomedicine being one of the pilot areas
    - [sample queries](https://www.wikidata.org/wiki/User:ProteinBoxBot/SPARQL_Examples)
      - [map of topics co-occurring with "Zika virus" in the literature](https://query.wikidata.org/#%23defaultView%3AGraph%0A%23defaultView%3ATable%0Aselect%20distinct%20%3Ftopic1%20%3Ftopic1Label%20%3Ftopic2%20%3Ftopic2Label%20where%20{%0A%20%20{%20%3Fwork%20wdt%3AP921%2Fwdt%3AP31*%2Fwdt%3AP279*%20wd%3AQ202864%20.%20}%0A%20%20union%20{%20%3Fwork%20wdt%3AP921%2Fwdt%3AP361%2B%20wd%3AQ202864%20.%20}%0A%20%20union%20{%20%3Fwork%20wdt%3AP921%2Fwdt%3AP1269%2B%20wd%3AQ202864%20.%20}%0A%20%20%3Fwork%20wdt%3AP921%20%3Ftopic1%2C%20%3Ftopic2%20.%20%0A%20%20filter%20(wd%3AQ202864%20!%3D%20%3Ftopic1%20%26%26%20wd%3AQ202864%20!%3D%20%3Ftopic2%20%26%26%20%3Ftopic1%20!%3D%20%3Ftopic2)%0A%20%20SERVICE%20wikibase%3Alabel%20{%0A%20%20%20%20bd%3AserviceParam%20wikibase%3Alanguage%20%22en%2Cfr%2Cde%2Cru%2Ces%2Czh%2Cjp%22.%0A%20%20}%0A}%0A%0A)
      - [scholarly profile pages](https://tools.wmflabs.org/scholia/topic/Q202864)
- **Ethics**: making ethics data FAIR
  - [talk on the topic](https://github.com/Daniel-Mietchen/events/blob/master/PIDapalooza.md)
  - [further notes](https://github.com/Daniel-Mietchen/datascience/blob/master/ethics.md)
- **Sustainability**: How to better align the priorities within the research ecosystems (open or not) with the needs of humanity as a whole?
  - e.g. the [UN's Sustainable Development Goals](https://sustainabledevelopment.un.org/sdgs)
  - [further notes](https://github.com/Daniel-Mietchen/datascience/blob/master/sustainability.md)
- **Lean administration**: How can openness be used to reduce bureaucracy?
  - e.g. [self-organized fund allocation](https://doi.org/10.1007/s11192-016-2110-3)
- **Effective policies**: How can different policies and infrastructures be made better aware of each other?
  - make policies machine readable?
  - start with machine readable licensing statements, e.g. Creative Commons licenses and CC0 waiver

## What does this mean for BEXIS?

* Use open licenses and [not -NC restrictions](https://dx.doi.org/10.3897/zookeys.150.2189) to the extent possible, and CC0 for data ([WikiPathways example](http://wikipathways.org/index.php/WikiPathways:CC0_Announcement)
* Share early and often: let people (and machines) see more of what you are doing, closer to when you are doing it ([upcoming iDiv symposium on data mobilization](https://github.com/Daniel-Mietchen/events/issues/44))
* Your ideas

# About

This page ( https://github.com/Daniel-Mietchen/events/blob/master/3rd-BEXIS-2-User-and-Developer-Conference.md ) hosts a presentation that will be given on 15 June 2017 at 7am UTC. It is a contribution to the [3rd BEXIS 2 User and Developer Conference](http://fusion.cs.uni-jena.de/bexis2userdevconf2017/) taking place on 16 June 2017 in Jena, with an associated workshop on June 15. BEXIS (also BExIS) stands for "[Biodiversity Exploratories Information System](https://www.bexis.uni-jena.de/)" and is a research environment for managing the entire data life cycle for biodiversity data.

# Contact

- [@EvoMRI](https://twitter.com/EvoMRI)
- email: daniel.mietchen[@](https://please-do-not-spam.me)virginia.edu
- ORCID: [0000-0001-9488-1870](http://orcid.org/0000-0001-9488-1870)


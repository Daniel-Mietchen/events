# About

This file hosts a contribution to the [10th International Conference on Ecological Informatics](http://icei2018.uni-jena.de/) taking place on 24-28 September 2018 in Jena and specifically the Session S3.6 ["Efficient data and workflow management for reaching Sustainable Development Goals (SDGs) targets associated to biodiversity and ecosystems"](https://icei2018.uni-jena.de/session/s3-6-sustain-development-goals-sdg/) at 10:30 - 12:30 on Tuesday 25 September 2018 in Lecture Hall 5.

# Title

* Community-curated Linked Open Data about the Sustainable Development Goals, their targets and indicators

# Submission abstract

The targets and indicators associated with the [Sustainable Development Goals](https://sustainabledevelopment.un.org/sdgs) form a complex network of relationships between policy and practice, aspirations and achievements across domains and around the globe. This poses challenges for monitoring, evaluating and communicating progress towards these goals. Wikidata is a Linked Open Data platform that is developed and curated collaboratively by the Wikimedia community as a sister project to Wikipedia. Extending across disciplinary boundaries, it contains information about many of the concepts related to the  Sustainable Development Goals, and the community has begun to map the network of relationships between these concepts.

Focusing on examples related to biodiversity and ecosystems, this presentation will explore how Wikidata, its semantic core Wikibase and its global multilingual community can be leveraged to represent and contextualize the Sustainable Development Goals as well as the associated targets and indicators in a way that allows people to make use of that information in the language of their choice, for a given country or on a global level. It will be given on the basis of https://github.com/Daniel-Mietchen/events/blob/master/ICEI2018-SDGs.md , which will be updated until and possibly after the event. Special emphasis will be given to practical examples for how Wikidata and Wikibase can help integrate information about efforts addressing different components of the SDGs, or in different contexts.

# Outline

1. [Unstructured representation of information related to the SDGs](ICEI2018-SDGs.md#unstructured-representation-of-information-related-to-the-sdgs)
2. [Structured representation of information related to the SDGs](ICEI2018-SDGs.md#structured-representation-of-information-related-to-the-sdgs)
3. [Making SDG-related data FAIR](ICEI2018-SDGs.md#making-sdg-related-data-fair)
4. [First steps](https://github.com/Daniel-Mietchen/events/blob/master/ICEI2018-SDGs.md#first-steps)
5. [Outlook](ICEI2018-SDGs.md#outlook)

# Unstructured representation of information related to the SDGs

- SDG-related pages at the United nations, e.g. https://www.un.org/sustainabledevelopment/sustainable-development-goals/
- Wikimedia sites
  - e.g. 
    - https://en.wikipedia.org/wiki/Sustainable_Development_Goals
    - https://meta.wikimedia.org/wiki/WikiProject_UNESCO/Global_Goals_Discussion
- many other places

# Structured representation of information related to the SDGs

- some sites about the SDGs as a group, e.g. http://www.sdgindex.org/
- sites specialized in individual SDGs, targets or indicators, e.g. 
  - http://childmortality.org/ for Target 3.2 (reducing child mortality)
  - https://hi-knowledge.org/invasion-biology/ for Target 15.8 (reducing the impact of invasive species)
    - set of ca. 40 key hypotheses in invasion biology
    - set of ca. 1000 papers that have been annotated as to the degree to which they support or question any of these hypotheses
- [Ontology Plays a Part in United Nations Sustainable Development Goals Project](http://www.dataversity.net/ontology-has-big-part-to-play-in-united-nations-sustainable-development-goals-project/)
- [Sustainable Development Goals Interface Ontology (SDGIO)](https://github.com/SDG-InterfaceOntology/sdgio)
  - imports several existing ontologies (overview on slide 14  of [this presentation](http://ncgia.buffalo.edu/OntologyConference/PPT/Jensen.pdf))
    - e.g. Environmental Ontology (ENVO)
  - [has no license](https://github.com/SDG-InterfaceOntology/sdgio/issues/112)
    - [part of a bigger problem](https://github.com/OBOFoundry/OBOFoundry.github.io/issues/285)

# Making SDG-related data FAIR

- FAIR Data Principles: [Findable, Accessible, Interoperable, Reusable](https://doi.org/10.1038/sdata.2016.18)
- [Wikidata is a FAIR platform](https://www.wikidata.org/wiki/Wikidata:WikidataCon_2017/Submissions/Using_Wikidata_to_make_research_data_FAIR)
  - Further characteristics of Wikidata
    - editable by anyone, including machines
    - reusable by anyone for any purpose (as per [CC0](https://creativecommons.org/publicdomain/zero/1.0/))
    - multilingual (can handle, integrate and expose data across ca. 300 languages)
    - community-driven (ca. [20k contributors per month](https://www.wikidata.org/wiki/Special:Statistics))
    - has substantial content about most of the topics covered by SDGs, targets and indicators
      - e.g. [recent disasters](https://www.wikidata.org/wiki/Wikidata:WikiProject_Humanitarian_Wikidata/Recent_disasters)

# First steps

Multiple SDG-relevant community initiatives (also known as "WikiProjects") have been created, e.g.:
- [WikiProject Sustainable Development](https://www.wikidata.org/wiki/Wikidata:WikiProject_Sustainable_Development)
- [WikiProject Humanitarian Wikidata](https://www.wikidata.org/wiki/Wikidata:WikiProject_Humanitarian_Wikidata)
- [WikiProject Invasive Species](https://www.wikidata.org/wiki/Wikidata:WikiProject_Invasive_Species)
- [WikiProject Ontology](https://www.wikidata.org/wiki/Wikidata:WikiProject_Ontology)
  - includes mapping to existing ontologies, e.g. 
    - [Environment Ontology ID (P3859)](https://www.wikidata.org/wiki/Property:P3859)
- [WikiProject Medicine](https://www.wikidata.org/wiki/Wikidata:WikiProject_Medicine)
- [WikiCite](https://meta.wikimedia.org/wiki/WikiCite)
  - allows Wikidata-based literature overviews, e.g. for
    - [invasive species](https://tools.wmflabs.org/scholia/topic/Q183368)
    - [Zika virus](https://tools.wmflabs.org/scholia/topic/Q202864)
    - [child mortality](https://tools.wmflabs.org/scholia/topic/Q61559)
    - [maternal mortality](https://tools.wmflabs.org/scholia/topic/Q1339474)
    - [waster water](https://tools.wmflabs.org/scholia/topic/Q336191)
  - see also talk tomorrow: 
    - [Visualizing the research ecosystem of ecosystem research via Wikidata](ICEI2018-research-ecosystem.md)
      - Lecture Hall 4, ca. 13:15.
      - Session S1.6 [Semantics for biodiversity and ecosystem research](https://icei2018.uni-jena.de/session/s1-6-semantics/), 10:30-14:15

# Outlook 

- Automatically updated maps that are interactive and editable and come with full provenance
  - [demo](https://commons.wikimedia.org/wiki/File:Map_of_disasters_color-coded_by_disaster_type_-_Wikidata_Query_Service_as_of_2018-07-14.png)
- Addressing bias in the data
  - [demo](https://commons.wikimedia.org/wiki/File:Wikidata_Map_July_2018_Big.png)
- Collaborative inquiries into the data
  - [demo](https://www.wikidata.org/wiki/Wikidata:Request_a_query)

# See also 

* [ICEI2018.md](ICEI2018.md)
* [ICEI2018-research-ecosystem.md](ICEI2018-research-ecosystem.md)

# History

The call for proposals had an [April 15 deadline](http://icei2018.uni-jena.de/calls/), by which I submitted the abstract, which received submission number 147. On May 15, I was notified of its acceptance.

# Name of the authors

Daniel Mietchen

# e-mail-address (please mark corresponding author)

daniel.mietchen[at]virginia.edu*

# Affiliations

Data Science Institute, University of Virginia, Charlottesville, VA, USA

# Keywords (max. 5)

- Wikidata
- Wikibase
- multilinguality
- Linked Open Data
- SPARQL

# About

On April 20-22, the [2017 Sage Assembly](http://sageassembly.org/?page_id=13) (hashtag: [#SageAssembly](https://twitter.com/search?vertical=default&q=sageassembly%20OR%20(sage%20AND%20(assembly%20OR%20congress%20PR%20bio))%20OR%20sagebio)) is taking place in Seattle. In preparation for the event, the organizers have asked for a "Link to your work that best fits the Assembly", which will be linked from the [list of participants](http://sageassembly.org/?page_id=48). I think the best way to address that is to set up a dedicated document here that I can update before, during and possibly after the Assembly, whose theme this year is "Mapping Open Research Ecosystems".

From the [homepage](http://sageassembly.wpengine.com/):
> In 2017, we will bring the Assembly to Seattle, Sage Bionetworks’ home base, and back to the themes closest to us: open innovation in science, and the acceleration of health research through open systems, incentives and  standards.  Together, we will explore how open ecosystems form, where they work, and what boundaries are necessary to operate them successfully. We will also address the consequences, intended or otherwise, of living in more open ways. As always you can expect the unexpected at a Sage Assembly – with a focus on participant interaction, engaging panels, lots of interaction, and an afternoon outside the venue where we will work in teams on projects that explore our themes in non-traditional ways.

# Some of my activities in this space

* At work
  - helping to improve [data sharing in public health emergencies](https://doi.org/10.2471/BLT.17.192096)
  - working on [making data mangement plans machine actionable, versioned and public](https://doi.org/10.3897/rio.3.e13086)
  - helped shape the [Open Science Prize](http://openscienceprize.org/)
  - organising events like [this open research do-a-thon](https://github.com/sparcopen/Open-Research-doathon) to help bring people together around data-centric research workflows
  - helping to explore [technical aspects of preprint services in the life sciences](https://doi.org/10.3897/rio.3.e11825)
  - More complete documentation [here](https://github.com/Daniel-Mietchen/datascience/)
* Elsewhere
  - helping to [collect citations for the sum of human knowledge](https://meta.wikimedia.org/wiki/WikiCite_2017)
  - contributing to [data science policy in the European Union](http://ec.europa.eu/transparency/regexpert/index.cfm?do=groupDetail.groupDetail&groupID=3464)
  - helping to [organize events around modernizing scholarly communication](https://www.force11.org/group/force2017-organizing-committee/program-committee)
  - editing an open-science [journal](http://riojournal.com/browse_articles) that aims to make entire research processes visible, not just the results
  - running a [bot](https://commons.wikimedia.org/wiki/User:Open_Access_Media_Importer_Bot) that feeds openly licensed multimedia from PubMed Central into Wikimedia Commons
  - editing the [Topic Pages](http://collections.plos.org/topic-pages) collection at PLOS Computational Biology

# 3-min talks

The organizers invited me to contribute to "a series of talks in a rapid-learning format with each speaker providing a three minute talk on their work and experience as they relate to the themes of the Assembly".

I [decided](https://twitter.com/EvoMRI/status/855207956899430400) to invite the audience to think about a long-term vision for Open Research Ecosystems, perhaps on the 2030 timescale, as per several ongoing strategy processes (e.g. [National Institute of Dental and Craniofacial Research (NIDCR)](https://nidcr2030.ideascale.com/), [Wikimedia](https://2030.wikimedia.org/), [Gathering for Open Source Hardware (GOSH)](https://openscience.ub.uni-bielefeld.de/1025/how-to-make-open-science-hardware-ubiquitous-by-2025)) and [What we know about the future](https://meta.wikimedia.org/wiki/Template:Strategy/Wikimedia_movement/2017/navbox).

To get things started, I'll be pointing out some things that I am missing in current ways of "Mapping Open Research Ecosystems", for which the following topics are good candidates:
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

# Demo

The organizers also invited suggestions for demos of up to 15 min. I had suggested to demo Wikimedia-based open research workflows, i.e. how Wikimedia platforms can be used to cover a broad range of digital research workflows in a wide array of disciplines (see [here](https://en.m.wikipedia.org/wiki/User:Daniel_Mietchen/Talks/UKSG_2015) for a talk covering part of this topic), but this suggestion was not taken.

# ORCID

I find it interesting that none of the participants has provided their ORCID as the "Link to your work that best fits the Assembly". In any case, mine is [0000-0001-9488-1870](http://orcid.org/0000-0001-9488-1870).

# Notes on the individual sessions

- Editing a file like this (i.e. larger than my screen) is a bit tedious, so my notes on the individual sessions are posted in the [ticket](https://github.com/Daniel-Mietchen/events/issues/8) I opened for this event.

# Contact

[@EvoMRI](https://twitter.com/EvoMRI)

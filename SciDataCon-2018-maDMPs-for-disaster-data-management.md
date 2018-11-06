# About

This file hosts a contribution in form of an oral presentation to SciDataCon 2018 [session 164: Scientific Data Challenges for Sustainable Development](https://www.scidatacon.org/IDW2018/sessions/164/) taking place on Tuesday, 6 November at 16:00–17:30 in room Tsodilo B3. 

See [here](International-Data-Week-2018.md) for my schedule and notes around the event more generally.

# Title

[To what extent can machine-actionable data management plans help automate disaster-related workflows?](https://github.com/Daniel-Mietchen/events/issues/337#issuecomment-400886404)

# Abstract


As highlighted in the session description, disaster reduction and mediation efforts are closely linked to the Sustainable Development Goals and have a broad range of data needs. These data needs include coping with a variety of kinds of data, zero to many resources that provide such data, long-term versus real-time data, data quality issues, the ethics of sharing (or not) and how, management of data-related resources (or the lack thereof) and various degrees of uncertainties around any of this and integration across or zooming in on various aspects thereof.

In this session, I would like to explore some avenues towards a higher degree of automation to address these data needs, focusing on how the concept of a Data Management Plan or the more general notion of an output management plan that has been put forward by the Wellcome Trust can be used to inform policies, workflows and infrastructure around disaster reduction and response. In particular, I will highlight the potential of making such plans machine-actionable, versioned, FAIR and public. This would allow to aggregate, visualize and reslice the information contained in such plans and to use it to interact with disaster-related infrastructure, policies or actors, or as a basis for people, organizations or machines to learn from data gathered about ongoing or past disasters.

For any specific future disaster, many details are of course unknowable at present, but depending on the kind of disaster, certain characteristic data needs are predictable to some extent. Disease outbreaks, for instance, may require different responses based on whether the respective pathogens and their potential modes of transmission are known or not, what their zoonotic potential is, where their host species live, whether the affected animal or human populations have any degree of immunity, whether travel or migration are involved, and so forth. On the basis of initial responses to these questions, decisions can be made as to whether additional information is needed, how to gather it, how to process, aggregate and communicate what is known, how to derive recommendations (e.g. with respect to vaccine campaigns or travel recommendations, or what research to fund), and what the corresponding resource needs are in terms of humans, machines, infrastructure, finances and logistics, where and on what time scales.

Similar questions can be asked for other disaster scenarios like earthquakes, wildfires, storms or oil spills, and information related to such questions already forms the backbone of institutionalized disaster response and prevention mechanisms in many contexts. What is often missing, though, is the interoperability - on both long and short time scales - of such existing mechanisms across actors, jurisdictions, disaster types, or research disciplines. Some pockets of basic interoperability exist in various places, e.g. emergency phone numbers are harmonized within most nations and across EU member states, tsunami warnings can be broadcast nationally or regionally within seconds of an earthquake, and high-speed trains can come to a stop in response. How can we achieve similar harmonization around disaster-related data, repositories, APIs, data models, simulations and related issues, how would that affect humans and machines, and how can we track relevant progress with respect to the Sustainable Development Goals?

# Presentation

This talk will not have slides beyond this page. Instead, I will walk the audience through a set of online resources linked below and comment on them from the perspective of how the concept of data/ output management plans that is popularized in research data contexts can be enhanced by ideas about making those plans machine actionable and then applied in the context of managing disaster-related data:
- Michener WK (2015) Ten Simple Rules for Creating a Good Data Management Plan. PLoS Comput Biol 11(10): e1004525. https://doi.org/10.1371/journal.pcbi.1004525
  - The piece is written with research data management in mind, which we will replace with disaster-related data in our minds for the purpose of this session.
- Miksa, Tomasz, Simms, Stephanie, Mietchen, Daniel, & Jones, Sarah. (2018). Ten principles for machine-actionable data management plans. Zenodo. http://doi.org/10.5281/zenodo.1461713
  - This piece outlines ten principles for making data management plans machine actionable, which we will apply to disaster contexts.
  - See also [RDA poster 7 "Ten principles for machine-actionable data management plans"](https://www.rd-alliance.org/rdas-12th-plenary-poster-session) ([in action](https://twitter.com/GigaScience/status/1059447556684607488)) and RDA breakout session "[Use cases for machine-actionable data management plans](https://www.rd-alliance.org/wg-dmp-common-standards-rda-12th-plenary-meeting)" this morning
- [Data sharing as a new component of addressing and preparing for disease outbreaks](SciDataCon-2018-data-sharing.md)
  - talk given in the session "[Health Databases across the African Continent: What do we have and what do we need for Sustainable Development?](https://www.scidatacon.org/IDW2018/sessions/222/)" earlier this afternoon
  - We will look at some of the examples presented in there from the perspective of generalizing from (past and present) disease outbreaks to (past and present) disasters more generally and how that can inform future data-related activities in disaster contexts.

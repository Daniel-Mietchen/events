# About

This file hosts my session proposal for [PIDapalooza 2018](https://doi.org/10.5438/11.0002). It was submitted on September 22, 2017, which was the extended [submission deadline](https://github.com/Daniel-Mietchen/events/issues/208). On October 11, I was notified that the proposal had been accepted.

# Title

PIDs for policy elements

# Abstract

Policies are a common way to structure interactions amongst humans as well as between humans and human-made systems. In turn, they have a structure to themselves, which may vary considerably across use cases but can generally be broken down into individual policy elements. In this session - which will be presented from https://github.com/Daniel-Mietchen/events/blob/master/PIDapalooza-2018.md - we will entertain the idea of assigning PIDs to such policy elements and explore the effects that might have on 
- exposing policies relevant to a given context, 
- flagging contradictions between policies, 
- building policy-aware workflows, 
- monitoring policy compliance, and 
- standardizing policies across languages, jurisdictions and other use cases.

# Target policies

This session is not specific to any domain, so I'll try to structure it around examples from various areas. For the moment, though, I'll just list here some potential starting points:

- [Mine PMC for ethics statements](https://github.com/Daniel-Mietchen/ideas/issues/499)
- [Sharing policies relevant to NIH](https://github.com/Daniel-Mietchen/events/blob/6ca5731c5ccde9069c5a205e65de83519c8cee49/5th-LEARN-workshop-2017.md#sharing-policies-relevant-to-nih)
- [Annotate some Wellcome policy pages](https://github.com/Daniel-Mietchen/ideas/issues/497)
- Analyze policies for data sharing 
  - in public health emergencies
  - at a single institution/ funder/ publisher
  - across multiple institutions/ funders/ publishers
- subsidiary policies may be a better target for PID tagging than strategic policies (see "Thinking Strategically in Federal Policy: Defining the Attributes of High-level Policies" below)

# Open Knowledge Maps

Since I am new to the topic of analyzing legal language, I am trying to get an overview of how others are doing it, for which I am using [Open Knowledge Maps](https://openknowledgemaps.org/). In order to document my discovery process, I am listing below the queries that I ran, roughly in the order in which I ran them:

- [legal semantics](https://openknowledgemaps.org/map/62309b165ffc2c815d3c11cb6a7b7bff)
- [legal concepts](https://openknowledgemaps.org/map/03c06165413c395e8c56206396bb7b13) (this triggered [a bug report](https://github.com/OpenKnowledgeMaps/project-website/issues/25))
- [mining legal texts](https://openknowledgemaps.org/map/d50e5b7dcad378e706749acb34a5e5a9)
- failed (instead of a results page, they simply lead to this not very helpful [help page](https://openknowledgemaps.org/search?service=base)):
  - A Pattern-Based Method for Identifying and Analyzing Laws
    - The help page does link to [the corresponding BASE search](https://base-search.net/Search/Results?refid=okmaps&type0[]=all&lookfor0[]=A%20Pattern-Based%20Method%20for%20Identifying%20and%20Analyzing%20Laws&type0[]=tit&lookfor0[]=&type0[]=aut&lookfor0[]=&type0[]=subj&lookfor0[]=&type0[]=url&lookfor0[]=&offset=10&ling=0&type0[]=country&lookfor0[]=&daterange=year&yearfrom=1665&yearto=2017&type1[]=doctype&lookfor1[]=121&allrights=all&type2[]=rights&lookfor2[]=CC-*&lookfor2[]=CC-BY&lookfor2[]=CC-BY-SA&lookfor2[]=CC-BY-ND&lookfor2[]=CC-BY-NC&lookfor2[]=CC-BY-NC-SA&lookfor2[]=CC-BY-NC-ND&lookfor2[]=PD&lookfor2[]=CC0&lookfor2[]=PDM&type3[]=access&lookfor3[]=1&lookfor3[]=0&lookfor3[]=2&name=&join=AND&bool0[]=AND&bool1[]=OR&bool2[]=OR&bool3[]=OR&newsearch=1), though, which seems not to be able to make sense of such long strings. Interestingly, [trimming the URL parameters](https://base-search.net/Search/Results?refid=okmaps&type0[]=all&lookfor0[]=A%20Pattern-Based%20Method%20for%20Identifying%20and%20Analyzing%20Laws) does yield useful results. This triggered two bugs reports: [#26](https://github.com/OpenKnowledgeMaps/project-website/issues/26), [#27](https://github.com/OpenKnowledgeMaps/project-website/issues/27).
  - Pattern analysis of laws
  - Pattern analysis laws
- [patterns legal language](https://openknowledgemaps.org/map/0a1e7920cc7601a7e48a065ce38d5646)
- [legal language](https://openknowledgemaps.org/map/30774bcddfbc3190cc009f3bf729d9ec)
- [automated legal texts](https://openknowledgemaps.org/map/ce741215f3c8c582edc81742aec63248)
- [automated analysis legal texts](https://openknowledgemaps.org/map/7866f7063b59fe359bfea5a4bc5254eb)
- [machine policy](https://openknowledgemaps.org/map/3c390d01b4ce35160163cd013e7d9147)
- [machine-readable policy](https://openknowledgemaps.org/map/ba7612335623bbb6167896fe36cdf227)
  - this yielded an interesting hit: [Towards a Similarity Metric for Comparing Machine-Readable Privacy Policies](https://brage.bibsys.no/xmlui/handle/11250/2430174), although it smells of P3P
- machine-actionable policy: failed
- [policy comparison](https://openknowledgemaps.org/map/41675b55fbb2f2768a32ca445e584076)
- ["policy comparison"](https://openknowledgemaps.org/map/417bfba6ac2911614e826c9384611154)
  - hit: [Thinking Strategically in Federal Policy: Defining the Attributes of High-level Policies](hdl.handle.net/1885/108725)
    - I [requested a copy](https://openresearch-repository.anu.edu.au/request-item?handle=1885/108725&bitstream-id=593239)
      - The copy came in with a friendly note by the author, and I thanked him and went through it right away. 
    - Focused on strategic policies as a subtype of policies. Five such policies are considered in detail (Table 1) and characterized in terms of 'attributes' like target audience, implementation incentives or whether they are principles-based.
    - Proposes (Fig. 2)
      - > that those policies that had stronger stakeholder representation during policy formulation tend to deliver policies that are clearer in their objectives
    - Not precisely what I was looking for, but maybe some of the language or references can be useful. For instance, according to his Fig. 1, subsidiary policies may be a better target for PID tagging than strategic policies.

# See also

- [P3P](https://en.wikipedia.org/wiki/P3P)
- [A Pattern-Based Method for Identifying and Analyzing Laws](https://doi.org/10.1007/978-3-642-28714-5_23)
- [SCAPE: creating machine understandable policy from human readable policy](http://openpreservation.org/blog/2013/07/29/scape-creating-machine-understandable-policy-human-readable-policy/)

*[PIDs for policy elements](PIDapalooza-2018.md#title)・[Abstract](PIDapalooza-2018.md#abstract)・[Examples](PIDapalooza-2018.md#examples)・[Notes](PIDapalooza-2018.md#notes-in-drafting)・[See also](PIDapalooza-2018.md#see-also)・[About](PIDapalooza-2018.md#about)*

[![Hammurabi's code](https://upload.wikimedia.org/wikipedia/commons/1/18/CodeDeHammurabiLouvre3.jpg)](https://commons.wikimedia.org/wiki/File:CodeDeHammurabiLouvre3.jpg) Detail of [Hammurabi's code](https://www.wikidata.org/wiki/Q93304). Image: [Claude Valette](https://commons.wikimedia.org/w/index.php?title=File:CodeDeHammurabiLouvre3.jpg&oldid=173500581), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). 


# Title

PIDs for policy elements

# Abstract

Policies are a common way to structure interactions amongst humans as well as between humans and human-made systems. In turn, they have a structure to themselves, which may vary considerably across use cases but can generally be broken down into individual policy elements, similar to [ingredients within a recipe](http://tinyurl.com/gqbmzlp). In this session - which will be presented from https://github.com/Daniel-Mietchen/events/blob/master/PIDapalooza-2018.md - we will entertain the idea of assigning PIDs to such policy elements and explore the effects that might have on 
- exposing policies relevant to a given context, 
- flagging contradictions between policies, 
- building [policy-aware automated workflows](http://openpreservation.org/blog/2013/07/29/scape-creating-machine-understandable-policy-human-readable-policy/), e.g. around [machine-actionable Data Management Plans](https://doi.org/10.3897/rio.3.e13086)
- monitoring policy compliance, and 
- [standardizing policies](https://sparcopen.org/policy-harmonization-statement/) across languages, jurisdictions and other use cases.

# Examples

## Hammurabi's Code

* [Wikidata entry with lots of PIDs](https://www.wikidata.org/wiki/Q93304)
* [Translation](https://en.wikisource.org/wiki/The_Code_of_Hammurabi_(Harper_translation))
* [commentary](https://www.farnamstreetblog.com/2017/11/hammurabis-code/)

## Data sharing policies

Let's consider data sharing policies, which are increasingly being drafted and implemented by a range of players in the research landscape, including research institutions, research funders, research publishers, learned societies and others.

Some key elements of policies in this space could be, e.g. 
- whether there is an embargo period before data can be shared openly, 
  - and if so,
    - whether it 
      - is 
        - optional
        - required
      - has
        - conditions
    - what data it applies to,
    - when it starts and 
    - when it ends, or 
- whether there are licensing requirements, 
  - and if so, 
    - whether they apply to data and/ or metadata
    - which licenses fulfill them
- whether there are any consequences for non-compliance,
  - and if so,
    - which ones.

Now imagine these policy elements to be available and addressable in a format that machines can act on, i.e. using a consistent predefined structure and a controlled vocabulary linked to persistent identifiers.

If we can do this [for cocktails](http://tinyurl.com/gqbmzlp), why not for policies?

## Technical approaches to automated handling of policy elements

* [Creating a Policy-Aware Web](https://www.wikidata.org/wiki/Q55693431)
* [Platform for Privacy Preferences Project (P3P)](https://en.wikipedia.org/wiki/P3P)
* [eXtensible Access Control Markup Language (XACML)](https://en.wikipedia.org/wiki/XACML)
* [Routing Policy Specification Language (RPSL)](https://en.wikipedia.org/wiki/Routing_Policy_Specification_Language)
* [InSpec](https://inspec.io/)
* [Policy Models](http://datatagginglibrary.readthedocs.io/en/latest/)
* [Shape Expressions (ShEx)](https://www.w3.org/2001/sw/wiki/ShEx)


# Notes in drafting

## Target policies

This session is not specific to any domain, so I'll try to structure it around examples from various areas. For the moment, though, I'll just list here some potential starting points:

- [Mine PMC for ethics statements](https://github.com/Daniel-Mietchen/ideas/issues/499)
- [Sharing policies relevant to NIH](https://github.com/Daniel-Mietchen/events/blob/6ca5731c5ccde9069c5a205e65de83519c8cee49/5th-LEARN-workshop-2017.md#sharing-policies-relevant-to-nih)
- [Annotate some Wellcome policy pages](https://github.com/Daniel-Mietchen/ideas/issues/497)
- Analyze policies for data sharing 
  - in public health emergencies
  - at a single institution/ funder/ publisher
  - across multiple institutions/ funders/ publishers
- or go for laws directly?
  - e.g. [safety belt laws in the US](http://www.iihs.org/iihs/topics/laws/safetybeltuse)
- [WMA Declaration of Helsinki – Ethical Principles for Medical Research Involving Human Subjects](https://www.wma.net/what-we-do/medical-ethics/declaration-of-helsinki/)
  - [related policy frameworks](https://www.wma.net/what-we-do/medical-ethics/declaration-of-helsinki/)
- subsidiary policies may be a better initial target for PID tagging than strategic policies (see "Thinking Strategically in Federal Policy: Defining the Attributes of High-level Policies" below)
- Hammurabi's code

## Open Knowledge Maps

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
  - this yielded an interesting hit: [Towards a Similarity Metric for Comparing Machine-Readable Privacy Policies](https://brage.bibsys.no/xmlui/handle/11250/2430174), although it smells of [P3P](https://en.wikipedia.org/wiki/P3P)
    - on P3P: 
      - > We do not consider particular privacy policy languages (such as P3P [9], PPL [10] or XACML [11]), but focus on the high-level concepts that need to be solved rather than the particular language dependent problems.
        - [Wikipedia article on XACML](https://en.wikipedia.org/wiki/XACML)
  - similar machine-directed policy language: 
    - [Routing Policy Specification Language](https://en.wikipedia.org/wiki/Routing_Policy_Specification_Language)
- machine-actionable policy: failed
- [policy comparison](https://openknowledgemaps.org/map/41675b55fbb2f2768a32ca445e584076)
- ["policy comparison"](https://openknowledgemaps.org/map/417bfba6ac2911614e826c9384611154)
  - hit: [Thinking Strategically in Federal Policy: Defining the Attributes of High-level Policies](https://hdl.handle.net/1885/108725)
    - I [requested a copy](https://openresearch-repository.anu.edu.au/request-item?handle=1885/108725&bitstream-id=593239)
      - The copy came in with a friendly note by the author, and I thanked him and went through it right away. 
    - Focused on strategic policies as a subtype of policies. Five such policies are considered in detail (Table 1) and characterized in terms of 'attributes' like target audience, implementation incentives or whether they are principles-based.
    - Proposes (Fig. 2)
      - > that those policies that had stronger stakeholder representation during policy formulation tend to deliver policies that are clearer in their objectives
        - author is conscious that 5 is a very small number to make such inferences
        - plausible in general (except when stakeholder representation is biased towards lobbyists whose interventions tend to make policies more vague) but information about 'stakeholder representation during policy formulation' is not necessarily easily available in or near a given policy text, so it's hard to include into workflows for identifying policies suitable for PID tagging of policy elements
    - Not precisely what I was looking for, but maybe some of the language or references can be useful. For instance, according to his Fig. 1, subsidiary policies may be a better initial target for PID tagging than strategic policies.
- zooming in on ethics
  - [ethics standards](https://openknowledgemaps.org/map/6a0cc6e9cb06d626cf1723873c38bf0e)
    - hit: [A conceptual analysis of ethics codes](http://hdl.handle.net/10806/5300) (abstract only)
  - [ethics forms](https://openknowledgemaps.org/map/f4654b277ceb612efa6f9c02e2169b99)
  - [ethics policies](https://openknowledgemaps.org/map/5b8774e66c95bd6c137b4e2326027513)
  - [ethical review](https://openknowledgemaps.org/map/31d8134696a409b5f6fb7a6697ae9b60)
- [information retrieval legal documents](https://openknowledgemaps.org/map/946ea0e9ac2cee8677b13ce0b5b84822)
- [legal information retrieval](https://openknowledgemaps.org/map/43bca81ffa28c72f3c4c631e3f6ea416)
- [automated analysis legal documents](https://openknowledgemaps.org/map/5637dfea7a169dbce705adeb732bc45b)
- "legal automated analysis" endlessly remains in "Creating your visualization takes longer than expected. Please stay tuned!" mode
- [legal semantic reasoning](https://openknowledgemaps.org/map/1988116b632949e70493ecbaf670da8f)
- [automated legal analysis](https://openknowledgemaps.org/map/d61028a8c11f63bb63a0fffa11a59fe9)
- [comparative law](https://openknowledgemaps.org/map/e7d256a5c54d8936023309554456f11e)
- [comparative legal studies](https://openknowledgemaps.org/map/5db88a2425423fc06d33744ff316e1eb)
- [automated comparative law](https://openknowledgemaps.org/map/0733501919bcf901fa35bb679e62aaa3)
- [law similarity](https://openknowledgemaps.org/map/b7e3c9188622c6376ada1f90cf05203a)
- [comparative international law](https://openknowledgemaps.org/map/8019614dd5a625c6a72ce80e4c85aaf7)

## Scholia

- [comparative law](https://tools.wmflabs.org/scholia/topic/Q741338)
- [international law](https://tools.wmflabs.org/scholia/topic/Q4394526)


# See also

- Wikipedia: [Comparative law](https://en.wikipedia.org/wiki/Comparative_law)
- [A Pattern-Based Method for Identifying and Analyzing Laws](https://doi.org/10.1007/978-3-642-28714-5_23)
- [Scalable Preservation Environments (SCAPE)](http://scape-project.eu/)
  - [Data policy as activity network](https://epubs.stfc.ac.uk/work/35227831)
  - [SCAPE: creating machine understandable policy from human readable policy](http://openpreservation.org/blog/2013/07/29/scape-creating-machine-understandable-policy-human-readable-policy/)
- [The Constitute Project](http://library.law.virginia.edu/ajm-blog/2015/02/26/the-constitute-project/)
  - comparative database of constitutions around the world, with SPARQL endpoint
- [Law StackExchange](https://law.stackexchange.com/search?q=policies) (does not look promising so far; maybe ask)
  - [Practicing European Law in English language](https://law.stackexchange.com/questions/19835/practicing-european-law-in-english-language)
    - > working on "legal automation software (question answering, automatic strategy inferrence, automatic argumentation, search of case law etc.)"
- [Academia StackExchange](https://academia.stackexchange.com/search?q=policies) (does not look promising so far; maybe [ask](https://law.stackexchange.com/questions/ask))
- [Challenges in Swedish hydropower – politics, economics and rights](https://doi.org/10.3897/rio.3.e21305)
  - plans to analyze the effect of two different water management policies
  - uses 
    - > "the Policy Arrangements Approach (PAA) to map and analyse the arrangements in which hydropower permit processes take place, focusing on four dimensions: rules, actors, resources/power, and discourses (van Tatenhove et al. 2000)."
- [Michael Bar-Sinai on Policy models](https://privacytools.seas.harvard.edu/blog/michael-bar-sinai-presents-policymodels-demo-force2017)
- [Data Tags](https://datatags.org/)
- [Key Elements of an Information Security Policy](http://resources.infosecinstitute.com/key-elements-information-security-policy/)
- [Open Contracting Data Standard](http://standard.open-contracting.org/latest/en/)
  - see also the [corresponding PIDapalooza talk](https://pidapalooza18.sched.com/event/Cwmc/uniquely-identifying-organisations-and-people-in-anti-corruption-contexts)
- In [omegataupodcast.net/264](http://omegataupodcast.net/264-blockchains-und-smart-contracts/) the [two](https://wwwmatthes.in.tum.de/pages/b6w19wt08gen/Ulrich-Gallersdoerfer) [interviewees](https://wwwmatthes.in.tum.de/pages/88bkmvw6y7gx/Prof.-Dr.-Florian-Matthes) mention a co-op between law & IT faculty (at TU Munich?). They might be interesting people to talk to or ask for more specialised contacts.
- [Research Funders' Open Access Policies](http://v2.sherpa.ac.uk/juliet/)
- [RDA: Practical Policy WG](https://rd-alliance.org/groups/practical-policy-wg.html)
- [ISA^2 &mdash; Interoperability solutions for public administrations, businesses and citizens](https://ec.europa.eu/isa2/home_en)

# About

This file hosts my session proposal for [PIDapalooza 2018](https://doi.org/10.5438/11.0002). It was submitted on September 22, 2017, which was the extended [submission deadline](https://github.com/Daniel-Mietchen/events/issues/208). On October 11, I was notified that the proposal had been accepted. The session took place [at 2pm CET on January 24](https://pidapalooza18.sched.com/event/Cwn9/pids-for-policyyeah-like-putting-ids-on-individual-elements-within-policiescool-righto) on [Stage 2](https://pidapalooza18.sched.com/venue/Stage+2).

# About

This file hosts materials related to my participation in the ASAPbio Design Sprint [Encouraging Preprint Curation and Review](http://web.archive.org/web/20201023035646/https://asapbio.org/sprint) in November-December 2020.

# Project proposal template
*Based on the [ASAPbio Preprint Sprint Proposal Template](http://web.archive.org/web/20201020184303/https://docs.google.com/document/d/1JzMXnSk9W7W0k02MdTV2BqYhja1v6VVQ1kSk63hECpM/edit)*, which is to be submitted by 3 November 2020.

## Title

Preprint review and curation by content type

## Organizer

* Daniel Mietchen, School of Data Science, University of Virginia, [@EvoMRI](https://twitter.com/EvoMRI)

## Project status

ongoing

## Project duration

ongoing

## Project aims
### Background

Preprints may include - or be accompanied by - a variety of materials, possibly in various file formats and locations. 
Curation of preprints has to take into account the submitted files and any associated materials, as well as appropriate metadata.

Peer review of preprints typically has two main components (a) general comments on parameters like the quality, scope, topicality or structure of the manuscript and (b) comments on details, e.g. inaccuracies, missing references, confusing plot parameters, unsubstantiated claims, typos. The general part is usually a synthesis that is best expressed in a new piece of text. Claims in this text are frequently substantiated with examples from the details part, though rarely in a click-through manner.

### Overview of the challenge to overcome

Reviewing or curating the materials associated with preprints poses challenges that can and do vary as a function of parameters like their kind, format or location.
For instance, if the preprint (i) is publicly available online in HTML format, (ii) is not versioned, (iii) does not contain non-textual elements like figures, tables, equations, code snippets or external identifiers and (iv) does not depend on things like software or data located elsewhere, then it can be reviewed by simply posting web annotations by means of a tool like Hypothesis ([example](https://via.hypothes.is/https://wellcomeopenresearch.org/articles/2-63/v1)). If any of these conditions are not met, then the review and/or curation workflows may require modification, particularly for the detailed comments. Some of these modifications can be simple (e.g. just mentioning the preprint's version ID in the review report can be enough to address the versioning problem), others may be more complex, e.g. reviewing software typically requires installing and running it, which may by complicated by dependencies or incompatibilities with respect to external software or data.

### The ideal outcome or output of the project

Some best practice recommendations for preprint review and curation by content type, along with examples and validation tools that are contextualized from the perspective of these recommendations.

## Overview
### Description of the intervention

Initially once: analysis of a random subset of preprints &mdash; ideally from a range of platforms &mdash; in terms of their non-textual components as well as the file formats and locations of associated materials.
Ideally, such an analysis would be performed automatically on a daily basis thereafter, for all preprints meeting certain criteria.

### Plan for monitoring project outcome

There are several milestones for the project to reach, in an iterative fashion
- identification of the initial test corpus
- identification of the initial set of criteria for analyzing the test corpus
- identification of best practice examples (perhaps with further improvements) with respect to these criteria
- distillation of the analysis into best practice recommendations
- distillation of the recommendations into validation tools, badge system and dashboard
- testing, documentation and training regarding the above

## What’s needed for success
### Additional technology development

- Development of validation tools that can check  &mdash; individually or in bulk &mdash; preprints or possibly also published articles for compliance with the recommendations.
- Development of the technical components of a badge system that signals compliance with the recommendations at the level of individual preprints and perhaps platforms or other units of organization (e.g. journals).
- Development of a dashboard to monitor adoption of the recommendations across the preprint landscape.
- Tools assisting with the discovery, review and curation of specific content types.

### Feedback, beta testing, collaboration, endorsement

- Collaborative development of the best practice recommendations and suitable examples.
- Development and testing of the validation and badge systems.
- Development and testing of mechanisms to discover, review and curate specific content types.
- Documentation and training materials for authors and reviewers of preprints as well as operators of preprint platforms or other stakeholders.

### Funding

- To move any of the above forward.

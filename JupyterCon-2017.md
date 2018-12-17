**[Watch the video](https://www.youtube.com/watch?v=Via7gBrjxHI)**

# About

This file hosts a submission on [rerunning Jupyter notebooks from PMC](https://github.com/sparcopen/open-research-doathon/issues/25) for [JupyterCon](https://conferences.oreilly.com/jupyter/jup-ny), to be held in New York on August 23-25, 2017 (see my [notes](https://github.com/Daniel-Mietchen/events/issues/19) on the event)). The deadline for submitting talks was March 14, 2017, 11:59pm Eastern Daylight Time, and I received confirmation of my submission at 11:49pm EDT that day. On April 13, I was informed that notifications of acceptance or rejection would be sent out "between now and next week (the week of April 17)." On April 22, I received notification that the talk had been selected, and I accepted the offer to present. The talk is now scheduled for 4:10pm - 4:50pm EDT (40 minutes) on August 25 in Murray Hill (see also [its entry in the program](https://conferences.oreilly.com/jupyter/jup-ny/public/schedule/detail/60126)).

Like the rest of the project, this was a collaborative effort. Special thanks go to [Tom Pollard](https://github.com/tompollard) for help with the [submission](#submission).

# Outline of the talk

## Timing

The slot is 40 min, so I'll be aiming for something like 25-30 min of presentation and 15-10 min of Q & A.

## Title

Post-publication peer review of Jupyter Notebooks referenced in articles on PubMed Central

## Definitions

- [post-publication peer review](https://en.wikipedia.org/w/index.php?title=Scholarly_peer_review&oldid=795877776#Pre-_and_post-publication): assessment of scholarly work once it is public
  - is a major mode of research communication, but often not done in public
- [Jupyter notebook](http://jupyter.org/): an interactive document with code, data and text embedded
  - [“To a non-coder, a Jupyter notebook is an interactive data document that happens to have some code in it”](https://twitter.com/carlystrasser/status/900793446176366592)
- [PubMed Central](https://www.ncbi.nlm.nih.gov/pmc/): the largest public full-text repository of biomedical research (> 4 million articles)

## Premises & comments on previous talks

- [Fernando: From interactive Python to open science](https://www.oreilly.com/ideas/project-jupyter-from-interactive-python-to-open-science)
  - I'm coming from the other end
- ["Science is about opening up the black box of nature; we shouldn't be doing that with things which themselves we are not legally allowed to understand"](https://www.youtube.com/watch?v=xuNj5paMuow#t=5m13s)
  - also applies to things where we have legal permission but technical barriers
- Jupyter notebooks
  - can be used to share analytical workflows
    - ["Jupyter as a conversational medium in science enabling reproducibility"](https://twitter.com/jiffyclub/status/901078588090454016) (see also [earlier presentation by Zach Seiler](https://github.com/Daniel-Mietchen/events/issues/19#issuecomment-324832640) who [demoed it](https://github.com/Zsailer/jupytercon-reproducible-notebooks))
    - in data journalism (see [earlier presentation by Karlijn Willems](https://github.com/Daniel-Mietchen/events/issues/19#issuecomment-324845042))
  - can provide a great learning experiences (["killer app for education"](https://twitter.com/lee_stott/status/901074238400065536))
    - [when they actually run](https://twitter.com/mpbruchez/status/901078147545935873)
  - have begun to be shared along with scholarly publications
    - > ["Drawing a complete list of all mentions of Jupyter notebooks in the Astrophysics Data System, we identified 91 relevant publications."](https://doi.org/10.1109/JCDL.2017.7991618)
      - but the practices for citing them are still evolving (see [earlier presentation by Bernie Randles et al.](https://github.com/Daniel-Mietchen/events/issues/19#issuecomment-324956004))
    - similar number in PubMed Central at the time
  - have begun to be shared on Wikimedia platforms
    - [Wikipedia](https://en.wikipedia.org/w/index.php?title=Lambert_series&oldid=744731728#cite_note-1)
    - [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Parameter_estimation_process_infinite_Gaussian_mixture_model.webm)
    - ["Data science is a critical skill for today's engaged citizen."](https://twitter.com/rosiepongracz/status/900744763422494720) ([Fernando](https://twitter.com/rroumeliotis/status/900722216748417024))
- ["reproducibility is not a one-click solution"](https://twitter.com/LorenaABarba/status/901081360235999232)
  - computational reproducibility should be, and Lorena alluded to it in her [reference to Jon F. Claerbout](https://speakerdeck.com/labarba/design-for-reproducibility?slide=2)
  - research reproducibility is a conversation indeed

## Inspiration

- [try.jupyter.org/](https://try.jupyter.org/)
  - works, but examples are not relevant to me
- [notebooks shared with papers](https://www.ncbi.nlm.nih.gov/pmc/?term=ipynb+OR+jupyter+OR+ipython)
  - relevant to me but they often don't work
- [Schematron validation of XML trees](http://jats4r.org/tools)

## Hackathon project

- [Analyze all Jupyter notebooks mentioned in PubMed Central](https://github.com/sparcopen/open-research-doathon/issues/25)
  - initial focus on Python, with broader scope in mind

## Observations

- [initial write-up](https://markwoodbridge.com/2017/03/05/jupyter-reproducible-science.html)
- Jupyter notebooks 
  - provide great learning experiences when they actually run
  - need to be shared in a more standardized fashion to allow reuse
  - can trigger frustration or additional learning experiences when they do not run
  - are growing in popularity on PMC

## Early prototypes for notebook verification

- [automated verification of a given Jupyter notebook](https://gitlab.com/mwoodbri/jupyter-ci/tree/master) (by [Mark Woodbridge](https://github.com/mrw34))
- [automated verification of the notebooks from our initial spreadsheet](http://paws-public.wmflabs.org/paws-public/995/WikiCite%20notebook%20validator.ipynb) (by [Laurentius](https://it.wikipedia.org/wiki/Utente:Laurentius))
- [web app to auto
notebooks mentioned in a list of papers](https://github.com/sparcopen/open-research-doathon/issues/25#issuecomment-324954665) (by [Alexander Pashuk](https://github.com/alexanderpashuk) and [Roman Gurinovich](https://github.com/RomanGurinovich))
  - [sample report](http://exe.sci.ai/results/d121f868-e73c-44c7-8ea9-f6140125fa06) based on
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5322252/
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4965465/
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5395614/

## Discussion

- terminology around rep\*bility
- lots of similar initiatives (see [comments in original thread](https://github.com/sparcopen/open-research-doathon/issues/25#issuecomment-285392746)) but little coordination


## Recommendations

- see [original write-up](https://markwoodbridge.com/2017/03/05/jupyter-reproducible-science.html)
- cite/ mention notebooks in a standardized fashion
  - > ["We identified eight ways in which scientists mentioned the Jupyter notebooks and five ways in which they provided access, only some of which appeared to facilitate open science. Of the 91 papers, 37 linked to openly accessible Jupyter notebooks containing detailed research procedures, associated code, analytical methods, and results. Another 54 papers mentioned a Jupyter notebook in the text, but did not provide access to one. Practices for mentioning, storing, and providing access to the notebooks varied greatly across papers."](https://doi.org/10.1109/JCDL.2017.7991618)
    - some additional modes:
      - [Figure only](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5014984/figure/figure1/)
      - [PDF in supplement](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5082134/#__ackidm140116235021904title)
- make all dependencies explicit and machine actionable (starting with [requirements.txt](https://github.com/sciAI/exe/blob/master/requirements.txt))
  - libraries in the notebook's main language
  - libraries in other languages
  - datasets required by the code
  - dependencies for all of the above
  - [note of caution](https://github.com/sparcopen/open-research-doathon/issues/25#issuecomment-288946423)
- share in self-contained environment
- ...

## Open questions

- multiple
  - to what extent can we reuse existing infrastructure for the purpose of 
    - validating a given notebook?
      - its containerized version?
  - what standards exist or are emerging in terms of best practices for 
    - mentioning notebooks
    - citing notebooks
    - expressing dependencies
    - documenting when a validation was run, and by whom
      - e.g. 
        - before submission of the paper (perhaps by author)
        - during review (perhaps by reviewer)
        - upon publication of the paper (perhaps by journal)
      

## Outlook

- research
- Wikimedia
- offline
  - [Kolibri](https://learningequality.org/kolibri/)
- data journalism
  - [Buzzfeed example](https://github.com/BuzzFeedNews/2017-08-partisan-sites-and-facebook-pages)
- looking for partners to pilot potential solutions
  
## Contact

- comment in the [original thread](https://github.com/sparcopen/open-research-doathon/issues/25)
- Twitter: [EvoMRI](https://twitter.com/EvoMRI)
- email: daniel.mietchen AT virginia DOT edu

# Submission

Below the horizontal line is a copy of the submission form, with my responses filled in as blockquotes. The form used a non-markdown way of markup, which is preserved in the way the hyperlinks are given.

In the "key takeaways" section, I went for just three, omitting the following two:

> Research institutions and publishers should establish workflows for verifying Notebooks in a standardized fashion. We are looking into possible approaches to do this. 

> Researchers and others using Jupyter Notebooks to document their workflows should make use of such verification environments routinely. 

I listed only myself as a speaker, since they were asking for email, bio and pic.

---

Submitting a proposal is a two stage process. First, enter the proposal details on this page. Because the first round will be a blind review, please do not include your name, affiliation, or any other identifying information in the title, description, or abstract of your proposal.

After submitting these, you will then be asked to input the speaker details.

Note: You will be logged out after 6 hours so please save your proposal locally if you need extra time.

Proposal title*

> Post-publication peer review of Jupyter Notebooks referenced in articles on PubMed Central

Description* (brief overview for marketing purposes, max. length 400 characters—about 65 words)

> Jupyter Notebooks are a popular option for sharing data science workflows. We sought to explore best practices in this regard and chose to analyze Jupyter Notebooks referenced in PubMed Central in terms of their reproducibility and other aspects of usability (e.g. documentation, ease of reuse). The project started at a hackathon earlier this month, is still ongoing and documented on GitHub.

Characters remaining: 400

Topic (Please choose the one topic most relevant to your proposal) \*

- Core architecture
- Jupyter subprojects
- Usage and application
- JupyterHub deployments

> Reproducible research and open science

- Development and community
- Documentation
- Kernels
- Extensions and customization

Session type*

> 40-minute session

Abstract* (Longer, more detailed description of your presentation to help the program committee understand what you will cover. If your proposal is chosen, this is the description that will appear on the website. Note that our copywriters may edit it for consistency and O'Reilly voice.)
read formatting help


> Jupyter Notebooks are a popular option for sharing data science workflows.
> 
> We sought to explore best practices for sharing reproducible research studies, focusing on the Jupyter Notebooks that had been referenced in published research articles. Our analysis reviewed aspects of reproducibility and usability, covering areas like quality of documentation, licensing, and ease of reuse. 
> 
> Our aim was to understand and document the extent to which these publicly accessible Notebooks are reproducible, both individually and collectively. By identifying the existing barriers to reproducibility, our hope is to lower those barriers for Notebooks shared in the future. 
> 
> To find research articles with associated Jupyter Notebooks, we performed a search for "ipynb OR Jupyter" on PubMed Central, a full-text database of biomedical articles. This yielded approximately 100 articles, which were then screened for mentions of actual Notebooks. 
> 
> The association of articles with Notebooks took multiple forms, such as screenshots, supplementary files, links to nbviewer, GitHub repositories and individual Notebooks on GitHub. For those Notebooks that were available in an executable form, we executed them in a clean Jupyter environment.
> 
> When executing Notebooks, we recorded whether they ran through without any errors, and the first error message if there was one. Subsequently, we looked at individual errors and tried to resolve them. Most frequently, this involved fixing code and data dependencies. Lack of documentation was often a barrier to reproducibility, as was code that was dependent on the platform (e.g. shell commands) and use of non-Python software packages (e.g. Java).
> 
> Our next step is to analyze the remaining errors, on the basis of which we are deducing recommendations on how they could be avoided. In addition, for those Notebooks that we manage to execute, we are documenting whether the results match the ones originally reported in the associated papers. 
> 
> Some Notebooks are provided along with a containerized version, usually through Docker. In such cases, we are taking an approach similar to analyzing the Notebooks themselves: attempting to build the container from scratch, run it and document problems encountered on the way, as well as attempts to solve them.
> 
> The project is a collaborative effort, still ongoing and documented in an open-science manner "on GitHub":(https://github.com/sparcopen/open-research-doathon/issues/25), as is "this submission":(https://github.com/Daniel-Mietchen/events/blob/master/JupyterCon-2017.md). I would like to thank everyone who has contributed so far.

Suggested secondary topic(s)

Please suggest up to 3 secondary topics, separated by a comma, that will best represent your proposal.
Who is this presentation for? *

> Notebook validation, publishing, education

(Job titles/functions and/or experience, for instance)

> researchers, data librarians, reviewers, publishers and research administrators

Audience level *

> Intermediate

What's the takeaway for the audience? *

Main ideas and/or skills attendees will learn from your presentation

> Efforts are needed to improve and standardize the way Jupyter Notebooks and associated containers are shared along with published research articles.

> Mechanisms (e.g. badges) should be explored to signal whether a given Notebook has passed such a standardized procedure. 

> Reviewers of research involving Jupyter Notebooks should be made aware of the reusability issues outlined here.


Prerequisite knowledge for this presentation *

This information is crucial for attendees. Please describe what skills and knowledge attendees need to have in order to get the most from your talk.

> We expect attendees to have some basic familiarity with Jupyter Notebooks and with the concept and practicalities of reproducibility in research.

Is this session more conceptual or how-to? *

> How-to

Application area

(i.e. science, education, industry, etc.)

> research, education

Tutorial hardware and/or installation requirements for attendees

If you are submitting a proposal for a 3-hour tutorial, what materials or downloads will attendees need in advance of your tutorial (e.g., a GitHub account, most current version of MySQL, a laptop, etc.)?

> N/A

Please let us know if you have any special equipment needs for your presentation.

(Note: Each presentation room will have a podium, projector, 16:9 screen, head table, microphone, ethernet connection for speaker, and wifi.)

> N/A

Video URL

While not compulsory, we strongly encourage you to provide at least one video clip of the speaker. If you don’t have video of the speaker in action at an event, please create a very short clip (2-3 minutes, see examples) proposing the session. We don’t care about the quality of the video; we care about the quality of the speakers. If your video isn’t already online, post it to a third-party site (YouTube is fine), and then share the link with us.

> https://github.com/Daniel-Mietchen/events/blob/master/recordings.md 

O'Reilly Author

If you are an author or content contributor at O’Reilly, please fill in the name of your main O’Reilly editorial contact.

> N/A

Did someone recommend or encourage you to submit a proposal?
If so, please let us know who sent you:

> N/A

Diversity *

Diversity is one of the factors we seriously consider when reviewing proposals as we seek to broaden our speaker roster.

Does your presentation have the participation of a woman, person of color, person with disabilities, or member of another group often underrepresented at tech conferences?

> No

Travel & other expense reimbursements *

If your proposal is chosen, would you need assistance with hotel or travel related expenses (for example, because you are self-employed)? Please note: Your answer to this question will have no impact on the committee’s review of your proposal.

> Yes.

If so, please describe.

> This is a spare time project, and I do not have any funding for attending JupyterCon at the moment, though I might be able to arrange for accommodation. If the submission is accepted, it would thus be helpful if you could assist with covering my return flight from Germany (ca. USD 800). If this is not possible, a fallback option would be to make use of the collaborative nature of the project and send someone for whom travel costs would be lower. One of the contributors - Tom Pollard, who is based in Boston - has signaled his availability for that.

Additional notes

Any other information you would like the program committee and/or conference organizers to know?
Code of Conduct

All participants, including speakers and presenters, must follow our Code of Conduct, the core of which is this: JupyterCon should be a safe and productive environment for everyone.

By submitting a proposal, I (and any other presenters included in this speaking proposal) agree to follow the [conference Code of Conduct](https://conferences.oreilly.com/jupyter/jup-ny/public/content/conduct). Read more »

You must now add one or more speakers before you can submit this proposal.


Add speaker 

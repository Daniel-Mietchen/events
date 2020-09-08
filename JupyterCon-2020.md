# About

This file hosts a proposal to [JupyterCon 2020](https://jupytercon.com/), which I [submitted](https://twitter.com/EvoMRI/status/1285746449846870016) on 21 July 2020. On August 22, I was notified of its acceptance. They requested confirmation that I still plan to give the talk, which I provided. On September 4, they sent me detailed instructions regarding how to do and submit the recordings of the talk by mid-September, for which there is now a [dedicated ticket](https://github.com/Daniel-Mietchen/events/issues/699).

# Form fields

The submission form has a number of fields. I will document my responses to the non-personal ones below.

## Title

* Jupyter in the Wikimedia ecosystem

## Audience level

* I chose "Novice" since the options were "Novice/ Intermediate/ Expert"

## Brief summary

*Short paragraph, maximum 400 characters. If your proposal is accepted, this will be in the public program.*

Jupyter interacts in various ways with Wikipedia and its sister sites. It forms the subject of some wiki pages, while Jupyter notebooks serve as references in others, help generate illustrations, assist in wiki editing or serve educational or testing purposes, and a JupyterHub facilitates such activities. This talk will look into how such interactions can be strengthened further to mutual benefit.

## Outline

*This is a self-contained statement that summarizes the objective of the proposal, its outline, central thesis, and key takeaways. After reading the description, the audience should have an idea of the overall presentation and what they will learn. The description should also make clear what background knowledge is expected from the attendees. Include links to relevant source code, articles, videos, or other information that add context to your proposal.*

This presentation is intended to (i) make the Jupyter community more familiar with current and potential usages of Jupyter in Wikimedia contexts, (ii) explore how Jupyter resources can become more findable and accessible by leveraging the reach of Wikimedia projects. It will be given based on https://github.com/Daniel-Mietchen/events/blob/master/JupyterCon-2020.md and does not assume any background knowledge other than a basic familiarity with Jupyter.

After a brief introduction to Wikimedia projects - which include Wikipedia, Wikimedia Commons and Wikidata and similar collaborative sites - we will explore existing usage examples of Jupyter in Wikimedia contexts. Based on the assumption that the two communities are mission-aligned and would benefit from closer interaction, we will then consider potential usage examples based on overlaps in mission and activity of the Jupyter and Wikimedia communities.

In closing, developers and maintainers of Jupyter-based educational materials or Jupyter-related functionality shall be stimulated to consider whether and how such materials or functionality might fit into the Wikimedia ecosystem, or, conversely, how they can leverage Wikimedia resources for educational and related purposes.


## Affiliation 

*For the purpose of this talk.*

* School of Data Science, University of Virginia, USA

## Past experience and any other information you would like the reviewers to know.

*If you have given a talk or poster before, feel free to include links to slides or videos.*

I briefly hinted at some aspects of the interaction between Wikimedia and Jupyter in my 2017 JupyterCon talk - see https://www.youtube.com/watch?v=Via7gBrjxHI#t=4m55s .
For other recordings of talks I gave, see https://github.com/Daniel-Mietchen/events/blob/master/recordings.md .

## Is this your first time presenting at JupyterCon? 

* No.

# Reviewer comments

* "Make sure the presentation has live demos of these current usages and previews of the potential ones."
* explain benefits and downsides (ideally for both sides) of linking from Wikipedia to the Jupyter ecosystem and back

# Notes

* Precursor presentation at WikiCite 2017: [Jupyter notebooks on Wikimedia sites](https://meta.wikimedia.org/wiki/WikiCite_2017/Jupyter_notebooks_on_Wikimedia_sites)
* Jupyter notebooks to increase replicability of research studies, including about Wikimedia projects like Wikidata
  - example:
    - paper: [Commonsense Knowledge in Wikidata](https://arxiv.org/abs/2008.08114)
    - [notebooks](https://github.com/usc-isi-i2/cskg/tree/master/wikidata)
* Usage examples
  * [quick search](https://www.google.com/search?q=%28site%3Awikipedia.org+OR+site%3Awikivoyage.org+OR+site%3Awikimedia.org+OR+site%3Amediawiki.org+OR+site%3Awikitech.org+OR+site%3Awikisource.org+OR+site%3Awikiquote.org+OR+site%3Awikinews.org+OR+site%3Awikidata.org%29+AND+%28nbviewer+OR+mybinder+OR+jupyter+OR+ipython%29)
  * Wiki pages about Jupyter
    * Wikipedia
      * [site search](https://www.google.com/search?q=site%3Awikipedia.org+jupyter)
      * English
        * Project Jupyter
        * Jupyter notebook
        * JupyterHub
        * [Binder Project](https://en.wikipedia.org/wiki/Binder_Project)
      * many other languages
    * [Wikimedia Commons](https://commons.wikimedia.org/w/index.php?cirrusUserTesting=mediasearch_commons_int&sort=relevance&search=Jupyter&title=Special:Search&profile=advanced&fulltext=1&advancedSearch-current=%7B%7D&ns0=1&ns1=1&ns2=1&ns3=1&ns4=1&ns5=1&ns6=1&ns7=1&ns8=1&ns9=1&ns10=1&ns11=1&ns12=1&ns13=1&ns14=1&ns15=1&ns100=1&ns101=1&ns102=1&ns103=1&ns104=1&ns105=1&ns106=1&ns107=1&ns460=1&ns461=1&ns486=1&ns487=1&ns490=1&ns491=1&ns828=1&ns829=1&ns1198=1&ns1199=1&ns2300=1&ns2301=1&ns2302=1&ns2303=1&searchToken=5figo091bfj49x281kbz9n7dn)
      * course materials
        * [Informatique quantique - travaux pratiques - ECE Paris](https://commons.wikimedia.org/wiki/File:Informatique_quantique_-_travaux_pratiques_-_ECE_Paris_(2019).pdf)
    * Wikidata
      * Wikidata frontends
        - [WikiDP](https://wikidp.org/search?string=Jupyter)
        - [Scholia](https://scholia.toolforge.org/topic/Q70357595)
          - note that we are exploring to use Jupyter for generating the visualizations; suggestions and comments most welcome
          - also check "use" aspect
      * [Map Making Workshop](https://github.com/KBNLwikimedia/WikidataMapMakingWorkshop) by [Royal Dutch Library](https://www.wikidata.org/wiki/Wikidata:GLAM/Koninklijke_Bibliotheek_Nederland)
    * Wikibooks
      * [Découverte de Python et de Jupyter](https://fr.wikibooks.org/wiki/Python_pour_le_calcul_scientifique/D%C3%A9couverte_de_Python_et_de_Jupyter#Installer_Jupyter)
      * [Introducing Julia/Working with text files](https://en.wikibooks.org/w/index.php?title=Introducing_Julia/Working_with_text_files&oldid=3678056#File_information)
    * Wikimania
      * [2019](https://wikimania.wikimedia.org/w/index.php?search=Jupyter&title=Special%3ASearch&go=Go&ns0=1&ns128=1)
      * [pre-2019](https://meta.wikimedia.org/w/index.php?search=Jupyter+Wikimania&title=Special%3ASearch&go=Go&ns0=1&ns12=1&ns200=1&ns202=1)
        - e.g. Wikimania 2014 talk [Open Scholarship Tools](https://nbviewer.jupyter.org/github/IanMulvany/wikimania-open-scholarship-tools/blob/master/WikimaniaOpenScholarshipTalk.ipynb)
    * Meta
      - [search](https://meta.wikimedia.org/w/index.php?sort=relevance&search=ipynb&title=Special:Search&profile=advanced&fulltext=1&advancedSearch-current=%7B%7D&ns0=1&ns1=1&ns2=1&ns3=1&ns4=1&ns5=1&ns6=1&ns7=1&ns8=1&ns9=1&ns10=1&ns11=1&ns12=1&ns13=1&ns14=1&ns15=1&ns200=1&ns201=1&ns202=1&ns203=1&ns206=1&ns207=1&ns470=1&ns471=1&ns482=1&ns483=1&ns828=1&ns829=1&ns866=1&ns867=1&ns1198=1&ns1199=1&ns2300=1&ns2301=1&ns2302=1&ns2303=1&searchToken=2m0bvery58w03wupd1b8ntv9z)
    * Phabricator
      * [RStudio Server running on JupyterHub on internal PAWS](https://phabricator.wikimedia.org/T180270)
    * etc.
  * Jupyter notebooks in articles
    * as references
      * [baseball stats](https://en.wikipedia.org/w/index.php?title=Chuck_Nieson&oldid=971841978#cite_note-1)
      * [optimization software](https://en.wikipedia.org/w/index.php?title=Gekko_(optimization_software)&oldid=970061912#cite_note-26)
    * infoboxes
      * [documentation](https://en.wikipedia.org/w/index.php?title=Open_energy_system_models&oldid=973759702#NEMO)
    * external links
      * [HMAC-based One-time Password algorithm](https://en.wikipedia.org/w/index.php?title=HMAC-based_One-time_Password_algorithm&oldid=964963525#External_links)
  * Jupyter notebooks to generate illustrations
    * [Human disease network](https://en.wikipedia.org/w/index.php?title=Human_disease_network&oldid=936368133#cite_note-1)
      * plotly and igraph are not installed on the Binder server
        * "Note: you may need to restart the kernel to use updated packages."
    * [Riemann zeta function](https://en.wikipedia.org/w/index.php?title=Riemann_zeta_function&oldid=974660152#cite_note-1) &mdash; provenance unclear, so worth trying it out on Binder, but matplotlib is missing on the Binder server
      - [DomainColoring.ipynb](https://nbviewer.jupyter.org/github/empet/Math/blob/master/DomainColoring.ipynb)
    * [Most Popular Wikipedia Articles of the Week (May 19 to 25, 2019)](https://en.m.wikipedia.org/wiki/File:Most_Popular_Wikipedia_Articles_of_the_Week_(June_2_to_8,_2019).png)
      * "We can't seem to find the Binder page you are looking for."
    * [Qiskit screenshot](https://commons.wikimedia.org/w/index.php?title=File:Qiskit_screenshot.png&oldid=326711914)
      * points to a URL that gives a 404; code has been [reorganized](https://github.com/redisa/QiskitTutorial/blob/master/games/quantum_awesomeness.ipynb)
  * Jupyter notebooks for educational purposes
    - [PyWikiBot tutorial](https://commons.wikimedia.org/wiki/File:Paws_notebook_showing_how_to_load_wikidata_item_dictionary.png)
    - [SPARQL tutorial](https://colab.research.google.com/drive/1EJiMsyYofEr3lOLTGY2sYaFQpKuN_IlN#scrollTo=qL8XNH13k2Wq)
  * Jupyter notebooks for Wikidata queries
    - example: [Binder link](https://gitlab.com/PersonalDataIO/wikidata/blob/master/README.md)
  * Jupyter notebooks in discussions
    * [finite element modelling](https://de.wikipedia.org/w/index.php?title=Wikipedia:Auskunft/Archiv/2017/Woche_25&oldid=194920685#Kostenlose_FEM-Software)
  * Jupyter notebooks for presentional purposes
  * Jupyter notebooks for testing purposes
    * [Wikidata subsetting](Wikidata:WikiProject Schemas/Subsetting)
      - [Jupyter notebook (on Colab) to copy items from Wikidata into another Wikibase](https://colab.research.google.com/drive/1DDws0pGPmP6eKwuDeSCHTCf6PYYMw9OL)
    * [prototyping of bot code](https://colab.research.google.com/drive/1GRVji8FBQd4xw3JipY8b5vG1Soip98My)
    * [importing schema.org into a Wikibase instance](https://colab.research.google.com/drive/1wVKGNYggYDnojKiqKMvt5Z5o_fzXbm00)
  * Jupyter notebooks to analyze event/ campaign participation data
    - [Wiki Loves Africa 2019](https://public.paws.wmcloud.org/User:CS_natematias/Query%20WikiLovesAfrica%20Images%20and%20How%20Often%20They%20Were%20Viewed.ipynb)
  * Jupyter notebooks for editing
    * [page redirects](https://de.wikipedia.org/w/index.php?title=Wikipedia:Fragen_zur_Wikipedia/Archiv/2018/Woche_17&oldid=177213623#Fehlende_Weiterleitungen_effizient_anlegen)
    * [Wikidata Integrator example](https://www.wikidata.org/wiki/Wikidata:Creating_a_bot#Example_Notebook)
  * PAWS
    - [public view](https://public.paws.wmcloud.org/)
  * [PAWS-Internal](https://meta.wikimedia.org/wiki/Discovery/Analytics#PAWS_Internal)
  * [Mention in WMF 2017-2018 Annual Plan](https://meta.wikimedia.org/wiki/Wikimedia_Foundation_Annual_Plan/2017-2018/Final/SinglePage)
  * Colab
  * Internet in a Box
    * via Kolibri
  * data modelling: 
    * how to model a Jupyter notebook?
      * ShEx?
    * how to cite a Jupyter notebook?
      * mention software citation principles
  * lexemes
* If you wrote a Jupyter notebook for educational purposes, chances are that it could serve these purposes through Wikimedia projects too.
* If you wrote code that adds functionality to Jupyter notebooks, JupyterHub, Binder or other parts of the Jupyter ecosystem, chances are that the functionality would be of interest to Jupyter users within the Wikimedia community, or even to users of Wikimedia contents.
* [Candidate items to be portrayed in Jupyter notebooks: items with no image or Commons category but a mathematical formula](https://w.wiki/aH8)
* [Wikipedia as a gateway to biomedical research: The relative distribution and use of citations in the English Wikipedia](https://doi.org/10.1371/journal.pone.0190046)
* Lots of code examples in Jupyter-supported languages in Wikipedia pages about algorithms, standards and similar concepts relevant to computational sciences. Would be nice to have a robust and straightforward way to link these example snippets to a Jupyter notebook that runs out of the box.
  * e.g. Python and Unity C# in [Centripetal Catmull–Rom spline](https://en.wikipedia.org/w/index.php?title=Centripetal_Catmull%E2%80%93Rom_spline&oldid=956131687#Code_example_in_Python)
* [Wikidata:WikiProject PersonalData/Jupyter wikidata](https://www.wikidata.org/wiki/Wikidata:WikiProject_PersonalData/Jupyter_wikidata)

# See also

* Awesome lists, e.g. 
  - Project Jupyter's [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
  - [Reproducibility of the Results of Climate Modeling Experiments](https://sites.nationalacademies.org/cs/groups/dbassesite/documents/webpage/dbasse_186748.pdf)
* [Video Wiki](https://videowiki.wmflabs.org/) &mdash; consider doing one on Jupyter
* [LIGO binder](https://github.com/minrk/ligo-binder)
  - mentioned in https://en.wikipedia.org/wiki/Project_Jupyter but not https://en.wikipedia.org/wiki/LIGO or https://en.wikipedia.org/wiki/First_observation_of_gravitational_waves#Announcement .
* [OpenHumans example notebooks](https://github.com/OpenHumans/ohjh-example-notebooks)
* [Brainstorm on an e-infrastructure grant for Jupyter](https://hackmd.io/fNJQFqgYQaCDGx-BFgz4XQ)
* [Personal Data Wikibase](https://wiki.personaldata.io/wiki/Main_Page)
  - [sample query](https://query.personaldata.io/embed.html#PREFIX%20pdio%3A%20%3Chttps%3A%2F%2Fwiki.personaldata.io%2Fentity%2F%3E%0APREFIX%20pdiot%3A%20%3Chttps%3A%2F%2Fwiki.personaldata.io%2Fprop%2Fdirect%2F%3E%0APREFIX%20pdiop%3A%20%3Chttps%3A%2F%2Fwiki.personaldata.io%2Fprop%2F%3E%0APREFIX%20pdiops%3A%20%3Chttps%3A%2F%2Fwiki.personaldata.io%2Fprop%2Fstatement%2F%3E%0APREFIX%20pdiopq%3A%20%3Chttps%3A%2F%2Fwiki.personaldata.io%2Fprop%2Fqualifier%2F%3E%0A%0ASELECT%20%3Fitem%20%3FitemLabel%20%3Fdate%20%3FregionLabel%20%3FcountryLabel%20%3Fquote%20%3Fweb%20WHERE%20%7B%0A%20%20%3Fitem%20pdiot%3AP110%20pdio%3AQ4138.%0A%20%20OPTIONAL%20%7B%3Fitem%20pdiot%3AP203%20%3Fquote%7D%0A%20%20OPTIONAL%20%7B%3Fitem%20pdiot%3AP100%20%3Fdate%7D%0A%20%20OPTIONAL%20%7B%3Fitem%20pdiot%3AP112%20%3Fregion%7D%0A%20%20OPTIONAL%20%7B%3Fitem%20pdiot%3AP55%20%3Fcountry%7D%0A%20%20OPTIONAL%20%7B%3Fitem%20pdiot%3AP15%20%3Fweb%7D%0A%20%20%0A%20%20SERVICE%20wikibase%3Alabel%20%7B%0A%20%20%20%20bd%3AserviceParam%20wikibase%3Alanguage%20%22en%22%20.%20%0A%20%20%7D%0A%20%20%0A%7D%0A%0A%0AORDER%20BY%20DESC(UCASE(str(%3FregionLabel))))

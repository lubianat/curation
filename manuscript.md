---
title: Conecting the biocuration longtrail
keywords:
- biocuration
- publishing
- review
lang: en-US
date-meta: '2021-04-14'
author-meta:
- Kleber Neves
- Tiago Lubiana
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Conecting the biocuration longtrail" />
  <meta name="citation_title" content="Conecting the biocuration longtrail" />
  <meta property="og:title" content="Conecting the biocuration longtrail" />
  <meta property="twitter:title" content="Conecting the biocuration longtrail" />
  <meta name="dc.date" content="2021-04-14" />
  <meta name="citation_publication_date" content="2021-04-14" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Kleber Neves" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="0000-0001-9519-4909" />
  <meta name="citation_author" content="Tiago Lubiana" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@lubianat" />
  <link rel="canonical" href="https://lubianat.github.io/curation/" />
  <meta property="og:url" content="https://lubianat.github.io/curation/" />
  <meta property="twitter:url" content="https://lubianat.github.io/curation/" />
  <meta name="citation_fulltext_html_url" content="https://lubianat.github.io/curation/" />
  <meta name="citation_pdf_url" content="https://lubianat.github.io/curation/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://lubianat.github.io/curation/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://lubianat.github.io/curation/v/f7297a25da57fd093a1d19f62d45876b62420eae/" />
  <meta name="manubot_html_url_versioned" content="https://lubianat.github.io/curation/v/f7297a25da57fd093a1d19f62d45876b62420eae/" />
  <meta name="manubot_pdf_url_versioned" content="https://lubianat.github.io/curation/v/f7297a25da57fd093a1d19f62d45876b62420eae/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://lubianat.github.io/curation/v/f7297a25da57fd093a1d19f62d45876b62420eae/))
was automatically generated
from [lubianat/curation@f7297a2](https://github.com/lubianat/curation/tree/f7297a25da57fd093a1d19f62d45876b62420eae)
on April 14, 2021.
</em></small>

## Authors



+ **Kleber Neves**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0001-9519-4909](https://orcid.org/0000-0001-9519-4909)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [KleberNeves](https://github.com/KleberNeves)<br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Tiago Lubiana**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [lubianat](https://github.com/lubianat)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [lubianat](https://twitter.com/lubianat)<br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
     · Funded by Grant \#2019/26284-1 from the São Paulo Research Foundation (FAPESP).
  </small>



## Abstract {.page_break_before}




## Draft {.page_break_before}

Whenever we sytematically search and record information from the literature, we genenerate curation data. Curation data comes in many flavours: a group of gene expression datasets related to a given disease, a set of articles united by the same methodology, a list of entities (species, drugs, microRNAs etc) and extracted information about then. In systematic reviews, the systematicity is unavoidable - the data in these tables are used when articles are considered for inclusion. However, these data, produced after many hours of focused, specialized work, are almost always relegated to forgotten folders or lost supplementary tables.

While we often ignore the value of curation as data, curation tables are distilled product of several days of highly-specialized work.
They can serve as evidence for organizing claims, both in our minds and on knowledge bases, thus, they count as "data" [@wikidata:Q31044579].
Data sharing of raw and processed data is maturing [@wikidata:Q106498418], and curation data deserves to be included in the momentum.    

Connecting the "long tail" of small datasets is a valuable prospect that extends beyond raw and processed data too[@wikidata:Q24790499].. 
We know of large biocuration projects, such as UniProt and Gene Ontology, which became  core tools of modern life sciences.
Systematic curations, albeit smaller, are high-quality structured perspectives of experts, and can complement the ecosystem of bio knowledge bases. 
With the growth of collaborative knowledge graphs, like Wikidata [@wikkidata:Q87830400] and BIO2RDF [@wikidata:Q27921271], small curations become first-class citizens in the knowledge exchange framework, adding value for users and recognition for curators.

Take an example from our own work on what we mean by "curation data". One of the authors works in a large project whose goal is to perform direct replications of biomedical experiments published by Brazilian scientists [@wikidata:Q61799268]. To select the experiments to be replicated, a large systematic review of the last 20 years of biomedical literature was conducted, with a focus on finding articles which made use of specific experimental methods. As a result, we obtained information about dozens of articles - about the methods used in the articles (e.g. RT-PCR or cell viability assay) and experimental models (e.g. cell line or species) -, information that was extracted and checked by two separate biomedical researchers. In the course of the project, we used these data to select the sample of experiments to be replicated in the end - that was the goal of this data collection - and the information regarding the experiments that were replicated will be made public when the project is finished. However, despite its agregate value, most of the data obtained in this step remained hidden in some abandoned folder.

Dozens of hours of specialized work, with a concrete result - the intermediate dataset containing the metadata about the articles - which remained unusable. We believe that the tools exist to overcome this with little effort and make these small intermediate datasets usable, unlocking their potential. We advocate for sharing small (or not so small) curated datasets made by every researcher. We argue that this would benefit both the researchers' careers and, collectively, provide a new core knowledge resource for life scientists.

First of all, your work has value: other researchers will love to see your curation, even if it is not perfect. It could save them many hours of work. Searching and harmonizing many small datasets that are relevant to your research is no small feat. For instance, in comparative neuroanatomy, a researcher has published a [tutorial] ([\<https://dieterlukas.github.io/data.html\>](https://dieterlukas.github.io/data.html){.uri}) enumerating the multiple steps one might have to follow to find and gather datasets.

Second, your work will be findable by anyone who wants to work with the data. For instance, Google Datasets makes it very easy to find the work (see Box). Others will find it, and you will find it. It makes science a more communal and shared endeavor, it helps bring in scientists who otherwise could not participate [@wikidata:Q99233710]. Also, most likely, it is you (or someone in your research group) that will be the one who will try to use the dataset again in the future. Say, in 5 years time, when you need it, you will be able to find your curated dataset on Google, instead of spending hours sifting through old e-mails, Google Drive, Dropbox, or even hard drives. You are your most likely future collaborator.

You will also be rewarded in other ways. A table in Zenodo with a DOI is citable, which means you get recognition for your valuable work. Empirical research also suggests that publications whose datasets are open are cited more often [@wikidata:Q93150448]. Also, openness is increasingly recognized as an essential aspect of scientific work that should be recognized and rewarded [@wikidata:Q52622119]. Publishers and funders recognize the importance of open data and are moving in that direction with their policies [@wikidata:Q59134700].

Lastly, if you connect your data to Wikidata, the community benefits from an integrated knowledge graph. For instance, it enables powerful queries via the SPARQL query system. It enables the use of the Scholia platform to visualize the topics you have curated. It makes it visible for everyone to improve academic search engines. Although Wikidata is not yet in widespread use for academic purposes [@wikidata:Q66724305], it has a lot of potential for research - especially for biocuration and organized reviews [@wikidata:Q87830400]. Wikidata is a gateway to fancy ways to integrate knowledge - like structured reviews [@wikidata:Q91866899] - that is acessible without coding skills, and with tutorials in tens of languages (<https://www.wikidata.org/wiki/Wikidata:Introduction>).

Thousands of systematic reviews are published each year [@wikidata:Q52584125], and a large part, if not most, of the curation performed in the course of these reviews remains invisible, unusable, and unrecognized. Systematic reviews could be designed from the start to have their curated datasets in a format that makes it easy to share them later. We argued that this is an excellent opportunity for open science, where there is a lot to be gained from a small additional effort. .This large amount of hidden small curated datasets, if combined and distributed, could make a massive impact on the flow of scientific information in the life sciences.

# How to connect your curation (BOX)

`Tentei colocar essa parte no frame do FAIR, mas não sei se usar DOIs tá em reusable ou interoperable. De qualquer forma, acho que isso aqui devia ser uma caixinha no artigo, sabe? Separado do texto principal, como um "passo a passo sugerido pra fazer isso com os seus datasets". Por isso eu trouxe essa seção pro final e adicionei uns trechos redundantes com o "Why", caso alguém resolva ler só a caixinha.`

Our proposal tries to balance the cost of making these intermediate datasets available with the value for the researchers who performed the data curation and for the scientific community at large [@wikidata:Q96836757]. Hence our focus on systematic reviews, where the data curation is already a necessary step and the data provenance - sources used and methods of curation - will likely be already documented in the published article. Because the structured dataset is a side effect of the research project, the only added step is making the dataset available - researchers likely already have a structured table (say, in CSV or Excel format) or it can be easily exported from other tools, like database management systems (such as Microsoft Access or Libre Office Base). While we give general pointers here, we develop more detailed step-by-step tutorials, which can be found here: **LINK**.

1.  Make it findable: nowadays, there are many possibilities for making datasets available. We recommend Zenodo, which will make the dataset citable, with its own DOI. As we mentioned above, the curation of these datasets is specialized work, it is a contribution to the scientific community. Being citable makes it easy for this work to be recognized. Another benefit is that Zenodo datasets are automatically indexed by data-specific search engines, such as Google Datasets, which makes it findable by interested researchers.

2.  Make it reusable: Describe datasets with enough information to facilitate reuse. A simple solution is to have a data dictionary available together with the dataset. A data dictionary is essentially a thorough description of what is contained in each column of the dataset. On a similar note, whenever possible, use unique identifiers (e.g., identify scientific articles by their DOI, instead of a full citation).

3.  Make it interoperable: if you feel comfortable, an extra-step is to add the data to open knowledge repositories, such as Wikidata (wikidata.org), while referencing your publicly available table. This makes your dataset available in a standard format, integrated with data from many other sources.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

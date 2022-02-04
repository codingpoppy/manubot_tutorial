---
title: Manubot Example
keywords:
- markdown
- manubot
- example
lang: en-US
date-meta: '2022-02-04'
author-meta:
- Yijun Li
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Manubot Example" />
  <meta name="citation_title" content="Manubot Example" />
  <meta property="og:title" content="Manubot Example" />
  <meta property="twitter:title" content="Manubot Example" />
  <meta name="dc.date" content="2022-02-04" />
  <meta name="citation_publication_date" content="2022-02-04" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Yijun Li" />
  <meta name="citation_author_institution" content="Department of Biostatistics, University of Michigan" />
  <meta name="citation_author_orcid" content="0000-0003-0513-9565" />
  <meta name="twitter:creator" content="@jenny589446011" />
  <link rel="canonical" href="https://codingpoppy.github.io/manubot_tutorial/" />
  <meta property="og:url" content="https://codingpoppy.github.io/manubot_tutorial/" />
  <meta property="twitter:url" content="https://codingpoppy.github.io/manubot_tutorial/" />
  <meta name="citation_fulltext_html_url" content="https://codingpoppy.github.io/manubot_tutorial/" />
  <meta name="citation_pdf_url" content="https://codingpoppy.github.io/manubot_tutorial/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://codingpoppy.github.io/manubot_tutorial/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://codingpoppy.github.io/manubot_tutorial/v/ffb05e25254e731c4e9cf8ec1513ec78764adfad/" />
  <meta name="manubot_html_url_versioned" content="https://codingpoppy.github.io/manubot_tutorial/v/ffb05e25254e731c4e9cf8ec1513ec78764adfad/" />
  <meta name="manubot_pdf_url_versioned" content="https://codingpoppy.github.io/manubot_tutorial/v/ffb05e25254e731c4e9cf8ec1513ec78764adfad/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <meta property="og:image" content="https://github.com/codingpoppy/manubot_tutorial/raw/ffb05e25254e731c4e9cf8ec1513ec78764adfad/thumbnail.png" />
  <meta property="twitter:image" content="https://github.com/codingpoppy/manubot_tutorial/raw/ffb05e25254e731c4e9cf8ec1513ec78764adfad/thumbnail.png" />
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
([permalink](https://codingpoppy.github.io/manubot_tutorial/v/ffb05e25254e731c4e9cf8ec1513ec78764adfad/))
was automatically generated
from [codingpoppy/manubot_tutorial@ffb05e2](https://github.com/codingpoppy/manubot_tutorial/tree/ffb05e25254e731c4e9cf8ec1513ec78764adfad)
on February 4, 2022.
</em></small>

## Authors



+ **Yijun Li**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-0513-9565](https://orcid.org/0000-0003-0513-9565)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [codingpoppy](https://github.com/codingpoppy)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [jenny589446011](https://twitter.com/jenny589446011)<br>
  <small>
     Department of Biostatistics, University of Michigan
  </small>



## Example Manuscript in Manubot {.page_break_before}
This is an example of a manuscript in Manubot. In this file, we will cover how to add tables, figures, mathematical equations, and citations to your manuscript text.

### Tables
Tables can be created manually or using the tables generator webapp: https://www.tablesgenerator.com/markdown_tables#.
See Table @tbl:example-1

|           | Age | Gender |
|:---------:|:---:|:------:|
| subject 1 |  12 |    F   |
| subject 2 |  22 |    M   |

Table: Caption for this example table. {#tbl:example-1}

### Figures
Figures can be uploaded in the ./content/images/ directory. \
See Figure {@fig:example-1}

![chromosome](images/manubot_fig.jpeg){#fig:example-1 tag="S1" width="100%" height="100%"}

### Equations
Mathematical equations can be written inline as the following:

$$\frac{\partial}{\partial \boldsymbol{X}}f(\boldsymbol{X}) = 2\boldsymbol{X};      \boldsymbol{X}\in\mathbb{R}^{5}$$

### Citations
#### Direct citations
Manubot supports multiple citations methods, including DOI, PubMed ID, url, etc.

See https://github.com/manubot/rootstock/blob/main/USAGE.md for the Manubot's prefix for the list of supported citation methods. Reference prefixes can also be added manually into the metadata file.

For example, for the following paper: "Pulmonary acini exhibit complex changes during postnatal rat lung development", we can cite via several of the following ways:\
*using DOI: [@doi:10.1371/journal.pone.0257349]
*using url: [@{https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0257349}]

Multiple citations can be added like so: [@{https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0257349}; @{https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007128}]

#### Citation aliases
Citations aliases are also supoprted. Citing the following paper "Pulmonary acini exhibit complex changes during postnatal rat lung development" [@my-url].

[@my-url]: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0257349

#### Citation aliases using metadata
We can add the following lines in the ./content/metadata.yaml file:

pandoc:
  citekey-aliases:
    my-url: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0257349


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

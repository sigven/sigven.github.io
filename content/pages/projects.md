---
title: projects
description: 'research projects | Sigve Nakken'
date: ''
author: Sigve Nakken
---

I am actively developing and maintaining multiple open-source software tools, typically applied within the fields of *cancer precision medicine* and *high-throughput cancer biology*. Technically, I use mostly R and Python. 

I try to make all tools I develop available and documented through <a href="https://github.com/sigven/" target="_blank">GitHub</a> repositories, allowing users to file bug reports, ask questions regarding functionality etc., and potentially contribute code. Some of the main ongoing projects are briefly outlined below.

<h5>Personal Cancer Genome Reporter (PCGR)</h5>

<a href="https://sigven.github.io/pcgr/"><img src="https://github.com/sigven/pcgr/raw/main/pcgrr/man/figures/logo.png" align="right" height="88.5" width="75"/></a>
We have developed the <a href="https://github.com/sigven/pcgr/" target = "_blank">Personal Cancer Genome Reporter (PCGR)</a>, a stand-alone software package for translation of individual tumor genomes for precision cancer medicine. Through the integration of a comprehensive set of <a href="https://rpubs.com/sigven/pcgrbundle" target = "_blank">knowledge resources</a> related to tumor biology and therapeutic biomarkers, PCGR generates a comprehensive variant report that acts as decision support for identification of novel treatment targets and strategies.

<h5>Cancer Predisposition Sequencing Reporter (CPSR)</h5>

<a href="https://sigven.github.io/cpsr/"><img src="https://github.com/sigven/cpsr/raw/main/man/figures/logo.png" align="right" height="88.5" width="75"/></a>
The <a href="https://github.com/sigven/cpsr/" target = "_blank">Cancer Predisposition Sequencing Reporter (CPSR)</a> is a computational workflow that interprets inherited DNA variation identified from next-generation sequencing in the context of cancer predisposition and inherited cancer syndromes. Importantly, CPSR classifies the pathogenicity of DNA variants in cancer predisposition genes trough a refined set of <a href="https://sigven.github.io/cpsr/articles/variant_classification.html" target = "_blank">ACMG/AMP variant classification criteria</a>.

<h5>oncoEnrichR</h5>

<a href="https://sigven.github.io/oncoEnrichR/"><img src="https://github.com/sigven/oncoEnrichR/raw/main/man/figures/logo.png" align="right" height="88.5" width="75"/></a>
Genome-scale screening experiments produce long lists of candidate genes that require extensive interpretation for biological insight and prioritization for follow-up studies. Interrogating these gene lists is a time-consuming and challenging undertaking. <a href="https://github.com/sigven/oncoEnrichR/" target="_blank">oncoEnrichR</a> is a user-friendly reporting framework that portrays the cancer relevance of candidate hits in a comprehensive manner, allowing researchers to efficiently gather evidence when picking candidates for in-depth follow-up experiments. oncoEnrichR comes as an R package, but is also accessible through a <a href="https://oncotools.elixir.no/" target="_blank">web interface in Galaxy</a>.

<h5>pharmOncoX</h5>

<a href="https://sigven.github.io/pharmOncoX/"><img src="https://github.com/sigven/pharmOncoX/raw/main/man/figures/logo.png" align="right" height="88.5" width="75"/></a>
pharmOncoX is an R package that provides access to targeted and non-targeted cancer drugs, including comprehensive annotations per target, drug mechanism-of-action, approval dates, clinical trial phases for various indications etc. Drugs are further classified according to the Anatomical Therapeutic Chemical (ATC) Classification System, enabling a filtering of cancer drugs according to their main types of action. Some of the functionality is outlined [here](https://sigven.github.io/pharmOncoX/articles/pharmOncoX.html).

<h5>geneOncoX</h5>

<a href="https://sigven.github.io/geneOncoX/"><img src="https://github.com/sigven/geneOncoX/raw/main/man/figures/logo.png" align="right" height="88.5" width="75"/></a>
Which human genes are implicated in tumor development?
<a href="https://github.com/sigven/geneOncoX/" target = "_blank">geneOncoX</a> is an R package that address this question through the integration of a number of resources with respect to cancer gene annotations, providing up-to-date information on tumor suppressive/proto-oncogenic roles of human genes, predicted cancer drivers, known cancer predisposition genes, and more.

<h5>phenOncoX</h5>

<a href="https://sigven.github.io/phenOncoX/"><img src="https://github.com/sigven/phenOncoX/raw/main/man/figures/logo.png" align="right" height="88.5" width="75"/></a>
An ontological definition of disease enables each type of disease to be singularly classified in a formalized structure. Multiple ontology frameworks have been developed for human cancers/diseases, examples being [OncoTree](https://oncotree.mskcc.org/#/home), [Experimental Factor Ontology (EFO)](https://www.ebi.ac.uk/efo/), [Disease Ontology (DO)](https://disease-ontology.org/), [MeSH](https://www.nlm.nih.gov/research/umls/sourcereleasedocs/current/MSH/index.html), and [ICD](https://www.who.int/standards/classifications/classification-of-diseases). However, these ontologies are typically used to different extents across knowledge resources in the oncology domain, such as gene-disease, drug-disease, or variant-disease associations. <a href="https://github.com/sigven/phenOncoX/" target = "_blank">phenOncoX</a> is an R package that cross-references disease entries across multiple ontologies, with a sole focus on the oncology domain. Its purpose is thus to bridge the various disease ontologies used for human cancers, and to simplify data integration procedures in this context. 

<h5>gvanno - generic variant annotation pipeline</h5>

<a href="https://github.com/sigven/gvanno/"><img src="https://github.com/sigven/gvanno/raw/master/src/gvanno_logo.png" align="right" height="88.5" width="75"/></a>
The generic variant annotator (<a href="https://github.com/sigven/gvanno/" target="_blank">gvanno</a>) is a software package intended for basic analysis and interpretation of human DNA variants. Variants and genes are annotated with disease-related and functional associations. Technically, the workflow is built with the Docker technology, and it can also be installed through the Singularity framework.



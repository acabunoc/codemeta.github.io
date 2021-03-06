---
layout: default
title: CodeMeta
---

Research relies heavily on scientific software, and a large and growing fraction of researchers are engaged in developing software as part of their own research [Hannay et al 2009](http://dx.doi.org/10.1109/SECSE.2009.5069155). Despite this, _infrastructure to  support the preservation, discovery, reuse, and attribution of software_ lags substantially behind that of other research products such as journal  articles and research data. This lag is driven not so much by a lack of  technology as it is by a lack of unity: existing mechanisms to archive,  document, index, share, discover, and cite software contributions are heterogeneous among both disciplines and archives and rarely meet best practices [Howison 2015](http://dx.doi.org/10.1002/asi.23538).

## How can we make this better?

Fortunately, a rapidly growing movement to improve preservation, discovery, reuse and attribution of academic software is now underway: a recent [NIH report](http://softwarediscoveryindex.org), conferences and working groups of [Force11](https://www.force11.org/), [WSSSPE](http://wssspe.researchcomputing.org.uk/) & [Software Sustainability Institute](http://www.software.ac.uk/), and the rising adoption of repositories like [GitHub](https://github.com), [Zenodo](https://zenodo.org), [figshare](https://figshare.com) & [DataONE](https://www.dataone.org) by academic software developers. Now is the time to improve how these resources can talk to each other.  
<hr/>

# April 15 - 17 2016

# Portland, Oregon

# The Future of Software Metadata

## [Agenda](/agenda)

<br/>

<hr/>

## CodeMeta

<img width="150px" style="float: right" src="/public/img/matt.png"/> <img width="150px" style="float: right" src="/public/img/carl.png"/>
The CodeMeta project does not seek to create [yet another standard](https://xkcd.com/927/).  Rather, we're aiming to _create a crosswalk table_ between standards already in use -- think of this as a Rosetta stone of software metadata.  Beginning in an [Open Science Code-fest](http://nceas.github.io/open-science-codefest/) discussion lead by [Abby Mayes](https://twitter.com/abbycabs) and now thanks to a generous [NSF EAGER Grant](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1549758&HistoricalAwards=false) to Carl Boettiger (UC Berkeley) & Matt Jones (NCEAS & UC Santa Barbara), we will bring together leaders of software and data repositories with academic researchers to develop this crosswalk table for software metadata. This event will dovetail with the [Force16](https://www.force11.org/meetings/force2016) (Future of Research Communication & e-Scholarship) meeting in Portland. 

### What is software metadata?

What metadata you want from software is determined by your use case.  If your primary concerns are credit for academic software, then you're most interested in _citation_ metadata.  If you're trying to replicate some analysis, you worry more about versions and dependencies than about authors and titles.  And if you seek to discover software you don't already know about that is suitable for a particular task, well then you are interested more in keywords and descriptions. Frequently, developers of scientific software, repositories that host that software, and users themselves are interested in more than one of these objectives, and others besides.

Different software repositories, software languages and scientific domains denote this information in different ways, which makes it difficult or impossible for tools to work across these different sources without losing valuable information along the way.  For instance, a fantastic collaboration between GitHub and figshare provides researchers a way to import software on the former into the persistent archive of the latter, getting a permanent identifier, a DOI in the process.  To assign a DOI, figshare must then pass metadata about the object to DataCite, the central DOI provider for all repositories.  While this makes DataCite a powerful aggregator, the lack of a crosswalk table means that much valuable metadata is currently lost along the way, such as the original software license, platform, and so forth. Any tool or approach working across software repositories faces similar challenges without a crosswalk table to translate between these.

### Our team

- [Carl Boettiger](http://carlboettiger.info), UC Berkeley
- [Matt Jones](https://twitter.com/metamattj), NCEAS
- [Arfon Smith](http://www.arfon.org/), GitHub
- [Yolanda Gil](http://www.isi.edu/~gil/), USC ISI
- [Martin Fenner](https://twitter.com/mfenner), DataCite
- [Krzysztof Nowak](https://github.com/krzysztof), Zenodo
- [Mark Hahnel](https://twitter.com/markhahnel?lang=en), figshare
- [Abby Mayes](https://twitter.com/abbycabs), Mozilla Science Foundation
- [Luke Coy](http://lukecoy.github.io/), RIT & MSF
- [Kyle Niemeyer](http://kyleniemeyer.com/), Oregon State
- [Alice Allen](https://twitter.com/asclnet), ASCL
- [Mercè Crosas](http://scholar.harvard.edu/mercecrosas), Harvard IQSS 
- [Ashley Sands](https://knowledgeinfrastructures.gseis.ucla.edu/?page_id=62#Sands), UCLA
- [Neil Chue Hong](https://twitter.com/npch) SSI
- [Peter Slaughter](https://github.com/sbpcs59), NCEAS
- [Patricia Cruse](https://www.datacite.org/news/datacite-appoints-patricia-cruse-executive-director.html), DataCite
- [Dan Katz](http://danielskatz.org/), NCSA
- [Carole Goble](http://www.manchester.ac.uk/research/Carole.goble/), University of Manchester


<!--
- [Lars Holm Nielsen](http://www.hankat.dk/), Zenodo
- [Jennifer Lin](https://twitter.com/jenniferlin15), CrossRef

-->


For more detail, [visit the project on GitHub](https://github.com/codemeta/codemeta) or check back here soon.

## Special thanks to our supporters

<img width="224px"  src="/public/img/nsf.jpg"/>
<img width="224px"  src="/public/img/datacite.png"/>
<img width="224px" src="/public/img/github.png"/>
<img width="224px"  src="/public/img/figshare.png"/> 
<img width="224px"  src="/public/img/zenodo.jpg"/>

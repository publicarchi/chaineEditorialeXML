# Actualités 2019

**Publishers Survey:** 

The State of Production Automation and Workflow Modernization 

| Workflow Step         | Yes  | No   |
| --------------------- | ---- | ---- |
| Editorial             | 51%  | 49%  |
| Print production      | 64%  | 34%  |
| e-Products production | 71%  | 29%  |

Enjeux plusieurs passes, format et qualité 

63% éditeurs passé le cap, jugent que décision plus importante qu’aient prise

Are you using

**38%:** **Yes
** **27%:** **No, but we are looking into it
** **6%:** **We are in the process of migrating now** **29%:** **No, and we have no plans to change*

Priorité 

**74%:** **Revenue
** **69%:** **Improving efficiency
** **66%:** **Reducing costs
** **29%:** **Improving author acquisition and satisfaction**  



articles récents

2018, What are the benefits of an XML-first workflow in publishing and Marketing ?

https://amnet-systems.com/what-are-the-benefits-of-an-xml-first-workflow-in-publishing-and-marketing/

---

## MIT Press (2012)

Premier éditeur dont les contenus scientifiques constituent l’activité principale aux US.

- 200 nouveaux livres /an
- 80% en XML (non XML ouvrages d’architecture, ou pas produits en traitement de txt)
- 4 436 titres numériques
- 2 552 web-ready
- 338 ePub (Kobo, Amazon, Barnes and nobles, etc.)

(En 2012 : Jake Furbush, digital publishing manager https://youtu.be/EHmXM61ItWY, depuis 2015 Harvard University Press)

???

Jake Furbush, digital publishing manager (2016). jfurbush@mit.edu

CMS Marklogic facilite 7 flux de travail. Remplacement par Alfresco. 

Utilisation de EXTYLES pour les brouillons. Possibilité de corriger syntaxe, identification des citations.

Utilisation de la validations, exploration de nouveaux formats pour le livre. JATS pour les journaux.

Transformation optimisée pour InDesign des fichiers corrigés. Utilisation de template pour alimenter les ePub.

Converstion TeX pour eXtyling

---

## CFA Institute

NLM Book DTD

Plus grande association de professionnels de l’investissement (110 000 membres dans 139 pays). Nombreuses activité de formation.

2010 adoption NLM Book DTD. Publication de journaux et lettres informations avec JATS. Environ 7 journaux.

Choix car utilisation NLM Journals

Cindy Maisannes https://youtu.be/7iEghsGOq5Y

- Single-source publishing (plus sûr)
- Facilitation de la production, automatisation des modifications, plus rapide

Automation prend du temps

---

## Elsevier

https://www.elsevier.com/authors/author-schemas/xml-in-science-publishing

> Elsevier is basing its workflow for primary book and journal publications on the "XML-first" principle: all articles and books are converted to XML as they come in and this XML is used to prepare all output, irrespective of the format.

[Elsevier DTD family](https://www.elsevier.com/authors/author-schemas/elsevier-xml-dtds-and-transport-schemas)

???

> Elsevier's book and journal content is based on XML. XML stands for eXtensible Markup Language. XML documents are structured ("tagged") independently of the presentation in a way that can be extended by the developer of the XML standard that is used.
>
> Elsevier is basing its workflow for primary book and journal publications on the "XML-first" principle: all articles and books are converted to XML as they come in and this XML is used to prepare all output, irrespective of the format.

[Elsevier DTD family](https://www.elsevier.com/authors/author-schemas/elsevier-xml-dtds-and-transport-schemas)

Dernières version 2016

Ensemble de la chaîne de travail est basée sur XML. Les commande sont également traitées en XML dans un format appelé CONTRAST (CONtent TRAnsport STandard)

---

## Standards Tag Suite (STS)

- ANSI/NISO Z39.102-2017
- Standard pour l’encodage XML de documents de standardisation

https://www.niso-sts.org/

Rétrocompatible avec ISO STS 1.1.

Usdin, B. Tommie. 2018. « What is NISO STS? » *XML.com* (blog). 6 janvier 2018. https://www.xml.com/articles/2018/01/06/what-niso-sts/.

---

## Hogrefe

éditeur spécialisé en psychologie

- 240 livres /an
- 42 journaux 
- tests

BITS et InDesign

2013

https://youtu.be/UPRIhdz8ycA

---

## Chaîne Métope

---

## The Web, the W3C and the Future of Publishing

https://www.w3.org/publishing/

Plusieurs ateliers dans le cadre de l’Open Web Platform

- ebooks New York (février 2013)
- internationalisation dans l’édition (Tokyo 2013)
- édition imprimée et OWP (Paris, septembre 2013)
- Annotation et OWP (San Francisco, avril 2014)

Digital Publishing Activity créée pour aider le W3C à se concerter sur les besoins de l’édition.

- Digital Publishing Interest Group premier brouillon pour mise en page des textes latins
- 

Liam Quim, 2014 JATS-Con https://youtu.be/uGVerpRsO3Q

Liam Quim, 2013 Balisage https://www.balisage.net/Proceedings/vol12/html/Quin01/BalisageVol12-Quin01.html

Digital Publishing Interest Group, draft par Dave Cramer (Hachette) 16 000 titres par an en CSS et HTML, arrière plan en XSL-FO. Actuellement Luc Audrain (Hachette) dirige le groupe https://www.w3.org/community/publishingbg/participants

Début 2017, IDPF  fut absorbé par le World Wide Web Consortium  (W3C). Dès lors le développement du standard EPUB et des autres technologies pour la Web Platform ont désormais lieu au sein du W3C.

Requirements for Latin Text Layout and Pagination 2014 https://www.w3.org/TR/dpub-latinreq/

https://www.w3.org/TR/dpub-css-priorities/

2017 https://www.w3.org/TR/pwp/ Web Publications for the Open Web Platform: Vision And Technical Challenges

> This document outlines a vision for the convergence between the Open Web Platform and portable documents while also significantly advancing and expanding the existing digital publishing ecosystem. The realization of this vision would require a strong cooperation between the traditional publishing and Web communities, based on a close collaboration between the W3C and other relevant organizations, like [IDPF](http://idpf.org/), [EDItEUR](http://editeur.org/), [BISG](http://www.bisg.org/), or others. While it is envisaged that most of the work could be done in one or more dedicated Working Groups (within W3C or elsewhere, depending on the exact charter), it must be emphasized that many of the features will affect and will be affected by work done elsewhere, within or outside these organizations. The starting point will be to explore and plan for the detailed technical challenges to gain a better insight into the work ahead; this exploration should be done together with the various interested communities.

2019 https://www.w3.org/TR/wpub/

https://www.w3.org/dpub/IG/

---

## Techniques

XSL-FO

### Pipelines

https://xprocbook.com/book/book-1.html

### Solutions à surveiller

- PrinceXML
- PDFreactor
- Paged.js

---

## Autres formats

- [Darwin Information Typing Architecture (DITA XML)](http://xml.coverpages.org/dita.html)

  documentation technique (structuration, hypertextualité, index)

- DocBook
  monographies techniques (logiciel, keyCode, GUIButton, etc.)

- TEI
  publication académique, versification, correspondance, transcriptions de ms

- NISO JATS journal / US National Library of Medicine (NLM)

- BITS [jats.nlm.nih.gov/extensions/bits/](https://jats.nlm.nih.gov/extensions/bits/)

- The Book Interchange Tag Suite (BITS) is an XML document model for STEM books that is based on JATS (the Journal Article Tag Suite ANSI/NISO Z39-96-2015). 

#### Journal Article Tag Suite (JATS)

- ANSI/NISO Z39.96-2015
- 1ère publication en 2003, dernier standard 2015

'JATS', également connu sous l’appelation ANSI/NISO Z39.96-2015 JATS: Journal Article Tag Suite,

Lapeyre, Debbie. 2018. « Introduction to JATS (Journal Article Tag Suite) ». *XML.com* (blog). 12 octobre 2018. https://www.xml.com/articles/2018/10/12/introduction-jats/.

Publié en 2003

### Book Interchange Tag Suite (BITS)

- ANSI/NISO Z39-96-2015
- Standardisation 2015

Lapeyre, Debbie. 2019. « Introduction to BITS (Book Interchange Tag Suite) ». *XML.com* (blog). 18 janvier 2019. https://www.xml.com/articles/2019/01/18/introduction-bits-book-interchange-tag-suite/.

> The Book Interchange Tag Suite (BITS) is an XML document model for  STEM books that is based on JATS (the Journal Article  Tag Suite ANSI/NISO Z39-96-2015). BITS is a named collection of XML  elements and attributes for describing the structural and semantic content of books and book  components, as well as a packaging  element for interchange of book parts. BITS provides a robust book model that is compatible with JATS, making it easy for publishers of both  journals and books to publish them using the same system.

Fournir un vocabulaire destiné à supporter l’échange, l’archivage, la conversion de format et la publication de livres scientifiques, de référence, d’enseignement supérieur, techniques et médicaux. Le format n’est pas centré sur les catalogues commerciaux, les livres de cuisine ou les libres scolaires, ni les publications légales, l’édition de texte historique.

Modèle de création fondé sur JATS. 'JATS', également connu sous l’appelation ANSI/NISO Z39.96-2015 JATS: Journal Article Tag Suite,

Format qui permet de prendre en charge

- métadonnées de collection
- métadonnées de livre
- front matter
- body et parties
- back matter

Déclaratif basé sur JATS, documenté, gratuit et public

---

## Question de la bibliographie

BibTeX, des successeurs

Tib (Refer). Refer un préprocesseur pour Tirof.

MlBibTEX https://www.tug.org/TUGboat/tb25-0/hufflen.pdf



---

Enquête XML 1st Workflow

2017 https://apexcovantage.com/

Apex CoVantage’s NuanSCE is a tool designed to improve the consistency and speed of copyediting.

> XML-First workflow was defined as getting to a structured document up-front of production. It may or may not mean that manuscript is transformed to XML. However, with proper care in using Word manuscripts, the underlying structure of the file is XML which, when combined with a proper styling template and document clean-up tools, it is possible to continue editing in Word but have XML under the hood.
>
> We’ve seen relatively few publishers take the step to edit directly in XML. Those that do tend to produce either standards documents or technical manuals.

SAAS-based system souvent privilégié par petits éditeurs. Pb de viabilité à long terme.

https://apexcovantage.com/blog/three-meaningful-workflow-improvements-for-university-press-publishers/

---

Sociétés

River Valley Technologies https://rivervalleytechnologies.com

https://www.infognana.com

https://www.pps-ace.com

https://www.stilo.com

http://expertml.com/tom.html

https://apexcovantage.com/

https://diacritech.com/inxml-automated-publishing-tool

*eXtyles* (Inera). Atypon Acquires Inera, Developer of Editorial and XML Workflow Solutions for Scholarly, Technical, and Legal Publishers (juillet 2019) https://www.atypon.com/news/atypon-acquires-inera-developer-of-editorial-and-xml-workflow-solutions-for-scholarly-technical-and-legal-publishers/

> Inera is widely recognized as a global leader in publishing technology. Since 1992, Inera’s seasoned team of publishing and software professionals has pooled a unique set of skills to bring transformational change to the publishing industry. Our solutions include the eXtyles family of Word-based editorial and XML tools and the Edifix online bibliographic reference solution. Publishers of scholarly journals and books, standards, and government documents worldwide rely on Inera’s software solutions to drive modern publishing workflows.

> Atypon develops end-to-end publishing technologies for getting mission-critical content into the hands of the practitioners and researchers who need it most. Literatum, Atypon’s online publishing and website development platform, lets publishers manage, deliver, and monetize all the content they distribute, from standards and scholarly articles to online courses and videos. Atypon’s tools for researchers let them easily author, discover, and access the content that they need. Founded in 1996, Atypon is headquartered in Santa Clara, California, with over 450 staff in 10 offices around the world.

https://rebus.foundation/

https://pressbooks.com/

Accessibilité

Accessible Books Consortium (ABC)

https://www.accessiblebooksconsortium.org/portal/en/index.html

> The Accessible Books Consortium (ABC) is a public-private partnership led by the World Intellectual Property Organization (WIPO). It includes organizations that represent people with print disabilities such as the World Blind Union (WBU); libraries for the blind; standards bodies, and organizations representing authors, publishers and collective management organizations.

---

## O’Reilly

http://toc.oreilly.com/

> “Publishing isn’t about putting ink on paper, and moving blocks of  said paper through warehouses to readers. It’s about knowledge  dissemination, learning, entertainment, codification of subject  authority — the real jobs that authors and publishers do for readers…  Our goal is to bring together people who are pushing the boundaries of  publishing and those who want to learn from them, and to provide a table of contents (TOC), so to speak, on what modern publishers need to  know.”

> We’ve been developers of publishing technology since the days we  first started publishing. In the “scratch your own itch” spirit of the  open source movement, we co-created [DocBook](http://www.docbook.org/whatis) in the early ’90s, published the first commercial web magazine, [GNN](http://en.wikipedia.org/wiki/Global_Network_Navigator) (initially developed as a demo to help bookstores grok the Internet!) in 1993, and launched [Safari Books Online](http://www.safaribooksonline.com) in 2000.  And we’ve used the internal production toolchain we built  over the years to create a digital distribution business that now  provides DRM-free ebooks in multiple formats not only from O’Reilly but  also from Microsoft Press, Wiley, Elsevier, No Starch, and many other  technical publishers.
>
> For the past few years, we’ve been focusing on development of a  platform code-named **Atlas**, and bringing that to fruition is central to  our future plans. Atlas is a tool for collaborative writing (currently  being used by authors of about two-thirds of the books in our pipeline), one-touch publishing in all formats (including print-on-demand), and an interactive online reading platform that takes full advantage of the  digital realm. We believe it takes a big step towards fulfilling the  promise of digital publishing. You’ll be hearing much more about Atlas  in the coming months.

https://atlas.oreilly.com/

---

## CSS XSLFO Gap Analysis (2016)

On the Monday DPUB call, one of the things that came up was doing a formal gap analysis for CSS vs XSL-FO.

Liam R. E. Quin started the following list. Please add or give samples.

- XSL-FO has a more powerful expression language for properties than calc() in CSS
- XSL-FO has page masters, and nothing comparable has taken off for CSS;
- XSL-FO (especially the 2.0 draft) has more powerful floats, indexes, hyphenation control, etc
- XSL-FO doesn't do the CSS cascade (for both good and ill), doesn't have the same box model (because the CSS box model wasn't finished when FO was done, but also because of inheritance in a more rigid vocabulary), and of course doesn't do CSS 3ish things. Not sure any of that matters when moving from FO to CSS.
- XSL-FO can copy & move elements e.g into page headers and footers, preserving or not preserving style, arguably more cleanly than the GCPM proposal(s) so far. [https://www.w3.org/TR/2011/WD-css3-gcpm-20111129/]
- XSL-FO has more powerful table support.

https://www.w3.org/dpub/IG/wiki/CSS_XSLFO_Gap_Analysis

Comparer avec ce que faisaient réellement les logiciels https://xmlgraphics.apache.org/fop/compliance.html

https://www.antennahouse.com

Aujourd’hui

CSS Generated Content for Paged Media Module, http://www.w3.org/TR/css-gcpm-3/

2018 https://www.w3.org/TR/css-page-3/
---
title: 'Computer Friday Nov 19, 2021: Documenting data (FAIR data at FAIR)'
author: Erik Ø. Sørensen
date: '2021-11-15'
slug: computer-friday-nov-19-2021-documenting-data
categories: []
tags: []
---

## Background
Demands on data documentation are increasing as more pressure is put on researchers to provide 
[FAIR data](https://www.go-fair.org/fair-principles/), ideally also FAIR data that are openly 
available. (It is confusing to talk about FAIR data at FAIR, but we'll have to find a way to live with that.)
The data produced from a research product is now often seen as a primary research product, in
need of [much more resources and attention](https://doi.org/10.1038/d41586-020-00505-7) than 
it has been afforded previously.


In the past, data documentation for publishing data is something that might be hurriedly put together
at the time of final acceptance of the paper - providing a replication package for journals that expect that.
Sometimes, contractual obligations meant that data needed to be provided for NSD; that  
sometimes happened long after actual publication (unfortunately).

The job of documenting data in detail will eventually have to be done. Is there any reason to 
postpone that work until publishing data at the time of paper publication? There is an obvious need
for some documentation also during the analysis. Even if the person or team that is intensively involved
in the analysis is intimately familiar with the details of the data, the rest of the team often are not
as informed about what information is actually in the data. 

- In the documentation stage, it can happen that misunderstandings about the content of data are cleared up. Better to do this early.
- In the documentation stage, it often becomes clear that the data file to document needs to be non-redundant and with useful names. 
the data that people work on is a bit of a mis-mash of raw data and analytical files. It would be better to freeze and document the useful set 
of raw data early on and have the analysis be based on this attempt at a final data product instead of having to modify the code as the
structure of data changes just before submission.



## Tools
There are tools that can help with documentation of data according to recognized standards. In social science,
an important set of standards are provided by the [Data Documentation Initiative (DDI)](https://ddialliance.org/). 
Tool providers are
- [Nesstar Publisher](http://www.nesstar.com/software/publisher.html): This is a tool that [NSD - Norwegian centre for research data](http://www.nesstar.com/software/publisher.html) has developed and use in their own archiving services. This tool can also ingest Stata data files and
  use labels. The Stata files must have been saved with `saveold XX, version(11)` to be ingestible. Produces a nice pdf output and a DDI-Codebook `.xml` file. Windows software. Free for use, and each researcher can use it.
- [Colectica](https://colectica.com/): A commercial enterprise that sells both lightweight [Colectica for Excel](https://colectica.com/software/colecticaforexcel/)
  and the more heavy duty (and more expensive) [Colectiva Designer](https://colectica.com/software/designer/). These tools can ingest Stata data files, use
  labels from those data files and write pdf and DDI-Lifecycle `.xml`files. Windows software. The full-blown Designer is more polished and up-to-date than Nesstar, but it is costly, at $59/user per month.
- [DataWiz](https://datawiz.leibniz-psychology.org/DataWiz/?datawiz_locale=en) A system developed at the Leibniz Institute for Psychology in Trier. Unclear
how available this. Web-based.

Productive use of these packages depend on having some understanding of what the fields are intended to mean in the relevant DDI standard. 
We should think about creating a standard template for fields to populate. There is some guidance in the [Best practices document](https://library.carleton.ca/sites/default/files/help/data-centre/BPDv3-1-2019-01-28.pdf) developed by people at [<odesi> (Ontario Data Documentation, Extraction Service and Infrastructure)](https://search2.odesi.ca/).

## Standard operating procedures?

I think we should discuss whether there is a potential for common Standard Operating Procedure (SOP) at FAIR,
this would provide guidance to new researchers, we could make them such that some internal quality assurance 
process is possible and improve the quality of the data product.  

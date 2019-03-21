---
title: 'DocOps Method'
date: 2018-03-21
weight: 1
---

In the spirit of the DevOps movement the DocOps method combines human written documentation with it's execution on the system it documents. Making human written documents executable just like an applications.

The majority of documentation artifacts and system state consist of content that rarely changes. Only small but important parts are changed regularly. This is the sweet spot where the DocOps concept provide a benefit by making sure that the regularly changed content is always up-to-date.  
DocOps is in general the concept of having an executable documentation, or enrichment of documentation based on execution results.

## Contribution

More on the GitHub Page

## Alternatives Concepts

Enrich the existing Documentation with the results from pipeline execution. So part of the documentation is injected from code. In this case the user is editing the various config files and scripts and as an output of this the documentation is updated with predefined injection points. 

## Examples

Example of good and bad DocOps practice:

Generate Reverse Proxy Config for HAProxy/Nginx from documentation. Provide markdown example.

Good Practice
Do

Bad Practice
Enriched documents should be up to date or the enriched content should be valid for a long period of time at least double the mean time between average document generation.
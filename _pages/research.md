---
title: "BioAI Research Group - Research"
layout: textlay
excerpt: "BioAI Research Group -- Research"
sitemap: false
permalink: /research/
---

# Research

Our overarching goal is to use computational biology approaches to gain a better understanding of biological systems. One focus is to develop deep neural network architectures to analyse high-throughput cancer data and push forward the area of precision medicine. We are interested in integrative approaches that combine high-throughput data (genomics, transcriptomics, proteomics, metabolomics) on particular systems with existing biological knowledge from knowledge-bases such as biological network data (KEGG, Reactome). We are also investigating the use of multi-agent systems (MAS) to facilitate flexible and goal-driven analysis to integrate bioinformatics data and methods.

Here are some themes and techniques that we currently work on: [Genomics](#genomics), [Transcriptomics](#transcriptomics), [Proteomics](#proteomics), [Metabolomics](#metabolomics), [Systems Biology Integration](#systems-biology-integration)


## Genomics

## Transcriptomics

<div class="row">

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.transcriptomics == 1 %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description_long }}</p>
  </div>
</div>  

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="80%" style="float: left" />
</div>  


{% endif %}
{% endif %}
{% endfor %}

</div>



## Proteomics

## Metabolomics

## Systems Biology Integration



---
title: "BioAI Research Group - Research"
layout: textlay
excerpt: "BioAI Research Group -- Research"
sitemap: false
permalink: /research/
---

# Research

Our overarching goal is to use computational biology approaches to gain a better understanding of biological systems. One focus is to develop deep neural network architectures to analyse high-throughput cancer data and push forward the area of precision medicine. We are interested in integrative approaches that combine high-throughput data (genomics, transcriptomics, proteomics, metabolomics) on particular systems with existing biological knowledge from knowledge-bases such as biological network data (KEGG, Reactome). We are also investigating the use of multi-agent systems (MAS) to facilitate flexible and goal-driven analysis to integrate bioinformatics data and methods.

Here are some themes and techniques that we currently work on: [Machine Learning and AI](#machine-learning-and-ai), [Precision Medicine](#precision-medicine), [Genomics / Genetics](#genomics--genetics), [Transcriptomics](#transcriptomics), [Proteomics](#proteomics), [Metabolomics](#metabolomics), [Systems Biology Integration](#systems-biology-integration)

## Machine Learning and AI


{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.ml_ai == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}


## Precision Medicine

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.precision_medicine == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}


## Genomics / Genetics

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.genomics == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}


## Transcriptomics

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.transcriptomics == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}


## Proteomics

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.proteomics == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}

## Metabolomics

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.metabolomics == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}



## Systems Biology Integration

{% for publi in site.data.publist %}

{% if publi.highlight == 1 %}
{% if publi.sysbio_integration == 1 %}

<div class="row">

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p>{{ publi.description}}</p>
  </div>
</div>  

<div class="col-sm-6">
 <div class="well">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%"/>
  </div>
</div>  


</div>

{% endif %}
{% endif %}
{% endfor %}


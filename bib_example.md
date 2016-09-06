---
layout: page
title: "Bibliography Example"
permalink: bib_example/
description: "This is an example on how to use jekyll-scholar"
---
{% include JB/setup %}

## publish

{% bibliography --query @article @inproceedings %}

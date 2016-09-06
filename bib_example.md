---
layout: page
title: "Bibliography Example"
description: "This is an example on how to use jekyll-scholar"
tags : [intro, beginner, jekyll, tutorial, bibliography, scholar]
---
{% include JB/setup %}

## publish

{% bibliography --query @article @inproceedings %}

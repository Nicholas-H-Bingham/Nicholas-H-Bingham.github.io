---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.papers reversed %}
  {% include archive-single.html %}
{% endfor %}

## 2019

## 2018

## 2017

## 2016

## 2015

## 2014

## 2013

## 2012

## 2010

## 2009

## 2008

## 2007

## 2006

## 2005

## 2004

## 2003

## 2002

## 2001

## 2000

  {% for post in site.papers.2000 reversed %}
    {% include archive-single.html %}
  {% endfor %}



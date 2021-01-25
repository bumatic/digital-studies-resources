---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
toc: true
draft: true
weight: 
summary: 
---

**Insert Lead paragraph here.**

## New Cool Posts

{{ range first 10 ( where .Site.RegularPages "Type" "cool" ) }}
* {{ .Title }}
{{ end }}
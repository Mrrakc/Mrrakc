---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
author: []
categories: []
regions: []
tags: []
gmaps: ""
cover:
  image: "{{.Name}}.jpg"
  alt: "{{.Name}}"
  caption: "{{ replace .Name "-" " " | title }}"
draft: true
---


---
title: "{{ title (delimit (after 3 (split .Name "-")) " " )}}"
date: {{ .Date }}
slug: "{{ lower (delimit (after 3 (split .Name "-")) "-" )}}"
draft: true
---

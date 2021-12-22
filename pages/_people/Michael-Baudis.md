---
title: "Michael Baudis"
layout: default
excerpt_link: 'https://info.baudisgroup.org/group/Michael_Baudis/'
excerpt_separator: <!--more-->
category:
  - contact
  - people
tags:
  - contacts
  - people
  - IS_2021_Data
  - IS_2021_hCNV-X
---

<h2>{{page.title}}
{%- assign portrait = page.title | replace: ' ', '-' -%}
{%- for static_file in site.static_files -%}
    {%- if static_file.extname == '.jpg' or static_file.extname == '.png'  -%}
        {%- assign imgf = static_file.basename | replace: ' ', '-' -%}
        {%- if imgf == portrait -%}
<img style="float: right; width: 80px; margin-top: -12px; margin-right: 10px; margin-bottom: -50px;" src="{{ static_file.path | relative_url}}" />
        {%- endif -%}
    {%- endif -%}
{%- endfor -%}</h2>

* Professor of Bioinformatics, University of Zurich & Swiss Institute of Bioinformatics  
* Co-chair GA4GH Discovery Work Stream  
* Co-lead ELIXIR hCNV Community  
* ELIXIR Beacon Project  

<!--more-->

email [mbaudis@progenetix.org](mailto:mbaudis@progenetix.org)  
web [UZH](https://www.imls.uzh.ch/en/research/baudis.html)  
web [SIB](https://www.sib.swiss/michael-baudis-group)  
web [group](https://info.baudisgroup.org)  

---
layout: page
title: Data and code
permalink: /data_code/
sidebar_link: true
sidebar_sort_order: 2
---

### Code

Lab project data and code will appear at our GitHub organization: [jmadinlab](https://github.com/orgs/jmadinlab). Projects will generally be private until first publication.

[[Tutorial](/data_code_tutorial) for lab members]

### Dataset Registry

Datasets are made public following first publication. Datasets are stored in a number of ways, including online databases, FigShare, GitHub and our lab server. Below is a growing list of datasets. This list is currently incomplete and being worked on to make all lab products visible in one location.

[[Add dataset](https://github.com/jmadinlab/jmadinlab.github.io/issues/new?assignees=jmadin&labels=add+dataset&template=add-dataset.md&title=I%27d+like+to+add+a+dataset+to+the+lab)]

|Name|Contact|Description|Access|
|---|---|---|---|---|
{%- for dataset in site.datasets %}
| [{{ dataset.name }}]({{ dataset.id }})| {{ dataset.contactName | replace: "|","/" }} | {{ dataset.description }} | {{ dataset.access }} |  
{%- endfor %}

[datasets.json](/datasets.json)

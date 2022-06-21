---
layout: page
title: People
permalink: /people/
sidebar_link: true
sidebar_sort_order: 1
---

### Principal Investigator

{% for person in site.people %}
  {% if person.role == "PI" and person.current %}
  - [{{ person.name }}]({{ person.id }})
  {% endif %}
{% endfor %}

### Lab Manager

{% for person in site.people %}
  {% if person.role == "Lab Manager" and person.current %}
  - [{{ person.name }}]({{ person.id }})
  {% endif %}
{% endfor %}

### Postdoctoral Researchers

{% for person in site.people %}
  {% if person.role == "Postdoctoral Researcher" and person.current %}
  - [{{ person.name }}]({{ person.id }})
  {% endif %}
{% endfor %}

### Graduate Students

{% for person in site.people %}
  {% if person.role == "Graduate Student" and person.current %}
  - [{{ person.name }}]({{ person.id }})
  {% endif %}
{% endfor %}

### Undergraduate Researchers

{% for person in site.people %}
  {% if person.role == "Undergraduate Researcher" and person.current %}
  - [{{ person.name }}]({{ person.id }})
  {% endif %}
{% endfor %}

### Past members

{% for person in site.people %}
  {% if person.current == false %}
  - {{ person.name }} ({{ person.role }})
  {% endif %}
{% endfor %}

- Peter David (Masters)
- Marcela Diaz (Research Assistant)
- Marguerite Gosse (Research Assistant)
- Liesl Grant (Undergraduate Project)
- Dr Aaron Harmer (Postdoc)
- Ludovic Hoarau (Masters)
- Dr Osmar Luiz Jr (PhD)
- Alisha Madsen (Honours, Research Assistant)
- Dr Joseph Maina (PhD)
- Dr Julieta Martinelli (PhD)
- Dr Toni Mizerek (PhD)
- Elisa Plati (Research Assistant)
- Dr Kristin Precoda (Research Assistant)
- Alex Robinson (Undergraduate Project)
- Jack Roxburgh (Undergraduate Project)
- Sheena Su (Masters)
- Dr Rachael Woods (Masters, PhD)
- Dr Kyle Zawada (PhD)

[[Add member](https://github.com/jmadinlab/jmadinlab.github.io/issues/new?assignees=jmadin&labels=add+person&template=add-person.md&title=I%27d+like+to+add+myself+to+the+lab)]

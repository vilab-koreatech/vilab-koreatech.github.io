---
title: Team
nav:
  order: 3
tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} Team

Our lab is made up of a highly engaged and collaborative team of researchers. We recognize that diverse teams do better research. We foster an environment where team members are treated equally and where we respect and admire our differences.

{% include section.html %}

{% assign pi_members = site.members | where_exp: "m", "m.role == 'pi' and m.group != 'alum'" %}
{% for m in pi_members %}
  {% include portrait.html
    name=m.name
    image=m.image
    role=m.role
    description=m.description
    affiliation=m.affiliation
    links=m.links
    url=m.url
    slug=m.slug
  %}
{% endfor %}

{% assign phd_members = site.members | where_exp: "m", "m.role == 'phd' and m.group != 'alum'" | sort: "joined_order" %}
{% for m in phd_members %}
  {% include portrait.html
    name=m.name
    image=m.image
    role=m.role
    description=m.description
    affiliation=m.affiliation
    links=m.links
    url=m.url
    slug=m.slug
  %}
{% endfor %}

{% assign ms_members = site.members | where_exp: "m", "m.role == 'ms' and m.group != 'alum'" | sort: "joined_order" %}
{% for m in ms_members %}
  {% include portrait.html
    name=m.name
    image=m.image
    role=m.role
    description=m.description
    affiliation=m.affiliation
    links=m.links
    url=m.url
    slug=m.slug
  %}
{% endfor %}

{% assign ug_members = site.members | where_exp: "m", "m.role == 'undergrad' and m.group != 'alum'" | sort: "joined_order" %}
{% for m in ug_members %}
  {% include portrait.html
    name=m.name
    image=m.image
    role=m.role
    description=m.description
    affiliation=m.affiliation
    links=m.links
    url=m.url
    slug=m.slug
  %}
{% endfor %}

{% include section.html dark=true %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives. We want to push the frontier of data science and train the next generation of data scientists.

{% include section.html %}

## Alumni

Gone but never forgotten.

{% assign alumni_members = site.members | where_exp: "m", "m.group == 'alum'" | sort: "joined_order" %}
{% for m in alumni_members %}
  {% include portrait.html
    name=m.name
    image=m.image
    role=m.role
    description=m.description
    affiliation=m.affiliation
    links=m.links
    url=m.url
    slug=m.slug
    style="small"
  %}
{% endfor %}

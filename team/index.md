---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of a highly engaged and collaborative team of researchers. We recognize that diverse teams do better research. We foster an environment where team members are treated equally and where we respect and admire our differences.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi' and group != 'alum'" %}

{% include section.html dark=true %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives.
We want to push the frontier of data science and train the next generation of data scientists.

{% include section.html %}

## Alumni

Gone but never forgotten.

{% include list.html data="members" component="portrait" filter="group == 'alum'" style="small" %}

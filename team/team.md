---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi' and group !='alum'" %}




## Alumni

{% include section.html %}


{% include list.html data="members" component="portrait" filter="role != 'pi' and group =='alum'" %}



{% include grid.html style="square" content=content %}



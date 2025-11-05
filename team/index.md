---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is a highly engaged and collaborative team of researchers. We believe that diverse teams do better science, so we work to create an environment where everyone is treated equitably and our differences are respected and valued.

**We are actively recruiting undergraduate and graduate students to join our team. Please see [CONTACT]({% link contact/index.md %}) for more information.**

{% include section.html %}

<!-- {% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %} -->

<!-- {% comment %}Collect active members by role{% endcomment %}
{% assign pi  = site.members | where: "active", true | where: "role", "pi"  | sort: "order" %}
{% assign phd = site.members | where: "active", true | where: "role", "phd" | sort: "order" %}
{% assign ms  = site.members | where: "active", true | where: "role", "ms"  | sort: "order" %}
{% assign ug  = site.members | where: "active", true | where: "role", "ug"  | sort: "order" %}

{% comment %}If you want section headings, keep these blocks; otherwise, skip to the "single grid" version below{% endcomment %} -->

### Principal Investigator
<div class="people-grid">
  {% for m in pi %}
    {% include member-card.html member=m %}
  {% endfor %}
</div>

### PhD Students
<div class="people-grid">
  {% for m in phd %}
    {% include member-card.html member=m %}
  {% endfor %}
</div>

### Master’s Students
<div class="people-grid">
  {% for m in ms %}
    {% include member-card.html member=m %}
  {% endfor %}
</div>

### Undergraduate Students
<div class="people-grid">
  {% for m in ug %}
    {% include member-card.html member=m %}
  {% endfor %}
</div>


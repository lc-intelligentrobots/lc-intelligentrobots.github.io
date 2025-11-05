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


### Principal Investigator
{% include list.html
   data="members"
   component="portrait"
   filter="role == 'principal-investigator'"
%}

### PhD Students
{% include list.html
   data="members"
   component="portrait"
   filter="current != false and role == 'phd'"
%}

### Master’s Students
{% include list.html
   data="members"
   component="portrait"
   filter="current != false and (role == 'ms' or role == 'master')"
%}

### Undergraduate Students
{% include list.html
   data="members"
   component="portrait"
   filter="current != false and (role == 'ug' or role == 'undergrad')"
%}


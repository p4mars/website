---
title: Team
nav:
  order: 4
  tooltip: Members of our lab
---

# {% include icon.html icon="fa-solid fa-users" %}Team

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. -->

{% include section.html %}
## Faculty
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

## Research Scientist
### Postdoc
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

### PhD
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

### Master students

### Alumni

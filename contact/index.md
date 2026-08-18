---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<p class="center" style="font-size: 1.3em;">We are allways interested to collaborate and meet new colleagues, do not hesitate to reach out.</p>

{%
  include button.html
  type="email"
  link="P4MARS-AE@tudelft.nl"
%}
<!-- {%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/aGo3qTV3fbQ7GBRGA"
%} -->

{% capture map_embed %}
<iframe
  src="https://www.google.com/maps?q=TU+Delft+Faculty+of+Aerospace+Engineering,+Kluyverweg+1,+2629+HS+Delft&output=embed"
  width="100%"
  height="100%"
  style="border: 0;"
  allowfullscreen=""
  loading="lazy"
  referrerpolicy="no-referrer-when-downgrade"
></iframe>
{% endcapture %}

{% capture contact_text %}

<div class="center">

<b>TU Delft Faculty of Aerospace Engineering</b>
<br>Kluyverweg 1, 2629 HS Delft, The Netherlands

</div>

{% endcapture %}

<style>
.feature-compact {
  max-width: 1000px;
  margin-left: auto;
  margin-right: auto;
  gap: 20px;
}
</style>

{%
  include feature.html
  embed=map_embed
  title="Address"
  text=contact_text
  flip=true
  class="feature-compact"
%}
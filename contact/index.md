---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you have questions about our research projects, want to collaborate on new educational designs, or are interested in using our teaching resources, please reach out to us.

{%
  include button.html
  type="email"
  text="cal-core@berkeley.edu"
  link="cal-core@berkeley.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/y1Rdc5f3e9QJcLC17"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Berkeley School of Education building, home of the CoRE Lab."
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Collaborative research and design sessions with educators."
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
**Mailing Address**  
Berkeley School of Education  
University of California, Berkeley  
Berkeley, CA 94720  
{% endcapture %}

{% capture col2 %}
**General Inquiries**  
For general questions or partnership opportunities, email us at:  
[cal-core@berkeley.edu](mailto:cal-core@berkeley.edu)  
{% endcapture %}

{% capture col3 %}
**Our Work**  
Explore our active curriculum designs, publications, and software on our [Projects](/projects/) page.  
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

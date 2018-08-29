---
title: Attendees
layout: reference
reference-type: swagger
---

{% capture deprecation-content %}
* DELETE `/expense/attendees/{id}`
{% endcapture %}

{% include deprecation-alert.html deprecation-date="05/19/2016" unsupported-date="11/19/2016" content=deprecation-content %}

{% swagger /api-explorer/v3-0/Attendees.swagger2.json %}

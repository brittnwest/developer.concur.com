---
title: Attendee Types
layout: reference
reference-type: swagger
---

{% capture deprecation-content %}
* POST `/expense/attendeetypes`
* DELETE `/expense/attendeetypes/{id}`
{% endcapture %}

{% include deprecation-alert.html deprecation-date="05/19/2016" unsupported-date="11/19/2016" content=deprecation-content %}


{% swagger /api-explorer/v3-0/AttendeeTypes.swagger2.json %}

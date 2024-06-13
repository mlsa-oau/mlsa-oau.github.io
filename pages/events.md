---
layout: page
title: Community Events
permalink: /events/
---

## Ongoing Events

{% for event in site.data.events.ongoing %}
### {{ event.name }}
- **Date**: {{ event.date }}
- **Location**: {{ event.location }}
- **Description**: {{ event.description }}
{% endfor %}

## Upcoming Events

{% for event in site.data.events.upcoming %}
### {{ event.name }}
- **Date**: {{ event.date }}
- **Location**: {{ event.location }}
- **Description**: {{ event.description }}
- **Registration**: {{ event.register }}
{% endfor %}

## Past Events

{% for event in site.data.events.past %}
### {{ event.name }}
- **Date**: {{ event.date }}
- **Location**: {{ event.location }}
- **Description**: {{ event.description }}
{% endfor %}

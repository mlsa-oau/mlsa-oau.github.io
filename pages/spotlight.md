---
layout: page
title: Community Spotlight
permalink: /spotlight/
---

Celebrating members who have excelled:

{% for member in site.data.spotlight %}
### {{ member.name }}
- **Achievements**: {{ member.achievements }}
- **Profile**: [View Profile]({{ member.url }})
{% endfor %}

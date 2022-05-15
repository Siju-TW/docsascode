---
Date: 15 May
layout: template
---


# Antivirus
Updated on {{page.Date}}

A program used to prevent, detect and remove computer virus. For more information, see [Antivirus](https://en.wikipedia.org/wiki/Antivirus_software)
## Types of Anitvirus Software
- Symantec
- Norton
- MacAfee
- Bitdefender

## Developers

{% for item in site.data.developers %}
- {{item.name}},{{item.year}}
{%endfor%}
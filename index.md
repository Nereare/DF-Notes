---
title: Home
layout: home
---

Hello and welcome! This is a collection of notes regarding my gameplay style and
schematics used frequently.

This site is intended as a way of keeping all the schematics and resources I use
recurrently in one place of easy access - and maybe helping some other soul in
the process.

## Schematics

{% assign scheems = site.schematics | join: '' %}
{% if scheems != '' %}
{% for scheme in site.schematics %}
* **[{{ scheme.title }}]({{ scheme.url }}):** {{ scheme.description }}
{% endfor %}
{% else %}
No schematics for now. :cry:
{% endif %}

## Acknowledgements

* This project uses [Mipui](https://www.mipui.net/) on most of its schematics.

---
layout: page
title: Računalniki
categories: [racunalnik]
shortinfo: Kratko o računalnikih in našteti računalniki in oprema
---

### Računalniki

{% for racunalnik in site.clanki%}

[{{racunalnik.title}}]({{racunalnik.url}})

{% endfor %}

### Programska oprema

{% for program in site.programskaoprema%}

[{{program.title}}]({{program.url}})

{% endfor %}
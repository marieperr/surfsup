---
title: "Colonnes"
categories: [
    "Shortcodes",
    "Go",
]
tags: [
    "organisation",
]
menu: "main"
---

# Colonnes

Les colonnes aident à organiser les informations horizontalement  en prenant moins de place.

```html
{{</* columns */>}} <!-- begin columns block -->
# Contenu à gauche
Lorem markdownum insigne...

<---> <!-- magic separator, between columns -->

# Contenu à droite
Lorem markdownum insigne...
{{</* /columns */>}}
```

## Exemple

{{< columns >}}
## Contenu à gauche
Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
protulit, sed sed aere valvis inhaesuro Pallas animam: qui _quid_, ignes.
Miseratus fonte Ditis conubia.

<--->


## Contenu à droite
Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
protulit, sed sed aere valvis inhaesuro Pallas animam: qui _quid_, ignes.
Miseratus fonte Ditis conubia.
{{< /columns >}}

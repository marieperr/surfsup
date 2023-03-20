---
title: "Marqueurs"
categories: [
    "Shortcodes",
    "Go",
]
tags: [
    "visuel",
    "organisation",
]
menu: "main"
---



# Marqueurs

Le shortcode Hint peut être utilisé en guise de bloc d'indice, d'alerte, de notification.

Il y a trois choix possibles : `info`, `warning` and `danger`.

```tpl
{{</* hint [info|warning|danger] */>}}
**Contenu en Markdown**  
Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
{{</* /hint */>}}
```

## Exemple

{{< hint info >}}
**Contenu en Markdown**  
Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
{{< /hint >}}

{{< hint warning >}}
**Contenu en Markdown**  
Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
{{< /hint >}}

{{< hint danger >}}
**Contenu en Markdown**  
Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
{{< /hint >}}

---
title: "Détails"
categories: [
    "Shortcodes",
    "Go",
]
tags: [
    "visuel",
]
menu: "main"
---

# Détails

Détails est un shortcode qui correspond à la balise html `details`. Cela peut remplacer le shortcode[`expand`](https://mmellet.github.io/Carnet-Modele3/posts/shortcodes/expand).

## Exemple
```tpl
{{</* details "Title" [open] */>}}
## Contenu en Markdown
Lorem markdownum insigne...
{{</* /details */>}}
```
```tpl
{{</* details title="Title" open=true */>}}
## Contenu en Markdown
Lorem markdownum insigne...
{{</* /details */>}}
```

{{< details "Title" open >}}
## Contenu en Markdown
Lorem markdownum insigne...
{{< /details >}}

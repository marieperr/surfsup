---
title: "KaTeX"
categories: [
    "Shortcodes",
    "Go",
]
tags: [
    "code",
    "visuel",
]
menu: "main"
---

# KaTeX

KaTeX est un shortcode qui permet d'afficher des formules mathématiques dans un document en markdown. Pour la documentation complète : voir [KaTeX](https://katex.org/)

## Exemple
{{< columns >}}

```latex
{{</*/* katex [display] [class="text-center"] */*/>}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{</*/* /katex */*/>}}
```

<--->

{{< katex display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}

{{< /columns >}}

## Exemple du mode d'affichage

Ici un exemple d'un affichage sur une même ligne : {{< katex >}}\pi(x){{< /katex >}}. 

Ci-dessous, un exemple de `display` en mode `display: block`
{{< katex display >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}


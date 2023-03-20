---
title: "Graphique"
categories: [
    "Shortcodes",
    "Go",
]
tags: [
    "organisation",
    "visuel",
]
menu: "main"
---

# Graphique de la Sirène

[MermaidJS](https://mermaid-js.github.io/) est une bibliothèque qui permet de générer des graphiques en svg et des diagrammes à partir du texte.

{{< hint info >}}
**Configuration de Mermaid**

Le fichier qui permet de mettre en place Mermaid sans suivre les [étapes de configurations](https://mermaid-js.github.io/mermaid/#/Setup) se trouve dans le dossiers `assets` et est nommé `mermaid.json`.
{{< /hint >}}

## Exemple

{{< columns >}}
```tpl
{{</*/* mermaid [class="text-center"]*/*/>}}
stateDiagram-v2
    State1: Première bulle
    note right of State1
        Il est possible de personnaliser les bulles.
    end note
    State1 --> State2
    note left of State2 : C'est la bulle 2.
{{</*/* /mermaid */*/>}}
```

<--->

{{< mermaid >}}
stateDiagram-v2
    State1: Première bulle
    note right of State1
        Il est possible de personnaliser les bulles.
    end note
    State1 --> State2
    note left of State2 : C'est la bulle 2.
{{< /mermaid >}}

{{< /columns >}}

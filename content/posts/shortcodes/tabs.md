---
title: "Tableau"
categories: [
    "Shortcodes",
    "Go",
]
tags: [
    "organisation",
]
menu: "main"
---

# Tableau

Le tableau permet d'organiser les contenus selon des contextes, comme par exemple des instructions selon les OS des machines. 


```tpl
{{</* tabs "uniqueid" */>}}
{{</* tab "MacOS" */>}} # Contenu pour MacOS {{</* /tab */>}}
{{</* tab "Linux" */>}} # Contenu pour Linux {{</* /tab */>}}
{{</* tab "Windows" */>}} # Contenu pour Windows {{</* /tab */>}}
{{</* /tabs */>}}
```

## Exemple

{{< tabs "uniqueid" >}}
{{< tab "MacOS" >}}
# MacOS

Ceci est l'onglet pour le Contenu pour **MacOS**.

Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
protulit, sed sed aere valvis inhaesuro Pallas animam: qui _quid_, ignes.
Miseratus fonte Ditis conubia.
{{< /tab >}}

{{< tab "Linux" >}}

# Linux

Ceci est l'onglet pour le Contenu pour **Linux**.

Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
protulit, sed sed aere valvis inhaesuro Pallas animam: qui _quid_, ignes.
Miseratus fonte Ditis conubia.
{{< /tab >}}

{{< tab "Windows" >}}

# Windows

Ceci est l'onglet pour le Contenu pour **Windows**.

Lorem markdownum insigne. Olympo signis Delphis! Retexi Nereius nova develat
stringit, frustra Saturnius uteroque inter! Oculis non ritibus Telethusa
protulit, sed sed aere valvis inhaesuro Pallas animam: qui _quid_, ignes.
Miseratus fonte Ditis conubia.
{{< /tab >}}
{{< /tabs >}}

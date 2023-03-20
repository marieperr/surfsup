---
categories: [
    "Hugo",
]
tags: [
    "theme",
    "organisation",
    ]
title: "Particulier au thème Book"
---

## Pour re-structurer le site 

Le dossier `posts` peut être supprimé **mais** ne peut pas être renommé (sinon le chemin vers les fichiers est perdu).

Le placement et le chemin dans la barre latérale de navigation sont établis automatiquement par le thèm : donc il n'est pas nécessaire d'éditer ce lien dans la page `index` dans le dossier `menu` comme pour les autres sections. 

Le contenu des fichiers peut être remplacé, les noms des fichiers à l'intérieur du dossier peuvent être renommés si voulu. 


## Pour enlever la ToC d'une page

Pour enlever la table des matières des pages, insérer cette condition dans les métadonnées : 

```
bookToc: false
```

# Pour cacher une page de l'affichage 

Pour cacher une page de l'affichage web, insérer cette condition dans les métadonnées : 

```
bookHidden: true
```
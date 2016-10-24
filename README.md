# Pixel-Isima.github.io
---

# How to
## Rédaction d'un post

Chaque post doit être rédigé en markdown dans le dossier `_posts`. Le nom du fichier doit respecter le format suivant : `AAAA-MM-JJ-titre.markdown`.

Le contenu du post contient un header définissant les méta-données de l'article et un corps comprenant le texte de l'article. Le header doit respecter le squelette suivant :
```
---
layout: <Template d'affichage souhaitée : post, page, default>
title:  <Titre de l'article>
date:   <Date de publication formatée : AAAA-MM-JJ HH:MM:SS +0200>
categories: <Catégorie dans laquelle sera publié le post : post, event, project>
summary: <Résumé de l'article>
---
```
Le layout des events, projets et articles est le layout post.  

## Layout
Les layout sont les fichiers .html définissant la structure types des pages et des posts.

## Includes
Les includes définissent les layout des aperçus des articles, events & projets.

# Le Markdown et vous
Les plus subtils diront **[RTFM]**.  
Plus raisonnablement :
* **[Markdown GitHub flavored]** : la syntax Markdown la plus utilisée, définie par Github pour les README
* **[Kramdown syntax]** : la syntaxe utilisée pour écrire les pages du site. Elle est semblable à la _Github flavored_ mais peut contenir certaines nuances.

[RTFM]:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#emphasis
[Markdown GitHub flavored]:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#emphasis
[Kramdown syntax]:http://kramdown.gettalong.org/syntax.html

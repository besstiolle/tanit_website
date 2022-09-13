---
title: "Sandbox"
description: "Page de démonstration à ne pas publier"
featured_image: "/images/Pope-Edouard-de-Beaumont-1844.jpg"
date: 2022-09-04T13:55:48+02:00
draft: true
---

# Titre niveau 1

## Titre niveau 2

### Titre niveau 3


**texte en gras**

*texte italique*

> citation

1. Premier item liste ordonale
2. Second item
3. Troisième item

- Un item
- Un autre item 
- Encore un item

`Du code, également utile pour un formatage particulier`

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
``` 

---
Au dessus, une ligne séparatrice

[Un lien](https://www.example.com)

Du texte
qui en réalité ne retourne
pas à la ligne



Du texte qui retourne

A la ligne

| Titre colonne 1  | Titre colonne 2 |
| ----------- | ----------- |
| Cellule 1 | Cellule 2 |
| Cellule 1b | Cellule 2b | 

Du texte avec une note de bas de page. [^1]

[^1]: Ceci est la note de bas de page. 

Un terme à définir
: La définition de ce mot

- [x] Checklist 
- [ ] Todo reste à faire
- [ ] Autre todo reste à faire


## Images

Insérer une figure avec une description. Attention, ceci ne permet pas d'optimiser l'image. L'image doit être dans le répertoire /static/

{{< figure src="/images/Victor_Hugo-Hunchback.jpg" title="Illustration from Victor Hugo et son temps (1881)" >}}

Insérer une image présente dans le répertoire courant de façon optimisée.

**exemple :** 100px de large, à gauche par défaut.

{{% image10ko "notebook.jpg" %}}
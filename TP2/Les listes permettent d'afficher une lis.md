Les listes permettent d'afficher une liste de contenu ordonné ou non-ordonné. Il existe trois types de listes différentes en HTML:

1.  **Listes à puces (unordered list)** : Les listes à puces sont utilisées pour représenter des éléments qui n'ont pas d'ordre particulier. Chaque élément est représenté par un point, un carré ou un cercle. Elle est créée en utilisant la balise `<ul>` et chaque élément est encadré dans une balise `<li>`.

Exemple :

```
<ul>
   <li>Élément 1</li>
   <li>Élément 2</li>
   <li>Élément 3</li>
</ul>
```

2.  **Listes numérotées (ordered list)** : Les listes numérotées représentent un ensemble d'éléments qui ont un ordre spécifique. Chaque élément est représenté par un numéro sous forme de chiffres ou de lettres. Elle est créée en utilisant la balise `<ol>` et chaque élément est encadré dans une balise `<li>`.

Exemple :

```
<ol>
   <li>Élément 1</li>
   <li>Élément 2</li>
   <li>Élément 3</li>
</ol>
```

3.  **Listes de définitions (definition list)** : Une liste de définition est utilisée pour fournir une série de termes et leurs définitions. Elle est créée en utilisant la balise `<dl>`. Chaque terme est encadré dans une balise `<dt>` et sa définition est encadrée dans une balise `<dd>`.

Exemple :

```
<dl>
   <dt>Terme 1</dt>
   <dd>Définition du terme 1</dd>
   <dt>Terme 2</dt>
   <dd>Définition du terme 2</dd>
</dl>
```
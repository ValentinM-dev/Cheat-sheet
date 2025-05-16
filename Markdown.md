# Markdown

Le markdown est un language de balisage permettant d'écrire et de lire différent documents. Il est souvent utilisé afin d'écrire et d'expliquer les éléments comportant un projet et ces différentes fonctionnalité. En général il est utilisé afin de rédiger le README des différents projets. De nombreux éditeurs de texte offrent un aperçu en temps réel du rendu final, rendant son adoption plus facile.
---

## Pourquoi utilisé le Markdown ?

Les raisons portant le markdown a être utilisé comme language d'écriture pour les README, Documents Explicatifs ect sont les suivants :

| Points fort | Explication |
| :-: | :-: |
| Simplicité | Le markdown est un language facile à apprendre et à utiliser developpeur ou non. |
| Lisibilité | Le format utilisé par le Markdown est clair et lisible même dans sa forme brute |
| Portabilité | Markdown ce compose seulement de fichiers texte (.md ou .markdown) il est donc ouvrable et modifiable dans n'importe quel éditeur de texte. |
| Flexibilité | Il est supporté par de nombreuse platforme web (Webs, Forums, Gestionnaires de versions comme GitHub, éditeurs de texte et outils de documentation.) |

**Il peut être utiliser de différente manière :**
---

# Les Titres

En markdown, les titres peuvent être afficher en différent niveaux grace à la balise "#" :
| Niveau | Prérequis |
| :---: | :---: |
| 1 | # + Message|
| 2 | ## + Message|
| 3 | ### + Message|
| 4 | #### + Message |
| 5 | ##### + Message |
| 6 | ###### + Message |
Voici ce que cela donne en pratique :
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6

:warning: Si vous mettez plus de **6** ou que **vous collez le message à la balise** alors la balise ne fonctionnera pas
---

# Les Mises en Exergue du texte

Markdown étant un language de balisage conçu pour lire et écrire. Il est donc possible d'avoir les texte en gras, en italique et barrer.

Pour cela il faudra donc enfermer le message sous divers balise.

- En *italique* ```_``` ou ```*``` avant et après le message  donne 

- En **gras** ```__``` ou ```**``` avant et après le message donne 

- En ***gras et en italique*** ```___``` ou ```***``` avant et après le message donne 

- ~~Barrer~~ le message ```~~``` Avant et après le message donne 
---

# Les Listes

Il a 3 façons d'utiliser les listes en Markdown. Les listes ordonées, les listes non ordonnées et listes de tâches

| Liste ordonée | Liste non ordonée | liste de tache
| :-: | :-: | :-: |
| * | 1. | [x]
| - | 2. | [ ]
| + | 3. |

:warning: Lors de l'utilisation de la liste ordonées il n'est pas nécessaire que les chiffres sois séquentiels. *Il est automatiquement incrémenter.*
---

# Les Liens

Afin de pouvoir afficher un lien via markdown on l'utilise de cette façon.

```[Lien de l'URL](URL "Titre optionnel du lien)```

[Ceci est un lien](https://www.lego.com/fr-fr/product/bmw-m-1000-rr-42130)
---

# Les Images
Les images fonctionne de la même façons que les liens cependant, Il faut qu'il sois précéder d'un "!"

```![Lien de l'image](URL de l'image "Titre optionnel de l'image)```

![Ceci est une image](https://kidzzz-n-quadzzz.com/wp-content/uploads/moto-electrique-enfant-HP4-race-12V--600x500.jpg)
---

# Les Citations 
En markdown, Lors d'une explication d'une fonctionnalité ou afin d'afficher une citation il a 2 façons de les expliquées. Une citation simple ou une citation imbriquée.

``` > Citation Simple```

``` > > Citation imbriqué```

> Ceci est une Citation
> > Ceci est une Citation Imbriqué
---

# Afficher du Code

En markdown, On peut tout aussi afficher du code directement avec le language souhaiter. 
Il suffis de préceder et terminer les lignes de codes avec "```"

⚠️ Il ne faut pas oublié d'indiquer le language utilisé lors de l'explication du code 

```javascript
function helloWorld(){
console.log("Bonjour, le monde !")
}
```
---

# Les Séparateurs

Enfin, En markdown il est possible de séparer les différents sujets ou fonction en utilisant ```---```

### Fonction numéro 1

---

### Fonction numéro 2

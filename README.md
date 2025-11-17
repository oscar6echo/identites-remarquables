# Chapitre : Les Identités Remarquables

## 1. Introduction : Pourquoi ?

En calcul littéral, on doit très souvent **développer** des expressions, c'est-à-dire transformer un produit en somme.

Par exemple, $(x + 3)(x + 2)$. On utilise la **double distributivité** :  
$(x + 3)(x + 2) = x \times x + x \times 2 + 3 \times x + 3 \times 2$  
$(x + 3)(x + 2) = x^2 + 2x + 3x + 6$  
$(x + 3)(x + 2) = x^2 + 5x + 6$  

Certains produits reviennent si souvent qu'on a créé des "raccourcis" pour aller plus vite.  
Ce sont les **identités remarquables**.  

---

## 2. L'identité (a + b)² : Carré d'une somme

C'est le cas où l'on multiplie une somme par elle-même, par exemple $(x + 5)(x + 5)$, qu'on note $(x + 5)^2$.

### La Formule

**$(a + b)^2 = a^2 + 2ab + b^2$**

### Démonstration (Calcul)

On utilise la double distributivité :  
$(a + b)^2 = (a + b)(a + b)$  
$(a + b)^2 = a \times a + a \times b + b \times a + b \times b$  
$(a + b)^2 = a^2 + ab + ab + b^2$  
$(a + b)^2 = a^2 + 2ab + b^2$  

### Démonstration (Géométrie)

On dessine un grand carré dont le côté mesure $(a + b)$.
L'aire de ce grand carré est donc **$(a + b)^2$**.

<img src="./img/identite-1.jpeg" alt="alt" width="250">

On peut aussi voir que ce grand carré est composé de quatre parties :

* Un carré de côté $a$ (son aire est $a^2$)
* Un carré de côté $b$ (son aire est $b^2$)
* Deux rectangles de côtés $a$ et $b$ (chacun a une aire de $ab$)

L'aire totale est la somme de ces parties : $a^2 + b^2 + ab + ab$.
En simplifiant, on obtient : **$a^2 + 2ab + b^2$**.

### Exemples (Développer)

* $(x + 3)^2$
  * $a = x$
  * $b = 3$
  * Résultat : $x^2 + 2(x)(3) + 3^2 = x^2 + 6x + 9$

* $(2y + 4)^2$
  * $a = 2y$
  * $b = 4$
  * Résultat : $(2y)^2 + 2(2y)(4) + 4^2 = 4y^2 + 16y + 16$

---

## 3. L'identité (a - b)² : Carré d'une différence

C'est le cas où l'on multiplie une différence par elle-même, par exemple $(x - 7)(x - 7)$, qu'on note $(x - 7)^2$.

### La Formule

**$(a - b)^2 = a^2 - 2ab + b^2$**

### Démonstration (Calcul)

On fait attention aux signes :  
$(a - b)^2 = (a - b)(a - b)$  
$(a - b)^2 = a \times a + a \times (-b) + (-b) \times a + (-b) \times (-b)$  
$(a - b)^2 = a^2 - ab - ab + b^2$  
$(a - b)^2 = a^2 - 2ab + b^2$  

### Démonstration (Géométrie)

On part d'un grand carré de côté $a$. Son aire est **$a^2$**.
On veut trouver l'aire du carré de côté $(a - b)$, qui est **$(a - b)^2$** (la zone jaune sur l'image).

<img src="./img/identite-2.jpeg" alt="alt" width="250">

On peut le voir par soustraction :

1. On prend le grand carré d'aire $a^2$.
2. On enlève le rectangle "du haut" (d'aire $a \times b$).
3. On enlève le rectangle "du côté" (d'aire $a \times b$).
4. En faisant $a^2 - ab - ab$, on a enlevé le petit carré de coin (d'aire $b^2$) **deux fois** !
5. Il faut donc le "rajouter" une fois pour compenser.

Ce qui donne la formule : $(a - b)^2 = a^2 - 2ab + b^2$.

### Exemples (Développer)

* $(x - 5)^2$
  * $a = x$
  * $b = 5$
  * Résultat : $x^2 - 2(x)(5) + 5^2 = x^2 - 10x + 25$

* $(3z - 1)^2$
  * $a = 3z$
  * $b = 1$
  * Résultat : $(3z)^2 - 2(3z)(1) + 1^2 = 9z^2 - 6z + 1$

---

## 4. L'identité (a + b)(a - b) : Différence de deux carrés

C'est le cas où l'on multiplie une somme par sa différence.

### La Formule

**$(a + b)(a - b) = a^2 - b^2$**

### Démonstration (Calcul)

Les termes du milieu s'annulent :  
$(a + b)(a - b) = a \times a + a \times (-b) + b \times a + b \times (-b)$  
$(a + b)(a - b) = a^2 - ab + ab - b^2$  
$(a + b)(a - b) = a^2 - b^2$  

### Démonstration (Géométrie)

<img src="./img/identite-3.jpeg" alt="alt" width="250">

1. On part d'un grand carré de côté $a$ (aire $a^2$).
2. On lui enlève (on "coupe") un petit carré de côté $b$ (aire $b^2$) dans un coin.
3. L'aire de la zone qui reste (en forme de "L" sur l'image) est donc $a^2 - b^2$.
4. Maintenant, on réorganise cette forme en "L" : on la coupe en deux rectangles.
5. On "pivote" l'un des rectangles pour le coller à l'autre.
6. On obtient un nouveau, grand rectangle.
    * Sa hauteur est $(a - b)$.
    * Sa largeur est $(a + b)$.
7. L'aire de ce nouveau rectangle est $(a + b)(a - b)$.

Comme c'est la même aire que celle de départ, on a bien l'égalité :
$a^2 - b^2 = (a + b)(a - b)$

### Application (Développer ET Factoriser)

C'est la formule la plus importante pour **factoriser** (transformer une somme/différence en produit).

* **Exemple (Développer) :**
  * $(x + 9)(x - 9) = x^2 - 9^2 = **x^2 - 81**$

* **Exemples (Factoriser) :**
  * $y^2 - 25$
    * $a^2 = y^2 \implies a = y$
    * $b^2 = 25 \implies b = 5$
    * Résultat : **$(y + 5)(y - 5)$**
  * $49 - z^2$
    * $a^2 = 49 \implies a = 7$
    * $b^2 = z^2 \implies b = z$
    * Résultat : **$(7 + z)(7 - z)$**
  * $4x^2 - 36$
    * $a^2 = 4x^2 \implies a = 2x$
    * $b^2 = 36 \implies b = 6$
    * Résultat : **$(2x + 6)(2x - 6)$**

---

## 5. Résumé à retenir

| Quand l'utiliser ? | Expression de départ | Formule |
| :--- | :--- | :--- |
| Carré d'une somme | $(a + b)^2$ | $a^2 + 2ab + b^2$ |
| Carré d'une différence | $(a - b)^2$ | $a^2 - 2ab + b^2$ |
| Différence de 2 carrés | $(a + b)(a - b)$ | $a^2 - b^2$ |

**Attention :** $(a + b)^2$ n'est **JAMAIS** égal à $a^2 + b^2$ !

## 6. Exercices d'application

### Exercice 1 : Développer

Utiliser les identités remarquables pour développer les expressions suivantes :

1. $(x + 8)^2$
2. $(y - 6)^2$
3. $(z + 10)(z - 10)$
4. $(2a + 3)^2$
5. $(4b - 1)^2$

### Exercice 2 : Factoriser

Utiliser l'identité remarquable $a^2 - b^2$ pour factoriser :

1. $x^2 - 100$
2. $y^2 - 9$
3. $64 - z^2$
4. $9x^2 - 1$
5. $16y^2 - 81$

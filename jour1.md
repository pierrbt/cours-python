# COURS PYTHON

### JOUR n°1

---

#### Notion du jour : les variables

1. Que sont les variables ?
   Les variables sont des façons de stocker temporairement des données, et d'y accéder à n'importe quel moment dans
   l'exécution du programme, on peut s'en servir pour stocker pleins de choses différentes, le résultat d'un calcul, le
   prénom de l'utilisateur, sa réponse à une question, une liste des restaurants dans une ville ou des messages dans un
   chat. Bref, on peut TOUT stocker.

2. Et comment tu la créées ta machin ? Pour créer des variables, il faut deux choses, un nom ( oui oui même aux
   variables il faut leur trouver un nom, on ne va pas l'appeler Evan, il faut trouver quelque chose qui la représente )
   , et il faut aussi une valeur, qui sera la valeur stockée dans la variable. Donc pour créer une variable, ça
   ressemble à ça :

```python
age = 15
```

***INFOS :*** Nous ne pouvons pas écrire les valeurs n'importe comment, il faut différencier trois catégories
principales : les nombres entiers `int` qui stockent un nombre entier comme `8` ou `58`, les nombres flottants
appelés `float` comme `5.15` ou `85.45` qui stockent un nombre à virgule et finalement les chaînes de
caractères `string` qui stockent des textes, attention là nuance, pour pouvoir stocker une chaîne, il faut la délimiter
par des signes `'` (apostrophe) ou `"` (guillemets), ce qui donne `'Evan'` ou `'Salut les boss'`.

3. C'est bien de te la créer ta variable mais tu en fais quoi maintenant ?! Et bien on y arrive ! Pour modifier une
   variable, c'est exactement comme pour la déclarer, mais si on veut exécuter une opération dessus, il faut utiliser
   les opérateurs, qu'on verra plus en détail dans le prochain cours mais qui ressemblent à peu près à
   ça `somme = somme + 5`
4. Cette variable, on peut aussi l'utiliser autrement que seulement pour faire des calculs, on peut l'afficher (pour
   l'instant en console mais on pourrait aussi le faire dans une belle interface ! MAIS IL EST BELLE MA CONSOLE !! non
   ... ). Pour ce faire on va utiliser la variable prenom qui a été définie à Evan comme ceci `prenom = 'Evan'`. Pour
   l'afficher, on utilise la fonction `print()` qui sert à imprimer dans la console, nous verrons plus en détails les
   fonctions de base dans le chapitre 3. Cela donne donc :

```python
print('Votre prenom est ' + prenom)
```

#### Petit projet

Comme tu connais maintenant les **variables**, tu peux t'amuser à les manipuler simplement, pour ce faire, je te donne
un petit defi :
Tu as la variable `adjacent1 = 8.824` et `adjacent2 = 12.984`, définit la variable `hypotenuse` en trouvant sa valeur
grâce au théorème de Pythagore, pour faire des puissances, utilise le symbole `**` (deux étoiles) et utilise des
parenthèses pour délimiter tes calculs

***RAPPEL :*** la racine carrée est la même chose que puissance 1/2, donc tu peux faire `**0.5` pour faire la racine
carrée, à la fin du programme, tu écriras "L'hypoténuse est égale à " et là le résultat, envoie-moi le programme que tu
auras fait 😉

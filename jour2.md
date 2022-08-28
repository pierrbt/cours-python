# COURS PYTHON
### JOUR n°2

---

#### Notion du jour : les opérateurs

1. Que sont les opérateurs ? Les opérateurs sont des façons de manipuler les variables à sa guise, en effectuant dessus des calculs mathématiques. Tu en as déjà effectué dans le dernier chapitre en utilisant `**` pour faire la puissance.
2. Comment on les utilise ? Et bien c'est très simple, il suffit d'utiliser les signes opératoirs classiques : 

`+` fait une addition : par exemple on peut faire `8+5`

`-` fait une soustraction
`*` fait une multiplication

`/` fait une division

`**` fait une puissance

`//` fait une division entière

`%` fait le module, c'est à dire le reste de la division entière, par exemple `5 % 2 = 1`

Ceci sont les opérations simples, on peut manipuler des nombres `8 + 2` mais aussi des variables `age ** taille` et donc si on veut faire une multiplication on peut faire `resultat = facteur * multiplicateur`

Mais on peut faire plus simple encore, si on veut directement effectuer une opération sur une variable directement, on peut utilier les opérateurs suivis d'un signe `=`, si on veut ajouter 100 à une variable, on peut faire :

```python
somme += 100
```

Cela permet de remplacer un long calcul comme `somme = somme + 100`, ça marche aussi mais c'est bien moins classe.

3. **Entrainement :** Maintenant que tu as découvert les opérateurs, je te conseille d'expérimenter ces calculs dans la console Python, pour que tu apprennes à utiliser chacuns d'eux pour l'instant sans réel objectif mais déjà pour les apprendre car ils seront très utile pour la suite. Ceci est un exemple pour expliquer le fonctionnement des opérateurs simples :
```python
a = 10
b = 4
res = a + b; # addition
print("a+b : ", res)

res = a - b; # soustraction
print("a-b :", res)

res = a * b; # multiplication
print("a*b :", res)

res = a / b; # division
print("a/b : ", res)

res = a % b; # Module
print("a mod b :", res)

res = a // b; # division entière
print("a // b :", res)
```



#### Petit projet
Comme tu connais maintenant les **opérateurs**, tu peux t'amuser à faire un petit programme qui demande à l'utilisateur deux nombres, et qui lui donne le résultat de la division entière ainsi que le reste, pour ce faire tu vas utiliser les opérateurs ainsi que deux fonctions, `print()` et `input()`, que tu verras plus en détail dans le prochain cours

Pour utiliser `print()` il suffit de séparer les différentes chaînes par une virgule, un petit exemple :
```python
age = 10
print('Vous avez ', age, ' ans')
```
`RÉSULTAT : Vous avez 10 ans`

Pour utiliser la fonction `input()` il faut mettre la question entre parenthèse entre apostrophes ou oublie pas et elle renverra ce que l'utilisateur a écrit, mais au format d'une chaîne de caractère, donc si tu veux un nombre il faut utiliser `int()` parce que la chaîne `'8'` est différente de l'entier `8`, tu verras ça dans le prochain chapitre, un petit exemple : 
```python
reponse = int(input('Donnez la réponse : '))
```
Voilà, tu as tous ce qu'il faut pour faire ce petit programme, tu me l'enverras pour que je vérifies.
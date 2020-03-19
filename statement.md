# Quiz Python Cyber

Bienvenue et bonne chance !

## Question 1 : Les commentaires

?[Comment commenter du code Python ?]
- [ ] En utilisant `//` devant le commentaire à écrire.
- [X] En utilisant `#` devant le commentaire à écrire.
- [ ] En utilisant `--` devant le commentaire à écrire.
- [ ] En utilisant `%` devant le commentaire à écrire.

## Question 2 : Déclaration de variable

?[Comment déclarer une variable avec comme valeur l'entier 35 ?]
- [X] `valeur = 35`
- [ ] `valeur = '35'`
- [ ] `35 -> valeur`
- [ ] `set valeur to 35`

## Question 3 : Les opérations entre variables numériques

Soit le code suivant :

```python
solde_compte = 150
retrait = 20

# nouveau_solde ?
```

?[Comment calculer le nouveau solde ?]
- [ ] `nouveau_solde <= solde_compte - retrait`
- [ ] `solde_compte - retrait => nouveau_solde`
- [ ] `nouveau_solde # solde_compte - retrait`
- [X] `nouveau_solde = solde_compte - retrait`

## Question 4 : Modulo

?[Que permet de faire l'opérateur `%` (le modulo) ?]
- [ ] D'avoir le résultat d'une division entière.
- [ ] De concaténer des chaines de caractères.
- [ ] D'afficher le nombre de chiffre après la virgule d'un chiffre.
- [X] De calculer le reste de la division entière.

## Question 5 : Les commentaires

?[Comment commenter du code Python ?]
- [ ] En utilisant `//` devant le commentaire à écrire.
- [X] En utilisant `#` devant le commentaire à écrire.
- [ ] En utilisant `--` devant le commentaire à écrire.
- [ ] En utilisant `%` devant le commentaire à écrire.

## Question 6 : Concaténer des chaînes de caractères

?[Comment concaténer des chaînes de caractères ?]
- [ ] `formateurs = 'Nicolas' && 'Mathieu'`
- [X] `formateurs = 'Nicolas' + 'Mathieu'`
- [ ] `formateurs = 'Nicolas' // 'Mathieu'`
- [ ] `formateurs = 'Nicolas' % 'Mathieu'`

## Question 7 : Comparer des chaînes de caractères

Soit le code suivant :

```python
line_1 = 'I love cyber'
line_2 = 'I love cyber'

print(line_1 == line_2)
```

?[Qu'affiche ce code ?]
- [X] `True`
- [ ] `False`
- [ ] `0`
- [ ] `1`

## Question 8 : Les conditions

Soit le code suivant :

```python
age = 2

if age < 0 :
  message = "merci d'entrer un age valide (positif)"

elif age < 3 :
  message = "tarif : gratuit"

elif age < 18 :
  message = "tarif : réduit"

elif age > 65 :
  message = "tarif : réduit"
```

?[Que vaut la variable `message` après son exécution ?]
- [ ] `merci d'entrer un age valide (positif)`
- [X] `tarif : gratuit`
- [ ] `tarif : réduit`
- [ ] `tarif : normal`

## Question 9 : Les fonctions

Soit la fonction suivante :

```python
def dire_bonjour(prenom):
  return "Bonjour " + prenom
```

?[Comment appeler la fonction avec mon prénom ?]
- [ ] `dire_bonjour(prenom <= Nicolas)`
- [ ] `dire_bonjour(set prenom to Nicolas)`
- [ ] `dire_bonjour(prenom = Nicolas)`
- [X] `dire_bonjour('Nicolas')`

## Question 10 : Les listes

?[Comment déclarer une liste de chaînes de caractères ?]
- [ ] `eleves = [sam, bob, al, odile]`
- [ ] `eleves = {'sam', 'bob', 'al', 'odile'}`
- [ ] `eleves = ('sam', 'bob', 'al', 'odile')`
- [X] `eleves = ['sam', 'bob', 'al', 'odile']`

## Question 11 : Les boucles

?[Quelle est la différence entre une boucle `for` et `while` ?]
- [ ] Le `for` ne peut pas s'utiliser dans une fonction, le `while` si.
- [ ] Le `for` ne peut pas boucler sur des listes, le `while` si.
- [X] Le `for` s'utilise pour un nombre connu d'itérations, le `while` avec une condition d'arrêt particulière.
- [ ] Le `for` s'utilise seulement sur des listes, le `while` pas forcément.

## Question 12 : Ecrire dans la console

?[Comment écrire dans la console ?]
- [X] `print('Salut')`
- [ ] `echo('Salut')`
- [ ] `println('Salut')`
- [ ] `printf('Salut')`

## Question 13 : Lire un fichier

Soit les fragments de codes suivants :

```python
# Fragment 1
print(f.readline('convention.md'))

# Fragment 2
open('convention.md', 'r')
print(readline())

# Fragment 3
f = open('convention.md', 'r')
print(f.readline())

# Fragment 4
f = read('convention.md')
print(f.printline())
```

?[Quel fragment est valide pour lire et afficher la première ligne du fichier `convention.md` ?]
- [ ] Fragment 1
- [ ] Fragment 2
- [X] Fragment 3
- [ ] Fragment 4

## Question 14 : Libération des ressources

?[Que faut-il faire une fois que l'on a fini d'utiliser un fichier ?]
- [ ] `f.release()`
- [X] `f.close()`
- [ ] `f.free()`
- [ ] `f = null`

## Vous pouvez tester du code ici

```python runnable
# Vous pouvez tester ici
```

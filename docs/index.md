# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


# Documentation de TP : Introduction à Python

## Introduction

Python est un langage de programmation interprété, de haut niveau et polyvalent. Il est largement utilisé dans le développement web, l'analyse de données, l'intelligence artificielle et bien plus encore.

## Installation de Python

Pour installer Python, suivez les étapes ci-dessous :

1. Rendez-vous sur le site officiel : [python.org](https://www.python.org/downloads/).
2. Téléchargez la dernière version pour votre système d'exploitation.
3. Suivez les instructions d'installation.

## Votre premier programme Python

Créez un fichier nommé `helloworld.py` et ajoutez le code suivant :

```python
print("hello world !")
```

Exécutez le programme dans votre terminal avec la commande :

```bash
python helloworld.py
```

## Types de données

Python supporte plusieurs types de données :

- **Entiers** : `x = 5`
- **Flottants** : `y = 3.14`
- **Chaînes de caractères** : `name = "Alice"`
- **Booléens** : `is_active = True`

## Structures de contrôle

### Conditionnelles

Les instructions conditionnelles permettent d'exécuter du code en fonction de certaines conditions.

```python
if x > 10:
    print("x est supérieur à 10")
else:
    print("x est inférieur ou égal à 10")
```

### Boucles

Les boucles permettent de répéter des actions.

#### Boucle `for`

```python
for i in range(5):
    print(i)
```

#### Boucle `while`

```python
while x < 10:
    x += 1
```

## Fonctions

Les fonctions permettent de regrouper du code réutilisable.

```python
def saluer(nom):
    print(f"Bonjour, {nom} !")

saluer("Alice")
```

## Conclusion

Python est un langage puissant et accessible qui permet de réaliser une multitude d'applications. Ce TP a couvert les bases de Python, mais il existe encore beaucoup à explorer !

## Ressources supplémentaires

- [Documentation officielle de Python](https://docs.python.org/3/)
- [W3Schools - Python Tutorial](https://www.w3schools.com/python/)
- [Codecademy - Learn Python](https://www.codecademy.com/learn/learn-python-3)

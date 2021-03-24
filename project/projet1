# Lecture d'un CSV

Ce project à pour but de te faire apprendre comment ouvrir un fichier CSV (comma separated values) sur ton ordinateur, le lire, faire une manipulation, puis ensuite, sauvegardé ces manipulations dans un nouveau fichier.

## Lectures préliminaire

* [Strings](https://www.tutorialspoint.com/python3/python_strings.htm) (15 min)
* [IF](https://www.tutorialspoint.com/python3/python_if_statement.htm) (5 min)
* [IF/ELSE](https://www.tutorialspoint.com/python3/python_if_else.htm) (15 min)
* [Looping](https://www.tutorialspoint.com/python3/python_loops.htm) (5 min)
* [For Loops](https://www.tutorialspoint.com/python3/python_for_loop.htm) (10 min)

Ceci devrait couvrir tout ce que as de besoin. Ensuite c'est de comprendre les "imports" ou les "modules" en Python, mais t'as pas besoin de trop comprendre là dessus pour t'en servir.

* [Modules](https://www.tutorialspoint.com/python3/python_modules.htm) (15 min) (Pas besoin de tout comprendre)

## Le Programme
### Création de ton projet

Dans PyCharm, créé toi un nouveau projet Python 3, pis met tout les configurations par défaut. Tu va ensuite te créé un nouveau fichier que tu va appaler "main".

### Lectures d'un fichier CSV

Il y a un fichier csv ici que tu peux télécharger et le mettre dans ton projet python. C'est une liste de livre avec leurs ISBN. Mais les ISBN ont une lettre supplémentaire comme erreure, alors tu va devoir corrigé celà, avec un peu de python ça va être très facile.

Si tu veux de la lecture sur l'ouverture d'un fichier, voici un [line](https://www.tutorialspoint.com/python3/python_files_io.htm)

Mais globallement, tu va vouloir faire au début de ton fichier

```python
import os
```

Ceci va importer le module "os" qui veux dire "operating system", dont c'est plein d'utilitaire pour intéragir avec ton système d'exploitation, tel que la manipulation des fichiers.

Ensuite pour ouvrir un fichier, tu va faire ceci:

```python
myFile = open("livres.csv", "rb")
```

Ceci va créé une variable, qui s'appel myFile. Cette variable est une abstraction de ton fichier et tu va pouvoir appeler des opérateurs dessus. La fonction "open" qui suit l'assignement de la variable, prend 2 paramètre. Le premier est le nom du fichier, et le deuxième est le mode d'ouverture. Présentement on veux lire le fichier, donc on l'ouvre en "read-only", dont "rb". Si nous voulions écrire dans un fichier, il faudrait l'ouvrir un "write" où "wb" en tant que paramètre.

### Lectures du fichier, ligne par ligne.

### Manipulation d'une ligne dans ton for loop

### Écriture dans un nouveau fichier

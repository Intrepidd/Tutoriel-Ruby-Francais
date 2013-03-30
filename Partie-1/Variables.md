Les variables
==============

Pour les personnes débutant la programmation, une variable permet de stocker une valeur en mémoire, et de pouvoir y accéder simplement par la suite.

En ruby, la syntaxe est la suivante :

    variable = valeur

Stockons par éxemple la valeur ``Thomas`` dans une variable qu'on appellera ``prenom``

    prenom = "thomas"
    => "thomas"

Parfait, on peut maintenant accéder à notre variable par son nom :

    prenom
    => "thomas"

De même avec un nombre :

    age = 42
    => 42

Nous avons donc crée deux variables, une contenant une chaîne, l'autre contenant un nombre entier.

Une fois crées, les variables peuvent s'utiliser comme si il s'agissait de la valeur qu'elles stockent.

Par exemple, stockons 2 nombres dans 2 variables, et stockons leur addition dans une troisième variable :

    nombre1 = 13
    nombre2 = 29
    addition = nombre1 + nombre2

Nous pouvons ensuite accéder au résultat dans la variable ``addition``

    addition
    => 42

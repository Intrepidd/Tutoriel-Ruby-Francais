Premières instructions aver irb
===============================

Maintenant que ruby est installé sur votre machine, il est temps de faire nos premiers pas.

Ruby fournit un utilitaire baptisé **IRB**, qui permet d'évaluer du code ruby de facon interactive et d'afficher le résultat.

C'est parti, on lance irb, simplement en lancant la commande ``irb`` en console.

On se retrouve avec une invite de commandes :

    2.0.0-p0 :001 >

## Opérations Arithmétiques

Ruby supporte les opérations arithmétiques comme de nombreux langages, on essaie rapidement :

    1 + 1
    => 2

    10 / 2
    => 5

    3 * 3
    => 9

    11 % 2
    => 1


## Hello world

Nous sommes Français, mais nous allons éviter de blasphémer en affichant "Bonjour le monde".

En Ruby, la fonction ``puts`` est utilisée pour afficher du texte sur la sortie standard. Cette fonction prend une chaine de caractères en paramètre.

En Ruby, une chaine de caractères peut être définie avec des guillemets doubles ``"`` ou des simples ``'``, nous verrons la différence un peu plus tard.

On peut appeler une fonction avec la même syntaxe qu'en PHP, en C / ++ :

    puts("Hello world")
    Hello world
    => nil

Que vient il de se passer ?

On a appelé la méthode ``puts`` avec la chaine ``"hello world"`` en paramètre.
On voit que ``"Hello world"`` a bien été écrit.

Que signifie ``=> nil`` ?

Il s'agit du retour de méthode, la méthode puts retourne ``nil``, il s'agit d'une valeur indiquant le néant, on peut le comparer à ``null`` en php / java, ou à ``NULL`` en C / C++.

### Et sans les parenthèses ?

Il est possible de produire le même résultat en omettant les parenthèses :

    puts "Hello world"
    Hello world
    => nil

Il s'agit la d'un des nombreux sucres syntaxiques de Ruby

## Jouons un peu avec les chaines

Comme montré plus haut, il est possible de créer une chaine de caractères avec des guillemets.

    "test"
    => "test"

Ruby est un langage qui se veut intuitif, voyez par vous même, ajoutons deux chaines :

    "Hello" + " world"
    => "Hello world"
    
Et si on voulait afficher 5 fois la chaine ``"toto"`` ?

    "toto" * 5
    => "totototototototototo"
    
Mélangons les 2 :

    "na" * 10 + " Batman !"
    => "nananananananananana Batman !"

Il est possible d'effectuer des opérations sur une chaine en effectuant un appel de méthode dessus.

Par exemple, il existe une méthode ``size`` permettant de récupérer la taille de la chaine, elle s'appelle en faisant ``chaine.size``

Si vous n'êtes pas à l'aise avec la programmation orientée objet, **pas de panique**, prenez ceci pour acquis pour le moment, le tutoriel couvrira cette partie plus tard.

Testons donc :

    "Hello".size
    => 5

Nous venons d'appeler la méthode ``size`` sur la chaine ``"hello"``

Cette méthode ne prend pas de paramètre, nous aurions pu aussi l'appeler avec des parenthèses : ``"hello".size()`` mais par convention, il est préférable de les omettre.

Pour l'exemple, voici d'autres appels de méthodes :

    "hello".capitalize
    => "Hello"
    "hello".upcase
    => "HELLO"
    "HELLO".downcase
    => "hello"

Vous savez maintenant manipuler basiquement des chaines !


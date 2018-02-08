# Cours programmation - Algorithmique 1 Bases

## Algorithmique
### Introduction


### Hello World

```PSeudoCode
afficher "Hello World!";
```

```JavaScript
alert('Hello world');
alert("Hello world");
//ou
window.alert('Hello world');
window.alert("Hello world");
//ou
console.log('Hello world!');
console.log("Hello world!"");
```

```Python
#En Python 3
print('Hello world!')
print("Hello world!")
print("""Hello world!""")
#ou
#En Python 2
print 'Hello world!'
print "Hello world!"
print """Hello world!"""

```

```PHP
<?php
echo "Hello world!";
echo("Hello world!");
//ou
print "Hello world!";
print("Hello world!");
?>
```

```C
#include <stdio.h>
#include <stdlib.h>

int main()
{
  printf("Hello world!");
  return 0;
}
```

```Java
public static void main(String[] args){
  System.out.print("Hello World !");
}
```

### Commentaires
```PSeudoCode
Généralement
// Une Seule Ligne

/* Sur
Plusieurs
lignes */

Parfois
# Mon commentaire
```

```JavaScript
// Une Seule Ligne

/* Sur
Plusieurs
lignes */
```

```Python
# Mon commentaire sur une seule ligne

"""
Un gros paragraphe
Avec un énorme commentaire
Qui prends plein de place.
OK ?
"""
```

```PHP
// Une Seule Ligne

/* Sur
Plusieurs
lignes */
```

```C
// Une Seule Ligne

/* Sur
Plusieurs
lignes */
```

```Java
// Une Seule Ligne

/* Sur
Plusieurs
lignes */
```

### Variables
#### Déclaration de variables
```PSeudoCode
var TYPE maVariable := Valeur;
var TYPE maVariable <- Valeur;
```

```JavaScript
var maVarable = Valeur;
```

```Python
maVariable = Valeur;
```

```PHP
$maVariable = Valeur;
```

```C
TYPEVAR maVariable = Valeur;
```

```Java
TYPEVAR maVariable = Valeur;
```

#### Déclaration de constantes
const maCst = val TYPE
const pi = 3.14 REAL

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```


#### Types de variables
##### Variables Numériques
* Entier | INT | 0, 4, 12, 1234, 9974116546
* Réel | REAL | 1.5, 3.1416 | 0.0000000000002 | 4589.166894109

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```

##### Variables Textuelles
* Carctère | CAR | 'a', 't', 'm', 'G', '&', '?''
* Chaine de caractère | STR | 'Hello', 'World', 'Hello World!', 'Coucou \n Beuh!'

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```


##### Variables Booléennes
* Vrais | TRUE
* Faux | FALSE

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```

##### Variables Tableau
VAR identificateur :

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```




### Expressions
* Opérateurs arithmétique + - * / %
* Opérateurs logiques NON ! OU || et &&
* Opérateurs relationnels = < > <= => 
* Opérateurs sur les chaines & © concaténation
Alt+0169

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```

### Priorité des opérateurs
1. () Parenthèses
2. ^ élévation à la puissance
3. * / multiplications et divisions
4. + - additions et soustractions

Table de vérité

| A | B | A AND B | A OR B |
| T | T | T | T |
| T | F | F | T |
| F| T | F | T |
| F | F | F | F |

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```

### Instructions conditionnelles

SI condition ALORS
    Suite d'instruction
SINON
    Suite d'instruction
FINI

SI condition ALORS
    Suite d'instruction
SINON SI condition ALORS
    Suite d'instruction
SINON SI condition ALORS
    Suite d'instruction
SINON
    Suite d'instruction
FINI

CAS OU ma Variable VAUT
    1 : faireCa
    2 : faireCa
    3 : faireCa
    4 : faireCa
    Autre : faireCa

var caractere
DEBUT
    SI caractere >= 'A' && caractere <='Z'
        CAS OU caractere vaut 'A', 'E', 'I', 'O', 'U', 'Y'
            ECRIRE("C'est une voyelle")
        FINCAS
    SINON
        ECRIRE("ce n'est pas une majusccule")
    FINSI
FIN

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```

### Boucles

TANTQUE condition
    instruction
FIN TANTQUE

REPETER
    instruction
JUSQU'A condition

POUR compteur ALLANT DE début A fin FAIRE
    instruction
FIN POUR

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```

### Fonctions
FONCTION maFonction(parametres)
DEBUT
    instructions
    Retourner(resultat)
FIN

```JavaScript
Contenu
```

```Python
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```Java
Contenu
```






===============================================================================
**Examples**

```JavaScript
Contenu
```

```Python
Contenu
```

```Ruby
Contenu
```

```PHP
Contenu
```

```C
Contenu
```

```C++
Contenu
```

```C#
Contenu
```

```Java
Contenu
```

```Cobol
Contenu
```

```Fortan
Contenu
```

```VBA
Contenu
```




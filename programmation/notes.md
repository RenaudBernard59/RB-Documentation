# Cours programmation - Algorithmique 1 Bases

## Algorithmique
### Introduction
### Afficher : Hello World
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

### Ecrire des Commentaires
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

```SQL
Contenu
```

### Variables
#### Déclaration de Variables
```PseudoCode
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

#### Déclaration de Constantes
const maCst = val TYPE
const pi = 3.14 REAL
```PseudoCode


```

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
##### Variables de TypeNumériques
* Entier | INT | 0, 4, 12, 1234, 9974116546
* Réel | FLOAT | 1.5, 3.1416 | 0.0000000000002 | 4589.166894109

```PseudoCode
//Entier (Entier Naturel N)
var INT maVar = 1234;

//Petits Entier | Small
var SHORT maVar = 4;

//Long Entier | Long
var LONG maVar = 9974116546;

//Flottant (Réel R)
var FLOAT maVar = 1.5;

//Grand Flottant | Double
var DOUBLE maVar = 4589.166894109
```

```JavaScript
//Entier (Entier Naturel N)
var unEntier = 456;

//Flottant (Réel R)
var unFlotant = 1.414;
```

```Python
//Entier (Entier Naturel N)
unEntier = 456;

//Flottant (Réel R)
unFlotant = 1.414;
```

```PHP
//Entier (Entier Naturel N)
$unEntier = 456;

//Flottant (Réel R)
$unFlotant = 1.414;
```

```C
Contenu
```

```Java
//Très-Petits Entier (1 octet) (type simple)
byte maVar;

//Petits Entier (2 octet) (type simple)
short maVar;

//Entier (4 octet) (type simple)
int maVar;

//Grand Entier(8 octet) (type simple)
long maVar;

//Flottant (type simple)
float maVar;

//Grand Flottant (type simple)
double maVar;

//Grand Entier (type Objet import from Math)
BigInteger maVar;

//Grand Décimal (type Objet from Math)
BigDecimal maVar;

//Wrappers Byte | Short | Integer | Long ...

```

```SQL
Contenu
```
##### Variables Textuelles
* Carctère | CHAR | 'a', 't', 'm', 'G', '&', '?''
* Chaine de caractère | STR | 'Hello', 'World', 'Hello World!', 'Coucou \n Beuh!'

//Caractère |Caractere

//Chaîne de Caractère | String

```PseudoCode


```
```JavaScript
//Chaîne de Caractère | String
var maChaineDeCaractere = "Mon message !";
var maChaineDeCaractere = 'Mon message !';
```

```Python
//Chaîne de Caractère | String
maChaineDeCaractere = "Mon message !";
maChaineDeCaractere = 'Mon message !';
maChaineDeCaractere = """Mon message !""";
```

```PHP
$maChaineDeCaractere = "Mon message !";
$maChaineDeCaractere = 'Mon message !';
```

```C
Contenu
```

```Java
//Caractère |Caractere (type simple)
char maVar;

//Chaîne de Caractère | String (type Objet)
String maVar;
```

```SQL
Contenu
```

##### Variables Spécialisés




##### Variables Booléennes
* Vrais | TRUE
* Faux | FALSE

```PseudoCode


```

```JavaScript
var unBooleen = true;
var unBooleen = false;
var nonDefini = undefined; 
```

```Python
unBooleen = True;
unBooleen = False;
nonDefini = ... 
```

```PHP
$unBooleen = true;
$unBooleen = false;
$nonDefini = NULL;
```

```C
Contenu
```

```Java
boolean maVar = true;
boolean maVar = false;
```

```SQL
Contenu
```

##### Variables Tableau
VAR identificateur :
```PseudoCode


```

```JavaScript
//Ancienne syntaxe de tableau
var tableau = new Array();

//Avec du contenu
var tableau = new Array(43, 12.5, "a", "azerty", "42");

//Autre notation
var tableau = []

//Autre notation avec du contenu
var tableau = [43, 12.5, "a", "azerty", "42"];

//3ème applet
tableau[2] = "a";

//Tableau associatif
var tableauAssociatif = new Array();
scores["Physique"] = 12;
scores["Chimie"] = 14;
scores["Maths"] = 11;
scores["SVT"] = 18;
scores["Français"] = 8;.

//Accès au tableau
tableauAssociatif['SVT'] = 18;
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

```SQL
Contenu
```

##### Objets littéraux
```PseudoCode


```

```JavaScript
//Créer un objet
var monObjet = {
Physique: 12,
Chimie: 14,
Maths: 11,
SVT: 18,
Français: 8
}

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

```SQL
Contenu
```
### Expressions
* Opérateurs arithmétique + - * / %
* Opérateurs logiques NON ! OU || et &&
* Opérateurs relationnels = < > <= => 
* Opérateurs sur les chaines & © concaténation
Alt+0169
```PseudoCode


```

```JavaScript
//Addition

//Soustraction

//Multiplication

//Division

//Modulo

//Logique OU

//Logique ET

//Logique NON

//Est égal

//Est strictement égal

//Est inférieur

//Est supérieur

//Est inférieur ou égal

//Est supérieur ou égal


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

```PseudoCode


```

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

```PseudoCode


```

```JavaScript
Contenu
```

```Python
if a > b:
    print(resultat)
else:
    print(resultat)

if a > b:
    print(resultat)
elif a < b:
    print(resultat)
else:
    print(resultat)

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

```PseudoCode


```

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

```PseudoCode


```

```JavaScript
function maFonction(arg1, arg2,...)
function maFonction(arg1, arg2,...) {
    //Le code de ma fonction
    return resultat //Eventuel
}

var uneFonction = maFonction(arg)

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

```SQL
Contenu
```


#Hello World
```C Fichier en .c
#include <studio.h>

int main(int rgc, chr *argv[])
{
  printf("Hello world!\n");
  return 0;
}
```

#Commentaires
```C
// Commentaire uniligne

/* un
Commentaire
multiligne */
```

#Minimal code
```C
#include <studio.h>

//Mon code
// ici
```

#Variables
C : Typage statique, faible et explicite
```C
//Variable ENTIER
int i;
i = 40;

//Constant ENTIER
int m = 10;

//Multi  Variables
int a, b, c=1, d=2;

//Variable locale (dans une fonction)
int main()
{
  int i;
  {
    int j = 20;
    i = j;
  }
  i += 2;
  printf("Résultat: %d", i);
  return 0;
}

//Caractère (1 octet ou 8 bits)
// ie c'est un entier représenter dans ISO-8869-1, iSO-8869-15, CP1252, UTF-8
char = 'z';
char i = 'a';
char i = 97;

//Petit entier (2 octets ou 16 bits)
short int a = -2^15 OR -32768;
short a = 2^15-1 OR 32767;

//Entier (2 octets ou 16 bits)
int a = 280;

//Long entier (4 octets ou 32 bits)
long int a =
long a =

//Entier (8 octets ou 64 bits)
long long int a =
long long a =

//Entier (2 octets ou 16 bits)
int a =

//Entier (2 octets ou 16 bits)
int a =

//Différences entre les petits
signed short a = -32767 TO 32767;
unsigned short a = 0 TO 65535;

//Réel
float a = 3.14;

//Réel long
double a = 3.1416;

//Réel encore plus long
long double a = 301416...;

//Booléen
bool a  = true;
bool a = false

short tableau[10];
short tableau[10] = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9};

tableau[1000] = {};

short tableau2d[10][10] = {};
short tableau3d[10][10][10] = {};

char chaine[] = "Coucou tout le monde";
char chaine[] = {"c", "h", "a", "i", "n", "e", "s"};
char chaine[] = "chaines";


```

#Opérateurs mathématiques


```C
2 + 2 //Vaut 4
2 - 2 //Vaut 0
2 * 2 //Vaut 4
2 / 2 //Vaut 1
Timo + leon // N'existe pas de concaténation en C

//En binaire
true = 1
false = 0

//Opérateur binaire
1 & 1 = 1
1 & 0 = 0
& ET inclusif
| OU inclusif
^ OU exclusif

//Opérateur booléen
true && false

//Affectations de Variables
a = a + b
Vaut
a += b
existe
+=
-=
*=
/=
&=
|=
^=
>>=
<<=

a = a +1;
a += 1;
a ++;

```


IF et ELSE

```C
int a;
if (b == 42) {
  a = 42
} else {
  a = 0;
}
Vaut
int a = (b == 42) ? 42 : 0;

Pré-incrémentation
int i = 0;
i++;
Post-incrémentation
int i = 0, j;
j = i++;

#Opérateurs booléens
#Opérateurs de comparaison
==
!=
>
<
>=
<=
Opérateurs logiques
&&
||
!



```
#Bibliothèques standard


```C
#include <math.h>
a
ceil(a) // Arrondi sup
floor(a) //Arrondi inf
sqrt(a) //Racine
pow(a, 2) //Carré
pow(a, 2.1) //Puissance
exp(a) //Exponentielle
log(a) //Logarithme népérien
log10(a) //Logarithme décimal
M_PI_4 //Pi/4
cos(M_PI_4) //Cossinus Pi/4
sin(M_PI_4) //Sinus Pi/4
tan(M_PI_4) //Tangeante Pi/4
acos(707.107) //ArcCos Pi/4
asin(707.107) //ArcSin Pi/4
atan(1) //ArcTan Pi/4

//Sorties standard
printf(a)
printf("%d", entier)
printf("%o", entierOctal)
printf("%O", entierOctalajuscule)
printf("%x", entierHexadecimal)
printf("%X", entierHexadecimalMajuscule)

//Entrée standard
scanf

int saisirEntier(void)
{
  int a;
  scanf("%d", &a)
  return a;
}

//Demander un Caractère
using char
u

nsigned char saisirCaractere(void)
{
  unsigned char a;
  scanf("%hhc", &a);
  return a;
}


```
#IF ELSE


```C
if (machin == truc)
{
  //true
} else {
  //false
}

if (machin == truc)
{
  //true
} else if (machin > bidule){
  //false mais
} else {
  //false
}

switch (choix)
{
  case 1:
    {
      //Un truc
      break;
    }
  case 2:
    {
      //Un truc
      break;
    }
  case 3:
    {
      //Un truc
      break;
    }
  case 4:
    {
      //Un truc
      break;
    }
  default:
    {
      //tada
      break;
    }



}


```
#Boucle


```C
int i = 0;
while (i != 10) {
  //machin
  i++;
}

do
{
 //Faire çà
}
while (z != 0);


int ;
for (i = 0; i < 10; i++)
{
  //Résultat
}

int i, j, k;
for (i = 0; i < 10; i++)
{
  for (j = 0; j < 10; j++)
  {
    for (k = 0; k < 10; k++)
    {
      //Résultat
    }
  }
}












```

#


```C




```

#


```C




```

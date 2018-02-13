# fiche synthese C

## Variables

### Déclaration:

```c
int nb; //déclaration d'un entier
float reel; //déclaration d'un floattant
char caract; //déclaration d'un caractère
```

### Initialisation:

```c
int nb=0; //exemple d'initialisation d'une variable
```

## Entrées / Sorties
>Attention : Un printf ou un scanf doit posseder autant de % que de ,


### Affichage à l'écran : printf

* exemple
```c
printf("La valeur de l'entier est : %d", nb)// afficher la valeur d'un entier
```


### Lecture au clavier : scanf

* exemple

```c
scanf("%d", &nb); // rentrer un entier
```

## Structures de Contrôles

### Boucles 
 
* For :

```c
int i;

for(i=0, i<10, i++)                      //Boucle qui va passer par toutes les valeurs de i pour i allant de 0 à 9
{
 printf("la variable i vaut : %d", i);   //Instruction de la boucle qui affiche la valeur de i
}
```

* While :

```c
int i = 0;

while(i<10)                               // Boucle qui va passer toutes les valeurs de i jusqu'à 9
{
printf("la variable i vaut : %d", i);     //Instruction de la boucle qui affiche la valeur de i
i++;                                      
}
```
Il est aussi possible de faire un do while par exemple si on demande à l'utilisateur d'entrer un nombre positif : 

```c
int entier;

do
{
printf("entrer un nombre positif");
scanf("%d", &entier);
}while(entier < 0)

```

### tests

* Switch : exemple d'une réduction de 10% par enfant sur le prix total (jusqu'à 3 enfants)
```c
int nb_enfants;
printf("entrer nombre enfants");
scanf("%d", &nb_enfants);

switch(nb_enfants)
{

case 1: printf("réduction de 10%");
        break;
        
case 2: printf("réduction de 20%");
        break;
        
case 3: printf("réduction de 30%");
        break;
       
default: printf("aucune réduction");
         break;
}

```

* If : exemple

```c
int nb;
if(nb>0)
{
printf("%d est positif", nb);
}
else if(nb<0)
{
printf("%d est negatif", nb);
}

```

## Variables Composées

### Tableaux
```c
int tableau[5]; //On intègre un tableau de 5 lignes allant de 0 à 4

tableau[0]=1;
tableau[1]=2;
tableau[2]=3;
tableau[3]=4;
tableau[4]=5;
```

### Structure


## Fonctions

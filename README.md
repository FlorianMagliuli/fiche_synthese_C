# fiche synthese C

## Variables

### Déclaration:

```c
int nb; //déclaration d'un entier
float réel; //déclaration d'un floattant
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
int i;

while(i<10)
{
printf("la variable i vaut : %d", i);
i++;
}
```



 
 
 
### tests

## Variables Composées

## Fonctions

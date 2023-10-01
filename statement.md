# Révision javascript

?[Javascript peut être exécuté ...]
-[] côté serveur.
-[] côté client.
-[x] côté serveur et côté client.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference


``` javascript runnable
let message = "Révision";
let message = "Révision révisée";
```
- Le code ci-dessous retourne une erreur, pourquoi ? 
- Remplacez ```let``` par ```var```, qu'en déduisez vous ? 

En utilisant let, déclarez (par au moins deux manières différentes), trois variables en leur attribuant une valeur : 
- ```name```
- ```nickname```
- ```age``` 

... puis affichez le message ```"Bonjour [name], tu as [age] ans et ton pseudo est : [nickname]"```


### 

### Conversion, syntax (virgule, precedence)



### interactivité
En utilisant les fonctions ```prompt```, ```confirm``` et ```alert``` :
- Demandez à un utilisateur de rentrez son nom, son age, puis son peudo (fonction ```prompt```)
- Ajoutez 3 à son age. ()
- Demandez à l'utilisateur de confirmer ces informations (```confirm```)
- Affichez un message d'excuse. 

### opérateur logiques
alert( null || 2 || undefined );

alert( 1 && null && 2 );

alert( null || 2 || undefined );
In other words, || doesn’t distinguish between false, 0, an empty string "" and null/undefined. They are all the same – falsy values. If any of these is the first argument of ||, then we’ll get the second argument as the result.
In practice though, we may want to use default value only when the variable is null/undefined. That is, when the value is really unknown/not set.




## Exercices

1- Ecrivez un programme qui demande les informations suivantes à l'utilisateur :
- Nom 
- Prénom 
- Email 
- Age
Le programme stocke ces informations dans des variables puis affiche le message suivant : 
```
"Bonjour [name], tu as [age] ans et ton email est : [email]"
```

On vérifiera, entre autres, que l'age n'est pas négatif et que les chaines de caractères ne sont pas vides.





<!-- typeof -->
<!-- Debugger page avec erreur-->

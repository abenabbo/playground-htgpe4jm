### Les programmes suivants renvoient-ils une erreur ? 
```javascript
console.log('Bonjour')
console.log( 'Rebonjour')
```

```javascript
let _variable;
let _; 
let my-variable;
let x$; 
let 我;
```

<!-- utilisation du var -->
```javascript
let variable;
let variable = 55;
```

<!--//"use strict";-->
```javascript
message = "Bonjour"; 
```
<!-- Pas de soucis. Une variable peut changer de type;-->
```javascript
let variable = 12.5;
variable = "Je suis une chaine de caractère"; 
```

### Que renvoient les programmes suivants ? 

<!-- NaN  -->
```javascript
console.log("trois"/5);
```

<!-- Il faut utiliser les backticks   -->
```javascript
let prenom = "Azzeddine";
console.log("Bonjour ${prenom}, ça va ?");
```

<!-- true
    false
    true
  -->
```javascript
console.log( 5 > 3 );
console.log( 10 > 5 > 2 );
console.log( 10 > 5 < 2 );
```
<!--In JavaScript, null is not a “reference to a non-existing object” or a “null pointer” like in some other languages.
It’s just a special value which represents “nothing”, “empty” or “value unknown”.-->

```javascript
let prenom;
console.log(prenom);
```

<!-- 200  -->
```javascript
console.log("10" * "20");
```

```javascript
console.log("50" + 9);
console.log(5 + 2 + "9");
console.log("5" + 2 + 9);
console.log("5" - 9);
```


```javascript

console.log( +'3' + +'20');
```

```javascript
console.log( "" + 1 + 0)
console.log( "" - 1 + 0)
console.log( true + false)
console.log( 6 / "3")
console.log( "2" * "3")
console.log( 4 + 5 + "px")
console.log( "$" + 4 + 5)
console.log( "4" - 2)
console.log( "4px" - 2)
console.log( "  -9  " + 5)
console.log( "  -9  " - 5 )
console.log( null + 1 )
console.log( undefined + 1 )
console.log( " \t \n" - 2 )
```


Que renvoie les comparaisons suivantes ? 
```javascript
10 > 50
"a" < "Z"
5 == "5"
5 === "5"
0 == false
```

<!-- 
console.log(priority_1 || priority_2 || priority_3);
console.log(priority_1 ?? priority_2 ?? priority_3);

console.log(0 || 100);
console.log(0 ?? 100);

equivalent à : 
(a !== null && a !== undefined) ? a : b;

|| doesn’t distinguish between false, 0, an empty string "" and null/undefined.
 -->
```javascript
let priority_1 ; // ex. priority_1= null;
let priority_2 ; // ex. priority_2= "Envoyer email";
let priority_3 ; // ex. priority_3= "Nettoyer bureau";


// Ecrivez un programme qui permet d'afficher la prochaine tâche prioritaire à faire
// Exemple d'exécution :
// ex. priority_1= null;
// ex. priority_2= "Envoyer email";
// ex. priority_3= "Nettoyer bureau";
// => "la prochaine tache de la to-do liste est : Envoyer email"

//PS: une solution des solutions possibles tient sur une ligne de code
```

Qu'affiche ce programme ? Le résultat aurait-il été différent avec ```break``` à la place de ```continue``` ?
```javascript
for (let i = 0; i < 10; i++) {

  if (i = 5 ) continue;
  console.log (i); 
}
```

Réecrivez le programme suivant en utilisant un switch
```javascript
    if(browser == 'Edge') {
        console.log("Mouais");
    } else if (browser == 'Chrome'
        || browser == 'Firefox'
        || browser == 'Safari'
        || browser == 'Opera') {
        console.log( 'Navigateur supporté' );
    } else {
    console.log( 'Navigateur inconnu !' );
    }
```

Quelle est la valeur de ```result``` ?
```javascript
function numberFunction() {
    let number = 5;
}

let number = 10;
numberFunction()
result = number + 1;
console.log( result ); 
```


Réecrivez cette fonction sans ```if```
```javascript

function showIdentity(id, login){
    if(id === undefined)
        id = "No ID";
    if(login === undefined)
        login = "Unknown";
    
    console.log(id);
    console.log(login);
}

```

Complétez la fonction ```traiterTexte``` (et ajoutez-en d'autres si besoin) qui permet de formater un texte au format donné. Voir exemples d'exécution
```javascript
function traiterTexte( ... ){
    // ...
    console.log(text);
}

traiterTexte("users", prefixerWP) // => "wp_users"
traterTexte("users", prefixerPS) // => "ps_users"
traterTexte("users", parentheser) // => "(users)"



```

Analyse le programme suivant. Identifiez vous des problèmes au niveau de l'appel aux fonctions, de la decalaration ou de la défintion des fonctions ? 

```javascript
myFunction();
myFunction_2();

function myFunction (){
  console.log("my function");
}

let myFunction_2 = function(){
  console.log("my function 2");
}
```


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

2- Ajoutez un tableau de notes et initialisez le avec 5 notes.

Ecrivez les fonctions suivantes : 
<!-- for & for of & for in && forEach -->
- ```afficherTableau(tableau)```, affiche l'ensemble des éléments du tableau
- ```somme(tableau)```, calcule et renvoie la somme des éléments du tableau 
- ```moyenne(tableau)```, calcule et renvoie la moyenne des éléments du tableau
- ```maximum(tableau)```, calcule et renvoie le maximum des éléments du tableau

3- Créez un objet ```etudiant``` dont les proriétés sont le nom, prénom, email, age et notes de l'étudiant.
Ecrivez une méthode ```afficherEtudiant(etudiant)``` qui affichera les détails de la manière suivante : 

```
[Prénom] [Nom] | [email] | [notes]
```

### Création d'un étudiant
- Ecrivez une fonction qui permet de vérifier si l'adresse mail de l'étudiant est une adresse institutionnelle de l'IUT Paul Sabatier
//exemple execution
- Ecrivez une fonction qui permet de générer une note aléatoire entre 0 et max
//exemple execution
Ecrivez une fonction qui permet de créer un étudiant à partir des données entrées en prompt. Cette fonction doit respecter les consignes suivantes;
- si le nom et/ou le prénom ne sont pas renseignés, les extraire de l'adresse mail
- vérifiez que l'email est une adresse institutionnelle de l'IUT Paul Sabatier
- générez 5 notes aléatoires (/20) 
//exemple execution
- Ecrivez une méthode afficher() qui affiche tous les détails d'un étudiant

### Gestion des étudiants
- Ecrivez un programme qui demande à entrer 3 étudiants, crée les objets correspondants et les stocke dans un tableau d'étudiants appelé ```promotion```.
- Ecrivez une méthode afficherEtudiants() qui affiche les détails de tous les étudiants
- Ecrivez une méthode qui renvoie la moyenne de la promotion
- Ecrivez une méthode qui renvoie le nom et prénom du major de la promotion
- Ecrivez une méthode qui classe et affiche l'ensemble des étudiants en fonction de leur moyenne.






<!-- typeof -->
<!-- Debugger page avec erreur-->

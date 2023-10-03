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


### Que renvoient les comparaisons suivantes ? 
<!-- lettres minuscules toujours plus grandes-->
```javascript
console.log( 10 > 50 )
console.log( "a" < "Z" )
console.log( 5 == "5" )
console.log( 5 === "5" )
console.log( 0 == false )
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
 Complétez le programme suivant
```javascript
let priority_1 ; // ex. priority_1= null;
let priority_2 ; // ex. priority_2= "Envoyer email";
let priority_3 ; // ex. priority_3= "Nettoyer bureau";


// Ecrivez un programme qui permet d'afficher la prochaine tâche prioritaire à faire
// Exemple d'exécution :
// ex. priority_1= null;
// ex. priority_2= "Envoyer email";
// ex. priority_3= "Nettoyer bureau";
// => afficher "la prochaine tache de la to-do liste est : Envoyer email"

//PS: une solution des solutions possibles tient sur une ligne de code
```

Qu'affiche ce programme ? Le résultat aurait-il été différent avec ```break``` à la place de ```continue``` ?
```javascript
for (let i = 0; i < 10; i++) {

  if (i == 5 ) continue;
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
<!-- 11 -->
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

Analyse le programme suivant. Est-ce que vous identifiez des problèmes au niveau de l'appel aux fonctions, de la decalaration ou de la défintion des fonctions ? 

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

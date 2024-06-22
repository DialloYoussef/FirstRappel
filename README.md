# FirstRappel

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.14.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


##
Installez json-serverà partir de npm à l'aide de la commande suivante.
 `npm install -g json-server`

  Rassurez vous de l'existence de db.json à la racine du projet
##
  `json-server --watch db.json`

  Dans votre navigateur Web, accédez au http://localhost:3000/locationset confirmez que la réponse inclut les données stockées dans db.json.

  


<hr>
<hr>
# FirstRappelAngular16

# NOTES:

<div>
    <h3> Services et Injection de dépendances </h3>
    Les services Angular permettent de séparer les données et les fonctions de l'application Angular qui peuvent être utilisées par plusieurs composants de notre application.
    <br>
    L'injection de dépendances est le mécanisme qui gère les dépendances des composants d'une
    application et les services que d'autres composants peuvent utiliser. 
    <br>
    <br>
    pour generer un service on utilise: 
    <h6> ng generate service housing </h6>
</div>

<hr>

<div>
    <h3>le Routing(Routage)</h3>
    Le routage est la possibilité de naviguer d'un composant de l'application à un autre. Dans les applications à page unique (SPA) , seules certaines parties de la page sont mises à jour pour représenter la vue demandée par l'utilisateur.

  <h6>La <i>routerLink</i> directive permet au routeur d'Angular de créer des liens dynamiques dans l'application. La valeur attribuée au routerLink est un tableau avec deux entrées : la partie   statique du chemin et les données dynamiques. <br>  
    Pour que le <i>routerLink</i> fonctionne dans le modèle, ajoutez une importation ( <i> RouterLinket RouterOutletvers </i> ) au niveau du fichier depuis <i>'@angular/router' </i> 
  </h6>

</div>

<hr>

<div>
  <h3>Les Forms</h3>

  <h6>
    En Angular, <i>FormGroupet FormControl</i> sont des types qui vous permettent de créer des formulaires. <br> Le type <i>FormControl</i> peut fournir une valeur par défaut et façonner les données du formulaire.
  </h6>

</div>

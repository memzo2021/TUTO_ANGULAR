﻿# angular-tuto


ngFOR => c'est une boucle for dans mon template
______________________________________________________________________________

ng generate component suivi du nom =>   créer mon component dans un dossier app:
<li>il crée un TEMPLATE</li>
<li>une feuille de style </li>
<li>et un fichier typscritp(@component({
    selector:'nom de mon app',
    templateUrl:'./nom-de-mon-app.html',
    StyleUrls:['./nom-de-mon-app.css']
})) </li>
_________________________________________________________________

j'injecte via le  constructeur()<br>
Exemple : constructor(<br>
    private route: ActivatedRoute,<br>
    private cartService: CartService <br>
  ) { }<br>
___________________________________________________________________________________
Interpolation : afficher des données venant du typscript dans le template <br>
Liaision par proprietés => code typscript  vers  template html


________________________________________________________________________________
composant = bloc de code affichant une fonctionnalité réutilisable dans les modules(Une application c'est ni plus ni moins une -> Abrescence de composants)<br>

Exemple: AppComponent /MenuComponent/ContentComponent/SidebarComponent<br>

je constate que je peux réutiliser des composants comme je veux<br>

Le composant racine lie la hierarchie des composants au DOM element

Appmodule =>modulaire racine permet de lancer l'application


Template: à revoir 
ng serve =pour lancer le server de developpement 

côté gauche : node_modules contient Typscript et peut aussi contenir bootstrap

src dossier source qui sera mon dossier de travail principal
dans le html je trouve :<app-root></app-root>
__________________________________________________________________________________

Liaison entre Typscript et mon Template :

Code vers template et 
template vers code

---De typscript vers le template :





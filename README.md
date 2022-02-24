# Angular-tuto:
AGULAR <br>
Avant tout, Angular est un framework orienté composant.<br> Il faudra écrire de petits composants, et assemblés, ils vont constituer une application complète.

 Un composant est un groupe d’éléments HTML, dans un template, dédiés à une tâche particulière.  
 Mes composants seront organisés de façon hiérarchique, comme le DOM : un composant racine aura des composants enfants, qui auront chacun des composants enfants, etc. 

 Angular est un framework complet, avec plein d’outils pour faciliter les tâches classiques du développement web, construire des formulaires, appeler un serveur HTTP, du routage d’URL, interagir avec d’autres bibliothèques, des animations,  
 
 ******************************************************************************
ngFOR => c'est une boucle for dans mon template

***********************************************************************************

ng generate component suivi du nom =>   crée mon component dans un dossier app:
<li>Il crée un TEMPLATE</li>
<li>Une feuille de style </li>
<li>Et un fichier typscritp(@component({ <br>
    selector:'nom de mon app',<br>
    templateUrl:'./nom-de-mon-app.html', <br>
    StyleUrls:['./nom-de-mon-app.css']
})) </li>
*************************************************************************************************************************************

j'injecte via le  constructeur()<br>
Exemple : constructor(<br>
    private route: ActivatedRoute,<br>
    private cartService: CartService <br>
  ) { }<br>
**********************************************************************************************************************************************************************
--Interpolation : afficher des données venant du typscript dans le template <br>
--Liaision par proprietés => code typscript  vers  template html
_Pour lier à une propieté , on utilise les crochets
_Pour et pour lier à un évenement du DOM on utilise les parenthèses


**********************************************************************************************************************************************************************
<li>Composant</li> : bloc de code affichant une fonctionnalité réutilisable dans les modules(Une application c'est ni plus ni moins une -> Abrescence de composants)<br>

Exemple: AppComponent /MenuComponent/ContentComponent/SidebarComponent<br>

je constate que je peux réutiliser des composants comme je veux<br>

Le composant racine lie la hierarchie des composants au DOM element

Appmodule =>modulaire racine permet de lancer l'application


Template: à revoir  

ng serve =pour lancer le server de developpement 

Côté gauche : node_modules contient Typscript et peut aussi contenir bootstrap

src dossier source qui sera mon dossier de travail principal 
dans le html je trouve :  [<app-root></app-root>]
**************************************************************************************************************************************************************************

Liaison entre Typscript et mon Template :

<li>Code vers template et </li>
<li>Template vers code</li>

-De typscript vers le template :

****************************************************************************
Je peux manipuler un template avec le databinding
Faire communiquer les composants avec les services
Créer des SPA avec le routing
Faire communiquer une apps avec un backend (Pas bien compris comment cela fonctionné exactement  à revoir)






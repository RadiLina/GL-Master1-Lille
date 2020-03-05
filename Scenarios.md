# Scenarios concrets 

## Acteurs 
Patron {Bob}

Serveur/se {Alice}

Client 

Chef de cuinie {Jon}

Cuisinier {Louis} 



### Patron

Avant chaque début d'un service Bob {le patron} établi une liste de plats et de menus, pour cela une interface est mise à disposition de Bob. Pour commencer Bob sélectionne une option sur l'interface.

 Bob se connecte à son interface en introduisant son login et mot de passe sur la page de connexion.

Pour ajouter les produit (entrées, plats, desserts), Bob clique sur le bouton "Gérer les produit", il choisi l'option ajouter un produit, puis selon la catégorie séléctionnée Bob ajoute le plats en remplissant un petit formulaire mis a disposition sur les détails des produit (ingrédient, prix...etc). Enfin il confirme avec le bouton confirmer.

Ensuite Bob sélectionne l'option "gérer les menu", ensuite "composer un menu" et choisi les (les entrees, les plats, les desserts), et confirme son choix de menu en cliquant sur le bouton ajouter à la liste.

Pendant le service Bob reçoit une notification que le dessert "tiramisu" n'est plus disponible alors sur l'interface "gérer les produits", il choisi l'option supprimer un produit, une liste de produit selon les categories est affichée, il séléctionne "tiramisu" puis clique sur le boutton suprimmer en bas de la liste,

puis sur l'interface "gérer les menu", Bob choisi l'option "modifier un menu" et selectionne les menu qui ont "tiramisu" comme dessert et modifie leurs dessert. sinon il peut supprimer le menu en cliquant sur le boutton "supprimer un menu" sur l'interface "gérer les menus"
### Serveur

Quand le client commande quelque chose pour manger auprès du serveur , le serveur utilise l'application , Lorsqu'il arrive devant l’interface, le Header est composé d’un logo symbolisant le panier et d’un bouton “Commander” non cliquable. il aperçoit des différentes catégories (entrées, burgers, dessert, boisson, menu et promotion.) qui contiennent de différents items , et il choisit les items commandés par le client , Ce système est composé d’un tableau, dont les items peuvent être sélectionnable, on peut modifier la quantité de cet élément grâce à des boutons “+” et moins “-” , et le prix se met à jour, le bouton “commander” devient alors cliquable.
Il clique sur le panier et un panel de droite s’affiche, celui ci se compose d’une liste récapitulant tout les éléments de la commande , ainsi que des boutons qui permettent de l’administrer (éditer, supprimer un élément).
En bas, un gros bouton :
- Valider le panier

Il passe à l'étape suivante, le client va payer le serveur sur place , soit en espèces soit par carte bancaire , une fois le serveur réalise le paiement, il modifie l'état de la commande vers “payée” pour qu'elle s'affiche dans le tableau de bord du chef cuisinier afin qu'il la prenne en compte.

Le serveur alors peut suivre l'état d'avancement de la commande , pour qu'il l'apporte au client quand elle est préparée.
 

### Client

Patrick(Client) souhaite prendre son repas au restaurant,Patrick rentre dans le restaurant et se dirige vers l'appareil de commande ,l'application affiche la liste des menus "Maxi", "Medium" ,"Family"...et les plats "Entrees" ,"Salades", "Desserts" ,"Boissons","Burgers" ,"Glaces" ...

Patrick choisit le menu "Maxi" en cliquant sur le bouton "Selectionner",l'application affiche les details du menu choisi : la liste des plats dans le menu avec des options a ajouter pour chaque produit ou a supprimer (boutons Oui / Non ) ainsi que la quantité avec des boutons `+` et `-` et indique le prix devant chaque produit,Patrick choisit de prendre une canette de plus en cliquant sur le bouton + ,puis clique sur "Valider la commande"

L'application fait l'addition de sa commande et affiche le recapitulatif de la commande avec le montant total de la commande , le numero de commande(ticket) , Patrick clique sur "Finaliser la commande" , l'application affiche un message "Veuillez proceder au paiement SVP" , Patrick paie sa commande en especes ou avec sa carte bleu,l'application enregistre la commande,genére le ticket de caisse et l'imprime.

### Chef de cuisine 

Jon (chef de cuisine) se connect à son profile. Le systé visualise la liste des commandes avec leurs etats. Il peut voir si un client à affectuer une commande. Une fois il recoit une commande (une notification d'une commande avec l'etat en attente va apparaître sur le profile de Jon ), il divise la commande à un ensemble des taches qui correspendent à l'ensemble des personels et il affecte chaque tache à la bonne personne. 
Ensuite, il change l'etat de la commande de en attente à en train de préparaton.
Jon (chef de cuisine) sera informer en cas de stock épuisé pour un ingrédiant, et il signale la non disponibilité des plats qui se preaprent en utilisant ce dernier.

Consulter la liste des commandes 
Affecter les taches aux personnels
Modifier l'etat d'une commande 
Signaler la non disponibilite d'un plat

### Cuisinier 

  Louis, un cuisinier dans le restaurant, vérifie dans l'application si il y a une tâche qui lui est attribuée dans la liste de toutes les tâches éditées par le chef cuisinier,Louis trouve une tâche pour lui qui est la préparation d'une salade niçoise, donc Louis change l'état de cette dernière en cliquant sur le bouton "En cours de préparation" , et commence la préparation, après avoir terminé, Louis passe l'état de la tâche cette fois à "Prêt". 
  Son partenaire Lucas qui est un glacier reçoit en même temps une tâche concernant un glace de fruits rouges, mais comme le parfum "Fraise" n'est plus disponible, Lucas signale dans l'application la non disponibilité de cette glace.
  Il y avait aussi une tâche destinée à Jack, le barmen du restaurant. Après changement de l'état de cette dernière, Jack prépare un mojito comme demandé et clique sur le bouton "Prêt" pour passer à la prochaine tâche.










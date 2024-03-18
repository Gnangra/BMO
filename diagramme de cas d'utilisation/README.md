Le diagramme des cas d'utilisation présente les interactions entre différents acteurs et le système de paris en ligne. 
Voici une explication de chaque élément du diagramme :

Source tierce : Cet acteur représente les fournisseurs d'informations en temps réel sur les événements sportifs. 
                La source tierce a pour cas d'utilisation "Fournir les informations", ce qui implique qu'elle alimente le système 
                avec des données mises à jour en continu sur les événements sportifs en cours, telles que les scores, les performances 
                et d'autres statistiques pertinentes pour les paris.

Parieur : C'est l'utilisateur final qui interagit avec le système pour placer des paris sur les événements sportifs. 
          Le parieur a deux cas d'utilisation principaux :

Gérer ses paris : Cela comprend toutes les actions relatives au placement des paris, comme choisir un événement, 
                    sélectionner un type de pari, déterminer le montant du pari en jetons et soumettre le pari au système.

Gérer son compte : Cela couvre les activités liées à la gestion de son propre compte sur le système, 
                    comme visualiser le solde de jetons, recharger les jetons (dont les détails seront fournis ultérieurement), 
                    et consulter l'historique des paris placés.

Bookmaker : C'est l'entité ou l'administrateur qui gère et supervise le système de paris. Le bookmaker a le cas 
            d'utilisation "Choisir les événements", ce qui signifie qu'il sélectionne et définit les événements sportifs disponibles pour les paris. 
            Il détermine aussi les cotes, les écarts sur les scores et peut mettre en place des restrictions comme des limites de montant pour les paris 
            ou un plafond pour les gains.
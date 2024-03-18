Événement : C'est la classe de base pour les événements sportifs sur lesquels les paris peuvent être placés. Elle possède des attributs tels 
            que l'ID, le nom, la date de début, et elle est en relation avec la classe Sport. Elle offre des méthodes pour obtenir et définir 
            les détails de l'événement.

Sport : Cette classe représente différents sports disponibles pour les paris. Elle contient un ID et un nom pour chaque sport, et elle est 
        liée à une classe spécialisée pour les règles, telle que RèglesFoot pour le football.

RèglesFoot, RèglesBasket, RèglesTennis, règlesCoursesChevaux : Ce sont des classes dérivées de la classe Sport qui définissent les 
            règles spécifiques à chaque sport. Elles contiennent les méthodes pour obtenir et définir les règles.

DétailsÉvénement : Elle étend la classe Événement avec des détails spécifiques tels que les cotes et l'écart des scores. Cette classe est
                    essentielle pour définir les cotes des événements et les détails des scores qui influencent les paris.

Parieur : Représente l'utilisateur qui place des paris. Cette classe contient des informations personnelles et les détails de compte du 
        parieur, ainsi que des méthodes pour gérer son compte, comme créditer ou retirer des jetons, et créer un pari.

Paris : C'est la classe centrale pour la gestion des paris. Elle inclut des informations sur chaque pari comme l'ID, le statut de gain, 
        le contenu, la date, et les méthodes pour définir et obtenir ces informations.

typeParis : Cette classe est une généralisation qui définit le type de pari. Il y a deux spécialisations de cette classe : Simple et 
            Avance, qui correspondent respectivement aux paris simples et avancés.

Simple et Avance : Ces deux classes héritent de typeParis et sont utilisées pour définir les types de paris disponibles. Les paris simples 
                    ont généralement moins de variables et sont plus faciles à gagner, tandis que les paris avancés offrent des options plus 
                    complexes et des gains potentiels plus élevés.

Le diagramme illustre également les relations entre les classes. Par exemple, un Parieur peut "Effectuer" plusieurs Paris, un Paris est 
"Défini" par un typeParis, et un Événement peut correspondre à plusieurs DétailsÉvénement.
Le diagramme d'état décrit le cycle de vie d'un pari dans votre système de paris en ligne. Voici les différentes étapes 
représentées :

créé : C'est l'état initial d'un pari, lorsqu'un parieur vient de le placer. À ce stade, le compte du parieur est débité du montant du pari.

en_cours : Une fois que l'événement sportif a commencé, le pari passe à l'état "en cours". Cela signifie que le pari est actif et que le 
            résultat est en attente.

annulé : Si l'événement est annulé ou si le pari est annulé pour une autre raison (peut-être par le parieur ou le système en raison d'une 
        erreur ou d'un changement de conditions), le pari passe à l'état "annulé". Généralement, cela entraîne le remboursement du pari au parieur.

succès : Si le résultat de l'événement est en faveur du parieur, le pari est un succès. Le compte du parieur est alors crédité du montant 
        gagné, calculé en multipliant la mise par la cote.

échec : Si le résultat de l'événement n'est pas en faveur du parieur, le pari est considéré comme un échec. Dans de nombreux systèmes, 
        cela signifie simplement que le pari est perdu. Cependant, dans certains cas, le système peut offrir un remboursement partiel en 
        fonction de conditions spécifiques.

Une fois le pari terminé (qu'il s'agisse d'un succès ou d'un échec), ou annulé, le processus atteint un état final, indiqué par un cercle 
entouré d'un cercle plus large
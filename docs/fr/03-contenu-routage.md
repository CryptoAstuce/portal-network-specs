# 3. Identifiants de contenu et routage

Un identifiant de contenu encode la nature de la donnée et les paramètres nécessaires pour la retrouver. Le routage compare cet identifiant avec les clés des pairs afin de rapprocher la requête des nœuds pertinents.

Les données History utilisent des formes d’identifiants adaptées aux blocs, transactions, reçus ou accumulateurs. Les données State nécessitent d’autres clés pour cibler des éléments de l’état.

Le protocole doit distinguer une absence de contenu d’une erreur de transport. Un nœud peut répondre qu’il ne possède pas l’objet et orienter la recherche vers d’autres pairs.

Les vecteurs de test servent à vérifier l’encodage et les frontières du routage sans dépendre d’un réseau public.

Suite : [Réseaux History et State](04-history-state.md).

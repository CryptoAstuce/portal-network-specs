# 5. Wire protocol et transport

Le wire protocol définit les requêtes et réponses échangées entre pairs : trouver du contenu, demander une donnée ou publier une donnée. Les messages encodent le type de contenu et les limites de taille.

Le transport UTP ajoute une transmission fiable pour des charges plus volumineuses que les petits messages de découverte. Il gère la progression, les fragments et la terminaison d’un transfert.

Un pair doit limiter les ressources consommées par une requête distante. Les erreurs de décodage, de taille ou de contenu invalide doivent être traitées sans compromettre le nœud.

Les extensions de version rendent explicites les capacités négociées et les changements de protocole.

Suite : [JSON-RPC, test vectors et limites](06-jsonrpc-vecteurs-limites.md).

# 2. Discv5 et découverte des pairs

Discv5 permet aux nœuds de découvrir des pairs et de maintenir une table de routage. Les nœuds annoncent leurs capacités et leurs adresses, puis répondent aux requêtes selon les règles du protocole.

La découverte ne signifie pas que le pair possède le contenu demandé. Elle fournit une proximité dans l’espace d’identifiants, qui sera exploitée par le routage Portal.

Les extensions de ping transportent des informations complémentaires sur les capacités d’un nœud. Elles doivent rester compatibles avec les types et les règles de version définis dans le dépôt.

La disponibilité d’un pair est temporelle : les tables doivent être rafraîchies et les échecs retirés progressivement.

Suite : [Identifiants de contenu et routage](03-contenu-routage.md).

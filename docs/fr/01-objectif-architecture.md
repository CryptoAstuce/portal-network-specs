# 1. Objectif et architecture

Le Portal Network distribue des données Ethereum historiques ou d’état entre des nœuds légers. Il complète les clients classiques en permettant de récupérer du contenu sans conserver toute la chaîne localement.

Le dépôt sépare plusieurs sous-réseaux : History, State, Beacon et leurs variantes. Chaque réseau possède des identifiants de contenu, des règles de stockage et des messages adaptés à son domaine.

Le protocole s’appuie sur une table de routage de type DHT et sur des échanges authentifiés entre pairs. La spécification décrit les contrats de messages, pas une implémentation unique.

La conception doit équilibrer disponibilité, coût de stockage, couverture du contenu et résistance aux pairs malveillants.

Suite : [Discv5 et découverte des pairs](02-discv5-pairs.md).

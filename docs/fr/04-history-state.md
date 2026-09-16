# 4. Réseaux History et State

Le réseau History vise des données passées comme les blocs, transactions, reçus et accumulateurs. Le réseau State cible des éléments de l’état, avec des identifiants et des preuves adaptés à leur structure.

Chaque réseau définit ses content keys, ses messages et ses règles de validation. Cette spécialisation évite de traiter toutes les données comme un simple blob.

Les accumulateurs et les structures Verkle ou Merkle permettent de compresser des références et de vérifier l’appartenance d’un élément. La preuve doit être interprétée dans le contexte de la racine attendue.

La séparation History/State permet aux nœuds de choisir les données qu’ils stockent et servent.

Suite : [Wire protocol et transport](05-wire-protocol.md).

# ACL et déchiffrement autorisé

FHE.allowThis permet au contrat de réutiliser un chiffré et FHE.allow accorde un droit à une adresse ciblée.
Une lecture en clair nécessite ensuite une requête de déchiffrement liée à l'identité autorisée.
Les permissions doivent être réappliquées après chaque calcul car le résultat possède une nouvelle poignée.
Une autorisation globale ou persistante mal placée annule la confidentialité malgré un chiffrement correct.
L'interface doit invalider ses autorisations lors d'un changement de compte, de réseau ou de contrat.
Le modèle d'accès fait ainsi partie de la logique métier, pas d'une simple couche d'affichage.

Suite : [04 — Interface](04-interface-et-etats-asynchrones.md).

# Le flux confidentiel FHEVM

L'application sépare le contrat Solidity, le relais FHE et l'interface Next.js.
L'utilisateur chiffre une entrée avant la transaction ; le contrat ne reçoit qu'une poignée et une preuve d'entrée valide.
Les opérations homomorphes produisent de nouveaux chiffrés sans révéler les valeurs intermédiaires.
Le déchiffrement revient à un utilisateur autorisé via le relais, hors de l'exécution ordinaire du contrat.
La confidentialité dépend donc de plusieurs frontières : navigateur, ACL, coprocesseur, KMS et réseau.
Le compteur du template rend ce chemin observable sans réduire FHEVM à une primitive Solidity locale.

Suite : [02 — Types chiffrés](02-types-et-operations.md).

# Types chiffrés et opérations

Les types euint représentent des valeurs chiffrées dont la largeur borne le domaine arithmétique.
Une entrée externe doit être convertie par la bibliothèque FHE après validation de sa preuve.
Addition, soustraction et comparaisons construisent des opérations symboliques exécutées par l'infrastructure FHE.
Chaque nouveau handle doit être traité comme un nouvel objet de sécurité, avec ses propres droits.
Les conversions de largeur et le comportement aux bornes doivent être décidés explicitement par l'application.
Cacher la valeur n'empêche ni les erreurs logiques ni les fuites par branchement ou métadonnées.

Suite : [03 — ACL](03-acl-et-dechiffrement.md).

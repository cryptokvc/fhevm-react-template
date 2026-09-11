# Interface et états asynchrones

Le frontend relie portefeuille, chaîne, adresse, ABI, relais et état de déchiffrement.
Chiffrement, transaction, calcul et déchiffrement ne terminent pas au même instant.
L'interface doit distinguer ces phases pour éviter les doubles soumissions et les valeurs obsolètes.
Une adresse de contrat ou un chain ID inattendu doit bloquer l'action avant la signature.
Les valeurs en clair existent dans le navigateur avant chiffrement et après déchiffrement : extensions et journaux sont dans le périmètre.
Une bonne UX confidentielle explique aussi quelles métadonnées restent publiques.

Suite : [05 — Limites](05-limites-et-menaces.md).

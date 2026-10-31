# BANK MANAGER Alpha 0.4 — Politique commerciale et concurrence

Jeu de simulation bancaire fictif 100 % local, hébergé par GitHub et Netlify (sans backend).

## Nouveautés
- Menu **Produits & tarifs** : modification des prix de 8 produits, dans des fourchettes prédéfinies.
- Benchmarks concurrents simulés évoluant chaque mois avec taux directeur fictif, chômage, inflation et confiance.
- Acquisition et départs quotidiens des clients selon l’attractivité de chaque segment.
- Marketing dont les taux de conversion dépendent des tarifs et de la capacité des agences.
- Demandes de crédits des conseillers utilisant la grille des taux de la banque.
- Sauvegardes compatibles avec Alpha 0.1–0.3 (clé `bank-manager-alpha-01`).

## Publication Netlify
Décompressez à la racine du dépôt GitHub. Build command : vide. Publish directory : `.`. `netlify.toml` est fourni.

## Important
Tous les cours, taux, scénarios et références concurrentielles sont **fictifs** et ne prétendent pas reproduire les taux du marché bancaire français en vigueur. Les fourchettes sont des limites de gameplay, pas des limites réglementaires. Le moteur reste simplifié, notamment concernant dépôts réglementés, scoring, provisions et réglementation bancaire. Le simulateur conserve les sauvegardes en localStorage : exportez régulièrement vos parties depuis l’onglet Sauvegardes.

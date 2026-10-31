# BANK MANAGER — Alpha 0.2

Simulateur fictif de direction bancaire, **100 % local** dans le navigateur, à publier directement sur GitHub + Netlify. Aucun Supabase, aucun serveur, aucune API ni installation npm.

## Publication

1. Décompresser l'archive et placer **index.html**, **app.js**, **style.css** et **netlify.toml** à la racine du dépôt GitHub.
2. Sur Netlify, connecter le dépôt.
3. Build command : laisser vide. Publish directory : `.`. Base directory : vide.
4. Déployer et recharger votre URL Netlify.

## Nouveautés 0.2

- Partie neuve avec environ 350 clients fictifs et 165 crédits constituant un portefeuille initial (le portefeuille de crédits est inscrit à l'actif, les dépôts créés au passif).
- Production de crédits automatique optionnelle, dépendant notamment des conseillers, de l'analyste risques et d'une limite interne de capital.
- Échéances de capital mensualisées (et non prélevées chaque jour).
- Fonds propres / actifs pondérés **indicatifs**, avec affichage « Non calculable » si les actifs sont insuffisants.
- Indication du produit net bancaire et du résultat cumulés.
- Maintien des recrutements agence, siège et marchés, ouverture d'agences, portefeuille fictif de titres, achats/ventes, sauvegardes et export/import JSON.

## Conservation des parties précédentes

La clé de stockage `bank-manager-alpha-01` et la structure de sauvegarde `version: 1` sont conservées. Une ancienne partie continuera de fonctionner avec les nouvelles règles mais **ne recevra pas artificiellement le nouveau portefeuille initial**. Pour jouer avec les nouvelles données de départ, exportez votre sauvegarde puis cliquez sur « Nouvelle partie » dans « Sauvegardes ».

## Limites

Ce logiciel est une simulation pédagogique et ludique, non un système bancaire réel. Les ratios ne représentent pas les calculs prudentiels officiels ; les produits et charges sont simplifiés, la tarification client et les risques de crédit ne reproduisent pas toutes les normes IFRS, françaises ou européennes. Les marchés sont entièrement synthétiques. Le jeu ne réalise aucune opération bancaire.

Les parties sont sauvegardées dans localStorage, sur ce navigateur et cet appareil. Exportez régulièrement vos parties en JSON.

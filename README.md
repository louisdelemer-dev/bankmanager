# Bank Manager Alpha 0.6

Jeu de simulation bancaire fictif, autonome et hébergé en statique.

## Déploiement GitHub / Netlify

Uploader **tous les fichiers à la racine** du dépôt GitHub. Sur Netlify : aucune commande de compilation, répertoire de publication `.`. Le fichier `netlify.toml` comporte déjà le paramètre de publication.

## Pour jouer

1. Ouvrir Direction générale.
2. Cliquer sur « + 7 jours » pour observer une première semaine.
3. Consulter les flux nouveaux clients, départs, demandes et les décisions à prendre.
4. Ouvrir « Comité de crédit », examiner les dossiers, accorder/refuser/négocier.
5. Aller dans « Marketing » pour lancer une campagne et dans « Produits & tarifs » pour modifier le positionnement de la banque.
6. Accéder à « Sauvegardes » pour exporter une partie JSON.

Les nouveaux clients sont ouverts automatiquement par le siège, sans validation du joueur. Les **crédits** nécessitent toujours une décision manuelle.

## Données

Calculs et sauvegardes locales, dans le navigateur (`localStorage`). Aucune base de données distante, aucun appel serveur, aucun cours réel. Les flux nouvellement suivis ne sont disponibles qu'après simulation de nouvelles journées et ne peuvent être reconstruits à partir d'anciennes sauvegardes. Pensez à exporter votre partie avant de mettre à jour.

## Limitations

Données fictives, risque et ratios simplifiés. Les résultats ne constituent ni une comptabilité bancaire certifiée, ni des données économiques réelles.

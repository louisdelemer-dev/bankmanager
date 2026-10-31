# BANK MANAGER — Alpha 0.3

Simulateur local de direction d'une banque régionale fictive : agences, clients, crédits, marketing, recrutements, siège, salle des marchés et bilan. Aucun serveur, aucune base externe, aucun npm.

## Installation sur GitHub + Netlify

1. Décompresser le ZIP et déposer **les fichiers à la racine** de votre dépôt GitHub existant.
2. Netlify : **Base directory** vide, **Build command** vide, **Publish directory** `.`.
3. Redéployer le site. Si la version précédente reste affichée, recharger avec `Ctrl+F5`.

## À jouer

- **Direction générale** : avancer le temps (1 jour ou 30 jours) ou lancer la simulation.
- **Comité de crédit** : les conseillers génèrent des demandes ; examiner puis accepter, refuser ou modifier le montant/taux/durée en contre-proposition. Une contre-proposition reçoit sa réponse après 24 heures simulées ; elle ne produit aucun crédit avant l'acceptation du client.
- **Marketing** : lancer des campagnes en choisissant cible, budget quotidien et durée. Le budget est dépensé au lancement ; les prospects et ouvertures sont générés au fil du temps. Les ouvertures sont validées automatiquement par le siège, sans validation du joueur.
- **Personnel** : recruter des conseillers pour augmenter la capacité commerciale, au siège ou en salle des marchés.
- **Crédits** : consulter le portefeuille de crédits, les intérêts et remboursements ; les demandes sont désormais décidées par le joueur.
- **Sauvegardes** : export/import JSON, nouvelle partie et sauvegarde locale automatique dans `localStorage`.

## Mises à jour et compatibilité

Cette version conserve la clé `bank-manager-alpha-01` et le format `version:1`. Les anciennes sauvegardes seront enrichies des nouvelles données de campagne et de demande, sans suppression du portefeuille de crédits existant. **Exportez d'abord votre partie par précaution.** Les nouveaux dossiers apparaissent en avançant le temps.

## Limites

Les clients, scores de risque, marchés, conversions marketing, délais et conditions sont fictifs. Le ratio de fonds propres est indicatif, non réglementaire. Le bilan simplifié n'est pas une comptabilité bancaire complète. Le jeu n'exécute aucune véritable opération bancaire et les taux de réponse, coûts et conversions sont des hypothèses ludiques. Les sauvegardes peuvent être effacées par un nettoyage du navigateur : exportez-les régulièrement.

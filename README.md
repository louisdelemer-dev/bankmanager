# BANK MANAGER — Alpha 0.7 (stabilisation du jeu)

Jeu de simulation bancaire fictif et local. Déploiement statique GitHub + Netlify sans compilation, sans base distante.

## Installation
Déposer tous les fichiers à la racine du dépôt GitHub. Netlify : base vide, build command vide, publish directory `.`.

## Jouer
1. Cliquer **▶ Démarrer le jeu** en haut de l'écran. Le bouton devient **Mettre en pause**.
2. Choisir la vitesse : **1 journée / 4 secondes**, **1 journée / seconde** ou **7 journées / seconde**.
3. Les mouvements de clientèle et les dossiers de crédit apparaissent lors des journées simulées.
4. Examiner les dossiers dans Comité de crédit : accepter, refuser ou faire une contre-proposition.
5. Marketing : lancer une campagne. Produits & tarifs : adapter les offres. Agences et Personnel : développer les capacités.
6. Exporter régulièrement la partie JSON dans Paramètres.

La simulation est suspendue quand l'onglet n'est pas visible, quand une fenêtre de décision est ouverte et à chaque rechargement. Les données sont sauvegardées dans le navigateur. Ne pas effacer les données du site sans exporter sa partie.

## Modifications Alpha 0.7
- Horloge jouable et accélérée en journées, sur toutes les pages.
- Statut du simulateur visible en permanence.
- Pause automatique pendant la saisie des formulaires de décision.
- Boutons Annuler et validation de formulaire gérés par des actions séparées.
- Historique des mouvements commerciaux conservé ; génération des crédits et des arrivées à minuit simulé.
- Anciennes sauvegardes Alpha 0.1 à 0.6 réutilisées via la même clé locale.

Les produits, clients, banques, marchés et données prudentielles sont entièrement fictifs et ne constituent pas une simulation réglementaire certifiée.

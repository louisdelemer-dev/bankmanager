# BANK MANAGER — Alpha 0.5

Simulateur bancaire personnel, fictif, entièrement local. Déployable directement sur GitHub + Netlify, sans npm, sans Supabase ni backend.

## Installation

Décompresser le ZIP, placer `index.html`, `app.js`, `style.css`, `netlify.toml`, `README.md` à la racine du dépôt GitHub. Sur Netlify, laisser **Build command** vide et **Publish directory** à `.`.

## Principales fonctions

- Direction : jeu à horloge accélérée, objectifs, réputation, satisfaction, conseils et événements économiques.
- Clients : ouvertures automatiques par le siège, évolution du portefeuille, départs pour tarification ou service insuffisants.
- Comité de crédit : demandes montées par les conseillers, acceptation, refus, contre-propositions avec réponse différée.
- Marketing : campagnes segmentées avec budget et durée, conversion influencée par les prix et la réputation.
- Offres : tarifs et taux modifiables, concurrence de marché synthétique mensuelle.
- Stratégie : quatre concurrents fictifs, part de marché, progression de missions et actualités de conjoncture.
- Recrutements : agence, siège, salle des marchés ; ouvertures d'agences ; trading synthétique.
- Finances : bilan simplifié avec distinction dépôts, crédits et capitaux propres.
- Sauvegardes : navigateur (localStorage), export/import JSON.

## Mises à jour

Conservez d'abord une sauvegarde JSON de votre partie dans **Sauvegardes**. Remplacez les fichiers de l'ancien dépôt par ceux-ci. La version conserve la clé `bank-manager-alpha-01` et complète les parties anciennes avec les nouveaux modules.

## Important

Les taux, banques concurrentes, équilibres prudentiels, scores de risque et mouvements économiques sont fictifs. Il s'agit d'un jeu sérieux, pas d'un système bancaire ni d'un outil professionnel de conseil. Le ratio de fonds propres affiché est indicatif et ne représente pas un ratio CET1 réglementaire. Les données sont stockées dans le navigateur et peuvent être perdues si son stockage est effacé.

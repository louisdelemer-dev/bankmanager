# BANK MANAGER — Alpha 0.1

Simulateur personnel de gestion d'une banque régionale française. **Aucun serveur applicatif, aucun Supabase, aucune dépendance npm**. Banque, clients, transactions et marchés entièrement fictifs.

## Publication GitHub + Netlify
1. Créer un dépôt GitHub (`bank-manager`).
2. Déposer les fichiers `index.html`, `style.css`, `app.js`, `netlify.toml` à la **racine**.
3. Dans Netlify : Import existing project → GitHub ; **build command vide** ; **publish directory `.`** ; base directory vide.
4. Ouvrir le site pour jouer.

## Sauvegardes
Sauvegarde automatique dans `localStorage` du navigateur et export/import JSON via Paramètres. Ne pas utiliser le mode privé pour conserver une partie. Exporter régulièrement une copie locale ; vider les données du navigateur les efface.

## Règles V1
- Simulation horaire, vitesse x1/x4/x12 et saut +1 jour / +30 jours.
- Agences, clients fictifs, dépôts, crédits, intérêts, commissions, incidents, salaires, charges fixes, marché synthétique, portefeuille et recrutement.
- Bilan simplifié cohérent : `cash + prêts + titres = dépôts + financement + fonds propres` (avec un compte de résultats et frais provisionnés pris en compte).
- Les dépôts clients sont des **passifs**, les crédits des **actifs** ; octroyer un crédit crée un dépôt et un crédit de même montant.
- Les opérations de marché restent des simulations synthétiques sans données réelles.
- Ratio de fonds propres approximatif à vocation ludique, **pas un calcul réglementaire CRR**. Cette version ne remplace ni comptabilité ni logiciel bancaire réel.

## Tests manuels conseillés
Créer un client, ouvrir un dépôt, octroyer un crédit, recruter un salarié, ouvrir une agence, acheter des titres, passer 30 jours, enregistrer/exporter/importer la partie. Vérifier la cohérence du bilan dans Finances.

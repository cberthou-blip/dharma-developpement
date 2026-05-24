# Note de contexte — dharma-developpement.fr

Date : 24/05/2026  
Dépôt : `cberthou-blip/dharma-developpement`  
Domaine principal : `dharma-developpement.fr`

## 1. Objet

Cette note consolide le contexte utile autour de **Dharma Développement / Dharma Dev** pour servir de base au futur site, aux offres et aux SaaS rattachés.

Sources utilisées :

- mémoire projet ;
- échanges récents ;
- Gmail, uniquement pour confirmer le domaine, Gandi et Stripe ;
- GitHub, pour identifier le dépôt.

Aucun secret, token, clé API ou identifiant sensible n’est volontairement stocké ici.

## 2. Identité commerciale

- L’entreprise individuelle dispose d’un SIREN.
- Le nom commercial envisagé / utilisé est **Dharma Développement**.
- Variante courte déjà utilisée : **Dharma Dev**.
- Le domaine principal est **dharma-developpement.fr**.
- Le domaine a été confirmé comme créé chez **Gandi**.
- L’organisation Gandi mentionne **Dharma Dev**.

Positionnement général : structure commerciale chapeau pour des services, outils IA, automatisations et SaaS.

## 3. Stripe et paiements

Contexte confirmé par Gmail :

- un compte Stripe **Dharma dev** est actif en production ;
- Stripe confirme la possibilité d’accepter des paiements réels ;
- un premier paiement réel a été reçu ;
- le compte Stripe est pensé comme compte unique pour plusieurs SaaS.

Règles :

- ne pas créer un compte Stripe par SaaS sans décision explicite ;
- ne pas stocker de clé Stripe dans Git ;
- ne pas stocker de webhook secret ;
- ne pas exposer de détail de paiement client dans le dépôt.

## 4. Rôle prévu de dharma-developpement.fr

Le site doit devenir le socle commercial des activités numériques et IA.

Rôles possibles :

1. site vitrine de Dharma Développement ;
2. point d’entrée commercial pour les SaaS ;
3. page de confiance pour les paiements Stripe ;
4. présentation des offres IA, automatisation et gouvernance légère ;
5. support de crédibilité pour TPE, PME, indépendants et dirigeants.

Le site doit rester sobre, clair, sérieux et orienté conversion.

## 5. Positionnement stratégique

Dharma Développement doit aider les entreprises à :

- identifier des cas d’usage IA utiles ;
- structurer leurs pratiques IA ;
- automatiser des tâches simples mais coûteuses ;
- mettre en place des outils web sobres ;
- formaliser une gouvernance légère ;
- produire des documents, registres, synthèses ou workflows exploitables.

Formulation cible :

> Dharma Développement conçoit des outils simples pour aider les entreprises à structurer, automatiser et piloter leurs usages numériques et IA.

À éviter : une posture vague d’« agence IA ».

## 6. Principes commerciaux

- Viser un vrai business, pas une collection d’outils gratuits.
- Privilégier des SaaS payants dès la V1 quand le produit s’y prête.
- Ne pas trop mettre en avant le mot “gratuit”.
- Préférer : essai, bêta privée, accès limité, offre payante, compte précréé.
- Ne pas inciter artificiellement à “prendre un accès”.
- Afficher clairement les fonctionnalités réservées aux offres payantes, sans ton agressif.
- Faire une passe “premium +20 %” sur les interfaces SaaS avant ouverture publique.

## 7. Projets liés

### Dharma Pilot

Contexte mémoire :

- outil B2B de pilotage de l’adoption IA par métier ;
- cible : dirigeants PME/ETI, DRH, DSI, transformation, conformité, formation ;
- produit cœur vendable seul ;
- extensions envisagées : Adoption et Learning ;
- fonctionnement historique : mode invité et stockage local ;
- vitrine publique séparée de l’application ;
- projet local connu : `C:\Users\cbert\Documents\Dev\dharma` ;
- Firebase historique : `adoptia-842d9` ;
- version fiable connue : V1.0 vendable.

Fonctions connues :

- cartographie métiers ;
- bibliothèque d’usages IA ;
- registre IA ;
- calculateur de gains ;
- diagnostic de maturité ;
- plan d’action 90 jours ;
- restitution dirigeant.

Attention : `dharma-developpement.fr` ne doit pas être un simple duplicat de Dharma Pilot. Le site doit porter la marque commerciale globale.

### Mon Registre IA

- SaaS orienté registre, conformité et pilotage des usages IA.
- Projet en phase de sécurisation / qualification / bêta privée.
- Logique commerciale : payant, pas gratuit par défaut.
- Peut être porté commercialement par Dharma Dev.

### CoPierre

- SaaS autour de la gestion SCI, biens, AG, PV et finances.
- Projet avancé : Stripe, sécurité, QA, production, onboarding, UI/UX.
- Sert de modèle de processus SaaS pour les prochains produits.

### charlesberthou.fr

- Site personnel déjà recentré autour d’un hub d’outils IA.
- Plusieurs outils et pages IA existent déjà.
- Dharma Développement doit être plus commercial, plus clair et moins personnel.

## 8. Offres possibles

### Diagnostic IA PME

- analyse de maturité ;
- cas d’usage prioritaires ;
- plan d’action 30 / 60 / 90 jours.

### Registre IA léger

- usages IA ;
- niveau de risque ;
- responsable ;
- données manipulées ;
- preuves et règles internes.

### Automatisation simple

- formulaire intelligent ;
- génération de document ;
- workflow email ;
- export PDF / CSV ;
- mini-dashboard.

### Mini SaaS métier

- outil web spécialisé ;
- paiement Stripe ;
- authentification ;
- espace client ;
- documentation et support minimal.

## 9. Cibles prioritaires

- dirigeants de TPE / PME ;
- indépendants ;
- professions libérales ;
- SCI et gestion patrimoniale ;
- responsables administratifs ;
- structures qui veulent formaliser sans complexifier.

Éviter une cible trop large du type “toutes les entreprises intéressées par l’IA”.

## 10. Ton public recommandé

- français de France ;
- sobre ;
- direct ;
- sérieux ;
- concret ;
- orienté problème client ;
- peu de jargon ;
- phrases courtes ;
- bénéfices visibles rapidement.

À éviter :

- promesses excessives ;
- discours trop startup ;
- références bancaires internes ;
- contenu trop personnel ;
- vocabulaire technique visible ;
- mentions du type “projet interne”, “V0.9”, “Firebase non configuré”, “Stripe à connecter”.

## 11. Pages probables du site

V1 simple :

1. Accueil ;
2. Services ;
3. Outils / SaaS ;
4. Cas d’usage ;
5. À propos ;
6. Contact ;
7. Mentions légales ;
8. Confidentialité ;
9. CGV si vente directe.

## 12. Message d’accueil possible

Titre :

> Des outils simples pour piloter vos projets numériques et IA

Sous-titre :

> Dharma Développement aide les petites entreprises à structurer leurs usages IA, automatiser leurs tâches répétitives et créer des outils web utiles, sans complexité inutile.

CTA principal :

> Présenter mon besoin

CTA secondaire :

> Voir les outils

## 13. Architecture à prévoir

À cadrer avant développement :

- hébergement ;
- DNS Gandi ;
- redirection `www` ;
- email de contact ;
- formulaire fiable ;
- pages légales ;
- relation exacte avec les SaaS existants ;
- nom affiché sur les factures ;
- analytics sobres ;
- politique de support.

## 14. Sécurité et conformité

Règles permanentes :

- aucun secret dans Git ;
- pas de clé Stripe dans le front ;
- pas de token Firebase, Resend ou Gandi dans le dépôt ;
- séparer notes internes et contenu public ;
- prévoir mentions légales, confidentialité et CGV ;
- vérifier le statut exact EI / nom commercial / SIREN avant publication.

## 15. Décision de départ recommandée

Construire `dharma-developpement.fr` comme **site commercial chapeau**, non comme duplicat de Dharma Pilot.

Priorité V1 :

1. crédibiliser Dharma Développement ;
2. expliquer l’offre en moins de 10 secondes ;
3. orienter vers contact ou outils ;
4. préparer Stripe et les pages légales ;
5. servir de base commune aux SaaS actuels et futurs.

## 16. Prochaine action logique

Créer ensuite un prompt Codex pour :

1. initialiser proprement le projet web ;
2. proposer une architecture simple ;
3. créer la première version du site ;
4. connecter progressivement DNS, email, formulaire et pages légales ;
5. ne rien casser côté SaaS existants.

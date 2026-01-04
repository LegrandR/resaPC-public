
**Projet ResaPC — Guide public**

**Résumé :**
- **Projet :** ResaPC (système de gestion de planning et de réservation de ressources).
- **But :** Permettre la consultation et la gestion des disponibilités, réservations, comptes utilisateurs et outils d'administration pour des structures (salles, activités, etc.).

**Public cible :**
- **Visiteurs :** personnes non authentifiées.
- **Utilisateurs :** personnes authentifiées (compte personnel).
- **Administrateurs :** comptes disposant de l'interface d'administration complète.

**Principes d'accès (hiérarchie)**
- Un **Utilisateur** a accès à tout ce qu'un **Visiteur** peut faire, plus des actions supplémentaires.
- Un **Administrateur** a accès à tout ce qu'un **Utilisateur** peut faire, plus l'interface d'administration complète.

**Fonctionnalités par type d'utilisateur**

**Visiteur** :
- **Consulter le planning :** vue publique des créneaux et disponibilités (lecture seule).
- **Rechercher des ressources :** filtrer par date, type de ressource, activité.
- **Voir les informations publiques :** description des salles/activités, horaires et règles de réservation.

**Utilisateur (authentifié)** — inclut les actions du Visiteur :
- **Créer et gérer ses réservations :** ajouter, modifier ou annuler ses propres réservations selon les règles et permissions.
- **Mon espace / Profil :** consulter et éditer les informations de son compte (email, mot de passe, préférences).
- **Notifications :** recevoir des alertes sur confirmations, annulations ou modifications.
- **Exporter / imprimer :** visualiser et exporter son planning (PDF/CSV selon configuration).
- **Historique :** consulter l'historique de ses réservations et actions.

**Administrateur** — inclut les actions de l'Utilisateur :
- **Interface d'administration complète :** accès à un tableau de bord administratif.
- **Gestion des utilisateurs :** créer, modifier, désactiver ou supprimer des comptes, réinitialiser des mots de passe.
- **Gestion des ressources :** ajouter/modifier/supprimer des salles, types de ressources, attributs (capacité, équipement, type de salle).
- **Gestion des réservations :** visualiser et modifier toutes les réservations, forcer annulations, valider demandes.
- **Politique et règles :** paramétrer règles de réservation (plages horaires autorisées, limitations, validations automatiques ou manuelles).
- **Import / Export et snapshots :** importer des plannings, exporter des états, créer et restaurer des snapshots de planning.
- **Analyse et conflits :** outils d'aide (détection et résolution de conflits, services d'auto-placement et cascade placement).
- **Verrouillage et logs :** gérer verrous de modification, consulter les journaux d'activité et d'audit.
- **Paramètres système :** accès à la configuration globale, options de planification et paramètres avancés.

**Sécurité et confidentialité**
- Les mots de passe sont gérés via des mécanismes de hachage sécurisés.
- Les administrateurs doivent limiter l'accès aux interfaces d'administration et tenir des logs d'audit.

**ResaPC — Guide grand public**

Résumé
- ResaPC est une application de consultation et de réservation de ressources (salles, activités, créneaux). Elle aide les personnes et les organisations à voir les disponibilités, réserver des créneaux et gérer les réservations simplement.

À qui s'adresse ResaPC
- Visiteurs : toute personne qui consulte le planning sans être connectée.
- Utilisateurs : personnes ayant un compte et pouvant gérer leurs réservations.
- Administrateurs : personnes gérant l'organisation (salles, comptes, règles).

Important — hiérarchie des accès
- Les actions sont inclusives : ce qu'un Visiteur peut faire est accessible à l'Utilisateur, et ce qu'un Utilisateur peut faire est accessible à l'Administrateur. Les sections ci‑dessous décrivent d'abord les actions publiques puis les ajouts pour les rôles supérieurs.

Fonctionnalités détaillées (rôle & objectif)

Visiteur — que pouvez-vous faire et pourquoi ?
- Consulter le planning : voir rapidement qui utilise quoi et quand. Objectif : décider si un créneau vous convient.
- Rechercher des ressources : filtrer par date, type d'espace ou activité. Objectif : trouver une salle ou un atelier adapté à vos besoins.
- Lire les informations publiques : description des salles, capacités, équipements et règles. Objectif : vérifier si la ressource correspond à vos besoins avant toute réservation.

Utilisateur (connecté) — en plus des actions du Visiteur
- Créer une réservation : réserver un créneau pour vous ou votre activité. Objectif : garantir la disponibilité d'une salle à un moment donné.
- Modifier / annuler une réservation : ajuster vos besoins ou libérer un créneau. Objectif : garder vos réservations à jour et éviter les conflits.
- Mon profil : mettre à jour vos coordonnées et préférences. Objectif : recevoir les notifications correctes et simplifier les échanges.
- Notifications : recevoir confirmations et rappels par email ou via l'interface. Objectif : ne pas oublier une réservation ou être informé d'un changement.
- Historique et justificatifs : consulter vos anciennes réservations et obtenir un récapitulatif imprimable. Objectif : conserver une trace ou produire des justificatifs si nécessaire.

Administrateur — en plus des actions de l'Utilisateur
- Gérer les comptes : créer ou aider des utilisateurs (réinitialiser un mot de passe). Objectif : maintenir un accès maîtrisé et soutenir les usagers.
- Gérer les ressources : ajouter ou modifier les salles, capacités et équipements. Objectif : tenir à jour l'offre disponible pour les réservations.
- Superviser les réservations : intervenir en cas de conflit, valider des demandes spéciales. Objectif : garantir la bonne organisation et résoudre les problèmes humains ou techniques.
- Définir les règles : limiter les plages réservables, définir des conditions (durée max, validations). Objectif : appliquer la politique d'utilisation propre à votre structure.

Comment signaler un bug (procédure via GitHub)
1. Rendez‑vous sur la page du projet sur GitHub (onglet « Issues »).
2. Cliquez sur « New issue » (Nouvelle issue).
3. Donnez un titre clair et résumez le problème en une ligne.
4. Décrivez le problème en détail :
	- Ce que vous vouliez faire (objectif).
	- Ce que vous avez fait (étapes précises pour reproduire le problème).
	- Ce qui s'est passé réellement (message d'erreur, comportement inattendu).
	- Ce que vous attendiez (résultat attendu).
5. Ajoutez des informations utiles : navigateur et version (ou application), date et heure, captures d'écran, et si possible des fichiers de logs.
6. Si le sujet est sensible (donnée personnelle ou faille de sécurité), ne publiez pas ces détails publiquement : envoyez un message privé aux responsables (voir `documents légaux/AUTHORS.md`) ou écrivez à l'adresse de contact indiquée.
7. Choisissez un label si demandé (bug, enhancement, question) et soumettez.

Objectif de cette procédure : permettre une résolution rapide et claire en donnant aux développeurs toutes les informations nécessaires pour reproduire et corriger le problème.

Support et contact
- Pour une question d'utilisation : ouvrir une issue ou contacter votre administrateur local.
- Pour une demande fonctionnelle ou une amélioration : suggérez-la via une issue en expliquant l'usage attendu.
- Pour des questions légales ou de confidentialité : consultez `documents légaux/AUTHORS.md`.

Mentions légales et contributeurs
- Les informations sur la licence et les contributeurs se trouvent dans `documents légaux/LICENSE.md` et `documents légaux/AUTHORS.md`.





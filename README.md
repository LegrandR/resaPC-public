# Bienvenue sur ResaPC - Guide Utilisateur

**ResaPC** est la solution centralisée de gestion des plannings et de réservation de salles de votre établissement. Elle facilite la coordination entre l'administration, les enseignants et le personnel technique pour garantir une organisation fluide des cours, des travaux pratiques et des événements.

Ce guide vous détaille les fonctionnalités disponibles selon votre profil et vous explique comment tirer le meilleur parti de l'application.

---

## 👥 Vos accès selon votre profil

ResaPC adapte ses fonctionnalités selon votre rôle. Voici ce que vous pouvez faire :

### 👀 1. Visiteur (Accès public)
*Profil par défaut pour les consultation sans connexion (ex: élèves, parents sur borne).*

*   **Consultation du Planning par classe** : Accès à l'emploi du temps par classe de l'établissement.

### 🎓 2. Utilisateur (Enseignant / Personnel)
*Nécessite une connexion avec identifiant et mot de passe.*
*Inclut toutes les fonctionnalités Visiteur, plus :*

*   **Gestion des Réservations** :
    *   **Réserver** : Effectuer une demande de réservation pour une salle spécifique ou un équipement.
    *   **Modifier / Annuler** : Ajuster vos demandes en cas de changement de programme ou d'imprévu.
    *   **Suivi** : Consulter l'état de vos demandes (En attente, Validée, Refusée).
*   **Espace Personnel** :
    *   **Mon Planning** : Une vue filtrée affichant uniquement *vos* cours et réservations.
    *   **Profil** : Mettre à jour vos informations (email, préférences).
    *   **Historique** : Retrouver la trace de toutes vos actions passées.
*   **Notifications** : Recevoir des alertes (email ou visuelles) lors de la validation de vos demandes.

### 🧪 3. Laboratoire
*Destiné aux préparateurs et responsables de laboratoires de sciences.*

*   **Gestion des TP** : Vue prioritaire sur les salles de Travaux Pratiques (Chimie, Physique, SVT).
*   **Coordination Matériel** : Permet de voir quels cours nécessitent du matériel expérimental.
*   **Validation Technique** : (Si activé) Possibilité de valider la faisabilité technique d'une demande de salle de TP.

### ⚙️ 4. Administrateur
*Direction, Vie Scolaire et Gestionnaires.*

*   **Pilotage Global** : Contrôle total sur l'ensemble des plannings (toutes classes, toutes salles).
*   **Centre de Validation** : Traitement des demandes des utilisateurs (Système de Tickets). Vous pouvez accepter, refuser ou demander des précisions.
*   **Gestion des Données** :
    *   **Utilisateurs** : Création de comptes, réinitialisation de mots de passe, gestion des rôles.
    *   **Ressources** : Ajout/Modification de salles, définition des capacités.
    *   **Règles** : Définition des périodes scolaires, des jours fériés et des contraintes de réservation.
*   **Outils Avancés** :
    *   **Import/Export** : Récupération de données depuis d'autres logiciels ou export pour archivage.
    *   **Snapshots** : Sauvegarde ponctuelle de l'état du planning pour sécuriser les modifications importantes.

---

## 🛠 Fonctionnement de l'Application

### Le Système de "Tickets"
Pour éviter les conflits (deux cours dans la même salle), ResaPC utilise un système de demande asynchrone :
1.  **Demande** : Vous cliquez sur un créneau libre et remplissez le formulaire (Motif, classe, type de salle souhaité).
2.  **Ticket Créé** : Votre demande apparaît sur le planning en "Attente" (couleur orange ou hachurée) et un "Ticket" est généré pour l'administration.
3.  **Traitement** : Un administrateur examine la demande. S'il l'accepte, le créneau devient "Validé" (couleur fixe). S'il refuse, le créneau est libéré et vous êtes notifié du motif.

### Types de Vues
*   **Planning Général** : Vue d'ensemble (Lundi au Samedi). Idéal pour voir l'occupation globale.
*   **Vue par Salle** : Permet de voir l'occupation d'une salle spécifique sur la semaine. Utile pour trouver un "trou" dans l'emploi du temps d'une salle informatique par exemple.
*   **Vue par Classe** : Affiche l'emploi du temps d'une classe spécifique.

---

## À propos
  ResaPC est conçu, développé et maintenu par LegrandR (contact.resapc@gmail.com),
  seul auteur et propriétaire du code, de l'instance et de l'hébergement.
  - Instance de pré-production (bêta) : https://resapc.duckdns.org
  - Code source : dépôt privé (accès sur demande)


## 🐛 Signaler un Bug ou un Problème

Si vous rencontrez une erreur technique ou un comportement inattendu, merci de suivre cette procédure pour nous aider à le corriger rapidement :

1.  **Rendez‑vous sur GitHub** : Allez sur la page du projet (onglet « Issues »).
2.  **Créer une Issue** : Cliquez sur « New issue ».
3.  **Décrire le problème** :
    *   **Titre** : Résumé court du problème.
    *   **Contexte** : Ce que vous essayiez de faire.
    *   **Étapes** : La suite d'actions précises qui a mené à l'erreur (ex: "J'ai cliqué sur Planning > Mardi 8h > Valider").
    *   **Résultat** : Ce qui s'est affiché (message d'erreur, page blanche...).
4.  **Détails Techniques** : Précisez votre navigateur (Chrome, Firefox...), l'heure de l'incident, et ajoutez des captures d'écran si possible.
5.  **Confidentialité** : Ne postez **jamais** de données personnelles (noms d'élèves, mots de passe) sur GitHub. Pour les problèmes sensibles, contactez directement l'administrateur de l'établissement.

---

## 📞 Support et Contact

*   **Problème de compte / Mot de passe perdu** : Contactez l'administrateur ResaPC de votre établissement.
*   **Question sur une réservation** : Adressez-vous à la Vie Scolaire ou au gestionnaire de planning.

---
*ResaPC - Simplifiez votre organisation scolaire.*

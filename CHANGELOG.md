## Pre-release : 2026-01-03
 - Création d'un dépot github
 - Ajout de la licence, liste des auteurs et politique de confidentialité
 
 ## v0.1.0beta : 2026-01-04
  - redaction du README
  - Corrections multiples d'erreur de comportement du planing général
  - Ajout d'options de menu pour annuler les placements
  - Modification du layout général du planning personnel :ajout de visuels pour les tickets et menus contextuels pour modification des tickets.
  - Corrections de bugs associés à l'interface du planning personnel.
  
   ## v0.2.0beta : 2026-01-05
  - Ajout d'une condition de detection de conflit lié aux utilisateurs : il est interdit de créer un créneau pour lequel l'utilisateur a déjà un autre créneau qui chevauche
  - Bug : "Refuser la demande" n'efface pas tout le temps une demande dans le planning global.
  - Amélioration du scrolling automatique dans le planning global.
  - Bug : Au refresh, les créneaux temporaires voyaient leur hauteur réduite.
  - Le marquage des conflits est maintenant appliqué lorsqu'on utilise la fonction "Accepter" (de la même manière que la fonction "Vérifie").
  - Correction du bug #7 lié à la fonction "annuler"
  - Ajout d'un système de notes plus complet associés aux créneaux
  - Ajout d'un système de messagerie entre utilisateur et administrateur associés aux tickets.
   
   ## v0.3.0beta : 2026-01-06
  - Modification de l'UI "Gestion des activités" pour permettre une présaisie du nombres d'élèves et du type de salle en fonction de l'activité.
  - Création de deux nouveaux rôles "laboratoire" et "Gestionnaire".
  - Modification du mode "lock" : un nouveau bouton apparait sur les comptes éditeur pour verrouiller l'édition des autres comptes éditeurs.
  - Modification raccourci administrateur : un bug renvoyait vers les tickets personnels au lieu de l'interface de gestion des tickets.
  
   ## v0.4.0beta : 2026-01-07
  - Bug fix : un créneau déjà placé par un administrateur n'est pas replacé de nouveau quand on lance le placement automatique. Seuls les créneaux issues de la zone de demandes sont placés automatiquement.
  - Ajout d'un menu sous le clic droit : placer ce créneau, permettant un placement automatique du créneau concerné.
  - Placement "Auto" place automatiquement les créneaux sous conflit (rouge), les créneaux sous demande de modification (violet) et les créneaux de la zone "demandes".
  - Ajout d'une logique d'épinglage pour interdire le placement automatique et le déplacement de créneau (fonctionne pour tout type de créneau. Ils sont ignorés de la fonction placement automatique et ne peuvent pas être déplacé par cette dernière).
  
  ## v0.5.0beta : 2026-01-16
  - Reprise du planning pour restructuration compléte : implémentation du planning générale V2
  
  ## v0.6.0beta : 2026-01-22
  - Réécriture de la database pour utiliser une logique multiétablissement
  - utilisation généralisé de wrapper sur les appels DB pour assurer l'utilisation d'un filtre établissement relatif à l'utilisateur
  
  ## v0.7.0beta : 2026-01-26
  - Modification du système d'inscription et de promotion des administrateurs
  - Ajout d'utilisateur virtuel
  
  ## v0.8.0beta : 2026-01-26
  - Refonte du système d'importation : utilisation directe de PDF ou ICS dans l'application.
  
  ## v0.9.0beta : 2026-01-29
  - Audit de securité et amélioration du code vis à vis de la sécurité de l'application
  - Ajout pepper dans l'encodage des mots de passe.
  
  ## v0.10.0beta : 2026-01-31
  - Audit de performance et amélioration des performances generales de l'application : refactorisation et modification des queries.
  
  ## v0.11.0beta : 2026-02-01
  - Ajout outils de monitoring et logging.
  
  ## v0.12.2 : 2026-02-15
  - Ajout politique CSP
  - Ajout systeme de rotation des secrets applicatifs
  - Corrections de bugs divers
  - Amélioration du logging d'erreurs
  - Ajout multiples CSV pour classe/salle/activités
  
  ## v0.13.0 : 2026-02-19
  - Corrections de bugs multiples dans le planning générale
  - Ajout d'une interface d'édition des alias et clés de reconnaissance pour l'importation de planning.
  - Correction d'erreur d'affichages.
  - Ajout de l'export pdf par jour et par semaine.
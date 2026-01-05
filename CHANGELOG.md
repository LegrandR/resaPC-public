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
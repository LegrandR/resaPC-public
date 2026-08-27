## Pre-release : 2026-01-03
 - Création d'un dépôt github
 - Ajout de la licence, liste des auteurs et politique de confidentialité
 
## v0.1.0beta : 2026-01-04
 - rédaction du README
 - Corrections multiples d'erreur de comportement du planning général
 - Ajout d'options de menu pour annuler les placements
 - Modification du layout général du planning personnel : ajout de visuels pour les tickets et menus contextuels pour modification des tickets
 - Corrections de bugs associés à l'interface du planning personnel
  
## v0.2.0beta : 2026-01-05
 - Ajout d'une condition de détection de conflit lié aux utilisateurs : il est interdit de créer un créneau pour lequel l'utilisateur a déjà un autre créneau qui chevauche
 - Bug : "Refuser la demande" n'efface pas tout le temps une demande dans le planning global
 - Amélioration du scrolling automatique dans le planning global
 - Bug : A la mise à jour, les créneaux temporaires voyaient leur hauteur réduite
 - Le marquage des conflits est maintenant appliqué lorsqu'on utilise la fonction "Accepter" (de la même manière que la fonction "Vérifie")
 - Correction du bug #7 lié à la fonction "annuler"
 - Ajout d'un système de notes plus complet associés aux créneaux
 - Ajout d'un système de messagerie entre utilisateur et administrateur associés aux tickets
   
## v0.3.0beta : 2026-01-06
 - Modification de l'UI "Gestion des activités" pour permettre une pré-saisie du nombre d'élèves et du type de salle en fonction de l'activité
 - Création de deux nouveaux rôles "laboratoire" et "Gestionnaire"
 - Modification du mode "lock" : un nouveau bouton apparait sur les comptes éditeur pour verrouiller l'édition des autres comptes éditeurs
 - Modification raccourci administrateur : un bug renvoyait vers les tickets personnels au lieu de l'interface de gestion des tickets
  
## v0.4.0beta : 2026-01-07
 - Bug fix : un créneau déjà placé par un administrateur n'est pas replacé de nouveau quand on lance le placement automatique. Seuls les créneaux issus de la zone de demandes sont placés automatiquement
 - Ajout d'un menu sous le clic droit : placer ce créneau, permettant un placement automatique du créneau concerné
 - Placement "Auto" place automatiquement les créneaux sous conflit (rouge), les créneaux sous demande de modification (violet) et les créneaux de la zone "demandes"
 - Ajout d'une logique d'épinglage pour interdire le placement automatique et le déplacement de créneau (fonctionne pour tout type de créneau. Ils sont ignorés de la fonction placement automatique et ne peuvent pas être déplacé par cette dernière)
  
## v0.5.0beta : 2026-01-16
 - Reprise du planning pour restructuration complète : implémentation du planning générale V2
  
## v0.6.0beta : 2026-01-22
 - Réécriture de la database pour utiliser une logique multi-établissement
 - utilisation généralisé de wrapper sur les appels DB pour assurer l'utilisation d'un filtre établissement relatif à l'utilisateur
  
## v0.7.0beta : 2026-01-26
 - Modification du système d'inscription et de promotion des administrateurs
 - Ajout d'utilisateur virtuel
  
## v0.8.0beta : 2026-01-26
 - Refonte du système d'importation : utilisation directe de PDF ou ICS dans l'application
  
## v0.9.0beta : 2026-01-29
 - Audit de sécurité et amélioration du code vis à vis de la sécurité de l'application
 - Ajout pepper dans l'encodage des mots de passe.
  
## v0.10.0beta : 2026-01-31
 - Audit de performance et amélioration des performances générales de l'application : refactorisation et modification des queries
  
## v0.11.0beta : 2026-02-01
 - Ajout outils de monitoring et logging.
  
## v0.12.2 : 2026-02-15
 - Ajout politique CSP
 - Ajout système de rotation des secrets applicatifs
 - Corrections de bugs divers
 - Amélioration du logging d'erreurs
 - Ajout multiples CSV pour classe/salle/activités
  
## v0.13.0 : 2026-02-19
 - Corrections de bugs multiples dans le planning générale
 - Ajout d'une interface d'édition des alias et clés de reconnaissance pour l'importation de planning.
 - Correction d'erreur d'affichages.
 - Ajout de l'export pdf par jour et par semaine.

## v0.14.0 : 2026-03-20
 - Implémentation d'un worker asynchrone
 - Mise en place de sauvegarde globale par établissement (snapshots)

## v0.15.0 : 2026-03-22
 - Implémentation du menu "Mes protocoles"

## v0.16.0 : 2026-03-22
 - Implémentation de workers multiples.
  
## v0.17.0 : 2026-03-30
 - Amélioration de la prise en charge de l'expiration de session
 - Amélioration de la typographie dans les protocoles
 - Amélioration de fenêtres de confirmation
 - Amélioration de la gestion de la liste du matériel pour les protocoles
 
## v0.18.0 : 2026-04-16
 - Amélioration de la logique de suppression de comptes
 - Les emails envoyés sur les boites professionnels arrivent maintenant de manière fiable
  
## v0.19.0 : 2026-04-25
 - Implémentation d'une version de démonstration (beta)
 - Amélioration mineur des notations scientifiques et mise en page de l'export pdf pour les protocoles
 - Correction d'un but empêchant la génération de l'export pdf pour les protocoles
 - Ajout d'un formulaire de demande d'inscription d'un établissement.

## v0.19.1 : 2026-04-26
 - Amélioration de l'interface de réservation

## v0.20.0 : 2026-05-01
 - Ajout de pièces jointes pour les notes de protocole
 - Ajout d'un quota utilisateur pour ces pièces jointes
 - Modification de l'export PDF pour inclure des images dans les notes de protocole.

## v0.21.0 : 2026-05-05/1
 - Ajout d'extensions pour les images téléversées
 - Changement de standard de stockage pour AVIF
 - Ajout application mobile pour téléversement d'images/fichiers

## v0.22.0 : 2026-05-05/2
 - Mise à jour php 8.2 vers php 8.4

## v0.22.1 : 2026-05-06
 - Amélioration du fonctionnement de l'interface de rapport de bugs
 - Amélioration du fonctionnement de l'interface d'envoi de messages
 
## v0.23.0 : 2026-05-15
 - Implémentation d'un système de news
 - Correction d'un bug empêchant un gestionnaire d'avoir accès au planning général

## v0.24.0 : 2026-05-27
 - Implémentation d'une application mobile PWA pour les opérations simples de consultation

## v0.24.1 : 2026-06-01
 - Implémentation d'une application mobile pour visiteur : consultation du planning d'une classe

## v0.24.2 : 2026-06-04
 - Correction de bugs : 
	- les tickets traités ou supprimé n'apparaitront plus dans la zone de demandes
	- le saut de date journalier faisait parfois sauter plusieurs années
	- le filtre de tickets déjà existant dans le processus d'import va maintenant ignorer les tickets traités ou supprimés
	- les tickets "toute l'année" seront maintenant correctement interprété dans le processus d'import d'emploi du temps
 - Amélioration du placement auto : maintenant le système cherchera à placer un même utilisateur dans la même salle si les créneaux se suivent.
 - Ajout d'une option d'export de planning dans /laboratory/planning
 
## v0.24.3 : 2026-06-05
 - amélioration de la géométrie du planning général

## v0.24.4 : 2026-06-06
 - amélioration du processus d'importation des emplois du temps : création d'une grille de prévisualisation
 - amélioration de l'affichage des conflits dans le cas où des classes sont partagées en groupes dont l'effectif est inférieur à 100%
 - ajout d'une option de création de planning PDF par utilisateur
 - ajout d'une option de génération pdf en portrait
 - ajout d'un filtre de mise en avant dans le planning général

## v0.24.5 : 2026-06-07
 - ajout d'un modificateur avec la touche "ctrl" :
   - affichage des notes par survol de la souris en appuyant sur ctrl
   - affichage de l'heure dans le planning en appuyant sur ctrl
   - déplacement d'un créneau avec modification automatique de l'heure avec ctrl + déplacement
 - modification de divers menus pour inclure un champ de recherche
 - ajout copier/coller de créneau
 - ajout d'une bascule pour changer les couleurs des créneaux en fonction des activités
 - modification de l'interface de gestion des activités pour y modifier leurs couleurs
 
## v0.25.6 : 2026-06-11
 - ajout d'un redimensionnement de créneau avec enregistrement automatique de l'heure par appuis sur ctrl + clic
 - modification de l'interface de création d'une demande de matériel pour y inclure une sélection de créneau
 
## v0.25.7 : 2026-06-12
 - fiabilisation de la detection du mode édition
 - ajout entrée/sortie automatique du mode édition lors de la création directe de créneau et de la consultation des demandes

## v0.25.8 : 2026-06-13
 - ajout d'une option pour afficher/cacher le mot de passe sur la page d'authentification
 - possibilité de modifier l'ordre des salles affichées dans les planning

## v0.25.9 : 2026-06-15
 - ajout d'une nouvelle relation entre les utilisateurs : la représentation. Un utilisateur peut représenter un autre utilisateur virtuel ou non pour réaliser des demandes de création de créneau et de modification de créneau en son nom

## v0.25.10 : 2026-06-18
 - ajout couper/coller d'un créneau (ctrl+x/v)
 - modification de l'UI planning général et planning laboratoire pour basculer en vue jour/semaine et plein écran
 - correction d'un bug qui empéchait le rôle laboratoire de réaliser les exports pdf
 - modifications mineures sur la structure des exports pdf
 - ajout d'un menu pour modifier les couleurs par défaut

## v0.25.11 : 2026-06-20
 - modification du système de journal
 - ajout d'onglet pour supprimer complétement certaines données liées à l'établissement
 
## v0.25.12 : 2026-06-27
 - correction d'un bugde formatage empéchant la reception d'email sur certaines boites
 - modification du processus de validation de certaines opérations administrateur critiques : une demande de confirmation de mot de passe est redemandé
 - les administrateurs ne sont plus autorisé à modifier l'email des utilisateurs. Les emails sont uniquement modifiables de manière individuelle
 
## v0.25.13 : 2026-07-21
 - remplacement et optimisation du système anti-spam et detection de robots

## v0.25.14 : 2026-08-03
 - correction d'un bug qui empéchait le téléversement de nom de fichiers avec certains caractéres
 - correction d'un bug lors du déplacement de créneau revenant à leur position initiale (couleur non rétablie)

## v0.26.1 : 2026-08-10
 - renforcement structurel du chiffrement et du cloisonnement inter-établissement
 - ajout d'une option pour autoriser ou non l'accés visiteur au niveau de l'établissement

## v0.26.2 : 2026-08-14
 - implémentation d'une architecture modulaire pour le chargement de fonctionnalités
 - passage des outils de gestions des protocoles en fonctionnalité modulaire

## v0.26.3 : 2026-08-26
 - correction de bugs d'interfaces diverses
 - modification de certaines indications dans l'interface
 - ajout d'un menu pour édition plus compléte d'un créneau récurrent à partir de l'interface de modification
 
## v0.26.4 : 2026-08-27
 - ajout modules "Vie de classe" : Plan de classe, Trombinoscope, assistant d'appels (désactivé par défaut)
 - ajout d'un champ de confirmation relatif au droit à l'image avant d'utiliser le module "Trombinoscope"
 - modification du système de colorisation des créneaux avec colorisation croisée Activité/Niveau
 - correction d'un bug dans le wizard d'importation des emplois du temps
 - ajout de l'activité dans le textes d'information des créneaux
# Fiche projet — Équipe N :1

> Livrable L2 · Jalon J1 (samedi 29 août 2026) · validée par l'encadreur référent.
> Aucune fabrication n'est autorisée avant la validation de ce jalon.

## 1. Titre et accroche

Nom du dispositif, une phrase pour le présenter à un chef d'établissement.

DISTRIBUTION AUTOMATIQUE DE DETERGENT, un dispositif intelligent qui délivre automatiquement une quantité contrôlée de détergent, tout en permettant aux éleves de comprendre et de mettre en pratique les principes de l'automatisation

## 2. Besoin et bénéficiaires

La difficulté d'apprentissage visée · les élèves concernés (discipline, niveau, effectif) ·
l'établissement d'accueil.

Difficulté d'appentissage visée: 
* comprendre le fonctionnement d’un capteur ultrasonique et son interaction avec un système automatisé ;
* réaliser le câblage électronique entre le capteur, la carte Arduino et la pompe ;
* comprendre la relation entre détection → traitement de l’information → commande → action ;
* concevoir un boîtier fonctionnel en 3D en tenant compte des dimensions des composants ;
* passer d’une idée ou d’un schéma à un prototype fonctionnel ;
* travailler en équipe et répartir efficacement les tâches entre électronique, conception 3D et fabrication.

Discipline : technologie

niveau : collège

Effectif : 40 élèves par classe

l'etablissement d'accueil: collège scientifique

## 3. Objectifs d'apprentissage

Trois objectifs observables rattachés au programme officiel, chapitre cité.

1.  réaliser un prototype simple
rataché au programme officiel de la classe de 6ème 
* technologie:
 lecon: réalisation du prototype d'une éprouvette graduée(réalisation d'un réservoir) 

* physique: 
THEME 1: electricité
lecon: circuits avec serie, circuit avec dérivation 

2. savoir utiliser fusion 360 dans la coneption assisté par l'ordinateur et dans la fabrication assisté par l'ordinateur ( CAO & FAO) rataché au programme officiel de la classe de 5ème
* technologie:
THEME: outil informatique
lecon : les logiciels

THEME: le dessin technique
lecon: introduction au dessin technique


 et 4ème ( technogie)
 THEME: le dessin technique 
 lecon: le dessin technique

3. Identifier et expliquer le rôle des différents composants d'un système automatique: capteur, unité de commande , actionneur, l'energie solaire et alimentation rataché rataché au programme officiel de la classe de 3ème (Technologie)
lecon: transformation des energies électriques




## 4. Description du dispositif

Ce que l'objet fait · ce que l'élève fait avec · croquis ou esquisse annotée
(versée dans `docs/medias/`).


Le dispositif est un système de distribution automatique de détergent conçu autour d'une carte électronique programmable.
 Il permet de détecter automatiquement la présence d'un utilisateur et de commander une petite pompe afin de distribuer le détergent sans manipulation directe du réservoir.
Le prototype présenté est composé principalement de :
* une carte de commande programmable, permettant de gérer le fonctionnement automatique du système ;
* un capteur à ultrasons, utilisé pour détecter la présence de la main ou du récipient devant le distributeur ;
* une mini-pompe à eau/liquide, chargée d'acheminer le détergent vers la sortie ;
* un panneau solaire, envisagé comme source d'énergie du dispositif ;
* un système d'alimentation/stockage  ( panneaux scolaires et batteries) 
* Des LED, utilisées comme indicateurs de fonctionnement ou d'état ;
* PCB


Principe de fonctionnement
Lorsque l' élève approche sa main ou son récipient de la zone de détection, le capteur mesure la présence de l'objet. La carte de commande ( carte arduino xiao ESP32S3) traite cette information et, si les conditions programmées sont satisfaites, active la pompe pendant une durée déterminée.
Le détergent est alors aspiré depuis le réservoir et distribué à travers le conduit de sortie. À la fin de la durée programmée, la pompe s'arrête automatiquement.

## 5. Architecture technique pressentie

Capteurs · actionneurs · liaison · application · procédés de fabrication envisagés
(au moins trois procédés distincts, exigence ET-FAB-02).

Capteur- carte de commande- pomme-distribution détergent

## 6. Rôle des élèves

Position sur le continuum POUR / AVEC / PAR et extension PAR décrite (exigence EP-03).

## 7. Ancrage réseau et implantation

Lab de rattachement (CRIT ou établissement) · lieu d'usage · conditions matérielles de la salle.

lieu d'usage: établissement


## 8. Périmètre

| | Contenu |
|---|---|
| Dans la v1.0 (Socle) | |
| En option (Avancé / Expert) | |
| Explicitement exclu | |

## 9. Risques et parades

| Risque | Type | Parade |
|---|---|---|
| | technique | |
| | calendrier | |
| | pédagogique | |


## 9. Risques et parades

| Risques identifiés | Parades / mesures préventives |
|---|---|
| Détection incorrecte de la main | Tester et ajuster la distance de détection du capteur ultrasonique. |
| Pompe qui ne fonctionne pas | Vérifier les connexions, l’alimentation et le câblage avant les essais. |
| Fuite de détergent | Vérifier l’étanchéité du réservoir, du tuyau et des raccordements. |
| Court-circuit électrique | Isoler correctement les connexions et protéger les composants électroniques contre le liquide. |
| Débordement du détergent | Prévoir un dosage adapté et limiter la durée de fonctionnement de la pompe. |
| Boîtier mal dimensionné | Vérifier les dimensions des composants avant l’impression 3D et l’assemblage. |
| Panne ou décharge de l’aliment## 9. Risques et parades

| Risques identifiés | Parades / mesures préventives |
|---|---|
| Détection incorrecte de la main | Tester et ajuster la distance de détection du capteur ultrasonique. |
| Pompe qui ne fonctionne pas | Vérifier les connexions, l’alimentation et le câblage avant les essais. |
| Fuite de détergent | Vérifier l’étanchéité du réservoir, du tuyau et des raccordements. |
| Court-circuit électrique | Isoler correctement les connexions et protéger les composants électroniques contre le liquide. |
| Débordement du détergent | Prévoir un dosage adapté et limiter la durée de fonctionnement de la pompe. |
| Boîtier mal dimensionné | Vérifier les dimensions des composants avant l’impression 3D et l’assemblage. |
| Panne ou décharge de l’alimentation | Vérifier régulièrement l’état de l’alimentation et prévoir une solution de secours pour les tests. |
| Mauvaise utilisation par les apprenants | Prévoir une démonstration, des consignes d’utilisation et une signalétique claire. |

## 10. Budget matière estimé

Grandes masses en FCFA, au regard de la dotation (plafond indicatif : 60 000 FCFA).


## 11. Licences et diffusion

Licences choisies et motivation · accord de l'équipe pour la mise en avant réseau.

## Exemptions demandées

- [ ] ET-FAB-06 (moulage) — justification :
- [ ] ET-MEC-01 (fonction motorisée) — justification :

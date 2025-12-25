# **Consignes**
## Workshop  
#### Outils
- Installer un émulateur pour la machine choisie  
=> https://fs-uae.net/
- Travailler avec Github education et VScode
Lien Classroom Github
https://classroom.github.com/a/7o-29Ai3
- Travailler avec copilot dans VScode

#### Ce que j'ai utilisé :
Émulateur
- Émulateur : FS-UAE
- Code dans l'émulateur : AMOS PRO 2.0

Visuels
- Dessins : Pixilart, Krita (-> Fichiers _Kexp)
- Gestion de l'échelle et des couleurs : GIMP (-> Fichiers _Gexp)
- Conversion en .iff : XnViewMP (-> Fichiers _Xexp)


## Objectifs
- Écrire un projet : jeu, texte, diaporama, etc.
- Anacronisme entre machine et expérience.

## Rendu 
- Disquette avec jaquette (possible dans tous les cas de figure)
- Émulation
- Scratch (écrit sur la machine)


# **Projet**
## Titre
_My battery is low and it's getting dark_

## Mots-clés
Mars,
Exploration spatiale,
Avancées technologiques

## Description
_My battery is low and it's getting dark_ est un jeu d'exploration où le joueur découvre la planète Mars par les yeux du rover Opportunity.
Une session de jeu retrace les 15 ans de vie du robot à une échelle réduite où 1 an = 40 secondes.

Pas de spoil, vous découvrirez l'histoire par vous-même.

P.S. Je raconte l'histoire parce que je n'ai pas pu finir le projet...
Le joueur fait bouger le sprite du rover Opportunity sur des éléments interactifs qui représentent des éléments que le rover a vu sur Mars (ex : Épave du bouclier thermique en décembre 2004, etc.) avec une petite histoire à chaque fois. Lorsque le compteur arrive à 2018, le message "My battery is low and it's getting dark" apparait et le jeu s'arrête, ces derniers mots étant ceux du petit rover marsien, éteint en 2018.

## Journal de bord
### Comment lancer le jeu
(toutes les étapes ne sont pas à jour dans les dossiers)
1. Télécharger le dossier [MyBatteryIsLow_Game](projets/MyBatteryIsLow/SORTIE/MyBatteryIsLow_Game).
2. Importer la banque [MyBatteryIsLow.Abk](projets/MyBatteryIsLow/img/MyBatteryIsLow.Abk) dans Amos Pro.
3. Importer le script [MyBatteryIsLow.ASC](projets/MyBatteryIsLow/MyBatteryIsLow.ASC).
4. Lancer le jeu.

Maquette de l'aperçu final :  
![Image de l'aperçu du jeu - numéro 1](aperçu/aperçu-du-projet_1.png)
![Image de l'aperçu du jeu - numéro 2](aperçu/aperçu-du-projet_2.png)
![Image de l'aperçu du jeu - numéro 3](aperçu/aperçu-du-projet_3.png)

**Update du 22-12 :** J'ai persévéré au delà de la semaine de cours et j'ai réussi à faire beaucoup de chose !  
**Update du 25-12 :** J'ai fini le jeu !!!!

### Rendu final :

<video controls src="aperçu/jeu-fini.mp4" title="Vidéo de démonstration du jeu fini !"></video>

Fond du jeu :  
![fond marsien](projets/MyBatteryIsLow/img/decors/fond_Gexp.png)

Le joueur :  

![rover](projets/MyBatteryIsLow/img/sprites/rover_pixelart.png)


Les objets à explorer :  

Épave du bouclier thermique, au sud d'Endurance (décembre 2004)  
![epave du bouclier thermique - pixelart](projets/MyBatteryIsLow/img/objets/epave_Gexp.png)  
![image popup de l'épave](projets/MyBatteryIsLow/SORTIE/MyBatteryIsLow_Game/visuels/objets/popup/epave/epave.png)

Météorite Heat Shield Rock (janvier 2005)  
![meteorite heat shield rock - pixelart](projets/MyBatteryIsLow/img/objets/meteorite_Gexp.png)  
![Image popup de la météorite](projets/MyBatteryIsLow/SORTIE/MyBatteryIsLow_Game/visuels/objets/popup/meteorite/meteorite_Kexp_Gexp.png)

Dunes :  
![dunes - pixelart](projets/MyBatteryIsLow/img/decors/dunes.png)  
![Image popup des dunes](projets/MyBatteryIsLow/img/objets-popup/dunes_Kexp_Gexp.png)

La falaise Burns, à l'intérieur du cratère Endurance (décembre 2004) :  
![falaise Burns - pixelart](projets/MyBatteryIsLow/img/decors/roche.png)  
![Image popup des dunes](projets/MyBatteryIsLow/img/objets-popup/falaise_Kexp_Gexp.png)

Le cratère Victoria (septembre 2006) :  
![cratère Victoria - pixelart](projets/MyBatteryIsLow/img/decors/cratere.png)  
![Image popup du cratère Victoria](projets/MyBatteryIsLow/img/objets-popup/victoria_Kexp_Gexp.png)
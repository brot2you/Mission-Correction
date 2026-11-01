MISSION CORRECTION — V3 · by BROT2YOU APP
=========================================

Un seul fichier : index.html (HTML + CSS + JavaScript ES5 + données JSON intégrées).
Hors ligne, sans compte, sans dépendance externe à part les polices Google Fonts
(Cinzel, Fredoka, Kalam, Lexend), remplacées par des polices système si elles ne chargent pas.

DÉPLOIEMENT GITHUB PAGES
- Déposer index.html, .nojekyll et le dossier images/ à la racine du dépôt.
- Les liens de parcours professeur utilisent l'adresse de la page : créez-les
  depuis la version en ligne (pas depuis un fichier ouvert en local).

CONTENU
- 45 codes numérotés en 7 familles :
  Orthographe 1-9 · Accords 10-16 · Conjugaison 17-23 · Grammaire 24-28
  Syntaxe 29-37 · Ponctuation 38-41 · Vocabulaire 42-45
- Chaque code = une enquête inductive en 5 étapes :
  indices à classer → pistes (fausses pistes réfutées par contre-exemple)
  → contre-épreuve → règle rédigée par l'élève puis comparée au rapport officiel
  → chasse à l'erreur en contexte.
- 270 défis (6 par code, options mélangées), 90 phrases de terrain.
- 15 documents de mission (2 par lieu : 6e-5e et 4e-3e, + mission finale).
- 11 outils de manipulation (« la mallette du détective ») reliés aux codes.
- Ma copie : l'élève recopie un passage annoté, touche les mots soulignés,
  saisit le code (numéro, abréviation de l'appli ou code perso du prof),
  corrige et formule la règle. Carnet + « pièges personnels » (3 codes les plus fréquents).
- Parcours professeur par lien (#p=…) : codes choisis, consigne, codes perso.
  Objectif par code : enquête classée + 4 défis sur 6.
- Fiche bilan imprimable, tableau des codes imprimable, export/import JSON.
- Mode lecture adaptée (Lexend + espacement), texte agrandi, sons désactivables.

ILLUSTRATIONS (facultatif) — dossier images/
L'appli fonctionne sans aucune image (décors dessinés en SVG/CSS).
Chaque PNG déposé avec le bon nom remplace automatiquement son décor :
  accueil.png        bandeau d'accueil (titre + les 4 détectives), large ~ 2:1 ou 3:1
  qg.png             fond du bureau du QG (sous les 8 tuiles)
  carte.png          carte des îles, format 1000 × 620 (ou même proportion)
                     → zones cliquables placées aux coordonnées de "map" dans
                       data-config (Orthographe en haut à gauche, Grammaire en haut
                       à droite, etc.) : à ajuster si votre carte diffère
  mascotte.png       détective qui pointe du doigt (page « La règle »)
  guide-sacha.png, guide-margot.png, guide-hugo.png, guide-nadia.png
                     portraits carrés des 4 équipiers (avatars, bulles de dialogue)
  icone-copie.png, icone-regles.png, icone-defis.png, icone-missions.png,
  icone-parcours.png, icone-badges.png, icone-collection.png, icone-prof.png
                     icônes carrées des tuiles du QG (fond transparent conseillé)

MODIFIER LE CONTENU
Les données sont dans les blocs <script type="application/json"> en bas de index.html :
data-notions (codes, enquêtes, défis), data-missions, data-badges, data-config.
Dans les textes : [mot] = mot surligné ; {faux|juste|code} = erreur à trouver ;
plusieurs corrections acceptées : {faux|juste1/juste2|code}.

ÉCONOMIE DES XP (pas de triche possible)
+10 par défi réussi la 1re fois, +2 en révision (une fois par jour et par défi),
0 pour une erreur ; +50 par affaire classée (une fois) ; mission : +40 la 1re fois
et +20 par étoile gagnée en plus ; +5 par correction du carnet (5 par jour max).

DONNÉES
Tout reste dans le navigateur de l'appareil (localStorage). Rien n'est envoyé.

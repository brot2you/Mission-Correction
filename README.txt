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

ILLUSTRATIONS
Intégrées dans index.html (WebP optimisé, ~1 Mo au total) : le fichier reste autonome.
- Fond de l'accueil : bibliothèque (écrans larges) / bureau vertical (smartphone, tablette en portrait)
- Logo en haut, équipe des 4 détectives juste derrière la première rangée de boutons
- 8 boutons illustrés du QG (4 colonnes sur PC, 2 sur smartphone)
- Portraits de Sacha, Margot, Hugo et Nadia découpés dans l'image de l'équipe
  (avatars, guides des enquêtes et des missions)
Optionnel, dossier images/ : carte.png (carte des îles, 1000 × 620) et mascotte.png
(page « La règle ») remplacent les décors dessinés s'ils sont présents.

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

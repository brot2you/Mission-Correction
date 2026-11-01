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

ILLUSTRATIONS (toutes intégrées dans index.html, WebP optimisé, ~2,5 Mo)
- Accueil : fond bibliothèque (PC) / bureau vertical (smartphone), logo, équipe, 8 boutons
- Bouton maison (retour au QG) sur toutes les pages
- Carte de l'île : 7 lieux + tribunal cliquables, lettres du code affichées sur les lieux résolus
  (positions réglables dans data-config → mapPct, en % de la largeur et de la hauteur)
- Pages des lieux : illustration du bâtiment ; décors (boussole, lanterne, loupe, parchemin)
- Ma collection : cartes-royaumes par famille (grisées et cadenassées tant que l'affaire n'est pas classée)
- Mes badges : blasons fantasy (grisés tant que le badge n'est pas obtenu)
- La mallette : une mallette illustrée par outil d'enquête
- Portraits de Sacha, Margot, Hugo et Nadia (guides de l'histoire)
- 12 avatars de profil au choix (Le Limier, L'Exploratrice, Le Chevalier, La Sage du temple,
  Le Savant des ruines, L'Archère de la forêt, Le Corsaire du phare, La Cartographe,
  Le Juge-enquêteur, La Grande Archiviste, Le Bouffon malicieux, Flair le chien détective),
  modifiables dans les réglages (⚙)
Optionnel : images/mascotte.png (page « La règle »).

SONS
Synthétisés en direct (aucun fichier audio) : pas feutrés, pages de dossier, clochette
d'indice, contrebasse de fausse piste, coup de tampon, serrure qui cède, machine à écrire,
nappe de suspense à l'ouverture d'une mission, vibraphone de résolution. Désactivables dans les réglages.

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

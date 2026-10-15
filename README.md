# Harry Potter — Destin de Poudlard

RPG narratif interactif non officiel, en français. Cette version est une aventure web autonome avec interface de grimoire sombre, couleurs adaptées à la maison, pages HTML distinctes et sauvegardes locales. Aucun fichier image ou son n'est intégré ; l'identité visuelle repose sur le CSS et la typographie.

## Démarrer

1. Décompresse le ZIP.
2. Ouvre `index.html` dans un navigateur récent pour un essai rapide.
3. Pour une utilisation plus fiable, lance le dossier via un serveur statique local ou publie-le sur GitHub Pages. Le stockage local peut être limité par certains navigateurs en mode `file://`.

## Pages incluses

- `index.html` : accueil et reprise de l’aventure
- `personnage.html` : création guidée du personnage
- `repartition.html` : cérémonie et choix du Choixpeau
- `histoire.html` : récit, dialogues et décisions
- `exploration.html` : carte narrative et lieux conditionnels
- `activites.html` : cours, duels, potions, Quidditch, créatures, examens, enquête, relations, défis de maison et achats
- `journal.html` : chroniques, indices et choix mémorables
- `profil.html` : personnage, compétences et ressources
- `relations.html` : relations et réputation
- `sorts.html` : grimoire et apprentissage
- `inventaire.html` : objets, ressources et utilisation de certains objets
- `sauvegardes.html` : cinq emplacements, export/import JSON
- `parametres.html` : préférences de lecture et d’accessibilité
- `epilogue.html` : bilan personnalisé de la chronique
- `styles.css` et `app.js` : style et logique partagés

## Fonctionnalités intégrées dans cette version

Les systèmes ci-dessous sont reliés à l’état de la partie. Leur profondeur reste celle d’un RPG narratif autonome : ce n’est pas un jeu 3D, et les interactions ne sont pas toutes aussi complexes qu’un jeu commercial.
 dans cette version

- Création guidée : nom, pronoms facultatifs, apparence textuelle, personnalité, origines, enfance, ambition, secret, qualité, défaut, baguette et animal.
- Questionnaire de répartition et thème couleur adapté à Gryffondor, Serpentard, Serdaigle ou Poufsouffle.
- Parcours chronologique sur sept années, avec scènes originales et choix à conséquences. Cette édition ajoute deux scènes originales par année aux scènes déjà présentes.
- Effets persistants sur les relations, les compétences, la réputation, les points de maison, les ressources, les objets, les indices et les drapeaux de décision.
- Activités : séances de cours, examens avec notes, duels tactiques, rencontres avec des créatures, entraînement et essai de Quidditch, préparation de potions en trois étapes.
- Enquête : conservation d’indices et synthèse de pistes selon les éléments recueillis.
- Interactions sociales contextuelles, temps avec l’animal, achats d’objets et utilisation de plusieurs objets.
- Défis spécifiques à la maison, carte narrative, journal personnel et épilogue prenant en compte une partie des décisions et relations.
- Cinq sauvegardes indépendantes, sauvegarde automatique/manuelle et export/import JSON.
- Réglages de lecture : taille du texte, largeur, contraste, réduction des animations et préférences de dialogue.
- Responsive, sans compte, sans serveur de jeu, sans images et sans audio.

## Publier sur GitHub Pages

1. Crée un dépôt GitHub.
2. Dépose **le contenu du dossier `destin_poudlard`** à la racine du dépôt (les fichiers HTML doivent se trouver à la racine publiée, pas dans un sous-dossier supplémentaire).
3. Dans `Settings → Pages`, sélectionne la branche principale et le dossier `/ (root)`.
4. Enregistre et attends la publication du site.

## Limites à connaître honnêtement

C’est une version enrichie et jouable, mais elle ne constitue pas encore un RPG commercial exhaustif. Les sept années sont accessibles et comprennent du contenu narratif, toutefois les campagnes ne sont pas toutes développées à la même profondeur ; certains systèmes restent des simulations légères et les embranchements ne sont pas tous uniques. Les examens, l’enquête, les activités et les relations ont des effets, mais ne forment pas encore un moteur narratif exhaustif avec des centaines de branches écrites à la main. La sauvegarde reste locale au navigateur : pas de compte, pas de synchronisation cloud, ni de sauvegarde partagée entre appareils sans export/import. Un test manuel complet de chaque parcours et de chaque navigateur reste nécessaire.

Les scènes et dialogues de ce fan project sont originaux et ne reproduisent pas les passages des livres ou des films. Projet non officiel, sans affiliation avec Warner Bros., J. K. Rowling ou les ayants droit de l’univers Harry Potter.

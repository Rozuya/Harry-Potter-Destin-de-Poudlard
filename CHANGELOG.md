# Journal des modifications — Destin de Poudlard

## Version intégrée — 15 octobre 2026

- Réuni les pages HTML, la feuille de style partagée et le moteur JavaScript dans une archive autonome cohérente.
- Relié la progression des sept années aux choix et à l’état persistant de la partie.
- Inclus les systèmes de cours/révisions, examens, duels tactiques, potions en trois étapes, essais et matchs de Quidditch, créatures, enquête, relations, points de maison, réputation, Patronus, inventaire et achats.
- Conservé les cinq emplacements de sauvegarde, l’auto-sauvegarde et l’import/export JSON.
- Clarifié dans le README les limites d’un RPG narratif local et l’absence de synchronisation cloud.

## À savoir

Cette livraison est une version intégrée et jouable du RPG narratif. La vérification effectuée dans cette livraison comprend la syntaxe JavaScript, la présence des pages et ressources, les références aux fichiers locaux et l’intégrité de l’archive. Cela ne remplace pas un test exhaustif de chaque embranchement interactif dans tous les navigateurs.

## Version approfondie — 15 octobre 2026

- Empêché de rejouer plusieurs fois le même choix de scène pour obtenir ses récompenses : une décision est désormais verrouillée et enregistrée avant l’affichage de sa conséquence.
- Limité les révisions répétées d’une même matière à une séance par année, et les duels victorieux à un duel d’entraînement récompensé par année.
- Empêché de répéter à l’infini les récompenses d’exploration d’un même lieu pendant une année scolaire.
- Encadré le repos par chapitre et ajouté des vérifications d’état aux actions du grimoire, à l’achat de potions et aux opérations sur les sauvegardes.
- Renforcé la validation des sauvegardes importées : chapitre cohérent avec l’année, collections attendues et types de données contrôlés.
- Enrichi l’épilogue et le profil avec des indicateurs issus de la partie réellement jouée (choix, indices, quêtes, défis de maison, examens et Quidditch).
- Corrigé le traitement des entrées de quête non structurées afin qu’elles ne puissent pas être validées par erreur depuis le tableau des objectifs.

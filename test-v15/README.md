# Ma Cinéthèque — version 2.62

Mise à jour de l'application personnelle de suivi des films et séries.

## Nouveautés
- Collection en mode Liste (titres élargis, statut à droite de la note) ou Vignettes (affiche, titre, année, note, statut).
- Recherche et sélection d'affiches pour les séries via TVmaze et les films via le catalogue Apple iTunes (sans compte API ni abonnement).
- Ajout d'affiches aux titres déjà enregistrés depuis leur fiche.
- Les fichiers de synchronisation/sauvegarde ne stockent que les URL des affiches, pas les fichiers images.

## Installation GitHub Pages
Remplacer à la racine du dépôt **index.html** et **sw.js** par les fichiers de ce ZIP, puis valider la modification. Le reste du projet peut rester inchangé. Si l'ancien écran reste affiché sur Android, fermer puis rouvrir l'application installée et vérifier « Version 2.62 » sous le titre.

## Données
Les données existantes dans le navigateur ne sont ni réinitialisées ni remplacées par cette mise à jour. L'affiche d'un ancien titre peut être complétée en ouvrant sa fiche dans Collection. Les affiches requièrent Internet pour apparaître, mais les titres, notes, épisodes et autres données restent accessibles hors ligne.

Archive nettoyée : le dossier historique « test-v15 » est exclu de ce ZIP. Seuls les fichiers de la version principale sont inclus ; un éventuel ancien dossier de test déjà présent sur GitHub n’a pas besoin d’être modifié.

## Correction 2.62
Numéro de version unique (la 2.61 était déjà utilisée) et nouvelle clé de cache pour déclencher une mise à jour de la PWA. Aucun changement de structure des données ni de synchronisation.

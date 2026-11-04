# Ma Cinéthèque — 2.7.8, édition cinéma

Version 2.7.7 (présentation nocturne, affiches, projecteur vintage) avec
mécanisme de validation des données de synchronisation repris de la V2.62
ayant fonctionné sur les trois appareils. Le diagnostic de test 2.7.7 est retiré.

## Installation GitHub Pages (dépôt principal)

* Ne désinstallez PAS l’application PWA et n’effacez PAS les données du navigateur.
* Vérifiez les sauvegardes et conservez les anciens fichiers dans l’historique GitHub.
* Dans la racine du dépôt, sur la branche main, remplacez trois fichiers seulement :
  `index.html`, `sw.js`, et ajoutez `projecteur-cinema.webp`.
* N’archivez PAS le ZIP dans le dépôt tel quel : GitHub ne le décompresse pas.
* Les autres fichiers sont inchangés et fournis dans le ZIP pour archivage.
* Rechargez l’application depuis son icône; le numéro affiché est 2.7.8.
* Sur chaque appareil, contrôlez que la collection locale est toujours présente,
  puis utilisez « Préparer la synchronisation » uniquement à titre de vérification.
* Si un message d’erreur apparaît, ne confirmez aucun envoi et conservez les sauvegardes.

## Compatibilité et sécurité

Les clés localStorage, la référence commune v16, le format du fichier Drive,
le compte OAuth et les confirmations de sauvegarde sont conservés.
Aucune sauvegarde de collection utilisateur n’est incluse dans cette archive.
La protection contre les deux envois strictement simultanés reste non atomique :
un seul appareil à la fois.

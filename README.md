# KN Suivi

Application de suivi de production — fichier unique, sans installation.

- `index.html` — l'application complète (autonome, aucune dépendance à installer)
- `vercel.json` — désactive le cache pour que les mises à jour arrivent immédiatement

## Mise en ligne

Relier ce dépôt à Vercel (Add New → Project → Import Git Repository), preset **Other**,
puis Deploy. Chaque envoi sur `main` republie automatiquement.

## Mise à jour

Remplacer `index.html` par la nouvelle version (même nom) et valider. Vercel republie
en une trentaine de secondes ; rien à réinstaller sur le téléphone.

## Sauvegarde des données

Les données sont stockées sur l'appareil. La section **Sauvegarde en ligne** des réglages
permet de les mirroriser dans un projet Supabase gratuit.

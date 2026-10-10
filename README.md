# JKF — Gestion de caisse (version tableau de bord + sécurité)

Application web responsive pour ordinateur et mobile.

## Inclus
- Tableau de bord avec filtres **Jour, Semaine, Mois, Année** et **dates personnalisées**.
- Chiffre d'affaires, dépenses, résultat net, nombre de ventes.
- Totaux séparés pour **Salaires** et **Électricité**.
- Classements des produits les plus et moins vendus, avec quantité et chiffre d'affaires.
- Dépenses classées par catégorie, du coût le plus élevé au plus faible.
- Historique, recherche et export CSV.
- Sauvegarde/restauration JSON.
- Mot de passe requis avant l'effacement de toutes les données locales.
- Cache du site actualisé (v5) pour réduire les problèmes d'ancienne version.

## Mise à jour sur GitHub Pages
1. Sauvegardez d'abord vos données depuis **Paramètres et sauvegarde → Télécharger une sauvegarde**.
2. Extrayez ce ZIP sur votre ordinateur.
3. Ouvrez le dépôt GitHub et utilisez **Add file → Upload files**.
4. Téléversez tous les fichiers et dossiers contenus dans ce dossier directement à la racine du dépôt (notamment `index.html`, `app.js`, `style.css` et `sw.js`). Ne téléversez pas uniquement le ZIP et ne mettez pas les fichiers dans un sous-dossier.
5. Cliquez **Commit changes**.
6. Attendez quelques minutes, puis ouvrez le site et faites `Ctrl + F5`. Sur téléphone, fermez l'application installée puis rouvrez le site dans le navigateur.

Les données restent dans le stockage local du navigateur. Le déploiement du nouveau code ne doit pas effacer ces données, mais une sauvegarde est recommandée avant toute mise à jour. La protection par mot de passe dans cette version est une barrière contre l'effacement accidentel, pas une authentification serveur forte.

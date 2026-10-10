# JKF — Gestion de caisse (application web)

Application web responsive pour mobile et ordinateur : tableau de bord analytique avec filtres jour/semaine/mois/année/plage personnalisée, produits les plus et moins vendus, dépenses classées par catégorie avec salaires et électricité séparés, saisie de ventes et dépenses, historique filtrable, catalogue produits/prix, export CSV et sauvegarde/restauration JSON. Installable comme PWA sur les navigateurs compatibles.

## Déployer gratuitement avec GitHub Pages
1. Connectez-vous à https://github.com/ et créez un nouveau dépôt, par exemple `jkf-caisse`.
2. Téléversez **tous les fichiers de ce dossier** à la racine du dépôt (`index.html`, `style.css`, `app.js`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `README.md`).
3. Ouvrez **Settings → Pages** dans le dépôt.
4. Sous **Build and deployment**, choisissez **Deploy from a branch**.
5. Sélectionnez la branche `main`, le dossier `/ (root)`, puis cliquez sur **Save**.
6. Attendez le déploiement, puis ouvrez l'URL affichée par GitHub Pages. Elle ressemble à `https://VOTRE-PSEUDO.github.io/jkf-caisse/`.
7. Ouvrez cette adresse sur votre téléphone et votre ordinateur. Sur mobile, utilisez le menu du navigateur **Ajouter à l'écran d'accueil** si proposé.

## Données et confidentialité
Les opérations sont enregistrées dans le stockage local du navigateur. Le dépôt public ne contient pas les ventes/dépenses de l'utilisateur. Les données **ne se synchronisent pas automatiquement** entre appareils ou navigateurs. Pour transférer les données, utilisez Paramètres → Télécharger une sauvegarde sur le premier appareil, puis Importer sur l'autre. Pour une vraie synchronisation en direct multi-appareils, il faut ajouter une base de données et une authentification (par exemple Supabase ou Firebase).

## Tester localement
Ouvrez `index.html` dans un navigateur. Pour tester le service worker/PWA, utilisez un serveur local ou l'hébergement GitHub Pages (les service workers nécessitent HTTPS ou localhost).

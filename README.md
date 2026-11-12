# Mon image de soi · Ombaliz Thérapie

## Déploiement sur Render

1. Décompressez cette archive. Dans GitHub, créez le dépôt `ombaliz-image-de-soi`. Ajoutez le dossier `dist` à la racine du dépôt, puis validez l’ajout sur la branche `main`.
2. Dans https://dashboard.render.com, choisissez **New → Static Site** et sélectionnez ce dépôt. Si le dépôt est privé, autorisez l’application GitHub de Render à y accéder.
3. Renseignez les champs ci-dessous, puis cliquez sur **Create Static Site**.

| Champ | Valeur |
|---|---|
| Name | `ombaliz-image-de-soi` |
| Branch | `main` |
| Root Directory | Laisser vide |
| Build Command | `test -f dist/index.html` |
| Publish Directory | `dist` |

4. Attendez que le déploiement soit **Live**, puis ouvrez l’URL fournie par Render en navigation privée. Vérifiez le parcours et le téléchargement PDF avec des coordonnées fictives.
5. Scannez le flashcode sur un téléphone. Il est configuré pour `https://ombaliz-image-de-soi.onrender.com`. Si Render attribue une autre URL, régénérez `dist/assets/qr.png` pour cette URL et remplacez le lien correspondant dans `dist/app.js`, puis publiez les deux modifications sur GitHub.

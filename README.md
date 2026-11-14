# Gamme Theraplos – Présentation des produits

Page web de présentation de la gamme Theraplos Laboratoires (19 produits), destinée aux médecins et aux pharmaciens. Pas de commande.

## Contenu
- `index.html` : la page complète (images, styles et fiches produits inclus, aucun autre fichier nécessaire)
- `.nojekyll` : indique à GitHub Pages de publier le site tel quel

## Publier avec GitHub Pages
1. Créer un dépôt sur github.com (par exemple `theraplos-gamme`), puis **Add file > Upload files**.
2. Déposer `index.html`, `.nojekyll` et `README.md` à la racine, puis **Commit changes**.
3. Ouvrir **Settings > Pages**, choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une ou deux minutes, la page est en ligne à l’adresse `https://<votre-compte>.github.io/theraplos-gamme/`.

## Modifier la page
Les produits sont dans le tableau `P` du script (nom, catégorie, prix, description), les fiches détaillées dans `DET`. Un prix à `null` est simplement masqué.

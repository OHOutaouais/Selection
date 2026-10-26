# Horaire Sélection

Affichage pour l'accueil : qui aller voir pour un walk-in Sélection (vert = 1er choix, jaune = 2e choix, rouge = téléphonie ou ne pas déranger, gris = en congé).

## Mettre en ligne avec GitHub Pages (gratuit)
1. Créer un dépôt sur github.com et y téléverser `index.html` et `horaire.json` (Add file → Upload files).
2. Settings → Pages → Source : *Deploy from a branch*, branche `main`, dossier `/ (root)` → Save.
3. Après une ou deux minutes, le lien est `https://<votre-compte>.github.io/<nom-du-dépôt>/`.
   Ouvrez-le sur les iPad, les Android et les ordis de la réception. Aucun compte n'est nécessaire pour regarder.

## Changer l'horaire, un congé, un « ne pas déranger »
- Ouvrir le lien → onglet **Configuration** → faire les changements.
- Cliquer **Copier le fichier**, puis **Ouvrir horaire.json sur GitHub** (il faut être connecté à GitHub).
- Tout remplacer par le texte copié → **Commit changes**.
- Les écrans relisent le fichier chaque minute. GitHub peut prendre jusqu'à environ 10 minutes pour servir la nouvelle version.

## Sans internet
Ouvrir `index.html` directement fonctionne aussi. La page affiche alors l'horaire de base inclus dans le fichier.

⚠ Un site GitHub Pages est public : n'importe qui avec le lien peut voir les prénoms et les dates de congé. N'écrivez rien de confidentiel dans les notes.

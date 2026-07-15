# Structure de ton repository GitHub

## Arborescence à créer

```
ton-repo/
├── README.md
└── assets/
    ├── bouquet.png
    ├── logo-ef.png
    ├── essence-florale-flyer.png
    ├── dos-etiquette.png
    ├── complexe-bonheur-logo.png
    └── complexe-bonheur-carte-visite.png
```

## Marche à suivre (via github.com)

1. Va sur la page principale de ton repo
2. Clique sur **"Ajouter un fichier"** → **"Importer des fichiers"**
3. Glisse les 6 images ci-dessus
4. En haut de la page d'import, dans le champ de chemin, tape :
   ```
   assets/
   ```
5. Clique **"Valider les modifications"**
6. Reviens sur la page principale, clique **"Ajouter un fichier"** → **"Créer un fichier"**
7. Nomme-le `README.md`
8. Colle le contenu du README que je t'ai donné
9. Clique **"Valider les modifications"**

## Noms de fichiers à respecter

Copie-colle ces noms exacts pour renommer tes images avant import (sinon les liens du README ne fonctionneront pas) :

```
bouquet.png
logo-ef.png
essence-florale-flyer.png
dos-etiquette.png
complexe-bonheur-logo.png
complexe-bonheur-carte-visite.png
```

## Si tu utilises Git en local

```bash
git clone https://github.com/ton-nom-utilisateur/ton-repo.git
cd ton-repo
mkdir assets
# copie tes 6 images dans le dossier assets/
git add .
git commit -m "Ajout du README et des visuels du portfolio"
git push
```

## Pour ajouter une vidéo plus tard

```markdown
[![Regarder la vidéo](assets/nom-miniature.png)](https://lien-youtube-ou-facebook.com)
```
Remplace `nom-miniature.png` par une image extraite de la vidéo, et le lien par l'URL réelle.

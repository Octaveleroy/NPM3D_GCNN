# NPM3D GCNN

## Préparation des données

Pour des raisons de taille, le dataset de ce projet n'est pas hébergé sur GitHub. Vous devez le télécharger manuellement avant de lancer les scripts.

**Étapes à suivre :**

1. Téléchargez le dataset `modelnet40_ply_hdf5_2048.zip` depuis ce lien Google Drive : 
   **[Dataset](https://drive.google.com/file/d/15WuKKi88efXV0wFLA2XB-CcHBL5X4BUK/view?usp=sharing)**
2. À la racine du projet, créez un dossier nommé `data`.
3. Placez l'archive `.zip` dans ce dossier.

l'arborescence de votre projet doit ressembler à ceci :

```text
NPM3D_GCNN/
├── data/
│   └── modelnet40_ply_hdf5_2048.zip
├── DGCNN.ipynb 
└── README.md
```

## Implémentation et Expériences

L'ensemble de l'implémentation et des expériences se trouve dans le Jupyter Notebook `DGCNN.ipynb`.

**Attention :** Si vous exécutez ce notebook sur Google Colab, il arrive que la VRAM soit saturée si l'on lance tous les tests à la suite, et plus particulièrement celui de la *curse of dimensionality*. 

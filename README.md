# HistoDomain — Subjective H&E to PAS Evaluation

Site statique pour évaluer subjectivement des images PAS virtuelles générées à partir d’images H&E, dans le cadre de la généralisation inter-centres du modèle His-MMDM.

## Contenu

- 10 patches affichés à la fois pour chaque tissu : Kidney (KPMP), Breast et Lung.
- Comparaison H&E input / Generated PAS — Model 1 / Model 2.
- Quatre niveaux de qualité et un résumé par modèle et par tissu.
- Export CSV des notes.
- Images servies depuis le dépôt GitHub ; notes conservées localement dans le navigateur.

## Déployer avec GitHub Pages

Les fichiers du site doivent rester à la racine du dépôt : `index.html`, `README.md` et le dossier `images/`.

Dans **Settings → Pages**, choisis **Deploy from a branch**, la branche `main` et le dossier `/(root)`, puis enregistre.

## Remplacer ou ajouter les images

Les noms et chemins attendus sont indiqués dans `images/README.md`. Dans GitHub, ouvre `images/kidney/` et ajoute ou remplace les fichiers en gardant exactement leurs noms. Après le commit et le redéploiement Pages, les nouvelles images apparaîtront dans le site.

Les notes restent propres au navigateur où elles ont été saisies. Exporte-les en CSV pour les conserver.


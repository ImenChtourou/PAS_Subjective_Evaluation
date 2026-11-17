# HistoDomain — Subjective H&E to PAS Evaluation

Site statique pour évaluer subjectivement des images PAS virtuelles générées à partir d’images H&E, dans le cadre de la généralisation inter-centres du modèle His-MMDM.

## Contenu

- 10 patches affichés pour chaque tissu : Kidney (KPMP), Breast et Lung.
- Comparaison H&E input / Generated PAS — Model 1 / Generated PAS — Model 2.
- Notes : Very High quality, High quality, Medium quality et Poor quality.
- Résumés des notes par modèle et par tissu.
- Export CSV des notes.
- Sauvegarde locale dans le navigateur via IndexedDB.

## Mise en ligne sur GitHub Pages

1. Place `index.html` et `README.md` à la racine du dépôt.
2. Dans GitHub, ouvre **Settings → Pages**.
3. Choisis **Deploy from a branch**, puis la branche `main` et le dossier `/(root)`.
4. Clique sur **Save**. GitHub Pages affichera ensuite l’adresse du site dans cette même section.

Aucune compilation ni dépendance externe n’est nécessaire.

## Ajouter les images

Ouvre le site et utilise **Add image** dans chaque case. Les formats acceptés sont PNG, JPEG et WebP (15 Mo maximum par image). Les images et les notes sont enregistrées dans le navigateur de l’utilisateur : elles ne sont pas intégrées au dépôt et ne sont pas partagées automatiquement entre plusieurs navigateurs ou ordinateurs. Exporte régulièrement les résultats CSV pour sauvegarder les notes.


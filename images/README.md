# Organisation des images

Les images sont séparées par type dans trois dossiers, puis par tissu :

- `HE/<tissu>/patch_01.png` : image d’entrée H&E
- `PAS_generated/<tissu>/patch_01.png` : PAS générée par His-MMDM entraîné à Nice
- `PAS_finetuned/<tissu>/patch_01.png` : PAS générée après fine-tuning

Noms attendus pour chaque tissu : `patch_01.png`, `patch_02.png`, …, `patch_10.png`. Les tissus prévus sont `kidney`, `breast` et `lung`. Pour modifier une image, remplace simplement son PNG dans le dossier GitHub correspondant en gardant le même nom.

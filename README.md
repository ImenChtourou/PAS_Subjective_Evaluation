# HistoDomain — évaluation H&E vers PAS

Site statique pour comparer les PAS virtuelles produites par His-MMDM entraîné à Nice et par la version fine-tunée.

## Images

Dépose les fichiers PNG dans les dossiers du tissu correspondant. Pour les 10 patches du rein :

- `images/HE/kidney/patch_01.png` à `patch_10.png` : entrées H&E KPMP
- `images/PAS_generated/kidney/patch_01.png` à `patch_10.png` : PAS His-MMDM sans fine-tuning
- `images/PAS_finetuned/kidney/patch_01.png` à `patch_10.png` : PAS His-MMDM après fine-tuning

Même structure pour `breast` et `lung`. La page comporte 10 patches par tissu. Les images ne sont pas incluses dans ce dépôt : ajoute tes propres PNG. Les notes sont sauvegardées localement dans le navigateur.

# tp-bachelor

![Capture d'écran](captureecran/clone.png)
Vu que j'ai eu un problème de fichier au debut on voit dans la capture d'écran
que j'ai du réinitialiser l'origin pour pouvoir le connecter à mon dépot GitHub.
Puis j'ai ajouté l'image et le dot en enregistrant avec git add ., git commit -m "change style",
git push.
![Capture d'écran](captureecran/conflit dot.png)
Après avoir crée le conflit j'ai eu une erreur de sauvegarde vers le depot.
![Capture d'écran](captureecran/conflit resolut.png)
Grace à la commande git config pull.rebase false et git pull origin main, les deux fichier on mergés en changeant
le fichier css local et se sont sauvegardés comme on peut le voir avec git status à la fin ou il n'y a rien a commit.


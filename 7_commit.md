# Modifier le commentaire d'un commit

 Pour modifier le commentaire d'un commit, il faut utiliser la commande suivante :
 
 ```bash
 git commit --amend -m "nouveau commentaire"
```
# Supprimer un commit
Pour supprimer un commit, il faut utiliser la commande suivante :

```bash
git reset --hard HEAD~1
```
--hard HEAD~1 signifie que vous voulez supprimer le dernier commit. Si vous voulez supprimer plusieurs commits, vous pouvez utiliser HEAD~n où n est le nombre de commits à supprimer.

si vous voulez supprimer un commit spécifique, vous pouvez utiliser la commande suivante :

```bash
git reset --hard <commit_id>
```
# Récupérer un commit supprimé
Pour récupérer un commit supprimé, il faut utiliser la commande suivante :
```bash
git reflog
```
Cette commande vous permet de lister tous les commits, y compris ceux qui ont été supprimés. Vous pouvez ensuite utiliser la commande git reset pour revenir à un commit spécifique.

# Récupérer un commit spécifique
Pour récupérer un commit spécifique, il faut utiliser la commande suivante :

```bash
git checkout <commit_id>
```
Cette commande vous permet de revenir à un commit spécifique. Vous pouvez ensuite créer une nouvelle branche à partir de ce commit si vous le souhaitez.

# Modifier un commit spécifique
Pour modifier un commit spécifique, il faut utiliser la commande suivante :

```bash
git rebase -i <commit_id>
```
Cette commande vous permet de modifier un commit spécifique. Vous pouvez ensuite choisir de modifier le commentaire du commit, de fusionner plusieurs commits en un seul, ou de supprimer un commit.

# Différence entre git reset et git revert
`git reset` et `git revert` sont deux commandes différentes qui ont des effets différents sur
votre historique de commits.
`git reset` est utilisé pour supprimer des commits de l'historique. Il modifie l'historique des commits et peut entraîner la perte de données si vous n'êtes pas prudent. Il est généralement utilisé pour annuler des commits récents ou pour réinitialiser votre branche à un état précédent.
`git revert`, en revanche, est utilisé pour annuler les modifications apportées par un commit spécifique sans modifier l'historique des commits. Il crée un nouveau commit qui annule les modifications du commit spécifié. Cela permet de conserver l'historique des commits tout en annulant les modifications indésirables.

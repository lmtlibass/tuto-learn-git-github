# Supprimer une branche sur git

Pour supprimer une branche, il faut utiliser la commande suivante :

```bash
git branch -d nom_de_la_branche
```

# C'est quoi un stash ?

Un stash est une zone de stockage temporaire pour les modifications de votre code. Il vous permet de sauvegarder des modifications non commitées, de changer de branche, de faire un pull, etc. sans avoir à faire de commit.

# Comment utiliser un stash ?

Pour utiliser un stash, il faut utiliser la commande suivante :

```bash
git stash
```
# comment ça marche ?

Lorsque vous utilisez la commande `git stash`, Git prend toutes les modifications non commitées dans votre répertoire de travail et les enregistre dans une zone de stockage temporaire appelée "stash". Cela vous permet de revenir à un état propre de votre code, sans perdre vos modifications en cours.
# Dans quel cas utiliser un stash ?
Un stash est utile dans les situations suivantes :

- Lorsque vous devez changer de branche mais que vous avez des modifications non commitées.
- Lorsque vous souhaitez faire un pull des modifications distantes sans perdre vos modifications locales.
- Lorsque vous souhaitez tester quelque chose rapidement sans faire de commit.

# Comment lister les stashes ?

Pour lister les stashes, il faut utiliser la commande suivante :


```bash
git stash list
```

# Comment appliquer un stash ?

Pour appliquer un stash, il faut utiliser la commande suivante :

```bash
git stash apply stash@{numero_stash}
```
appliquer un stash veut dire recupérer les modifications stockées dans le stash et les appliquer à votre répertoire de travail actuel. Vous pouvez spécifier le stash que vous souhaitez appliquer en utilisant son numéro, par exemple `stash@{0}` pour le dernier stash créé.

# Comment supprimer un stash ?

Pour supprimer un stash, il faut utiliser la commande suivante :

```bash
git stash drop stash@{numero_stash}
```



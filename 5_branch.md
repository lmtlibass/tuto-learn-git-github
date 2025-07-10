😇 
# Alors j'espère que vous en savez plus a propos des branches ?

![](img/C.png)

Imaginez, vous êtes 4 developpeurs dans un projets. vous avez une version qui marche bien. et si le 4eme codeur décide d'ajouter des fonctionnalités et aprés son commit et push sans verification il se rends compte qu'il a tout cassé, vous serez dans ce cas obligés de se débrouiller pour tout régler et cela pourait vous prendre du temps. 😠 


Le mieux a faire c'etait donc de donner la possibilité à chaccun d'entre vous d'avoir une copie du code principale et à partir de là vous pourez faire vaut modifications les tester, casser le code tout détruire recommencer .... sans affecter le projet princiale. 

Et une fois tout est ok chez vous le capitaine d'entre vous vas se charger de prendre en compte vos modification et l'intéfrer sans problème dans le code principale .
Et mainetenat tous le monde sera content 😺 
et persone n'aura de soucis suplèmentaire . 🤟 

**Grâce aux branches, vous créez l'évolution  de votre projet sans toucher à l'application en cours de production**


## Pourquoi les branches ?

Les branches sont alors des versions de votre projet qui sont indépendantes les unes des autres.

## Comment créer une branche ?

Pour créer une branche, il faut utiliser la commande suivante :

```bash
git branch nom_de_la_branche
```

## Comment se déplacer entre les branches ?

Pour se déplacer entre les branches, il faut utiliser la commande suivante :

```bash
git checkout nom_de_la_branche
```

## Comment créer une branche et se déplacer dessus en même temps ?

Pour créer une branche et se déplacer dessus en même temps, il faut utiliser la commande suivante :

```bash
git checkout -b nom_de_la_branche
```

## Comment supprimer une branche ?

Pour supprimer une branche, il faut utiliser la commande suivante :

```bash
git branch -d nom_de_la_branche
```

# Ok c'est cool maintenant, vous comprenez les branches ! super 🦸 
## Maintenant pratiquons un peu 
 1. lister touts nos branches 
```bash
git branch
```
On aura la liste de nos branches ( à noter que la branche par defaut de git est main ou master)  
2. créer une branche
```bash
git branche my_first_branch
```
3. se déplacer sur la branche
```bash
git checkout my_first_branch
```
4. créer un fichier
```bash
touch my_file.txt
```
5. ajouter le fichier 
```bash
git add my_file.txt
```
6. commit
```bash
git commit -m "my first commit"
```
7. push mainter le fichier dans notre branche 
```bash
git push origin my_first_branch
```
**Mais maintenant, comment faire pour que votre branche et ses modifications soit intégrée dans la branche principale ?**
8. revenir sur la branche principale
```bash
git checkout main
```
9. fusionner la branche principale avec la branche my_first_branch
```bash
git merge my_first_branch
```

       J'espères que vous avez compris l'idée😻 

# Les conflits

Les conflits sont des erreurs qui peuvent survenir lors d'une fusion de branches.

## Comment résoudre un conflit ?

Pour résoudre un conflit, il faut ouvrir le fichier en conflit et supprimer les lignes qui ne sont pas nécessaires.





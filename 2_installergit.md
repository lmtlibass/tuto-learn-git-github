# telecharger et installer git via le lien suivant 
     https://git-scm.com/downloads
```text
     l'installation est la même sur toutes les OS
```

# quelques comandes à utiliser 

     cd -> pour navider entre vos dossiers 
     ls -> pour lister les dossiers et fichier présents dans un emplacement

     mkdir -> pour créer un dossiers (mkdir nomDossier)
     touch -> pour creer un fichier  (touch nomFicier.extention [ extention =>.php , .md, .doc ....])

- **nb: Si tous ses elemnts cités sont des** chinois pour toi, ne te décourage pas mon grand. 😻  Va juste apprendre à utiliser la ligne de commande sur ubuntu et reviens. 🏃 🏃‍♂️ 

# initialier un nouveau dépo git

- **avant tout tachez vous a configurer  votre identifiant git** 

Alors ouvrez votre terminale git et tapez les lignes suivants: 

```bash
     git config --global user.name "libscode"  
     git config --global user.email libscode@example.com
``` 

mettez votre nom et email

Pour voir vos configurations tapez la commande 

```bash
     git config --list
```

- **Initialisons maintenant notre premier dépôt git**

- Avant cela encore 😎😅
créeons un projet réél à initialiser, pour ne pas initiialiser du vide!!

Maintenant sans refflechir tapez les commandes suivants: 
``` bash
     mkdir testprojet
     ls
     cd testprojet
     touch test.html
```
- Voyons maintenant qu'est ce qu'on a fait

     1. la commande mkdir nous a permi de créer un nouveau dosier "testprojet" à partire de notre terminale
     2. ls nous montre le dossier qu'on vient de créer
     3. cd testprojet, lui à son tour nous a permit de se déplacer dans le dossier testprojet
     4. et enfin touche teste.html pour créer un fichier html dans le dossier ou nous venons de nous placer

- maintenant re tournons initialisons git 

```bash
     git init
``` 

📣 🤞 Bravo !! vous venez d'initialiser votre premier dépot git . 
git à ainsi donc créer un fichier caché que vous pouvez voir en affichant les fichiers masqués dans votre répertoire.



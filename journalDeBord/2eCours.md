Pour le deuxième cours, nous avons pris le temps pour corriger l'exercice à faire pour ce 2ème cours sur les commandes d'Unix. 
Puis nous avons fini de créer notre clé SSH et l'importer dans notre git.
Puis nous faisons des manipulations de git comme cloner le répertoire du cours ou de créer une git à nous même et puis la mettre à jour. 
En suite nous mettons à jour un fichier, per exemple README.md avec la commande echo. Voici les étapes :
echo hello >> README.md
Puis on met à jour notre git
git add README.md
git commit -m "Modif readme.md"
git push

Puis on fait la configuration de notre git avec git config.
git config user.email "gialoc2001@gmail.com"
git config user.name "Loc PHAM"


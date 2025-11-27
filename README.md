Examen Git Avancé

Le projet hébergé sur le dépôt Git est un mini serveur web représentant une
bibliothèque, le site permet d’afficher la liste des livres avec 4 champs : ID , Title ,
Author , Year . Le site possède aussi une page pour chaque livre, pour les afficher
individuellement

Pour le démarrer:

- Cloner le repo sur votre machine: ```git clone https://www.github.com/ShoriMatt/exam-git-avance```
  
- Utilisez ```go mod init main``` puis ```go mod tidy``` pour installer les modules supplémentaires au lancement du projet.

- Pour terminer faites ```go run main.go``` depuis la racine du projet pour le lancer

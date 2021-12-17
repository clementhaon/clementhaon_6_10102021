# clementhaon_6_10102021
Hot Takes 
Construction d'une API sécurisé pour une application d'avis gastronomiques sur les sauces piquantes.

Partie front-end développé par openclassrooms : https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6

1 Installation

  Pour la partie front end voici les dépendances que vous devez installer :

    NodeJS 12.14 ou 14.0.
    CLI angulaire 7.0.2.
    node-sass : assurez-vous d'utiliser la version correspondante à NodeJS. Pour Noe 14.0 par exemple, vous avez besoin de node-sass dans la version 4.14+.

Ensuite, clonez le référentiel front end, puis à la racine front end run npm install, et run npm install --save-dev run-script-os. Puis npm run start pour lancer l'application

Clonez le référentiel backend et y installer tous les modules.

Voici les modules utilisés pour la partie backend : 

    bcrypt
    body-parser
    crypto-js
    dotenv
    express
    helmet
    jsonwebtoken
    mongoose
    mongoose-unique-validator
    multer
    nodemon
    
  Pour lancer le server vous devrez le connecter à votre base de donné avec un fichier .env remplis comme celui ci : 
  
  DB_USER=
  DB_PASS=
  DB_HOST=
  EMAIL_KEY=
  TOKEN_KEY=
  
  Pour la connection se fasse bien avec la base de donnée.
  
  Puis lancer le serveur avec nodemon server à la racine back end

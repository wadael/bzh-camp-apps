# Concours BreizhCamp

Bonjour , tu veux gagner une place pour le [BreizhCamp](http://www.breizhcamp.org/)? (parce que en fait, c'est sold out!) Et Clever Cloud a une place en trop. Que va t'on en faire? On va organiser une loterie. On tirera au sort le gagnant le 6 Avril. Comment faire pour t'inscrire à la lotterie? Tu dois modifier puis déployer cette application sur [Clever Cloud](http://www.clever-cloud.com).

Modifier le code? Ouvre le fichier `index.js`, on a commenté un appel REST. Il suffit de le décommenter. Il sera exécuté au déploiement de l'application automatiquement. Cet appel vous inscrit au concours! N'oubliez pas non plus de modifier l'objet JSON envoyé par l'appel REST. Il nous aidera à vous contacter.

Ensuite, comment je déploie? Deux possibilités:

## Utiliser le Client CLI Clever Cloud

Pour commencer, la documentation est ici [https://www.clever-cloud.com/doc/clever-tools/getting_started/](https://www.clever-cloud.com/doc/clever-tools/getting_started/).

Installer `clever-tools` avec npm:

````
npm install -g clever-tools
````

Ou bien yarn:

````
yarn global add clever-tools
````

Une fois `clever-tools` installé, placer vous dans ce repository Git et:

````
clever login
clever create --type node mybzhcamp
clever deploy
clever open
````

Vous avez déployer votre application, félicitations 👏 ! Et n'oubliez pas de modifier le fichier `index.js`.

## Utiliser la Console Clever Cloud

Suivez la documentation ici [https://www.clever-cloud.com/doc/nodejs/nodejs/](https://www.clever-cloud.com/doc/nodejs/nodejs/). Et n'oubliez pas de modifier le fichier `index.js`.

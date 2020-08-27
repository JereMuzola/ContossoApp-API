# ContossoApp-API

1. Etant donné la version utilisée de Laravel, il faudra avoir dans votre PATH un exe de PHP de version superieur à 7.2.1
2.tappez la commande composer require all 
3. créer un fichier .env dont le contenu sera celui que vous allez copiez du fichier .env.example (tout copier)
4. pour lancer les migrations de la BD, toujours se placer à la racine et tapez la commande
php artisan migrate (Rassurez vous d'avoir MySQL dans votre machine et d'avoir créer une base de données portant un nom tel que specifié dans le fichier .env,
concernant user et password libre à vous de mettre ce que vous voulez)
5. Pour lister toutes les routes de l'API tapez php artisan route:list
6. pour demarrer le serveur dédié à l'api, il faut se mettre à la racince du repertoire de L'Api est tapé la commande 
php artisan serve


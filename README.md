# TP3_Docker

Il nous est demander de créer un fichier yaml permettant de créer un environnement de développement Web PHP.

Nous allons donc créer un fichier docker-compose.yaml afin de créer un environnement avec les services apache , php , mysql , phpmyadmin.
Une fois le fichier créer 
On lance le fichier 
 > docker-compose up
 
 Notre environnement est mis en place , nous allons maintenant le tester avec un page index php

Créer et configurer un fichier index.php dans /opt/apache2
vim .php/index.php

<html>
    <head>
        <title>PHP Test</title>
    </head>
    <body>
        <?php 
            echo '<p>Hello World</p>';
            phpinfo(); ?>
    </body>
</html>

Vérifier que la page est bien accessible

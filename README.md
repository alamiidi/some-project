# some-project


Pour securiser le mot de passe on va crée une variable d'environnement "DB_PASSWORD" avec cette commande : export DB_PASSWORD='monmotdepasse', celle-ci  contiendra notre mot de passe  qu'on pourra appellé à chaque fois que l'on veut se connecter à notre base de données avec la commande suivante : "process.env.DB_PASSWORD".

Pour sécuriser davantage le dépôt Git nous allons modifié notre mot de passe car celui-ci a été exposé et supprimer notre mot de passe de l'historique des commits, on utilise la commande  "git filter-branch"

Désormais nous pouvons nous connecter à notre base de données en toute securité:
-user:admin
-password:process.env.DB_PASSWORD



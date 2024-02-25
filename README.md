# some-project


Pour securiser le mot de passe on va crée une varibble d'environnement "DB_PASSWORD" avec cette commande :
```bash
export DB_PASSWORD='monmotdepasse' 

celle-ci  contiendra notre mot de passe  qu'on pourra appellé à chaque fois que l'on veut se connecter à notre base de données avec la commande suivante : "process.env.DB_PASSWORD".

Pour sécuriser davantage le dépôt Git et supprimer notre mot de passe de l'historique des commits, on utilise la commande  git filter-branch



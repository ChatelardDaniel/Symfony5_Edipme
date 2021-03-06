# Symfony5_Edipme

- Créer des applications Symfony.

Ouvrez votre terminal de console et exécutez l'une de ces commandes pour créer une nouvelle application Symfony :

```php
symfony new my_project_directory --version=5.4 --webapp
```

- Configurer un projet Symfony existant

En plus de créer de nouveaux projets Symfony, vous travaillerez également sur des projets déjà créés par d'autres développeurs. Dans ce cas, il vous suffit d'obtenir le code du projet et d'installer les dépendances avec Composer. En supposant que votre équipe utilise Git, configurez votre projet avec les commandes suivantes :

```php
cd my-project/
composer install
```

- Lorsque vous travaillez pour la première fois sur une application Symfony existante, il peut être utile d'exécuter cette commande qui affiche des informations sur le projet :

```php
php bin/console about
```

- Exécuter des applications Symfony

```php
cd my-project/
symfony server:start
```

Ouvrez votre navigateur et accédez à <http://localhost:8000/>. Si tout fonctionne, vous verrez une page de bienvenue. Plus tard, lorsque vous avez fini de travailler, arrêtez le serveur en appuyant sur Ctrl+C depuis votre terminal.

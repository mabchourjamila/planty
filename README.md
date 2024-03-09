# Planty

Bienvenue dans le guide d'installation de Planty, un projet de site WordPress.

## Prérequis
Assurez-vous que votre environnement de développement répond aux exigences suivantes :

- Serveur Web : Apache, Nginx ou tout autre serveur web pris en charge par WordPress.
- PHP : Version 7.2 ou supérieure.
- Base de données : MySQL 5.6 ou supérieure ou MariaDB 10.0 ou supérieure.

## Instructions d'Installation
1. **Clonez le dépôt :**
    ```bash
    git clone https://github.com/mabchourjamila/planty.git
    ```

2. **Configurez la base de données :**
   - Importez la base de données et modifiez les accès à la base dans le fichier de configuration de WordPress **wp-config.php** qui se trouve à la racine du projet :
```php
/** The name of the database for WordPress */
define( 'DB_NAME', 'local' );

/** Database username */
define( 'DB_USER', 'root' );

/** Database password */
define( 'DB_PASSWORD', 'root' );

/** Database hostname */
define( 'DB_HOST', 'localhost' );

```

3. **Accédez à votre site WordPress :**
   - Ouvrez votre navigateur et accédez à l'URL de votre site, par exemple : `http://localhost:10015`

4. **Connectez-vous à l'administration :**
   - Connectez-vous à l'administration WordPress avec les identifiants suivants :
     - **URL d'accès à l'interface d'administration WordPress :** `http://localhost:10015/wp-admin`
     - **Nom d'utilisateur :** admin
     - **Mot de passe :** admin

Félicitations ! Vous avez installé avec succès Planty sur votre environnement local.

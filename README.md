# Configuration de l'environnement de travail

## Objectif

Installer et configurer l'environnement de travail pour un projet web ou web mobile utilisant JavaScript, HTML et CSS pour le front-end, Node.js pour le backend, et PostgreSQL comme base de données.

## Prérequis

Assurez-vous d'avoir installé les éléments suivants sur votre machine :

- Un éditeur de code : [Télécharger et installer Visual Studio Code (VS Code)](https://code.visualstudio.com/)
- Node.js : [Télécharger et installer Node.js](https://nodejs.org/)
- Git : [Télécharger et installer Git](https://git-scm.com/)
- Postman : [Télécharger et installer Postman](https://www.postman.com/downloads/)
- PostgreSQL : [Télécharger et installer PostgreSQL](https://www.postgresql.org/download/)

## Étapes de configuration

### 1. Installation de Node.js

- Allez sur le site officiel de Node.js et téléchargez la dernière version.
- Suivez les instructions d'installation.

```bash
npm -v 
node -v
```
Cela affichera la version de npm installée sur votre système

##
### 2. Configuration de Git

- Téléchargez Git à partir du site officiel de Git : [https://git-scm.com](https://git-scm.com).
- Suivez les instructions d'installation.
- Configurez Git en suivant le guide officiel de Visual Studio Code : [Configuration de Git dans VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git).

#### Configuration de Git avec des clés SSH

comment configurer Git sur votre PC avec des clés SSH pour utiliser GitHub de manière sécurisée et sans avoir à saisir votre nom d'utilisateur et votre mot de passe à chaque interaction.

### Étapes

### 1. Installation de Git

- Téléchargez Git à partir du site officiel : [https://git-scm.com/](https://git-scm.com/).
- Suivez les instructions d'installation pour votre système d'exploitation.

#### 2. Génération de la paire de clés SSH

- Vous aurez besoin d’un nom d’utilisateur et d’une adresse email valide pour travailler avec Git. Pour configurer les deux :
Spécifier un nom 	
```bash
git config --global user.name « votre nom »
Spécifier une adresse email : 	
git config --global user.email « adresse exemple@exemple.fr »
```
- Ouvrez un terminal sur votre PC.
- Utilisez la commande suivante pour générer une nouvelle paire de clés SSH :

  ```bash
  ssh-keygen -t rsa -b 4096 -C "votre_email@example.com"

- Créer un référentiel
Créez un nouveau référentiel ou téléchargez un référentiel existant.
- Créer et nommer un nouveau référentiel local : 	
git init nom exemple.
 - Copier un référentiel existant et son historique avec Git Clone: 
 git clone http://pageexemple.de

##

### 3. Téléchargement et installation de Postman

- Téléchargez et installez Postman à partir du site officiel : [https://www.postman.com/downloads/](https://www.postman.com/downloads/).

### 4. Téléchargement et installation de PostgreSQL

- Téléchargez et installez PostgreSQL à partir du site officiel : [https://www.postgresql.org/download/](https://www.postgresql.org/download/).

### 5. Téléchargement et installation de pgAdmin

- Téléchargez et installez pgAdmin pour gérer facilement vos bases de données PostgreSQL.

## Conclusion

Une fois que vous avez suivi ces étapes, vous aurez configuré votre environnement de travail pour développer des projets web ou web mobile avec JavaScript, HTML, CSS, Node.js et PostgreSQL. Vous êtes maintenant prêt à commencer à coder !

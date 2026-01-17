# Mini-Projet Ansible: Déploiement d'une Application

Ce projet consiste en deux étapes pour déployer une application à l'aide d'Ansible : une première étape de déploiement classique et une seconde étape de déploiement en conteneur utilisant Docker, avec le support d'un proxy Nginx en tant que rôle Ansible.

## Prérequis

- **Ansible** installé sur votre machine
- **Docker** installé pour la seconde partie du projet
- Accès à un environnement cible (serveur ou machine virtuelle) où l'application sera déployée

## Partie 1 : Déploiement de l'Application avec un Playbook Simple

### Étapes à suivre

1. **Naviguer dans le répertoire `app-init` du dépôt.**
2. Utiliser le playbook pour déployer l'application du client :
3. Vérifier que l'application est disponible :
   - Utilisez un navigateur web ou une commande curl pour vérifier que l'application est accessible à l'adresse spécifiée.

## Partie 2 : Déploiement de l'Application en Conteneur avec Docker et Nginx en utilisant les rôles ansible

### Étapes à suivre

1. Naviguer dans le répertoire app-template du dépôt.
2. Compléter les fichiers de configuration :

    - Remplacez les expressions <FIX IT> par les valeurs appropriées dans les fichiers de rôle pour l'application et Nginx.
    - Assurez-vous que les configurations Ansible pour Docker et Nginx sont correctement définies.
    - Redigez entièrement le contenu du fichier webapp/task/main.yml afin de deployer l'application conteneuriser en utilisant le proxy nginx
      
3. Lancer le playbook pour déployer l'application

### Vérification

Partie 1 : L'application doit être accessible après le déploiement avec un simple playbook.

Partie 2 : L'application doit être accessible via un proxy Nginx dans un conteneur Docker après avoir complété les fichiers et lancé le playbook.

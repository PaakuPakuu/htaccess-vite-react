# Fichier .htaccess

Ce référentiel contient un fichier `.htaccess` destiné à être utilisé sur un serveur web Apache. Le fichier `.htaccess` est un fichier de configuration qui permet de définir des règles de redirection et de réécriture d'URL, ainsi que d'autres configurations spécifiques au serveur Apache.

## Fonctionnalités

Le fichier `.htaccess` fournit les fonctionnalités suivantes :

1. **Redirection HTTP vers HTTPS :** Toutes les connexions HTTP sont redirigées vers HTTPS pour garantir une connexion sécurisée.

2. **Réécriture d'URL :** Les URL demandées qui ne correspondent pas à des fichiers existants sont réécrites pour acheminer toutes les demandes vers la page d'accueil (`index.html`).

## Utilisation

Pour utiliser ce fichier `.htaccess` sur un serveur Apache, suivez ces étapes :

1. Assurez-vous que le module `mod_rewrite` est activé sur votre serveur Apache. Vous pouvez le vérifier dans la configuration du serveur.

2. Copiez le contenu du fichier `.htaccess` de ce référentiel dans le fichier `.htaccess` de votre projet sur le serveur.

3. Redémarrez le serveur Apache pour que les modifications prennent effet.

## Remarques

- Assurez-vous de sauvegarder votre fichier `.htaccess` actuel s'il en existe un avant de le remplacer par celui-ci, au cas où vous auriez déjà des règles spécifiques à votre projet.

- Avant de déployer ces règles sur un serveur en production, testez-les d'abord sur un environnement de développement pour vous assurer qu'elles fonctionnent comme prévu.

<h1 align="center">
 🚩Suggest Bot⚙
</h1>
# Discord Lgd-Captcha Bot

Ce bot Discord permet de sécuriser votre serveur en obligeant les nouveaux membres à passer un test CAPTCHA avant de rejoindre votre communauté.

## Installation

1. Clonez ce dépôt sur votre machine ou serveur.
2. Exécutez `npm install` pour installer les dépendances.
3. modifier le fichier config.example.json.json en `config.json` et remplissez le correctement.
4. Exécutez le bot en lançant la commande `node index.js` ou en utilisant une méthode de déploiement de votre choix.

## Utilisation

Lorsqu'un nouveau membre rejoint votre serveur, le bot va envoyer un message contenant une image CAPTCHA et un bouton "Répondre". Le membre devra répondre au test CAPTCHA en entrant le code affiché dans l'image dans une fenêtre modale, accessible en cliquant sur le bouton "Répondre". Si le membre répond correctement au test, le bot lui attribuera le ou les rôles spécifiés dans `config.json`. Si le membre répond incorrectement ou ne répond pas dans le temps imparti, il sera automatiquement expulsé du serveur.

## Configuration

La configuration du bot se fait via le fichier `config.json`. Vous pouvez y spécifier le canal où le test CAPTCHA sera envoyé, le temps imparti pour répondre au test, les rôles à attribuer aux membres qui passent le test, et plus encore.

## Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez soumettre une correction de bogue, une amélioration ou une nouvelle fonctionnalité, veuillez créer une "pull request" depuis une branche séparée.

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

## Credit
- ['Hawk#4890'](https://github.com/HawkButGithub/Captcha-Bot)

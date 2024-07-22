# Hook Git post-commit

Ce script de hook `post-commit` demande à l'utilisateur de valider le processus de création et d'ajout d'un fichier de vérification après chaque commit.

## Installation

Pour installer le hook, suivez les étapes suivantes :

1. Copiez le script `post-commit` dans le répertoire `.git/hooks` de votre dépôt :

   ```sh
   cp hooks/post-commit .git/hooks/

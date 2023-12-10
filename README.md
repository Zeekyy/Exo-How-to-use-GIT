# Exo-How-to-use-GIT
Exo related to the use of GIT for ESGI B3

# Présentation de Git

Git est un système de contrôle de version distribué largement utilisé dans le développement de logiciels. Il permet de suivre les modifications apportées aux fichiers et de collaborer efficacement avec d'autres développeurs.

Les principales caractéristiques de Git sont les suivantes :

- **Décentralisé** : Chaque développeur dispose d'une copie complète de l'historique du projet, ce qui permet de travailler hors ligne et de fusionner les modifications ultérieurement.
- **Branches** : Git facilite la création et la gestion de branches, ce qui permet de travailler sur des fonctionnalités ou des correctifs de manière isolée avant de les fusionner dans la branche principale.
- **Historique complet** : Git enregistre toutes les modifications apportées aux fichiers, ce qui permet de revenir en arrière, de comparer les versions et de comprendre l'évolution du projet.
- **Collaboration** : Git facilite la collaboration entre les développeurs en permettant de partager facilement les modifications et de résoudre les conflits lors de la fusion des branches.

En résumé, Git est un outil puissant et flexible qui facilite la gestion des versions et la collaboration dans les projets de développement de logiciels.

# Installation de Git

Git est disponible pour Windows, macOS et Linux. Vous pouvez télécharger les installateurs à partir du site officiel de Git : https://git-scm.com/downloads

# Commandes de base

## Initialiser un dépôt

Pour créer un nouveau dépôt Git, utilisez la commande `git init`. Cette commande crée un nouveau sous-répertoire nommé `.git` qui contient tous les fichiers nécessaires au dépôt, ce qui rend le répertoire de travail actuel un dépôt Git.

```bash
git init
```

## Cloner un dépôt

Pour créer une copie locale d'un dépôt distant, utilisez la commande `git clone`. Vous devez spécifier l'URL du dépôt distant à cloner.

```bash
git clone <url>
```

## Vérifier l'état des fichiers

Pour obtenir des informations sur les fichiers modifiés dans le répertoire de travail, utilisez la commande `git status`.

```bash
git status
```

## Suivre les nouveaux fichiers

Pour ajouter un nouveau fichier au suivi, utilisez la commande `git add`.

```bash
git add <file>
```

# Création d'un dépot GIT

## Création d'un dépot GIT en local

Das la console, initialisation du dépot:

```bash
git init
``

## Visualisation de l'état du GIT

```bash
git status
``
### Pour voir les fichiers et dossiers Unix

```bash
ls-a
```

## Pour ajouter un fichier à la future sauvegarde

```bash
git README.md
```

## Pour effectuer la sauvegarde

Les fichiers en attentes de sauvegarde sont en vert>

Les fichiers non suivi sont en rouge.

Seul les fichiers en **stagging** seront sauvés

```bash
git commit -m"message du commit"

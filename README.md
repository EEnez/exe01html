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
```
Un commit est une sauvegarde, on peut y accéder avec un `gitlog` (affichage des identifiants des s> et `gitshow` (sans paramétres, affichage du dernier commit)

## Pour afficher tous les fichiers en stagging

```bash
git add .
```

## Ajout d'un serveur

Nous allons utiliser un dépôt que l'on va créer sur github.com,
après connexion. Comme c'est un travail personnel, son URL sera git@github.com:EEnez/exe01html.git

Nous créeons un nex Repository, puis nous copions la clef SSH :

git@github.com:EEnez/exe01html.git

Nous retournons dans notre console

```bash 
git remote add origin git@github.com:EEnez/exe01html.git
```

Pour voir si ça a fonctionné :

```bash
git remote -v
```

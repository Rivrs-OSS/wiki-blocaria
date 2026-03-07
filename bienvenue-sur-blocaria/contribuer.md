---
description: >-
  Retrouvez ici toutes les informations vous permettant de nous aider à modifier
  ce wiki
icon: pen-to-square
---

# Contribuer

Bienvenue ! Ce guide vous accompagnera pas à pas dans la **contribution** au wiki du projet **Blocaria** sur **GitHub**.

### 📋 Pré-requis <a href="#pre-requis" id="pre-requis"></a>

* Créez un compte GitHub : [Inscription GitHub](https://github.com/join).
* Installez Git sur votre ordinateur : [Télécharger Git](https://git-scm.com/downloads).
* Choisissez un éditeur simple et convivial comme [Visual Studio Code](https://code.visualstudio.com/).

### ⚙️ Installer et configurer Git <a href="#installer-et-configurer-git" id="installer-et-configurer-git"></a>

Après l'installation, ouvrez votre terminal et configurez votre nom et email (ceux utilisés pour GitHub) :

<a class="button secondary">Copy</a>

```
git config --global user.name "Votre Nom"
git config --global user.email "votre-email@example.com"
```

### 🚀 Faire une contribution <a href="#faire-une-contribution" id="faire-une-contribution"></a>

#### 1. Forker le Repository <a href="#id-1.-forker-le-repository" id="id-1.-forker-le-repository"></a>

* Rendez-vous sur [wiki-blocaria](https://github.com/Rivrs-OSS/wiki-blocaria)
* Cliquez sur le bouton **Fork** en haut à droite pour créer une copie du repository sur votre compte.

#### 2. Cloner votre Fork sur votre ordinateur <a href="#id-2.-cloner-votre-fork-sur-votre-ordinateur" id="id-2.-cloner-votre-fork-sur-votre-ordinateur"></a>

Copiez le lien de votre fork puis dans votre terminal :

<a class="button secondary">Copy</a>

```
git clone https://github.com/VOTRE-NOM-UTILISATEUR/wiki-blocaria.git
cd wiki-blocaria
```

#### 3. Créer une nouvelle branche <a href="#id-3.-creer-une-nouvelle-branche" id="id-3.-creer-une-nouvelle-branche"></a>

Créer une branche par sujet traité pour bien organiser vos contributions :

<a class="button secondary">Copy</a>

```
git checkout -b nom-de-votre-branche
```

Exemple : `git checkout -b ajout-guide-capture`

#### 4. Modifier le Wiki <a href="#id-4.-modifier-le-wiki" id="id-4.-modifier-le-wiki"></a>

* Utilisez Visual Studio Code pour éditer les fichiers markdown (`.md`).
* Vous pouvez également créer de nouveaux fichiers, par exemple `comment-creer-ma-box.md`.

Exemple de structure markdown simple :

<a class="button secondary">Copy</a>

```
# Titre principal

## Sous-titre

Votre contenu ici...

- Liste à puces
- Second point

[Un lien utile](http://example.com)
```

#### 5. Ajouter vos modifications à Git <a href="#id-5.-ajouter-vos-modifications-a-git" id="id-5.-ajouter-vos-modifications-a-git"></a>

Dans votre terminal, ajoutez et validez vos changements :

<a class="button secondary">Copy</a>

```
git add .
git commit -m "Ajout du guide sur les métiers"
```

#### 6. Envoyer votre contribution <a href="#id-6.-envoyer-votre-contribution" id="id-6.-envoyer-votre-contribution"></a>

Envoyez vos modifications sur GitHub :

<a class="button secondary">Copy</a>

```
git push origin nom-de-votre-branche
```

#### 7. Ouvrir une Pull Request (PR) <a href="#id-7.-ouvrir-une-pull-request-pr" id="id-7.-ouvrir-une-pull-request-pr"></a>

* Retournez sur votre fork du projet GitHub.
* Cliquez sur **Compare & pull request**.
* Décrivez votre contribution clairement puis validez en cliquant sur **Create pull request**.

### 💡 Bonnes pratiques et conseils <a href="#bonnes-pratiques-et-conseils" id="bonnes-pratiques-et-conseils"></a>

* Restez clair et concis dans vos explications.
* Vérifiez l'orthographe et la grammaire.
* Structurez bien vos pages markdown.
* Utilisez les prévisualisations markdown de Visual Studio Code (Ctrl + Shift + V) avant de soumettre.

### 🛠️ En cas de problème <a href="#en-cas-de-probleme" id="en-cas-de-probleme"></a>

N'hésitez pas à créer une [issue](https://github.com/Rivrs-OSS/wiki-blocaria/issues) sur GitHub pour demander de l'aide ou poser une question.

Merci pour votre contribution ! ✨

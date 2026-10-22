# Suivi des dossiers

Application de suivi des dossiers clients par statut et produit.

## Installation sur Android

1. Va sur : `https://YOUR_USERNAME.github.io/suivi-dossiers/`
2. Ouvre Chrome
3. Clique sur le menu ⋮ → **Installer l'app** (ou appuie longuement sur le bouton "Accueil" en bas)
4. L'app s'installe sur ton écran d'accueil !

L'app fonctionne hors ligne et sauvegarde tes dossiers localement.

## Fichiers

- `index.html` - L'application principale
- `manifest.json` - Configuration PWA (pour l'installation)
- `sw.js` - Service Worker (pour le mode hors ligne)

## Mise à jour

Pour mettre à jour l'app après l'installation, supprime et réinstalle depuis le navigateur.

## Signature mail

`signature/index.html` : générateur de signature e-mail AV Patrimoine pour Outlook (ordinateur et Android), avec un profil Antoine et un profil Charlotte & Camille. La signature est responsive : colonnes côte à côte sur ordinateur, empilées sur téléphone.

1. Active GitHub Pages sur le dépôt (Settings → Pages → branche principale).
2. Ouvre `https://aversichel.github.io/business-suivi/signature/`.
3. Choisis le profil et la version (ordinateur / téléphone), puis **Copier la signature** et colle-la dans les paramètres de signature d'Outlook.

Photos, logo et icônes sont dans `signature/img/` et doivent être en ligne pour s'afficher chez les destinataires.

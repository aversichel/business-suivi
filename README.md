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

`signature/index.html` : générateur de signature e-mail AV Patrimoine pour Outlook, avec un profil Antoine et un profil Charlotte & Camille.

- Version en ligne (artefact claude.ai) : https://claude.ai/artifact/MrJhSEJKBKxZKyndvmcJku
- Parcours en 3 étapes : choisir la signature, choisir son Outlook, puis copier (ou télécharger).
- Un format par Outlook : fluide pour le nouvel Outlook / Outlook web (se réorganise sur petit écran), tableau fixe pour Outlook classique (avec une variante compacte), texte simple pour l'appli mobile.
- Format image (PNG) en alternative : la mise en page est garantie, mais rien n'est cliquable. Rendu par `signature/vendor/html2canvas.min.js` (html2canvas 1.4.1, licence MIT).
- Les images des signatures sont hébergées sur `https://avpatrimoine.fr/assets/partage/` (mêmes noms de fichiers que `signature/img/`, qui sert à l'aperçu).

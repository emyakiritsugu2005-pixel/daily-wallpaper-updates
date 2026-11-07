# Daily Wallpaper — Téléchargements & mises à jour

Ce dépôt héberge **uniquement les versions publiées** de l'application
Daily Wallpaper pour Windows (installateurs et fichiers de mise à jour).

Le code source se trouve dans un dépôt non public

## 📥 Télécharger

Rendez-vous sur la page [Releases](https://github.com/emyakiritsugu2005-pixel/daily-wallpaper-updates/releases)
et téléchargez `Daily-Wallpaper-Setup-x.y.z.exe` depuis la dernière version.

## 🖼️ C'est quoi Daily Wallpaper ?

Application Windows (Electron) qui change automatiquement votre fond d'écran :

- ⏱️ Rotation automatique réglable (1 à 60 min) ou "photo du jour" à heure fixe
- 🌍 Sources : dossier local, images en ligne, catégories (Wikimedia), NASA (photo astronomique du jour)
- 🖥️ Multi-écrans : une image différente par écran
- 🌙 Horaires de silence (pas de changement la nuit)
- 🖱️ Fond suivant/précédent au clic droit du bureau
- ⌨️ Raccourci global `Ctrl+Alt+W`

## 🔄 Mises à jour automatiques

L'application vérifie les nouvelles versions au démarrage et se met à jour
toute seule (téléchargement puis installation à la fermeture ou au redémarrage).
Le fichier `latest.yml` présent dans chaque release est le manifeste utilisé
par `electron-updater`.

> ℹ️ Les installateurs ne sont pas signés numériquement : Windows/SmartScreen
> peut afficher un avertissement à l'installation — c'est normal, cliquez
> "Informations complémentaires" → "Exécuter quand même".


---
Auteur : Devemya

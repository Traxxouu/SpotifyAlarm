# SpotiClock ⏰

**SpotiClock** est une application de bureau conçue pour améliorer votre routine de réveil en intégrant une horloge personnalisable avec des playlists Spotify. Réglez l'heure de l'alarme, fournissez une URL de playlist Spotify, et SpotiClock s'occupera du reste. Lorsque l'alarme se déclenche, elle ouvrira votre playlist dans un navigateur web et simulera un clic de souris pour démarrer automatiquement votre musique préférée.

## Fonctionnalités 🔧

- **Heure d'alarme personnalisable** : Réglez l'heure de l'alarme à l'heure, à la minute et à la seconde.
- **Intégration de playlists Spotify** : Fournissez une URL de playlist Spotify pour vous réveiller avec vos morceaux préférés.
- **Clic de souris automatique** : L'application simule un clic de souris pour démarrer automatiquement la playlist.
- **Interface conviviale** : Interface facile à utiliser construite avec Tkinter.

## Captures d'écran 🖼️

![Interface principale](path_to_screenshot_1)
*Interface principale de SpotiClock*

![Définir la position de la souris](path_to_screenshot_2)
*Fenêtre popup pour définir la position de la souris*

## Téléchargement .exe ⬇️

Pour télécharger l'application en fichier .EXE, cliquez sur le logo ci-dessous :

[![Télécharger SpotiClock](path_to_download_logo)](link_to_exe_file)

## Installation .py 🧰

1. Clonez le dépôt :
    ```bash
    git clone https://github.com/yourusername/SpotiClock.git
    ```
2. Installez les bibliothèques nécessaires :
    ```bash
    pip install pyautogui pytz
    ```
3. Exécutez l'application :
    ```bash
    python spoticlock.py
    ```

## Utilisation 🪛

1. **Définir la position de la souris** : Cliquez sur le bouton "Commencer" pour ouvrir une fenêtre popup. Vous aurez 6 secondes pour déplacer votre souris à l'emplacement où se trouve le bouton de lecture de Spotify. L'application enregistrera la position de la souris.
2. **Régler l'heure de l'alarme** : Utilisez les menus déroulants pour définir l'heure, la minute et la seconde de l'alarme.
3. **Entrer l'URL de la playlist Spotify** : Copiez et collez l'URL de votre playlist Spotify préférée dans le champ prévu à cet effet.
4. **Démarrer l'alarme** : Cliquez sur le bouton "Régler l'alarme" pour régler l'alarme. Lorsque l'heure de l'alarme est atteinte, l'application ouvrira l'URL de la playlist dans votre navigateur web par défaut et simulera un clic de souris pour démarrer la musique.

## Prérequis ⚡

- Python 3.x
- Tkinter
- PyAutoGUI
- Pytz

## Contribution 🦾

Si vous souhaitez contribuer à SpotiClock, veuillez forker le dépôt et utiliser une branche de fonctionnalité. Les pull requests sont les bienvenues.

## Licence 📜

Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.

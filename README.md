# Élite Body & Beauty Center — Tanger

Version autonome du site vitrine, reconstituée à partir de la sauvegarde locale Chrome (HTML, CSS, JavaScript et images).

## Lancer

Ouvrez `index.html` dans votre navigateur, ou utilisez un serveur statique :

```sh
python -m http.server 8080
```

Puis visitez http://localhost:8080

## Déployer sur GitHub Pages

Après avoir envoyé les fichiers dans la branche `main`, rendez-vous dans **Settings → Pages → Build and deployment → Deploy from a branch**, puis choisissez `main` et `/ (root)`.

## Remarques

- Il s'agit du code public sauvegardé par Chrome, et non de l'export original du projet ChatGPT Sites.
- `facade.webp` ne figurait pas dans l'archive. Pour éviter une image cassée, la photo de la réception est réutilisée dans la section Contact. Vous pouvez rétablir une photo de façade en ajoutant `assets/facade.webp` et en remplaçant la référence correspondante.
- Le formulaire de rendez-vous ouvre WhatsApp, il n'utilise pas de serveur ni de base de données.
- Les polices Google Fonts nécessitent une connexion internet.
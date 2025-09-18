# TiltVolume — YouTube au tilt (GitHub Pages)

App web qui intègre une vidéo YouTube et règle le volume automatiquement selon l’inclinaison du téléphone en mode portrait.

## Déploiement sur GitHub Pages

1. Crée un dépôt **public** sur GitHub, par ex. `tiltvolume`.
2. Ajoute les fichiers de ce dossier (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`).
3. Commit & push sur la branche **main**.
4. Dans **Settings → Pages** :
   - *Build and deployment* → **Deploy from branch**
   - *Branch* → **main** (/**root**)
5. L’URL sera `https://<ton-username>.github.io/tiltvolume/`

## Utilisation sur iPhone
- Ouvre la page, colle un lien YouTube → **Intégrer**.
- Appuie sur **Activer le contrôle par inclinaison** et autorise l’accès.
- **Lire / Pause** si iOS bloque l’autoplay.
- Ajoute sur l’écran d’accueil (Share → Add to Home Screen) pour la version PWA.

> Remarque : le volume agit sur le lecteur YouTube intégré, pas le volume système iOS.

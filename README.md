# Studio Signaux 6GEI418

Application de révision du chapitre 1 de Signaux et systèmes (UQAC) : 35 slides animées, oscilloscope, atelier x(at + b), simulateur de systèmes et quiz.

C’est une application web installable (PWA) : une fois en ligne sur GitHub Pages, elle s’installe sur le téléphone avec son icône, s’ouvre en plein écran et fonctionne hors ligne après la première ouverture.

## Mettre en ligne sur GitHub Pages

1. Sur github.com, crée un nouveau dépôt **public** (par exemple `studio-signaux`).
2. Dans le dépôt : **Add file → Upload files**, puis sélectionne **tous les fichiers** du dossier (index.html, sw.js, manifest.webmanifest et les 5 icônes .png). Clique **Commit changes**.
3. **Settings → Pages** → Source : **Deploy from a branch** → Branch : **main** / **(root)** → **Save**.
4. Attends une à deux minutes. L’adresse s’affiche en haut de la page Pages :
   `https://TON-NOM.github.io/studio-signaux/`

## Installer sur le téléphone

- **Android (Chrome)** : ouvre l’adresse, touche le bouton **Installer** dans la barre du haut (ou menu ⋮ → **Installer l’application**).
- **iPhone (Safari)** : ouvre l’adresse, touche **Partager** puis **Sur l’écran d’accueil**.

## Mettre à jour plus tard

1. Remplace `index.html` dans le dépôt (Upload files).
2. Dans `sw.js`, change `signaux-v1` en `signaux-v2` (puis v3, etc.) pour que les téléphones récupèrent la nouvelle version.
3. Ferme et rouvre l’application sur le téléphone.

## Contenu du dossier

| Fichier | Rôle |
| --- | --- |
| `index.html` | toute l’application |
| `manifest.webmanifest` | nom, icônes et couleurs de l’application installée |
| `sw.js` | mise en cache pour l’utilisation hors ligne |
| `*.png` | icônes (Android, iPhone, onglet du navigateur) |

# QCM - Révisions

Deux quiz interactifs de révision (Architecture des ordinateurs, Architecture réseaux) en HTML/CSS/JS, avec une page d'accueil commune. Le style est centralisé dans `style.css`, partagé par les trois pages.

## Fichiers à publier

- `index.html` — page d'accueil (menu)
- `architecture.html` — quiz Architecture des ordinateurs
- `reseaux.html` — quiz Architecture réseaux
- `style.css` — feuille de style partagée par les trois pages

## Publier avec GitHub Pages

1. Crée un nouveau repository sur GitHub (public).
2. Ajoute les 4 fichiers ci-dessus au repo.
3. Va dans **Settings → Pages**.
4. Dans "Build and deployment", choisis **Source : Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/ (root)`, puis **Save**.
6. Après 1-2 minutes, ton site est disponible à :
   `https://<ton-pseudo>.github.io/<nom-du-repo>/`

Ajoute cette adresse à l'écran d'accueil de ton iPhone (bouton Partager → "Sur l'écran d'accueil") pour un accès en un tap, comme une app.

## Mise à jour

- Pour modifier des questions : édite directement `architecture.html` ou `reseaux.html` (tableau `Q` dans le `<script>`).
- Pour modifier le style (couleurs, polices, espacements) : édite uniquement `style.css`, ça s'applique aux trois pages automatiquement.
- Repousse (`git push`, ou ré-upload sur github.com) : GitHub Pages se met à jour automatiquement.

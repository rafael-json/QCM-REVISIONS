# QCM - Architecture des ordinateurs

Quiz interactif de révision (10 modules) en HTML/CSS/JS autonome, sans dépendance externe.

## Publier avec GitHub Pages

1. Crée un nouveau repository sur GitHub (public).
2. Ajoute ce dossier au repo (`index.html` + ce `README.md`).
3. Va dans **Settings → Pages**.
4. Dans "Build and deployment", choisis **Source : Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/ (root)`, puis **Save**.
6. Après 1-2 minutes, ton site est disponible à :
   `https://<ton-pseudo>.github.io/<nom-du-repo>/`

Ouvre cette adresse dans Safari sur iPhone : elle s'affiche comme un vrai site web, avec possibilité de l'ajouter à l'écran d'accueil (bouton Partager → "Sur l'écran d'accueil") pour un accès en un tap, comme une app.

## Mise à jour du quiz

Pour modifier les questions, édite directement `index.html` (tableau `Q` dans le `<script>`), puis repousse (`git push`) — GitHub Pages se met à jour automatiquement.

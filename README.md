# cecho-public

Repo public minimal servant uniquement à héberger les pages légales/publiques de
l'app **Cécho** (jeu de soirée, éditée par CopierAndColler) via GitHub Pages —
sans rendre public le code source du jeu, qui reste dans un repo privé séparé.

## Contenu

- `privacy-policy.html` — politique de confidentialité, dont l'URL est renseignée
  dans les fiches App Store Connect / Google Play Console.

Ce fichier est une copie de `docs/privacy-policy.html` du repo principal (privé).
En cas de modification, penser à répercuter le changement dans les deux repos.

## Activer GitHub Pages (une fois)

1. Settings → Pages → Source : "Deploy from a branch" → branche `main` → dossier
   `/ (root)`.
2. Chez le registrar du domaine `copierandcoller.fr`, ajouter un enregistrement
   DNS de type `CNAME` : `cecho` → `bibenji.github.io.`
3. Le fichier `CNAME` de ce repo indique déjà à GitHub Pages le domaine
   personnalisé (`cecho.copierandcoller.fr`) — une fois le DNS propagé, GitHub
   provisionne automatiquement le certificat HTTPS.

URL finale : `https://cecho.copierandcoller.fr/privacy-policy.html`

Le pseudo GitHub (`bibenji`) sert uniquement de cible technique au CNAME, il
n'apparaît jamais dans l'URL vue par les utilisateurs/reviewers des stores.

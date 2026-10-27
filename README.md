# claude-prime

Portfolio de John Apple — site statique publié avec **GitHub Pages**.

🌐 <https://johnapplewan.github.io/claude-prime/>

## Contenu du dépôt

| Fichier | Rôle |
| --- | --- |
| `index.html` | Le site : une seule page, HTML + CSS + un peu de JavaScript intégrés. |
| `assets/logo-noir.webp`, `logo-marine.webp`, `logo-or.webp` | Le monogramme JA en trois versions, recadré. Chaque fond est identique, au pixel près, à la couleur de la page : noir `#000000`, marine `#002454`, or `#a67e42`. |
| `assets/icon-512.png`, `apple-touch-icon.png`, `favicon-48.png` | Icônes du site (monogramme or). |
| `assets/og.png` | Image affichée quand le lien est partagé (1200 × 630). |
| `assets/fonts/` | Bodoni Moda et Jost, auto-hébergées (licence SIL OFL 1.1, textes joints). |
| `.nojekyll` | Les fichiers sont servis tels quels, sans traitement Jekyll. |
| `.github/workflows/pages.yml` | Déploiement automatique sur GitHub Pages via GitHub Actions. |

## Activer GitHub Pages

1. Ouvrir le dépôt sur GitHub, puis **Settings → Pages**.
2. Dans **Build and deployment**, choisir **Source : GitHub Actions**.
3. C'est tout : à chaque mise à jour de `main`, le workflow **Déployer sur GitHub Pages** publie le site.
   Pour le lancer à la main : onglet **Actions → Déployer sur GitHub Pages → Run workflow**.

Le site est aussi compatible avec **Deploy from a branch** (`main`, `/ (root)`), mais il faut
choisir l'une **ou** l'autre source : avec « Deploy from a branch », le workflow échouerait.

## Tester en local

Ouvrir simplement `index.html` dans un navigateur, ou lancer un petit serveur :

```bash
python3 -m http.server 8000
```

puis visiter <http://localhost:8000>.

## Modifier le site

Éditer `index.html`, committer et pousser sur `main` : GitHub Pages redéploie automatiquement le site.

# claude-prime

Portfolio de John Apple — site statique publié avec **GitHub Pages**.

🌐 Une fois activé, le site sera disponible à l'adresse :
<https://johnapplewan.github.io/claude-prime/>

## Contenu du dépôt

| Fichier      | Rôle                                                              |
| ------------ | ----------------------------------------------------------------- |
| `index.html` | Page d'accueil du site (HTML + CSS intégrés, aucune dépendance).  |
| `.nojekyll`  | Désactive le traitement Jekyll : les fichiers sont servis tels quels. |
| `README.md`  | Ce fichier.                                                       |
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

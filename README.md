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

## Activer GitHub Pages

1. Ouvrir le dépôt sur GitHub, puis **Settings → Pages**.
2. Dans **Build and deployment**, choisir **Source : Deploy from a branch**.
3. Sélectionner la branche `main` et le dossier `/ (root)`, puis **Save**.
4. Après une ou deux minutes, le site est en ligne à l'adresse indiquée ci-dessus.

## Tester en local

Ouvrir simplement `index.html` dans un navigateur, ou lancer un petit serveur :

```bash
python3 -m http.server 8000
```

puis visiter <http://localhost:8000>.

## Modifier le site

Éditer `index.html`, committer et pousser sur `main` : GitHub Pages redéploie automatiquement le site.

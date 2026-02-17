# Site Portfolio - Robin Gourgues

Portfolio personnel développé avec Astro.

## 🚀 Déploiement sur GitHub Pages

Ce site est configuré pour être déployé automatiquement sur GitHub Pages.

### Configuration actuelle

- **URL du site**: https://summerflamme.github.io/Portfolio/
- **Base URL**: `/Portfolio`
- **Répertoire de build**: `docs/`

### Instructions de déploiement

1. **Build du projet** :
   ```bash
   npm run build
   ```
   Cette commande génère le site dans le dossier `docs/`.

2. **Commit et push** :
   ```bash
   git add .
   git commit -m "Update site"
   git push origin main
   ```

3. **Configuration GitHub Pages** :
   - Allez dans **Settings** → **Pages** de votre dépôt
   - Source : **Deploy from a branch**
   - Branch : **main** / **/docs**
   - Sauvegardez

Le site sera automatiquement déployé à chaque push.

## 🛠️ Développement local

```bash
# Installer les dépendances
npm install

# Lancer le serveur de développement
npm run dev

# Prévisualiser le build
npm run preview
```

## 📦 Structure du projet

```
/
├── public/          # Fichiers statiques (images, PDF, etc.)
├── src/
│   ├── components/  # Composants Astro réutilisables
│   ├── content/     # Contenu des projets (Markdown)
│   ├── layouts/     # Layouts de page
│   ├── pages/       # Pages du site
│   └── styles/      # Styles globaux
├── docs/            # Build pour GitHub Pages (généré)
└── astro.config.mjs # Configuration Astro
```

## ⚙️ Configuration importante

Le fichier `astro.config.mjs` contient la configuration pour GitHub Pages :

```javascript
export default defineConfig({
    site: 'https://summerflamme.github.io',
    base: '/Portfolio',
    outDir: './docs',
});
```

- `site` : URL de base de GitHub Pages
- `base` : Nom du dépôt (important pour les chemins)
- `outDir` : Répertoire de sortie pour le build

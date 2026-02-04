# WebsiteBuild 🌐

Sites web professionnels livrés en 48h.

## 🚀 Déploiement

### Option 1: Railway (Recommandé)

1. **Créer un compte Railway**
   - Va sur [railway.app](https://railway.app)
   - Connecte-toi avec GitHub

2. **Déployer depuis GitHub**
   - Clique sur "New Project"
   - Sélectionne "Deploy from GitHub repo"
   - Choisis ce repository
   - Railway détecte automatiquement Node.js et déploie

3. **Configurer le domaine**
   - Dans Settings > Domains
   - Génère un domaine Railway gratuit ou connecte ton domaine custom

### Option 2: Vercel

```bash
npm i -g vercel
vercel
```

### Option 3: Local

```bash
# Installer les dépendances
npm install

# Lancer le serveur
npm start

# Le site est accessible sur http://localhost:3000
```

## 📁 Structure

```
websitebuild/
├── public/
│   └── index.html      # Landing page
├── server.js           # Serveur Express
├── package.json        # Config npm
└── README.md
```

## 🛠 Stack technique

- **Frontend**: HTML, CSS (vanilla)
- **Backend**: Node.js + Express
- **Hosting**: Railway / Vercel

## 📝 Ajouter une page

1. Créer le fichier HTML dans `/public/`
2. Le fichier est automatiquement servi

Exemple: `/public/mentions-legales.html` → accessible sur `/mentions-legales.html`

## 🔧 Variables d'environnement

| Variable | Description | Default |
|----------|-------------|---------|
| `PORT` | Port du serveur | 3000 |
| `NODE_ENV` | Environment | development |

## 📧 Contact

contact@websitebuild.store

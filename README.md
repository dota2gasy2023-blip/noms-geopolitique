# Base de Noms Géopolitiques - GPTV

Site statique contenant la base de référence de noms propres pour ChatGPT.

## 📝 Instructions de déploiement

### 1. Créer un repo GitHub

```bash
# Clone ou crée un nouveau repo
git init noms-geopolitiques
cd noms-geopolitiques

# Copie tous les fichiers ici:
# - noms-geopolitiques.html
# - geopolitique-db-cleaned.json
# - package.json
# - vercel.json
# - README.md

git add .
git commit -m "Initial commit"
git remote add origin https://github.com/TON_USERNAME/noms-geopolitiques.git
git push -u origin main
```

### 2. Déployer sur Vercel

**Option A: Via l'interface Vercel**
1. Va sur https://vercel.com
2. Clique "New Project"
3. Importe ton repo GitHub
4. Clique "Deploy"

**Option B: Via CLI**
```bash
npm install -g vercel
vercel
```

### 3. Accès

Une fois déployé, l'URL sera quelque chose comme:
- `https://noms-geopolitiques.vercel.app`

ChatGPT pourra accéder à cette URL pour vérifier les noms!

## 📚 Contenu

- `noms-geopolitiques.html` - Page HTML avec interface
- `geopolitique-db-cleaned.json` - Base de 5000+ noms
- Responsive design pour tous les appareils

## ⚙️ Configuration

Aucune configuration nécessaire! Vercel détecte les fichiers statiques automatiquement.

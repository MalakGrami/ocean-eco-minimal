# Ocean - Gardiens des Mers

Site web éco-conçu multi-pages pour la sensibilisation à la conservation des océans.

## Structure du Site

- **[index.html](index.html)** - Page d'accueil avec navigation (4.5 KB)
- **[crise.html](crise.html)** - État critique des océans (7.5 KB)
- **[solutions.html](solutions.html)** - Solutions pour sauver les océans (8.6 KB)
- **[agir.html](agir.html)** - Actions concrètes à votre portée (10 KB)
- **[apropos.html](apropos.html)** - Principes d'éco-conception du site (11 KB)

**Total : 41.6 KB pour 5 pages**

## Caractéristiques du Challenge

✅ **Une seule requête par page** - Chaque page contient son propre HTML + CSS inline, pas de fichiers externes
✅ **Poids < 50KB** - Chaque page < 12KB (75% sous la limite)
✅ **Contenus texte prioritaires** - Zéro image, priorité à l'information
✅ **Accessibilité totale** - Navigation clavier (Alt+C, Alt+S, Alt+A), contrastes optimaux, HTML sémantique
✅ **Terminal-friendly** - Compatible w3m, links, lynx
✅ **Code minimaliste** - Zéro framework, zéro JavaScript, CSS inline uniquement

## Principes Gemini Appliqués

- Contenu textuel prioritaire
- Design sobre et efficace
- Pas de tracking, pas de cookies
- Respect du temps et de la bande passante du visiteur
- Accessible partout, même sur connexions lentes

## Déploiement

### Option 1: GitHub Pages (Gratuit)

```bash
git init
git add .
git commit -m "Initial commit - Ocean eco-site"
git branch -M main
git remote add origin https://github.com/..
git push -u origin main
```

Puis activez GitHub Pages dans les paramètres du repo (Settings > Pages > Source: main branch)



### Option 3: Vercel

```bash
npm i -g vercel
vercel --prod
```

### Option 4: Serveur local

```bash
python3 -m http.server 8000
# Ouvrir http://localhost:8000
```

## Navigation Clavier

- `Alt+C` - Page Crise (depuis l'accueil)
- `Alt+S` - Page Solutions (depuis l'accueil)
- `Alt+A` - Page Agir (depuis l'accueil)
- `Tab` - Navigation entre liens
- `Enter` - Suivre un lien

## Test Terminal

```bash
# Installer w3m (macOS)
brew install w3m

# Tester
w3m index.html
```

## Analyse de Performance

```bash
# Taille totale
ls -lh index.html

# Validation HTML
curl -H "Content-Type: text/html; charset=utf-8" \
  --data-binary @index.html \
  https://validator.w3.org/nu/?out=gnu

# Test accessibilité (avec pa11y)
npx pa11y index.html
```

## Technologies

- HTML5 sémantique
- CSS3 inline (gradients, media queries)
- Zéro JavaScript
- Zéro framework
- Zéro dépendance externe



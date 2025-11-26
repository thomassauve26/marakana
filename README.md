# MaraKana Latin Jazz - Site Officiel

Site web officiel du groupe de Latin Jazz MaraKana, basé à Bordeaux.

## 🎵 Présentation

MaraKana est un sextet de Latin Jazz proposant un répertoire varié mêlant jazz standards, bossa nova, samba et musiques caribéennes. Le groupe se produit pour des concerts, mariages, festivals et événements d'entreprise en Nouvelle-Aquitaine et partout en France.

## 🛠️ Technologies Utilisées

- **HTML5** - Structure sémantique
- **Tailwind CSS** (via CDN) - Framework CSS utility-first
- **Lucide Icons** (via CDN) - Bibliothèque d'icônes
- **Vanilla JavaScript** - Interactions personnalisées
- **un-static Forms** - Gestion des formulaires de contact

## 📁 Structure du Projet

```
V2/
├── assets/
│   ├── images/
│   │   ├── musicians/      # Photos des 6 musiciens
│   │   ├── gallery/        # Photos de galerie
│   │   └── hero/           # Image principale (Groupe Hero.jpg)
│   ├── videos/             # Vidéos (1080p et 4K)
│   └── favicons/           # Favicons et apple-touch-icon
├── docs/                   # Documentation
├── index.html              # Page principale
├── videos.html             # Page vidéos & audios
├── README.md               # Ce fichier
├── CLAUDE.md               # Guide pour Claude Code
├── .gitignore              # Fichiers ignorés par Git
└── CNAME                   # Configuration domaine personnalisé
```

## 🚀 Développement Local

Aucun build process n'est nécessaire. Il suffit d'ouvrir le fichier HTML dans un navigateur :

```bash
# Cloner le repository
git clone [URL_DU_REPO]

# Se placer dans le dossier
cd V2

# Ouvrir dans le navigateur
open index.html
```

Ou utiliser un serveur local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (http-server)
npx http-server

# Ouvrir http://localhost:8000
```

## 📝 Fonctionnalités

### Page Principale (index.html)
- Section héro avec image principale
- Présentation du groupe
- Grille de 6 musiciens avec effets hover
- Vidéo studio intégrée
- Répertoire musical (3 colonnes)
- Agenda des concerts
- Galerie photos avec lightbox
- Formulaire de contact fonctionnel

### Page Vidéos (videos.html)
- 6 vidéos du groupe (1080p et 4K)
- Section streaming (YouTube, Facebook)
- Design cohérent avec la page principale

### Optimisations
- **Images compressées** : Réduction de ~60% du poids
- **Formulaire de contact** : Intégration un-static.com
- **Responsive design** : Mobile-first
- **Animations scroll** : IntersectionObserver API
- **SEO optimisé** : Meta tags, JSON-LD, sitemap

## 📧 Formulaire de Contact

Le formulaire utilise [un-static.com](https://un-static.com) pour gérer les soumissions :
- Endpoint : `https://forms.un-static.com/forms/b6c7ab08a3a87699e47448de8cdfd419cf249318`
- Email de destination : `thomassauve26@gmail.com`
- Redirection après envoi : `https://marakana-jazz.com`

## 🎨 Palette de Couleurs

```css
--beige: #F3F3F1    /* Fond principal */
--orange: #FF6600   /* Accent primaire */
--bleu: #0077BE     /* Accent secondaire */
--black: #000000    /* Header/footer/texte */
--white: #FFFFFF    /* Texte sur fond sombre */
```

## 🎭 Musiciens

1. **Bruno Sauvé** - Batterie (Fondateur)
2. **Olivier Lorang** - Basse
3. **Michaela Slavikova** - Flûte
4. **Jérôme Denner** - Trompette
5. **Nicolas Lancia** - Piano
6. **Patrick Leyrat** - Congas

## 🌐 Déploiement

Le site est déployé sur GitHub Pages :
- **URL** : https://marakana-jazz.com
- **Repository** : Ce dossier V2 a son propre repository Git
- **Branche** : `main` (déploiement automatique)

### Workflow de déploiement

```bash
# Faire les modifications
# Tester en local

# Commit
git add .
git commit -m "Description des modifications"

# Push (déploiement automatique)
git push origin main
```

## 📱 Compatibilité

- ✅ Chrome/Edge (dernières versions)
- ✅ Firefox (dernières versions)
- ✅ Safari (dernières versions)
- ✅ Mobile (iOS/Android)

## 🔧 Maintenance

### Ajouter une vidéo
1. Placer le fichier `.mp4` dans `assets/videos/`
2. Ajouter un bloc vidéo dans `videos.html`
3. Suivre la structure existante

### Modifier l'agenda
Éditer la section `#agenda` dans `index.html`

### Changer les images
1. Optimiser l'image (qualité 85%, format JPG)
2. Placer dans le bon dossier `assets/images/`
3. Mettre à jour le chemin dans le HTML

## 📄 Licence

© 2025 MaraKana Latin Jazz. Tous droits réservés.

## 📞 Contact

- **Email** : bruno.sauve@hotmail.fr
- **Téléphone** : 06.61.53.45.36
- **Facebook** : [MaraKana Latin Jazz](https://www.facebook.com/p/MaraKana-latin-jazz-61560077231411/)
- **YouTube** : [@brunosauve6155](https://www.youtube.com/@brunosauve6155)

---

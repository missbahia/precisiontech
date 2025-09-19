# Images et Vidéos - Guide d'Utilisation

## 📁 Structure des Dossiers

```
vbwebloock/
├── images/
│   └── gallery/
│       ├── usinage-cnc-1.jpg
│       ├── soudure-tig.jpg
│       ├── assemblage-mecanique.jpg
│       ├── prototype-innovation.jpg
│       ├── outillage-auto.jpg
│       └── piece-aeronautique.jpg
└── videos/
    └── promo-video.mp4
```

## 🖼️ Images de Galerie Générées

J'ai créé 6 images SVG de démonstration qui représentent différents aspects de l'usinage CNC :

### 1. **usinage-cnc-1.jpg**
- **Sujet** : Machine CNC en action
- **Éléments** : Broche, pièce usinée, copeaux, panneau de contrôle
- **Couleurs** : Bleu et gris métallique

### 2. **soudure-tig.jpg**
- **Sujet** : Soudure TIG professionnelle
- **Éléments** : Torche TIG, arc électrique, étincelles, pièces métalliques
- **Couleurs** : Bleu électrique sur fond sombre

### 3. **assemblage-mecanique.jpg**
- **Sujet** : Mécanismes et engrenages
- **Éléments** : Engrenages, boulons, structures de support
- **Couleurs** : Doré et gris métallique

### 4. **prototype-innovation.jpg**
- **Sujet** : Développement de prototypes
- **Éléments** : Plans CAD, spécifications techniques, certifications
- **Couleurs** : Vert et bleu avec grille technique

### 5. **outillage-auto.jpg**
- **Sujet** : Industrie automobile
- **Éléments** : Silhouette de voiture, chaîne de production, contrôle qualité
- **Couleurs** : Rouge automobile et gris industriel

### 6. **piece-aeronautique.jpg**
- **Sujet** : Composants aéronautiques
- **Éléments** : Avion, certifications, standards de qualité
- **Couleurs** : Bleu ciel et blanc

## 🎥 Vidéo Publicitaire

Le fichier `videos/promo-video.mp4` est actuellement un placeholder. Pour ajouter votre vraie vidéo :

1. **Remplacez le fichier** par votre vidéo MP4
2. **Formats recommandés** :
   - Format : MP4 (H.264)
   - Résolution : 1920x1080 ou 1280x720
   - Durée : 30-60 secondes
   - Taille : < 50MB pour un chargement rapide

3. **Ajoutez aussi une version WebM** pour une meilleure compatibilité :
   ```html
   <source src="videos/promo-video.webm" type="video/webm">
   ```

## 🔄 Remplacement des Images

### Pour remplacer par vos vraies images :

1. **Gardez les mêmes noms de fichiers** ou mettez à jour les chemins dans `index.html`
2. **Formats recommandés** : JPG, PNG, WebP
3. **Dimensions optimales** : 800x600px (ratio 4:3)
4. **Taille** : < 500KB par image pour de bonnes performances
5. **Optimisation** : Utilisez des outils comme TinyPNG pour compresser

### Exemple de remplacement :
```bash
# Remplacez simplement les fichiers existants
cp votre-image-usinage.jpg images/gallery/usinage-cnc-1.jpg
cp votre-image-soudure.jpg images/gallery/soudure-tig.jpg
# etc...
```

## 📱 Optimisation Mobile

Les images sont configurées avec :
- `loading="lazy"` pour un chargement différé
- `aspect-ratio: 4/3` pour maintenir les proportions
- Responsive design automatique

## 🎨 Personnalisation

### Pour ajouter plus d'images :
1. Ajoutez vos images dans `images/gallery/`
2. Ajoutez une nouvelle `gallery-card` dans `index.html` :
```html
<div class="gallery-card">
    <div class="gallery-image">
        <img src="images/gallery/votre-nouvelle-image.jpg" alt="Description" loading="lazy">
        <div class="gallery-overlay">
            <h3>Titre de votre projet</h3>
            <p>Description courte</p>
        </div>
    </div>
</div>
```

## ✨ Galerie Simplifiée

La nouvelle galerie est **moderne et épurée** avec :
- ✅ Design simple et élégant
- ✅ Animations fluides au survol
- ✅ Responsive parfait
- ✅ Performance optimisée
- ✅ Facilité de maintenance

Plus besoin de lightbox complexe ou de filtres compliqués - la galerie se concentre sur l'essentiel : **montrer vos réalisations de manière professionnelle**.

## 🚀 Prochaines Étapes

1. **Remplacez les images SVG** par vos vraies photos de projets
2. **Ajoutez votre vidéo publicitaire** dans le dossier videos/
3. **Personnalisez les textes** dans les overlays de galerie
4. **Testez sur différents appareils** pour vérifier la responsivité

Le site est maintenant **prêt pour la production** avec une galerie moderne et performante ! 🎉

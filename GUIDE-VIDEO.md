# 🎬 Guide pour Ajouter Votre Vidéo MP4

## 📁 Comment Ajouter Votre Vidéo

### **Étape 1 : Préparer votre vidéo**
1. **Nommez votre fichier** : `promo-video.mp4`
2. **Placez-le dans** : `videos/promo-video.mp4`

### **Étape 2 : Spécifications Recommandées**
- **Format** : MP4 (H.264)
- **Résolution** : 1920x1080 (Full HD) ou 1280x720 (HD)
- **Durée** : 30 secondes à 2 minutes
- **Taille** : Maximum 50MB pour un chargement rapide
- **Ratio** : 16:9 (paysage)

### **Étape 3 : Copier votre vidéo**
```bash
# Méthode 1 : Copier directement
copy "votre-video.mp4" "videos/promo-video.mp4"

# Méthode 2 : Glisser-déposer
# Glissez votre fichier dans le dossier videos/ et renommez-le
```

## 🔧 Structure Actuelle

Le site est configuré pour :
- **Chemin vidéo** : `videos/promo-video.mp4`
- **Format alternatif** : `videos/promo-video.webm` (optionnel)
- **Contrôles** : Lecture automatique au clic sur le bouton play
- **Responsive** : S'adapte à tous les écrans

## ✅ Test de Fonctionnement

### **Après avoir ajouté votre vidéo :**
1. **Actualisez la page** dans le navigateur
2. **Cliquez sur le bouton play** ▶️
3. **Votre vidéo devrait se lancer** automatiquement
4. **À la fin**, retour automatique au placeholder

### **En cas de problème :**
- Vérifiez que le fichier s'appelle exactement `promo-video.mp4`
- Vérifiez qu'il est dans le dossier `videos/`
- Vérifiez que le format est bien MP4 (H.264)
- Ouvrez la console du navigateur (F12) pour voir les erreurs

## 🎯 Exemple de Contenu Vidéo

### **Idées pour votre vidéo d'usinage :**
- **Machine CNC en action** (vue d'ensemble)
- **Gros plan sur l'outil** qui usine
- **Pièces finies** de qualité
- **Équipe au travail** (optionnel)
- **Contrôle qualité** avec instruments de mesure

### **Structure suggérée :**
1. **0-5s** : Logo/titre "Precision Tech"
2. **5-20s** : Machine CNC en action
3. **20-35s** : Pièces usinées (différents angles)
4. **35-45s** : Contrôle qualité/précision
5. **45-50s** : Logo final + contact

## 🚀 Optimisation

### **Pour une meilleure performance :**
1. **Compressez votre vidéo** avec HandBrake ou similar
2. **Ajoutez une version WebM** pour une meilleure compatibilité :
   ```html
   <source src="videos/promo-video.webm" type="video/webm">
   ```
3. **Créez une image de prévisualisation** :
   ```html
   <video poster="images/video-preview.jpg">
   ```

## 📱 Responsive

La vidéo s'adapte automatiquement :
- **Desktop** : Taille optimale dans la grille
- **Tablet** : Ajustement automatique
- **Mobile** : Pleine largeur avec contrôles tactiles

## 🔍 Dépannage

### **Vidéo ne se charge pas :**
- Vérifiez le chemin : `videos/promo-video.mp4`
- Vérifiez les permissions du fichier
- Testez avec un autre fichier MP4

### **Vidéo se charge mais ne joue pas :**
- Vérifiez le codec (H.264 recommandé)
- Testez dans différents navigateurs
- Vérifiez la console pour les erreurs

### **Performance lente :**
- Réduisez la taille du fichier
- Baissez la résolution si nécessaire
- Utilisez un outil de compression

## 💡 Conseils Pro

1. **Ajoutez des sous-titres** si nécessaire
2. **Testez sur mobile** pour l'expérience utilisateur
3. **Gardez une copie de sauvegarde** de votre vidéo originale
4. **Mesurez les performances** de chargement

---

**Votre vidéo est maintenant prête à être intégrée ! 🎉**

Placez simplement votre fichier `promo-video.mp4` dans le dossier `videos/` et la magie opère !

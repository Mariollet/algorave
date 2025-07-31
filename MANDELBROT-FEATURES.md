# Nouveau Mandelbrot - Fonctionnalités

## 🎨 **UI Identique à Quantum Kaleidoscope**
- Panneau d'information glassmorphe (gauche)
- Panneau de contrôles glassmorphe (droite)  
- Bouton retour (bas gauche)
- Effets backdrop-filter et transparences

## 🔧 **Contrôles Spécifiques Mandelbrot**

### **Palettes de Couleurs**
- `Arc-en-ciel` - Spectre complet HSL
- `Feu` - Rouge/orange/jaune progressif
- `Océan` - Bleu/vert/cyan aquatique
- `Psychédélique` - Sinus multicolore (défaut)
- `Monochrome` - Niveaux de gris

### **Paramètres de Calcul**
- **Itérations max** (50-500) - Précision du calcul
- **Qualité** - Rapide/Normale/Haute (compromis vitesse/qualité)
- **Vitesse auto** (0.2-3.0) - Vitesse des transitions automatiques

### **Modes d'Exploration**
- **Manuel** - Clic pour zoomer (curseur crosshair)
- **Auto** - Exploration guidée avec 8 points d'intérêt
- **Aléatoire** - Saut vers position aléatoire
- **Reset** - Retour à la vue d'ensemble

## 🎯 **Points d'Intérêt Auto Mode**

1. **Vue d'ensemble** (-0.5, 0.0) - Zoom 1x
2. **Spirale principale** (-0.7269, 0.1889) - Zoom 100x  
3. **Mini-Mandelbrot** (-0.8, 0.156) - Zoom 200x
4. **Détails fins** (-0.16, 1.0407) - Zoom 400x
5. **Bulbe latéral** (-1.25066, 0.02012) - Zoom 600x
6. **Fractales complexes** (-0.235125, 0.827215) - Zoom 800x
7. **Spirales profondes** (-0.7463, 0.1102) - Zoom 1000x
8. **Infini fractal** (-0.16070135, 1.0375665) - Zoom 1500x

## ⚡ **Optimisations Performance**

### **Qualité Adaptative**
- **Rapide** : Pixels 3x3 (exploration rapide)
- **Normale** : Pixels 2x2 (équilibre optimal)  
- **Haute** : Pixel par pixel (détails maximaux)

### **Animations Fluides**
- Interpolation ease-out cubic
- Transitions de 4 secondes / vitesse auto
- Pause de 2 secondes entre points auto

## 🎮 **Interactions**

- **Clic** : Zoomer sur position (mode manuel uniquement)
- **Mode Auto** : Exploration automatique guidée
- **Boutons** : Effets hover avec gradients animés
- **Sliders** : Mise à jour temps réel

## 🎵 **Design Cohérent**
Même style glassmorphe que Quantum Kaleidoscope :
- Fond rgba(255,255,255,0.06)
- Bordures rgba(255,255,255,0.12) 
- Backdrop-filter blur(20px)
- Gradients rose/bleu pour boutons
- Police Orbitron/JetBrains Mono

# 🍽️ OhMyFood - Projet OpenClassrooms

![OpenClassrooms](https://img.shields.io/badge/OpenClassrooms-Project-FF6B6B?style=for-the-badge&logo=openclassrooms&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Mobile First](https://img.shields.io/badge/Mobile%20First-FF79DA?style=for-the-badge&logo=mobile&logoColor=white)

## 📚 Contexte du Projet

**OhMyFood** est un projet de formation OpenClassrooms qui consiste à développer l'interface mobile-first d'une plateforme de réservation de repas en ligne. Ce projet permet d'apprendre les concepts fondamentaux du développement front-end moderne.

### 🎯 Objectifs Pédagogiques

Ce projet vise à développer les compétences suivantes :
- 🎨 **Mettre en œuvre** des effets CSS graphiques avancés
- 🎯 **Assurer** la cohérence graphique d'un site web
- 🧭 **Mettre en place** une structure de navigation pour un site web
- ⚙️ **Mettre en place** son environnement Front-End
- 📝 **Utiliser** un système de gestion de versions pour le suivi du projet

### 🚀 Compétences Développées

- **Mobile First** : Approche responsive design moderne
- **Animations CSS** : Enrichissement de l'expérience utilisateur
- **SASS** : Structuration et optimisation du CSS
- **Git & GitHub** : Gestion de version et collaboration
- **Intégration** : Transformation de maquettes en code fonctionnel

## 📋 Spécifications du Projet

### 🎯 Objectifs du Projet
Ce projet vous amène à travailler sur l'interface mobile-first du site d'une start-up. Vous implémenterez des animations CSS en utilisant SASS et versionnerez votre projet avec Git et GitHub.

### 📱 Approche Mobile First
- **Intégration** : Maquettes mobile et desktop fournies
- **Prototype** : Figma disponible pour référence
- **Ressources** : Images et textes fournis
- **Adaptatif** : Compréhension de l'importance des sites réactifs

### 🎨 Animations CSS
- **Expérience utilisateur** : Enrichissement de l'interface
- **Interactivité** : Navigation plus engageante
- **Vie de l'interface** : Animations qui donnent du dynamisme
- **Sans JavaScript** : Utilisation exclusive du CSS

### 🔧 Gestion de Version
- **Git** : Suivi des modifications du projet
- **GitHub** : Hébergement et collaboration
- **Commits** : Historique des changements
- **Déploiement** : Publication sur GitHub Pages

## ✨ Fonctionnalités Implémentées

### 🏠 Page d'Accueil
- **Localisation** : Affichage de la position géographique
- **Présentation** : Description claire du concept
- **Restaurants** : 4 cartes de restaurants gastronomiques
- **Fonctionnement** : Guide en 3 étapes

### 🍽️ Pages Restaurants
- **Menus détaillés** : Entrées, plats, desserts
- **Animations** : Apparition progressive des plats
- **Sélection** : Système de coche pour composer le menu
- **Design** : Interface moderne et intuitive

### 🎨 Animations & Effets
- **Loader** : Animation de chargement élégante
- **Hover** : Effets de survol sur tous les éléments interactifs
- **Transitions** : Animations fluides et naturelles
- **Responsive** : Adaptabilité parfaite sur tous les écrans

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique et accessible
- **CSS3** : Styles modernes avec Flexbox et Grid
- **SASS** : Préprocesseur CSS avec architecture modulaire
- **Mobile First** : Approche responsive design
- **Animations CSS** : Effets visuels sans JavaScript

## 📁 Structure du Projet

```
OhMyFood/
├── 📄 homepage.html          # Page d'accueil
├── 📁 restaurants/           # Pages des restaurants
│   ├── a-la-francaise.html
│   ├── la-note-enchantee.html
│   ├── la-palette-du-gout.html
│   └── le-delice-des-sens.html
├── 📁 assets/               # Ressources statiques
│   ├── 📁 css/              # Fichiers CSS compilés
│   └── 📁 images/           # Images et logos
├── 📁 sass/                 # Code source SASS
│   ├── 📁 base/             # Variables, reset, typographie
│   ├── 📁 components/       # Composants réutilisables
│   ├── 📁 layout/           # Mise en page générale
│   ├── 📁 pages/            # Styles spécifiques aux pages
│   └── 📁 utils/            # Mixins et utilitaires
└── 📄 README.md
```

## 🚀 Installation & Développement

### Prérequis
- Node.js (pour SASS)
- Un éditeur de code (VS Code recommandé)
- Navigateur web moderne

### Installation
```bash
# Cloner le repository
git clone https://github.com/Moonyelit/OhMyFood---OpenClassRoom---FOUGEROUSE-Elodie

# Se déplacer dans le dossier
cd OhMyFood---OpenClassRoom---FOUGEROUSE-Elodie

# Installer SASS (si pas déjà installé)
npm install -g sass
```

### Compilation SASS
```bash
# Compilation en mode développement
sass sass/main.scss assets/css/main.css

# Compilation en mode production (minifié)
sass sass/main.scss assets/css/main.css --style=compressed

# Compilation avec surveillance des changements
sass sass/main.scss assets/css/main.css --watch
```

## 🎨 Charte Graphique

### Couleurs
- **Primaire** : `#9356DC` (Violet)
- **Secondaire** : `#FF79DA` (Rose)
- **Tertiaire** : `#99E2D0` (Vert menthe)

### Typographie
- **Titres** : Shrikhand (cursive)
- **Corps** : Roboto (sans-serif)

### Breakpoints
- **Mobile** : < 768px
- **Tablet** : 768px - 1023px
- **Desktop** : 1024px+

## 📱 Responsive Design

Le site utilise une approche **Mobile First** avec des breakpoints optimisés :

```scss
// Mobile (base)
.element { /* styles mobile */ }

// Tablet
@include tablet { /* adaptations tablette */ }

// Desktop
@include desktop { /* optimisations desktop */ }
```

## 🎯 Fonctionnalités Techniques

### Animations CSS
- **Loader** : Animation de chargement avec fadeOut
- **Boutons** : Effets de survol avec éclaircissement
- **Cartes** : Transformations et ombres dynamiques
- **Plats** : Apparition progressive avec délais

### Accessibilité
- **HTML sémantique** : Structure logique et accessible
- **Alt text** : Descriptions des images
- **Aria-labels** : Labels pour les éléments interactifs
- **Navigation** : Structure claire et intuitive



## 📋 Checklist de Validation

- ✅ **HTML** : Validation W3C sans erreurs
- ✅ **CSS** : Validation W3C sans erreurs
- ✅ **Responsive** : Testé sur mobile, tablet, desktop
- ✅ **Animations** : Effets fluides et naturels
- ✅ **Accessibilité** : Navigation claire et intuitive
- ✅ **Performance** : Chargement rapide et optimisé

## 🎓 Contexte de Formation

### 📚 Parcours OpenClassrooms
Ce projet fait partie du parcours **"Développeur d'application JavaScript React"** d'OpenClassrooms.

### 🎯 Compétences Professionnelles
La capacité à créer des interfaces web mobile-first est de plus en plus demandée dans le développement web moderne. L'intégration d'animations CSS améliore non seulement l'aspect visuel du site, mais aussi l'expérience utilisateur. La maîtrise de SASS pour structurer et optimiser le CSS est une compétence précieuse, tout comme la capacité à utiliser Git et GitHub pour la gestion de version et la collaboration sur des projets.

### 📋 Checklist de Validation
- ✅ **HTML** : Validation W3C sans erreurs
- ✅ **CSS** : Validation W3C sans erreurs  
- ✅ **Responsive** : Testé sur mobile, tablet, desktop
- ✅ **Animations** : Effets fluides et naturels
- ✅ **Accessibilité** : Navigation claire et intuitive
- ✅ **Performance** : Chargement rapide et optimisé
- ✅ **Git** : Commits réguliers et messages clairs
- ✅ **GitHub** : Repository bien organisé et documenté

## 👨‍💻 Auteur

**Elodie FOUGEROUSE** - Étudiante OpenClassrooms
- **Parcours** : Développeur d'application JavaScript React
- **Projet** : P3 - Dynamisez une page web avec des animations CSS
- **Année** : 2025

---

<div align="center">
  <p>Fait avec ❤️ et beaucoup de ☕</p>
  <p>© 2024 OhMyFood - Tous droits réservés - FOUGEROUSE Élodie</p>
</div>
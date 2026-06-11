# 🍽️ ohmyfood

Une plateforme de réservation de restaurants moderne et intuitive qui permet aux utilisateurs de découvrir des restaurants d'exception et de réserver leurs menus préférés.

![ohmyfood](https://img.shields.io/badge/status-active-brightgreen)
![HTML](https://img.shields.io/badge/HTML-E34C26?logo=html5&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-CC6699?logo=sass&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-blue)

## 📋 Table des matières

- [Présentation](#présentation)
- [Fonctionnalités](#fonctionnalités)
- [Technologies](#technologies)
- [Structure du projet](#structure-du-projet)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Restaurants disponibles](#restaurants-disponibles)
- [Design responsif](#design-responsif)
- [Contribution](#contribution)
- [Licence](#licence)

## 🎯 Présentation

**ohmyfood** est une application web de découverte et de réservation de restaurants à Paris. L'objectif est de permettre aux utilisateurs de consulter les menus des restaurants partenaires, de composer leur commande, et de réserver facilement une table.

Le site propose une expérience utilisateur fluide avec un design élégant et moderne, optimisé pour tous les appareils (mobile, tablette, desktop).

### Point de localisation
📍 **Paris, Belleville** - Base d'opération pour tous les restaurants partenaires

## ✨ Fonctionnalités

### 🌐 Page d'accueil
- **En-tête** avec logo ohmyfood et localisation
- **Section héros** avec appel à l'action pour explorer les restaurants
- **Section "Fonctionnement"** expliquant les 3 étapes simples :
  1. 📱 Choisissez un restaurant
  2. 📋 Composez votre menu
  3. 🍽️ Dégustez au restaurant
- **Section restaurants** avec cartes affichant :
  - Image du restaurant
  - Nom du restaurant
  - Localisation
  - Badge "Nouveau" pour les nouveaux restaurants
  - Bouton cœur pour mettre en favori (animation de remplissage)
- **Pied de page** avec liens de contact et d'information

### 💫 Animations et interactivité
- **Loader** qui s'affiche au chargement du site
- **Animations au survol** des cartes de restaurants
- **Cœurs interactifs** pour marquer les restaurants en favoris
- **Effets visuels** fluides et modernes

### 📱 Pages restaurants
- Pages détaillées pour chaque restaurant (À développer)
  - La palette du goût
  - La note enchantée
  - À la française
  - Le délice des sens

### ♿ Accessibilité
- Navigation sémantique et lisible
- Icons Font Awesome pour meilleure accessibilité
- Textes alternatifs pour les images

## 🛠️ Technologies

### Front-end
- **HTML5** : Structure sémantique de l'application
- **SASS/SCSS** : Préprocesseur CSS pour stylisation modulaire
- **CSS3** : Animations, flexbox, grid, médias queries
- **JavaScript** : Interactivité (loader, animations)

### Ressources externes
- **Font Awesome 6.2.1** : Bibliothèque d'icônes
- **Google Fonts** :
  - Montserrat (polices variées)
  - Roboto (polices variées)
  - Shrikhand (polices décoratives)

## 📁 Structure du projet

```
ohmyfood/
├── index.html                           # Page d'accueil principale
├── README.md                            # Documentation du projet
├── README.txt                           # Fichier original
├── assets/
│   ├── css/
│   │   └── style.css                   # Styles compilés à partir du SASS
│   └── images/
│       └── restaurants/
│           ├── logo/
│           │   └── ohmyfood.png        # Logo principal
│           └── photos/
│               ├── jay-wennington-...jpg      # La palette du goût
│               ├── stil-u2Lp8tXIcjw-...png   # La note enchantée
│               ├── toa-heftiba-...jpg        # À la française
│               └── louis-hansel-...jpg       # Le délice des sens
├── pages-restau/                        # Pages détaillées des restaurants
│   ├── La-palette-du-goût.html
│   ├── la-note-enchantée.html
│   ├── a-la-française.html
│   └── Le-délice-des-sens.html
├── sass/                                # Fichiers SASS source
│   ├── _variables.scss                 # Variables CSS
│   ├── _mixins.scss                    # Mixins réutilisables
│   ├── _base.scss                      # Styles de base
│   ├── _header.scss                    # Styles de l'en-tête
│   ├── _footer.scss                    # Styles du pied de page
│   ├── _cards.scss                     # Styles des cartes
│   ├── _animations.scss                # Animations CSS
│   └── style.scss                      # Fichier principal SASS
└── .vscode/                             # Configuration VS Code
```

## 🚀 Installation

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- (Optionnel) Éditeur de code pour modifier le projet
- (Optionnel) Node.js et Sass pour compiler les SCSS

### Étapes d'installation

1. **Cloner le repository**
   ```bash
   git clone https://github.com/Justhiraga/ohmyfood.git
   cd ohmyfood
   ```

2. **Ouvrir le site localement**
   - Double-cliquez sur `index.html` dans votre explorateur de fichiers, OU
   - Utilisez un serveur local (Live Server sur VS Code, ou Python)
   
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Python 2
   python -m SimpleHTTPServer 8000
   
   # Avec Node.js et http-server
   npx http-server
   ```

3. **Ouvrir dans le navigateur**
   - Accédez à `http://localhost:8000` (ou le port indiqué)

### Compilation SASS (optionnel)

Pour compiler les fichiers SASS vers CSS :

```bash
# Installation de Sass (si non installé)
npm install -g sass

# Compiler les fichiers
sass sass/style.scss assets/css/style.css

# Ou regarder les changements en temps réel
sass --watch sass:assets/css
```

## 💻 Utilisation

### Pour les utilisateurs
1. Ouvrez le site dans votre navigateur
2. Explorez les restaurants disponibles sur la page d'accueil
3. Cliquez sur un restaurant pour voir son menu détaillé
4. Marquez vos restaurants préférés en cliquant sur le cœur
5. Composez votre commande et réservez

### Pour les développeurs
- Modifiez les fichiers HTML pour le contenu
- Éditez les fichiers SASS pour la stylisation
- Les changements SASS doivent être compilés en CSS
- Testez sur différentes résolutions d'écran

## 🏪 Restaurants disponibles

| Restaurant | Localisation | Statut |
|------------|-------------|--------|
| **La palette du goût** | Ménilmontant | 🆕 Nouveau |
| **La note enchantée** | Charonne | 🆕 Nouveau |
| **À la française** | Cité Rouge | Établi |
| **Le délice des sens** | Folie-Méricourt | Établi |

## 📱 Design responsif

Le site est entièrement responsive et optimisé pour :

- 📱 **Mobile** : < 768px
  - Navigation adaptée
  - Images optimisées
  - Touchers tactiles
  
- 📱 **Tablette** : 768px - 1024px
  - Layout flexible
  - Images HD
  
- 🖥️ **Desktop** : > 1024px
  - Expérience complète
  - Animations fluides
  - Grille optimale

## 🎨 Palette de couleurs

```css
Primary: #9356DC (Violet)
Secondary: #FF6B6B (Rose/Rouge)
Tertiary: #99E2D0 (Vert)
Background: #F7F7F7 (Gris clair)
Text: #353535 (Gris foncé)
```

## 🤝 Contribution

Les contributions sont bienvenues ! Pour contribuer :

1. Forkez le repository
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Poussez vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

### Domaines d'amélioration
- [ ] Développer les pages détaillées des restaurants
- [ ] Ajouter les fonctionnalités de panier et commande
- [ ] Intégrer une base de données pour les menus
- [ ] Système d'authentification utilisateur
- [ ] Améliorer les animations
- [ ] Optimisation de la performance

## 📝 Licence

Ce projet est sous licence [MIT](LICENSE) - voir le fichier LICENSE pour plus de détails.

## 👨‍💻 Auteur

**Justhiraga** - [Profil GitHub](https://github.com/Justhiraga)

- 📧 Email : (À ajouter)
- 🐙 GitHub : [@Justhiraga](https://github.com/Justhiraga)

## 📞 Support

Pour les questions ou problèmes :
- Ouvrez une [Issue](https://github.com/Justhiraga/ohmyfood/issues)
- Consultez les [Discussions](https://github.com/Justhiraga/ohmyfood/discussions)

## 🔗 Ressources utiles

- [HTML5 Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3 Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Sass Documentation](https://sass-lang.com/documentation)
- [Font Awesome Icons](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

---

<div align="center">

**Fait avec ❤️ par Justhiraga**

[⬆ Retour au début](#-ohmyfood)

</div>

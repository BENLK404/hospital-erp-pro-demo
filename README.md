# 🏥 ERP Hospital Pro - Système Ultra-Moderne

## ✨ Fonctionnalités Avancées

### 🎨 Interface Moderne
- **Design Glassmorphism** avec effets de transparence
- **Animations Framer Motion** fluides et professionnelles
- **Mode Sombre/Clair** avec transition douce
- **Multi-langues** (Français/Anglais) avec i18next
- **Responsive Design** optimisé pour tous les appareils
- **Sidebar Rétractable** avec animations

### 📊 Modules Complets
1. **Dashboard** - Statistiques en temps réel avec graphiques
2. **Patients** - Gestion complète des dossiers
3. **Rendez-vous** - Calendrier et planification
4. **Laboratoire** ⭐ - Analyses et résultats
5. **Radiologie** ⭐ - Imagerie médicale
6. **Pharmacie** ⭐ - Ordonnances et délivrance
7. **Inventaire** - Stocks et alertes
8. **Facturation** - Gestion financière
9. **Personnel** ⭐ - Gestion des employés
10. **Rapports** ⭐ - Statistiques avancées

### 🚀 Technologies Ultra-Modernes
- **React 18** + **Vite** (Build ultra-rapide)
- **Tailwind CSS** (Design system personnalisé)
- **Framer Motion** (Animations professionnelles)
- **Zustand** (State management léger)
- **React Hook Form** + **Zod** (Validation)
- **Recharts** (Graphiques interactifs)
- **Lucide + Tabler Icons** (3000+ icônes)
- **React Hot Toast** (Notifications élégantes)

## 🎯 Installation

```bash
# Exécuter le setup
node setup.js

# Démarrer l'application
cd hospital-erp-pro
npm run dev
```# 🏥 ERP Hospital Pro - Système Ultra-Moderne

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![React](https://img.shields.io/badge/react-18.2.0-%2361DAFB.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Build](https://img.shields.io/badge/build-passing-success.svg)

## ✨ Fonctionnalités Avancées

### 🎨 Interface Moderne Premium
- **Design Glassmorphism** avec effets de transparence et flous
- **Animations Framer Motion** fluides et professionnelles
- **Mode Sombre/Clair** avec transition douce et persistance
- **Multi-langues** (Français/Anglais) avec i18next intégré
- **Responsive Design** optimisé pour tous les appareils
- **Sidebar Rétractable** avec animations et états persistants
- **Thèmes personnalisables** avec système de couleurs étendu

### 📊 Modules Complets Professionnels

| Module | Statut | Fonctionnalités |
|--------|--------|----------------|
| **📊 Dashboard** | ✅ | Statistiques temps réel, KPIs, graphiques interactifs |
| **👥 Patients** | ✅ | Dossiers médicaux complets, historique, documents |
| **📅 Rendez-vous** | ✅ | Calendrier interactif, rappels, planification |
| **🧪 Laboratoire** ⭐ | 🚧 | Analyses, résultats, intégration instruments |
| **📷 Radiologie** ⭐ | 🚧 | Imagerie médicale, DICOM, rapports |
| **💊 Pharmacie** ⭐ | 🚧 | Ordonnances, stock, interactions médicamenteuses |
| **📦 Inventaire** | ✅ | Gestion stocks, alertes, fournisseurs |
| **💰 Facturation** | ✅ | Facturation, assurances, rapports financiers |
| **👨‍💼 Personnel** ⭐ | 🚧 | Gestion employés, plannings, compétences |
| **📈 Rapports** ⭐ | 🚧 | Statistiques avancées, exports, analytics |

### 🚀 Stack Technologique Ultra-Moderne

- **⚛️ React 18** + **Vite** - Build ultra-rapide et optimisé
- **🎨 Tailwind CSS** - Design system personnalisable
- **✨ Framer Motion** - Animations professionnelles
- **🐻 Zustand** - State management léger et performant
- **📝 React Hook Form** + **Zod** - Validation robuste
- **📊 Recharts** - Graphiques interactifs et responsives
- **🎯 Lucide + Tabler Icons** - 3000+ icônes modernes
- **🔥 React Hot Toast** - Notifications élégantes
- **🌐 i18next** - Internationalisation complète

## 🚀 Installation et Démarrage

### Prérequis
- Node.js 18+ 
- npm ou yarn
- Git

### Installation

```bash
# Cloner le repository
git clone https://github.com/votre-org/hospital-erp-pro.git
cd hospital-erp-pro

# Installer les dépendances
npm install

# Démarrer en mode développement
npm run dev

# Ou construire pour la production
npm run build
npm run preview
```

### 📦 Scripts Disponibles

```bash
npm run dev          # Démarre le serveur de développement
npm run build        # Construction pour la production
npm run preview      # Prévisualisation de la build
npm run lint         # Vérification du code
npm run type-check   # Vérification TypeScript
```

## 🌐 Accès et Configuration

### Environnements

| Environnement | URL | Description |
|---------------|-----|-------------|
| **Development** | http://localhost:3000 | Mode développement avec hot reload |
| **Production** | À configurer | Build optimisée pour la production |

### Configuration

Créez un fichier `.env` à la racine :

```env
VITE_APP_NAME="ERP Hospital Pro"
VITE_API_URL=http://localhost:8000/api
VITE_APP_VERSION=1.0.0
VITE_I18NEXT_DEBUG=false
```

## 🎨 Personnalisation

### Thèmes et Couleurs

Modifiez `tailwind.config.js` pour personnaliser le design :

```js
theme: {
  extend: {
    colors: {
      primary: {
        50: '#f0f9ff',
        500: '#0ea5e9',
        600: '#0284c7',
        700: '#0369a1',
      },
      // Ajoutez vos couleurs personnalisées
    }
  }
}
```

### Langues et Internationalisation

Ajoutez des traductions dans `src/locales/` :

```json
// src/locales/fr.json
{
  "dashboard": {
    "title": "Tableau de Bord",
    "welcome": "Bienvenue, {{name}}!"
  }
}
```

## 📱 Responsive Design

Le système est optimisé pour :

- **📱 Mobile** (320px+) : Navigation compacte, gestures
- **💻 Tablette** (768px+) : Layout adaptatif, sidebar rétractable
- **🖥️ Desktop** (1024px+) : Interface complète, multi-colonnes

## 🔐 Sécurité et Authentification

### Fonctionnalités de Sécurité
- **JWT Authentication** avec refresh tokens
- **Gestion des Rôles** (Admin, Médecin, Infirmier, etc.)
- **Protection des Routes** avec guards
- **Validation des Formulaires** avec Zod
- **Sanitization des données** XSS protection

### Configuration Auth

```js
// Exemple de configuration auth
const authConfig = {
  tokenRefreshInterval: 15 * 60 * 1000, // 15 minutes
  storage: localStorage,
  routes: {
    login: '/auth/login',
    logout: '/auth/logout',
    callback: '/auth/callback'
  }
};
```

## 📊 Performance et Optimisation

### Metrics
- ⚡ First Contentful Paint < 1.5s
- 🎯 Largest Contentful Paint < 2.5s
- 📦 Bundle size < 500KB gzipped
- 🔥 Hot reload < 100ms

### Optimisations
- **Code Splitting** automatique avec React.lazy
- **Tree Shaking** pour réduire la taille du bundle
- **Image Optimization** avec compression WebP
- **Caching Strategy** optimisée

## 🧪 Tests et Qualité

```bash
# Exécuter les tests
npm test

# Tests avec couverture
npm run test:coverage

# Linting
npm run lint

# Vérification types
npm run type-check
```

## 📦 Déploiement

### Docker (Recommandé)

```dockerfile
FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "run", "preview"]
```

### Platforms Supportées

- **Vercel** (Recommandé)
- **Netlify**
- **AWS Amplify**
- **Docker/ Kubernetes**

## 🤝 Contribution

### Processus de Contribution

1. Fork le projet
2. Créez une branche feature (`git checkout -b feature/AmazingFeature`)
3. Commit vos changes (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

### Standards de Code

- **ESLint** + **Prettier** configurés
- **Conventional Commits**
- **Tests requis** pour nouvelles fonctionnalités
- **Documentation** obligatoire

## 📄 Licence

Distribué sous licence MIT. Voir `LICENSE` pour plus d'informations.

## 🆘 Support

### Documentation
- 📚 [Guide d'utilisation](docs/guide.md)
- 🐛 [Signaler un bug](https://github.com/votre-org/hospital-erp-pro/issues)
- 💡 [Suggérer une fonctionnalité](https://github.com/votre-org/hospital-erp-pro/issues)

### Contact
- 📧 Email : support@hospital-erp-pro.com
- 💬 Discord : [Rejoindre le serveur](https://discord.gg/example)
- 🐦 Twitter : [@HospitalERP](https://twitter.com/HospitalERP)

---

**Développé avec ❤️ et les technologies les plus modernes pour révolutionner la gestion hospitalière.**
